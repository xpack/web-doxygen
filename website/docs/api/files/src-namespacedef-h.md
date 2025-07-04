---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/namespacedef-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `namespacedef.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;memory&gt;
#include &lt;unordered_set&gt;
#include "<a href="/web-doxygen/docs/api/files/src/definition-h">definition.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/namespacelinkedmap">NamespaceLinkedMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/namespacelinkedrefmap">NamespaceLinkedRefMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An abstract interface of a namespace symbol. <a href="/web-doxygen/docs/api/classes/namespacedef/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/namespacedefmutable">NamespaceDefMutable</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa97ca3d448ea31d3e13f39c698f605ec">NamespaceDefSet</a> = std::unordered_set&lt; const <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> * &gt;</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fed9778007d6ffd1bb549337a4dfced">createNamespaceDef</a> (const QCString &amp;defFileName, int defLine, int defColumn, const QCString &amp;name, const QCString &amp;ref=QCString(), const QCString &amp;refFile=QCString(), const QCString &amp;type=QCString(), bool isPublished=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Factory method to create new <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> instance. <a href="#a8fed9778007d6ffd1bb549337a4dfced">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6212baba497e02a45f5c5fe48aa7d4af">createNamespaceDefAlias</a> (const Definition *newScope, const NamespaceDef *nd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Factory method to create an alias of an existing namespace. <a href="#a6212baba497e02a45f5c5fe48aa7d4af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae303e4de18684cb3d0c72d936cc0654f">toNamespaceDef</a> (Definition *d)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af52a8a4a35b2209c0c4609c23b5b82e4">toNamespaceDef</a> (DefinitionMutable *d)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4a3a7d929c1539b4580ef9895c48f0f">toNamespaceDef</a> (const Definition *d)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/namespacedefmutable">NamespaceDefMutable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae480c007a9e16b642a72ffb1119c5812">toNamespaceDefMutable</a> (Definition *d)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a299c303cf66b245b416c9167b2f9aaa9">replaceNamespaceAliases</a> (QCString &amp;name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3b0b7f32404c52577802d626b64a49e">getResolvedNamespace</a> (const QCString &amp;key)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/namespacedefmutable">NamespaceDefMutable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03b786b13e194f1f753b5ec0b0ed1a38">getResolvedNamespaceMutable</a> (const QCString &amp;key)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a061ac5e55a8b63f2c06e1f4e272cb011">namespaceHasNestedNamespace</a> (const NamespaceDef *nd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af84e6fea0b6f07072eab35b1569fd357">namespaceHasNestedConcept</a> (const NamespaceDef *nd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d15fcf5c959d5ce9db005cba5692094">namespaceHasNestedClass</a> (const NamespaceDef *nd, bool filterClasses, ClassDef::CompoundType ct)</td>
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


<div class="doxySectionDef">

## Typedefs

### NamespaceDefSet {#aa97ca3d448ea31d3e13f39c698f605ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using NamespaceDefSet =  std::unordered_set&lt;const NamespaceDef*&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa97ca3d448ea31d3e13f39c698f605ec">39</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#aa97ca3d448ea31d3e13f39c698f605ec">NamespaceDefSet</a> = std::unordered_set&lt;const NamespaceDef*&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### createNamespaceDef() {#a8fed9778007d6ffd1bb549337a4dfced}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; NamespaceDef &gt; createNamespaceDef (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; defFileName, int defLine, int defColumn, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; refFile=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; type=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), bool isPublished=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Factory method to create new <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> instance.</p>

<p>Declaration at line 130 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>, definition at line 174 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp">namespacedef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ac1d161993501b3f63c91fe154559dce8">174</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::unique_ptr&lt;NamespaceDef&gt; <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ac1d161993501b3f63c91fe154559dce8">createNamespaceDef</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;defFileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> defLine,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> defColumn,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">                 </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">                 </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;refFile,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;type,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">                 </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isPublished)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("createNamespaceDef(%s)\n",qPrint(name));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::make_unique&lt;NamespaceDefImpl&gt;(defFileName,defLine,defColumn,name,ref,refFile,type,isPublished);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a10458b8a16238a4eae5fb5019df747e8">adjustConfiguration</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a71f923667206aac9e24848997edd6d8b">buildNamespaceList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#acc3d9699d44f100227430700d7c62a68">buildScopeFromQualifiedName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a9e88b70863796306c5f0070d263ab4c8">findUsingDirectives</a> and <a href="/web-doxygen/docs/api/classes/namespacedefmutable/#ab41129b22b4eac9adde902522bcca6c2">NamespaceDefMutable::setInline</a>.</p>

</div>
</div>

### createNamespaceDefAlias() {#a6212baba497e02a45f5c5fe48aa7d4af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; NamespaceDef &gt; createNamespaceDefAlias (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * newScope, const <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> * nd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Factory method to create an alias of an existing namespace.</p>


<p>Used for inline namespaces.</p>


<p>Declaration at line 136 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>, definition at line 262 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp">namespacedef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#a6212baba497e02a45f5c5fe48aa7d4af">262</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::unique_ptr&lt;NamespaceDef&gt; <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#a6212baba497e02a45f5c5fe48aa7d4af">createNamespaceDefAlias</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *newScope,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *nd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> alnd = std::make_unique&lt;NamespaceDefAliasImpl&gt;(newScope,nd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("alnd name=%s localName=%s qualifiedName=%s displayName()=%s\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//    qPrint(alnd-&gt;name()),qPrint(alnd-&gt;localName()),qPrint(alnd-&gt;qualifiedName()),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//    qPrint(alnd-&gt;displayName()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> alnd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a71f923667206aac9e24848997edd6d8b">buildNamespaceList</a> and <a href="/web-doxygen/docs/api/classes/namespacedefmutable/#ab41129b22b4eac9adde902522bcca6c2">NamespaceDefMutable::setInline</a>.</p>

</div>
</div>

### getResolvedNamespace() {#ac3b0b7f32404c52577802d626b64a49e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NamespaceDef * getResolvedNamespace (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; key)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 149 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>, definition at line 1789 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp">namespacedef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ac29daa4ae4a11022a30d2deb6934624c">1789</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *<a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ac29daa4ae4a11022a30d2deb6934624c">getResolvedNamespace</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1790</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1791</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("&gt; getResolvedNamespace(%s)\n",qPrint(name));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1792</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (name.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1793</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/containers-h/#a0bc125fc346e538d66d5ea1c33428f00">StringSet</a> namespacesTried;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1794</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> ns = <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#a5651f6ae6e0fe13853fa30bfd52d07a4">getResolvedNamespaceRec</a>(namespacesTried,<a href="/web-doxygen/docs/api/structs/namespacealiasinfo">NamespaceAliasInfo</a>(name.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1795</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("&lt; getResolvedNamespace(%s)=%s\n",qPrint(name),ns?qPrint(ns-&gt;qualifiedName()):"nullptr");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1796</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> ns;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1797</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#a5651f6ae6e0fe13853fa30bfd52d07a4">getResolvedNamespaceRec</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a568741e989fcbe6cd20c1295cf9c7aed">buildTypedefList</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a99ce0f316902ba135f970cba1731ed97">extractNamespaceName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a30174567b25121087a939ea7745b20ab">findUsedNamespace</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a9e88b70863796306c5f0070d263ab4c8">findUsingDirectives</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a080345cfde4ece732f42ded5413ea957">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a3345ad9e2ab3a9d1b524391ae5f6c545">generateClassOrGlobalLink</a>, <a href="#a03b786b13e194f1f753b5ec0b0ed1a38">getResolvedNamespaceMutable</a>, <a href="/web-doxygen/docs/api/classes/ccodeparser/#a106ea78aa6382f5b06dbd2563d5b99e4">CCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ab3604b365f2d78c31db8a2fae321b6a8">setCallContextForVar</a>, <a href="/web-doxygen/docs/api/classes/namespacedefmutable/#ab41129b22b4eac9adde902522bcca6c2">NamespaceDefMutable::setInline</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#af38aa297b15715ebca7acecf3144d839">writeAlphabeticalClassList</a>.</p>

</div>
</div>

### getResolvedNamespaceMutable() {#a03b786b13e194f1f753b5ec0b0ed1a38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NamespaceDefMutable * getResolvedNamespaceMutable (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; key)</td>
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



<p>Definition at line 150 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a03b786b13e194f1f753b5ec0b0ed1a38">150</a></span><span class="doxyLineContent"><span class="doxyHighlight">inline <a href="/web-doxygen/docs/api/classes/namespacedefmutable">NamespaceDefMutable</a> *<a href="#a03b786b13e194f1f753b5ec0b0ed1a38">getResolvedNamespaceMutable</a>(const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;key)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ae480c007a9e16b642a72ffb1119c5812">toNamespaceDefMutable</a>(<a href="#ac3b0b7f32404c52577802d626b64a49e">getResolvedNamespace</a>(key));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#ac3b0b7f32404c52577802d626b64a49e">getResolvedNamespace</a>, <a href="#a03b786b13e194f1f753b5ec0b0ed1a38">getResolvedNamespaceMutable</a> and <a href="#ae480c007a9e16b642a72ffb1119c5812">toNamespaceDefMutable</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a636b9cfb60b78163bb29dbb6f21def29">addEnumValuesToEnums</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a95106cfe8d0c8504016e0714ae0e10f7">addGlobalFunction</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a704656a4d637d9f99c1adef34aafe856">addVariableToFile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a82770a95f2aebec7ffee2162e3a67215">findEnums</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a043364950b2274c362fdd7e6b48d6ef6">findUsingDeclarations</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a9e88b70863796306c5f0070d263ab4c8">findUsingDirectives</a> and <a href="#a03b786b13e194f1f753b5ec0b0ed1a38">getResolvedNamespaceMutable</a>.</p>

</div>
</div>

### namespaceHasNestedClass() {#a3d15fcf5c959d5ce9db005cba5692094}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool namespaceHasNestedClass (const <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> * nd, bool filterClasses, <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939">ClassDef::CompoundType</a> ct)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 156 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>, definition at line 1837 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp">namespacedef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#a3d15fcf5c959d5ce9db005cba5692094">1837</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#a3d15fcf5c959d5ce9db005cba5692094">namespaceHasNestedClass</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *nd,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> filterClasses,<a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939">ClassDef::CompoundType</a> ct)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1838</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1839</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("&gt;namespaceHasNestedClass(%s,filterClasses=%d)\n",qPrint(nd-&gt;name()),filterClasses);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1840</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cnd : nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#a948889b7a35fb82ebcdf2598a63e1d8d">getNamespaces</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1841</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1842</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#a3d15fcf5c959d5ce9db005cba5692094">namespaceHasNestedClass</a>(cnd,filterClasses,ct))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1843</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1844</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("&lt;namespaceHasNestedClass(%s,filterClasses=%d): case1\n",qPrint(nd-&gt;name()),filterClasses);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1845</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1846</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1847</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1848</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1849</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/classlinkedrefmap">ClassLinkedRefMap</a> list = nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#ad43237a69f056b45fc87beed091688d5">getClasses</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1850</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (filterClasses)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1851</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1852</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (ct)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1853</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1854</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a6ff6e3b1bbf7e59a752826880e148528">ClassDef::Interface</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1855</span><span class="doxyLineContent"><span class="doxyHighlight">        list = nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#ae5d69194a246277c1ac27efe392a085c">getInterfaces</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1856</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1857</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939adbed80de6b389027e03afb5abb06f2c9">ClassDef::Struct</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1858</span><span class="doxyLineContent"><span class="doxyHighlight">        list = nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#a5c5e7b84cb85d95090306d81ec55a676">getStructs</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1859</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1860</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939ad14369c9a6f5e3977c0e02714a4beba8">ClassDef::Exception</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1861</span><span class="doxyLineContent"><span class="doxyHighlight">        list = nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#a7cf1f663e03f57dd359aaacf71c2e3be">getExceptions</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1862</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1863</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1864</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1865</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1866</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1867</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1868</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cd : list)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1869</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1870</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("candidate %s isLinkableInProject()=%d\n",qPrint(cd-&gt;name()),cd-&gt;isLinkableInProject());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1871</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;isLinkableInProject())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1872</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1873</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("&lt;namespaceHasNestedClass(%s,filterClasses=%d): case2\n",qPrint(nd-&gt;name()),filterClasses);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1874</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1875</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1876</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1877</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("&lt;namespaceHasNestedClass(%s,filterClasses=%d): case3\n",qPrint(nd-&gt;name()),filterClasses);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1878</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1879</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939ad14369c9a6f5e3977c0e02714a4beba8">ClassDef::Exception</a>, <a href="/web-doxygen/docs/api/classes/namespacedef/#ad43237a69f056b45fc87beed091688d5">NamespaceDef::getClasses</a>, <a href="/web-doxygen/docs/api/classes/namespacedef/#a7cf1f663e03f57dd359aaacf71c2e3be">NamespaceDef::getExceptions</a>, <a href="/web-doxygen/docs/api/classes/namespacedef/#ae5d69194a246277c1ac27efe392a085c">NamespaceDef::getInterfaces</a>, <a href="/web-doxygen/docs/api/classes/namespacedef/#a948889b7a35fb82ebcdf2598a63e1d8d">NamespaceDef::getNamespaces</a>, <a href="/web-doxygen/docs/api/classes/namespacedef/#a5c5e7b84cb85d95090306d81ec55a676">NamespaceDef::getStructs</a>, <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a6ff6e3b1bbf7e59a752826880e148528">ClassDef::Interface</a>, <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#a3d15fcf5c959d5ce9db005cba5692094">namespaceHasNestedClass</a> and <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939adbed80de6b389027e03afb5abb06f2c9">ClassDef::Struct</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#a3d15fcf5c959d5ce9db005cba5692094">namespaceHasNestedClass</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0a4d1d807b56446946886c0c6c7450cf">writeClassTreeInsideNamespaceElement</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6273279cbb942fdbf1988a7f5a336404">writeNamespaceTreeElement</a>.</p>

</div>
</div>

### namespaceHasNestedConcept() {#af84e6fea0b6f07072eab35b1569fd357}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool namespaceHasNestedConcept (const <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> * nd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 155 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>, definition at line 1813 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp">namespacedef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#af84e6fea0b6f07072eab35b1569fd357">1813</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#af84e6fea0b6f07072eab35b1569fd357">namespaceHasNestedConcept</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *nd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1814</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1815</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("&gt;namespaceHasNestedConcept(%s)\n",qPrint(nd-&gt;name()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1816</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cnd : nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#a948889b7a35fb82ebcdf2598a63e1d8d">getNamespaces</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1817</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1818</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#af84e6fea0b6f07072eab35b1569fd357">namespaceHasNestedConcept</a>(cnd))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1819</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1820</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("&lt;namespaceHasNestedConcept(%s): case1\n",qPrint(nd-&gt;name()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1821</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1822</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1823</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1824</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cnd : nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#a393d5ddac9a98c0f829b7866cce931dc">getConcepts</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1825</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1826</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("candidate %s isLinkableInProject()=%d\n",qPrint(cnd-&gt;name()),cnd-&gt;isLinkableInProject());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1827</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cnd-&gt;isLinkableInProject())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1828</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1829</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("&lt;namespaceHasNestedConcept(%s): case2\n",qPrint(nd-&gt;name()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1830</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1831</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1832</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1833</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("&lt;namespaceHasNestedConcept(%s): case3\n",qPrint(nd-&gt;name()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1834</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1835</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/namespacedef/#a393d5ddac9a98c0f829b7866cce931dc">NamespaceDef::getConcepts</a>, <a href="/web-doxygen/docs/api/classes/namespacedef/#a948889b7a35fb82ebcdf2598a63e1d8d">NamespaceDef::getNamespaces</a> and <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#af84e6fea0b6f07072eab35b1569fd357">namespaceHasNestedConcept</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#af84e6fea0b6f07072eab35b1569fd357">namespaceHasNestedConcept</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a9f3b04775e88a72b563fdd34c6f2646c">writeConceptTreeInsideNamespaceElement</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6273279cbb942fdbf1988a7f5a336404">writeNamespaceTreeElement</a>.</p>

</div>
</div>

### namespaceHasNestedNamespace() {#a061ac5e55a8b63f2c06e1f4e272cb011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool namespaceHasNestedNamespace (const <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> * nd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 154 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>, definition at line 1801 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp">namespacedef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#a061ac5e55a8b63f2c06e1f4e272cb011">1801</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#a061ac5e55a8b63f2c06e1f4e272cb011">namespaceHasNestedNamespace</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *nd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1802</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1803</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cnd : nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#a948889b7a35fb82ebcdf2598a63e1d8d">getNamespaces</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1804</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1805</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cnd-&gt;isLinkableInProject() &amp;&amp; !cnd-&gt;isAnonymous())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1806</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1807</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1808</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1809</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1810</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1811</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/namespacedef/#a948889b7a35fb82ebcdf2598a63e1d8d">NamespaceDef::getNamespaces</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6273279cbb942fdbf1988a7f5a336404">writeNamespaceTreeElement</a>.</p>

</div>
</div>

### replaceNamespaceAliases() {#a299c303cf66b245b416c9167b2f9aaa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void replaceNamespaceAliases (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 148 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>, definition at line 1781 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp">namespacedef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#a299c303cf66b245b416c9167b2f9aaa9">1781</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#a299c303cf66b245b416c9167b2f9aaa9">replaceNamespaceAliases</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1782</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1783</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("&gt; replaceNamespaceAliases(%s)\n",qPrint(name));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1784</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/containers-h/#a0bc125fc346e538d66d5ea1c33428f00">StringSet</a> namespacesTried;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1785</span><span class="doxyLineContent"><span class="doxyHighlight">  name = <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#abdb19859c5ccfaf3a834f47fedd3e06d">replaceNamespaceAliasesRec</a>(namespacesTried,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1786</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("&lt; replaceNamespaceAliases: result=%s\n",qPrint(name));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1787</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#abdb19859c5ccfaf3a834f47fedd3e06d">replaceNamespaceAliasesRec</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2855c4f3905bf9bd629622f65075b558">findClassRelation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a595b7d13e1597947419c621de298acad">findUsedClassesForClass</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5ecfe67024087367b33d18430021a3c0">getMemberFromSymbol</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a41fdc2a524c5339afd35c067a828459d">SymbolResolver::Private::getResolvedSymbolRec</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a3aea62dc3d2f6c0e0109e5aefc155a41">SymbolResolver::Private::getResolvedTypeRec</a> and <a href="/web-doxygen/docs/api/classes/namespacedefmutable/#ab41129b22b4eac9adde902522bcca6c2">NamespaceDefMutable::setInline</a>.</p>

</div>
</div>

### toNamespaceDef() {#ae303e4de18684cb3d0c72d936cc0654f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NamespaceDef * toNamespaceDef (<a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 141 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>, definition at line 1640 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp">namespacedef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ae303e4de18684cb3d0c72d936cc0654f">1640</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *<a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ae303e4de18684cb3d0c72d936cc0654f">toNamespaceDef</a>(<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1641</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1642</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d &amp;&amp; (</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/namespacedefimpl">NamespaceDefImpl</a>) || </span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/namespacedefaliasimpl">NamespaceDefAliasImpl</a>)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1643</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1644</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1645</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1646</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1647</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1648</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1649</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1650</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docsets/#a68e99525be1bdf8596ca067a014e9931">DocSets::addIndexItem</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a34803fafd2b7ff3f593f4c9a97c59f2d">NamespaceDefImpl::addInnerCompound</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a71f923667206aac9e24848997edd6d8b">buildNamespaceList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5dc8c4afa4009560979330b7c6fb2cb3">findGlobalMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a9e88b70863796306c5f0070d263ab4c8">findUsingDirectives</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#aab0947e93a77169efff48326518717ab">SymbolResolver::Private::followPath</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#aa723e85238b66b5916c25989013e52b8">generateClassMemberLink</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a92aa0c495ca4eb835bb914dbb5fefa35">getDefsNew</a>, <a href="/web-doxygen/docs/api/classes/namespacedefaliasimpl/#a5be38caca7bbb8eb32defba1f26a15b0">NamespaceDefAliasImpl::getNSAlias</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a60ffd0b23680e5318865a367b0d26871">SymbolResolver::Private::isAccessibleFrom</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a01a031ffd0a93eb06668c1e93fb57f69">SymbolResolver::Private::isAccessibleFromWithExpScope</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a263db4e9ffc625509018045b0345b31c">MemberDefImpl::moveTo</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a34157df0fe53d6d10cc4560ca942f488">resolveClassNestingRelations</a>, <a href="/web-doxygen/docs/api/classes/namespacedefmutable/#ab41129b22b4eac9adde902522bcca6c2">NamespaceDefMutable::setInline</a> and <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a83984e7adf06e5e5006d61c0634d8a54">writeJavasScriptSearchDataPage</a>.</p>

</div>
</div>

### toNamespaceDef() {#af52a8a4a35b2209c0c4609c23b5b82e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NamespaceDef * toNamespaceDef (<a href="/web-doxygen/docs/api/classes/definitionmutable">DefinitionMutable</a> * d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 142 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>, definition at line 1652 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp">namespacedef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#a11cdaa39ac25a83a376fa59f6b0a9cde">1652</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *<a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ae303e4de18684cb3d0c72d936cc0654f">toNamespaceDef</a>(<a href="/web-doxygen/docs/api/classes/definitionmutable">DefinitionMutable</a> *md)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1653</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1654</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d = <a href="/web-doxygen/docs/api/files/src/definition-cpp/#ab43e817b86eeee8909980167d1a140c8">toDefinition</a>(md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1655</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d &amp;&amp; </span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/namespacedefimpl">NamespaceDefImpl</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1656</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1657</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1658</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1659</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1660</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1661</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1662</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1663</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/definition-cpp/#ab43e817b86eeee8909980167d1a140c8">toDefinition</a>.</p>

</div>
</div>

### toNamespaceDef() {#ac4a3a7d929c1539b4580ef9895c48f0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const NamespaceDef * toNamespaceDef (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 143 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>, definition at line 1666 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp">namespacedef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ac4a3a7d929c1539b4580ef9895c48f0f">1666</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *<a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ae303e4de18684cb3d0c72d936cc0654f">toNamespaceDef</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1667</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1668</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d &amp;&amp; (</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/namespacedefimpl">NamespaceDefImpl</a>) || </span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/namespacedefaliasimpl">NamespaceDefAliasImpl</a>)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1669</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1670</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1671</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1672</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1673</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1674</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1675</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1676</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### toNamespaceDefMutable() {#ae480c007a9e16b642a72ffb1119c5812}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NamespaceDefMutable * toNamespaceDefMutable (<a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 144 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>, definition at line 1678 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp">namespacedef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ae480c007a9e16b642a72ffb1119c5812">1678</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/namespacedefmutable">NamespaceDefMutable</a> *<a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ae480c007a9e16b642a72ffb1119c5812">toNamespaceDefMutable</a>(<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1679</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1680</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d &amp;&amp; </span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/namespacedefimpl">NamespaceDefImpl</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1681</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1682</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/namespacedefmutable">NamespaceDefMutable</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1683</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1684</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1685</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1686</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1687</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1688</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a636b9cfb60b78163bb29dbb6f21def29">addEnumValuesToEnums</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a855be67fd81a52fbfc822a4e4b41cc7e">addListReferences</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a4219b5e9c9b107b0b5380459e032a142">addMembersToMemberGroup</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a035458fc750e2a32abad901b719f8392">addNamespaceToGroups</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a10458b8a16238a4eae5fb5019df747e8">adjustConfiguration</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a71f923667206aac9e24848997edd6d8b">buildNamespaceList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#acc3d9699d44f100227430700d7c62a68">buildScopeFromQualifiedName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#aeaa1f39cbbca14be0b6afe4528da6cf7">combineUsingRelations</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#adb540ceca54353f5cfffd531bf8d7a15">FileDefImpl::combineUsingRelations</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a732b5ed7216a2bb4f66b8e5c1862814b">NamespaceDefImpl::combineUsingRelations</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a4130a395a6948c0202fc85ac018a6236">computeMemberReferences</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a777a8d72bf18dc4c572fb70528ec18b2">countMembers</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5f7021c47224d92c76642ad8501d5eb6">distributeMemberGroupDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a82770a95f2aebec7ffee2162e3a67215">findEnums</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a8cb9252694dc27b52bd30efe903f9654">findScopeFromQualifiedName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad0183e79b7d98cfc8d0fd1b32efa27d5">findSectionsInDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a9e88b70863796306c5f0070d263ab4c8">findUsingDirectives</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#aca55661d627c7aa878d722fc2d1ae882">generateNamespaceDocs</a>, <a href="#a03b786b13e194f1f753b5ec0b0ed1a38">getResolvedNamespaceMutable</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ad1c6c890ed8e8ebcfe057f3de5db4fcb">NamespaceDefImpl::insertMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a02e748da779cf061b14c27d976efdb65">insertMemberAlias</a>, <a href="/web-doxygen/docs/api/classes/namespacedefmutable/#ab41129b22b4eac9adde902522bcca6c2">NamespaceDefMutable::setInline</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a510e0aa934874b28d777e3e1d1c13341">sortMemberLists</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#acbd9db076ae71bddeb6c5e9b27dd23da">writeTagFile</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
