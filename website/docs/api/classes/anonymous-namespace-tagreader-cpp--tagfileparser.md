---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `TagFileParser` Class Reference

<p>Tag file parser. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous_namespace{tagreader.cpp}::TagFileParser { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">State { <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85">...</a> }</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43f4ea41f01f767ade7898b8d69d0f43">TagFileParser</a> (const char *tagName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a662591474cf5ed7adce79a42d49736af">setDocumentLocator</a> (const XMLLocator *locator)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a071b83231ad06ddf1f4192c2ee682839">startDocument</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a487b3d40047a75c0612f66ab78f61d96">startElement</a> (const QCString &amp;name, const XMLHandlers::Attributes &amp;attrib)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e01aed32d5dbf43b922e4152b65b54f">endElement</a> (const QCString &amp;name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98c5a0d5ae75e20939baaba36ecaf2e3">characters</a> (const QCString &amp;ch)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bd1e95f8dd3062e45ad9c14ef6ff3bc">error</a> (const QCString &amp;fileName, int lineNr, const QCString &amp;msg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafd3846f78cc76b992152366c99f7d74">dump</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a2a4b0accaef9069229937226e60b10">buildLists</a> (const std::shared_ptr&lt; Entry &gt; &amp;root)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbafb9f58aa69f3ea191211d77ffccae">addIncludes</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab17fadda7f7d30dce3d68f186aaed55d">startCompound</a> (const XMLHandlers::Attributes &amp;attrib)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e0857519c95a2ab4f2649588f52b244">endCompound</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4db9510d59066b8d7f847bda9fb9574">startMember</a> (const XMLHandlers::Attributes &amp;attrib)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afce64693b86203b0106f25a6697a8076">endMember</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc3a2293108d7a644b0c57ad06f29c11">startEnumValue</a> (const XMLHandlers::Attributes &amp;attrib)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06a8a71d6e6d9f8e93cee750e2faa0ef">endEnumValue</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b2c9b8ab174e898f87b90803529766c">endDocAnchor</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0af5855a848b20e3136d941d7840732">endClass</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88c616e8f2d519406f88102cf9913811">endConcept</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0c63ea4440394d9c1089cc804f6b3cb">endModule</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f364b44aa47f45ead81e1892359c3ee">endNamespace</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34e5a973da1491d711704a2ee6ee8ae0">endFile</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40b954bb215265f9d331f673102f8e11">endPage</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fd29da85de1ed3faf625ee0d27122ae">endSubpage</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af120fd7d4ed4df2d800e4a531152728d">endDir</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f27e5fd0bb44175b3aead4641fab718">startStringValue</a> (const XMLHandlers::Attributes &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3646ed3d0fe02e98b159d52ff914f305">startDocAnchor</a> (const XMLHandlers::Attributes &amp;attrib)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f6885619a9e437468650af93b8f05f3">endType</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5d579a5b02bb8153e8be2ffe25d2b90">endName</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6927f64d6b3e45878b5102852e1e2fac">startBase</a> (const XMLHandlers::Attributes &amp;attrib)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ac7de66e90ffbf93cd637c67c7cc76c">endBase</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a347e401a684f17633b5d23c1010b3f28">startIncludes</a> (const XMLHandlers::Attributes &amp;attrib)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18f64ce17ad437b8675f4bd7b9f8a974">endIncludes</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a942847def781fe793b9bf3b1a7179c3f">endTemplateArg</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb8e913e38db3f6aa9c1bbb9a641a17f">endFilename</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8020f9f5e883fd98854ac72e4e6e776d">endPath</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42aff7a35ce87a4df59d4a05f374f54e">endAnchor</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab27d1e74556a11f12e2d6a3b0dfa1225">endClangId</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a898f929ad250f095d46ce638e8fce78a">endAnchorFile</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a005718bfd790617c0cf8b3ab0c86a6c3">endArglist</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6e06a88bac03298d1b7b1d960786089">endTitle</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab01b451a3fc33322e98c40bd5cca5878">endSubgroup</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89373019d59ca8a862b03c6b665daa48">startIgnoreElement</a> (const XMLHandlers::Attributes &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06ded03287ca59344a1d300d78789abe">endIgnoreElement</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5dd16fd497d034a55fdca37a3c17804">buildMemberList</a> (const std::shared_ptr&lt; Entry &gt; &amp;ce, const std::vector&lt; TagMemberInfo &gt; &amp;members)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04e4220513820012d31302361cf4f24d">addDocAnchors</a> (const std::shared_ptr&lt; Entry &gt; &amp;e, const std::vector&lt; TagAnchorInfo &gt; &amp;l)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9daed7f8f5651e85aaa17885e61134c">buildClassEntry</a> (const std::shared_ptr&lt; Entry &gt; &amp;root, const TagClassInfo *tci)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5bfa36a1a89d2e6f35ac34fc6b0af3d">buildClassTree</a> (const std::shared_ptr&lt; Entry &gt; &amp;root, const ClassNode &amp;node)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant">TagCompoundVariant</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac75f982d3520a85cd31cabafbbd60dc7">m_tagFileCompounds</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant">TagCompoundVariant</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagmemberinfo">TagMemberInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagenumvalueinfo">TagEnumValueInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa13860af0001daf87f69281389f3c101">m_curEnumValue</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagincludeinfo">TagIncludeInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abac57def474d6cfc6844a2c62c81b23e">m_curIncludes</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19ed33b56774430bad0811dbb24aa38d">m_fileName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75e30c8c85ae1460b55b1585e9386693">m_title</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85">State</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a> = <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ac73a5e6827c3a9bb6731a484f29a1224">Invalid</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::stack&lt; <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85">State</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada7baee04d5b524d2d3b2c4d2207cf6d">m_stateStack</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/xmllocator">XMLLocator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a560587cbf60c107e9bae7e205fd6ef50">m_locator</a> = nullptr</td>
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

<p>Tag file parser.</p>


<p>Reads an XML-structured tagfile and builds up the structure in memory. The method <a href="#a9a2a4b0accaef9069229937226e60b10">buildLists()</a> is used to transfer/translate the structures to the doxygen engine.</p>


<p>Definition at line 328 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### State {#a7a2a20ef2fb10c1c35e093f0c3f41f85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous_namespace{tagreader.cpp}::TagFileParser::State </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Invalid<a id="a7a2a20ef2fb10c1c35e093f0c3f41f85ac73a5e6827c3a9bb6731a484f29a1224"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InClass<a id="a7a2a20ef2fb10c1c35e093f0c3f41f85a93b6ce3a1981ac7eec5187fe01f13f88"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InConcept<a id="a7a2a20ef2fb10c1c35e093f0c3f41f85ab50fef501e869e3a88c64c5dd7b49d0b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InFile<a id="a7a2a20ef2fb10c1c35e093f0c3f41f85a8153ea8cb5da0e11193e8780e0235ecd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InNamespace<a id="a7a2a20ef2fb10c1c35e093f0c3f41f85aaa2eff2017752b6a0d1a8b902f99b53d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InGroup<a id="a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InPage<a id="a7a2a20ef2fb10c1c35e093f0c3f41f85ac57db6ff719aec7e364b0823d5c231db"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InMember<a id="a7a2a20ef2fb10c1c35e093f0c3f41f85a463a8e3a1d39b8771600448eff1ab94f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InEnumValue<a id="a7a2a20ef2fb10c1c35e093f0c3f41f85af0bd1defdb45363bbae05d446baa8ba8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InPackage<a id="a7a2a20ef2fb10c1c35e093f0c3f41f85a10248ae7318932ab6199589d50836c37"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InDir<a id="a7a2a20ef2fb10c1c35e093f0c3f41f85acf8144d7c837a76fe6497c8158c6b973"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InModule<a id="a7a2a20ef2fb10c1c35e093f0c3f41f85a31219fa12b60084e1f85db1eeffe4697"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InTempArgList<a id="a7a2a20ef2fb10c1c35e093f0c3f41f85aeff175cadd93a4748a132b8020e4022e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 989 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ac73a5e6827c3a9bb6731a484f29a1224">989</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">enum</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85">State</a> { <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ac73a5e6827c3a9bb6731a484f29a1224">Invalid</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a93b6ce3a1981ac7eec5187fe01f13f88">990</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a93b6ce3a1981ac7eec5187fe01f13f88">InClass</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ab50fef501e869e3a88c64c5dd7b49d0b">991</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ab50fef501e869e3a88c64c5dd7b49d0b">InConcept</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a8153ea8cb5da0e11193e8780e0235ecd">992</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a8153ea8cb5da0e11193e8780e0235ecd">InFile</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85aaa2eff2017752b6a0d1a8b902f99b53d">993</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85aaa2eff2017752b6a0d1a8b902f99b53d">InNamespace</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">994</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">InGroup</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ac57db6ff719aec7e364b0823d5c231db">995</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ac57db6ff719aec7e364b0823d5c231db">InPage</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a463a8e3a1d39b8771600448eff1ab94f">996</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a463a8e3a1d39b8771600448eff1ab94f">InMember</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85af0bd1defdb45363bbae05d446baa8ba8">997</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85af0bd1defdb45363bbae05d446baa8ba8">InEnumValue</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a10248ae7318932ab6199589d50836c37">998</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a10248ae7318932ab6199589d50836c37">InPackage</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85acf8144d7c837a76fe6497c8158c6b973">999</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85acf8144d7c837a76fe6497c8158c6b973">InDir</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a31219fa12b60084e1f85db1eeffe4697">1000</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a31219fa12b60084e1f85db1eeffe4697">InModule</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85aeff175cadd93a4748a132b8020e4022e">1001</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85aeff175cadd93a4748a132b8020e4022e">InTempArgList</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1002</span><span class="doxyLineContent"><span class="doxyHighlight">               };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### TagFileParser() {#a43f4ea41f01f767ade7898b8d69d0f43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous_namespace{tagreader.cpp}::TagFileParser::TagFileParser (const char * tagName)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 336 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a43f4ea41f01f767ade7898b8d69d0f43">336</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">explicit</span><span class="doxyHighlight"> <a href="#a43f4ea41f01f767ade7898b8d69d0f43">TagFileParser</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *tagName) : <a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>(tagName) {}</span></span></div>

</div>


<p>Reference <a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#a1cb67a3965d52e8078507f0bfd354337">parseTagFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addDocAnchors() {#a04e4220513820012d31302361cf4f24d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::addDocAnchors (const std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt; &amp; e, const std::vector&lt; <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/taganchorinfo">TagAnchorInfo</a> &gt; &amp; l)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 986 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a04e4220513820012d31302361cf4f24d">1359</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a04e4220513820012d31302361cf4f24d">TagFileParser::addDocAnchors</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::shared_ptr&lt;Entry&gt; &amp;e,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::vector&lt;TagAnchorInfo&gt; &amp;l)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1360</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1361</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ta : l)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1362</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1363</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/sectionmanager/#afcf31c2b2bad467541c924342b08773d">SectionManager::instance</a>().find(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(ta.label))==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1364</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1365</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("New sectionInfo file=%s anchor=%s\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1366</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//    qPrint(ta-&gt;fileName),qPrint(ta-&gt;label));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1367</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> *si=<a href="/web-doxygen/docs/api/classes/sectionmanager/#afcf31c2b2bad467541c924342b08773d">SectionManager::instance</a>().<a href="/web-doxygen/docs/api/classes/sectionmanager/#afbb62a940b1b5d7dda3b31a81a9df922">add</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1368</span><span class="doxyLineContent"><span class="doxyHighlight">          ta.label,ta.fileName,-1,ta.title,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1369</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/sectiontype/#a017df4547430d10bdd70d7c56efcd78a">SectionType::Anchor</a>,0,<a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1370</span><span class="doxyLineContent"><span class="doxyHighlight">      e-&gt;anchors.push_back(si);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1371</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1372</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1373</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1374</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("Replace sectionInfo file=%s anchor=%s\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1375</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//    qPrint(ta-&gt;fileName),qPrint(ta-&gt;label));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1376</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/sectionmanager/#afcf31c2b2bad467541c924342b08773d">SectionManager::instance</a>().<a href="/web-doxygen/docs/api/classes/sectionmanager/#aa01b0cef766ad1df71b59741da1d7d88">replace</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1377</span><span class="doxyLineContent"><span class="doxyHighlight">          ta.label,ta.fileName,-1,ta.title,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1378</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/sectiontype/#a017df4547430d10bdd70d7c56efcd78a">SectionType::Anchor</a>,0,<a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1379</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1380</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1381</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/sectionmanager/#afbb62a940b1b5d7dda3b31a81a9df922">SectionManager::add</a>, <a href="/web-doxygen/docs/api/classes/sectiontype/#a017df4547430d10bdd70d7c56efcd78a">SectionType::Anchor</a>, <a href="/web-doxygen/docs/api/classes/sectionmanager/#afcf31c2b2bad467541c924342b08773d">SectionManager::instance</a>, <a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a> and <a href="/web-doxygen/docs/api/classes/sectionmanager/#aa01b0cef766ad1df71b59741da1d7d88">SectionManager::replace</a>.</p>


<p>Referenced by <a href="#aa9daed7f8f5651e85aaa17885e61134c">buildClassEntry</a>, <a href="#a9a2a4b0accaef9069229937226e60b10">buildLists</a> and <a href="#aa5dd16fd497d034a55fdca37a3c17804">buildMemberList</a>.</p>

</div>
</div>

### addIncludes() {#afbafb9f58aa69f3ea191211d77ffccae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::addIncludes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 358 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afbafb9f58aa69f3ea191211d77ffccae">1805</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afbafb9f58aa69f3ea191211d77ffccae">TagFileParser::addIncludes</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1806</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1807</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;comp : <a href="#ac75f982d3520a85cd31cabafbbd60dc7">m_tagFileCompounds</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1808</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1809</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo">TagFileInfo</a> *tfi = comp.getFileInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1810</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tfi)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1811</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1812</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("tag file tagName=%s path=%s name=%s\n",qPrint(m_tagName),qPrint(tfi-&gt;path),qPrint(tfi-&gt;name));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1813</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/filename">FileName</a> *fn = <a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>-&gt;find(tfi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">name</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1814</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fn)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1815</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1816</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;fd : *fn)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1817</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1818</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//printf("input file path=%s name=%s\n",qPrint(fd-&gt;getPath()),qPrint(fd-&gt;name()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1819</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fd-&gt;getPath()==<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(<a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>+</span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight">+tfi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo/#a156c071cac61ccf562a2b9d2fed30a95">path</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1820</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1821</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">//printf("found\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1822</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ii : tfi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo/#abfaa3aacc2e737b6b144cc72ee5755d5">includes</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1823</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1824</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightComment">//printf("ii-&gt;name='%s'\n",qPrint(ii-&gt;name));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1825</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/classes/filename">FileName</a> *ifn = <a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>-&gt;find(ii.name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1826</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>(ifn!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1827</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ifn)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1828</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1829</span><span class="doxyLineContent"><span class="doxyHighlight">                </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ifd : *ifn)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1830</span><span class="doxyLineContent"><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1831</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightComment">//printf("ifd-&gt;getOutputFileBase()=%s ii-&gt;id=%s\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1832</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightComment">//        qPrint(ifd-&gt;getOutputFileBase()),qPrint(ii-&gt;id));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1833</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ifd-&gt;getOutputFileBase()==<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(ii.id))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1834</span><span class="doxyLineContent"><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1835</span><span class="doxyLineContent"><span class="doxyHighlight">                    <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8">IncludeKind</a> kind = <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8ab0ead0aebf84f57889aab39d528f34b4">IncludeKind::IncludeSystem</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1836</span><span class="doxyLineContent"><span class="doxyHighlight">                    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ii.isModule)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1837</span><span class="doxyLineContent"><span class="doxyHighlight">                    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1838</span><span class="doxyLineContent"><span class="doxyHighlight">                      kind = <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8a57522338dd8bf2361634a923a2b71b81">IncludeKind::ImportModule</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1839</span><span class="doxyLineContent"><span class="doxyHighlight">                    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1840</span><span class="doxyLineContent"><span class="doxyHighlight">                    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ii.isImported)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1841</span><span class="doxyLineContent"><span class="doxyHighlight">                    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1842</span><span class="doxyLineContent"><span class="doxyHighlight">                      kind = ii.isLocal ? <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8a2dbc22c9108714bfd4417e558b7b82e2">IncludeKind::ImportLocal</a> : <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8ac597d64b5224025af7bef1aad3172845">IncludeKind::ImportSystem</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1843</span><span class="doxyLineContent"><span class="doxyHighlight">                    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1844</span><span class="doxyLineContent"><span class="doxyHighlight">                    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ii.isLocal)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1845</span><span class="doxyLineContent"><span class="doxyHighlight">                    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1846</span><span class="doxyLineContent"><span class="doxyHighlight">                      kind = <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8a72f604ea2eef74f27164fe740e67847b">IncludeKind::IncludeLocal</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1847</span><span class="doxyLineContent"><span class="doxyHighlight">                    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1848</span><span class="doxyLineContent"><span class="doxyHighlight">                    fd-&gt;addIncludeDependency(ifd.get(),ii.text,kind);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1849</span><span class="doxyLineContent"><span class="doxyHighlight">                  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1850</span><span class="doxyLineContent"><span class="doxyHighlight">                }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1851</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1852</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1853</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1854</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1855</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1856</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1857</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1858</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>, <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8a2dbc22c9108714bfd4417e558b7b82e2">ImportLocal</a>, <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8a57522338dd8bf2361634a923a2b71b81">ImportModule</a>, <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8ac597d64b5224025af7bef1aad3172845">ImportSystem</a>, <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8a72f604ea2eef74f27164fe740e67847b">IncludeLocal</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo/#abfaa3aacc2e737b6b144cc72ee5755d5">anonymous_namespace{tagreader.cpp}::TagFileInfo::includes</a>, <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8ab0ead0aebf84f57889aab39d528f34b4">IncludeSystem</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>, <a href="#ac75f982d3520a85cd31cabafbbd60dc7">m_tagFileCompounds</a>, <a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">anonymous_namespace{tagreader.cpp}::TagCompoundInfo::name</a> and <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo/#a156c071cac61ccf562a2b9d2fed30a95">anonymous_namespace{tagreader.cpp}::TagFileInfo::path</a>.</p>

</div>
</div>

### buildLists() {#a9a2a4b0accaef9069229937226e60b10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::buildLists (const std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt; &amp; root)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Injects the info gathered by the XML parser into the <a href="/web-doxygen/docs/api/classes/entry">Entry</a> tree. This tree contains the information extracted from the input in a "unrelated" form.</p>


<p>Definition at line 357 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9a2a4b0accaef9069229937226e60b10">1567</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9a2a4b0accaef9069229937226e60b10">TagFileParser::buildLists</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::shared_ptr&lt;Entry&gt; &amp;root)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1568</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1569</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// First reorganize the entries in m_tagFileCompounds such that</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1570</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// outer scope is processed before the nested class scope.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1571</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// To solve issue #11569, where a class nested in a specialization is</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1572</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// processed first, which later causes the wrong class to be used</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1573</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileparser/classnode">ClassNode</a> classRoot(</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1574</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;comp : <a href="#ac75f982d3520a85cd31cabafbbd60dc7">m_tagFileCompounds</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1575</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1576</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo">TagClassInfo</a> *tci = comp.getClassInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1577</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tci)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1578</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1579</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileparser/classnode">ClassNode</a> *current = &amp;classRoot;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1580</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> parts = <a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a>(tci-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">name</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1581</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0; i&lt;parts.size(); ++i)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1582</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1583</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;part = parts[i];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1584</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (current-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileparser/classnode/#a694169fa539ad5c675f8d301acb54b2c">children</a>.find(part)==current-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileparser/classnode/#a694169fa539ad5c675f8d301acb54b2c">children</a>.end()) </span><span class="doxyHighlightComment">// new child node</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1585</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1586</span><span class="doxyLineContent"><span class="doxyHighlight">          current-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileparser/classnode/#a694169fa539ad5c675f8d301acb54b2c">children</a>[part] = std::make_unique&lt;ClassNode&gt;(part);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1587</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1588</span><span class="doxyLineContent"><span class="doxyHighlight">        current = current-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileparser/classnode/#a694169fa539ad5c675f8d301acb54b2c">children</a>[part].get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1589</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i==parts.size()-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1590</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1591</span><span class="doxyLineContent"><span class="doxyHighlight">          current-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileparser/classnode/#a6aa32a2acb4b87396f2a74ba319c6299">tci</a> = tci;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1592</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1593</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1594</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1595</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1596</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1597</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// now process the classes following the tree structure</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1598</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ab5bfa36a1a89d2e6f35ac34fc6b0af3d">buildClassTree</a>(root,classRoot);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1599</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1600</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1601</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// build file list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1602</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;comp : <a href="#ac75f982d3520a85cd31cabafbbd60dc7">m_tagFileCompounds</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1603</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1604</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo">TagFileInfo</a> *tfi = comp.getFileInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1605</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tfi)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1606</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1607</span><span class="doxyLineContent"><span class="doxyHighlight">      std::shared_ptr&lt;Entry&gt; fe = std::make_shared&lt;Entry&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1608</span><span class="doxyLineContent"><span class="doxyHighlight">      fe-&gt;section = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a99344d48bf61e8b0948b39680259cf11">guessSection</a>(tfi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">name</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1609</span><span class="doxyLineContent"><span class="doxyHighlight">      fe-&gt;name     = tfi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">name</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1610</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a04e4220513820012d31302361cf4f24d">addDocAnchors</a>(fe,tfi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#abd7c06610979d5c6078dbf666c4358b5">docAnchors</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1611</span><span class="doxyLineContent"><span class="doxyHighlight">      fe-&gt;tagInfoData.tagName  = <a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1612</span><span class="doxyLineContent"><span class="doxyHighlight">      fe-&gt;tagInfoData.fileName = tfi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a25246009588765b59a7e73cc87db2548">filename</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1613</span><span class="doxyLineContent"><span class="doxyHighlight">      fe-&gt;hasTagInfo = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1614</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1615</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fullName = <a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>+</span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight">+tfi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo/#a156c071cac61ccf562a2b9d2fed30a95">path</a>+<a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(tfi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">name</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1616</span><span class="doxyLineContent"><span class="doxyHighlight">      fe-&gt;fileName  = fullName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1617</span><span class="doxyLineContent"><span class="doxyHighlight">      fe-&gt;startLine = tfi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a8d08366f8e993aab489906c4998886e6">lineNr</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1618</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("createFileDef() filename=%s\n",qPrint(tfi-&gt;filename));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1619</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tagid = <a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>+</span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight">+tfi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo/#a156c071cac61ccf562a2b9d2fed30a95">path</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1620</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> fd = <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>(tagid, tfi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">name</a>,<a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>, tfi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a25246009588765b59a7e73cc87db2548">filename</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1621</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/filename">FileName</a> *mn = <a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>-&gt;find(tfi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">name</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1622</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mn)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1623</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1624</span><span class="doxyLineContent"><span class="doxyHighlight">        mn-&gt;push_back(std::move(fd));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1625</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1626</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1627</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1628</span><span class="doxyLineContent"><span class="doxyHighlight">        mn = <a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>-&gt;add(tfi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">name</a>,fullName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1629</span><span class="doxyLineContent"><span class="doxyHighlight">        mn-&gt;push_back(std::move(fd));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1630</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1631</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aa5dd16fd497d034a55fdca37a3c17804">buildMemberList</a>(fe,tfi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#af08267c179ffb9c4e799ea9a59f8f2a2">members</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1632</span><span class="doxyLineContent"><span class="doxyHighlight">      root-&gt;moveToSubEntryAndKeep(fe);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1633</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1634</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1635</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1636</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// build concept list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1637</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;comp : <a href="#ac75f982d3520a85cd31cabafbbd60dc7">m_tagFileCompounds</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1638</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1639</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagconceptinfo">TagConceptInfo</a> *tci = comp.getConceptInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1640</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tci)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1641</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1642</span><span class="doxyLineContent"><span class="doxyHighlight">      std::shared_ptr&lt;Entry&gt; ce = std::make_shared&lt;Entry&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1643</span><span class="doxyLineContent"><span class="doxyHighlight">      ce-&gt;section = EntryType::makeConcept();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1644</span><span class="doxyLineContent"><span class="doxyHighlight">      ce-&gt;name     = tci-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">name</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1645</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a04e4220513820012d31302361cf4f24d">addDocAnchors</a>(ce,tci-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#abd7c06610979d5c6078dbf666c4358b5">docAnchors</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1646</span><span class="doxyLineContent"><span class="doxyHighlight">      ce-&gt;tagInfoData.tagName  = <a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1647</span><span class="doxyLineContent"><span class="doxyHighlight">      ce-&gt;tagInfoData.fileName = tci-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a25246009588765b59a7e73cc87db2548">filename</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1648</span><span class="doxyLineContent"><span class="doxyHighlight">      ce-&gt;startLine   = tci-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a8d08366f8e993aab489906c4998886e6">lineNr</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1649</span><span class="doxyLineContent"><span class="doxyHighlight">      ce-&gt;fileName    = <a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1650</span><span class="doxyLineContent"><span class="doxyHighlight">      ce-&gt;hasTagInfo  = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1651</span><span class="doxyLineContent"><span class="doxyHighlight">      ce-&gt;id       = tci-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagconceptinfo/#a5fd44909318ed3f44b17aaf966e7c019">clangId</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1652</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1653</span><span class="doxyLineContent"><span class="doxyHighlight">      root-&gt;moveToSubEntryAndKeep(ce);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1654</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1655</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1656</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1657</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// build module list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1658</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;comp : <a href="#ac75f982d3520a85cd31cabafbbd60dc7">m_tagFileCompounds</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1659</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1660</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagmoduleinfo">TagModuleInfo</a> *tmi = comp.getModuleInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1661</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tmi)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1662</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1663</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mm = <a href="/web-doxygen/docs/api/classes/modulemanager/#a4f48cf5d05907a6acc4b9c6ddec752b7">ModuleManager::instance</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1664</span><span class="doxyLineContent"><span class="doxyHighlight">      mm.createModuleDef(tmi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a25246009588765b59a7e73cc87db2548">filename</a>,tmi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a8d08366f8e993aab489906c4998886e6">lineNr</a>,1,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">,tmi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">name</a>,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1665</span><span class="doxyLineContent"><span class="doxyHighlight">      mm.addTagInfo(tmi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a25246009588765b59a7e73cc87db2548">filename</a>,<a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>,tmi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagmoduleinfo/#a4a0db546adc33a679754bf1a2c7b0a46">clangId</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1666</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1667</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *mod = mm.getPrimaryInterface(tmi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">name</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1668</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mod &amp;&amp; !tmi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#abd7c06610979d5c6078dbf666c4358b5">docAnchors</a>.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1669</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1670</span><span class="doxyLineContent"><span class="doxyHighlight">        std::vector&lt;const SectionInfo *&gt; anchorList;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1671</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ta : tmi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#abd7c06610979d5c6078dbf666c4358b5">docAnchors</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1672</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1673</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/sectionmanager/#afcf31c2b2bad467541c924342b08773d">SectionManager::instance</a>().find(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(ta.label))==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1674</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1675</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">//printf("New sectionInfo file=%s anchor=%s\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1676</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">//    qPrint(ta-&gt;fileName),qPrint(ta-&gt;label));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1677</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> *si=<a href="/web-doxygen/docs/api/classes/sectionmanager/#afcf31c2b2bad467541c924342b08773d">SectionManager::instance</a>().<a href="/web-doxygen/docs/api/classes/sectionmanager/#afbb62a940b1b5d7dda3b31a81a9df922">add</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1678</span><span class="doxyLineContent"><span class="doxyHighlight">                ta.label,ta.fileName,-1,ta.title,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1679</span><span class="doxyLineContent"><span class="doxyHighlight">                <a href="/web-doxygen/docs/api/classes/sectiontype/#a017df4547430d10bdd70d7c56efcd78a">SectionType::Anchor</a>,0,<a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1680</span><span class="doxyLineContent"><span class="doxyHighlight">            anchorList.push_back(si);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1681</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1682</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1683</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1684</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Duplicate anchor {} found"</span><span class="doxyHighlight">,ta.label);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1685</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1686</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1687</span><span class="doxyLineContent"><span class="doxyHighlight">        mod-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#a887b37e99fd86677550a17186db349f2">addSectionsToDefinition</a>(anchorList);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1688</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1689</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1690</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1691</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1692</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1693</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// build namespace list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1694</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;comp : <a href="#ac75f982d3520a85cd31cabafbbd60dc7">m_tagFileCompounds</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1695</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1696</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagnamespaceinfo">TagNamespaceInfo</a> *tni = comp.getNamespaceInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1697</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tni)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1698</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1699</span><span class="doxyLineContent"><span class="doxyHighlight">      std::shared_ptr&lt;Entry&gt; ne = std::make_shared&lt;Entry&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1700</span><span class="doxyLineContent"><span class="doxyHighlight">      ne-&gt;section = EntryType::makeNamespace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1701</span><span class="doxyLineContent"><span class="doxyHighlight">      ne-&gt;name     = tni-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">name</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1702</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a04e4220513820012d31302361cf4f24d">addDocAnchors</a>(ne,tni-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#abd7c06610979d5c6078dbf666c4358b5">docAnchors</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1703</span><span class="doxyLineContent"><span class="doxyHighlight">      ne-&gt;tagInfoData.tagName  = <a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1704</span><span class="doxyLineContent"><span class="doxyHighlight">      ne-&gt;tagInfoData.fileName = tni-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a25246009588765b59a7e73cc87db2548">filename</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1705</span><span class="doxyLineContent"><span class="doxyHighlight">      ne-&gt;startLine   = tni-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a8d08366f8e993aab489906c4998886e6">lineNr</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1706</span><span class="doxyLineContent"><span class="doxyHighlight">      ne-&gt;fileName    = <a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1707</span><span class="doxyLineContent"><span class="doxyHighlight">      ne-&gt;hasTagInfo  = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1708</span><span class="doxyLineContent"><span class="doxyHighlight">      ne-&gt;id       = tni-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagnamespaceinfo/#a0ff6b0d4cff44254154e3c249cecf903">clangId</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1709</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1710</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aa5dd16fd497d034a55fdca37a3c17804">buildMemberList</a>(ne,tni-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#af08267c179ffb9c4e799ea9a59f8f2a2">members</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1711</span><span class="doxyLineContent"><span class="doxyHighlight">      root-&gt;moveToSubEntryAndKeep(ne);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1712</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1713</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1714</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1715</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// build package list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1716</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;comp : <a href="#ac75f982d3520a85cd31cabafbbd60dc7">m_tagFileCompounds</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1717</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1718</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpackageinfo">TagPackageInfo</a> *tpgi = comp.getPackageInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1719</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tpgi)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1720</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1721</span><span class="doxyLineContent"><span class="doxyHighlight">      std::shared_ptr&lt;Entry&gt; pe = std::make_shared&lt;Entry&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1722</span><span class="doxyLineContent"><span class="doxyHighlight">      pe-&gt;section = EntryType::makePackage();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1723</span><span class="doxyLineContent"><span class="doxyHighlight">      pe-&gt;name     = tpgi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">name</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1724</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a04e4220513820012d31302361cf4f24d">addDocAnchors</a>(pe,tpgi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#abd7c06610979d5c6078dbf666c4358b5">docAnchors</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1725</span><span class="doxyLineContent"><span class="doxyHighlight">      pe-&gt;tagInfoData.tagName  = <a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1726</span><span class="doxyLineContent"><span class="doxyHighlight">      pe-&gt;tagInfoData.fileName = tpgi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a25246009588765b59a7e73cc87db2548">filename</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1727</span><span class="doxyLineContent"><span class="doxyHighlight">      pe-&gt;startLine   = tpgi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a8d08366f8e993aab489906c4998886e6">lineNr</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1728</span><span class="doxyLineContent"><span class="doxyHighlight">      pe-&gt;fileName    = <a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1729</span><span class="doxyLineContent"><span class="doxyHighlight">      pe-&gt;hasTagInfo  = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1730</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1731</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aa5dd16fd497d034a55fdca37a3c17804">buildMemberList</a>(pe,tpgi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#af08267c179ffb9c4e799ea9a59f8f2a2">members</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1732</span><span class="doxyLineContent"><span class="doxyHighlight">      root-&gt;moveToSubEntryAndKeep(pe);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1733</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1734</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1735</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1736</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// build group list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1737</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;comp : <a href="#ac75f982d3520a85cd31cabafbbd60dc7">m_tagFileCompounds</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1738</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1739</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo">TagGroupInfo</a> *tgi = comp.getGroupInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1740</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tgi)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1741</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1742</span><span class="doxyLineContent"><span class="doxyHighlight">      std::shared_ptr&lt;Entry&gt; ge = std::make_shared&lt;Entry&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1743</span><span class="doxyLineContent"><span class="doxyHighlight">      ge-&gt;section = EntryType::makeGroupDoc();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1744</span><span class="doxyLineContent"><span class="doxyHighlight">      ge-&gt;name     = tgi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">name</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1745</span><span class="doxyLineContent"><span class="doxyHighlight">      ge-&gt;type     = tgi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#ac3b6e212c0c08a615327124433781ad2">title</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1746</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a04e4220513820012d31302361cf4f24d">addDocAnchors</a>(ge,tgi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#abd7c06610979d5c6078dbf666c4358b5">docAnchors</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1747</span><span class="doxyLineContent"><span class="doxyHighlight">      ge-&gt;tagInfoData.tagName  = <a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1748</span><span class="doxyLineContent"><span class="doxyHighlight">      ge-&gt;tagInfoData.fileName = tgi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a25246009588765b59a7e73cc87db2548">filename</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1749</span><span class="doxyLineContent"><span class="doxyHighlight">      ge-&gt;startLine   = tgi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a8d08366f8e993aab489906c4998886e6">lineNr</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1750</span><span class="doxyLineContent"><span class="doxyHighlight">      ge-&gt;fileName    = <a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1751</span><span class="doxyLineContent"><span class="doxyHighlight">      ge-&gt;hasTagInfo  = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1752</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1753</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aa5dd16fd497d034a55fdca37a3c17804">buildMemberList</a>(ge,tgi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#af08267c179ffb9c4e799ea9a59f8f2a2">members</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1754</span><span class="doxyLineContent"><span class="doxyHighlight">      root-&gt;moveToSubEntryAndKeep(ge);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1755</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1756</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1757</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1758</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;comp : <a href="#ac75f982d3520a85cd31cabafbbd60dc7">m_tagFileCompounds</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1759</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1760</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo">TagGroupInfo</a> *tgi = comp.getGroupInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1761</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tgi)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1762</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1763</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// set subgroup relations bug_774118</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1764</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;sg : tgi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#acd576264c0c610848fa2d34e3808487f">subgroupList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1765</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1766</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;children = root-&gt;children();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1767</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> i = std::find_if(children.begin(),children.end(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1768</span><span class="doxyLineContent"><span class="doxyHighlight">            [&amp;](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::shared_ptr&lt;Entry&gt; &amp;e) { return e-&gt;name == sg.c_str(); });</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1769</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i!=children.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1770</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1771</span><span class="doxyLineContent"><span class="doxyHighlight">          (*i)-&gt;groups.emplace_back(tgi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">name</a>,<a href="/web-doxygen/docs/api/structs/grouping/#a9f0ec5ab376b083ebe3274ea79fd2d70a464b2001acf04bed5df29c11a66fb2fb">Grouping::GROUPING_INGROUP</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1772</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1773</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1774</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1775</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1776</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1777</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// build page list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1778</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;comp : <a href="#ac75f982d3520a85cd31cabafbbd60dc7">m_tagFileCompounds</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1779</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1780</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpageinfo">TagPageInfo</a> *tpi = comp.getPageInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1781</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tpi)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1782</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1783</span><span class="doxyLineContent"><span class="doxyHighlight">      std::shared_ptr&lt;Entry&gt; pe = std::make_shared&lt;Entry&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1784</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isIndex = (<a href="/web-doxygen/docs/api/files/src/util-cpp/#a73d2ea8014e5ac678dac39cfd56ba148">stripExtensionGeneral</a>(tpi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a25246009588765b59a7e73cc87db2548">filename</a>,<a href="/web-doxygen/docs/api/files/src/util-cpp/#af18ed4687438f52f5c7fe9dfb226244c">getFileNameExtension</a>(tpi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a25246009588765b59a7e73cc87db2548">filename</a>))==</span><span class="doxyHighlightStringLiteral">"index"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1785</span><span class="doxyLineContent"><span class="doxyHighlight">      pe-&gt;section  = isIndex ? EntryType::makeMainpageDoc() : EntryType::makePageDoc();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1786</span><span class="doxyLineContent"><span class="doxyHighlight">      pe-&gt;name     = tpi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">name</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1787</span><span class="doxyLineContent"><span class="doxyHighlight">      pe-&gt;args     = tpi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpageinfo/#a251988254871e25f8b2a3f041ab0a0d1">title</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1788</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;subpage : tpi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpageinfo/#ac15a5ec4694c2839b96398815b523ad7">subpages</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1789</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1790</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// we add subpage labels as a kind of "inheritance" relation to prevent</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1791</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// needing to add another list to the Entry class.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1792</span><span class="doxyLineContent"><span class="doxyHighlight">        pe-&gt;extends.emplace_back(<a href="/web-doxygen/docs/api/files/src/util-cpp/#a8653297bcfce5f19bebc8602e35cb589">stripExtension</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(subpage)),Protection::Public,Specifier::Normal);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1793</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1794</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a04e4220513820012d31302361cf4f24d">addDocAnchors</a>(pe,tpi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#abd7c06610979d5c6078dbf666c4358b5">docAnchors</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1795</span><span class="doxyLineContent"><span class="doxyHighlight">      pe-&gt;tagInfoData.tagName  = <a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1796</span><span class="doxyLineContent"><span class="doxyHighlight">      pe-&gt;tagInfoData.fileName = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8653297bcfce5f19bebc8602e35cb589">stripExtension</a>(tpi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a25246009588765b59a7e73cc87db2548">filename</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1797</span><span class="doxyLineContent"><span class="doxyHighlight">      pe-&gt;startLine   = tpi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a8d08366f8e993aab489906c4998886e6">lineNr</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1798</span><span class="doxyLineContent"><span class="doxyHighlight">      pe-&gt;fileName    = <a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1799</span><span class="doxyLineContent"><span class="doxyHighlight">      pe-&gt;hasTagInfo  = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1800</span><span class="doxyLineContent"><span class="doxyHighlight">      root-&gt;moveToSubEntryAndKeep(pe);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1801</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1802</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1803</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/sectionmanager/#afbb62a940b1b5d7dda3b31a81a9df922">SectionManager::add</a>, <a href="#a04e4220513820012d31302361cf4f24d">addDocAnchors</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#a887b37e99fd86677550a17186db349f2">DefinitionMutable::addSectionsToDefinition</a>, <a href="/web-doxygen/docs/api/classes/sectiontype/#a017df4547430d10bdd70d7c56efcd78a">SectionType::Anchor</a>, <a href="#ab5bfa36a1a89d2e6f35ac34fc6b0af3d">buildClassTree</a>, <a href="#aa5dd16fd497d034a55fdca37a3c17804">buildMemberList</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileparser/classnode/#a694169fa539ad5c675f8d301acb54b2c">anonymous_namespace{tagreader.cpp}::TagFileParser::ClassNode::children</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagconceptinfo/#a5fd44909318ed3f44b17aaf966e7c019">anonymous_namespace{tagreader.cpp}::TagConceptInfo::clangId</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagmoduleinfo/#a4a0db546adc33a679754bf1a2c7b0a46">anonymous_namespace{tagreader.cpp}::TagModuleInfo::clangId</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagnamespaceinfo/#a0ff6b0d4cff44254154e3c249cecf903">anonymous_namespace{tagreader.cpp}::TagNamespaceInfo::clangId</a>, <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#abd7c06610979d5c6078dbf666c4358b5">anonymous_namespace{tagreader.cpp}::TagCompoundInfo::docAnchors</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a25246009588765b59a7e73cc87db2548">anonymous_namespace{tagreader.cpp}::TagCompoundInfo::filename</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af18ed4687438f52f5c7fe9dfb226244c">getFileNameExtension</a>, <a href="/web-doxygen/docs/api/structs/grouping/#a9f0ec5ab376b083ebe3274ea79fd2d70a464b2001acf04bed5df29c11a66fb2fb">Grouping::GROUPING_INGROUP</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a99344d48bf61e8b0948b39680259cf11">guessSection</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a4f48cf5d05907a6acc4b9c6ddec752b7">ModuleManager::instance</a>, <a href="/web-doxygen/docs/api/classes/sectionmanager/#afcf31c2b2bad467541c924342b08773d">SectionManager::instance</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a8d08366f8e993aab489906c4998886e6">anonymous_namespace{tagreader.cpp}::TagCompoundInfo::lineNr</a>, <a href="#ac75f982d3520a85cd31cabafbbd60dc7">m_tagFileCompounds</a>, <a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#af08267c179ffb9c4e799ea9a59f8f2a2">anonymous_namespace{tagreader.cpp}::TagCompoundInfo::members</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">anonymous_namespace{tagreader.cpp}::TagCompoundInfo::name</a>, <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo/#a156c071cac61ccf562a2b9d2fed30a95">anonymous_namespace{tagreader.cpp}::TagFileInfo::path</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8653297bcfce5f19bebc8602e35cb589">stripExtension</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a73d2ea8014e5ac678dac39cfd56ba148">stripExtensionGeneral</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#acd576264c0c610848fa2d34e3808487f">anonymous_namespace{tagreader.cpp}::TagGroupInfo::subgroupList</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpageinfo/#ac15a5ec4694c2839b96398815b523ad7">anonymous_namespace{tagreader.cpp}::TagPageInfo::subpages</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileparser/classnode/#a6aa32a2acb4b87396f2a74ba319c6299">anonymous_namespace{tagreader.cpp}::TagFileParser::ClassNode::tci</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#ac3b6e212c0c08a615327124433781ad2">anonymous_namespace{tagreader.cpp}::TagGroupInfo::title</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpageinfo/#a251988254871e25f8b2a3f041ab0a0d1">anonymous_namespace{tagreader.cpp}::TagPageInfo::title</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### buildMemberList() {#aa5dd16fd497d034a55fdca37a3c17804}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::buildMemberList (const std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt; &amp; ce, const std::vector&lt; <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagmemberinfo">TagMemberInfo</a> &gt; &amp; members)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 985 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa5dd16fd497d034a55fdca37a3c17804">1383</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa5dd16fd497d034a55fdca37a3c17804">TagFileParser::buildMemberList</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::shared_ptr&lt;Entry&gt; &amp;ce,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::vector&lt;TagMemberInfo&gt; &amp;members)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1384</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1385</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;tmi : members)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1386</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1387</span><span class="doxyLineContent"><span class="doxyHighlight">    std::shared_ptr&lt;Entry&gt; me = std::make_shared&lt;Entry&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1388</span><span class="doxyLineContent"><span class="doxyHighlight">    me-&gt;type       = tmi.type;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1389</span><span class="doxyLineContent"><span class="doxyHighlight">    me-&gt;name       = tmi.name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1390</span><span class="doxyLineContent"><span class="doxyHighlight">    me-&gt;args       = tmi.arglist;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1391</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!me-&gt;args.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1392</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1393</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;argList = *<a href="/web-doxygen/docs/api/files/src/defargs-h/#a88825bfb79a9c15e54ff57415b4de54d">stringToArgumentList</a>(SrcLangExt::Cpp,me-&gt;args);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1394</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1395</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tmi.enumValues.size()&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1396</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1397</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;spec.setStrong(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1398</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;evi : tmi.enumValues)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1399</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1400</span><span class="doxyLineContent"><span class="doxyHighlight">        std::shared_ptr&lt;Entry&gt; ev = std::make_shared&lt;Entry&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1401</span><span class="doxyLineContent"><span class="doxyHighlight">        ev-&gt;type       = </span><span class="doxyHighlightStringLiteral">"@"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1402</span><span class="doxyLineContent"><span class="doxyHighlight">        ev-&gt;name       = evi.name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1403</span><span class="doxyLineContent"><span class="doxyHighlight">        ev-&gt;id         = evi.clangid;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1404</span><span class="doxyLineContent"><span class="doxyHighlight">        ev-&gt;section = EntryType::makeVariable();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1405</span><span class="doxyLineContent"><span class="doxyHighlight">        ev-&gt;tagInfoData.tagName    = <a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1406</span><span class="doxyLineContent"><span class="doxyHighlight">        ev-&gt;tagInfoData.anchor     = evi.anchor;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1407</span><span class="doxyLineContent"><span class="doxyHighlight">        ev-&gt;tagInfoData.fileName   = evi.file;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1408</span><span class="doxyLineContent"><span class="doxyHighlight">        ev-&gt;hasTagInfo    = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1409</span><span class="doxyLineContent"><span class="doxyHighlight">        me-&gt;moveToSubEntryAndKeep(ev);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1410</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1411</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1412</span><span class="doxyLineContent"><span class="doxyHighlight">    me-&gt;protection = tmi.prot;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1413</span><span class="doxyLineContent"><span class="doxyHighlight">    me-&gt;virt       = tmi.virt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1414</span><span class="doxyLineContent"><span class="doxyHighlight">    me-&gt;isStatic   = tmi.isStatic;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1415</span><span class="doxyLineContent"><span class="doxyHighlight">    me-&gt;fileName   = ce-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1416</span><span class="doxyLineContent"><span class="doxyHighlight">    me-&gt;id         = tmi.clangId;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1417</span><span class="doxyLineContent"><span class="doxyHighlight">    me-&gt;startLine  = tmi.lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1418</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ce-&gt;section.isGroupDoc())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1419</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1420</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;groups.emplace_back(ce-&gt;name,<a href="/web-doxygen/docs/api/structs/grouping/#a9f0ec5ab376b083ebe3274ea79fd2d70a464b2001acf04bed5df29c11a66fb2fb">Grouping::GROUPING_INGROUP</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1421</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1422</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a04e4220513820012d31302361cf4f24d">addDocAnchors</a>(me,tmi.docAnchors);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1423</span><span class="doxyLineContent"><span class="doxyHighlight">    me-&gt;tagInfoData.tagName    = <a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1424</span><span class="doxyLineContent"><span class="doxyHighlight">    me-&gt;tagInfoData.anchor     = tmi.anchor;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1425</span><span class="doxyLineContent"><span class="doxyHighlight">    me-&gt;tagInfoData.fileName   = tmi.anchorFile;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1426</span><span class="doxyLineContent"><span class="doxyHighlight">    me-&gt;hasTagInfo    = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1427</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tmi.kind==</span><span class="doxyHighlightStringLiteral">"define"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1428</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1429</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;type=</span><span class="doxyHighlightStringLiteral">"#define"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1430</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;section = EntryType::makeDefine();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1431</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1432</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tmi.kind==</span><span class="doxyHighlightStringLiteral">"enumvalue"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1433</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1434</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;section = EntryType::makeVariable();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1435</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;mtype = MethodTypes::Method;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1436</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1437</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tmi.kind==</span><span class="doxyHighlightStringLiteral">"property"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1438</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1439</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;section = EntryType::makeVariable();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1440</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;mtype = MethodTypes::Property;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1441</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1442</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tmi.kind==</span><span class="doxyHighlightStringLiteral">"event"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1443</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1444</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;section = EntryType::makeVariable();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1445</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;mtype = MethodTypes::Event;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1446</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1447</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tmi.kind==</span><span class="doxyHighlightStringLiteral">"variable"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1448</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1449</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;section = EntryType::makeVariable();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1450</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;mtype = MethodTypes::Method;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1451</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1452</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tmi.kind==</span><span class="doxyHighlightStringLiteral">"typedef"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1453</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1454</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;section = EntryType::makeVariable();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1455</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;type.prepend(</span><span class="doxyHighlightStringLiteral">"typedef "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1456</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;mtype = MethodTypes::Method;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1457</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1458</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tmi.kind==</span><span class="doxyHighlightStringLiteral">"enumeration"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1459</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1460</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;section = EntryType::makeEnum();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1461</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;mtype = MethodTypes::Method;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1462</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1463</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tmi.kind==</span><span class="doxyHighlightStringLiteral">"function"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1464</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1465</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;section = EntryType::makeFunction();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1466</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;mtype = MethodTypes::Method;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1467</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1468</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tmi.kind==</span><span class="doxyHighlightStringLiteral">"signal"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1469</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1470</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;section = EntryType::makeFunction();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1471</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;mtype = MethodTypes::Signal;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1472</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1473</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tmi.kind==</span><span class="doxyHighlightStringLiteral">"prototype"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1474</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1475</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;section = EntryType::makeFunction();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1476</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;mtype = MethodTypes::Method;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1477</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1478</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tmi.kind==</span><span class="doxyHighlightStringLiteral">"friend"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1479</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1480</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;section = EntryType::makeFunction();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1481</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;type.prepend(</span><span class="doxyHighlightStringLiteral">"friend "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1482</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;mtype = MethodTypes::Method;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1483</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1484</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tmi.kind==</span><span class="doxyHighlightStringLiteral">"dcop"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1485</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1486</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;section = EntryType::makeFunction();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1487</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;mtype = MethodTypes::DCOP;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1488</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1489</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tmi.kind==</span><span class="doxyHighlightStringLiteral">"slot"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1490</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1491</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;section = EntryType::makeFunction();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1492</span><span class="doxyLineContent"><span class="doxyHighlight">      me-&gt;mtype = MethodTypes::Slot;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1493</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1494</span><span class="doxyLineContent"><span class="doxyHighlight">    ce-&gt;moveToSubEntryAndKeep(me);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1495</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1496</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a04e4220513820012d31302361cf4f24d">addDocAnchors</a>, <a href="/web-doxygen/docs/api/structs/grouping/#a9f0ec5ab376b083ebe3274ea79fd2d70a464b2001acf04bed5df29c11a66fb2fb">Grouping::GROUPING_INGROUP</a>, <a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>, <a href="/web-doxygen/docs/api/files/src/defargs-h/#a88825bfb79a9c15e54ff57415b4de54d">stringToArgumentList</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>


<p>Referenced by <a href="#aa9daed7f8f5651e85aaa17885e61134c">buildClassEntry</a> and <a href="#a9a2a4b0accaef9069229937226e60b10">buildLists</a>.</p>

</div>
</div>

### characters() {#a98c5a0d5ae75e20939baaba36ecaf2e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::characters (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ch)</td>
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



<p>Definition at line 350 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a98c5a0d5ae75e20939baaba36ecaf2e3">350</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a98c5a0d5ae75e20939baaba36ecaf2e3">characters</a> ( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ch ) { <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>+=ch; }</span></span></div>

</div>


<p>Reference <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>.</p>

</div>
</div>

### dump() {#aafd3846f78cc76b992152366c99f7d74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Dumps the internal structures. For debugging only!</p>


<p>Definition at line 356 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aafd3846f78cc76b992152366c99f7d74">1176</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aafd3846f78cc76b992152366c99f7d74">TagFileParser::dump</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1177</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1178</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"-------- Results --------\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1179</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//============== CLASSES</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1180</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;comp : <a href="#ac75f982d3520a85cd31cabafbbd60dc7">m_tagFileCompounds</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1181</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1182</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (comp.type()==<a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant/#a1a5f5ee04cdc70747f2c031f548d4ed7a9bd81329febf6efe22788e03ddeaf0af">TagCompoundVariant::Type::Class</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1183</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1184</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo">TagClassInfo</a> *cd = comp.getClassInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1185</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"class '{}'\n"</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">name</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1186</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"  filename '{}'\n"</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a25246009588765b59a7e73cc87db2548">filename</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1187</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/baseinfo">BaseInfo</a> &amp;bi : cd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ac56edb55f992391df4adef74f54f596f">bases</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1188</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1189</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0, </span><span class="doxyHighlightStringLiteral">"  base: {}\n"</span><span class="doxyHighlight">,bi.<a href="/web-doxygen/docs/api/structs/baseinfo/#ae8bba327d477830b4664f9d03b05c97b">name</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1190</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1191</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1192</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;md : cd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#af08267c179ffb9c4e799ea9a59f8f2a2">members</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1193</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1194</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"  member:\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1195</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"    kind: '{}'\n"</span><span class="doxyHighlight">,md.kind);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1196</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"    name: '{}'\n"</span><span class="doxyHighlight">,md.name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1197</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"    anchor: '{}'\n"</span><span class="doxyHighlight">,md.anchor);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1198</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"    arglist: '{}'\n"</span><span class="doxyHighlight">,md.arglist);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1199</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1200</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1201</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1202</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//============== CONCEPTS</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1203</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;comp : <a href="#ac75f982d3520a85cd31cabafbbd60dc7">m_tagFileCompounds</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1204</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1205</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (comp.type()==<a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant/#a1a5f5ee04cdc70747f2c031f548d4ed7ad99a604c79ce3c2e76a2f43488d5d4c3">TagCompoundVariant::Type::Concept</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1206</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1207</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagconceptinfo">TagConceptInfo</a> *cd = comp.getConceptInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1208</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1209</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"concept '{}'\n"</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">name</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1210</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"  filename '{}'\n"</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a25246009588765b59a7e73cc87db2548">filename</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1211</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1212</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1213</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//============== MODULES</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1214</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;comp : <a href="#ac75f982d3520a85cd31cabafbbd60dc7">m_tagFileCompounds</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1215</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1216</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (comp.type()==<a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant/#a1a5f5ee04cdc70747f2c031f548d4ed7ae55f75a29310d7b60f7ac1d390c8ae42">TagCompoundVariant::Type::Module</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1217</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1218</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagmoduleinfo">TagModuleInfo</a> *mi = comp.getModuleInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1219</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1220</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"module '{}'\n"</span><span class="doxyHighlight">,mi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">name</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1221</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"  filename '{}'\n"</span><span class="doxyHighlight">,mi-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a25246009588765b59a7e73cc87db2548">filename</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1222</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1223</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1224</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//============== NAMESPACES</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1225</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;comp : <a href="#ac75f982d3520a85cd31cabafbbd60dc7">m_tagFileCompounds</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1226</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1227</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (comp.type()==<a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant/#a1a5f5ee04cdc70747f2c031f548d4ed7ab3ba0fe968ce39dcfc6fe8cc0f1b02da">TagCompoundVariant::Type::Namespace</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1228</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1229</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagnamespaceinfo">TagNamespaceInfo</a> *nd = comp.getNamespaceInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1230</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1231</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"namespace '{}'\n"</span><span class="doxyHighlight">,nd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">name</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1232</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"  filename '{}'\n"</span><span class="doxyHighlight">,nd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a25246009588765b59a7e73cc87db2548">filename</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1233</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cls : nd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagnamespaceinfo/#abdeeffe4f911bf72f5811d03c04e39a3">classList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1234</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1235</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0, </span><span class="doxyHighlightStringLiteral">"  class: {}\n"</span><span class="doxyHighlight">,cls);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1236</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1237</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1238</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;md : nd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#af08267c179ffb9c4e799ea9a59f8f2a2">members</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1239</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1240</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"  member:\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1241</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"    kind: '{}'\n"</span><span class="doxyHighlight">,md.kind);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1242</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"    name: '{}'\n"</span><span class="doxyHighlight">,md.name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1243</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"    anchor: '{}'\n"</span><span class="doxyHighlight">,md.anchor);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1244</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"    arglist: '{}'\n"</span><span class="doxyHighlight">,md.arglist);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1245</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1246</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1247</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1248</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1249</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//============== FILES</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1250</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;comp : <a href="#ac75f982d3520a85cd31cabafbbd60dc7">m_tagFileCompounds</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1251</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1252</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (comp.type()==<a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant/#a1a5f5ee04cdc70747f2c031f548d4ed7a0b27918290ff5323bea1e3b78a9cf04e">TagCompoundVariant::Type::File</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1253</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1254</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo">TagFileInfo</a> *fd = comp.getFileInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1255</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1256</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"file '{}'\n"</span><span class="doxyHighlight">,fd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">name</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1257</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"  filename '{}'\n"</span><span class="doxyHighlight">,fd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a25246009588765b59a7e73cc87db2548">filename</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1258</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ns : fd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo/#a5c3e03594e0c0c25c2810deeb76c1297">namespaceList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1259</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1260</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0, </span><span class="doxyHighlightStringLiteral">"  namespace: {}\n"</span><span class="doxyHighlight">,ns);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1261</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1262</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cs : fd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo/#ada9ca1bc4c9e47fb4bcbe1d58e35eae7">classList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1263</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1264</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0, </span><span class="doxyHighlightStringLiteral">"  class: {} \n"</span><span class="doxyHighlight">,cs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1265</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1266</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1267</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;md : fd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#af08267c179ffb9c4e799ea9a59f8f2a2">members</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1268</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1269</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"  member:\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1270</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"    kind: '{}'\n"</span><span class="doxyHighlight">,md.kind);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1271</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"    name: '{}'\n"</span><span class="doxyHighlight">,md.name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1272</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"    anchor: '{}'\n"</span><span class="doxyHighlight">,md.anchor);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1273</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"    arglist: '{}'\n"</span><span class="doxyHighlight">,md.arglist);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1274</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1275</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1276</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ii : fd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo/#abfaa3aacc2e737b6b144cc72ee5755d5">includes</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1277</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1278</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"  includes id: {} name: {}\n"</span><span class="doxyHighlight">,ii.id,ii.name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1279</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1280</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1281</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1282</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1283</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//============== GROUPS</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1284</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;comp : <a href="#ac75f982d3520a85cd31cabafbbd60dc7">m_tagFileCompounds</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1285</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1286</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (comp.type()==<a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant/#a1a5f5ee04cdc70747f2c031f548d4ed7a03937134cedab9078be39a77ee3a48a0">TagCompoundVariant::Type::Group</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1287</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1288</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo">TagGroupInfo</a> *gd = comp.getGroupInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1289</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"group '{}'\n"</span><span class="doxyHighlight">,gd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">name</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1290</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"  filename '{}'\n"</span><span class="doxyHighlight">,gd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a25246009588765b59a7e73cc87db2548">filename</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1291</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1292</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ns : gd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#a4fd2089dc1695052ecacfae92e2b914d">namespaceList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1293</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1294</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0, </span><span class="doxyHighlightStringLiteral">"  namespace: {}\n"</span><span class="doxyHighlight">,ns);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1295</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1296</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cs : gd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#a875e577e0208e2abb0cc261be780dcb6">classList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1297</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1298</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0, </span><span class="doxyHighlightStringLiteral">"  class: {}\n"</span><span class="doxyHighlight">,cs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1299</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1300</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;fi : gd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#ac98ead5c7177e4b65948de31a4c459be">fileList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1301</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1302</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0, </span><span class="doxyHighlightStringLiteral">"  file: {}\n"</span><span class="doxyHighlight">,fi);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1303</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1304</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;sg : gd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#acd576264c0c610848fa2d34e3808487f">subgroupList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1305</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1306</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0, </span><span class="doxyHighlightStringLiteral">"  subgroup: {}\n"</span><span class="doxyHighlight">,sg);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1307</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1308</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;pg : gd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#a491a4103f8b699cd1357254403040c95">pageList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1309</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1310</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0, </span><span class="doxyHighlightStringLiteral">"  page: {}\n"</span><span class="doxyHighlight">,pg);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1311</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1312</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1313</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;md : gd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#af08267c179ffb9c4e799ea9a59f8f2a2">members</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1314</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1315</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"  member:\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1316</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"    kind: '{}'\n"</span><span class="doxyHighlight">,md.kind);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1317</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"    name: '{}'\n"</span><span class="doxyHighlight">,md.name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1318</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"    anchor: '{}'\n"</span><span class="doxyHighlight">,md.anchor);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1319</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"    arglist: '{}'\n"</span><span class="doxyHighlight">,md.arglist);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1320</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1321</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1322</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1323</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1324</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//============== PAGES</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1325</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;comp : <a href="#ac75f982d3520a85cd31cabafbbd60dc7">m_tagFileCompounds</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1326</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1327</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (comp.type()==<a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant/#a1a5f5ee04cdc70747f2c031f548d4ed7a193cfc9be3b995831c6af2fea6650e60">TagCompoundVariant::Type::Page</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1328</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1329</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpageinfo">TagPageInfo</a> *pd = comp.getPageInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1330</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"page '{}'\n"</span><span class="doxyHighlight">,pd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">name</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1331</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"  title '{}'\n"</span><span class="doxyHighlight">,pd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpageinfo/#a251988254871e25f8b2a3f041ab0a0d1">title</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1332</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"  filename '{}'\n"</span><span class="doxyHighlight">,pd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a25246009588765b59a7e73cc87db2548">filename</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1333</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1334</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1335</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1336</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//============== DIRS</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1337</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;comp : <a href="#ac75f982d3520a85cd31cabafbbd60dc7">m_tagFileCompounds</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1338</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1339</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (comp.type()==<a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant/#a1a5f5ee04cdc70747f2c031f548d4ed7a3c4e6dbf3e1df93a734d9959bac9ee94">TagCompoundVariant::Type::Dir</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1340</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1341</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagdirinfo">TagDirInfo</a> *dd = comp.getDirInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1342</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1343</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"dir '{}'\n"</span><span class="doxyHighlight">,dd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">name</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1344</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"  path '{}'\n"</span><span class="doxyHighlight">,dd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagdirinfo/#a4cc9abe1c86f41a084f57c364ad56dda">path</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1345</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;fi : dd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagdirinfo/#a949b238cd7c7927e08818bfc1100b20b">fileList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1346</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1347</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0, </span><span class="doxyHighlightStringLiteral">"  file: {}\n"</span><span class="doxyHighlight">,fi);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1348</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1349</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;sd : dd-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagdirinfo/#a54c65e15ae8672ee0c41439891fc6055">subdirList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1350</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1351</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0, </span><span class="doxyHighlightStringLiteral">"  subdir: {}\n"</span><span class="doxyHighlight">,sd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1352</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1353</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1354</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1355</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1356</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>,0,</span><span class="doxyHighlightStringLiteral">"-------------------------\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1357</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ac56edb55f992391df4adef74f54f596f">anonymous_namespace{tagreader.cpp}::TagClassInfo::bases</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant/#a1a5f5ee04cdc70747f2c031f548d4ed7a9bd81329febf6efe22788e03ddeaf0af">anonymous_namespace{tagreader.cpp}::TagCompoundVariant::Class</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo/#ada9ca1bc4c9e47fb4bcbe1d58e35eae7">anonymous_namespace{tagreader.cpp}::TagFileInfo::classList</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#a875e577e0208e2abb0cc261be780dcb6">anonymous_namespace{tagreader.cpp}::TagGroupInfo::classList</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagnamespaceinfo/#abdeeffe4f911bf72f5811d03c04e39a3">anonymous_namespace{tagreader.cpp}::TagNamespaceInfo::classList</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant/#a1a5f5ee04cdc70747f2c031f548d4ed7ad99a604c79ce3c2e76a2f43488d5d4c3">anonymous_namespace{tagreader.cpp}::TagCompoundVariant::Concept</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant/#a1a5f5ee04cdc70747f2c031f548d4ed7a3c4e6dbf3e1df93a734d9959bac9ee94">anonymous_namespace{tagreader.cpp}::TagCompoundVariant::Dir</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant/#a1a5f5ee04cdc70747f2c031f548d4ed7a0b27918290ff5323bea1e3b78a9cf04e">anonymous_namespace{tagreader.cpp}::TagCompoundVariant::File</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagdirinfo/#a949b238cd7c7927e08818bfc1100b20b">anonymous_namespace{tagreader.cpp}::TagDirInfo::fileList</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#ac98ead5c7177e4b65948de31a4c459be">anonymous_namespace{tagreader.cpp}::TagGroupInfo::fileList</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a25246009588765b59a7e73cc87db2548">anonymous_namespace{tagreader.cpp}::TagCompoundInfo::filename</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant/#a1a5f5ee04cdc70747f2c031f548d4ed7a03937134cedab9078be39a77ee3a48a0">anonymous_namespace{tagreader.cpp}::TagCompoundVariant::Group</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo/#abfaa3aacc2e737b6b144cc72ee5755d5">anonymous_namespace{tagreader.cpp}::TagFileInfo::includes</a>, <a href="#ac75f982d3520a85cd31cabafbbd60dc7">m_tagFileCompounds</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#af08267c179ffb9c4e799ea9a59f8f2a2">anonymous_namespace{tagreader.cpp}::TagCompoundInfo::members</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant/#a1a5f5ee04cdc70747f2c031f548d4ed7ae55f75a29310d7b60f7ac1d390c8ae42">anonymous_namespace{tagreader.cpp}::TagCompoundVariant::Module</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">anonymous_namespace{tagreader.cpp}::TagCompoundInfo::name</a>, <a href="/web-doxygen/docs/api/structs/baseinfo/#ae8bba327d477830b4664f9d03b05c97b">BaseInfo::name</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant/#a1a5f5ee04cdc70747f2c031f548d4ed7ab3ba0fe968ce39dcfc6fe8cc0f1b02da">anonymous_namespace{tagreader.cpp}::TagCompoundVariant::Namespace</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo/#a5c3e03594e0c0c25c2810deeb76c1297">anonymous_namespace{tagreader.cpp}::TagFileInfo::namespaceList</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#a4fd2089dc1695052ecacfae92e2b914d">anonymous_namespace{tagreader.cpp}::TagGroupInfo::namespaceList</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant/#a1a5f5ee04cdc70747f2c031f548d4ed7a193cfc9be3b995831c6af2fea6650e60">anonymous_namespace{tagreader.cpp}::TagCompoundVariant::Page</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#a491a4103f8b699cd1357254403040c95">anonymous_namespace{tagreader.cpp}::TagGroupInfo::pageList</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagdirinfo/#a4cc9abe1c86f41a084f57c364ad56dda">anonymous_namespace{tagreader.cpp}::TagDirInfo::path</a>, <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagdirinfo/#a54c65e15ae8672ee0c41439891fc6055">anonymous_namespace{tagreader.cpp}::TagDirInfo::subdirList</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#acd576264c0c610848fa2d34e3808487f">anonymous_namespace{tagreader.cpp}::TagGroupInfo::subgroupList</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a> and <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpageinfo/#a251988254871e25f8b2a3f041ab0a0d1">anonymous_namespace{tagreader.cpp}::TagPageInfo::title</a>.</p>

</div>
</div>

### endAnchor() {#a42aff7a35ce87a4df59d4a05f374f54e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::endAnchor ()</td>
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



<p>Definition at line 877 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a42aff7a35ce87a4df59d4a05f374f54e">877</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a42aff7a35ce87a4df59d4a05f374f54e">endAnchor</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">878</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">879</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>==<a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a463a8e3a1d39b8771600448eff1ab94f">InMember</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">880</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">881</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a>.anchor = <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">882</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">883</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>==<a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a93b6ce3a1981ac7eec5187fe01f13f88">InClass</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">884</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">885</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo">TagClassInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getClassInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">886</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info) info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#a3f52c99f682fa0035584aedfc2ed8dbf">anchor</a> = <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">887</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">888</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">889</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">890</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Unexpected tag 'anchor' found"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">891</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">892</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#a3f52c99f682fa0035584aedfc2ed8dbf">anonymous_namespace{tagreader.cpp}::TagClassInfo::anchor</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a93b6ce3a1981ac7eec5187fe01f13f88">InClass</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a463a8e3a1d39b8771600448eff1ab94f">InMember</a>, <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>, <a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a>, <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a> and <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>.</p>

</div>
</div>

### endAnchorFile() {#a898f929ad250f095d46ce638e8fce78a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::endAnchorFile ()</td>
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



<p>Definition at line 918 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a898f929ad250f095d46ce638e8fce78a">918</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a898f929ad250f095d46ce638e8fce78a">endAnchorFile</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">919</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">920</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>==<a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a463a8e3a1d39b8771600448eff1ab94f">InMember</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">921</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">922</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a>.anchorFile = <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">923</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">924</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">925</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">926</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Unexpected tag 'anchorfile' found"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">927</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">928</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a463a8e3a1d39b8771600448eff1ab94f">InMember</a>, <a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a>, <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a> and <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>.</p>

</div>
</div>

### endArglist() {#a005718bfd790617c0cf8b3ab0c86a6c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::endArglist ()</td>
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



<p>Definition at line 930 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a005718bfd790617c0cf8b3ab0c86a6c3">930</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a005718bfd790617c0cf8b3ab0c86a6c3">endArglist</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">931</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">932</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>==<a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a463a8e3a1d39b8771600448eff1ab94f">InMember</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">933</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">934</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a>.arglist = <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">935</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">936</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">937</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">938</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Unexpected tag 'arglist' found"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">939</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">940</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a463a8e3a1d39b8771600448eff1ab94f">InMember</a>, <a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a>, <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a> and <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>.</p>

</div>
</div>

### endBase() {#a1ac7de66e90ffbf93cd637c67c7cc76c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::endBase ()</td>
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



<p>Definition at line 779 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1ac7de66e90ffbf93cd637c67c7cc76c">779</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1ac7de66e90ffbf93cd637c67c7cc76c">endBase</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">780</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">781</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo">TagClassInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getClassInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">782</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>==<a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a93b6ce3a1981ac7eec5187fe01f13f88">InClass</a> &amp;&amp; info)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">783</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">784</span><span class="doxyLineContent"><span class="doxyHighlight">        info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ac56edb55f992391df4adef74f54f596f">bases</a>.back().name = <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">785</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">786</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">787</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">788</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Unexpected tag 'base' found"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">789</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">790</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ac56edb55f992391df4adef74f54f596f">anonymous_namespace{tagreader.cpp}::TagClassInfo::bases</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a93b6ce3a1981ac7eec5187fe01f13f88">InClass</a>, <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>, <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a> and <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>.</p>

</div>
</div>

### endClangId() {#ab27d1e74556a11f12e2d6a3b0dfa1225}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::endClangId ()</td>
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



<p>Definition at line 894 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab27d1e74556a11f12e2d6a3b0dfa1225">894</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab27d1e74556a11f12e2d6a3b0dfa1225">endClangId</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">895</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">896</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>==<a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a463a8e3a1d39b8771600448eff1ab94f">InMember</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">897</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">898</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a>.clangId = <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">899</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">900</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>==<a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a93b6ce3a1981ac7eec5187fe01f13f88">InClass</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">901</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">902</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo">TagClassInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getClassInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">903</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info) info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ab014917f432e45612c083450553a2726">clangId</a> =  <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">904</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">905</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>==<a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85aaa2eff2017752b6a0d1a8b902f99b53d">InNamespace</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">906</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">907</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagnamespaceinfo">TagNamespaceInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getNamespaceInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">908</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info) info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagnamespaceinfo/#a0ff6b0d4cff44254154e3c249cecf903">clangId</a> = <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">909</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">910</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">911</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">912</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Unexpected tag 'clangid' found"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">913</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">914</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ab014917f432e45612c083450553a2726">anonymous_namespace{tagreader.cpp}::TagClassInfo::clangId</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagnamespaceinfo/#a0ff6b0d4cff44254154e3c249cecf903">anonymous_namespace{tagreader.cpp}::TagNamespaceInfo::clangId</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a93b6ce3a1981ac7eec5187fe01f13f88">InClass</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a463a8e3a1d39b8771600448eff1ab94f">InMember</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85aaa2eff2017752b6a0d1a8b902f99b53d">InNamespace</a>, <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>, <a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a>, <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a> and <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>.</p>

</div>
</div>

### endClass() {#ab0af5855a848b20e3136d941d7840732}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::endClass ()</td>
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



<p>Definition at line 516 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab0af5855a848b20e3136d941d7840732">516</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab0af5855a848b20e3136d941d7840732">endClass</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">517</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">518</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a93b6ce3a1981ac7eec5187fe01f13f88">InClass</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">521</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo">TagClassInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getClassInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info) info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#a91f4902e8759c8a1aad1162893ad1132">classList</a>.push_back(<a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">525</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">526</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a8153ea8cb5da0e11193e8780e0235ecd">InFile</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">527</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">528</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo">TagFileInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getFileInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">529</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info) info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo/#ada9ca1bc4c9e47fb4bcbe1d58e35eae7">classList</a>.push_back(<a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">530</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">531</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">532</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85aaa2eff2017752b6a0d1a8b902f99b53d">InNamespace</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">533</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">534</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagnamespaceinfo">TagNamespaceInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getNamespaceInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">535</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info) info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagnamespaceinfo/#abdeeffe4f911bf72f5811d03c04e39a3">classList</a>.push_back(<a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">536</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">537</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">538</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">InGroup</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">539</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">540</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo">TagGroupInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getGroupInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">541</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info) info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#a875e577e0208e2abb0cc261be780dcb6">classList</a>.push_back(<a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">542</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">543</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">544</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a10248ae7318932ab6199589d50836c37">InPackage</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">545</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">546</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpackageinfo">TagPackageInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getPackageInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">547</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info) info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpackageinfo/#a6e6f7e303a13f4d757e0146ad9468717">classList</a>.push_back(<a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">548</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">549</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">550</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">551</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Unexpected tag 'class' found"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">552</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">553</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">554</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#a91f4902e8759c8a1aad1162893ad1132">anonymous_namespace{tagreader.cpp}::TagClassInfo::classList</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo/#ada9ca1bc4c9e47fb4bcbe1d58e35eae7">anonymous_namespace{tagreader.cpp}::TagFileInfo::classList</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#a875e577e0208e2abb0cc261be780dcb6">anonymous_namespace{tagreader.cpp}::TagGroupInfo::classList</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagnamespaceinfo/#abdeeffe4f911bf72f5811d03c04e39a3">anonymous_namespace{tagreader.cpp}::TagNamespaceInfo::classList</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpackageinfo/#a6e6f7e303a13f4d757e0146ad9468717">anonymous_namespace{tagreader.cpp}::TagPackageInfo::classList</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a93b6ce3a1981ac7eec5187fe01f13f88">InClass</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a8153ea8cb5da0e11193e8780e0235ecd">InFile</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">InGroup</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85aaa2eff2017752b6a0d1a8b902f99b53d">InNamespace</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a10248ae7318932ab6199589d50836c37">InPackage</a>, <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>, <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a> and <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>.</p>

</div>
</div>

### endCompound() {#a3e0857519c95a2ab4f2649588f52b244}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::endCompound ()</td>
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



<p>Definition at line 361 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3e0857519c95a2ab4f2649588f52b244">361</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3e0857519c95a2ab4f2649588f52b244">endCompound</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a93b6ce3a1981ac7eec5187fe01f13f88">InClass</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">366</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ab50fef501e869e3a88c64c5dd7b49d0b">InConcept</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">367</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a8153ea8cb5da0e11193e8780e0235ecd">InFile</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85aaa2eff2017752b6a0d1a8b902f99b53d">InNamespace</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">InGroup</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ac57db6ff719aec7e364b0823d5c231db">InPage</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85acf8144d7c837a76fe6497c8158c6b973">InDir</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a31219fa12b60084e1f85db1eeffe4697">InModule</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a10248ae7318932ab6199589d50836c37">InPackage</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#ac75f982d3520a85cd31cabafbbd60dc7">m_tagFileCompounds</a>.push_back(std::move(<a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"tag 'compound' was not expected!"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a93b6ce3a1981ac7eec5187fe01f13f88">InClass</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ab50fef501e869e3a88c64c5dd7b49d0b">InConcept</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85acf8144d7c837a76fe6497c8158c6b973">InDir</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a8153ea8cb5da0e11193e8780e0235ecd">InFile</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">InGroup</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a31219fa12b60084e1f85db1eeffe4697">InModule</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85aaa2eff2017752b6a0d1a8b902f99b53d">InNamespace</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a10248ae7318932ab6199589d50836c37">InPackage</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ac57db6ff719aec7e364b0823d5c231db">InPage</a>, <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>, <a href="#ac75f982d3520a85cd31cabafbbd60dc7">m_tagFileCompounds</a> and <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>.</p>

</div>
</div>

### endConcept() {#a88c616e8f2d519406f88102cf9913811}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::endConcept ()</td>
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



<p>Definition at line 556 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a88c616e8f2d519406f88102cf9913811">556</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a88c616e8f2d519406f88102cf9913811">endConcept</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">557</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">558</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">559</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">560</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85aaa2eff2017752b6a0d1a8b902f99b53d">InNamespace</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">561</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagnamespaceinfo">TagNamespaceInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getNamespaceInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">563</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info) info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagnamespaceinfo/#aa359781ecb15bfccb8ed538eface4a68">conceptList</a>.push_back(<a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">566</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a8153ea8cb5da0e11193e8780e0235ecd">InFile</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">567</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">568</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo">TagFileInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getFileInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">569</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info) info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo/#a22fa1ae1f73c523e66ffd0abd6483aa6">conceptList</a>.push_back(<a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">570</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">571</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">572</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">InGroup</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo">TagGroupInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getGroupInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">575</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info) info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#a24159b7f6ebc47ac361d96f5dd45bff6">conceptList</a>.push_back(<a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">576</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">577</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">578</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Unexpected tag 'concept' found"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo/#a22fa1ae1f73c523e66ffd0abd6483aa6">anonymous_namespace{tagreader.cpp}::TagFileInfo::conceptList</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#a24159b7f6ebc47ac361d96f5dd45bff6">anonymous_namespace{tagreader.cpp}::TagGroupInfo::conceptList</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagnamespaceinfo/#aa359781ecb15bfccb8ed538eface4a68">anonymous_namespace{tagreader.cpp}::TagNamespaceInfo::conceptList</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a8153ea8cb5da0e11193e8780e0235ecd">InFile</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">InGroup</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85aaa2eff2017752b6a0d1a8b902f99b53d">InNamespace</a>, <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>, <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a> and <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>.</p>

</div>
</div>

### endDir() {#af120fd7d4ed4df2d800e4a531152728d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::endDir ()</td>
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



<p>Definition at line 682 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af120fd7d4ed4df2d800e4a531152728d">682</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af120fd7d4ed4df2d800e4a531152728d">endDir</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">683</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">684</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">685</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">686</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85acf8144d7c837a76fe6497c8158c6b973">InDir</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">687</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">688</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagdirinfo">TagDirInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getDirInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">689</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info) info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagdirinfo/#a54c65e15ae8672ee0c41439891fc6055">subdirList</a>.push_back(<a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">690</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">691</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">692</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">693</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Unexpected tag 'dir' found"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">694</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">696</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85acf8144d7c837a76fe6497c8158c6b973">InDir</a>, <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>, <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>, <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a> and <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagdirinfo/#a54c65e15ae8672ee0c41439891fc6055">anonymous_namespace{tagreader.cpp}::TagDirInfo::subdirList</a>.</p>

</div>
</div>

### endDocAnchor() {#a5b2c9b8ab174e898f87b90803529766c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::endDocAnchor ()</td>
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



<p>Definition at line 469 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5b2c9b8ab174e898f87b90803529766c">469</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5b2c9b8ab174e898f87b90803529766c">endDocAnchor</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// Check whether or not the tag is automatically generate, in that case ignore the tag.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a93b6ce3a1981ac7eec5187fe01f13f88">InClass</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ab50fef501e869e3a88c64c5dd7b49d0b">InConcept</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a8153ea8cb5da0e11193e8780e0235ecd">InFile</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85aaa2eff2017752b6a0d1a8b902f99b53d">InNamespace</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">InGroup</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">479</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ac57db6ff719aec7e364b0823d5c231db">InPage</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a463a8e3a1d39b8771600448eff1ab94f">InMember</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a10248ae7318932ab6199589d50836c37">InPackage</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85acf8144d7c837a76fe6497c8158c6b973">InDir</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a31219fa12b60084e1f85db1eeffe4697">InModule</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/anchorgenerator/#a8d3ac23f544142e96ccf645831743432">AnchorGenerator::looksGenerated</a>(<a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>.str())) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Unexpected tag 'docanchor' found"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a93b6ce3a1981ac7eec5187fe01f13f88">InClass</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ab50fef501e869e3a88c64c5dd7b49d0b">InConcept</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a8153ea8cb5da0e11193e8780e0235ecd">InFile</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85aaa2eff2017752b6a0d1a8b902f99b53d">InNamespace</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">InGroup</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ac57db6ff719aec7e364b0823d5c231db">InPage</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a10248ae7318932ab6199589d50836c37">InPackage</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85acf8144d7c837a76fe6497c8158c6b973">InDir</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a31219fa12b60084e1f85db1eeffe4697">InModule</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo">TagCompoundInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getCompoundInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">              info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#abd7c06610979d5c6078dbf666c4358b5">docAnchors</a>.emplace_back(<a href="#a19ed33b56774430bad0811dbb24aa38d">m_fileName</a>,<a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>,<a href="#a75e30c8c85ae1460b55b1585e9386693">m_title</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a463a8e3a1d39b8771600448eff1ab94f">InMember</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a>.docAnchors.emplace_back(<a href="#a19ed33b56774430bad0811dbb24aa38d">m_fileName</a>,<a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>,<a href="#a75e30c8c85ae1460b55b1585e9386693">m_title</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// will not be reached</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">513</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">514</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#abd7c06610979d5c6078dbf666c4358b5">anonymous_namespace{tagreader.cpp}::TagCompoundInfo::docAnchors</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a93b6ce3a1981ac7eec5187fe01f13f88">InClass</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ab50fef501e869e3a88c64c5dd7b49d0b">InConcept</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85acf8144d7c837a76fe6497c8158c6b973">InDir</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a8153ea8cb5da0e11193e8780e0235ecd">InFile</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">InGroup</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a463a8e3a1d39b8771600448eff1ab94f">InMember</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a31219fa12b60084e1f85db1eeffe4697">InModule</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85aaa2eff2017752b6a0d1a8b902f99b53d">InNamespace</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a10248ae7318932ab6199589d50836c37">InPackage</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ac57db6ff719aec7e364b0823d5c231db">InPage</a>, <a href="/web-doxygen/docs/api/classes/anchorgenerator/#a8d3ac23f544142e96ccf645831743432">AnchorGenerator::looksGenerated</a>, <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>, <a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a>, <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>, <a href="#a19ed33b56774430bad0811dbb24aa38d">m_fileName</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>, <a href="#a75e30c8c85ae1460b55b1585e9386693">m_title</a> and <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>.</p>

</div>
</div>

### endElement() {#a3e01aed32d5dbf43b922e4152b65b54f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::endElement (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 349 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3e01aed32d5dbf43b922e4152b65b54f">1134</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3e01aed32d5dbf43b922e4152b65b54f">TagFileParser::endElement</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1135</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1136</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("endElement '%s'\n",qPrint(name));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1137</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="/web-doxygen/docs/api/namespaces/anonymous-tagreader-cpp-/#ac4f239fedcca27a83995d7b9a02b683d">g_elementHandlers</a>.find(name.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1138</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=std::end(<a href="/web-doxygen/docs/api/namespaces/anonymous-tagreader-cpp-/#ac4f239fedcca27a83995d7b9a02b683d">g_elementHandlers</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1139</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1140</span><span class="doxyLineContent"><span class="doxyHighlight">    it-&gt;second.endCb(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1141</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1142</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1143</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1144</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Unknown end tag '{}' found!"</span><span class="doxyHighlight">,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1145</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1146</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/namespaces/anonymous-tagreader-cpp-/#ac4f239fedcca27a83995d7b9a02b683d">anonymous_namespace{tagreader.cpp}::g_elementHandlers</a>, <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>

</div>
</div>

### endEnumValue() {#a06a8a71d6e6d9f8e93cee750e2faa0ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::endEnumValue ()</td>
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



<p>Definition at line 457 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a06a8a71d6e6d9f8e93cee750e2faa0ef">457</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a06a8a71d6e6d9f8e93cee750e2faa0ef">endEnumValue</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aa13860af0001daf87f69281389f3c101">m_curEnumValue</a>.name = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(<a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a> = <a href="#ada7baee04d5b524d2d3b2c4d2207cf6d">m_stateStack</a>.top();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ada7baee04d5b524d2d3b2c4d2207cf6d">m_stateStack</a>.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>==<a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a463a8e3a1d39b8771600448eff1ab94f">InMember</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a>.enumValues.push_back(<a href="#aa13860af0001daf87f69281389f3c101">m_curEnumValue</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aa13860af0001daf87f69281389f3c101">m_curEnumValue</a>=<a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagenumvalueinfo">TagEnumValueInfo</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a463a8e3a1d39b8771600448eff1ab94f">InMember</a>, <a href="#aa13860af0001daf87f69281389f3c101">m_curEnumValue</a>, <a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a>, <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>, <a href="#ada7baee04d5b524d2d3b2c4d2207cf6d">m_stateStack</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>.</p>

</div>
</div>

### endFile() {#a34e5a973da1491d711704a2ee6ee8ae0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::endFile ()</td>
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



<p>Definition at line 628 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a34e5a973da1491d711704a2ee6ee8ae0">628</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a34e5a973da1491d711704a2ee6ee8ae0">endFile</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">629</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">630</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">631</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">632</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">InGroup</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">633</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">634</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo">TagGroupInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getGroupInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">635</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info) info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#ac98ead5c7177e4b65948de31a4c459be">fileList</a>.push_back(<a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">636</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">637</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">638</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85acf8144d7c837a76fe6497c8158c6b973">InDir</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">639</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">640</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagdirinfo">TagDirInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getDirInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">641</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info) info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagdirinfo/#a949b238cd7c7927e08818bfc1100b20b">fileList</a>.push_back(<a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">642</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">643</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">644</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">645</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Unexpected tag 'file' found"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">646</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">647</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">648</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagdirinfo/#a949b238cd7c7927e08818bfc1100b20b">anonymous_namespace{tagreader.cpp}::TagDirInfo::fileList</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#ac98ead5c7177e4b65948de31a4c459be">anonymous_namespace{tagreader.cpp}::TagGroupInfo::fileList</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85acf8144d7c837a76fe6497c8158c6b973">InDir</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">InGroup</a>, <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>, <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a> and <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>.</p>

</div>
</div>

### endFilename() {#acb8e913e38db3f6aa9c1bbb9a641a17f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::endFilename ()</td>
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



<p>Definition at line 831 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acb8e913e38db3f6aa9c1bbb9a641a17f">831</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acb8e913e38db3f6aa9c1bbb9a641a17f">endFilename</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">832</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">833</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">834</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">835</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a93b6ce3a1981ac7eec5187fe01f13f88">InClass</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">836</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ab50fef501e869e3a88c64c5dd7b49d0b">InConcept</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">837</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85aaa2eff2017752b6a0d1a8b902f99b53d">InNamespace</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">838</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a8153ea8cb5da0e11193e8780e0235ecd">InFile</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">839</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">InGroup</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">840</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ac57db6ff719aec7e364b0823d5c231db">InPage</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">841</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a10248ae7318932ab6199589d50836c37">InPackage</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">842</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85acf8144d7c837a76fe6497c8158c6b973">InDir</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">843</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a31219fa12b60084e1f85db1eeffe4697">InModule</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">844</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">845</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo">TagCompoundInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getCompoundInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">846</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info) info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a25246009588765b59a7e73cc87db2548">filename</a> = <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">847</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">848</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">849</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">850</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Unexpected tag 'filename' found"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">851</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">852</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">853</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a25246009588765b59a7e73cc87db2548">anonymous_namespace{tagreader.cpp}::TagCompoundInfo::filename</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a93b6ce3a1981ac7eec5187fe01f13f88">InClass</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ab50fef501e869e3a88c64c5dd7b49d0b">InConcept</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85acf8144d7c837a76fe6497c8158c6b973">InDir</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a8153ea8cb5da0e11193e8780e0235ecd">InFile</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">InGroup</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a31219fa12b60084e1f85db1eeffe4697">InModule</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85aaa2eff2017752b6a0d1a8b902f99b53d">InNamespace</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a10248ae7318932ab6199589d50836c37">InPackage</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ac57db6ff719aec7e364b0823d5c231db">InPage</a>, <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>, <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a> and <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>.</p>

</div>
</div>

### endIgnoreElement() {#a06ded03287ca59344a1d300d78789abe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::endIgnoreElement ()</td>
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



<p>Definition at line 981 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a06ded03287ca59344a1d300d78789abe">981</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a06ded03287ca59344a1d300d78789abe">endIgnoreElement</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">982</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">983</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>

</div>
</div>

### endIncludes() {#a18f64ce17ad437b8675f4bd7b9f8a974}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::endIncludes ()</td>
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



<p>Definition at line 804 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a18f64ce17ad437b8675f4bd7b9f8a974">804</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a18f64ce17ad437b8675f4bd7b9f8a974">endIncludes</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">805</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">806</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#abac57def474d6cfc6844a2c62c81b23e">m_curIncludes</a>.text = <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">807</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo">TagFileInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getFileInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">808</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>==<a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a8153ea8cb5da0e11193e8780e0235ecd">InFile</a> &amp;&amp; info)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">809</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">810</span><span class="doxyLineContent"><span class="doxyHighlight">        info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo/#abfaa3aacc2e737b6b144cc72ee5755d5">includes</a>.push_back(<a href="#abac57def474d6cfc6844a2c62c81b23e">m_curIncludes</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">811</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">812</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">813</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">814</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Unexpected tag 'includes' found"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">815</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">816</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo/#abfaa3aacc2e737b6b144cc72ee5755d5">anonymous_namespace{tagreader.cpp}::TagFileInfo::includes</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a8153ea8cb5da0e11193e8780e0235ecd">InFile</a>, <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>, <a href="#abac57def474d6cfc6844a2c62c81b23e">m_curIncludes</a>, <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a> and <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>.</p>

</div>
</div>

### endMember() {#afce64693b86203b0106f25a6697a8076}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::endMember ()</td>
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



<p>Definition at line 414 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afce64693b86203b0106f25a6697a8076">414</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afce64693b86203b0106f25a6697a8076">endMember</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">415</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a> = <a href="#ada7baee04d5b524d2d3b2c4d2207cf6d">m_stateStack</a>.top();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">417</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ada7baee04d5b524d2d3b2c4d2207cf6d">m_stateStack</a>.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">418</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">419</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a93b6ce3a1981ac7eec5187fe01f13f88">InClass</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">421</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a8153ea8cb5da0e11193e8780e0235ecd">InFile</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">422</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85aaa2eff2017752b6a0d1a8b902f99b53d">InNamespace</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">423</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">InGroup</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">424</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a10248ae7318932ab6199589d50836c37">InPackage</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">425</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">426</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo">TagCompoundInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getCompoundInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">427</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">428</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">429</span><span class="doxyLineContent"><span class="doxyHighlight">              info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#af08267c179ffb9c4e799ea9a59f8f2a2">members</a>.push_back(<a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">430</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">431</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">432</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">433</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">434</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Unexpected tag 'member' found"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">435</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a93b6ce3a1981ac7eec5187fe01f13f88">InClass</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a8153ea8cb5da0e11193e8780e0235ecd">InFile</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">InGroup</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85aaa2eff2017752b6a0d1a8b902f99b53d">InNamespace</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a10248ae7318932ab6199589d50836c37">InPackage</a>, <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>, <a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>, <a href="#ada7baee04d5b524d2d3b2c4d2207cf6d">m_stateStack</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#af08267c179ffb9c4e799ea9a59f8f2a2">anonymous_namespace{tagreader.cpp}::TagCompoundInfo::members</a> and <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>.</p>

</div>
</div>

### endModule() {#aa0c63ea4440394d9c1089cc804f6b3cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::endModule ()</td>
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



<p>Definition at line 584 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa0c63ea4440394d9c1089cc804f6b3cb">584</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa0c63ea4440394d9c1089cc804f6b3cb">endModule</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">586</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">587</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">InGroup</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">589</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">590</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo">TagGroupInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getGroupInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">591</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info) info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#ac3c6fd89407442477963e1214db6724b">moduleList</a>.push_back(<a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">592</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">593</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Unexpected tag 'module' found"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">InGroup</a>, <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>, <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#ac3c6fd89407442477963e1214db6724b">anonymous_namespace{tagreader.cpp}::TagGroupInfo::moduleList</a> and <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>.</p>

</div>
</div>

### endName() {#af5d579a5b02bb8153e8be2ffe25d2b90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::endName ()</td>
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



<p>Definition at line 722 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af5d579a5b02bb8153e8be2ffe25d2b90">722</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af5d579a5b02bb8153e8be2ffe25d2b90">endName</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">723</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">724</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">725</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">726</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a93b6ce3a1981ac7eec5187fe01f13f88">InClass</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">727</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ab50fef501e869e3a88c64c5dd7b49d0b">InConcept</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">728</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a8153ea8cb5da0e11193e8780e0235ecd">InFile</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">729</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85aaa2eff2017752b6a0d1a8b902f99b53d">InNamespace</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">730</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">InGroup</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">731</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ac57db6ff719aec7e364b0823d5c231db">InPage</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">732</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85acf8144d7c837a76fe6497c8158c6b973">InDir</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">733</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a10248ae7318932ab6199589d50836c37">InPackage</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">734</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a31219fa12b60084e1f85db1eeffe4697">InModule</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">735</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">736</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo">TagCompoundInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getCompoundInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">737</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info) info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">name</a> = <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">738</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">739</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">740</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a463a8e3a1d39b8771600448eff1ab94f">InMember</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">741</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a>.name = <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">742</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">743</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">744</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Unexpected tag 'name' found"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">745</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">746</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">747</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a93b6ce3a1981ac7eec5187fe01f13f88">InClass</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ab50fef501e869e3a88c64c5dd7b49d0b">InConcept</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85acf8144d7c837a76fe6497c8158c6b973">InDir</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a8153ea8cb5da0e11193e8780e0235ecd">InFile</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">InGroup</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a463a8e3a1d39b8771600448eff1ab94f">InMember</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a31219fa12b60084e1f85db1eeffe4697">InModule</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85aaa2eff2017752b6a0d1a8b902f99b53d">InNamespace</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a10248ae7318932ab6199589d50836c37">InPackage</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ac57db6ff719aec7e364b0823d5c231db">InPage</a>, <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>, <a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a>, <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">anonymous_namespace{tagreader.cpp}::TagCompoundInfo::name</a> and <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>.</p>

</div>
</div>

### endNamespace() {#a5f364b44aa47f45ead81e1892359c3ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::endNamespace ()</td>
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



<p>Definition at line 600 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5f364b44aa47f45ead81e1892359c3ee">600</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5f364b44aa47f45ead81e1892359c3ee">endNamespace</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">601</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">602</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">603</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">604</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85aaa2eff2017752b6a0d1a8b902f99b53d">InNamespace</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagnamespaceinfo">TagNamespaceInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getNamespaceInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info) info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagnamespaceinfo/#acd449b40f1afca3839ebdd0e12a461df">namespaceList</a>.push_back(<a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a8153ea8cb5da0e11193e8780e0235ecd">InFile</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo">TagFileInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getFileInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">613</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info) info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo/#a5c3e03594e0c0c25c2810deeb76c1297">namespaceList</a>.push_back(<a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">614</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">615</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">616</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">InGroup</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">618</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo">TagGroupInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getGroupInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">619</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info) info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#a4fd2089dc1695052ecacfae92e2b914d">namespaceList</a>.push_back(<a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">620</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">621</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">622</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">623</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Unexpected tag 'namespace' found"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">624</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">625</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">626</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a8153ea8cb5da0e11193e8780e0235ecd">InFile</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">InGroup</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85aaa2eff2017752b6a0d1a8b902f99b53d">InNamespace</a>, <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>, <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo/#a5c3e03594e0c0c25c2810deeb76c1297">anonymous_namespace{tagreader.cpp}::TagFileInfo::namespaceList</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#a4fd2089dc1695052ecacfae92e2b914d">anonymous_namespace{tagreader.cpp}::TagGroupInfo::namespaceList</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagnamespaceinfo/#acd449b40f1afca3839ebdd0e12a461df">anonymous_namespace{tagreader.cpp}::TagNamespaceInfo::namespaceList</a> and <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>.</p>

</div>
</div>

### endPage() {#a40b954bb215265f9d331f673102f8e11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::endPage ()</td>
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



<p>Definition at line 650 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a40b954bb215265f9d331f673102f8e11">650</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a40b954bb215265f9d331f673102f8e11">endPage</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">651</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">652</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">653</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">654</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">InGroup</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">655</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">656</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo">TagGroupInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getGroupInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">657</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info) info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#ac98ead5c7177e4b65948de31a4c459be">fileList</a>.push_back(<a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">658</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">659</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">660</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">661</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Unexpected tag 'page' found"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">662</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">663</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">664</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#ac98ead5c7177e4b65948de31a4c459be">anonymous_namespace{tagreader.cpp}::TagGroupInfo::fileList</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">InGroup</a>, <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>, <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a> and <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>.</p>

</div>
</div>

### endPath() {#a8020f9f5e883fd98854ac72e4e6e776d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::endPath ()</td>
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



<p>Definition at line 855 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8020f9f5e883fd98854ac72e4e6e776d">855</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8020f9f5e883fd98854ac72e4e6e776d">endPath</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">856</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">857</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">858</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">859</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a8153ea8cb5da0e11193e8780e0235ecd">InFile</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">860</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">861</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo">TagFileInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getFileInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">862</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info) info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo/#a156c071cac61ccf562a2b9d2fed30a95">path</a> = <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">863</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">864</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">865</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85acf8144d7c837a76fe6497c8158c6b973">InDir</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">866</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">867</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagdirinfo">TagDirInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getDirInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">868</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info) info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagdirinfo/#a4cc9abe1c86f41a084f57c364ad56dda">path</a> = <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">869</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">870</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">871</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">872</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Unexpected tag 'path' found"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">873</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">874</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">875</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85acf8144d7c837a76fe6497c8158c6b973">InDir</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a8153ea8cb5da0e11193e8780e0235ecd">InFile</a>, <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>, <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>, <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagdirinfo/#a4cc9abe1c86f41a084f57c364ad56dda">anonymous_namespace{tagreader.cpp}::TagDirInfo::path</a> and <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo/#a156c071cac61ccf562a2b9d2fed30a95">anonymous_namespace{tagreader.cpp}::TagFileInfo::path</a>.</p>

</div>
</div>

### endSubgroup() {#ab01b451a3fc33322e98c40bd5cca5878}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::endSubgroup ()</td>
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



<p>Definition at line 964 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab01b451a3fc33322e98c40bd5cca5878">964</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab01b451a3fc33322e98c40bd5cca5878">endSubgroup</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">965</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">966</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>==<a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">InGroup</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">967</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">968</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo">TagGroupInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getGroupInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">969</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info) info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#acd576264c0c610848fa2d34e3808487f">subgroupList</a>.push_back(<a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">970</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">971</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">972</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">973</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Unexpected tag 'subgroup' found"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">974</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">975</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">InGroup</a>, <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>, <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>, <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a> and <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#acd576264c0c610848fa2d34e3808487f">anonymous_namespace{tagreader.cpp}::TagGroupInfo::subgroupList</a>.</p>

</div>
</div>

### endSubpage() {#a6fd29da85de1ed3faf625ee0d27122ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::endSubpage ()</td>
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



<p>Definition at line 666 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6fd29da85de1ed3faf625ee0d27122ae">666</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6fd29da85de1ed3faf625ee0d27122ae">endSubpage</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">668</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">670</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ac57db6ff719aec7e364b0823d5c231db">InPage</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">671</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">672</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpageinfo">TagPageInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getPageInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">673</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info) info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpageinfo/#ac15a5ec4694c2839b96398815b523ad7">subpages</a>.push_back(<a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">674</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">675</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">676</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">677</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Unexpected tag 'subpage' found"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">678</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">679</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">680</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ac57db6ff719aec7e364b0823d5c231db">InPage</a>, <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>, <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>, <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a> and <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpageinfo/#ac15a5ec4694c2839b96398815b523ad7">anonymous_namespace{tagreader.cpp}::TagPageInfo::subpages</a>.</p>

</div>
</div>

### endTemplateArg() {#a942847def781fe793b9bf3b1a7179c3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::endTemplateArg ()</td>
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



<p>Definition at line 818 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a942847def781fe793b9bf3b1a7179c3f">818</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a942847def781fe793b9bf3b1a7179c3f">endTemplateArg</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">819</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">820</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo">TagClassInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getClassInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">821</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>==<a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a93b6ce3a1981ac7eec5187fe01f13f88">InClass</a> &amp;&amp; info)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">822</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">823</span><span class="doxyLineContent"><span class="doxyHighlight">        info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#a747b8b8d3b89a1e4744e354c4de534ee">templateArguments</a>.push_back(<a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">824</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">825</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">826</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">827</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Unexpected tag 'templarg' found"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">828</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">829</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a93b6ce3a1981ac7eec5187fe01f13f88">InClass</a>, <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>, <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>, <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a> and <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#a747b8b8d3b89a1e4744e354c4de534ee">anonymous_namespace{tagreader.cpp}::TagClassInfo::templateArguments</a>.</p>

</div>
</div>

### endTitle() {#aa6e06a88bac03298d1b7b1d960786089}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::endTitle ()</td>
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



<p>Definition at line 942 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa6e06a88bac03298d1b7b1d960786089">942</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa6e06a88bac03298d1b7b1d960786089">endTitle</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">943</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">944</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">945</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">946</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">InGroup</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">947</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">948</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo">TagGroupInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getGroupInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">949</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info) info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#ac3b6e212c0c08a615327124433781ad2">title</a> = <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">950</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">951</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">952</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ac57db6ff719aec7e364b0823d5c231db">InPage</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">953</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">954</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpageinfo">TagPageInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getPageInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">955</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info) info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpageinfo/#a251988254871e25f8b2a3f041ab0a0d1">title</a> = <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">956</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">957</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">958</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">959</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Unexpected tag 'title' found"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">960</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">961</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">962</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a0f3cb97fa8ce0ce8b07863c65b5a0d3a">InGroup</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ac57db6ff719aec7e364b0823d5c231db">InPage</a>, <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>, <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>, <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#ac3b6e212c0c08a615327124433781ad2">anonymous_namespace{tagreader.cpp}::TagGroupInfo::title</a> and <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpageinfo/#a251988254871e25f8b2a3f041ab0a0d1">anonymous_namespace{tagreader.cpp}::TagPageInfo::title</a>.</p>

</div>
</div>

### endType() {#a1f6885619a9e437468650af93b8f05f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::endType ()</td>
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



<p>Definition at line 710 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1f6885619a9e437468650af93b8f05f3">710</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1f6885619a9e437468650af93b8f05f3">endType</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">711</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">712</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>==<a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a463a8e3a1d39b8771600448eff1ab94f">InMember</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">713</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">714</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a>.type = <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">715</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">716</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">717</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">718</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Unexpected tag 'type' found"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">719</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">720</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a463a8e3a1d39b8771600448eff1ab94f">InMember</a>, <a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a>, <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a> and <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>.</p>

</div>
</div>

### error() {#a6bd1e95f8dd3062e45ad9c14ef6ff3bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::error (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, int lineNr, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; msg)</td>
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



<p>Definition at line 351 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6bd1e95f8dd3062e45ad9c14ef6ff3bc">351</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6bd1e95f8dd3062e45ad9c14ef6ff3bc">error</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(fileName,lineNr,</span><span class="doxyHighlightStringLiteral">"{}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.</p>

</div>
</div>

### setDocumentLocator() {#a662591474cf5ed7adce79a42d49736af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::setDocumentLocator (const <a href="/web-doxygen/docs/api/classes/xmllocator">XMLLocator</a> * locator)</td>
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



<p>Definition at line 338 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a662591474cf5ed7adce79a42d49736af">338</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a662591474cf5ed7adce79a42d49736af">setDocumentLocator</a> ( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmllocator">XMLLocator</a> * locator )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a560587cbf60c107e9bae7e205fd6ef50">m_locator</a> = locator;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a560587cbf60c107e9bae7e205fd6ef50">m_locator</a>.</p>

</div>
</div>

### startBase() {#a6927f64d6b3e45878b5102852e1e2fac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::startBase (const <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp; attrib)</td>
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



<p>Definition at line 749 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6927f64d6b3e45878b5102852e1e2fac">749</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6927f64d6b3e45878b5102852e1e2fac">startBase</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a>&amp; attrib )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">750</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">751</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">752</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo">TagClassInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getClassInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">753</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>==<a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a93b6ce3a1981ac7eec5187fe01f13f88">InClass</a> &amp;&amp; info)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">754</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">755</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> protStr = <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>(attrib,</span><span class="doxyHighlightStringLiteral">"protection"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">756</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> virtStr = <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>(attrib,</span><span class="doxyHighlightStringLiteral">"virtualness"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">757</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> prot = Protection::Public;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">758</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/types-h/#ab16236bdd10ddf4d73a9847350f0017e">Specifier</a>  virt = Specifier::Normal;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">759</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (protStr==</span><span class="doxyHighlightStringLiteral">"protected"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">760</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">761</span><span class="doxyLineContent"><span class="doxyHighlight">          prot = Protection::Protected;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">762</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">763</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (protStr==</span><span class="doxyHighlightStringLiteral">"private"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">764</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">765</span><span class="doxyLineContent"><span class="doxyHighlight">          prot = Protection::Private;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">766</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">767</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (virtStr==</span><span class="doxyHighlightStringLiteral">"virtual"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">768</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">769</span><span class="doxyLineContent"><span class="doxyHighlight">          virt = Specifier::Virtual;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">770</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">771</span><span class="doxyLineContent"><span class="doxyHighlight">        info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ac56edb55f992391df4adef74f54f596f">bases</a>.emplace_back(<a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>,prot,virt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">772</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">773</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">774</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">775</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Unexpected tag 'base' found"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">776</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">777</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ac56edb55f992391df4adef74f54f596f">anonymous_namespace{tagreader.cpp}::TagClassInfo::bases</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a93b6ce3a1981ac7eec5187fe01f13f88">InClass</a>, <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>, <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>, <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a> and <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>.</p>

</div>
</div>

### startCompound() {#ab17fadda7f7d30dce3d68f186aaed55d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::startCompound (const <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp; attrib)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 359 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab17fadda7f7d30dce3d68f186aaed55d">1148</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab17fadda7f7d30dce3d68f186aaed55d">TagFileParser::startCompound</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a>&amp; attrib )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1149</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1150</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a> = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1151</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string kind   = <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>(attrib,</span><span class="doxyHighlightStringLiteral">"kind"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1152</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string isObjC = <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>(attrib,</span><span class="doxyHighlightStringLiteral">"objc"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1153</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1154</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="/web-doxygen/docs/api/namespaces/anonymous-tagreader-cpp-/#aa152a4c7667a4529af23ddb5fe6f80ee">g_compoundFactory</a>.find(kind);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1155</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="/web-doxygen/docs/api/namespaces/anonymous-tagreader-cpp-/#aa152a4c7667a4529af23ddb5fe6f80ee">g_compoundFactory</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1156</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1157</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a> = it-&gt;second.make_instance();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1158</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>       = it-&gt;second.state;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1159</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo">TagCompoundInfo</a> *info = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getCompoundInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1160</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (info) info-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a8d08366f8e993aab489906c4998886e6">lineNr</a> = <a href="#a560587cbf60c107e9bae7e205fd6ef50">m_locator</a>-&gt;lineNr();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1161</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1162</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1163</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1164</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Unknown compound attribute '{}' found!"</span><span class="doxyHighlight">,kind);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1165</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a> = <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ac73a5e6827c3a9bb6731a484f29a1224">Invalid</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1166</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1167</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1168</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo">TagClassInfo</a> *classInfo = <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>.getClassInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1169</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isObjC==</span><span class="doxyHighlightStringLiteral">"yes"</span><span class="doxyHighlight"> &amp;&amp; classInfo)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1170</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1171</span><span class="doxyLineContent"><span class="doxyHighlight">    classInfo-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ae6caddaf29b3b9b89dbf500afd0d71a3">isObjC</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1172</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1173</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/namespaces/anonymous-tagreader-cpp-/#aa152a4c7667a4529af23ddb5fe6f80ee">anonymous_namespace{tagreader.cpp}::g_compoundFactory</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ac73a5e6827c3a9bb6731a484f29a1224">Invalid</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ae6caddaf29b3b9b89dbf500afd0d71a3">anonymous_namespace{tagreader.cpp}::TagClassInfo::isObjC</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a8d08366f8e993aab489906c4998886e6">anonymous_namespace{tagreader.cpp}::TagCompoundInfo::lineNr</a>, <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>, <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>, <a href="#a560587cbf60c107e9bae7e205fd6ef50">m_locator</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>, <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>.</p>

</div>
</div>

### startDocAnchor() {#a3646ed3d0fe02e98b159d52ff914f305}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::startDocAnchor (const <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp; attrib)</td>
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



<p>Definition at line 703 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3646ed3d0fe02e98b159d52ff914f305">703</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3646ed3d0fe02e98b159d52ff914f305">startDocAnchor</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a>&amp; attrib )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">704</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">705</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a19ed33b56774430bad0811dbb24aa38d">m_fileName</a>  = <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>(attrib,</span><span class="doxyHighlightStringLiteral">"file"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">706</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a75e30c8c85ae1460b55b1585e9386693">m_title</a>     = <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>(attrib,</span><span class="doxyHighlightStringLiteral">"title"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">707</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a> = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">708</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>, <a href="#a19ed33b56774430bad0811dbb24aa38d">m_fileName</a>, <a href="#a75e30c8c85ae1460b55b1585e9386693">m_title</a> and <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>.</p>

</div>
</div>

### startDocument() {#a071b83231ad06ddf1f4192c2ee682839}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::startDocument ()</td>
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



<p>Definition at line 343 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a071b83231ad06ddf1f4192c2ee682839">343</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a071b83231ad06ddf1f4192c2ee682839">startDocument</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a> = <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ac73a5e6827c3a9bb6731a484f29a1224">Invalid</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ac73a5e6827c3a9bb6731a484f29a1224">Invalid</a> and <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>.</p>

</div>
</div>

### startElement() {#a487b3d40047a75c0612f66ab78f61d96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::startElement (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp; attrib)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 348 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a487b3d40047a75c0612f66ab78f61d96">1120</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a487b3d40047a75c0612f66ab78f61d96">TagFileParser::startElement</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a>&amp; attrib )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1121</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1122</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("startElement '%s'\n",qPrint(name));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1123</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="/web-doxygen/docs/api/namespaces/anonymous-tagreader-cpp-/#ac4f239fedcca27a83995d7b9a02b683d">g_elementHandlers</a>.find(name.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1124</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=std::end(<a href="/web-doxygen/docs/api/namespaces/anonymous-tagreader-cpp-/#ac4f239fedcca27a83995d7b9a02b683d">g_elementHandlers</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1125</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1126</span><span class="doxyLineContent"><span class="doxyHighlight">    it-&gt;second.startCb(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,attrib);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1127</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1128</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1129</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1130</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Unknown start tag '{}' found!"</span><span class="doxyHighlight">,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1131</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1132</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/namespaces/anonymous-tagreader-cpp-/#ac4f239fedcca27a83995d7b9a02b683d">anonymous_namespace{tagreader.cpp}::g_elementHandlers</a>, <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>

</div>
</div>

### startEnumValue() {#afc3a2293108d7a644b0c57ad06f29c11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::startEnumValue (const <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp; attrib)</td>
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



<p>Definition at line 439 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afc3a2293108d7a644b0c57ad06f29c11">439</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afc3a2293108d7a644b0c57ad06f29c11">startEnumValue</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a>&amp; attrib)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">441</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>==<a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a463a8e3a1d39b8771600448eff1ab94f">InMember</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">442</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a> = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aa13860af0001daf87f69281389f3c101">m_curEnumValue</a> = <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagenumvalueinfo">TagEnumValueInfo</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aa13860af0001daf87f69281389f3c101">m_curEnumValue</a>.file    = <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>(attrib,</span><span class="doxyHighlightStringLiteral">"file"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">446</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aa13860af0001daf87f69281389f3c101">m_curEnumValue</a>.anchor  = <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>(attrib,</span><span class="doxyHighlightStringLiteral">"anchor"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">447</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aa13860af0001daf87f69281389f3c101">m_curEnumValue</a>.clangid = <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>(attrib,</span><span class="doxyHighlightStringLiteral">"clangid"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ada7baee04d5b524d2d3b2c4d2207cf6d">m_stateStack</a>.push(<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a> = <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85af0bd1defdb45363bbae05d446baa8ba8">InEnumValue</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(</span><span class="doxyHighlightStringLiteral">"Found 'enumvalue' tag outside of member tag"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85af0bd1defdb45363bbae05d446baa8ba8">InEnumValue</a>, <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a463a8e3a1d39b8771600448eff1ab94f">InMember</a>, <a href="#aa13860af0001daf87f69281389f3c101">m_curEnumValue</a>, <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>, <a href="#ada7baee04d5b524d2d3b2c4d2207cf6d">m_stateStack</a>, <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a> and <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>.</p>

</div>
</div>

### startIgnoreElement() {#a89373019d59ca8a862b03c6b665daa48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::startIgnoreElement (const <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp;)</td>
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



<p>Definition at line 977 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a89373019d59ca8a862b03c6b665daa48">977</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a89373019d59ca8a862b03c6b665daa48">startIgnoreElement</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a>&amp; )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">978</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">979</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>

</div>
</div>

### startIncludes() {#a347e401a684f17633b5d23c1010b3f28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::startIncludes (const <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp; attrib)</td>
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



<p>Definition at line 792 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a347e401a684f17633b5d23c1010b3f28">792</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a347e401a684f17633b5d23c1010b3f28">startIncludes</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a>&amp; attrib )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">793</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">794</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#abac57def474d6cfc6844a2c62c81b23e">m_curIncludes</a> = <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagincludeinfo">TagIncludeInfo</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">795</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#abac57def474d6cfc6844a2c62c81b23e">m_curIncludes</a>.id         = <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>(attrib,</span><span class="doxyHighlightStringLiteral">"id"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">796</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#abac57def474d6cfc6844a2c62c81b23e">m_curIncludes</a>.name       = <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>(attrib,</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">797</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#abac57def474d6cfc6844a2c62c81b23e">m_curIncludes</a>.isLocal    = <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>(attrib,</span><span class="doxyHighlightStringLiteral">"local"</span><span class="doxyHighlight">)==</span><span class="doxyHighlightStringLiteral">"yes"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">798</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#abac57def474d6cfc6844a2c62c81b23e">m_curIncludes</a>.isImported = <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>(attrib,</span><span class="doxyHighlightStringLiteral">"imported"</span><span class="doxyHighlight">)==</span><span class="doxyHighlightStringLiteral">"yes"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">799</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#abac57def474d6cfc6844a2c62c81b23e">m_curIncludes</a>.isModule   = <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>(attrib,</span><span class="doxyHighlightStringLiteral">"module"</span><span class="doxyHighlight">)==</span><span class="doxyHighlightStringLiteral">"yes"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">800</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#abac57def474d6cfc6844a2c62c81b23e">m_curIncludes</a>.isObjC     = <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>(attrib,</span><span class="doxyHighlightStringLiteral">"objc"</span><span class="doxyHighlight">)==</span><span class="doxyHighlightStringLiteral">"yes"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">801</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">802</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#abac57def474d6cfc6844a2c62c81b23e">m_curIncludes</a>, <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a> and <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>.</p>

</div>
</div>

### startMember() {#aa4db9510d59066b8d7f847bda9fb9574}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::startMember (const <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp; attrib)</td>
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



<p>Definition at line 382 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa4db9510d59066b8d7f847bda9fb9574">382</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa4db9510d59066b8d7f847bda9fb9574">startMember</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a>&amp; attrib)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a> = <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagmemberinfo">TagMemberInfo</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a>.kind   = <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>(attrib,</span><span class="doxyHighlightStringLiteral">"kind"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> protStr   = <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>(attrib,</span><span class="doxyHighlightStringLiteral">"protection"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> virtStr   = <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>(attrib,</span><span class="doxyHighlightStringLiteral">"virtualness"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> staticStr = <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>(attrib,</span><span class="doxyHighlightStringLiteral">"static"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a>.lineNr = <a href="#a560587cbf60c107e9bae7e205fd6ef50">m_locator</a>-&gt;lineNr();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (protStr==</span><span class="doxyHighlightStringLiteral">"protected"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a>.prot = Protection::Protected;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (protStr==</span><span class="doxyHighlightStringLiteral">"private"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a>.prot = Protection::Private;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (virtStr==</span><span class="doxyHighlightStringLiteral">"virtual"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a>.virt = Specifier::Virtual;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">402</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (virtStr==</span><span class="doxyHighlightStringLiteral">"pure"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a>.virt = Specifier::Pure;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">405</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">406</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (staticStr==</span><span class="doxyHighlightStringLiteral">"yes"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">407</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">408</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a>.isStatic = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">409</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ada7baee04d5b524d2d3b2c4d2207cf6d">m_stateStack</a>.push(<a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">411</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a> = <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a463a8e3a1d39b8771600448eff1ab94f">InMember</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">412</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85a463a8e3a1d39b8771600448eff1ab94f">InMember</a>, <a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a>, <a href="#a560587cbf60c107e9bae7e205fd6ef50">m_locator</a>, <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a>, <a href="#ada7baee04d5b524d2d3b2c4d2207cf6d">m_stateStack</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>.</p>

</div>
</div>

### startStringValue() {#a5f27e5fd0bb44175b3aead4641fab718}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::startStringValue (const <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp;)</td>
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



<p>Definition at line 698 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5f27e5fd0bb44175b3aead4641fab718">698</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5f27e5fd0bb44175b3aead4641fab718">startStringValue</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a>&amp; )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">699</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">700</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a> = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">701</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### buildClassEntry() {#aa9daed7f8f5651e85aaa17885e61134c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::buildClassEntry (const std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt; &amp; root, const <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo">TagClassInfo</a> * tci)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1013 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa9daed7f8f5651e85aaa17885e61134c">1498</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa9daed7f8f5651e85aaa17885e61134c">TagFileParser::buildClassEntry</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::shared_ptr&lt;Entry&gt; &amp;root, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo">TagClassInfo</a> *tci)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1499</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1500</span><span class="doxyLineContent"><span class="doxyHighlight">  std::shared_ptr&lt;Entry&gt; ce = std::make_shared&lt;Entry&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1501</span><span class="doxyLineContent"><span class="doxyHighlight">  ce-&gt;section = EntryType::makeClass();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1502</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (tci-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ad04e53456007b170a459584ae6f313ac">kind</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1503</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1504</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ad710e6d1b19b22e7b1c9342cbe994497a9bd81329febf6efe22788e03ddeaf0af">TagClassInfo::Kind::Class</a>:     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1505</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ad710e6d1b19b22e7b1c9342cbe994497a886ef5dbd655a6c97726d7091c6b173e">TagClassInfo::Kind::Struct</a>:    ce-&gt;spec = <a href="/web-doxygen/docs/api/classes/typespecifier">TypeSpecifier</a>().setStruct(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1506</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ad710e6d1b19b22e7b1c9342cbe994497aaef12e903e606a4895a16b393bfdec8c">TagClassInfo::Kind::Union</a>:     ce-&gt;spec = <a href="/web-doxygen/docs/api/classes/typespecifier">TypeSpecifier</a>().setUnion(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1507</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ad710e6d1b19b22e7b1c9342cbe994497a3c1aac82863ed9e5a9aca8ce687f711d">TagClassInfo::Kind::Interface</a>: ce-&gt;spec = <a href="/web-doxygen/docs/api/classes/typespecifier">TypeSpecifier</a>().setInterface(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1508</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ad710e6d1b19b22e7b1c9342cbe994497acf20423ed48998082c20099488a0917c">TagClassInfo::Kind::Enum</a>:      ce-&gt;spec = <a href="/web-doxygen/docs/api/classes/typespecifier">TypeSpecifier</a>().setEnum(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1509</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ad710e6d1b19b22e7b1c9342cbe994497ab0d4998a26f5b5742ad38c4af8817e32">TagClassInfo::Kind::Exception</a>: ce-&gt;spec = <a href="/web-doxygen/docs/api/classes/typespecifier">TypeSpecifier</a>().setException(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1510</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ad710e6d1b19b22e7b1c9342cbe994497a888a77f5ac0748b6c8001822417df8b6">TagClassInfo::Kind::Protocol</a>:  ce-&gt;spec = <a href="/web-doxygen/docs/api/classes/typespecifier">TypeSpecifier</a>().setProtocol(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);  </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1511</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ad710e6d1b19b22e7b1c9342cbe994497a3adbdb3ac060038aa0e6e6c138ef9873">TagClassInfo::Kind::Category</a>:  ce-&gt;spec = <a href="/web-doxygen/docs/api/classes/typespecifier">TypeSpecifier</a>().setCategory(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);  </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1512</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ad710e6d1b19b22e7b1c9342cbe994497ac2ba7e785c49050f48da9aacc45c2b85">TagClassInfo::Kind::Service</a>:   ce-&gt;spec = <a href="/web-doxygen/docs/api/classes/typespecifier">TypeSpecifier</a>().setService(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1513</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ad710e6d1b19b22e7b1c9342cbe994497a6ff5f73c8b5ebd311406568c8ef50bfd">TagClassInfo::Kind::Singleton</a>: ce-&gt;spec = <a href="/web-doxygen/docs/api/classes/typespecifier">TypeSpecifier</a>().setSingleton(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1514</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ad710e6d1b19b22e7b1c9342cbe994497a6adf97f83acf6453d4a6a4b1070f3754">TagClassInfo::Kind::None</a>:      </span><span class="doxyHighlightComment">// should never happen, means not properly initialized</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1515</span><span class="doxyLineContent"><span class="doxyHighlight">                                        assert(tci-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ad04e53456007b170a459584ae6f313ac">kind</a> != <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ad710e6d1b19b22e7b1c9342cbe994497a6adf97f83acf6453d4a6a4b1070f3754">TagClassInfo::Kind::None</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1516</span><span class="doxyLineContent"><span class="doxyHighlight">                                        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1517</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1518</span><span class="doxyLineContent"><span class="doxyHighlight">  ce-&gt;name     = tci-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">name</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1519</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tci-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ad04e53456007b170a459584ae6f313ac">kind</a>==<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ad710e6d1b19b22e7b1c9342cbe994497a888a77f5ac0748b6c8001822417df8b6">TagClassInfo::Kind::Protocol</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1520</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1521</span><span class="doxyLineContent"><span class="doxyHighlight">    ce-&gt;name+=</span><span class="doxyHighlightStringLiteral">"-p"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1522</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1523</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a04e4220513820012d31302361cf4f24d">addDocAnchors</a>(ce,tci-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#abd7c06610979d5c6078dbf666c4358b5">docAnchors</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1524</span><span class="doxyLineContent"><span class="doxyHighlight">  ce-&gt;tagInfoData.tagName  = <a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1525</span><span class="doxyLineContent"><span class="doxyHighlight">  ce-&gt;tagInfoData.anchor   = tci-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#a3f52c99f682fa0035584aedfc2ed8dbf">anchor</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1526</span><span class="doxyLineContent"><span class="doxyHighlight">  ce-&gt;tagInfoData.fileName = tci-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a25246009588765b59a7e73cc87db2548">filename</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1527</span><span class="doxyLineContent"><span class="doxyHighlight">  ce-&gt;startLine            = tci-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a8d08366f8e993aab489906c4998886e6">lineNr</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1528</span><span class="doxyLineContent"><span class="doxyHighlight">  ce-&gt;fileName             = <a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1529</span><span class="doxyLineContent"><span class="doxyHighlight">  ce-&gt;hasTagInfo           = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1530</span><span class="doxyLineContent"><span class="doxyHighlight">  ce-&gt;id                   = tci-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ab014917f432e45612c083450553a2726">clangId</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1531</span><span class="doxyLineContent"><span class="doxyHighlight">  ce-&gt;lang                 = tci-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ae6caddaf29b3b9b89dbf500afd0d71a3">isObjC</a> ? SrcLangExt::ObjC : SrcLangExt::Unknown;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1532</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// transfer base class list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1533</span><span class="doxyLineContent"><span class="doxyHighlight">  ce-&gt;extends  = tci-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ac56edb55f992391df4adef74f54f596f">bases</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1534</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!tci-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#a747b8b8d3b89a1e4744e354c4de534ee">templateArguments</a>.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1535</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1536</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> al;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1537</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;argName : tci-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#a747b8b8d3b89a1e4744e354c4de534ee">templateArguments</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1538</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1539</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/structs/argument">Argument</a> a;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1540</span><span class="doxyLineContent"><span class="doxyHighlight">      a.<a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">type</a> = </span><span class="doxyHighlightStringLiteral">"class"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1541</span><span class="doxyLineContent"><span class="doxyHighlight">      a.<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a> = argName.c_str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1542</span><span class="doxyLineContent"><span class="doxyHighlight">      al.<a href="/web-doxygen/docs/api/classes/argumentlist/#aa80c14f74871d9274671a9e33ac3c870">push_back</a>(a);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1543</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1544</span><span class="doxyLineContent"><span class="doxyHighlight">    ce-&gt;tArgLists.<a href="/web-doxygen/docs/api/classes/argumentlist/#aa80c14f74871d9274671a9e33ac3c870">push_back</a>(al);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1545</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1546</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1547</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aa5dd16fd497d034a55fdca37a3c17804">buildMemberList</a>(ce,tci-&gt;<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#af08267c179ffb9c4e799ea9a59f8f2a2">members</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1548</span><span class="doxyLineContent"><span class="doxyHighlight">  root-&gt;moveToSubEntryAndKeep(ce);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1549</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a04e4220513820012d31302361cf4f24d">addDocAnchors</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#a3f52c99f682fa0035584aedfc2ed8dbf">anonymous_namespace{tagreader.cpp}::TagClassInfo::anchor</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ac56edb55f992391df4adef74f54f596f">anonymous_namespace{tagreader.cpp}::TagClassInfo::bases</a>, <a href="#aa5dd16fd497d034a55fdca37a3c17804">buildMemberList</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ad710e6d1b19b22e7b1c9342cbe994497a3adbdb3ac060038aa0e6e6c138ef9873">anonymous_namespace{tagreader.cpp}::TagClassInfo::Category</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ab014917f432e45612c083450553a2726">anonymous_namespace{tagreader.cpp}::TagClassInfo::clangId</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ad710e6d1b19b22e7b1c9342cbe994497a9bd81329febf6efe22788e03ddeaf0af">anonymous_namespace{tagreader.cpp}::TagClassInfo::Class</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#abd7c06610979d5c6078dbf666c4358b5">anonymous_namespace{tagreader.cpp}::TagCompoundInfo::docAnchors</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ad710e6d1b19b22e7b1c9342cbe994497acf20423ed48998082c20099488a0917c">anonymous_namespace{tagreader.cpp}::TagClassInfo::Enum</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ad710e6d1b19b22e7b1c9342cbe994497ab0d4998a26f5b5742ad38c4af8817e32">anonymous_namespace{tagreader.cpp}::TagClassInfo::Exception</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a25246009588765b59a7e73cc87db2548">anonymous_namespace{tagreader.cpp}::TagCompoundInfo::filename</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ad710e6d1b19b22e7b1c9342cbe994497a3c1aac82863ed9e5a9aca8ce687f711d">anonymous_namespace{tagreader.cpp}::TagClassInfo::Interface</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ae6caddaf29b3b9b89dbf500afd0d71a3">anonymous_namespace{tagreader.cpp}::TagClassInfo::isObjC</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ad04e53456007b170a459584ae6f313ac">anonymous_namespace{tagreader.cpp}::TagClassInfo::kind</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#a8d08366f8e993aab489906c4998886e6">anonymous_namespace{tagreader.cpp}::TagCompoundInfo::lineNr</a>, <a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#af08267c179ffb9c4e799ea9a59f8f2a2">anonymous_namespace{tagreader.cpp}::TagCompoundInfo::members</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#ad66cfffc0d1431ede0df482a7c5beaca">anonymous_namespace{tagreader.cpp}::TagCompoundInfo::name</a>, <a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">Argument::name</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ad710e6d1b19b22e7b1c9342cbe994497a6adf97f83acf6453d4a6a4b1070f3754">anonymous_namespace{tagreader.cpp}::TagClassInfo::None</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ad710e6d1b19b22e7b1c9342cbe994497a888a77f5ac0748b6c8001822417df8b6">anonymous_namespace{tagreader.cpp}::TagClassInfo::Protocol</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#aa80c14f74871d9274671a9e33ac3c870">ArgumentList::push_back</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ad710e6d1b19b22e7b1c9342cbe994497ac2ba7e785c49050f48da9aacc45c2b85">anonymous_namespace{tagreader.cpp}::TagClassInfo::Service</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ad710e6d1b19b22e7b1c9342cbe994497a6ff5f73c8b5ebd311406568c8ef50bfd">anonymous_namespace{tagreader.cpp}::TagClassInfo::Singleton</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ad710e6d1b19b22e7b1c9342cbe994497a886ef5dbd655a6c97726d7091c6b173e">anonymous_namespace{tagreader.cpp}::TagClassInfo::Struct</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#a747b8b8d3b89a1e4744e354c4de534ee">anonymous_namespace{tagreader.cpp}::TagClassInfo::templateArguments</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">Argument::type</a> and <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#ad710e6d1b19b22e7b1c9342cbe994497aaef12e903e606a4895a16b393bfdec8c">anonymous_namespace{tagreader.cpp}::TagClassInfo::Union</a>.</p>


<p>Referenced by <a href="#ab5bfa36a1a89d2e6f35ac34fc6b0af3d">buildClassTree</a>.</p>

</div>
</div>

### buildClassTree() {#ab5bfa36a1a89d2e6f35ac34fc6b0af3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous_namespace{tagreader.cpp}::TagFileParser::buildClassTree (const std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt; &amp; root, const <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileparser/classnode">ClassNode</a> &amp; node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1014 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab5bfa36a1a89d2e6f35ac34fc6b0af3d">1551</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab5bfa36a1a89d2e6f35ac34fc6b0af3d">TagFileParser::buildClassTree</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::shared_ptr&lt;Entry&gt; &amp;root,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileparser/classnode">ClassNode</a> &amp;node)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1552</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1553</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (node.<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileparser/classnode/#a6aa32a2acb4b87396f2a74ba319c6299">tci</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1554</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1555</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa9daed7f8f5651e85aaa17885e61134c">buildClassEntry</a>(root,node.<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileparser/classnode/#a6aa32a2acb4b87396f2a74ba319c6299">tci</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1556</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1557</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;child : node.<a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileparser/classnode/#a694169fa539ad5c675f8d301acb54b2c">children</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1558</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1559</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ab5bfa36a1a89d2e6f35ac34fc6b0af3d">buildClassTree</a>(root,*child.second);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1560</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1561</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#aa9daed7f8f5651e85aaa17885e61134c">buildClassEntry</a>, <a href="#ab5bfa36a1a89d2e6f35ac34fc6b0af3d">buildClassTree</a>, <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileparser/classnode/#a694169fa539ad5c675f8d301acb54b2c">anonymous_namespace{tagreader.cpp}::TagFileParser::ClassNode::children</a> and <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileparser/classnode/#a6aa32a2acb4b87396f2a74ba319c6299">anonymous_namespace{tagreader.cpp}::TagFileParser::ClassNode::tci</a>.</p>


<p>Referenced by <a href="#ab5bfa36a1a89d2e6f35ac34fc6b0af3d">buildClassTree</a> and <a href="#a9a2a4b0accaef9069229937226e60b10">buildLists</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_curCompound {#a68d8d8033bf8bd3d346a60e7237e276c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TagCompoundVariant anonymous_namespace{tagreader.cpp}::TagFileParser::m_curCompound</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1018 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a68d8d8033bf8bd3d346a60e7237e276c">1018</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant">TagCompoundVariant</a>                <a href="#a68d8d8033bf8bd3d346a60e7237e276c">m_curCompound</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a42aff7a35ce87a4df59d4a05f374f54e">endAnchor</a>, <a href="#a1ac7de66e90ffbf93cd637c67c7cc76c">endBase</a>, <a href="#ab27d1e74556a11f12e2d6a3b0dfa1225">endClangId</a>, <a href="#ab0af5855a848b20e3136d941d7840732">endClass</a>, <a href="#a3e0857519c95a2ab4f2649588f52b244">endCompound</a>, <a href="#a88c616e8f2d519406f88102cf9913811">endConcept</a>, <a href="#af120fd7d4ed4df2d800e4a531152728d">endDir</a>, <a href="#a5b2c9b8ab174e898f87b90803529766c">endDocAnchor</a>, <a href="#a34e5a973da1491d711704a2ee6ee8ae0">endFile</a>, <a href="#acb8e913e38db3f6aa9c1bbb9a641a17f">endFilename</a>, <a href="#a18f64ce17ad437b8675f4bd7b9f8a974">endIncludes</a>, <a href="#afce64693b86203b0106f25a6697a8076">endMember</a>, <a href="#aa0c63ea4440394d9c1089cc804f6b3cb">endModule</a>, <a href="#af5d579a5b02bb8153e8be2ffe25d2b90">endName</a>, <a href="#a5f364b44aa47f45ead81e1892359c3ee">endNamespace</a>, <a href="#a40b954bb215265f9d331f673102f8e11">endPage</a>, <a href="#a8020f9f5e883fd98854ac72e4e6e776d">endPath</a>, <a href="#ab01b451a3fc33322e98c40bd5cca5878">endSubgroup</a>, <a href="#a6fd29da85de1ed3faf625ee0d27122ae">endSubpage</a>, <a href="#a942847def781fe793b9bf3b1a7179c3f">endTemplateArg</a>, <a href="#aa6e06a88bac03298d1b7b1d960786089">endTitle</a>, <a href="#a6927f64d6b3e45878b5102852e1e2fac">startBase</a> and <a href="#ab17fadda7f7d30dce3d68f186aaed55d">startCompound</a>.</p>

</div>
</div>

### m\_curEnumValue {#aa13860af0001daf87f69281389f3c101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TagEnumValueInfo anonymous_namespace{tagreader.cpp}::TagFileParser::m_curEnumValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1021 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa13860af0001daf87f69281389f3c101">1021</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagenumvalueinfo">TagEnumValueInfo</a>           <a href="#aa13860af0001daf87f69281389f3c101">m_curEnumValue</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a06a8a71d6e6d9f8e93cee750e2faa0ef">endEnumValue</a> and <a href="#afc3a2293108d7a644b0c57ad06f29c11">startEnumValue</a>.</p>

</div>
</div>

### m\_curIncludes {#abac57def474d6cfc6844a2c62c81b23e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TagIncludeInfo anonymous_namespace{tagreader.cpp}::TagFileParser::m_curIncludes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1022 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abac57def474d6cfc6844a2c62c81b23e">1022</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagincludeinfo">TagIncludeInfo</a>             <a href="#abac57def474d6cfc6844a2c62c81b23e">m_curIncludes</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a18f64ce17ad437b8675f4bd7b9f8a974">endIncludes</a> and <a href="#a347e401a684f17633b5d23c1010b3f28">startIncludes</a>.</p>

</div>
</div>

### m\_curMember {#a703f6a9467842a8bd8d6c5b05ea60bfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TagMemberInfo anonymous_namespace{tagreader.cpp}::TagFileParser::m_curMember</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1020 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">1020</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagmemberinfo">TagMemberInfo</a>              <a href="#a703f6a9467842a8bd8d6c5b05ea60bfc">m_curMember</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a42aff7a35ce87a4df59d4a05f374f54e">endAnchor</a>, <a href="#a898f929ad250f095d46ce638e8fce78a">endAnchorFile</a>, <a href="#a005718bfd790617c0cf8b3ab0c86a6c3">endArglist</a>, <a href="#ab27d1e74556a11f12e2d6a3b0dfa1225">endClangId</a>, <a href="#a5b2c9b8ab174e898f87b90803529766c">endDocAnchor</a>, <a href="#a06a8a71d6e6d9f8e93cee750e2faa0ef">endEnumValue</a>, <a href="#afce64693b86203b0106f25a6697a8076">endMember</a>, <a href="#af5d579a5b02bb8153e8be2ffe25d2b90">endName</a>, <a href="#a1f6885619a9e437468650af93b8f05f3">endType</a> and <a href="#aa4db9510d59066b8d7f847bda9fb9574">startMember</a>.</p>

</div>
</div>

### m\_curString {#a9548f3206b46e2bd177d3a0de2d3f125}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString anonymous_namespace{tagreader.cpp}::TagFileParser::m_curString</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1024 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9548f3206b46e2bd177d3a0de2d3f125">1024</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>                   <a href="#a9548f3206b46e2bd177d3a0de2d3f125">m_curString</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a98c5a0d5ae75e20939baaba36ecaf2e3">characters</a>, <a href="#a42aff7a35ce87a4df59d4a05f374f54e">endAnchor</a>, <a href="#a898f929ad250f095d46ce638e8fce78a">endAnchorFile</a>, <a href="#a005718bfd790617c0cf8b3ab0c86a6c3">endArglist</a>, <a href="#a1ac7de66e90ffbf93cd637c67c7cc76c">endBase</a>, <a href="#ab27d1e74556a11f12e2d6a3b0dfa1225">endClangId</a>, <a href="#ab0af5855a848b20e3136d941d7840732">endClass</a>, <a href="#a88c616e8f2d519406f88102cf9913811">endConcept</a>, <a href="#af120fd7d4ed4df2d800e4a531152728d">endDir</a>, <a href="#a5b2c9b8ab174e898f87b90803529766c">endDocAnchor</a>, <a href="#a06a8a71d6e6d9f8e93cee750e2faa0ef">endEnumValue</a>, <a href="#a34e5a973da1491d711704a2ee6ee8ae0">endFile</a>, <a href="#acb8e913e38db3f6aa9c1bbb9a641a17f">endFilename</a>, <a href="#a18f64ce17ad437b8675f4bd7b9f8a974">endIncludes</a>, <a href="#aa0c63ea4440394d9c1089cc804f6b3cb">endModule</a>, <a href="#af5d579a5b02bb8153e8be2ffe25d2b90">endName</a>, <a href="#a5f364b44aa47f45ead81e1892359c3ee">endNamespace</a>, <a href="#a40b954bb215265f9d331f673102f8e11">endPage</a>, <a href="#a8020f9f5e883fd98854ac72e4e6e776d">endPath</a>, <a href="#ab01b451a3fc33322e98c40bd5cca5878">endSubgroup</a>, <a href="#a6fd29da85de1ed3faf625ee0d27122ae">endSubpage</a>, <a href="#a942847def781fe793b9bf3b1a7179c3f">endTemplateArg</a>, <a href="#aa6e06a88bac03298d1b7b1d960786089">endTitle</a>, <a href="#a1f6885619a9e437468650af93b8f05f3">endType</a>, <a href="#a6927f64d6b3e45878b5102852e1e2fac">startBase</a>, <a href="#ab17fadda7f7d30dce3d68f186aaed55d">startCompound</a>, <a href="#a3646ed3d0fe02e98b159d52ff914f305">startDocAnchor</a>, <a href="#afc3a2293108d7a644b0c57ad06f29c11">startEnumValue</a>, <a href="#a347e401a684f17633b5d23c1010b3f28">startIncludes</a> and <a href="#a5f27e5fd0bb44175b3aead4641fab718">startStringValue</a>.</p>

</div>
</div>

### m\_fileName {#a19ed33b56774430bad0811dbb24aa38d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString anonymous_namespace{tagreader.cpp}::TagFileParser::m_fileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1026 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a19ed33b56774430bad0811dbb24aa38d">1026</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>                   <a href="#a19ed33b56774430bad0811dbb24aa38d">m_fileName</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a5b2c9b8ab174e898f87b90803529766c">endDocAnchor</a> and <a href="#a3646ed3d0fe02e98b159d52ff914f305">startDocAnchor</a>.</p>

</div>
</div>

### m\_locator {#a560587cbf60c107e9bae7e205fd6ef50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const XMLLocator* anonymous_namespace{tagreader.cpp}::TagFileParser::m_locator = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1030 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a560587cbf60c107e9bae7e205fd6ef50">1030</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmllocator">XMLLocator</a>          *<a href="#a560587cbf60c107e9bae7e205fd6ef50">m_locator</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a662591474cf5ed7adce79a42d49736af">setDocumentLocator</a>, <a href="#ab17fadda7f7d30dce3d68f186aaed55d">startCompound</a> and <a href="#aa4db9510d59066b8d7f847bda9fb9574">startMember</a>.</p>

</div>
</div>

### m\_state {#ac0775f760651bb75fb5919795b8a1241}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">State anonymous_namespace{tagreader.cpp}::TagFileParser::m_state = <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ac73a5e6827c3a9bb6731a484f29a1224">Invalid</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1028 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac0775f760651bb75fb5919795b8a1241">1028</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85">State</a>                      <a href="#ac0775f760651bb75fb5919795b8a1241">m_state</a> = <a href="#a7a2a20ef2fb10c1c35e093f0c3f41f85ac73a5e6827c3a9bb6731a484f29a1224">Invalid</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a42aff7a35ce87a4df59d4a05f374f54e">endAnchor</a>, <a href="#a898f929ad250f095d46ce638e8fce78a">endAnchorFile</a>, <a href="#a005718bfd790617c0cf8b3ab0c86a6c3">endArglist</a>, <a href="#a1ac7de66e90ffbf93cd637c67c7cc76c">endBase</a>, <a href="#ab27d1e74556a11f12e2d6a3b0dfa1225">endClangId</a>, <a href="#ab0af5855a848b20e3136d941d7840732">endClass</a>, <a href="#a3e0857519c95a2ab4f2649588f52b244">endCompound</a>, <a href="#a88c616e8f2d519406f88102cf9913811">endConcept</a>, <a href="#af120fd7d4ed4df2d800e4a531152728d">endDir</a>, <a href="#a5b2c9b8ab174e898f87b90803529766c">endDocAnchor</a>, <a href="#a06a8a71d6e6d9f8e93cee750e2faa0ef">endEnumValue</a>, <a href="#a34e5a973da1491d711704a2ee6ee8ae0">endFile</a>, <a href="#acb8e913e38db3f6aa9c1bbb9a641a17f">endFilename</a>, <a href="#a18f64ce17ad437b8675f4bd7b9f8a974">endIncludes</a>, <a href="#afce64693b86203b0106f25a6697a8076">endMember</a>, <a href="#aa0c63ea4440394d9c1089cc804f6b3cb">endModule</a>, <a href="#af5d579a5b02bb8153e8be2ffe25d2b90">endName</a>, <a href="#a5f364b44aa47f45ead81e1892359c3ee">endNamespace</a>, <a href="#a40b954bb215265f9d331f673102f8e11">endPage</a>, <a href="#a8020f9f5e883fd98854ac72e4e6e776d">endPath</a>, <a href="#ab01b451a3fc33322e98c40bd5cca5878">endSubgroup</a>, <a href="#a6fd29da85de1ed3faf625ee0d27122ae">endSubpage</a>, <a href="#a942847def781fe793b9bf3b1a7179c3f">endTemplateArg</a>, <a href="#aa6e06a88bac03298d1b7b1d960786089">endTitle</a>, <a href="#a1f6885619a9e437468650af93b8f05f3">endType</a>, <a href="#a6927f64d6b3e45878b5102852e1e2fac">startBase</a>, <a href="#ab17fadda7f7d30dce3d68f186aaed55d">startCompound</a>, <a href="#a071b83231ad06ddf1f4192c2ee682839">startDocument</a>, <a href="#afc3a2293108d7a644b0c57ad06f29c11">startEnumValue</a> and <a href="#aa4db9510d59066b8d7f847bda9fb9574">startMember</a>.</p>

</div>
</div>

### m\_stateStack {#ada7baee04d5b524d2d3b2c4d2207cf6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::stack&lt;State&gt; anonymous_namespace{tagreader.cpp}::TagFileParser::m_stateStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1029 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ada7baee04d5b524d2d3b2c4d2207cf6d">1029</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::stack&lt;State&gt;          <a href="#ada7baee04d5b524d2d3b2c4d2207cf6d">m_stateStack</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a06a8a71d6e6d9f8e93cee750e2faa0ef">endEnumValue</a>, <a href="#afce64693b86203b0106f25a6697a8076">endMember</a>, <a href="#afc3a2293108d7a644b0c57ad06f29c11">startEnumValue</a> and <a href="#aa4db9510d59066b8d7f847bda9fb9574">startMember</a>.</p>

</div>
</div>

### m\_tagFileCompounds {#ac75f982d3520a85cd31cabafbbd60dc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; TagCompoundVariant &gt; anonymous_namespace{tagreader.cpp}::TagFileParser::m_tagFileCompounds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1017 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac75f982d3520a85cd31cabafbbd60dc7">1017</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::vector&lt; TagCompoundVariant &gt; <a href="#ac75f982d3520a85cd31cabafbbd60dc7">m_tagFileCompounds</a>;</span></span></div>

</div>


<p>Referenced by <a href="#afbafb9f58aa69f3ea191211d77ffccae">addIncludes</a>, <a href="#a9a2a4b0accaef9069229937226e60b10">buildLists</a>, <a href="#aafd3846f78cc76b992152366c99f7d74">dump</a> and <a href="#a3e0857519c95a2ab4f2649588f52b244">endCompound</a>.</p>

</div>
</div>

### m\_tagName {#adfdee579b9a50ed97a730b7a9f23436f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString anonymous_namespace{tagreader.cpp}::TagFileParser::m_tagName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1025 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adfdee579b9a50ed97a730b7a9f23436f">1025</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>                   <a href="#adfdee579b9a50ed97a730b7a9f23436f">m_tagName</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a04e4220513820012d31302361cf4f24d">addDocAnchors</a>, <a href="#afbafb9f58aa69f3ea191211d77ffccae">addIncludes</a>, <a href="#aa9daed7f8f5651e85aaa17885e61134c">buildClassEntry</a>, <a href="#a9a2a4b0accaef9069229937226e60b10">buildLists</a>, <a href="#aa5dd16fd497d034a55fdca37a3c17804">buildMemberList</a> and <a href="#a43f4ea41f01f767ade7898b8d69d0f43">TagFileParser</a>.</p>

</div>
</div>

### m\_title {#a75e30c8c85ae1460b55b1585e9386693}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString anonymous_namespace{tagreader.cpp}::TagFileParser::m_title</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1027 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a75e30c8c85ae1460b55b1585e9386693">1027</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>                   <a href="#a75e30c8c85ae1460b55b1585e9386693">m_title</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a5b2c9b8ab174e898f87b90803529766c">endDocAnchor</a> and <a href="#a3646ed3d0fe02e98b159d52ff914f305">startDocAnchor</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
