---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `TagCompoundVariant` Class Reference

<p>Variant class that holds a unique pointer to one of the specific container types. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous_namespace{tagreader.cpp}::TagCompoundVariant { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a180b3bf02446b2249b46c69eb8dd62ff">VariantT</a> = std::variant&lt; std::monostate, <a href="/web-doxygen/docs/api/namespaces/anonymous-tagreader-cpp-/#a5055d50d738c7bf6ebe9b5bade46e34d">TagClassInfoPtr</a>, <a href="/web-doxygen/docs/api/namespaces/anonymous-tagreader-cpp-/#ab3b5a8da78dc8ec0119e6d7b56e2545a">TagConceptInfoPtr</a>, <a href="/web-doxygen/docs/api/namespaces/anonymous-tagreader-cpp-/#a50af41c6081ab1dcdb696e3c1768beb4">TagNamespaceInfoPtr</a>, <a href="/web-doxygen/docs/api/namespaces/anonymous-tagreader-cpp-/#a324558b93fb5700fffa8713199f35dfc">TagPackageInfoPtr</a>, <a href="/web-doxygen/docs/api/namespaces/anonymous-tagreader-cpp-/#a4e7fd7caf31f4ca05305cc0ee61472fa">TagFileInfoPtr</a>, <a href="/web-doxygen/docs/api/namespaces/anonymous-tagreader-cpp-/#aef3e7c391dd4085358bacfb0b692eca7">TagGroupInfoPtr</a>, <a href="/web-doxygen/docs/api/namespaces/anonymous-tagreader-cpp-/#ab997be9b5e3a3eda38e76c61f23dfb76">TagPageInfoPtr</a>, <a href="/web-doxygen/docs/api/namespaces/anonymous-tagreader-cpp-/#a9da5cc42113e1508854c0eb011ed699c">TagDirInfoPtr</a>, <a href="/web-doxygen/docs/api/namespaces/anonymous-tagreader-cpp-/#ab7dcf33c7ebe9a10a42b37f39627fe45">TagModuleInfoPtr</a> &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Type : uint8_t { <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a539d6efdb511dab3ec85713d00b1aafe">TagCompoundVariant</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8eb9cd31bdc8e283acaa0c1d815df137">TagCompoundVariant</a> (VariantT &amp;&amp;v)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24b64c432de406c5edb3d954bc9ccd05">TagCompoundVariant</a> (const TagCompoundVariant &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adff6c25f9c60bb0097ddcdd38492171f">TagCompoundVariant</a> (TagCompoundVariant &amp;&amp;)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56f02d4c6510f4d3a652fdaf4c55392d">~TagCompoundVariant</a> ()=default</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant">TagCompoundVariant</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e88276610fa75a9879b6a8b0721f17f">operator=</a> (const TagCompoundVariant &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant">TagCompoundVariant</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec0d33eb116c7bb6aee702f80e068305">operator=</a> (TagCompoundVariant &amp;&amp;)=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class R&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">R *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generic non-const getter. <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class R&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const R *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a075bedde017c1e7f64a865823d650e9a">get</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generic const getter. <a href="#a075bedde017c1e7f64a865823d650e9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo">TagCompoundInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada07509516bd81f1be4bec2da3d968ee">getCompoundInfo</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience method to get the shared compound info. <a href="#ada07509516bd81f1be4bec2da3d968ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1a5f5ee04cdc70747f2c031f548d4ed7">Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ebebef7531a74c845017678e95a648f">type</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a180b3bf02446b2249b46c69eb8dd62ff">VariantT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a624ef630086cfd11dad472d26148b0c7">m_variant</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class R, typename... Args&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant">TagCompoundVariant</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3af267dcba2e60ce52e4c260cefd2659">make</a> (Args &amp;&amp;... args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generic factory method to create a variant holding a unique pointer to a given compound type. <a href="#a3af267dcba2e60ce52e4c260cefd2659">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## convenience const and non-const getters for each variant component Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo">TagClassInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecdddc886c305831f0e4bf9b36cb2144">getClassInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo">TagClassInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76af6272f2edf465e56c6dfc731f9192">getClassInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagconceptinfo">TagConceptInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fb7e7fefecde97cea369c55f58e367e">getConceptInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagconceptinfo">TagConceptInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1df259306a8b49db56edfae975212438">getConceptInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagnamespaceinfo">TagNamespaceInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38cd32d0f444be4c1c966bff3810741e">getNamespaceInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagnamespaceinfo">TagNamespaceInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcdb3194641b47c4fa4c6fb03056d907">getNamespaceInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpackageinfo">TagPackageInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9db08cc2c472e51fcba120aa465a3e3b">getPackageInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpackageinfo">TagPackageInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fff18a657808d4b9a2e2e9dac582e02">getPackageInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo">TagFileInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab91e958d6133e04a11ce51184b97a7d5">getFileInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo">TagFileInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4ac3ae910e5db8c0b0120f43f51fa7d">getFileInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo">TagGroupInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0370312a169de5cd396e6a75693b93fd">getGroupInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo">TagGroupInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52b5bd323b2e0f0438d9bff2a99e451a">getGroupInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpageinfo">TagPageInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01ad2fda8badd6741ecbfc924465dd83">getPageInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpageinfo">TagPageInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a946094c2f97fca0434faf9a5b7ba0018">getPageInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagdirinfo">TagDirInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b55a2a4fcbe5a242bf54617b55dbd12">getDirInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagdirinfo">TagDirInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0263464701c1c349edf780cfeb4b8328">getDirInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagmoduleinfo">TagModuleInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37e76b5208428c5718b25c6d0d8954f8">getModuleInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagmoduleinfo">TagModuleInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d0ddf6c0d348a5f8469131a71bd632e">getModuleInfo</a> () const</td>
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

<p>Variant class that holds a unique pointer to one of the specific container types.</p>

<p>Definition at line 213 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### VariantT {#a180b3bf02446b2249b46c69eb8dd62ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous_namespace{tagreader.cpp}::TagCompoundVariant::VariantT =  std::variant&lt; std::monostate,      
                                   TagClassInfoPtr,     
                                   TagConceptInfoPtr,   
                                   TagNamespaceInfoPtr, 
                                   TagPackageInfoPtr,   
                                   TagFileInfoPtr,      
                                   TagGroupInfoPtr,     
                                   TagPageInfoPtr,      
                                   TagDirInfoPtr,       
                                   TagModuleInfoPtr&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a180b3bf02446b2249b46c69eb8dd62ff">216</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a180b3bf02446b2249b46c69eb8dd62ff">VariantT</a> = std::variant&lt; std::monostate,      </span><span class="doxyHighlightComment">// 0</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### Type {#a1a5f5ee04cdc70747f2c031f548d4ed7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class anonymous_namespace{tagreader.cpp}::TagCompoundVariant::Type : uint8_t</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">Uninitialized<a id="a1a5f5ee04cdc70747f2c031f548d4ed7af704f57ea420275ad51bf55b7dec2c96"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Class<a id="a1a5f5ee04cdc70747f2c031f548d4ed7a9bd81329febf6efe22788e03ddeaf0af"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Concept<a id="a1a5f5ee04cdc70747f2c031f548d4ed7ad99a604c79ce3c2e76a2f43488d5d4c3"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Namespace<a id="a1a5f5ee04cdc70747f2c031f548d4ed7ab3ba0fe968ce39dcfc6fe8cc0f1b02da"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Package<a id="a1a5f5ee04cdc70747f2c031f548d4ed7a209802fb858e2c83205027dbbb5d9e6c"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">File<a id="a1a5f5ee04cdc70747f2c031f548d4ed7a0b27918290ff5323bea1e3b78a9cf04e"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Group<a id="a1a5f5ee04cdc70747f2c031f548d4ed7a03937134cedab9078be39a77ee3a48a0"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Page<a id="a1a5f5ee04cdc70747f2c031f548d4ed7a193cfc9be3b995831c6af2fea6650e60"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Dir<a id="a1a5f5ee04cdc70747f2c031f548d4ed7a3c4e6dbf3e1df93a734d9959bac9ee94"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Module<a id="a1a5f5ee04cdc70747f2c031f548d4ed7ae55f75a29310d7b60f7ac1d390c8ae42"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 227 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1a5f5ee04cdc70747f2c031f548d4ed7af704f57ea420275ad51bf55b7dec2c96">229</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7af704f57ea420275ad51bf55b7dec2c96">Uninitialized</a> = 0,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1a5f5ee04cdc70747f2c031f548d4ed7a9bd81329febf6efe22788e03ddeaf0af">230</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7a9bd81329febf6efe22788e03ddeaf0af">Class</a>         = 1,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1a5f5ee04cdc70747f2c031f548d4ed7ad99a604c79ce3c2e76a2f43488d5d4c3">231</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7ad99a604c79ce3c2e76a2f43488d5d4c3">Concept</a>       = 2,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1a5f5ee04cdc70747f2c031f548d4ed7ab3ba0fe968ce39dcfc6fe8cc0f1b02da">232</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7ab3ba0fe968ce39dcfc6fe8cc0f1b02da">Namespace</a>     = 3,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1a5f5ee04cdc70747f2c031f548d4ed7a209802fb858e2c83205027dbbb5d9e6c">233</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7a209802fb858e2c83205027dbbb5d9e6c">Package</a>       = 4,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1a5f5ee04cdc70747f2c031f548d4ed7a0b27918290ff5323bea1e3b78a9cf04e">234</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7a0b27918290ff5323bea1e3b78a9cf04e">File</a>          = 5,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1a5f5ee04cdc70747f2c031f548d4ed7a03937134cedab9078be39a77ee3a48a0">235</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7a03937134cedab9078be39a77ee3a48a0">Group</a>         = 6,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1a5f5ee04cdc70747f2c031f548d4ed7a193cfc9be3b995831c6af2fea6650e60">236</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7a193cfc9be3b995831c6af2fea6650e60">Page</a>          = 7,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1a5f5ee04cdc70747f2c031f548d4ed7a3c4e6dbf3e1df93a734d9959bac9ee94">237</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7a3c4e6dbf3e1df93a734d9959bac9ee94">Dir</a>           = 8,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1a5f5ee04cdc70747f2c031f548d4ed7ae55f75a29310d7b60f7ac1d390c8ae42">238</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7ae55f75a29310d7b60f7ac1d390c8ae42">Module</a>        = 9</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">    };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### TagCompoundVariant() {#a539d6efdb511dab3ec85713d00b1aafe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous_namespace{tagreader.cpp}::TagCompoundVariant::TagCompoundVariant ()</td>
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



<p>Definition at line 241 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a539d6efdb511dab3ec85713d00b1aafe">241</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a539d6efdb511dab3ec85713d00b1aafe">TagCompoundVariant</a>() {}</span></span></div>

</div>


<p>Referenced by <a href="#a3af267dcba2e60ce52e4c260cefd2659">make</a>, <a href="#a4e88276610fa75a9879b6a8b0721f17f">operator=</a>, <a href="#aec0d33eb116c7bb6aee702f80e068305">operator=</a>, <a href="#a24b64c432de406c5edb3d954bc9ccd05">TagCompoundVariant</a> and <a href="#adff6c25f9c60bb0097ddcdd38492171f">TagCompoundVariant</a>.</p>

</div>
</div>

### TagCompoundVariant() {#a8eb9cd31bdc8e283acaa0c1d815df137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous_namespace{tagreader.cpp}::TagCompoundVariant::TagCompoundVariant (<a href="#a180b3bf02446b2249b46c69eb8dd62ff">VariantT</a> &amp;&amp; v)</td>
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



<p>Definition at line 242 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8eb9cd31bdc8e283acaa0c1d815df137">242</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">explicit</span><span class="doxyHighlight"> <a href="#a8eb9cd31bdc8e283acaa0c1d815df137">TagCompoundVariant</a>(<a href="#a180b3bf02446b2249b46c69eb8dd62ff">VariantT</a> &amp;&amp;v) : <a href="#a624ef630086cfd11dad472d26148b0c7">m_variant</a>(std::move(v)) {}</span></span></div>

</div>


<p>Reference <a href="#a624ef630086cfd11dad472d26148b0c7">m_variant</a>.</p>

</div>
</div>

### TagCompoundVariant() {#a24b64c432de406c5edb3d954bc9ccd05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous_namespace{tagreader.cpp}::TagCompoundVariant::TagCompoundVariant (const <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant">TagCompoundVariant</a> &amp;)</td>
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



<p>Definition at line 243 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<p>Reference <a href="#a539d6efdb511dab3ec85713d00b1aafe">TagCompoundVariant</a>.</p>

</div>
</div>

### TagCompoundVariant() {#adff6c25f9c60bb0097ddcdd38492171f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous_namespace{tagreader.cpp}::TagCompoundVariant::TagCompoundVariant (<a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant">TagCompoundVariant</a> &amp;&amp;)</td>
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



<p>Definition at line 245 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<p>Reference <a href="#a539d6efdb511dab3ec85713d00b1aafe">TagCompoundVariant</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~TagCompoundVariant() {#a56f02d4c6510f4d3a652fdaf4c55392d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous_namespace{tagreader.cpp}::TagCompoundVariant::~TagCompoundVariant ()</td>
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



<p>Definition at line 247 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a4e88276610fa75a9879b6a8b0721f17f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TagCompoundVariant &amp; anonymous_namespace{tagreader.cpp}::TagCompoundVariant::operator= (const <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant">TagCompoundVariant</a> &amp;)</td>
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



<p>Definition at line 244 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<p>Reference <a href="#a539d6efdb511dab3ec85713d00b1aafe">TagCompoundVariant</a>.</p>

</div>
</div>

### operator=() {#aec0d33eb116c7bb6aee702f80e068305}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TagCompoundVariant &amp; anonymous_namespace{tagreader.cpp}::TagCompoundVariant::operator= (<a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant">TagCompoundVariant</a> &amp;&amp;)</td>
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



<p>Definition at line 246 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<p>Reference <a href="#a539d6efdb511dab3ec85713d00b1aafe">TagCompoundVariant</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### get() {#acbc0d02d8c19b6c832b770b5e6100ff3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class R&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">R * anonymous_namespace{tagreader.cpp}::TagCompoundVariant::get ()</td>
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

<p>Generic non-const getter.</p>

<p>Definition at line 251 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acbc0d02d8c19b6c832b770b5e6100ff3">251</a></span><span class="doxyLineContent"><span class="doxyHighlight">    R *<a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">      std::unique_ptr&lt;R&gt; *p = std::get_if&lt;std::unique_ptr&lt;R&gt;&gt;(&amp;<a href="#a624ef630086cfd11dad472d26148b0c7">m_variant</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> p ? p-&gt;get() : </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a624ef630086cfd11dad472d26148b0c7">m_variant</a>.</p>


<p>Referenced by <a href="#aecdddc886c305831f0e4bf9b36cb2144">getClassInfo</a>, <a href="#a76af6272f2edf465e56c6dfc731f9192">getClassInfo</a>, <a href="#a5fb7e7fefecde97cea369c55f58e367e">getConceptInfo</a>, <a href="#a1df259306a8b49db56edfae975212438">getConceptInfo</a>, <a href="#a6b55a2a4fcbe5a242bf54617b55dbd12">getDirInfo</a>, <a href="#a0263464701c1c349edf780cfeb4b8328">getDirInfo</a>, <a href="#ab91e958d6133e04a11ce51184b97a7d5">getFileInfo</a>, <a href="#ab4ac3ae910e5db8c0b0120f43f51fa7d">getFileInfo</a>, <a href="#a0370312a169de5cd396e6a75693b93fd">getGroupInfo</a>, <a href="#a52b5bd323b2e0f0438d9bff2a99e451a">getGroupInfo</a>, <a href="#a37e76b5208428c5718b25c6d0d8954f8">getModuleInfo</a>, <a href="#a6d0ddf6c0d348a5f8469131a71bd632e">getModuleInfo</a>, <a href="#a38cd32d0f444be4c1c966bff3810741e">getNamespaceInfo</a>, <a href="#abcdb3194641b47c4fa4c6fb03056d907">getNamespaceInfo</a>, <a href="#a9db08cc2c472e51fcba120aa465a3e3b">getPackageInfo</a>, <a href="#a3fff18a657808d4b9a2e2e9dac582e02">getPackageInfo</a>, <a href="#a01ad2fda8badd6741ecbfc924465dd83">getPageInfo</a> and <a href="#a946094c2f97fca0434faf9a5b7ba0018">getPageInfo</a>.</p>

</div>
</div>

### get() {#a075bedde017c1e7f64a865823d650e9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class R&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const R * anonymous_namespace{tagreader.cpp}::TagCompoundVariant::get ()</td>
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

<p>Generic const getter.</p>

<p>Definition at line 258 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a075bedde017c1e7f64a865823d650e9a">258</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> R *<a href="#a075bedde017c1e7f64a865823d650e9a">get</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::unique_ptr&lt;R&gt; *p = std::get_if&lt;std::unique_ptr&lt;R&gt;&gt;(&amp;<a href="#a624ef630086cfd11dad472d26148b0c7">m_variant</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> p ? p-&gt;get() : </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a624ef630086cfd11dad472d26148b0c7">m_variant</a>.</p>

</div>
</div>

### getCompoundInfo() {#ada07509516bd81f1be4bec2da3d968ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TagCompoundInfo * anonymous_namespace{tagreader.cpp}::TagCompoundVariant::getCompoundInfo ()</td>
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

<p>Convenience method to get the shared compound info.</p>

<p>Definition at line 295 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ada07509516bd81f1be4bec2da3d968ee">295</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo">TagCompoundInfo</a> *<a href="#ada07509516bd81f1be4bec2da3d968ee">getCompoundInfo</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(<a href="#a3ebebef7531a74c845017678e95a648f">type</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7af704f57ea420275ad51bf55b7dec2c96">Type::Uninitialized</a>: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7a9bd81329febf6efe22788e03ddeaf0af">Type::Class</a>:         </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aecdddc886c305831f0e4bf9b36cb2144">getClassInfo</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7ad99a604c79ce3c2e76a2f43488d5d4c3">Type::Concept</a>:       </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a5fb7e7fefecde97cea369c55f58e367e">getConceptInfo</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7ab3ba0fe968ce39dcfc6fe8cc0f1b02da">Type::Namespace</a>:     </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a38cd32d0f444be4c1c966bff3810741e">getNamespaceInfo</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7a209802fb858e2c83205027dbbb5d9e6c">Type::Package</a>:       </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a9db08cc2c472e51fcba120aa465a3e3b">getPackageInfo</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7a0b27918290ff5323bea1e3b78a9cf04e">Type::File</a>:          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab91e958d6133e04a11ce51184b97a7d5">getFileInfo</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7a03937134cedab9078be39a77ee3a48a0">Type::Group</a>:         </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a0370312a169de5cd396e6a75693b93fd">getGroupInfo</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7a193cfc9be3b995831c6af2fea6650e60">Type::Page</a>:          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a01ad2fda8badd6741ecbfc924465dd83">getPageInfo</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7a3c4e6dbf3e1df93a734d9959bac9ee94">Type::Dir</a>:           </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a6b55a2a4fcbe5a242bf54617b55dbd12">getDirInfo</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7ae55f75a29310d7b60f7ac1d390c8ae42">Type::Module</a>:        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a37e76b5208428c5718b25c6d0d8954f8">getModuleInfo</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7a9bd81329febf6efe22788e03ddeaf0af">Class</a>, <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7ad99a604c79ce3c2e76a2f43488d5d4c3">Concept</a>, <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7a3c4e6dbf3e1df93a734d9959bac9ee94">Dir</a>, <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7a0b27918290ff5323bea1e3b78a9cf04e">File</a>, <a href="#aecdddc886c305831f0e4bf9b36cb2144">getClassInfo</a>, <a href="#a5fb7e7fefecde97cea369c55f58e367e">getConceptInfo</a>, <a href="#a6b55a2a4fcbe5a242bf54617b55dbd12">getDirInfo</a>, <a href="#ab91e958d6133e04a11ce51184b97a7d5">getFileInfo</a>, <a href="#a0370312a169de5cd396e6a75693b93fd">getGroupInfo</a>, <a href="#a37e76b5208428c5718b25c6d0d8954f8">getModuleInfo</a>, <a href="#a38cd32d0f444be4c1c966bff3810741e">getNamespaceInfo</a>, <a href="#a9db08cc2c472e51fcba120aa465a3e3b">getPackageInfo</a>, <a href="#a01ad2fda8badd6741ecbfc924465dd83">getPageInfo</a>, <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7a03937134cedab9078be39a77ee3a48a0">Group</a>, <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7ae55f75a29310d7b60f7ac1d390c8ae42">Module</a>, <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7ab3ba0fe968ce39dcfc6fe8cc0f1b02da">Namespace</a>, <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7a209802fb858e2c83205027dbbb5d9e6c">Package</a>, <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7a193cfc9be3b995831c6af2fea6650e60">Page</a>, <a href="#a3ebebef7531a74c845017678e95a648f">type</a> and <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7af704f57ea420275ad51bf55b7dec2c96">Uninitialized</a>.</p>

</div>
</div>

### type() {#a3ebebef7531a74c845017678e95a648f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type anonymous_namespace{tagreader.cpp}::TagCompoundVariant::type ()</td>
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



<p>Definition at line 312 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3ebebef7531a74c845017678e95a648f">312</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1a5f5ee04cdc70747f2c031f548d4ed7">Type</a> <a href="#a3ebebef7531a74c845017678e95a648f">type</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="#a1a5f5ee04cdc70747f2c031f548d4ed7">Type</a></span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a624ef630086cfd11dad472d26148b0c7">m_variant</a>.index());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a624ef630086cfd11dad472d26148b0c7">m_variant</a>.</p>


<p>Referenced by <a href="#ada07509516bd81f1be4bec2da3d968ee">getCompoundInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_variant {#a624ef630086cfd11dad472d26148b0c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VariantT anonymous_namespace{tagreader.cpp}::TagCompoundVariant::m_variant</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 318 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a624ef630086cfd11dad472d26148b0c7">318</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a180b3bf02446b2249b46c69eb8dd62ff">VariantT</a> <a href="#a624ef630086cfd11dad472d26148b0c7">m_variant</a>;</span></span></div>

</div>


<p>Referenced by <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get</a>, <a href="#a075bedde017c1e7f64a865823d650e9a">get</a>, <a href="#a8eb9cd31bdc8e283acaa0c1d815df137">TagCompoundVariant</a> and <a href="#a3ebebef7531a74c845017678e95a648f">type</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### make() {#a3af267dcba2e60ce52e4c260cefd2659}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class R, typename... Args&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TagCompoundVariant anonymous_namespace{tagreader.cpp}::TagCompoundVariant::make (Args &amp;&amp;... args)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generic factory method to create a variant holding a unique pointer to a given compound type.</p>

<p>Definition at line 266 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3af267dcba2e60ce52e4c260cefd2659">266</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="#a539d6efdb511dab3ec85713d00b1aafe">TagCompoundVariant</a> <a href="#a3af267dcba2e60ce52e4c260cefd2659">make</a>(Args&amp;&amp;... args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a539d6efdb511dab3ec85713d00b1aafe">TagCompoundVariant</a>(<a href="#a180b3bf02446b2249b46c69eb8dd62ff">VariantT</a>(std::make_unique&lt;R&gt;(std::forward&lt;Args&gt;(args)...)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a539d6efdb511dab3ec85713d00b1aafe">TagCompoundVariant</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## convenience const and non-const getters for each variant component

### getClassInfo {#aecdddc886c305831f0e4bf9b36cb2144}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TagClassInfo * anonymous_namespace{tagreader.cpp}::TagCompoundVariant::getClassInfo ()</td>
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



<p>Definition at line 274 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aecdddc886c305831f0e4bf9b36cb2144">274</a></span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo">TagClassInfo</a>     *<a href="#aecdddc886c305831f0e4bf9b36cb2144">getClassInfo</a>()           { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get&lt;TagClassInfo    &gt;</a>(); }</span></span></div>

</div>


<p>Reference <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get</a>.</p>


<p>Referenced by <a href="#ada07509516bd81f1be4bec2da3d968ee">getCompoundInfo</a>.</p>

</div>
</div>

### getClassInfo {#a76af6272f2edf465e56c6dfc731f9192}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TagClassInfo * anonymous_namespace{tagreader.cpp}::TagCompoundVariant::getClassInfo ()</td>
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



<p>Definition at line 275 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a76af6272f2edf465e56c6dfc731f9192">275</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo">TagClassInfo</a>     *<a href="#a76af6272f2edf465e56c6dfc731f9192">getClassInfo</a>()</span><span class="doxyHighlightKeyword">     const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get&lt;TagClassInfo    &gt;</a>(); }</span></span></div>

</div>


<p>Reference <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get</a>.</p>

</div>
</div>

### getConceptInfo {#a5fb7e7fefecde97cea369c55f58e367e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TagConceptInfo * anonymous_namespace{tagreader.cpp}::TagCompoundVariant::getConceptInfo ()</td>
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



<p>Definition at line 276 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fb7e7fefecde97cea369c55f58e367e">276</a></span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagconceptinfo">TagConceptInfo</a>   *<a href="#a5fb7e7fefecde97cea369c55f58e367e">getConceptInfo</a>()         { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get&lt;TagConceptInfo  &gt;</a>(); }</span></span></div>

</div>


<p>Reference <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get</a>.</p>


<p>Referenced by <a href="#ada07509516bd81f1be4bec2da3d968ee">getCompoundInfo</a>.</p>

</div>
</div>

### getConceptInfo {#a1df259306a8b49db56edfae975212438}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TagConceptInfo * anonymous_namespace{tagreader.cpp}::TagCompoundVariant::getConceptInfo ()</td>
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



<p>Definition at line 277 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1df259306a8b49db56edfae975212438">277</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagconceptinfo">TagConceptInfo</a>   *<a href="#a1df259306a8b49db56edfae975212438">getConceptInfo</a>()</span><span class="doxyHighlightKeyword">   const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get&lt;TagConceptInfo  &gt;</a>(); }</span></span></div>

</div>


<p>Reference <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get</a>.</p>

</div>
</div>

### getDirInfo {#a6b55a2a4fcbe5a242bf54617b55dbd12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TagDirInfo * anonymous_namespace{tagreader.cpp}::TagCompoundVariant::getDirInfo ()</td>
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



<p>Definition at line 288 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6b55a2a4fcbe5a242bf54617b55dbd12">288</a></span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagdirinfo">TagDirInfo</a>       *<a href="#a6b55a2a4fcbe5a242bf54617b55dbd12">getDirInfo</a>()             { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get&lt;TagDirInfo      &gt;</a>(); }</span></span></div>

</div>


<p>Reference <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get</a>.</p>


<p>Referenced by <a href="#ada07509516bd81f1be4bec2da3d968ee">getCompoundInfo</a>.</p>

</div>
</div>

### getDirInfo {#a0263464701c1c349edf780cfeb4b8328}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TagDirInfo * anonymous_namespace{tagreader.cpp}::TagCompoundVariant::getDirInfo ()</td>
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



<p>Definition at line 289 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0263464701c1c349edf780cfeb4b8328">289</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagdirinfo">TagDirInfo</a>       *<a href="#a0263464701c1c349edf780cfeb4b8328">getDirInfo</a>()</span><span class="doxyHighlightKeyword">       const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get&lt;TagDirInfo      &gt;</a>(); }</span></span></div>

</div>


<p>Reference <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get</a>.</p>

</div>
</div>

### getFileInfo {#ab91e958d6133e04a11ce51184b97a7d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TagFileInfo * anonymous_namespace{tagreader.cpp}::TagCompoundVariant::getFileInfo ()</td>
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



<p>Definition at line 282 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab91e958d6133e04a11ce51184b97a7d5">282</a></span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo">TagFileInfo</a>      *<a href="#ab91e958d6133e04a11ce51184b97a7d5">getFileInfo</a>()            { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get&lt;TagFileInfo     &gt;</a>(); }</span></span></div>

</div>


<p>Reference <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get</a>.</p>


<p>Referenced by <a href="#ada07509516bd81f1be4bec2da3d968ee">getCompoundInfo</a>.</p>

</div>
</div>

### getFileInfo {#ab4ac3ae910e5db8c0b0120f43f51fa7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TagFileInfo * anonymous_namespace{tagreader.cpp}::TagCompoundVariant::getFileInfo ()</td>
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



<p>Definition at line 283 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab4ac3ae910e5db8c0b0120f43f51fa7d">283</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo">TagFileInfo</a>      *<a href="#ab4ac3ae910e5db8c0b0120f43f51fa7d">getFileInfo</a>()</span><span class="doxyHighlightKeyword">      const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get&lt;TagFileInfo     &gt;</a>(); }</span></span></div>

</div>


<p>Reference <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get</a>.</p>

</div>
</div>

### getGroupInfo {#a0370312a169de5cd396e6a75693b93fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TagGroupInfo * anonymous_namespace{tagreader.cpp}::TagCompoundVariant::getGroupInfo ()</td>
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



<p>Definition at line 284 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0370312a169de5cd396e6a75693b93fd">284</a></span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo">TagGroupInfo</a>     *<a href="#a0370312a169de5cd396e6a75693b93fd">getGroupInfo</a>()           { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get&lt;TagGroupInfo    &gt;</a>(); }</span></span></div>

</div>


<p>Reference <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get</a>.</p>


<p>Referenced by <a href="#ada07509516bd81f1be4bec2da3d968ee">getCompoundInfo</a>.</p>

</div>
</div>

### getGroupInfo {#a52b5bd323b2e0f0438d9bff2a99e451a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TagGroupInfo * anonymous_namespace{tagreader.cpp}::TagCompoundVariant::getGroupInfo ()</td>
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



<p>Definition at line 285 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a52b5bd323b2e0f0438d9bff2a99e451a">285</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo">TagGroupInfo</a>     *<a href="#a52b5bd323b2e0f0438d9bff2a99e451a">getGroupInfo</a>()</span><span class="doxyHighlightKeyword">     const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get&lt;TagGroupInfo    &gt;</a>(); }</span></span></div>

</div>


<p>Reference <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get</a>.</p>

</div>
</div>

### getModuleInfo {#a37e76b5208428c5718b25c6d0d8954f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TagModuleInfo * anonymous_namespace{tagreader.cpp}::TagCompoundVariant::getModuleInfo ()</td>
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



<p>Definition at line 290 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a37e76b5208428c5718b25c6d0d8954f8">290</a></span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagmoduleinfo">TagModuleInfo</a>    *<a href="#a37e76b5208428c5718b25c6d0d8954f8">getModuleInfo</a>()          { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get&lt;TagModuleInfo   &gt;</a>(); }</span></span></div>

</div>


<p>Reference <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get</a>.</p>


<p>Referenced by <a href="#ada07509516bd81f1be4bec2da3d968ee">getCompoundInfo</a>.</p>

</div>
</div>

### getModuleInfo {#a6d0ddf6c0d348a5f8469131a71bd632e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TagModuleInfo * anonymous_namespace{tagreader.cpp}::TagCompoundVariant::getModuleInfo ()</td>
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



<p>Definition at line 291 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6d0ddf6c0d348a5f8469131a71bd632e">291</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagmoduleinfo">TagModuleInfo</a>    *<a href="#a6d0ddf6c0d348a5f8469131a71bd632e">getModuleInfo</a>()</span><span class="doxyHighlightKeyword">    const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get&lt;TagModuleInfo   &gt;</a>(); }</span></span></div>

</div>


<p>Reference <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get</a>.</p>

</div>
</div>

### getNamespaceInfo {#a38cd32d0f444be4c1c966bff3810741e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TagNamespaceInfo * anonymous_namespace{tagreader.cpp}::TagCompoundVariant::getNamespaceInfo ()</td>
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



<p>Definition at line 278 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a38cd32d0f444be4c1c966bff3810741e">278</a></span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagnamespaceinfo">TagNamespaceInfo</a> *<a href="#a38cd32d0f444be4c1c966bff3810741e">getNamespaceInfo</a>()       { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get&lt;TagNamespaceInfo&gt;</a>(); }</span></span></div>

</div>


<p>Reference <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get</a>.</p>


<p>Referenced by <a href="#ada07509516bd81f1be4bec2da3d968ee">getCompoundInfo</a>.</p>

</div>
</div>

### getNamespaceInfo {#abcdb3194641b47c4fa4c6fb03056d907}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TagNamespaceInfo * anonymous_namespace{tagreader.cpp}::TagCompoundVariant::getNamespaceInfo ()</td>
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



<p>Definition at line 279 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abcdb3194641b47c4fa4c6fb03056d907">279</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagnamespaceinfo">TagNamespaceInfo</a> *<a href="#abcdb3194641b47c4fa4c6fb03056d907">getNamespaceInfo</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get&lt;TagNamespaceInfo&gt;</a>(); }</span></span></div>

</div>


<p>Reference <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get</a>.</p>

</div>
</div>

### getPackageInfo {#a9db08cc2c472e51fcba120aa465a3e3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TagPackageInfo * anonymous_namespace{tagreader.cpp}::TagCompoundVariant::getPackageInfo ()</td>
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



<p>Definition at line 280 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9db08cc2c472e51fcba120aa465a3e3b">280</a></span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpackageinfo">TagPackageInfo</a>   *<a href="#a9db08cc2c472e51fcba120aa465a3e3b">getPackageInfo</a>()         { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get&lt;TagPackageInfo  &gt;</a>(); }</span></span></div>

</div>


<p>Reference <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get</a>.</p>


<p>Referenced by <a href="#ada07509516bd81f1be4bec2da3d968ee">getCompoundInfo</a>.</p>

</div>
</div>

### getPackageInfo {#a3fff18a657808d4b9a2e2e9dac582e02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TagPackageInfo * anonymous_namespace{tagreader.cpp}::TagCompoundVariant::getPackageInfo ()</td>
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



<p>Definition at line 281 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3fff18a657808d4b9a2e2e9dac582e02">281</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpackageinfo">TagPackageInfo</a>   *<a href="#a3fff18a657808d4b9a2e2e9dac582e02">getPackageInfo</a>()</span><span class="doxyHighlightKeyword">   const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get&lt;TagPackageInfo  &gt;</a>(); }</span></span></div>

</div>


<p>Reference <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get</a>.</p>

</div>
</div>

### getPageInfo {#a01ad2fda8badd6741ecbfc924465dd83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TagPageInfo * anonymous_namespace{tagreader.cpp}::TagCompoundVariant::getPageInfo ()</td>
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



<p>Definition at line 286 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a01ad2fda8badd6741ecbfc924465dd83">286</a></span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpageinfo">TagPageInfo</a>      *<a href="#a01ad2fda8badd6741ecbfc924465dd83">getPageInfo</a>()            { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get&lt;TagPageInfo     &gt;</a>(); }</span></span></div>

</div>


<p>Reference <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get</a>.</p>


<p>Referenced by <a href="#ada07509516bd81f1be4bec2da3d968ee">getCompoundInfo</a>.</p>

</div>
</div>

### getPageInfo {#a946094c2f97fca0434faf9a5b7ba0018}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TagPageInfo * anonymous_namespace{tagreader.cpp}::TagCompoundVariant::getPageInfo ()</td>
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



<p>Definition at line 287 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a946094c2f97fca0434faf9a5b7ba0018">287</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpageinfo">TagPageInfo</a>      *<a href="#a946094c2f97fca0434faf9a5b7ba0018">getPageInfo</a>()</span><span class="doxyHighlightKeyword">      const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get&lt;TagPageInfo     &gt;</a>(); }</span></span></div>

</div>


<p>Reference <a href="#acbc0d02d8c19b6c832b770b5e6100ff3">get</a>.</p>

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
