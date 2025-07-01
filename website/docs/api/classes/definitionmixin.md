---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/definitionmixin
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `DefinitionMixin` Class Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;class Base&gt;
class DefinitionMixin&lt;Base&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/definitionimpl-h">src/definitionimpl.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Base</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aa314c6a73e812b62d5e991ebd695cdd1">DefinitionMixin</a> (const QCString &amp;defFileName, int defLine, int defColumn, const QCString &amp;name, const char *b=nullptr, const char *d=nullptr, bool isSymbol=TRUE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a9b3cbc90a75238c4231cbaad9107f13f">DefinitionMixin</a> (const DefinitionMixin &amp;other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aec5f32919542649a690cd311ec4bc7d6">DefinitionMixin</a> (DefinitionMixin &amp;&amp;)=delete</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a698644e08e5678cfade98150eb0f097b">~DefinitionMixin</a> () override=default</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/definitionmixin">DefinitionMixin</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2b18a1e181f0001e50887bfb0e2f32a7">operator=</a> (const DefinitionMixin &amp;other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/definitionmixin">DefinitionMixin</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a28ba90ab17bf7e21a396e8a5814dbd17">operator=</a> (DefinitionMixin &amp;&amp;)=delete</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acc207912ee434d4be81444f20f758c42">isAlias</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a084cf29cf38b39f8826f74300ec142a3">name</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4e8481d8676dbc4609b6164c38a3d106">isAnonymous</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaef9557cbcd9ef70171b43669cbf69e4">localName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a47fbd183e7875e3446a5a5059fc3fc18">qualifiedName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5d92005bf382f44874dc7b34196a1ac4">symbolName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6936f9ad8c00e760f0d3f2a9f71d8062">getSourceFileBase</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a456387716bea5b3efb759ae28e016012">getSourceAnchor</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae8fdeb361a15e2342867d47936e0e5cd">documentation</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad46b34a786acf616797f7ea22c733fca">docLine</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a35745772d5cbc15835976d602ebae951">docFile</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7dc1bbded3ac0ed218fff164f1da0504">briefDescription</a> (bool abbreviate=FALSE) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a33c52548681bf6be9ef52027adb53f83">briefDescriptionAsTooltip</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae6d1d3c3703fd95217c72b5e09e6026b">briefLine</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad3ac9d5d6118dcce7ece8ca2b4cfbb25">inbodyDocumentation</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0c0d049fa0196e7b240dcc35d349ab5b">inbodyFile</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad667c5e00fe9063054fd9bf4d25b3b88">inbodyLine</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a41226d110ae0c4514ec5d2acce3b5a1d">briefFile</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a110bf2aa0cf3af983ac301adb0483a2f">getDefFileName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3c8ff898904d67dbed89c16e4bc4210b">getDefFileExtension</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a016daf21744b5c79ec6232a7b247b042">getDefLine</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aeb503ebb52acc96c37bb3cd30190b72f">getDefColumn</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afe3c1ea08436b40521d94878cadf9c0f">hasDocumentation</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0aaa947a6a57bf5c7698f8c854f7ebb9">hasUserDocumentation</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a180f4796532e181fc5bb1014c7a77d9a">isVisibleInProject</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab5e39836930c40293df64e90d435ef40">isVisible</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab5feda26fd74e0f0c430132b36942f4c">isHidden</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae1b90ef5245bf2fffa90b41da2f9f66e">isArtificial</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1c14be8556addce7b154dc26059ecd5e">isExported</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9de91e7b1badbba3573f6c1827eab01c">getReference</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a02af6a985756c345fcc5b94962c11213">isReference</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a023727ef82a91c6c1fa150409180851b">externalReference</a> (const QCString &amp;relPath) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad17428050c735af6bf1adf5507f53e8f">getStartDefLine</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acf6ad305b67c683d1d30c51f6f1c2b62">getStartBodyLine</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa4c29fec74b7015e02a76354c268f1d6">getEndBodyLine</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#accaec928eb70b0232fb7b1666cac3485">getBodyDef</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aff16f5c631848265076805fa667fc43a">getLanguage</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/grouplist">GroupList</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac930798d5e2008a99386890ea44f8625">partOfGroups</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1b4737d666571fd4e7868030a322b42f">isLinkableViaGroup</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const <a href="/web-doxygen/docs/api/files/src/reflist-h/#a51b03784d48079baab06a4d5c8b08c42">RefItemVector</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7080c8c1be27b05ba64f160655530571">xrefListItems</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac8df42dc069675f2835ab89b73015cfe">findInnerCompound</a> (const QCString &amp;name) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/definition">Definition</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9205d504e802a7030d5f8408b0347176">getOuterScope</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/membervector">MemberVector</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a778beca21c8fde89bba352467dbcb655">getReferencesMembers</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/membervector">MemberVector</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5e4ca19102a811875f1917b0caad407d">getReferencedByMembers</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad372f7b60a11a8ca3a2ffa4a0ce12eb4">hasSections</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3f6c82ff6cc6ccc6fc75c2399828e5ee">hasSources</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2a93cd5cf5b0945e68de39ed6f7684df">hasBriefDescription</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5664b56e962bcc049e8a59cd3ffe5a68">id</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/sectionrefs">SectionRefs</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adef316d429538b09212c34eda65a5cab">getSectionRefs</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7d64f115d59d2667225ea684dfd2aa9d">setName</a> (const QCString &amp;name) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a34b916976d8f272c97f00d74001fdd0c">setId</a> (const QCString &amp;name) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad1c72eb42ed909d2056c16f3bcbf960f">setDefFile</a> (const QCString &amp;df, int defLine, int defColumn) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a57049ae0a543644fa13d44472098f7ae">setDocumentation</a> (const QCString &amp;doc, const QCString &amp;docFile, int docLine, bool stripWhiteSpace=TRUE) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8934a29fc121ab4bffaedd8e960713bc">setBriefDescription</a> (const QCString &amp;brief, const QCString &amp;briefFile, int briefLine) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9dac0008b22397baee417797233657f4">setInbodyDocumentation</a> (const QCString &amp;doc, const QCString &amp;docFile, int docLine) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5b7806d54dc3504a626078ac0d22dc19">setReference</a> (const QCString &amp;r) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2367c2405cb856670d78d45053cbe2c7">addSectionsToDefinition</a> (const std::vector&lt; const SectionInfo * &gt; &amp;anchorList) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a09634fd6d1779376b3c53141ba3f3d26">setBodySegment</a> (int defLine, int bls, int ble) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa6dbecf61d4840467a33899011d0cb11">setBodyDef</a> (const FileDef *fd) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3bd511a0977bf2621a15edbe0d90ed32">addSourceReferencedBy</a> (MemberDef *md, const QCString &amp;sourceRefName) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a963c53f9395e89eb1c3a12e40cbf51b9">addSourceReferences</a> (MemberDef *md, const QCString &amp;sourceRefName) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af1dfd6ae62c6a43f590645a80fc039a7">setRefItems</a> (const RefItemVector &amp;sli) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abbbd4d57b3f9c4c6a1bf436a6418c499">mergeRefItems</a> (Definition *def) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6b8996a6213108c6d925e284d372bf26">mergeReferences</a> (const Definition *other) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa14c9f0a9553f1bf85c0a71c921e441c">mergeReferencedBy</a> (const Definition *other) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3e1056f3e52c899cbb2ea8b4b513748f">addInnerCompound</a> (Definition *def) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5701961a47f8f5336495771c8d3d611d">setOuterScope</a> (Definition *def) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adb72e3dd9d7e09222e8b351c744d844e">setHidden</a> (bool b) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6faed3bc5a08c5f991d1223b11f46bc7">setArtificial</a> (bool b) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a71b4c90ca024920118d6da8ac61ea689">setExported</a> (bool b) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a513b45b150ca956112360ccf93f7cebd">setLanguage</a> (SrcLangExt lang) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0922bcff85f540f991fd4e5fd3a68a02">writeSourceDef</a> (OutputList &amp;ol) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab4f70a9c2798cb1b656a002e28af6a87">writeInlineCode</a> (OutputList &amp;ol, const QCString &amp;scopeName) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab3637501f75263f66aeeb56f088b9585">hasSourceRefs</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8019928f9557a20ee13eb6d31e5e9943">hasSourceReffedBy</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a24663e9c959433e58e8e102ad4306814">writeSourceRefs</a> (OutputList &amp;ol, const QCString &amp;scopeName) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a91fa887054f1f3aafb9bb330491b8f84">writeSourceReffedBy</a> (OutputList &amp;ol, const QCString &amp;scopeName) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a68421bb76ed3da467e074ecb06e5cf12">makePartOfGroup</a> (GroupDef *gd) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1920f150021e040075a423418fb0e85a">writeNavigationPath</a> (OutputList &amp;ol) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af64c20fb61ef66db149815f84ef20124">navigationPathAsString</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad191384d79c44e12ae31ee900209c3c6">writeQuickMemberLinks</a> (OutputList &amp;ol, const MemberDef *md) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad951f2f7aef7a2408a8bafc08b7b5899">writeSummaryLinks</a> (OutputList &amp;ol) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a48df7719d4f28f55162adc4b1064699b">writePageNavigation</a> (OutputList &amp;ol) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a923515abd1bebf6566f807b4dc2e02bd">pathFragment</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afcd2841ebfa088d88d8624e5f54f1aa9">writeDocAnchorsToTagFile</a> (TextStream &amp;fs) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abf40dcb168e2a970e68dabbcbde25ee6">setLocalName</a> (const QCString &amp;name) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad12243a0430f318cbe3b499ca21c9e4b">writeToc</a> (OutputList &amp;ol, const LocalToc &amp;lt) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab7826eed19f5c7c6f60b781f66a2c4cb">computeTooltip</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1f425520bda2df8a42b4a804806879cc">_setSymbolName</a> (const QCString &amp;name) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2a045a5eb349b5ed419a067c2d2fde96">_symbolName</a> () const override</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/definition">Definition</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab644c9a49a1aeb38b65e9edb4f11d9e1">toDefinition_</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/definitionmutable">DefinitionMutable</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0b28f6bdf8b17b0c89b4ea1a69129527">toDefinitionMutable_</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/definitionimpl">DefinitionImpl</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8344f08e2dda50c48becfde382067b46">toDefinitionImpl_</a> () const override</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Base&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/definitionimpl">DefinitionImpl</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a></td>
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


Definition at line 148 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxySectionDef">

## Public Constructors

### DefinitionMixin() {#aa314c6a73e812b62d5e991ebd695cdd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DefinitionMixin&lt; Base &gt;::DefinitionMixin (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; defFileName, int defLine, int defColumn, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const char * b=nullptr, const char * d=nullptr, bool isSymbol=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</td>
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




Create a new definition

Definition at line 152 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa314c6a73e812b62d5e991ebd695cdd1">152</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa314c6a73e812b62d5e991ebd695cdd1">DefinitionMixin</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;defFileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> defLine,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> defColumn,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#a084cf29cf38b39f8826f74300ec142a3">name</a>,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *b=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *d=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isSymbol=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>) : <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>(this,defFileName,defLine,defColumn,<a href="#a084cf29cf38b39f8826f74300ec142a3">name</a>,b,d,isSymbol) {}</span></span></div>

</div>


References <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>, <a href="#a084cf29cf38b39f8826f74300ec142a3">DefinitionMixin&lt; Base &gt;::name</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="#a9b3cbc90a75238c4231cbaad9107f13f">DefinitionMixin&lt; Base &gt;::DefinitionMixin</a>, <a href="#aec5f32919542649a690cd311ec4bc7d6">DefinitionMixin&lt; Base &gt;::DefinitionMixin</a>, <a href="#a2b18a1e181f0001e50887bfb0e2f32a7">DefinitionMixin&lt; Base &gt;::operator=</a> and <a href="#a28ba90ab17bf7e21a396e8a5814dbd17">DefinitionMixin&lt; Base &gt;::operator=</a>.
</div>
</div>

### DefinitionMixin() {#a9b3cbc90a75238c4231cbaad9107f13f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DefinitionMixin&lt; Base &gt;::DefinitionMixin (const <a href="/web-doxygen/docs/api/classes/definitionmixin">DefinitionMixin</a> &amp; other)</td>
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



Definition at line 156 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9b3cbc90a75238c4231cbaad9107f13f">156</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a9b3cbc90a75238c4231cbaad9107f13f">DefinitionMixin</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#aa314c6a73e812b62d5e991ebd695cdd1">DefinitionMixin</a> &amp;other) : Base(other), <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>(other.<a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>) {}</span></span></div>

</div>


References <a href="#aa314c6a73e812b62d5e991ebd695cdd1">DefinitionMixin&lt; Base &gt;::DefinitionMixin</a> and <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### DefinitionMixin() {#aec5f32919542649a690cd311ec4bc7d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DefinitionMixin&lt; Base &gt;::DefinitionMixin (<a href="/web-doxygen/docs/api/classes/definitionmixin">DefinitionMixin</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 158 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

Reference <a href="#aa314c6a73e812b62d5e991ebd695cdd1">DefinitionMixin&lt; Base &gt;::DefinitionMixin</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DefinitionMixin() {#a698644e08e5678cfade98150eb0f097b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DefinitionMixin&lt; Base &gt;::~DefinitionMixin ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 160 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a2b18a1e181f0001e50887bfb0e2f32a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DefinitionMixin &amp; DefinitionMixin&lt; Base &gt;::operator= (const <a href="/web-doxygen/docs/api/classes/definitionmixin">DefinitionMixin</a> &amp; other)</td>
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



Definition at line 157 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2b18a1e181f0001e50887bfb0e2f32a7">157</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa314c6a73e812b62d5e991ebd695cdd1">DefinitionMixin</a> &amp;<a href="#a2b18a1e181f0001e50887bfb0e2f32a7">operator=</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#aa314c6a73e812b62d5e991ebd695cdd1">DefinitionMixin</a> &amp;other) { </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">!=&amp;other) { <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a> = other.<a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>; }; </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">; }</span></span></div>

</div>


References <a href="#aa314c6a73e812b62d5e991ebd695cdd1">DefinitionMixin&lt; Base &gt;::DefinitionMixin</a> and <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### operator=() {#a28ba90ab17bf7e21a396e8a5814dbd17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DefinitionMixin &amp; DefinitionMixin&lt; Base &gt;::operator= (<a href="/web-doxygen/docs/api/classes/definitionmixin">DefinitionMixin</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 159 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

Reference <a href="#aa314c6a73e812b62d5e991ebd695cdd1">DefinitionMixin&lt; Base &gt;::DefinitionMixin</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### \_setSymbolName() {#a1f425520bda2df8a42b4a804806879cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::_setSymbolName (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



Definition at line 291 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1f425520bda2df8a42b4a804806879cc">291</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1f425520bda2df8a42b4a804806879cc">_setSymbolName</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#a084cf29cf38b39f8826f74300ec142a3">name</a>)</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>._setSymbolName(<a href="#a084cf29cf38b39f8826f74300ec142a3">name</a>); }</span></span></div>

</div>


References <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a> and <a href="#a084cf29cf38b39f8826f74300ec142a3">DefinitionMixin&lt; Base &gt;::name</a>.
</div>
</div>

### \_symbolName() {#a2a045a5eb349b5ed419a067c2d2fde96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DefinitionMixin&lt; Base &gt;::_symbolName ()</td>
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



Definition at line 293 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2a045a5eb349b5ed419a067c2d2fde96">293</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a2a045a5eb349b5ed419a067c2d2fde96">_symbolName</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>._symbolName(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### addInnerCompound() {#a3e1056f3e52c899cbb2ea8b4b513748f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::addInnerCompound (<a href="/web-doxygen/docs/api/classes/definition">Definition</a> * def)</td>
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



Definition at line 245 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3e1056f3e52c899cbb2ea8b4b513748f">245</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3e1056f3e52c899cbb2ea8b4b513748f">addInnerCompound</a>(<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *def)</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.addInnerCompound(def); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### addSectionsToDefinition() {#a2367c2405cb856670d78d45053cbe2c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::addSectionsToDefinition (const std::vector&lt; const <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> * &gt; &amp; anchorList)</td>
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



Definition at line 227 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2367c2405cb856670d78d45053cbe2c7">227</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2367c2405cb856670d78d45053cbe2c7">addSectionsToDefinition</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::vector&lt;const SectionInfo*&gt; &amp;anchorList)</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.addSectionsToDefinition(anchorList); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### addSourceReferencedBy() {#a3bd511a0977bf2621a15edbe0d90ed32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::addSourceReferencedBy (<a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; sourceRefName)</td>
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



Definition at line 233 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3bd511a0977bf2621a15edbe0d90ed32">233</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3bd511a0977bf2621a15edbe0d90ed32">addSourceReferencedBy</a>(<a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;sourceRefName)</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.addSourceReferencedBy(md,sourceRefName); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### addSourceReferences() {#a963c53f9395e89eb1c3a12e40cbf51b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::addSourceReferences (<a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; sourceRefName)</td>
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



Definition at line 235 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a963c53f9395e89eb1c3a12e40cbf51b9">235</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a963c53f9395e89eb1c3a12e40cbf51b9">addSourceReferences</a>(<a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;sourceRefName)</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.addSourceReferences(md,sourceRefName); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### briefDescription() {#a7dc1bbded3ac0ed218fff164f1da0504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DefinitionMixin&lt; Base &gt;::briefDescription (bool abbreviate=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
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



Definition at line 175 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7dc1bbded3ac0ed218fff164f1da0504">175</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a7dc1bbded3ac0ed218fff164f1da0504">briefDescription</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a73a802f4c5838f2ebe51f19aa9c2d8ea">abbreviate</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.briefDescription(<a href="/web-doxygen/docs/api/files/src/definition-cpp/#a73a802f4c5838f2ebe51f19aa9c2d8ea">abbreviate</a>); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a73a802f4c5838f2ebe51f19aa9c2d8ea">abbreviate</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3824166b5b2188e8d18fa4c29f220aa5">MemberDefImpl::briefDescription</a>.
</div>
</div>

### briefDescriptionAsTooltip() {#a33c52548681bf6be9ef52027adb53f83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DefinitionMixin&lt; Base &gt;::briefDescriptionAsTooltip ()</td>
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



Definition at line 176 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a33c52548681bf6be9ef52027adb53f83">176</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a33c52548681bf6be9ef52027adb53f83">briefDescriptionAsTooltip</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.briefDescriptionAsTooltip(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### briefFile() {#a41226d110ae0c4514ec5d2acce3b5a1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DefinitionMixin&lt; Base &gt;::briefFile ()</td>
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



Definition at line 181 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a41226d110ae0c4514ec5d2acce3b5a1d">181</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a41226d110ae0c4514ec5d2acce3b5a1d">briefFile</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.briefFile(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.

Referenced by <a href="#a8934a29fc121ab4bffaedd8e960713bc">DefinitionMixin&lt; Base &gt;::setBriefDescription</a>.
</div>
</div>

### briefLine() {#ae6d1d3c3703fd95217c72b5e09e6026b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DefinitionMixin&lt; Base &gt;::briefLine ()</td>
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



Definition at line 177 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1d3c3703fd95217c72b5e09e6026b">177</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#ae6d1d3c3703fd95217c72b5e09e6026b">briefLine</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.briefLine(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.

Referenced by <a href="#a8934a29fc121ab4bffaedd8e960713bc">DefinitionMixin&lt; Base &gt;::setBriefDescription</a>.
</div>
</div>

### computeTooltip() {#ab7826eed19f5c7c6f60b781f66a2c4cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::computeTooltip ()</td>
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



Definition at line 289 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab7826eed19f5c7c6f60b781f66a2c4cb">289</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab7826eed19f5c7c6f60b781f66a2c4cb">computeTooltip</a>()</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.computeTooltip(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### docFile() {#a35745772d5cbc15835976d602ebae951}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DefinitionMixin&lt; Base &gt;::docFile ()</td>
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



Definition at line 174 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a35745772d5cbc15835976d602ebae951">174</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a35745772d5cbc15835976d602ebae951">docFile</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.docFile(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.

Referenced by <a href="#a57049ae0a543644fa13d44472098f7ae">DefinitionMixin&lt; Base &gt;::setDocumentation</a> and <a href="#a9dac0008b22397baee417797233657f4">DefinitionMixin&lt; Base &gt;::setInbodyDocumentation</a>.
</div>
</div>

### docLine() {#ad46b34a786acf616797f7ea22c733fca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DefinitionMixin&lt; Base &gt;::docLine ()</td>
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



Definition at line 173 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad46b34a786acf616797f7ea22c733fca">173</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#ad46b34a786acf616797f7ea22c733fca">docLine</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.docLine(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.

Referenced by <a href="#a57049ae0a543644fa13d44472098f7ae">DefinitionMixin&lt; Base &gt;::setDocumentation</a> and <a href="#a9dac0008b22397baee417797233657f4">DefinitionMixin&lt; Base &gt;::setInbodyDocumentation</a>.
</div>
</div>

### documentation() {#ae8fdeb361a15e2342867d47936e0e5cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DefinitionMixin&lt; Base &gt;::documentation ()</td>
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



Definition at line 172 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae8fdeb361a15e2342867d47936e0e5cd">172</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ae8fdeb361a15e2342867d47936e0e5cd">documentation</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.documentation(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ace184e297580f096238b97fc6c2f14c7">MemberDefImpl::documentation</a>.
</div>
</div>

### externalReference() {#a023727ef82a91c6c1fa150409180851b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DefinitionMixin&lt; Base &gt;::externalReference (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath)</td>
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



Definition at line 195 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a023727ef82a91c6c1fa150409180851b">195</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a023727ef82a91c6c1fa150409180851b">externalReference</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;relPath)</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.externalReference(relPath); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### findInnerCompound() {#ac8df42dc069675f2835ab89b73015cfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Definition * DefinitionMixin&lt; Base &gt;::findInnerCompound (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



Definition at line 204 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac8df42dc069675f2835ab89b73015cfe">204</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *<a href="#ac8df42dc069675f2835ab89b73015cfe">findInnerCompound</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#a084cf29cf38b39f8826f74300ec142a3">name</a>)</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.findInnerCompound(<a href="#a084cf29cf38b39f8826f74300ec142a3">name</a>); }</span></span></div>

</div>


References <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a> and <a href="#a084cf29cf38b39f8826f74300ec142a3">DefinitionMixin&lt; Base &gt;::name</a>.
</div>
</div>

### getBodyDef() {#accaec928eb70b0232fb7b1666cac3485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FileDef * DefinitionMixin&lt; Base &gt;::getBodyDef ()</td>
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



Definition at line 199 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#accaec928eb70b0232fb7b1666cac3485">199</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *<a href="#accaec928eb70b0232fb7b1666cac3485">getBodyDef</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.getBodyDef(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### getDefColumn() {#aeb503ebb52acc96c37bb3cd30190b72f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DefinitionMixin&lt; Base &gt;::getDefColumn ()</td>
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



Definition at line 185 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aeb503ebb52acc96c37bb3cd30190b72f">185</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#aeb503ebb52acc96c37bb3cd30190b72f">getDefColumn</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.getDefColumn(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### getDefFileExtension() {#a3c8ff898904d67dbed89c16e4bc4210b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DefinitionMixin&lt; Base &gt;::getDefFileExtension ()</td>
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



Definition at line 183 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3c8ff898904d67dbed89c16e4bc4210b">183</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a3c8ff898904d67dbed89c16e4bc4210b">getDefFileExtension</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.getDefFileExtension(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### getDefFileName() {#a110bf2aa0cf3af983ac301adb0483a2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DefinitionMixin&lt; Base &gt;::getDefFileName ()</td>
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



Definition at line 182 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a110bf2aa0cf3af983ac301adb0483a2f">182</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a110bf2aa0cf3af983ac301adb0483a2f">getDefFileName</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.getDefFileName(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a74e7d2dfc4dd50bd19a070adcdd48b71">ModuleDefImpl::mergeSymbolsFrom</a>.
</div>
</div>

### getDefLine() {#a016daf21744b5c79ec6232a7b247b042}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DefinitionMixin&lt; Base &gt;::getDefLine ()</td>
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



Definition at line 184 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a016daf21744b5c79ec6232a7b247b042">184</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a016daf21744b5c79ec6232a7b247b042">getDefLine</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.getDefLine(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a74e7d2dfc4dd50bd19a070adcdd48b71">ModuleDefImpl::mergeSymbolsFrom</a>.
</div>
</div>

### getEndBodyLine() {#aa4c29fec74b7015e02a76354c268f1d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DefinitionMixin&lt; Base &gt;::getEndBodyLine ()</td>
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



Definition at line 198 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa4c29fec74b7015e02a76354c268f1d6">198</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#aa4c29fec74b7015e02a76354c268f1d6">getEndBodyLine</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.getEndBodyLine(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### getLanguage() {#aff16f5c631848265076805fa667fc43a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SrcLangExt DefinitionMixin&lt; Base &gt;::getLanguage ()</td>
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



Definition at line 200 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aff16f5c631848265076805fa667fc43a">200</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> <a href="#aff16f5c631848265076805fa667fc43a">getLanguage</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.getLanguage(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### getOuterScope() {#a9205d504e802a7030d5f8408b0347176}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Definition * DefinitionMixin&lt; Base &gt;::getOuterScope ()</td>
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



Definition at line 205 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9205d504e802a7030d5f8408b0347176">205</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *<a href="#a9205d504e802a7030d5f8408b0347176">getOuterScope</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.getOuterScope(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### getReference() {#a9de91e7b1badbba3573f6c1827eab01c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DefinitionMixin&lt; Base &gt;::getReference ()</td>
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



Definition at line 193 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9de91e7b1badbba3573f6c1827eab01c">193</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a9de91e7b1badbba3573f6c1827eab01c">getReference</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.getReference(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a0164826d41cea9b086b19576f9d17e78">ClassDefImpl::getReference</a> and <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ac86cd7aa5ce2d8d62ce8d8ab3fc035af">MemberDefImpl::getReference</a>.
</div>
</div>

### getReferencedByMembers() {#a5e4ca19102a811875f1917b0caad407d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MemberVector &amp; DefinitionMixin&lt; Base &gt;::getReferencedByMembers ()</td>
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



Definition at line 207 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5e4ca19102a811875f1917b0caad407d">207</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/membervector">MemberVector</a> &amp;<a href="#a5e4ca19102a811875f1917b0caad407d">getReferencedByMembers</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.getReferencedByMembers(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### getReferencesMembers() {#a778beca21c8fde89bba352467dbcb655}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MemberVector &amp; DefinitionMixin&lt; Base &gt;::getReferencesMembers ()</td>
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



Definition at line 206 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a778beca21c8fde89bba352467dbcb655">206</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/membervector">MemberVector</a> &amp;<a href="#a778beca21c8fde89bba352467dbcb655">getReferencesMembers</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.getReferencesMembers(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### getSectionRefs() {#adef316d429538b09212c34eda65a5cab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SectionRefs &amp; DefinitionMixin&lt; Base &gt;::getSectionRefs ()</td>
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



Definition at line 212 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adef316d429538b09212c34eda65a5cab">212</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectionrefs">SectionRefs</a> &amp;<a href="#adef316d429538b09212c34eda65a5cab">getSectionRefs</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.getSectionRefs(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### getSourceAnchor() {#a456387716bea5b3efb759ae28e016012}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DefinitionMixin&lt; Base &gt;::getSourceAnchor ()</td>
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



Definition at line 171 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a456387716bea5b3efb759ae28e016012">171</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a456387716bea5b3efb759ae28e016012">getSourceAnchor</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.getSourceAnchor(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### getSourceFileBase() {#a6936f9ad8c00e760f0d3f2a9f71d8062}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DefinitionMixin&lt; Base &gt;::getSourceFileBase ()</td>
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



Definition at line 170 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6936f9ad8c00e760f0d3f2a9f71d8062">170</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a6936f9ad8c00e760f0d3f2a9f71d8062">getSourceFileBase</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.getSourceFileBase(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#afcb63a3b0089fb71f3f73a9b03c7fc31">ClassDefImpl::getSourceFileBase</a>.
</div>
</div>

### getStartBodyLine() {#acf6ad305b67c683d1d30c51f6f1c2b62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DefinitionMixin&lt; Base &gt;::getStartBodyLine ()</td>
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



Definition at line 197 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acf6ad305b67c683d1d30c51f6f1c2b62">197</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#acf6ad305b67c683d1d30c51f6f1c2b62">getStartBodyLine</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.getStartBodyLine(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### getStartDefLine() {#ad17428050c735af6bf1adf5507f53e8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DefinitionMixin&lt; Base &gt;::getStartDefLine ()</td>
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



Definition at line 196 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad17428050c735af6bf1adf5507f53e8f">196</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#ad17428050c735af6bf1adf5507f53e8f">getStartDefLine</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.getStartDefLine(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### hasBriefDescription() {#a2a93cd5cf5b0945e68de39ed6f7684df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DefinitionMixin&lt; Base &gt;::hasBriefDescription ()</td>
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



Definition at line 210 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2a93cd5cf5b0945e68de39ed6f7684df">210</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a2a93cd5cf5b0945e68de39ed6f7684df">hasBriefDescription</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.hasBriefDescription(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### hasDocumentation() {#afe3c1ea08436b40521d94878cadf9c0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DefinitionMixin&lt; Base &gt;::hasDocumentation ()</td>
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



Definition at line 186 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afe3c1ea08436b40521d94878cadf9c0f">186</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#afe3c1ea08436b40521d94878cadf9c0f">hasDocumentation</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.hasDocumentation(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae29d1e189d9b89a28dd51f26cab22f80">ClassDefImpl::hasDocumentation</a> and <a href="/web-doxygen/docs/api/classes/memberdefimpl/#abd0635e8066f90ac2b0b7fe1e2e52f6f">MemberDefImpl::hasDocumentation</a>.
</div>
</div>

### hasSections() {#ad372f7b60a11a8ca3a2ffa4a0ce12eb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DefinitionMixin&lt; Base &gt;::hasSections ()</td>
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



Definition at line 208 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad372f7b60a11a8ca3a2ffa4a0ce12eb4">208</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ad372f7b60a11a8ca3a2ffa4a0ce12eb4">hasSections</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.hasSections(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### hasSourceReffedBy() {#a8019928f9557a20ee13eb6d31e5e9943}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DefinitionMixin&lt; Base &gt;::hasSourceReffedBy ()</td>
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



Definition at line 263 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8019928f9557a20ee13eb6d31e5e9943">263</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a8019928f9557a20ee13eb6d31e5e9943">hasSourceReffedBy</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.hasSourceReffedBy(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### hasSourceRefs() {#ab3637501f75263f66aeeb56f088b9585}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DefinitionMixin&lt; Base &gt;::hasSourceRefs ()</td>
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



Definition at line 261 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab3637501f75263f66aeeb56f088b9585">261</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ab3637501f75263f66aeeb56f088b9585">hasSourceRefs</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.hasSourceRefs(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### hasSources() {#a3f6c82ff6cc6ccc6fc75c2399828e5ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DefinitionMixin&lt; Base &gt;::hasSources ()</td>
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



Definition at line 209 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3f6c82ff6cc6ccc6fc75c2399828e5ee">209</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a3f6c82ff6cc6ccc6fc75c2399828e5ee">hasSources</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.hasSources(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### hasUserDocumentation() {#a0aaa947a6a57bf5c7698f8c854f7ebb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DefinitionMixin&lt; Base &gt;::hasUserDocumentation ()</td>
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



Definition at line 187 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0aaa947a6a57bf5c7698f8c854f7ebb9">187</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a0aaa947a6a57bf5c7698f8c854f7ebb9">hasUserDocumentation</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.hasUserDocumentation(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a42eb6508c403c170f82da3c1023acdd2">MemberDefImpl::hasUserDocumentation</a>.
</div>
</div>

### id() {#a5664b56e962bcc049e8a59cd3ffe5a68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DefinitionMixin&lt; Base &gt;::id ()</td>
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



Definition at line 211 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5664b56e962bcc049e8a59cd3ffe5a68">211</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a5664b56e962bcc049e8a59cd3ffe5a68">id</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.id(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### inbodyDocumentation() {#ad3ac9d5d6118dcce7ece8ca2b4cfbb25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DefinitionMixin&lt; Base &gt;::inbodyDocumentation ()</td>
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



Definition at line 178 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad3ac9d5d6118dcce7ece8ca2b4cfbb25">178</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ad3ac9d5d6118dcce7ece8ca2b4cfbb25">inbodyDocumentation</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.inbodyDocumentation(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### inbodyFile() {#a0c0d049fa0196e7b240dcc35d349ab5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DefinitionMixin&lt; Base &gt;::inbodyFile ()</td>
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



Definition at line 179 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0c0d049fa0196e7b240dcc35d349ab5b">179</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a0c0d049fa0196e7b240dcc35d349ab5b">inbodyFile</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.inbodyFile(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### inbodyLine() {#ad667c5e00fe9063054fd9bf4d25b3b88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DefinitionMixin&lt; Base &gt;::inbodyLine ()</td>
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



Definition at line 180 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad667c5e00fe9063054fd9bf4d25b3b88">180</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#ad667c5e00fe9063054fd9bf4d25b3b88">inbodyLine</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.inbodyLine(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### isAlias() {#acc207912ee434d4be81444f20f758c42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DefinitionMixin&lt; Base &gt;::isAlias ()</td>
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



Definition at line 162 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acc207912ee434d4be81444f20f758c42">162</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#acc207912ee434d4be81444f20f758c42">isAlias</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>; }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>.
</div>
</div>

### isAnonymous() {#a4e8481d8676dbc4609b6164c38a3d106}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DefinitionMixin&lt; Base &gt;::isAnonymous ()</td>
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



Definition at line 166 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4e8481d8676dbc4609b6164c38a3d106">166</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a4e8481d8676dbc4609b6164c38a3d106">isAnonymous</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.isAnonymous(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### isArtificial() {#ae1b90ef5245bf2fffa90b41da2f9f66e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DefinitionMixin&lt; Base &gt;::isArtificial ()</td>
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



Definition at line 191 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae1b90ef5245bf2fffa90b41da2f9f66e">191</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae1b90ef5245bf2fffa90b41da2f9f66e">isArtificial</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.isArtificial(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### isExported() {#a1c14be8556addce7b154dc26059ecd5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DefinitionMixin&lt; Base &gt;::isExported ()</td>
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



Definition at line 192 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c14be8556addce7b154dc26059ecd5e">192</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a1c14be8556addce7b154dc26059ecd5e">isExported</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.isExported(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### isHidden() {#ab5feda26fd74e0f0c430132b36942f4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DefinitionMixin&lt; Base &gt;::isHidden ()</td>
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



Definition at line 190 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab5feda26fd74e0f0c430132b36942f4c">190</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ab5feda26fd74e0f0c430132b36942f4c">isHidden</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.isHidden(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### isLinkableViaGroup() {#a1b4737d666571fd4e7868030a322b42f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DefinitionMixin&lt; Base &gt;::isLinkableViaGroup ()</td>
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



Definition at line 202 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1b4737d666571fd4e7868030a322b42f">202</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a1b4737d666571fd4e7868030a322b42f">isLinkableViaGroup</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.isLinkableViaGroup(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### isReference() {#a02af6a985756c345fcc5b94962c11213}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DefinitionMixin&lt; Base &gt;::isReference ()</td>
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



Definition at line 194 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a02af6a985756c345fcc5b94962c11213">194</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a02af6a985756c345fcc5b94962c11213">isReference</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.isReference(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a6cfddb7b53727313068eaeb3d11cc47d">ClassDefImpl::isReference</a> and <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a2e5d400dee873383aba9435ca6bf6560">MemberDefImpl::isReference</a>.
</div>
</div>

### isVisible() {#ab5e39836930c40293df64e90d435ef40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DefinitionMixin&lt; Base &gt;::isVisible ()</td>
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



Definition at line 189 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab5e39836930c40293df64e90d435ef40">189</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ab5e39836930c40293df64e90d435ef40">isVisible</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.isVisible(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### isVisibleInProject() {#a180f4796532e181fc5bb1014c7a77d9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DefinitionMixin&lt; Base &gt;::isVisibleInProject ()</td>
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



Definition at line 188 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a180f4796532e181fc5bb1014c7a77d9a">188</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a180f4796532e181fc5bb1014c7a77d9a">isVisibleInProject</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.isVisibleInProject(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### localName() {#aaef9557cbcd9ef70171b43669cbf69e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const QCString &amp; DefinitionMixin&lt; Base &gt;::localName ()</td>
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



Definition at line 167 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaef9557cbcd9ef70171b43669cbf69e4">167</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#aaef9557cbcd9ef70171b43669cbf69e4">localName</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.localName(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### makePartOfGroup() {#a68421bb76ed3da467e074ecb06e5cf12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::makePartOfGroup (<a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> * gd)</td>
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



Definition at line 269 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a68421bb76ed3da467e074ecb06e5cf12">269</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a68421bb76ed3da467e074ecb06e5cf12">makePartOfGroup</a>(<a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *gd)</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.makePartOfGroup(gd); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### mergeReferencedBy() {#aa14c9f0a9553f1bf85c0a71c921e441c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::mergeReferencedBy (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * other)</td>
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



Definition at line 243 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa14c9f0a9553f1bf85c0a71c921e441c">243</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa14c9f0a9553f1bf85c0a71c921e441c">mergeReferencedBy</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *other)</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.mergeReferencedBy(other); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### mergeReferences() {#a6b8996a6213108c6d925e284d372bf26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::mergeReferences (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * other)</td>
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



Definition at line 241 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6b8996a6213108c6d925e284d372bf26">241</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6b8996a6213108c6d925e284d372bf26">mergeReferences</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *other)</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.mergeReferences(other); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### mergeRefItems() {#abbbd4d57b3f9c4c6a1bf436a6418c499}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::mergeRefItems (<a href="/web-doxygen/docs/api/classes/definition">Definition</a> * def)</td>
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



Definition at line 239 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abbbd4d57b3f9c4c6a1bf436a6418c499">239</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abbbd4d57b3f9c4c6a1bf436a6418c499">mergeRefItems</a>(<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *def)</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.mergeRefItems(def); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### name() {#a084cf29cf38b39f8826f74300ec142a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const QCString &amp; DefinitionMixin&lt; Base &gt;::name ()</td>
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



Definition at line 165 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a084cf29cf38b39f8826f74300ec142a3">165</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#a084cf29cf38b39f8826f74300ec142a3">name</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.name(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.

Referenced by <a href="#a1f425520bda2df8a42b4a804806879cc">DefinitionMixin&lt; Base &gt;::\_setSymbolName</a>, <a href="#aa314c6a73e812b62d5e991ebd695cdd1">DefinitionMixin&lt; Base &gt;::DefinitionMixin</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a29f03d38a8c3a17ed8bfd7c7b45aedf0">GroupDefImpl::displayName</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a665ab7cf57db208502f36d382cf88ce6">MemberDefImpl::displayName</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#aa97380304b365c704f3198fc66efa73d">PageDefImpl::displayName</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac43c4867446413fa46a4d1140f40eb9f">FileDefImpl::FileDefImpl</a>, <a href="#ac8df42dc069675f2835ab89b73015cfe">DefinitionMixin&lt; Base &gt;::findInnerCompound</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a864e550c852235c136046b55066365a6">FileDefImpl::name</a>, <a href="#a34b916976d8f272c97f00d74001fdd0c">DefinitionMixin&lt; Base &gt;::setId</a>, <a href="#abf40dcb168e2a970e68dabbcbde25ee6">DefinitionMixin&lt; Base &gt;::setLocalName</a> and <a href="#a7d64f115d59d2667225ea684dfd2aa9d">DefinitionMixin&lt; Base &gt;::setName</a>.
</div>
</div>

### navigationPathAsString() {#af64c20fb61ef66db149815f84ef20124}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DefinitionMixin&lt; Base &gt;::navigationPathAsString ()</td>
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



Definition at line 273 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af64c20fb61ef66db149815f84ef20124">273</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#af64c20fb61ef66db149815f84ef20124">navigationPathAsString</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.navigationPathAsString(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### partOfGroups() {#ac930798d5e2008a99386890ea44f8625}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GroupList &amp; DefinitionMixin&lt; Base &gt;::partOfGroups ()</td>
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



Definition at line 201 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac930798d5e2008a99386890ea44f8625">201</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/grouplist">GroupList</a> &amp;<a href="#ac930798d5e2008a99386890ea44f8625">partOfGroups</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.partOfGroups(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### pathFragment() {#a923515abd1bebf6566f807b4dc2e02bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DefinitionMixin&lt; Base &gt;::pathFragment ()</td>
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



Definition at line 281 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a923515abd1bebf6566f807b4dc2e02bd">281</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a923515abd1bebf6566f807b4dc2e02bd">pathFragment</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.pathFragment(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### qualifiedName() {#a47fbd183e7875e3446a5a5059fc3fc18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DefinitionMixin&lt; Base &gt;::qualifiedName ()</td>
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



Definition at line 168 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a47fbd183e7875e3446a5a5059fc3fc18">168</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a47fbd183e7875e3446a5a5059fc3fc18">qualifiedName</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.qualifiedName(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a2321a445b1cd8afde4016715417435eb">MemberDefImpl::qualifiedName</a>.
</div>
</div>

### setArtificial() {#a6faed3bc5a08c5f991d1223b11f46bc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::setArtificial (bool b)</td>
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



Definition at line 251 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6faed3bc5a08c5f991d1223b11f46bc7">251</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6faed3bc5a08c5f991d1223b11f46bc7">setArtificial</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b)</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.setArtificial(b); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### setBodyDef() {#aa6dbecf61d4840467a33899011d0cb11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::setBodyDef (const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd)</td>
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



Definition at line 231 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa6dbecf61d4840467a33899011d0cb11">231</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa6dbecf61d4840467a33899011d0cb11">setBodyDef</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd)</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.setBodyDef(fd); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### setBodySegment() {#a09634fd6d1779376b3c53141ba3f3d26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::setBodySegment (int defLine, int bls, int ble)</td>
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



Definition at line 229 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a09634fd6d1779376b3c53141ba3f3d26">229</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a09634fd6d1779376b3c53141ba3f3d26">setBodySegment</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> defLine,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> bls,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> ble)</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.setBodySegment(defLine,bls,ble); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### setBriefDescription() {#a8934a29fc121ab4bffaedd8e960713bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::setBriefDescription (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; brief, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; briefFile, int briefLine)</td>
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



Definition at line 221 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8934a29fc121ab4bffaedd8e960713bc">221</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8934a29fc121ab4bffaedd8e960713bc">setBriefDescription</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;brief,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#a41226d110ae0c4514ec5d2acce3b5a1d">briefFile</a>,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#ae6d1d3c3703fd95217c72b5e09e6026b">briefLine</a>)</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.setBriefDescription(brief,<a href="#a41226d110ae0c4514ec5d2acce3b5a1d">briefFile</a>,<a href="#ae6d1d3c3703fd95217c72b5e09e6026b">briefLine</a>); }</span></span></div>

</div>


References <a href="#a41226d110ae0c4514ec5d2acce3b5a1d">DefinitionMixin&lt; Base &gt;::briefFile</a>, <a href="#ae6d1d3c3703fd95217c72b5e09e6026b">DefinitionMixin&lt; Base &gt;::briefLine</a> and <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#af801e76c7e6cdaa106fb020538267e08">MemberDefImpl::setBriefDescription</a>.
</div>
</div>

### setDefFile() {#ad1c72eb42ed909d2056c16f3bcbf960f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::setDefFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; df, int defLine, int defColumn)</td>
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



Definition at line 217 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad1c72eb42ed909d2056c16f3bcbf960f">217</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad1c72eb42ed909d2056c16f3bcbf960f">setDefFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>&amp; df,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> defLine,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> defColumn)</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.setDefFile(df,defLine,defColumn); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### setDocumentation() {#a57049ae0a543644fa13d44472098f7ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::setDocumentation (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; doc, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; docFile, int docLine, bool stripWhiteSpace=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</td>
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



Definition at line 219 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a57049ae0a543644fa13d44472098f7ae">219</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a57049ae0a543644fa13d44472098f7ae">setDocumentation</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;doc,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#a35745772d5cbc15835976d602ebae951">docFile</a>,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#ad46b34a786acf616797f7ea22c733fca">docLine</a>,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/stringutil-h/#aef47e534975880014a6514745e885a99">stripWhiteSpace</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.setDocumentation(doc,<a href="#a35745772d5cbc15835976d602ebae951">docFile</a>,<a href="#ad46b34a786acf616797f7ea22c733fca">docLine</a>,<a href="/web-doxygen/docs/api/files/src/stringutil-h/#aef47e534975880014a6514745e885a99">stripWhiteSpace</a>); }</span></span></div>

</div>


References <a href="#a35745772d5cbc15835976d602ebae951">DefinitionMixin&lt; Base &gt;::docFile</a>, <a href="#ad46b34a786acf616797f7ea22c733fca">DefinitionMixin&lt; Base &gt;::docLine</a>, <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>, <a href="/web-doxygen/docs/api/files/src/stringutil-h/#aef47e534975880014a6514745e885a99">stripWhiteSpace</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a56fca82d471e653da6daf3177a58a270">MemberDefImpl::setDocumentation</a>.
</div>
</div>

### setExported() {#a71b4c90ca024920118d6da8ac61ea689}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::setExported (bool b)</td>
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



Definition at line 253 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a71b4c90ca024920118d6da8ac61ea689">253</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a71b4c90ca024920118d6da8ac61ea689">setExported</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b)</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.setExported(b); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### setHidden() {#adb72e3dd9d7e09222e8b351c744d844e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::setHidden (bool b)</td>
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



Definition at line 249 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adb72e3dd9d7e09222e8b351c744d844e">249</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#adb72e3dd9d7e09222e8b351c744d844e">setHidden</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b)</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.setHidden(b); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a18dbfa828cd48e261c2558ea4dcebb52">MemberDefImpl::setHidden</a>.
</div>
</div>

### setId() {#a34b916976d8f272c97f00d74001fdd0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::setId (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



Definition at line 216 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a34b916976d8f272c97f00d74001fdd0c">216</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a34b916976d8f272c97f00d74001fdd0c">setId</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#a084cf29cf38b39f8826f74300ec142a3">name</a>)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.setId(<a href="#a084cf29cf38b39f8826f74300ec142a3">name</a>); }</span></span></div>

</div>


References <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a> and <a href="#a084cf29cf38b39f8826f74300ec142a3">DefinitionMixin&lt; Base &gt;::name</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/modulemanager/#a698e0a915bfb6a6d27731b5290580c96">ModuleManager::addTagInfo</a>.
</div>
</div>

### setInbodyDocumentation() {#a9dac0008b22397baee417797233657f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::setInbodyDocumentation (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; doc, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; docFile, int docLine)</td>
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



Definition at line 223 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9dac0008b22397baee417797233657f4">223</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9dac0008b22397baee417797233657f4">setInbodyDocumentation</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;doc,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#a35745772d5cbc15835976d602ebae951">docFile</a>,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#ad46b34a786acf616797f7ea22c733fca">docLine</a>)</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.setInbodyDocumentation(doc,<a href="#a35745772d5cbc15835976d602ebae951">docFile</a>,<a href="#ad46b34a786acf616797f7ea22c733fca">docLine</a>); }</span></span></div>

</div>


References <a href="#a35745772d5cbc15835976d602ebae951">DefinitionMixin&lt; Base &gt;::docFile</a>, <a href="#ad46b34a786acf616797f7ea22c733fca">DefinitionMixin&lt; Base &gt;::docLine</a> and <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a9c839795961099b7cc26d24b267910d7">MemberDefImpl::setInbodyDocumentation</a>.
</div>
</div>

### setLanguage() {#a513b45b150ca956112360ccf93f7cebd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::setLanguage (<a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang)</td>
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



Definition at line 255 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a513b45b150ca956112360ccf93f7cebd">255</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a513b45b150ca956112360ccf93f7cebd">setLanguage</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang)</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.setLanguage(lang); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### setLocalName() {#abf40dcb168e2a970e68dabbcbde25ee6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::setLocalName (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



Definition at line 285 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abf40dcb168e2a970e68dabbcbde25ee6">285</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abf40dcb168e2a970e68dabbcbde25ee6">setLocalName</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#a084cf29cf38b39f8826f74300ec142a3">name</a>)</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.setLocalName(<a href="#a084cf29cf38b39f8826f74300ec142a3">name</a>); }</span></span></div>

</div>


References <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a> and <a href="#a084cf29cf38b39f8826f74300ec142a3">DefinitionMixin&lt; Base &gt;::name</a>.
</div>
</div>

### setName() {#a7d64f115d59d2667225ea684dfd2aa9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::setName (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



Definition at line 215 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7d64f115d59d2667225ea684dfd2aa9d">215</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7d64f115d59d2667225ea684dfd2aa9d">setName</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#a084cf29cf38b39f8826f74300ec142a3">name</a>)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.setName(<a href="#a084cf29cf38b39f8826f74300ec142a3">name</a>); }</span></span></div>

</div>


References <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a> and <a href="#a084cf29cf38b39f8826f74300ec142a3">DefinitionMixin&lt; Base &gt;::name</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ad69defdcb3fb2c2d26fe2e5a15e8f723">NamespaceDefImpl::setName</a>.
</div>
</div>

### setOuterScope() {#a5701961a47f8f5336495771c8d3d611d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::setOuterScope (<a href="/web-doxygen/docs/api/classes/definition">Definition</a> * def)</td>
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



Definition at line 247 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5701961a47f8f5336495771c8d3d611d">247</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5701961a47f8f5336495771c8d3d611d">setOuterScope</a>(<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *def)</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.setOuterScope(def); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### setReference() {#a5b7806d54dc3504a626078ac0d22dc19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::setReference (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; r)</td>
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



Definition at line 225 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5b7806d54dc3504a626078ac0d22dc19">225</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5b7806d54dc3504a626078ac0d22dc19">setReference</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;r)</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.setReference(r); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/modulemanager/#a698e0a915bfb6a6d27731b5290580c96">ModuleManager::addTagInfo</a>.
</div>
</div>

### setRefItems() {#af1dfd6ae62c6a43f590645a80fc039a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::setRefItems (const <a href="/web-doxygen/docs/api/files/src/reflist-h/#a51b03784d48079baab06a4d5c8b08c42">RefItemVector</a> &amp; sli)</td>
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



Definition at line 237 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af1dfd6ae62c6a43f590645a80fc039a7">237</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af1dfd6ae62c6a43f590645a80fc039a7">setRefItems</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/reflist-h/#a51b03784d48079baab06a4d5c8b08c42">RefItemVector</a> &amp;sli)</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.setRefItems(sli); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### symbolName() {#a5d92005bf382f44874dc7b34196a1ac4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DefinitionMixin&lt; Base &gt;::symbolName ()</td>
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



Definition at line 169 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5d92005bf382f44874dc7b34196a1ac4">169</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a5d92005bf382f44874dc7b34196a1ac4">symbolName</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.symbolName(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### writeDocAnchorsToTagFile() {#afcd2841ebfa088d88d8624e5f54f1aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::writeDocAnchorsToTagFile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; fs)</td>
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



Definition at line 283 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afcd2841ebfa088d88d8624e5f54f1aa9">283</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afcd2841ebfa088d88d8624e5f54f1aa9">writeDocAnchorsToTagFile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;fs)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.writeDocAnchorsToTagFile(fs); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### writeInlineCode() {#ab4f70a9c2798cb1b656a002e28af6a87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::writeInlineCode (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; scopeName)</td>
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



Definition at line 259 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab4f70a9c2798cb1b656a002e28af6a87">259</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab4f70a9c2798cb1b656a002e28af6a87">writeInlineCode</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;scopeName)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.writeInlineCode(ol,scopeName); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### writeNavigationPath() {#a1920f150021e040075a423418fb0e85a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::writeNavigationPath (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
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



Definition at line 271 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1920f150021e040075a423418fb0e85a">271</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1920f150021e040075a423418fb0e85a">writeNavigationPath</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.writeNavigationPath(ol); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### writePageNavigation() {#a48df7719d4f28f55162adc4b1064699b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::writePageNavigation (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
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



Definition at line 279 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a48df7719d4f28f55162adc4b1064699b">279</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a48df7719d4f28f55162adc4b1064699b">writePageNavigation</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.writePageNavigation(ol); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### writeQuickMemberLinks() {#ad191384d79c44e12ae31ee900209c3c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::writeQuickMemberLinks (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md)</td>
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



Definition at line 275 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad191384d79c44e12ae31ee900209c3c6">275</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad191384d79c44e12ae31ee900209c3c6">writeQuickMemberLinks</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.writeQuickMemberLinks(ol,md); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### writeSourceDef() {#a0922bcff85f540f991fd4e5fd3a68a02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::writeSourceDef (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
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



Definition at line 257 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0922bcff85f540f991fd4e5fd3a68a02">257</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0922bcff85f540f991fd4e5fd3a68a02">writeSourceDef</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.writeSourceDef(ol); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### writeSourceReffedBy() {#a91fa887054f1f3aafb9bb330491b8f84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::writeSourceReffedBy (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; scopeName)</td>
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



Definition at line 267 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91fa887054f1f3aafb9bb330491b8f84">267</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a91fa887054f1f3aafb9bb330491b8f84">writeSourceReffedBy</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;scopeName)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.writeSourceReffedBy(ol,scopeName); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### writeSourceRefs() {#a24663e9c959433e58e8e102ad4306814}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::writeSourceRefs (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; scopeName)</td>
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



Definition at line 265 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a24663e9c959433e58e8e102ad4306814">265</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a24663e9c959433e58e8e102ad4306814">writeSourceRefs</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;scopeName)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.writeSourceRefs(ol,scopeName); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### writeSummaryLinks() {#ad951f2f7aef7a2408a8bafc08b7b5899}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::writeSummaryLinks (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
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



Definition at line 277 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad951f2f7aef7a2408a8bafc08b7b5899">277</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad951f2f7aef7a2408a8bafc08b7b5899">writeSummaryLinks</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.writeSummaryLinks(ol); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### writeToc() {#ad12243a0430f318cbe3b499ca21c9e4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefinitionMixin&lt; Base &gt;::writeToc (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/localtoc">LocalToc</a> &amp; lt)</td>
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



Definition at line 287 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad12243a0430f318cbe3b499ca21c9e4b">287</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad12243a0430f318cbe3b499ca21c9e4b">writeToc</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/localtoc">LocalToc</a> &amp;lt)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.writeToc(ol,lt); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### xrefListItems() {#a7080c8c1be27b05ba64f160655530571}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RefItemVector &amp; DefinitionMixin&lt; Base &gt;::xrefListItems ()</td>
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



Definition at line 203 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7080c8c1be27b05ba64f160655530571">203</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/reflist-h/#a51b03784d48079baab06a4d5c8b08c42">RefItemVector</a> &amp;<a href="#a7080c8c1be27b05ba64f160655530571">xrefListItems</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>.xrefListItems(); }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### toDefinition\_() {#ab644c9a49a1aeb38b65e9edb4f11d9e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Definition * DefinitionMixin&lt; Base &gt;::toDefinition_ ()</td>
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



Definition at line 297 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab644c9a49a1aeb38b65e9edb4f11d9e1">297</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *<a href="#ab644c9a49a1aeb38b65e9edb4f11d9e1">toDefinition_</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">; }</span></span></div>

</div>

</div>
</div>

### toDefinitionImpl\_() {#a8344f08e2dda50c48becfde382067b46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DefinitionImpl * DefinitionMixin&lt; Base &gt;::toDefinitionImpl_ ()</td>
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



Definition at line 299 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8344f08e2dda50c48becfde382067b46">299</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definitionimpl">DefinitionImpl</a> *<a href="#a8344f08e2dda50c48becfde382067b46">toDefinitionImpl_</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> &amp;<a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>; }</span></span></div>

</div>


Reference <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">DefinitionMixin&lt; Base &gt;::m\_impl</a>.
</div>
</div>

### toDefinitionMutable\_() {#a0b28f6bdf8b17b0c89b4ea1a69129527}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DefinitionMutable * DefinitionMixin&lt; Base &gt;::toDefinitionMutable_ ()</td>
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



Definition at line 298 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0b28f6bdf8b17b0c89b4ea1a69129527">298</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/definitionmutable">DefinitionMutable</a> *<a href="#a0b28f6bdf8b17b0c89b4ea1a69129527">toDefinitionMutable_</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">; }</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_impl {#ad289ca02baba6cbd480afa1e9bbc27c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Base&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DefinitionImpl DefinitionMixin&lt; Base &gt;::m_impl</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 301 of file <a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad289ca02baba6cbd480afa1e9bbc27c1">301</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/definitionimpl">DefinitionImpl</a> <a href="#ad289ca02baba6cbd480afa1e9bbc27c1">m_impl</a>;</span></span></div>

</div>


Referenced by <a href="#a1f425520bda2df8a42b4a804806879cc">DefinitionMixin&lt; Base &gt;::\_setSymbolName</a>, <a href="#a2a045a5eb349b5ed419a067c2d2fde96">DefinitionMixin&lt; Base &gt;::\_symbolName</a>, <a href="#a3e1056f3e52c899cbb2ea8b4b513748f">DefinitionMixin&lt; Base &gt;::addInnerCompound</a>, <a href="#a2367c2405cb856670d78d45053cbe2c7">DefinitionMixin&lt; Base &gt;::addSectionsToDefinition</a>, <a href="#a3bd511a0977bf2621a15edbe0d90ed32">DefinitionMixin&lt; Base &gt;::addSourceReferencedBy</a>, <a href="#a963c53f9395e89eb1c3a12e40cbf51b9">DefinitionMixin&lt; Base &gt;::addSourceReferences</a>, <a href="#a7dc1bbded3ac0ed218fff164f1da0504">DefinitionMixin&lt; Base &gt;::briefDescription</a>, <a href="#a33c52548681bf6be9ef52027adb53f83">DefinitionMixin&lt; Base &gt;::briefDescriptionAsTooltip</a>, <a href="#a41226d110ae0c4514ec5d2acce3b5a1d">DefinitionMixin&lt; Base &gt;::briefFile</a>, <a href="#ae6d1d3c3703fd95217c72b5e09e6026b">DefinitionMixin&lt; Base &gt;::briefLine</a>, <a href="#ab7826eed19f5c7c6f60b781f66a2c4cb">DefinitionMixin&lt; Base &gt;::computeTooltip</a>, <a href="#a9b3cbc90a75238c4231cbaad9107f13f">DefinitionMixin&lt; Base &gt;::DefinitionMixin</a>, <a href="#aa314c6a73e812b62d5e991ebd695cdd1">DefinitionMixin&lt; Base &gt;::DefinitionMixin</a>, <a href="#a35745772d5cbc15835976d602ebae951">DefinitionMixin&lt; Base &gt;::docFile</a>, <a href="#ad46b34a786acf616797f7ea22c733fca">DefinitionMixin&lt; Base &gt;::docLine</a>, <a href="#ae8fdeb361a15e2342867d47936e0e5cd">DefinitionMixin&lt; Base &gt;::documentation</a>, <a href="#a023727ef82a91c6c1fa150409180851b">DefinitionMixin&lt; Base &gt;::externalReference</a>, <a href="#ac8df42dc069675f2835ab89b73015cfe">DefinitionMixin&lt; Base &gt;::findInnerCompound</a>, <a href="#accaec928eb70b0232fb7b1666cac3485">DefinitionMixin&lt; Base &gt;::getBodyDef</a>, <a href="#aeb503ebb52acc96c37bb3cd30190b72f">DefinitionMixin&lt; Base &gt;::getDefColumn</a>, <a href="#a3c8ff898904d67dbed89c16e4bc4210b">DefinitionMixin&lt; Base &gt;::getDefFileExtension</a>, <a href="#a110bf2aa0cf3af983ac301adb0483a2f">DefinitionMixin&lt; Base &gt;::getDefFileName</a>, <a href="#a016daf21744b5c79ec6232a7b247b042">DefinitionMixin&lt; Base &gt;::getDefLine</a>, <a href="#aa4c29fec74b7015e02a76354c268f1d6">DefinitionMixin&lt; Base &gt;::getEndBodyLine</a>, <a href="#aff16f5c631848265076805fa667fc43a">DefinitionMixin&lt; Base &gt;::getLanguage</a>, <a href="#a9205d504e802a7030d5f8408b0347176">DefinitionMixin&lt; Base &gt;::getOuterScope</a>, <a href="#a9de91e7b1badbba3573f6c1827eab01c">DefinitionMixin&lt; Base &gt;::getReference</a>, <a href="#a5e4ca19102a811875f1917b0caad407d">DefinitionMixin&lt; Base &gt;::getReferencedByMembers</a>, <a href="#a778beca21c8fde89bba352467dbcb655">DefinitionMixin&lt; Base &gt;::getReferencesMembers</a>, <a href="#adef316d429538b09212c34eda65a5cab">DefinitionMixin&lt; Base &gt;::getSectionRefs</a>, <a href="#a456387716bea5b3efb759ae28e016012">DefinitionMixin&lt; Base &gt;::getSourceAnchor</a>, <a href="#a6936f9ad8c00e760f0d3f2a9f71d8062">DefinitionMixin&lt; Base &gt;::getSourceFileBase</a>, <a href="#acf6ad305b67c683d1d30c51f6f1c2b62">DefinitionMixin&lt; Base &gt;::getStartBodyLine</a>, <a href="#ad17428050c735af6bf1adf5507f53e8f">DefinitionMixin&lt; Base &gt;::getStartDefLine</a>, <a href="#a2a93cd5cf5b0945e68de39ed6f7684df">DefinitionMixin&lt; Base &gt;::hasBriefDescription</a>, <a href="#afe3c1ea08436b40521d94878cadf9c0f">DefinitionMixin&lt; Base &gt;::hasDocumentation</a>, <a href="#ad372f7b60a11a8ca3a2ffa4a0ce12eb4">DefinitionMixin&lt; Base &gt;::hasSections</a>, <a href="#a8019928f9557a20ee13eb6d31e5e9943">DefinitionMixin&lt; Base &gt;::hasSourceReffedBy</a>, <a href="#ab3637501f75263f66aeeb56f088b9585">DefinitionMixin&lt; Base &gt;::hasSourceRefs</a>, <a href="#a3f6c82ff6cc6ccc6fc75c2399828e5ee">DefinitionMixin&lt; Base &gt;::hasSources</a>, <a href="#a0aaa947a6a57bf5c7698f8c854f7ebb9">DefinitionMixin&lt; Base &gt;::hasUserDocumentation</a>, <a href="#a5664b56e962bcc049e8a59cd3ffe5a68">DefinitionMixin&lt; Base &gt;::id</a>, <a href="#ad3ac9d5d6118dcce7ece8ca2b4cfbb25">DefinitionMixin&lt; Base &gt;::inbodyDocumentation</a>, <a href="#a0c0d049fa0196e7b240dcc35d349ab5b">DefinitionMixin&lt; Base &gt;::inbodyFile</a>, <a href="#ad667c5e00fe9063054fd9bf4d25b3b88">DefinitionMixin&lt; Base &gt;::inbodyLine</a>, <a href="#a4e8481d8676dbc4609b6164c38a3d106">DefinitionMixin&lt; Base &gt;::isAnonymous</a>, <a href="#ae1b90ef5245bf2fffa90b41da2f9f66e">DefinitionMixin&lt; Base &gt;::isArtificial</a>, <a href="#a1c14be8556addce7b154dc26059ecd5e">DefinitionMixin&lt; Base &gt;::isExported</a>, <a href="#ab5feda26fd74e0f0c430132b36942f4c">DefinitionMixin&lt; Base &gt;::isHidden</a>, <a href="#a1b4737d666571fd4e7868030a322b42f">DefinitionMixin&lt; Base &gt;::isLinkableViaGroup</a>, <a href="#a02af6a985756c345fcc5b94962c11213">DefinitionMixin&lt; Base &gt;::isReference</a>, <a href="#ab5e39836930c40293df64e90d435ef40">DefinitionMixin&lt; Base &gt;::isVisible</a>, <a href="#a180f4796532e181fc5bb1014c7a77d9a">DefinitionMixin&lt; Base &gt;::isVisibleInProject</a>, <a href="#aaef9557cbcd9ef70171b43669cbf69e4">DefinitionMixin&lt; Base &gt;::localName</a>, <a href="#a68421bb76ed3da467e074ecb06e5cf12">DefinitionMixin&lt; Base &gt;::makePartOfGroup</a>, <a href="#aa14c9f0a9553f1bf85c0a71c921e441c">DefinitionMixin&lt; Base &gt;::mergeReferencedBy</a>, <a href="#a6b8996a6213108c6d925e284d372bf26">DefinitionMixin&lt; Base &gt;::mergeReferences</a>, <a href="#abbbd4d57b3f9c4c6a1bf436a6418c499">DefinitionMixin&lt; Base &gt;::mergeRefItems</a>, <a href="#a084cf29cf38b39f8826f74300ec142a3">DefinitionMixin&lt; Base &gt;::name</a>, <a href="#af64c20fb61ef66db149815f84ef20124">DefinitionMixin&lt; Base &gt;::navigationPathAsString</a>, <a href="#a2b18a1e181f0001e50887bfb0e2f32a7">DefinitionMixin&lt; Base &gt;::operator=</a>, <a href="#ac930798d5e2008a99386890ea44f8625">DefinitionMixin&lt; Base &gt;::partOfGroups</a>, <a href="#a923515abd1bebf6566f807b4dc2e02bd">DefinitionMixin&lt; Base &gt;::pathFragment</a>, <a href="#a47fbd183e7875e3446a5a5059fc3fc18">DefinitionMixin&lt; Base &gt;::qualifiedName</a>, <a href="#a6faed3bc5a08c5f991d1223b11f46bc7">DefinitionMixin&lt; Base &gt;::setArtificial</a>, <a href="#aa6dbecf61d4840467a33899011d0cb11">DefinitionMixin&lt; Base &gt;::setBodyDef</a>, <a href="#a09634fd6d1779376b3c53141ba3f3d26">DefinitionMixin&lt; Base &gt;::setBodySegment</a>, <a href="#a8934a29fc121ab4bffaedd8e960713bc">DefinitionMixin&lt; Base &gt;::setBriefDescription</a>, <a href="#ad1c72eb42ed909d2056c16f3bcbf960f">DefinitionMixin&lt; Base &gt;::setDefFile</a>, <a href="#a57049ae0a543644fa13d44472098f7ae">DefinitionMixin&lt; Base &gt;::setDocumentation</a>, <a href="#a71b4c90ca024920118d6da8ac61ea689">DefinitionMixin&lt; Base &gt;::setExported</a>, <a href="#adb72e3dd9d7e09222e8b351c744d844e">DefinitionMixin&lt; Base &gt;::setHidden</a>, <a href="#a34b916976d8f272c97f00d74001fdd0c">DefinitionMixin&lt; Base &gt;::setId</a>, <a href="#a9dac0008b22397baee417797233657f4">DefinitionMixin&lt; Base &gt;::setInbodyDocumentation</a>, <a href="#a513b45b150ca956112360ccf93f7cebd">DefinitionMixin&lt; Base &gt;::setLanguage</a>, <a href="#abf40dcb168e2a970e68dabbcbde25ee6">DefinitionMixin&lt; Base &gt;::setLocalName</a>, <a href="#a7d64f115d59d2667225ea684dfd2aa9d">DefinitionMixin&lt; Base &gt;::setName</a>, <a href="#a5701961a47f8f5336495771c8d3d611d">DefinitionMixin&lt; Base &gt;::setOuterScope</a>, <a href="#a5b7806d54dc3504a626078ac0d22dc19">DefinitionMixin&lt; Base &gt;::setReference</a>, <a href="#af1dfd6ae62c6a43f590645a80fc039a7">DefinitionMixin&lt; Base &gt;::setRefItems</a>, <a href="#a5d92005bf382f44874dc7b34196a1ac4">DefinitionMixin&lt; Base &gt;::symbolName</a>, <a href="#a8344f08e2dda50c48becfde382067b46">DefinitionMixin&lt; Base &gt;::toDefinitionImpl\_</a>, <a href="#afcd2841ebfa088d88d8624e5f54f1aa9">DefinitionMixin&lt; Base &gt;::writeDocAnchorsToTagFile</a>, <a href="#ab4f70a9c2798cb1b656a002e28af6a87">DefinitionMixin&lt; Base &gt;::writeInlineCode</a>, <a href="#a1920f150021e040075a423418fb0e85a">DefinitionMixin&lt; Base &gt;::writeNavigationPath</a>, <a href="#a48df7719d4f28f55162adc4b1064699b">DefinitionMixin&lt; Base &gt;::writePageNavigation</a>, <a href="#ad191384d79c44e12ae31ee900209c3c6">DefinitionMixin&lt; Base &gt;::writeQuickMemberLinks</a>, <a href="#a0922bcff85f540f991fd4e5fd3a68a02">DefinitionMixin&lt; Base &gt;::writeSourceDef</a>, <a href="#a91fa887054f1f3aafb9bb330491b8f84">DefinitionMixin&lt; Base &gt;::writeSourceReffedBy</a>, <a href="#a24663e9c959433e58e8e102ad4306814">DefinitionMixin&lt; Base &gt;::writeSourceRefs</a>, <a href="#ad951f2f7aef7a2408a8bafc08b7b5899">DefinitionMixin&lt; Base &gt;::writeSummaryLinks</a>, <a href="#ad12243a0430f318cbe3b499ca21c9e4b">DefinitionMixin&lt; Base &gt;::writeToc</a> and <a href="#a7080c8c1be27b05ba64f160655530571">DefinitionMixin&lt; Base &gt;::xrefListItems</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
