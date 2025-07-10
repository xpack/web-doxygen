---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/symbolresolver/private
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Private` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct SymbolResolver::Private { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67735bb927b53dcc800ef7bce7929cb5">Private</a> (const FileDef *f)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab01c8bb71a27205b862142b2c049f9a6">reset</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa553c3d55ea82c85ce0f8a65861f32f7">setFileScope</a> (const FileDef *fileScope)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3aea62dc3d2f6c0e0109e5aefc155a41">getResolvedTypeRec</a> (VisitedKeys &amp;visitedKeys, const Definition *scope, const QCString &amp;n, const MemberDef **pTypeDef, QCString *pTemplSpec, QCString *pResolvedType)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41fdc2a524c5339afd35c067a828459d">getResolvedSymbolRec</a> (VisitedKeys &amp;visitedKeys, const Definition *scope, const QCString &amp;n, const QCString &amp;args, bool checkCV, bool insideCode, bool onlyLinkable, const MemberDef **pTypeDef, QCString *pTemplSpec, QCString *pResolvedType)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60ffd0b23680e5318865a367b0d26871">isAccessibleFrom</a> (VisitedKeys &amp;visitedKeys, AccessStack &amp;accessStack, const Definition *scope, const Definition *item)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01a031ffd0a93eb06668c1e93fb57f69">isAccessibleFromWithExpScope</a> (VisitedKeys &amp;visitedKeys, VisitedNamespaces &amp;visitedNamespaces, AccessStack &amp;accessStack, const Definition *scope, const Definition *item, const QCString &amp;explicitScopePart)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef9c4245c6f445e282a59005f1f6ca5a">getResolvedType</a> (VisitedKeys &amp;visitedKeys, const Definition *scope, const Definition *d, const QCString &amp;explicitScopePart, const ArgumentList *actTemplParams, int &amp;minDistance, const ClassDef *&amp;bestMatch, const MemberDef *&amp;bestTypedef, QCString &amp;bestTemplSpec, QCString &amp;bestResolvedType)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40f0f9c9cb6b6b7392ae6e695fc74671">getResolvedSymbol</a> (VisitedKeys &amp;visitedKeys, const Definition *scope, const Definition *d, const QCString &amp;args, bool checkCV, bool insideCode, const QCString &amp;explicitScopePart, const QCString &amp;strippedTemplateParams, bool forceCallable, int &amp;minDistance, const Definition *&amp;bestMatch, const MemberDef *&amp;bestTypedef, QCString &amp;bestTemplSpec, QCString &amp;bestResolvedType)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a551a021a6f4d4732e5181f8041375066">newResolveTypedef</a> (VisitedKeys &amp;visitedKeys, const Definition *scope, const MemberDef *md, const MemberDef **pMemType, QCString *pTemplSpec, QCString *pResolvedType, const ArgumentList *actTemplParams=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab0947e93a77169efff48326518717ab">followPath</a> (VisitedKeys &amp;visitedKeys, const Definition *start, const QCString &amp;path)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ba942e1e7634e03d9ecb279ea62f2b3">endOfPathIsUsedClass</a> (const LinkedRefMap&lt; const Definition &gt; &amp;dl, const QCString &amp;localName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46a2ef2308f1ef7d03889cea544d4909">accessibleViaUsingNamespace</a> (VisitedKeys &amp;visitedKeys, VisitedNamespaceKeys &amp;visitedNamespaces, const LinkedRefMap&lt; NamespaceDef &gt; &amp;nl, const Definition *item, const QCString &amp;explicitScopePart="", int level=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41e981742ff67fe146064ae772af3f72">accessibleViaUsingDefinition</a> (VisitedKeys &amp;visitedKeys, const LinkedRefMap&lt; const Definition &gt; &amp;dl, const Definition *item, const QCString &amp;explicitScopePart="")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a763d03603a7b427c9f02719fb95b2c30">substTypedef</a> (VisitedKeys &amp;visitedKeys, const Definition *scope, const QCString &amp;name, const MemberDef **pTypeDef=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7af4e916211ea5af0a6d86560c7216e">resolvedType</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12df5d8fbcd835e0484e12a02eca4ceb">typeDef</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac446c39cc6dcbdda4dd7532c0e8e695d">templateSpec</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; std::string, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae906eac3154529faa0b02dabaa1b54b1">m_resolvedTypedefs</a></td>
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


<p>Definition at line 112 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Private() {#a67735bb927b53dcc800ef7bce7929cb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolResolver::Private::Private (const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * f)</td>
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



<p>Definition at line 115 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a67735bb927b53dcc800ef7bce7929cb5">115</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a67735bb927b53dcc800ef7bce7929cb5">Private</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *f) : <a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>(f) {}</span></span></div>

</div>


<p>Reference <a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getResolvedSymbolRec() {#a41fdc2a524c5339afd35c067a828459d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Definition * SymbolResolver::Private::getResolvedSymbolRec (<a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a62fc03f5f79aa6176eb0cb02cb054ac9">VisitedKeys</a> &amp; visitedKeys, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * scope, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; n, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; args, bool checkCV, bool insideCode, bool onlyLinkable, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> ** pTypeDef, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> * pTemplSpec, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> * pResolvedType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a41fdc2a524c5339afd35c067a828459d">390</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *<a href="#a41fdc2a524c5339afd35c067a828459d">SymbolResolver::Private::getResolvedSymbolRec</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlight">           <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a62fc03f5f79aa6176eb0cb02cb054ac9">VisitedKeys</a> &amp;visitedKeys,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *scope,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;n,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;args,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> checkCV,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> insideCode,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> onlyLinkable,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> **pTypeDef,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">           <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> *pTemplSpec,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">           <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> *pResolvedType)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">402</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"scope={} name={} args={} checkCV={} insideCode={}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">      scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(),n,args,checkCV,insideCode);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (n.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">405</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> explicitScopePart;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">406</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> strippedTemplateParams;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">407</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> scopeName=scope!=<a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a> ? scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>() : <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">408</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name=<a href="/web-doxygen/docs/api/files/src/util-cpp/#ad87c70b117b898e5077a28ba5114c8c2">stripTemplateSpecifiersFromScope</a>(n,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,&amp;strippedTemplateParams,scopeName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">409</span><span class="doxyLineContent"><span class="doxyHighlight">  std::unique_ptr&lt;ArgumentList&gt; actTemplParams;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!strippedTemplateParams.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightComment">// template part that was stripped</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">411</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">412</span><span class="doxyLineContent"><span class="doxyHighlight">    actTemplParams = <a href="/web-doxygen/docs/api/files/src/defargs-h/#a88825bfb79a9c15e54ff57415b4de54d">stringToArgumentList</a>(scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">getLanguage</a>(),strippedTemplateParams);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">413</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">414</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">415</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> qualifierIndex = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a84e80a5dfaa2db05ad8b5d2e8d0f58f7">computeQualifiedIndex</a>(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("name=%s qualifierIndex=%d\n",qPrint(name),qualifierIndex);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">417</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (qualifierIndex!=-1) </span><span class="doxyHighlightComment">// qualified name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">418</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">419</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// split off the explicit scope part</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span><span class="doxyLineContent"><span class="doxyHighlight">    explicitScopePart=name.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(qualifierIndex);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">421</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// todo: improve namespace alias substitution</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">422</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#a299c303cf66b245b416c9167b2f9aaa9">replaceNamespaceAliases</a>(explicitScopePart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">423</span><span class="doxyLineContent"><span class="doxyHighlight">    name=name.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(qualifierIndex+2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">424</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">425</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"qualifierIndex={} name={} explicitScopePart={} strippedTemplateParams={}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">426</span><span class="doxyLineContent"><span class="doxyHighlight">                 qualifierIndex,name,explicitScopePart,strippedTemplateParams);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">427</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">428</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (name.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">429</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">430</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"empty name qualifierIndex={}"</span><span class="doxyHighlight">,qualifierIndex);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">431</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// empty name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">432</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">433</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">434</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">435</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;range1 = <a href="/web-doxygen/docs/api/classes/doxygen/#adcf907e4baf6aafe25d9a812c2f58e14">Doxygen::symbolMap</a>-&gt;find(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;range  = (range1.empty() &amp;&amp; (i=name.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">))!=-1) ? <a href="/web-doxygen/docs/api/classes/doxygen/#adcf907e4baf6aafe25d9a812c2f58e14">Doxygen::symbolMap</a>-&gt;find(name.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(i)) : range1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (range.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">439</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"no symbols with name '{}' (including unspecialized)"</span><span class="doxyHighlight">,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">441</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">442</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"{} -&gt; {} candidates"</span><span class="doxyHighlight">,name,range.<a href="/web-doxygen/docs/api/classes/qcstring/#a957be37e3b98707fc7e8daeff18e391b">size</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasUsingStatements =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">    (<a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a> &amp;&amp; (!<a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>-&gt;getUsedNamespaces().empty() ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">446</span><span class="doxyLineContent"><span class="doxyHighlight">                     !<a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>-&gt;getUsedDefinitions().empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">447</span><span class="doxyLineContent"><span class="doxyHighlight">    );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Since it is often the case that the same name is searched in the same</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// scope over an over again (especially for the linked source code generation)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// we use a cache to collect previous results. This is possible since the</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// result of a lookup is deterministic. As the key we use the concatenated</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// scope, the name to search for and the explicit scope prefix. The speedup</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// achieved by this simple cache can be enormous.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> scopeNameLen = scope!=<a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a> ? scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()+1 : 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> nameLen = name.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> explicitPartLen = explicitScopePart.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">457</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> strippedTemplateParamsLen = strippedTemplateParams.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> fileScopeLen = hasUsingStatements ? 1+<a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>-&gt;absFilePath().length() : 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> argsLen = args.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// below is a more efficient coding of</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// QCString key=scope-&gt;name()+"+"+name+"+"+explicitScopePart+args+typesOnly?'T':'F';</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string key;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">  key.reserve(scopeNameLen+nameLen+explicitPartLen+strippedTemplateParamsLen+fileScopeLen+argsLen);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (scope!=<a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">    key+=scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">    key+=</span><span class="doxyHighlightCharLiteral">'+'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">  key+=name.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">  key+=</span><span class="doxyHighlightCharLiteral">'+'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">  key+=explicitScopePart.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">  key+=strippedTemplateParams.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// if a file scope is given and it contains using statements we should</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// also use the file part in the key (as a class name can be in</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// two different namespaces and a using statement in a file can select</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// one of them).</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">479</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hasUsingStatements)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// below is a more efficient coding of</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// key+="+"+m_fileScope-&gt;name();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">    key+=</span><span class="doxyHighlightCharLiteral">'+'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">    key+=<a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>-&gt;absFilePath().str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (argsLen&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">    key+=</span><span class="doxyHighlightCharLiteral">'+'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">    key+=args.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *bestMatch=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (std::find(visitedKeys.begin(),visitedKeys.end(),key)!=std::end(visitedKeys))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// we are already in the middle of find the definition for this key.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// avoid recursion</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// remember the key</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span><span class="doxyLineContent"><span class="doxyHighlight">    visitedKeys.push_back(key);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/lookupinfo">LookupInfo</a> *pval = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">      std::lock_guard lock(<a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#abf10ed4dca35ec7b624c1aa7cd018327">g_cacheMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">      pval = <a href="/web-doxygen/docs/api/classes/doxygen/#a934a6ff68e6c5baecdbdf6fa6899b67d">Doxygen::symbolLookupCache</a>-&gt;find(key);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"key={} found={}"</span><span class="doxyHighlight">,key,pval!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pval)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pTemplSpec)    *pTemplSpec=pval-&gt;<a href="/web-doxygen/docs/api/structs/lookupinfo/#ab6109313beafe89f7d42431f8da344fb">templSpec</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pTypeDef)      *pTypeDef=pval-&gt;<a href="/web-doxygen/docs/api/structs/lookupinfo/#abae8ff1217132e626eeb3380cc700053">typeDef</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pResolvedType) *pResolvedType=pval-&gt;<a href="/web-doxygen/docs/api/structs/lookupinfo/#a55af5dfe2282dcc19615ac1e0ace76ff">resolvedType</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">513</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"found cached name={} templSpec={} typeDef={} resolvedTypedef={}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">514</span><span class="doxyLineContent"><span class="doxyHighlight">          pval-&gt;<a href="/web-doxygen/docs/api/structs/lookupinfo/#a9421fd652d8b718b86eb095de4483146">definition</a>?pval-&gt;<a href="/web-doxygen/docs/api/structs/lookupinfo/#a9421fd652d8b718b86eb095de4483146">definition</a>-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">515</span><span class="doxyLineContent"><span class="doxyHighlight">          pval-&gt;<a href="/web-doxygen/docs/api/structs/lookupinfo/#ab6109313beafe89f7d42431f8da344fb">templSpec</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">516</span><span class="doxyLineContent"><span class="doxyHighlight">          pval-&gt;<a href="/web-doxygen/docs/api/structs/lookupinfo/#abae8ff1217132e626eeb3380cc700053">typeDef</a>?pval-&gt;<a href="/web-doxygen/docs/api/structs/lookupinfo/#abae8ff1217132e626eeb3380cc700053">typeDef</a>-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">517</span><span class="doxyLineContent"><span class="doxyHighlight">          pval-&gt;<a href="/web-doxygen/docs/api/structs/lookupinfo/#a55af5dfe2282dcc19615ac1e0ace76ff">resolvedType</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">518</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> pval-&gt;<a href="/web-doxygen/docs/api/structs/lookupinfo/#a9421fd652d8b718b86eb095de4483146">definition</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">521</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *bestTypedef=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> bestTemplSpec;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> bestResolvedType;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> minDistance=10000; </span><span class="doxyHighlightComment">// init at "infinite"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">525</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">526</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d : range)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">527</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">528</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a0632c385ff1dbdd8af012ee995e3c1a7">isCodeSymbol</a>(d-&gt;definitionType()) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">529</span><span class="doxyLineContent"><span class="doxyHighlight">          (!onlyLinkable ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">530</span><span class="doxyLineContent"><span class="doxyHighlight">           d-&gt;isLinkable() ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">531</span><span class="doxyLineContent"><span class="doxyHighlight">           d-&gt;isLinkableInProject() ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">532</span><span class="doxyLineContent"><span class="doxyHighlight">           (d-&gt;definitionType()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea203462c7d34ced15beac624562c2708e">Definition::TypeFile</a> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">533</span><span class="doxyLineContent"><span class="doxyHighlight">            (<a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a4114c484f3ccea1048608b9caa9f51de">toFileDef</a>(d))-&gt;generateSourceFile()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">534</span><span class="doxyLineContent"><span class="doxyHighlight">           ) </span><span class="doxyHighlightComment">// undocumented file that has source code we can link to</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">535</span><span class="doxyLineContent"><span class="doxyHighlight">          )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">536</span><span class="doxyLineContent"><span class="doxyHighlight">         )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">537</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">538</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="#a40f0f9c9cb6b6b7392ae6e695fc74671">getResolvedSymbol</a>(visitedKeys,scope,d,args,checkCV,insideCode,explicitScopePart,strippedTemplateParams,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">539</span><span class="doxyLineContent"><span class="doxyHighlight">            minDistance,bestMatch,bestTypedef,bestTemplSpec,bestResolvedType);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">540</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">541</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">  (minDistance==0) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// we can stop reaching if we already reached distance 0</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">542</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">543</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">544</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// in case we are looking for e.g. func() and the real function is func(int x) we also</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">545</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// accept func(), see example 36 in the test set.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">546</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bestMatch==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> &amp;&amp; args==</span><span class="doxyHighlightStringLiteral">"()"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">547</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">548</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d : range)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">549</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">550</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a0632c385ff1dbdd8af012ee995e3c1a7">isCodeSymbol</a>(d-&gt;definitionType()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">551</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">552</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a40f0f9c9cb6b6b7392ae6e695fc74671">getResolvedSymbol</a>(visitedKeys,scope,d,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,insideCode,explicitScopePart,strippedTemplateParams,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">553</span><span class="doxyLineContent"><span class="doxyHighlight">            minDistance,bestMatch,bestTypedef,bestTemplSpec,bestResolvedType);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">554</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">555</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">  (minDistance==0) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// we can stop reaching if we already reached distance 0</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">556</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">557</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">558</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">559</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pTypeDef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">560</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">561</span><span class="doxyLineContent"><span class="doxyHighlight">      *pTypeDef = bestTypedef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">563</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pTemplSpec)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">      *pTemplSpec = bestTemplSpec;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">566</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">567</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pResolvedType)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">568</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">569</span><span class="doxyLineContent"><span class="doxyHighlight">      *pResolvedType = bestResolvedType;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">570</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">571</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">572</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/structs/lookupinfo">LookupInfo</a> lookupInfo(bestMatch,bestTypedef,bestTemplSpec,bestResolvedType);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlight">      std::lock_guard lock(<a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#abf10ed4dca35ec7b624c1aa7cd018327">g_cacheMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">575</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// we need to insert the item in the cache again, as it could be removed in the meantime</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">576</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/doxygen/#a934a6ff68e6c5baecdbdf6fa6899b67d">Doxygen::symbolLookupCache</a>-&gt;insert(key,std::move(lookupInfo));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">577</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">578</span><span class="doxyLineContent"><span class="doxyHighlight">    visitedKeys.erase(std::remove(visitedKeys.begin(),visitedKeys.end(),key),visitedKeys.end());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"found name={} templSpec={} typeDef={} resolvedTypedef={}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">        bestMatch?bestMatch-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span><span class="doxyLineContent"><span class="doxyHighlight">        bestTemplSpec,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">        bestTypedef?bestTypedef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">584</span><span class="doxyLineContent"><span class="doxyHighlight">        bestResolvedType);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">586</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> bestMatch;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">587</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a84e80a5dfaa2db05ad8b5d2e8d0f58f7">computeQualifiedIndex</a>, <a href="/web-doxygen/docs/api/structs/lookupinfo/#a9421fd652d8b718b86eb095de4483146">LookupInfo::definition</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#abf10ed4dca35ec7b624c1aa7cd018327">g_cacheMutex</a>, <a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">Definition::getLanguage</a>, <a href="#a40f0f9c9cb6b6b7392ae6e695fc74671">getResolvedSymbol</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a>, <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a0632c385ff1dbdd8af012ee995e3c1a7">isCodeSymbol</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#a299c303cf66b245b416c9167b2f9aaa9">replaceNamespaceAliases</a>, <a href="/web-doxygen/docs/api/structs/lookupinfo/#a55af5dfe2282dcc19615ac1e0ace76ff">LookupInfo::resolvedType</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a957be37e3b98707fc7e8daeff18e391b">QCString::size</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/files/src/defargs-h/#a88825bfb79a9c15e54ff57415b4de54d">stringToArgumentList</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad87c70b117b898e5077a28ba5114c8c2">stripTemplateSpecifiersFromScope</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a934a6ff68e6c5baecdbdf6fa6899b67d">Doxygen::symbolLookupCache</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#adcf907e4baf6aafe25d9a812c2f58e14">Doxygen::symbolMap</a>, <a href="/web-doxygen/docs/api/structs/lookupinfo/#ab6109313beafe89f7d42431f8da344fb">LookupInfo::templSpec</a>, <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a4114c484f3ccea1048608b9caa9f51de">toFileDef</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/structs/lookupinfo/#abae8ff1217132e626eeb3380cc700053">LookupInfo::typeDef</a> and <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea203462c7d34ced15beac624562c2708e">Definition::TypeFile</a>.</p>

</div>
</div>

### getResolvedTypeRec() {#a3aea62dc3d2f6c0e0109e5aefc155a41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ClassDef * SymbolResolver::Private::getResolvedTypeRec (<a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a62fc03f5f79aa6176eb0cb02cb054ac9">VisitedKeys</a> &amp; visitedKeys, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * scope, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; n, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> ** pTypeDef, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> * pTemplSpec, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> * pResolvedType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3aea62dc3d2f6c0e0109e5aefc155a41">230</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *<a href="#a3aea62dc3d2f6c0e0109e5aefc155a41">SymbolResolver::Private::getResolvedTypeRec</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">           <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a62fc03f5f79aa6176eb0cb02cb054ac9">VisitedKeys</a> &amp;visitedKeys,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *scope,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;n,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> **pTypeDef,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">           <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> *pTemplSpec,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">           <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> *pResolvedType)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"scope={} name={}"</span><span class="doxyHighlight">,scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(),n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (n.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> explicitScopePart;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> strippedTemplateParams;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> scopeName=scope!=<a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a> ? scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>() : <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name=<a href="/web-doxygen/docs/api/files/src/util-cpp/#ad87c70b117b898e5077a28ba5114c8c2">stripTemplateSpecifiersFromScope</a>(n,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,&amp;strippedTemplateParams,scopeName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">  std::unique_ptr&lt;ArgumentList&gt; actTemplParams;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!strippedTemplateParams.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightComment">// template part that was stripped</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">    actTemplParams = <a href="/web-doxygen/docs/api/files/src/defargs-h/#a88825bfb79a9c15e54ff57415b4de54d">stringToArgumentList</a>(scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">getLanguage</a>(),strippedTemplateParams);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> qualifierIndex = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a84e80a5dfaa2db05ad8b5d2e8d0f58f7">computeQualifiedIndex</a>(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("name=%s qualifierIndex=%d\n",qPrint(name),qualifierIndex);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (qualifierIndex!=-1) </span><span class="doxyHighlightComment">// qualified name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// split off the explicit scope part</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">    explicitScopePart=name.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(qualifierIndex);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// todo: improve namespace alias substitution</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#a299c303cf66b245b416c9167b2f9aaa9">replaceNamespaceAliases</a>(explicitScopePart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">    name=name.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(qualifierIndex+2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (name.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"empty name"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// empty name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;range = <a href="/web-doxygen/docs/api/classes/doxygen/#adcf907e4baf6aafe25d9a812c2f58e14">Doxygen::symbolMap</a>-&gt;find(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (range.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"no symbol with this name"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasUsingStatements =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">    (<a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a> &amp;&amp; (!<a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>-&gt;getUsedNamespaces().empty() ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">                     !<a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>-&gt;getUsedDefinitions().empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">    );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Since it is often the case that the same name is searched in the same</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// scope over an over again (especially for the linked source code generation)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// we use a cache to collect previous results. This is possible since the</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// result of a lookup is deterministic. As the key we use the concatenated</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// scope, the name to search for and the explicit scope prefix. The speedup</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// achieved by this simple cache can be enormous.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> scopeNameLen = scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> nameLen = name.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> explicitPartLen = explicitScopePart.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> fileScopeLen = hasUsingStatements ? 1+<a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>-&gt;absFilePath().length() : 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// below is a more efficient coding of</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// QCString key=scope-&gt;name()+"+"+name+"+"+explicitScopePart+args+typesOnly?'T':'F';</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> key(scopeNameLen+nameLen+explicitPartLen+fileScopeLen, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *pk=key.<a href="/web-doxygen/docs/api/classes/qcstring/#a5f5c9dc172d638c8d7b07010d100117a">rawData</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/qcstring-h/#ac32a77e081e980d3a32c45578b7be389">qstrcpy</a>(pk,scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()); *(pk+scopeNameLen-1)=</span><span class="doxyHighlightCharLiteral">'+'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">  pk+=scopeNameLen;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/qcstring-h/#ac32a77e081e980d3a32c45578b7be389">qstrcpy</a>(pk,name.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()); *(pk+nameLen-1)=</span><span class="doxyHighlightCharLiteral">'+'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">  pk+=nameLen;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/qcstring-h/#ac32a77e081e980d3a32c45578b7be389">qstrcpy</a>(pk,explicitScopePart.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">  pk+=explicitPartLen;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// if a file scope is given and it contains using statements we should</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// also use the file part in the key (as a class name can be in</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// two different namespaces and a using statement in a file can select</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// one of them).</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hasUsingStatements)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// below is a more efficient coding of</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// key+="+"+m_fileScope-&gt;name();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">    *pk++=</span><span class="doxyHighlightCharLiteral">'+'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/qcstring-h/#ac32a77e081e980d3a32c45578b7be389">qstrcpy</a>(pk,<a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>-&gt;absFilePath().data());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">    pk+=fileScopeLen-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">  *pk=</span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *bestMatch=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (std::find(visitedKeys.begin(),visitedKeys.end(),key.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>())!=std::end(visitedKeys))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// we are already in the middle of find the definition for this key.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// avoid recursion</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"recursion detected"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// remember the key</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">    visitedKeys.push_back(key.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/lookupinfo">LookupInfo</a> *pval = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">      std::lock_guard lock(<a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#abf10ed4dca35ec7b624c1aa7cd018327">g_cacheMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">      pval = <a href="/web-doxygen/docs/api/classes/doxygen/#a41becb082a98f10b1162bb6cd83b0918">Doxygen::typeLookupCache</a>-&gt;find(key.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"key={} found={}"</span><span class="doxyHighlight">,key,pval!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pval)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pTemplSpec)    *pTemplSpec=pval-&gt;<a href="/web-doxygen/docs/api/structs/lookupinfo/#ab6109313beafe89f7d42431f8da344fb">templSpec</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pTypeDef)      *pTypeDef=pval-&gt;<a href="/web-doxygen/docs/api/structs/lookupinfo/#abae8ff1217132e626eeb3380cc700053">typeDef</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pResolvedType) *pResolvedType=pval-&gt;<a href="/web-doxygen/docs/api/structs/lookupinfo/#a55af5dfe2282dcc19615ac1e0ace76ff">resolvedType</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"found cached name={} templSpec={} typeDef={} resolvedTypedef={}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlight">          pval-&gt;<a href="/web-doxygen/docs/api/structs/lookupinfo/#a9421fd652d8b718b86eb095de4483146">definition</a>?pval-&gt;<a href="/web-doxygen/docs/api/structs/lookupinfo/#a9421fd652d8b718b86eb095de4483146">definition</a>-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">          pval-&gt;<a href="/web-doxygen/docs/api/structs/lookupinfo/#ab6109313beafe89f7d42431f8da344fb">templSpec</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">          pval-&gt;<a href="/web-doxygen/docs/api/structs/lookupinfo/#abae8ff1217132e626eeb3380cc700053">typeDef</a>?pval-&gt;<a href="/web-doxygen/docs/api/structs/lookupinfo/#abae8ff1217132e626eeb3380cc700053">typeDef</a>-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">          pval-&gt;<a href="/web-doxygen/docs/api/structs/lookupinfo/#a55af5dfe2282dcc19615ac1e0ace76ff">resolvedType</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>(pval-&gt;<a href="/web-doxygen/docs/api/structs/lookupinfo/#a9421fd652d8b718b86eb095de4483146">definition</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *bestTypedef=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">347</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> bestTemplSpec;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> bestResolvedType;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> minDistance=10000; </span><span class="doxyHighlightComment">// init at "infinite"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">351</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d : range)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a0632c385ff1dbdd8af012ee995e3c1a7">isCodeSymbol</a>(d-&gt;definitionType()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">355</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/symbolresolver/#a6f023b174a5e9064fb4afdf69a02f284">getResolvedType</a>(visitedKeys,scope,d,explicitScopePart,actTemplParams.get(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">356</span><span class="doxyLineContent"><span class="doxyHighlight">            minDistance,bestMatch,bestTypedef,bestTemplSpec,bestResolvedType);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">  (minDistance==0) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// we can stop reaching if we already reached distance 0</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">361</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pTypeDef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span><span class="doxyLineContent"><span class="doxyHighlight">      *pTypeDef = bestTypedef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pTemplSpec)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">366</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">367</span><span class="doxyLineContent"><span class="doxyHighlight">      *pTemplSpec = bestTemplSpec;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pResolvedType)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">      *pResolvedType = bestResolvedType;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">      std::lock_guard lock(<a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#abf10ed4dca35ec7b624c1aa7cd018327">g_cacheMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/doxygen/#a41becb082a98f10b1162bb6cd83b0918">Doxygen::typeLookupCache</a>-&gt;insert(key.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">                            <a href="/web-doxygen/docs/api/structs/lookupinfo">LookupInfo</a>(bestMatch,bestTypedef,bestTemplSpec,bestResolvedType));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">    visitedKeys.erase(std::remove(visitedKeys.begin(), visitedKeys.end(), key.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()), visitedKeys.end());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"found name={} templSpec={} typeDef={} resolvedTypedef={}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">        bestMatch?bestMatch-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">        bestTemplSpec,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">        bestTypedef?bestTypedef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">        bestResolvedType);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> bestMatch;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a84e80a5dfaa2db05ad8b5d2e8d0f58f7">computeQualifiedIndex</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/structs/lookupinfo/#a9421fd652d8b718b86eb095de4483146">LookupInfo::definition</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>, <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#abf10ed4dca35ec7b624c1aa7cd018327">g_cacheMutex</a>, <a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">Definition::getLanguage</a>, <a href="/web-doxygen/docs/api/classes/symbolresolver/#a6f023b174a5e9064fb4afdf69a02f284">SymbolResolver::getResolvedType</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a>, <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a0632c385ff1dbdd8af012ee995e3c1a7">isCodeSymbol</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#ac32a77e081e980d3a32c45578b7be389">qstrcpy</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a5f5c9dc172d638c8d7b07010d100117a">QCString::rawData</a>, <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#a299c303cf66b245b416c9167b2f9aaa9">replaceNamespaceAliases</a>, <a href="/web-doxygen/docs/api/structs/lookupinfo/#a55af5dfe2282dcc19615ac1e0ace76ff">LookupInfo::resolvedType</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/files/src/defargs-h/#a88825bfb79a9c15e54ff57415b4de54d">stringToArgumentList</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad87c70b117b898e5077a28ba5114c8c2">stripTemplateSpecifiersFromScope</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#adcf907e4baf6aafe25d9a812c2f58e14">Doxygen::symbolMap</a>, <a href="/web-doxygen/docs/api/structs/lookupinfo/#ab6109313beafe89f7d42431f8da344fb">LookupInfo::templSpec</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/structs/lookupinfo/#abae8ff1217132e626eeb3380cc700053">LookupInfo::typeDef</a> and <a href="/web-doxygen/docs/api/classes/doxygen/#a41becb082a98f10b1162bb6cd83b0918">Doxygen::typeLookupCache</a>.</p>


<p>Referenced by <a href="#a551a021a6f4d4732e5181f8041375066">newResolveTypedef</a>.</p>

</div>
</div>

### isAccessibleFrom() {#a60ffd0b23680e5318865a367b0d26871}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int SymbolResolver::Private::isAccessibleFrom (<a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a62fc03f5f79aa6176eb0cb02cb054ac9">VisitedKeys</a> &amp; visitedKeys, <a href="/web-doxygen/docs/api/classes/accessstack">AccessStack</a> &amp; accessStack, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * scope, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * item)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a60ffd0b23680e5318865a367b0d26871">1361</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a60ffd0b23680e5318865a367b0d26871">SymbolResolver::Private::isAccessibleFrom</a>(<a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a62fc03f5f79aa6176eb0cb02cb054ac9">VisitedKeys</a> &amp;visitedKeys,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1362</span><span class="doxyLineContent"><span class="doxyHighlight">                                              <a href="/web-doxygen/docs/api/classes/accessstack">AccessStack</a> &amp;accessStack,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1363</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *scope,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1364</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *item)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1365</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1366</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"scope={} item={} item.definitionType={}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1367</span><span class="doxyLineContent"><span class="doxyHighlight">      scope?scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), item?item-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1368</span><span class="doxyLineContent"><span class="doxyHighlight">      item?(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)item-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>():-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1369</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1370</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (accessStack.<a href="/web-doxygen/docs/api/classes/accessstack/#a9d144e56b75159f1bba48c299fb0a1ee">find</a>(scope,<a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>,item))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1371</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1372</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"already processed!"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1373</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1374</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1375</span><span class="doxyLineContent"><span class="doxyHighlight">  accessStack.<a href="/web-doxygen/docs/api/classes/accessstack/#aa6044b906f049112dc68aff47e91d4a7">push</a>(scope,<a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>,item);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1376</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1377</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> result=0; </span><span class="doxyHighlightComment">// assume we found it</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1378</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1379</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1380</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *itemScope=item-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1381</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> itemIsMember = item-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea422b8b811bcf8869a67732f9829d005b">Definition::TypeMember</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1382</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> itemIsClass  = item-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1383</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1384</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// if item is a global member and scope points to a specific file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1385</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// we adjust the scope so the file gets preference over members with the same name in</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1386</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// other files.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1387</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((itemIsMember || itemIsClass) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1388</span><span class="doxyLineContent"><span class="doxyHighlight">      (itemScope==<a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a> || </span><span class="doxyHighlightComment">// global</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1389</span><span class="doxyLineContent"><span class="doxyHighlight">       (itemScope &amp;&amp; itemScope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">startsWith</a>(</span><span class="doxyHighlightStringLiteral">"anonymous_namespace{"</span><span class="doxyHighlight">)) </span><span class="doxyHighlightComment">// member of an anonymous namespace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1390</span><span class="doxyLineContent"><span class="doxyHighlight">      ) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1391</span><span class="doxyLineContent"><span class="doxyHighlight">      scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea203462c7d34ced15beac624562c2708e">Definition::TypeFile</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1392</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1393</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (itemIsMember)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1394</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1395</span><span class="doxyLineContent"><span class="doxyHighlight">      itemScope = <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>(item)-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5036fd8ee16b186925236105029ee823">getFileDef</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1396</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1397</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (itemIsClass)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1398</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1399</span><span class="doxyLineContent"><span class="doxyHighlight">      itemScope = <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>(item)-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#aed4a0864e51e5a3ac616f6c8e10f56c6">getFileDef</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1400</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1401</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"adjusting scope to {}"</span><span class="doxyHighlight">,itemScope?itemScope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1402</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1403</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1404</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> memberAccessibleFromScope =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1405</span><span class="doxyLineContent"><span class="doxyHighlight">      (itemIsMember &amp;&amp;                                                     </span><span class="doxyHighlightComment">// a member</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1406</span><span class="doxyLineContent"><span class="doxyHighlight">       itemScope &amp;&amp; itemScope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a>  &amp;&amp; </span><span class="doxyHighlightComment">// of a class</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1407</span><span class="doxyLineContent"><span class="doxyHighlight">       scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a> &amp;&amp;                   </span><span class="doxyHighlightComment">// accessible</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1408</span><span class="doxyLineContent"><span class="doxyHighlight">       (<a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>(scope))-&gt;isAccessibleMember(<a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>(item)) </span><span class="doxyHighlightComment">// from scope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1409</span><span class="doxyLineContent"><span class="doxyHighlight">      );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1410</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> nestedClassInsideBaseClass =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1411</span><span class="doxyLineContent"><span class="doxyHighlight">      (itemIsClass &amp;&amp;                                                      </span><span class="doxyHighlightComment">// a nested class</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1412</span><span class="doxyLineContent"><span class="doxyHighlight">       itemScope &amp;&amp; itemScope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a> &amp;&amp;  </span><span class="doxyHighlightComment">// inside a base</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1413</span><span class="doxyLineContent"><span class="doxyHighlight">       scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a> &amp;&amp;                   </span><span class="doxyHighlightComment">// class of scope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1414</span><span class="doxyLineContent"><span class="doxyHighlight">       (<a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>(scope))-&gt;isBaseClass(<a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>(itemScope),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1415</span><span class="doxyLineContent"><span class="doxyHighlight">      );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1416</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> enumValueOfStrongEnum =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1417</span><span class="doxyLineContent"><span class="doxyHighlight">      (itemIsMember &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1418</span><span class="doxyLineContent"><span class="doxyHighlight">       <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>(item)-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5b99e725308ea15248722f69611844aa">isStrongEnumValue</a>() &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1419</span><span class="doxyLineContent"><span class="doxyHighlight">       scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea422b8b811bcf8869a67732f9829d005b">Definition::TypeMember</a> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1420</span><span class="doxyLineContent"><span class="doxyHighlight">       <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>(scope)-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ab99e728441f3ce7d5784ad6fb6df18f2">isEnumerate</a>() &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1421</span><span class="doxyLineContent"><span class="doxyHighlight">       scope==<a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>(item)-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#af99e46c3a8716075dfcb6debf428e44f">getEnumScope</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1422</span><span class="doxyLineContent"><span class="doxyHighlight">      );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1423</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1424</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (itemScope==scope || memberAccessibleFromScope || nestedClassInsideBaseClass || enumValueOfStrongEnum)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1425</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1426</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"memberAccessibleFromScope={} nestedClassInsideBaseClass={} enumValueOfStrongEnum={}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1427</span><span class="doxyLineContent"><span class="doxyHighlight">        memberAccessibleFromScope, nestedClassInsideBaseClass, enumValueOfStrongEnum);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1428</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> distanceToBase=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1429</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nestedClassInsideBaseClass)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1430</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1431</span><span class="doxyLineContent"><span class="doxyHighlight">      result++; </span><span class="doxyHighlightComment">// penalty for base class to prevent</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1432</span><span class="doxyLineContent"><span class="doxyHighlight">                </span><span class="doxyHighlightComment">// this is preferred over nested class in this class</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1433</span><span class="doxyLineContent"><span class="doxyHighlight">                </span><span class="doxyHighlightComment">// see bug 686956</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1434</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1435</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (memberAccessibleFromScope &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1436</span><span class="doxyLineContent"><span class="doxyHighlight">             itemScope &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1437</span><span class="doxyLineContent"><span class="doxyHighlight">             itemScope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1438</span><span class="doxyLineContent"><span class="doxyHighlight">             scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1439</span><span class="doxyLineContent"><span class="doxyHighlight">             (distanceToBase=<a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>(scope)-&gt;isBaseClass(<a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>(itemScope),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>))&gt;0</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1440</span><span class="doxyLineContent"><span class="doxyHighlight">            )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1441</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1442</span><span class="doxyLineContent"><span class="doxyHighlight">      result+=distanceToBase; </span><span class="doxyHighlightComment">// penalty if member is accessible via a base class</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1443</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1444</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1445</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (scope==<a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1446</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1447</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (itemScope &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1448</span><span class="doxyLineContent"><span class="doxyHighlight">        itemScope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea35a2dfa1d3ce6c023cbddb4af2cd18bc">Definition::TypeNamespace</a> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1449</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ae303e4de18684cb3d0c72d936cc0654f">toNamespaceDef</a>(itemScope)-&gt;isAnonymous() &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1450</span><span class="doxyLineContent"><span class="doxyHighlight">        itemScope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>()==<a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1451</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightComment">// item is in an anonymous namespace in the global scope and we are</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1452</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// looking in the global scope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1453</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"found in anonymous namespace"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1454</span><span class="doxyLineContent"><span class="doxyHighlight">      result++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1455</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> done;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1456</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1457</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1458</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1459</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a41e981742ff67fe146064ae772af3f72">accessibleViaUsingDefinition</a>(visitedKeys,<a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>-&gt;getUsedDefinitions(),item))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1460</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1461</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"found via used class"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1462</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> done;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1463</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1464</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a03559acac4e6e0def9c8804b0fcd7beb">VisitedNamespaceKeys</a> visitedNamespaceKeys;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1465</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a46a2ef2308f1ef7d03889cea544d4909">accessibleViaUsingNamespace</a>(visitedKeys,visitedNamespaceKeys,<a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>-&gt;getUsedNamespaces(),item))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1466</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1467</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"found via used namespace"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1468</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> done;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1469</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1470</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1471</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"reached global scope"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1472</span><span class="doxyLineContent"><span class="doxyHighlight">    result=-1; </span><span class="doxyHighlightComment">// not found in path to globalScope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1473</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1474</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// keep searching</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1475</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1476</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// check if scope is a namespace, which is using other classes and namespaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1477</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea35a2dfa1d3ce6c023cbddb4af2cd18bc">Definition::TypeNamespace</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1478</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1479</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *nscope = <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ae303e4de18684cb3d0c72d936cc0654f">toNamespaceDef</a>(scope);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1480</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a41e981742ff67fe146064ae772af3f72">accessibleViaUsingDefinition</a>(visitedKeys,nscope-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#ae894d3e60b106c127ed42266ec7d6e83">getUsedDefinitions</a>(),item))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1481</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1482</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"found via used class"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1483</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> done;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1484</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1485</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a03559acac4e6e0def9c8804b0fcd7beb">VisitedNamespaceKeys</a> visitedNamespaceKeys;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1486</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a46a2ef2308f1ef7d03889cea544d4909">accessibleViaUsingNamespace</a>(visitedKeys,visitedNamespaceKeys,nscope-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#a742c3ca27e3383a1495dd972aaf6b43b">getUsedNamespaces</a>(),item,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1487</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1488</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"found via used namespace"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1489</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> done;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1490</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1491</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1492</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea203462c7d34ced15beac624562c2708e">Definition::TypeFile</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1493</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1494</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *nfile = <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a4114c484f3ccea1048608b9caa9f51de">toFileDef</a>(scope);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1495</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a41e981742ff67fe146064ae772af3f72">accessibleViaUsingDefinition</a>(visitedKeys,nfile-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a7304fd5a027f3efb4972abb52ecb4490">getUsedDefinitions</a>(),item))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1496</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1497</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"found via used class"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1498</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> done;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1499</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1500</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a03559acac4e6e0def9c8804b0fcd7beb">VisitedNamespaceKeys</a> visitedNamespaceKeys;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1501</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a46a2ef2308f1ef7d03889cea544d4909">accessibleViaUsingNamespace</a>(visitedKeys,visitedNamespaceKeys,nfile-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a7034a3e83b3708fef2741870ada63406">getUsedNamespaces</a>(),item,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1502</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1503</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"found via used namespace"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1504</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> done;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1505</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1506</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1507</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// repeat for the parent scope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1508</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *parentScope = scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1509</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (parentScope==<a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1510</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1511</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1512</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1513</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd = <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>(scope)-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#aed4a0864e51e5a3ac616f6c8e10f56c6">getFileDef</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1514</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1515</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1516</span><span class="doxyLineContent"><span class="doxyHighlight">          parentScope = fd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1517</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1518</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1519</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1520</span><span class="doxyLineContent"><span class="doxyHighlight">    i=<a href="/web-doxygen/docs/api/classes/symbolresolver/#a2d50ab34b5f003b3ee4c1283a414eca0">isAccessibleFrom</a>(visitedKeys,accessStack,parentScope,item);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1521</span><span class="doxyLineContent"><span class="doxyHighlight">    result= (i==-1) ? -1 : i+2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1522</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1523</span><span class="doxyLineContent"><span class="doxyHighlight">done:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1524</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1525</span><span class="doxyLineContent"><span class="doxyHighlight">  accessStack.<a href="/web-doxygen/docs/api/classes/accessstack/#a3cd93006259acc5edf0cad527c3935bb">pop</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1526</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1527</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a41e981742ff67fe146064ae772af3f72">accessibleViaUsingDefinition</a>, <a href="#a46a2ef2308f1ef7d03889cea544d4909">accessibleViaUsingNamespace</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">Definition::definitionType</a>, <a href="/web-doxygen/docs/api/classes/accessstack/#a9d144e56b75159f1bba48c299fb0a1ee">AccessStack::find</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#af99e46c3a8716075dfcb6debf428e44f">MemberDef::getEnumScope</a>, <a href="/web-doxygen/docs/api/classes/classdef/#aed4a0864e51e5a3ac616f6c8e10f56c6">ClassDef::getFileDef</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a5036fd8ee16b186925236105029ee823">MemberDef::getFileDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">Definition::getOuterScope</a>, <a href="/web-doxygen/docs/api/classes/filedef/#a7304fd5a027f3efb4972abb52ecb4490">FileDef::getUsedDefinitions</a>, <a href="/web-doxygen/docs/api/classes/namespacedef/#ae894d3e60b106c127ed42266ec7d6e83">NamespaceDef::getUsedDefinitions</a>, <a href="/web-doxygen/docs/api/classes/filedef/#a7034a3e83b3708fef2741870ada63406">FileDef::getUsedNamespaces</a>, <a href="/web-doxygen/docs/api/classes/namespacedef/#a742c3ca27e3383a1495dd972aaf6b43b">NamespaceDef::getUsedNamespaces</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a>, <a href="/web-doxygen/docs/api/classes/symbolresolver/#a2d50ab34b5f003b3ee4c1283a414eca0">SymbolResolver::isAccessibleFrom</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#ab99e728441f3ce7d5784ad6fb6df18f2">MemberDef::isEnumerate</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a5b99e725308ea15248722f69611844aa">MemberDef::isStrongEnumValue</a>, <a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/classes/accessstack/#a3cd93006259acc5edf0cad527c3935bb">AccessStack::pop</a>, <a href="/web-doxygen/docs/api/classes/accessstack/#aa6044b906f049112dc68aff47e91d4a7">AccessStack::push</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">QCString::startsWith</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>, <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a4114c484f3ccea1048608b9caa9f51de">toFileDef</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>, <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ae303e4de18684cb3d0c72d936cc0654f">toNamespaceDef</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea203462c7d34ced15beac624562c2708e">Definition::TypeFile</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea422b8b811bcf8869a67732f9829d005b">Definition::TypeMember</a> and <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea35a2dfa1d3ce6c023cbddb4af2cd18bc">Definition::TypeNamespace</a>.</p>

</div>
</div>

### isAccessibleFromWithExpScope() {#a01a031ffd0a93eb06668c1e93fb57f69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int SymbolResolver::Private::isAccessibleFromWithExpScope (<a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a62fc03f5f79aa6176eb0cb02cb054ac9">VisitedKeys</a> &amp; visitedKeys, <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a589f084c907127f8eb7da515347f2bc4">VisitedNamespaces</a> &amp; visitedNamespaces, <a href="/web-doxygen/docs/api/classes/accessstack">AccessStack</a> &amp; accessStack, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * scope, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * item, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; explicitScopePart)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a01a031ffd0a93eb06668c1e93fb57f69">1038</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a01a031ffd0a93eb06668c1e93fb57f69">SymbolResolver::Private::isAccessibleFromWithExpScope</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1039</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a62fc03f5f79aa6176eb0cb02cb054ac9">VisitedKeys</a> &amp;visitedKeys,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1040</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a589f084c907127f8eb7da515347f2bc4">VisitedNamespaces</a> &amp;visitedNamespaces,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1041</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="/web-doxygen/docs/api/classes/accessstack">AccessStack</a>       &amp;accessStack,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1042</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *scope,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1043</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *item,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1044</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;explicitScopePart)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1045</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1046</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> result=0; </span><span class="doxyHighlightComment">// assume we found it</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1047</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"scope={} item={} explictScopePart={}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1048</span><span class="doxyLineContent"><span class="doxyHighlight">      scope?scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), item?item-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), explicitScopePart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1049</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (explicitScopePart.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1050</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1051</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// handle degenerate case where there is no explicit scope.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1052</span><span class="doxyLineContent"><span class="doxyHighlight">    result = <a href="/web-doxygen/docs/api/classes/symbolresolver/#a2d50ab34b5f003b3ee4c1283a414eca0">isAccessibleFrom</a>(visitedKeys,accessStack,scope,item);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1053</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1054</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1055</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1056</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1057</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (accessStack.<a href="/web-doxygen/docs/api/classes/accessstack/#a9d144e56b75159f1bba48c299fb0a1ee">find</a>(scope,<a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>,item,explicitScopePart))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1058</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1059</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"already found"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1060</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1061</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1062</span><span class="doxyLineContent"><span class="doxyHighlight">  accessStack.<a href="/web-doxygen/docs/api/classes/accessstack/#aa6044b906f049112dc68aff47e91d4a7">push</a>(scope,<a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>,item,explicitScopePart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1063</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1064</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *newScope = <a href="#aab0947e93a77169efff48326518717ab">followPath</a>(visitedKeys,scope,explicitScopePart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1065</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (newScope)  </span><span class="doxyHighlightComment">// explicitScope is inside scope =&gt; newScope is the result</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1066</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1067</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *itemScope = item-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1068</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1069</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"scope traversal successful newScope={}"</span><span class="doxyHighlight">,newScope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1070</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1071</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> nestedClassInsideBaseClass =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1072</span><span class="doxyLineContent"><span class="doxyHighlight">         itemScope &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1073</span><span class="doxyLineContent"><span class="doxyHighlight">         itemScope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1074</span><span class="doxyLineContent"><span class="doxyHighlight">         newScope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1075</span><span class="doxyLineContent"><span class="doxyHighlight">         (<a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>(newScope))-&gt;isBaseClass(<a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>(itemScope),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1076</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1077</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> enumValueWithinEnum =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1078</span><span class="doxyLineContent"><span class="doxyHighlight">         item-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea422b8b811bcf8869a67732f9829d005b">Definition::TypeMember</a> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1079</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>(item)-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#afa1ed0ba61a371a22b21dbd4d538e06c">isEnumValue</a>() &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1080</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>(item)-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#af99e46c3a8716075dfcb6debf428e44f">getEnumScope</a>()==newScope;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1081</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1082</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (itemScope==newScope)  </span><span class="doxyHighlightComment">// exact match of scopes =&gt; distance==0</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1083</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1084</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"found scope match"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1085</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1086</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nestedClassInsideBaseClass)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1087</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1088</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// inheritance is also ok. Example: looking for B::I, where</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1089</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// class A { public: class I {} };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1090</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// class B : public A {}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1091</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// but looking for B::I, where</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1092</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// class A { public: class I {} };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1093</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// class B { public: class I {} };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1094</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// will find A::I, so we still prefer a direct match and give this one a distance of 1</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1095</span><span class="doxyLineContent"><span class="doxyHighlight">      result=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1096</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1097</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"{} is a bass class of {}"</span><span class="doxyHighlight">,scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(),newScope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1098</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1099</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (enumValueWithinEnum)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1100</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1101</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"found enum value inside enum"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1102</span><span class="doxyLineContent"><span class="doxyHighlight">      result=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1103</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1104</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1105</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1106</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1107</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (newScope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea35a2dfa1d3ce6c023cbddb4af2cd18bc">Definition::TypeNamespace</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1108</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1109</span><span class="doxyLineContent"><span class="doxyHighlight">        visitedNamespaces.emplace(newScope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),newScope);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1110</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// this part deals with the case where item is a class</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1111</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// A::B::C but is explicit referenced as A::C, where B is imported</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1112</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// in A via a using directive.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1113</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("newScope is a namespace: %s!\n",qPrint(newScope-&gt;name()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1114</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *nscope = <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ae303e4de18684cb3d0c72d936cc0654f">toNamespaceDef</a>(newScope);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1115</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ud : nscope-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#ae894d3e60b106c127ed42266ec7d6e83">getUsedDefinitions</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1116</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1117</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ud==item)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1118</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1119</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"found in used definition {}"</span><span class="doxyHighlight">,ud-&gt;name());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1120</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> done;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1121</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1122</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1123</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;nd : nscope-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#a742c3ca27e3383a1495dd972aaf6b43b">getUsedNamespaces</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1124</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1125</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (visitedNamespaces.find(nd-&gt;name().str())==visitedNamespaces.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1126</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1127</span><span class="doxyLineContent"><span class="doxyHighlight">            i = <a href="/web-doxygen/docs/api/classes/symbolresolver/#a63c2a4c6c16e4b5f9f527ab147c0ea2e">isAccessibleFromWithExpScope</a>(visitedKeys,visitedNamespaces,accessStack,scope,item,nd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1128</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1129</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1130</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"found in used namespace {}"</span><span class="doxyHighlight">,nd-&gt;name());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1131</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> done;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1132</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1133</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1134</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1135</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1136</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#if 0  </span><span class="doxyHighlightComment">// this caused problems resolving A::f() in the docs when there was a A::f(int) but also a</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1137</span><span class="doxyLineContent"><span class="doxyHighlight">       </span><span class="doxyHighlightComment">// global function f() that exactly matched the argument list.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1138</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isParentScope(scope,newScope) &amp;&amp; newScope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1139</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1140</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// if we a look for a type B and have explicit scope A, then it is also fine if B</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1141</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// is found at the global scope.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1142</span><span class="doxyLineContent"><span class="doxyHighlight">        result = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1143</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> done;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1144</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1145</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1146</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// repeat for the parent scope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1147</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (scope!=<a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1148</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1149</span><span class="doxyLineContent"><span class="doxyHighlight">        i = <a href="/web-doxygen/docs/api/classes/symbolresolver/#a63c2a4c6c16e4b5f9f527ab147c0ea2e">isAccessibleFromWithExpScope</a>(visitedKeys,visitedNamespaces,accessStack,scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>(),item,explicitScopePart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1150</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1151</span><span class="doxyLineContent"><span class="doxyHighlight">      result = (i==-1) ? -1 : i+2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1152</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1153</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1154</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// failed to resolve explicitScope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1155</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1156</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"failed to resolve explicitScope"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1157</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea35a2dfa1d3ce6c023cbddb4af2cd18bc">Definition::TypeNamespace</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1158</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1159</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *nscope = <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ae303e4de18684cb3d0c72d936cc0654f">toNamespaceDef</a>(scope);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1160</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a03559acac4e6e0def9c8804b0fcd7beb">VisitedNamespaceKeys</a> locVisitedNamespaceKeys;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1161</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a46a2ef2308f1ef7d03889cea544d4909">accessibleViaUsingNamespace</a>(visitedKeys,locVisitedNamespaceKeys,nscope-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#a742c3ca27e3383a1495dd972aaf6b43b">getUsedNamespaces</a>(),item,explicitScopePart))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1162</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1163</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"found in used class"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1164</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> done;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1165</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1166</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1167</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (scope==<a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1168</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1169</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1170</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1171</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a03559acac4e6e0def9c8804b0fcd7beb">VisitedNamespaceKeys</a> locVisitedNamespaceKeys;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1172</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a46a2ef2308f1ef7d03889cea544d4909">accessibleViaUsingNamespace</a>(visitedKeys,locVisitedNamespaceKeys,<a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>-&gt;getUsedNamespaces(),item,explicitScopePart))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1173</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1174</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"found in used namespace"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1175</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> done;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1176</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1177</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1178</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"not found in this scope"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1179</span><span class="doxyLineContent"><span class="doxyHighlight">      result=-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1180</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1181</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// continue by looking into the parent scope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1182</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1183</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=<a href="/web-doxygen/docs/api/classes/symbolresolver/#a63c2a4c6c16e4b5f9f527ab147c0ea2e">isAccessibleFromWithExpScope</a>(visitedKeys,visitedNamespaces,accessStack,scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>(),item,explicitScopePart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1184</span><span class="doxyLineContent"><span class="doxyHighlight">      result= (i==-1) ? -1 : i+2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1185</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1186</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1187</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1188</span><span class="doxyLineContent"><span class="doxyHighlight">done:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1189</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1190</span><span class="doxyLineContent"><span class="doxyHighlight">  accessStack.<a href="/web-doxygen/docs/api/classes/accessstack/#a3cd93006259acc5edf0cad527c3935bb">pop</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1191</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1192</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a46a2ef2308f1ef7d03889cea544d4909">accessibleViaUsingNamespace</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">Definition::definitionType</a>, <a href="/web-doxygen/docs/api/classes/accessstack/#a9d144e56b75159f1bba48c299fb0a1ee">AccessStack::find</a>, <a href="#aab0947e93a77169efff48326518717ab">followPath</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#af99e46c3a8716075dfcb6debf428e44f">MemberDef::getEnumScope</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">Definition::getOuterScope</a>, <a href="/web-doxygen/docs/api/classes/namespacedef/#ae894d3e60b106c127ed42266ec7d6e83">NamespaceDef::getUsedDefinitions</a>, <a href="/web-doxygen/docs/api/classes/namespacedef/#a742c3ca27e3383a1495dd972aaf6b43b">NamespaceDef::getUsedNamespaces</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a>, <a href="/web-doxygen/docs/api/classes/symbolresolver/#a2d50ab34b5f003b3ee4c1283a414eca0">SymbolResolver::isAccessibleFrom</a>, <a href="/web-doxygen/docs/api/classes/symbolresolver/#a63c2a4c6c16e4b5f9f527ab147c0ea2e">SymbolResolver::isAccessibleFromWithExpScope</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#afa1ed0ba61a371a22b21dbd4d538e06c">MemberDef::isEnumValue</a>, <a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/classes/accessstack/#a3cd93006259acc5edf0cad527c3935bb">AccessStack::pop</a>, <a href="/web-doxygen/docs/api/classes/accessstack/#aa6044b906f049112dc68aff47e91d4a7">AccessStack::push</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>, <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ae303e4de18684cb3d0c72d936cc0654f">toNamespaceDef</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea422b8b811bcf8869a67732f9829d005b">Definition::TypeMember</a> and <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea35a2dfa1d3ce6c023cbddb4af2cd18bc">Definition::TypeNamespace</a>.</p>

</div>
</div>

### reset() {#ab01c8bb71a27205b862142b2c049f9a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SymbolResolver::Private::reset ()</td>
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



<p>Definition at line 116 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab01c8bb71a27205b862142b2c049f9a6">116</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab01c8bb71a27205b862142b2c049f9a6">reset</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ae906eac3154529faa0b02dabaa1b54b1">m_resolvedTypedefs</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad7af4e916211ea5af0a6d86560c7216e">resolvedType</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a12df5d8fbcd835e0484e12a02eca4ceb">typeDef</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ac446c39cc6dcbdda4dd7532c0e8e695d">templateSpec</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#ae906eac3154529faa0b02dabaa1b54b1">m_resolvedTypedefs</a>, <a href="#ad7af4e916211ea5af0a6d86560c7216e">resolvedType</a>, <a href="#ac446c39cc6dcbdda4dd7532c0e8e695d">templateSpec</a> and <a href="#a12df5d8fbcd835e0484e12a02eca4ceb">typeDef</a>.</p>

</div>
</div>

### setFileScope() {#aa553c3d55ea82c85ce0f8a65861f32f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SymbolResolver::Private::setFileScope (const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fileScope)</td>
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



<p>Definition at line 123 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa553c3d55ea82c85ce0f8a65861f32f7">123</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa553c3d55ea82c85ce0f8a65861f32f7">setFileScope</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fileScope)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a> = fileScope;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### accessibleViaUsingDefinition() {#a41e981742ff67fe146064ae772af3f72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SymbolResolver::Private::accessibleViaUsingDefinition (<a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a62fc03f5f79aa6176eb0cb02cb054ac9">VisitedKeys</a> &amp; visitedKeys, const <a href="/web-doxygen/docs/api/classes/linkedrefmap">LinkedRefMap</a>&lt; const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> &gt; &amp; dl, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * item, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; explicitScopePart="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 215 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a41e981742ff67fe146064ae772af3f72">1341</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a41e981742ff67fe146064ae772af3f72">SymbolResolver::Private::accessibleViaUsingDefinition</a>(<a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a62fc03f5f79aa6176eb0cb02cb054ac9">VisitedKeys</a> &amp;visitedKeys,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1342</span><span class="doxyLineContent"><span class="doxyHighlight">                                                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/linkedrefmap">LinkedRefMap&lt;const Definition&gt;</a> &amp;dl,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1343</span><span class="doxyLineContent"><span class="doxyHighlight">                                                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *item,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1344</span><span class="doxyLineContent"><span class="doxyHighlight">                                                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;explicitScopePart)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1345</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1346</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"item={} explicitScopePart={}"</span><span class="doxyHighlight">,item?item-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), explicitScopePart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1347</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ud : dl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1348</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1349</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"trying via used definition '{}'"</span><span class="doxyHighlight">,ud-&gt;name());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1350</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *sc = explicitScopePart.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() ? ud : <a href="#aab0947e93a77169efff48326518717ab">followPath</a>(visitedKeys,ud,explicitScopePart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1351</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sc &amp;&amp; sc==item)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1352</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1353</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"true"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1354</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1355</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1356</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1357</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"false"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1358</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1359</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="#aab0947e93a77169efff48326518717ab">followPath</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>.</p>


<p>Referenced by <a href="#a60ffd0b23680e5318865a367b0d26871">isAccessibleFrom</a>.</p>

</div>
</div>

### accessibleViaUsingNamespace() {#a46a2ef2308f1ef7d03889cea544d4909}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SymbolResolver::Private::accessibleViaUsingNamespace (<a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a62fc03f5f79aa6176eb0cb02cb054ac9">VisitedKeys</a> &amp; visitedKeys, <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a03559acac4e6e0def9c8804b0fcd7beb">VisitedNamespaceKeys</a> &amp; visitedNamespaces, const <a href="/web-doxygen/docs/api/classes/linkedrefmap">LinkedRefMap</a>&lt; <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> &gt; &amp; nl, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * item, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; explicitScopePart="", int level=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 209 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a46a2ef2308f1ef7d03889cea544d4909">1303</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a46a2ef2308f1ef7d03889cea544d4909">SymbolResolver::Private::accessibleViaUsingNamespace</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1304</span><span class="doxyLineContent"><span class="doxyHighlight">                                 <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a62fc03f5f79aa6176eb0cb02cb054ac9">VisitedKeys</a> &amp;visitedKeys,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1305</span><span class="doxyLineContent"><span class="doxyHighlight">                                 <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a03559acac4e6e0def9c8804b0fcd7beb">VisitedNamespaceKeys</a> &amp;visitedNamespaces,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1306</span><span class="doxyLineContent"><span class="doxyHighlight">                                 </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/linkedrefmap">LinkedRefMap&lt;NamespaceDef&gt;</a> &amp;nl,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1307</span><span class="doxyLineContent"><span class="doxyHighlight">                                 </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *item,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1308</span><span class="doxyLineContent"><span class="doxyHighlight">                                 </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;explicitScopePart,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1309</span><span class="doxyLineContent"><span class="doxyHighlight">                                 </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1310</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1311</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"item={} explicitScopePart={} level={}"</span><span class="doxyHighlight">,item?item-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), explicitScopePart, level);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1312</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;und : nl) </span><span class="doxyHighlightComment">// check used namespaces for the class</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1313</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1314</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"trying via used namespace '{}'"</span><span class="doxyHighlight">,und-&gt;name());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1315</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *sc = explicitScopePart.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() ? und : <a href="#aab0947e93a77169efff48326518717ab">followPath</a>(visitedKeys,und,explicitScopePart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1316</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sc &amp;&amp; item-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>()==sc)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1317</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1318</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"true"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1319</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1320</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1321</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (item-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">getLanguage</a>()==SrcLangExt::Cpp)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1322</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1323</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> key=und-&gt;qualifiedName();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1324</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!und-&gt;getUsedNamespaces().empty() &amp;&amp; std::find(visitedNamespaces.begin(),visitedNamespaces.end(),key.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>())==std::end(visitedNamespaces))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1325</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1326</span><span class="doxyLineContent"><span class="doxyHighlight">        visitedNamespaces.push_back(key.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1327</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a46a2ef2308f1ef7d03889cea544d4909">accessibleViaUsingNamespace</a>(visitedKeys,visitedNamespaces,und-&gt;getUsedNamespaces(),item,explicitScopePart,level+1))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1328</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1329</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"true"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1330</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1331</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1332</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1333</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1334</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1335</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1336</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"false"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1337</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1338</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a46a2ef2308f1ef7d03889cea544d4909">accessibleViaUsingNamespace</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="#aab0947e93a77169efff48326518717ab">followPath</a>, <a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">Definition::getLanguage</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">Definition::getOuterScope</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>


<p>Referenced by <a href="#a46a2ef2308f1ef7d03889cea544d4909">accessibleViaUsingNamespace</a>, <a href="#a60ffd0b23680e5318865a367b0d26871">isAccessibleFrom</a> and <a href="#a01a031ffd0a93eb06668c1e93fb57f69">isAccessibleFromWithExpScope</a>.</p>

</div>
</div>

### endOfPathIsUsedClass() {#a6ba942e1e7634e03d9ecb279ea62f2b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Definition * SymbolResolver::Private::endOfPathIsUsedClass (const <a href="/web-doxygen/docs/api/classes/linkedrefmap">LinkedRefMap</a>&lt; const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> &gt; &amp; dl, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; localName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 207 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6ba942e1e7634e03d9ecb279ea62f2b3">1291</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *<a href="#a6ba942e1e7634e03d9ecb279ea62f2b3">SymbolResolver::Private::endOfPathIsUsedClass</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/linkedrefmap">LinkedRefMap&lt;const Definition&gt;</a> &amp;dl,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;localName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1292</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1293</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;d : dl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1294</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1295</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d-&gt;localName()==localName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1296</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1297</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> d;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1298</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1299</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1300</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1301</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="#aab0947e93a77169efff48326518717ab">followPath</a>.</p>

</div>
</div>

### followPath() {#aab0947e93a77169efff48326518717ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Definition * SymbolResolver::Private::followPath (<a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a62fc03f5f79aa6176eb0cb02cb054ac9">VisitedKeys</a> &amp; visitedKeys, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * start, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 204 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aab0947e93a77169efff48326518717ab">1194</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *<a href="#aab0947e93a77169efff48326518717ab">SymbolResolver::Private::followPath</a>(<a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a62fc03f5f79aa6176eb0cb02cb054ac9">VisitedKeys</a> &amp;visitedKeys,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1195</span><span class="doxyLineContent"><span class="doxyHighlight">                                                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *start,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;path)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1196</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1197</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"start={},path={}"</span><span class="doxyHighlight">,start?start-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), path);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1198</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> is=0,ps=0,l=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1199</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1200</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *current=start;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1201</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// for each part of the explicit scope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1202</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((is=<a href="/web-doxygen/docs/api/files/src/util-cpp/#afd249e264b966d05a54b740e3d43ad6e">getScopeFragment</a>(path,ps,&amp;l))!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1203</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1204</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// try to resolve the part if it is a typedef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1205</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *memTypeDef=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1206</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> qualScopePart = <a href="#a763d03603a7b427c9f02719fb95b2c30">substTypedef</a>(visitedKeys,current,path.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(is,l),&amp;memTypeDef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1207</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"qualScopePart={}"</span><span class="doxyHighlight">,qualScopePart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1208</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (memTypeDef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1209</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1210</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *type = <a href="#a551a021a6f4d4732e5181f8041375066">newResolveTypedef</a>(visitedKeys,<a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>,memTypeDef,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1211</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (type)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1212</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1213</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"type={}"</span><span class="doxyHighlight">,type-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1214</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> type;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1215</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1216</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1217</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *next = current-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a99240810ee50ab17c2cb21b56651cf09">findInnerCompound</a>(qualScopePart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1218</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"Looking for {} inside {} result={}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1219</span><span class="doxyLineContent"><span class="doxyHighlight">        qualScopePart, current-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(), next?next-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1220</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (next==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1221</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1222</span><span class="doxyLineContent"><span class="doxyHighlight">      next = current-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a99240810ee50ab17c2cb21b56651cf09">findInnerCompound</a>(qualScopePart+</span><span class="doxyHighlightStringLiteral">"-p"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1223</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1224</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (current-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1225</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1226</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *classMember = <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>(current)-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a3bec35936216530bf2385a8dfd2ab0e5">getMemberByName</a>(qualScopePart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1227</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (classMember &amp;&amp; classMember-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ab99e728441f3ce7d5784ad6fb6df18f2">isEnumerate</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1228</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1229</span><span class="doxyLineContent"><span class="doxyHighlight">        next = classMember;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1230</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1231</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1232</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (current!=<a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a> &amp;&amp; current-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea35a2dfa1d3ce6c023cbddb4af2cd18bc">Definition::TypeNamespace</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1233</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1234</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *namespaceMember = <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ae303e4de18684cb3d0c72d936cc0654f">toNamespaceDef</a>(current)-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#abfeac05d3bebefde162e271a1d9e6b24">getMemberByName</a>(qualScopePart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1235</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (namespaceMember &amp;&amp; namespaceMember-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ab99e728441f3ce7d5784ad6fb6df18f2">isEnumerate</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1236</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1237</span><span class="doxyLineContent"><span class="doxyHighlight">        next = namespaceMember;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1238</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1239</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1240</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (current==<a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a> || current-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea203462c7d34ced15beac624562c2708e">Definition::TypeFile</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1241</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1242</span><span class="doxyLineContent"><span class="doxyHighlight">       </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;range = <a href="/web-doxygen/docs/api/classes/doxygen/#adcf907e4baf6aafe25d9a812c2f58e14">Doxygen::symbolMap</a>-&gt;find(qualScopePart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1243</span><span class="doxyLineContent"><span class="doxyHighlight">       </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *def : range)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1244</span><span class="doxyLineContent"><span class="doxyHighlight">       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1245</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *outerScope = def-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1246</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1247</span><span class="doxyLineContent"><span class="doxyHighlight">             (outerScope==<a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a> || </span><span class="doxyHighlightComment">// global scope or</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1248</span><span class="doxyLineContent"><span class="doxyHighlight">              (outerScope &amp;&amp; </span><span class="doxyHighlightComment">// anonymous namespace in the global scope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1249</span><span class="doxyLineContent"><span class="doxyHighlight">               outerScope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">startsWith</a>(</span><span class="doxyHighlightStringLiteral">"anonymous_namespace{"</span><span class="doxyHighlight">) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1250</span><span class="doxyLineContent"><span class="doxyHighlight">               outerScope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>()==<a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1251</span><span class="doxyLineContent"><span class="doxyHighlight">              )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1252</span><span class="doxyLineContent"><span class="doxyHighlight">             ) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1253</span><span class="doxyLineContent"><span class="doxyHighlight">             (def-&gt;definitionType()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1254</span><span class="doxyLineContent"><span class="doxyHighlight">              def-&gt;definitionType()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea422b8b811bcf8869a67732f9829d005b">Definition::TypeMember</a> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1255</span><span class="doxyLineContent"><span class="doxyHighlight">              def-&gt;definitionType()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea35a2dfa1d3ce6c023cbddb4af2cd18bc">Definition::TypeNamespace</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1256</span><span class="doxyLineContent"><span class="doxyHighlight">             )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1257</span><span class="doxyLineContent"><span class="doxyHighlight">            )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1258</span><span class="doxyLineContent"><span class="doxyHighlight">         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1259</span><span class="doxyLineContent"><span class="doxyHighlight">           next=def;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1260</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1261</span><span class="doxyLineContent"><span class="doxyHighlight">         }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1262</span><span class="doxyLineContent"><span class="doxyHighlight">       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1263</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1264</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (next==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// failed to follow the path</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1265</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1266</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (current-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea35a2dfa1d3ce6c023cbddb4af2cd18bc">Definition::TypeNamespace</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1267</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1268</span><span class="doxyLineContent"><span class="doxyHighlight">        next = <a href="#a6ba942e1e7634e03d9ecb279ea62f2b3">endOfPathIsUsedClass</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1269</span><span class="doxyLineContent"><span class="doxyHighlight">            (<a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ae303e4de18684cb3d0c72d936cc0654f">toNamespaceDef</a>(current))-&gt;getUsedDefinitions(),qualScopePart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1270</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1271</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (current-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea203462c7d34ced15beac624562c2708e">Definition::TypeFile</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1272</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1273</span><span class="doxyLineContent"><span class="doxyHighlight">        next = <a href="#a6ba942e1e7634e03d9ecb279ea62f2b3">endOfPathIsUsedClass</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1274</span><span class="doxyLineContent"><span class="doxyHighlight">            (<a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a4114c484f3ccea1048608b9caa9f51de">toFileDef</a>(current))-&gt;getUsedDefinitions(),qualScopePart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1275</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1276</span><span class="doxyLineContent"><span class="doxyHighlight">      current = next;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1277</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (current==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1278</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1279</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// continue to follow scope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1280</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1281</span><span class="doxyLineContent"><span class="doxyHighlight">      current = next;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1282</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"current={}"</span><span class="doxyHighlight">,current-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1283</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1284</span><span class="doxyLineContent"><span class="doxyHighlight">    ps=is+l;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1285</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1286</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1287</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,current?current-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1288</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> current; </span><span class="doxyHighlightComment">// path could be followed</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1289</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">Definition::definitionType</a>, <a href="#a6ba942e1e7634e03d9ecb279ea62f2b3">endOfPathIsUsedClass</a>, <a href="/web-doxygen/docs/api/classes/definition/#a99240810ee50ab17c2cb21b56651cf09">Definition::findInnerCompound</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a3bec35936216530bf2385a8dfd2ab0e5">ClassDef::getMemberByName</a>, <a href="/web-doxygen/docs/api/classes/namespacedef/#abfeac05d3bebefde162e271a1d9e6b24">NamespaceDef::getMemberByName</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">Definition::getOuterScope</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#afd249e264b966d05a54b740e3d43ad6e">getScopeFragment</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#ab99e728441f3ce7d5784ad6fb6df18f2">MemberDef::isEnumerate</a>, <a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="#a551a021a6f4d4732e5181f8041375066">newResolveTypedef</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">QCString::startsWith</a>, <a href="#a763d03603a7b427c9f02719fb95b2c30">substTypedef</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#adcf907e4baf6aafe25d9a812c2f58e14">Doxygen::symbolMap</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>, <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a4114c484f3ccea1048608b9caa9f51de">toFileDef</a>, <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ae303e4de18684cb3d0c72d936cc0654f">toNamespaceDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea203462c7d34ced15beac624562c2708e">Definition::TypeFile</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea422b8b811bcf8869a67732f9829d005b">Definition::TypeMember</a> and <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea35a2dfa1d3ce6c023cbddb4af2cd18bc">Definition::TypeNamespace</a>.</p>


<p>Referenced by <a href="#a41e981742ff67fe146064ae772af3f72">accessibleViaUsingDefinition</a>, <a href="#a46a2ef2308f1ef7d03889cea544d4909">accessibleViaUsingNamespace</a> and <a href="#a01a031ffd0a93eb06668c1e93fb57f69">isAccessibleFromWithExpScope</a>.</p>

</div>
</div>

### getResolvedSymbol() {#a40f0f9c9cb6b6b7392ae6e695fc74671}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SymbolResolver::Private::getResolvedSymbol (<a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a62fc03f5f79aa6176eb0cb02cb054ac9">VisitedKeys</a> &amp; visitedKeys, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * scope, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; args, bool checkCV, bool insideCode, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; explicitScopePart, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; strippedTemplateParams, bool forceCallable, int &amp; minDistance, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *&amp; bestMatch, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *&amp; bestTypedef, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; bestTemplSpec, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; bestResolvedType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a40f0f9c9cb6b6b7392ae6e695fc74671">754</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a40f0f9c9cb6b6b7392ae6e695fc74671">SymbolResolver::Private::getResolvedSymbol</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">755</span><span class="doxyLineContent"><span class="doxyHighlight">                         <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a62fc03f5f79aa6176eb0cb02cb054ac9">VisitedKeys</a> &amp;visitedKeys,                            </span><span class="doxyHighlightComment">// in</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">756</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *scope,                             </span><span class="doxyHighlightComment">// in</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">757</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d,                                 </span><span class="doxyHighlightComment">// in</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">758</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;args,                                </span><span class="doxyHighlightComment">// in</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">759</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">  checkCV,                                       </span><span class="doxyHighlightComment">// in</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">760</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">  insideCode,                                    </span><span class="doxyHighlightComment">// in</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">761</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;explicitScopePart,                   </span><span class="doxyHighlightComment">// in</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">762</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;strippedTemplateParams,              </span><span class="doxyHighlightComment">// in</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">763</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> forceCallable,                                  </span><span class="doxyHighlightComment">// in</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">764</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> &amp;minDistance,                                    </span><span class="doxyHighlightComment">// inout</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">765</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *&amp;bestMatch,                        </span><span class="doxyHighlightComment">// out</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">766</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *&amp;bestTypedef,                       </span><span class="doxyHighlightComment">// out</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">767</span><span class="doxyLineContent"><span class="doxyHighlight">                         <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;bestTemplSpec,                             </span><span class="doxyHighlightComment">// out</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">768</span><span class="doxyLineContent"><span class="doxyHighlight">                         <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;bestResolvedType                           </span><span class="doxyHighlightComment">// out</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">769</span><span class="doxyLineContent"><span class="doxyHighlight">                      )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">770</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">771</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"scope={} sym={}"</span><span class="doxyHighlight">,scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(),d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">qualifiedName</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">772</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// only look at classes and members that are enums or typedefs</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">773</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a589f084c907127f8eb7da515347f2bc4">VisitedNamespaces</a> visitedNamespaces;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">774</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/accessstack">AccessStack</a> accessStack;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">775</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// test accessibility of definition within scope.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">776</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> distance = <a href="/web-doxygen/docs/api/classes/symbolresolver/#a63c2a4c6c16e4b5f9f527ab147c0ea2e">isAccessibleFromWithExpScope</a>(visitedKeys,visitedNamespaces,accessStack,scope,d,explicitScopePart+strippedTemplateParams);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">777</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (distance==-1 &amp;&amp; !strippedTemplateParams.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">778</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">779</span><span class="doxyLineContent"><span class="doxyHighlight">    distance = <a href="/web-doxygen/docs/api/classes/symbolresolver/#a63c2a4c6c16e4b5f9f527ab147c0ea2e">isAccessibleFromWithExpScope</a>(visitedKeys,visitedNamespaces,accessStack,scope,d,explicitScopePart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">780</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">781</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"distance={}"</span><span class="doxyHighlight">,distance);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">782</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (distance!=-1) </span><span class="doxyHighlightComment">// definition is accessible</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">783</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">784</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// see if we are dealing with a class or a typedef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">785</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (args.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; !forceCallable &amp;&amp; d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a>) </span><span class="doxyHighlightComment">// d is a class</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">786</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">787</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd = <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">788</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a9eabb427f58a6631c73f76c6856694a7">isTemplateArgument</a>()) </span><span class="doxyHighlightComment">// skip classes that</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">789</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// are only there to</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">790</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// represent a template</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">791</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// argument</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">792</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">793</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (distance&lt;minDistance) </span><span class="doxyHighlightComment">// found a definition that is "closer"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">794</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">795</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"found symbol={} at distance={} minDistance={}"</span><span class="doxyHighlight">,d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(),distance,minDistance);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">796</span><span class="doxyLineContent"><span class="doxyHighlight">          minDistance=distance;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">797</span><span class="doxyLineContent"><span class="doxyHighlight">          bestMatch = d;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">798</span><span class="doxyLineContent"><span class="doxyHighlight">          bestTypedef = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">799</span><span class="doxyLineContent"><span class="doxyHighlight">          bestTemplSpec.<a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">clear</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">800</span><span class="doxyLineContent"><span class="doxyHighlight">          bestResolvedType = cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">qualifiedName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">801</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">802</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (distance==minDistance &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">803</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a> &amp;&amp; bestMatch &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">804</span><span class="doxyLineContent"><span class="doxyHighlight">            !<a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>-&gt;getUsedNamespaces().empty() &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">805</span><span class="doxyLineContent"><span class="doxyHighlight">            d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>()-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea35a2dfa1d3ce6c023cbddb4af2cd18bc">Definition::TypeNamespace</a> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">806</span><span class="doxyLineContent"><span class="doxyHighlight">            bestMatch-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>()==<a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">807</span><span class="doxyLineContent"><span class="doxyHighlight">            )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">808</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">809</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// in case the distance is equal it could be that a class X</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">810</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// is defined in a namespace and in the global scope. When searched</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">811</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// in the global scope the distance is 0 in both cases. We have</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">812</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// to choose one of the definitions: we choose the one in the</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">813</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// namespace if the fileScope imports namespaces and the definition</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">814</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// found was in a namespace while the best match so far isn't.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">815</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// Just a non-perfect heuristic but it could help in some situations</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">816</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// (kdecore code is an example).</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">817</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"found symbol={} at distance={} minDistance={}"</span><span class="doxyHighlight">,d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(),distance,minDistance);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">818</span><span class="doxyLineContent"><span class="doxyHighlight">          minDistance=distance;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">819</span><span class="doxyLineContent"><span class="doxyHighlight">          bestMatch = d;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">820</span><span class="doxyLineContent"><span class="doxyHighlight">          bestTypedef = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">821</span><span class="doxyLineContent"><span class="doxyHighlight">          bestTemplSpec.<a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">clear</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">822</span><span class="doxyLineContent"><span class="doxyHighlight">          bestResolvedType = cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">qualifiedName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">823</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">824</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">825</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">826</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">827</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"class with template arguments"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">828</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">829</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">830</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea422b8b811bcf8869a67732f9829d005b">Definition::TypeMember</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">831</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">832</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md = <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">833</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">834</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> match = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">835</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"member={} args={} isCallable()={}"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(),<a href="/web-doxygen/docs/api/files/src/util-cpp/#a9d5c2a3aefbda0b0e684f768a380d2db">argListToString</a>(md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">argumentList</a>()),md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#af589ca13a0dec56fb92038c9b2488208">isCallable</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">836</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#af589ca13a0dec56fb92038c9b2488208">isCallable</a>() &amp;&amp; !args.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">837</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">838</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> actArgs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">839</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac74ba7e23ad9695f7ac03add58038243">isArtificial</a>() &amp;&amp; md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#aaaddfdfb06c2122a283d4afc01bd78a8">formalTemplateArguments</a>()) </span><span class="doxyHighlightComment">// for members of an instantiated template we need to replace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">840</span><span class="doxyLineContent"><span class="doxyHighlight">                                                                 </span><span class="doxyHighlightComment">// the formal arguments by the actual ones before matching</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">841</span><span class="doxyLineContent"><span class="doxyHighlight">                                                                 </span><span class="doxyHighlightComment">// See issue #10640</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">842</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">843</span><span class="doxyLineContent"><span class="doxyHighlight">          actArgs = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a8974bb194ed8b33e8f81653c8aacf6">substituteTemplateArgumentsInString</a>(args,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#aaaddfdfb06c2122a283d4afc01bd78a8">formalTemplateArguments</a>().value(),&amp;md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">argumentList</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">844</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">845</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">846</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">847</span><span class="doxyLineContent"><span class="doxyHighlight">          actArgs = args;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">848</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">849</span><span class="doxyLineContent"><span class="doxyHighlight">        std::unique_ptr&lt;ArgumentList&gt; argList = <a href="/web-doxygen/docs/api/files/src/defargs-h/#a88825bfb79a9c15e54ff57415b4de54d">stringToArgumentList</a>(md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">getLanguage</a>(),actArgs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">850</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;mdAl = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">argumentList</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">851</span><span class="doxyLineContent"><span class="doxyHighlight">        match = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a78739b1ab728bbecd4d3e54ae90bbbce">matchArguments2</a>(md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>(),md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5036fd8ee16b186925236105029ee823">getFileDef</a>(),&amp;mdAl,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">852</span><span class="doxyLineContent"><span class="doxyHighlight">              scope, md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5036fd8ee16b186925236105029ee823">getFileDef</a>(),argList.get(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">853</span><span class="doxyLineContent"><span class="doxyHighlight">              checkCV,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">getLanguage</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">854</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"match={}"</span><span class="doxyHighlight">,match);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">855</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">856</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">857</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (match &amp;&amp; distance&lt;minDistance)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">858</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">859</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"found symbol={} at distance={} minDistance={}"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(),distance,minDistance);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">860</span><span class="doxyLineContent"><span class="doxyHighlight">        minDistance=distance;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">861</span><span class="doxyLineContent"><span class="doxyHighlight">        bestMatch = md;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">862</span><span class="doxyLineContent"><span class="doxyHighlight">        bestTypedef = md;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">863</span><span class="doxyLineContent"><span class="doxyHighlight">        bestTemplSpec = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">864</span><span class="doxyLineContent"><span class="doxyHighlight">        bestResolvedType = md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">qualifiedName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">865</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">866</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">867</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea35a2dfa1d3ce6c023cbddb4af2cd18bc">Definition::TypeNamespace</a> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">868</span><span class="doxyLineContent"><span class="doxyHighlight">              d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea203462c7d34ced15beac624562c2708e">Definition::TypeFile</a> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">869</span><span class="doxyLineContent"><span class="doxyHighlight">              d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea3a91bc6cdee1a47194d4e8be5ff00156">Definition::TypeModule</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">870</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">871</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (distance&lt;minDistance) </span><span class="doxyHighlightComment">// found a definition that is "closer"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">872</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">873</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"found symbol={} at distance={} minDistance={}"</span><span class="doxyHighlight">,d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(),distance,minDistance);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">874</span><span class="doxyLineContent"><span class="doxyHighlight">        minDistance=distance;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">875</span><span class="doxyLineContent"><span class="doxyHighlight">        bestMatch = d;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">876</span><span class="doxyLineContent"><span class="doxyHighlight">        bestTypedef = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">877</span><span class="doxyLineContent"><span class="doxyHighlight">        bestTemplSpec.<a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">clear</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">878</span><span class="doxyLineContent"><span class="doxyHighlight">        bestResolvedType.<a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">clear</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">879</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">880</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">881</span><span class="doxyLineContent"><span class="doxyHighlight">  } </span><span class="doxyHighlightComment">// if definition accessible</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">882</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">883</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">884</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"not accessible"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">885</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">886</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"bestMatch sym={} distance={}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">887</span><span class="doxyLineContent"><span class="doxyHighlight">      bestMatch?bestMatch-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"&lt;none&gt;"</span><span class="doxyHighlight">),bestResolvedType);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">888</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9d5c2a3aefbda0b0e684f768a380d2db">argListToString</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">MemberDef::argumentList</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">QCString::clear</a>, <a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">Definition::definitionType</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#aaaddfdfb06c2122a283d4afc01bd78a8">MemberDef::formalTemplateArguments</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a5036fd8ee16b186925236105029ee823">MemberDef::getFileDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">Definition::getLanguage</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">Definition::getOuterScope</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a>, <a href="/web-doxygen/docs/api/classes/symbolresolver/#a63c2a4c6c16e4b5f9f527ab147c0ea2e">SymbolResolver::isAccessibleFromWithExpScope</a>, <a href="/web-doxygen/docs/api/classes/definition/#ac74ba7e23ad9695f7ac03add58038243">Definition::isArtificial</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#af589ca13a0dec56fb92038c9b2488208">MemberDef::isCallable</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a9eabb427f58a6631c73f76c6856694a7">ClassDef::isTemplateArgument</a>, <a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a78739b1ab728bbecd4d3e54ae90bbbce">matchArguments2</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">Definition::qualifiedName</a>, <a href="/web-doxygen/docs/api/files/src/defargs-h/#a88825bfb79a9c15e54ff57415b4de54d">stringToArgumentList</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a8974bb194ed8b33e8f81653c8aacf6">substituteTemplateArgumentsInString</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea203462c7d34ced15beac624562c2708e">Definition::TypeFile</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea422b8b811bcf8869a67732f9829d005b">Definition::TypeMember</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea3a91bc6cdee1a47194d4e8be5ff00156">Definition::TypeModule</a> and <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea35a2dfa1d3ce6c023cbddb4af2cd18bc">Definition::TypeNamespace</a>.</p>


<p>Referenced by <a href="#a41fdc2a524c5339afd35c067a828459d">getResolvedSymbolRec</a>.</p>

</div>
</div>

### getResolvedType() {#aef9c4245c6f445e282a59005f1f6ca5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SymbolResolver::Private::getResolvedType (<a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a62fc03f5f79aa6176eb0cb02cb054ac9">VisitedKeys</a> &amp; visitedKeys, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * scope, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; explicitScopePart, const <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> * actTemplParams, int &amp; minDistance, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *&amp; bestMatch, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *&amp; bestTypedef, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; bestTemplSpec, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; bestResolvedType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aef9c4245c6f445e282a59005f1f6ca5a">589</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aef9c4245c6f445e282a59005f1f6ca5a">SymbolResolver::Private::getResolvedType</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">590</span><span class="doxyLineContent"><span class="doxyHighlight">                         <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a62fc03f5f79aa6176eb0cb02cb054ac9">VisitedKeys</a> &amp;visitedKeys,                            </span><span class="doxyHighlightComment">// in</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">591</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *scope,                             </span><span class="doxyHighlightComment">// in</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">592</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d,                                 </span><span class="doxyHighlightComment">// in</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">593</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;explicitScopePart,                   </span><span class="doxyHighlightComment">// in</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> *actTemplParams,                  </span><span class="doxyHighlightComment">// in</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> &amp;minDistance,                                    </span><span class="doxyHighlightComment">// inout</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *&amp;bestMatch,                          </span><span class="doxyHighlightComment">// out</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *&amp;bestTypedef,                       </span><span class="doxyHighlightComment">// out</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlight">                         <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;bestTemplSpec,                             </span><span class="doxyHighlightComment">// out</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span><span class="doxyLineContent"><span class="doxyHighlight">                         <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;bestResolvedType                           </span><span class="doxyHighlightComment">// out</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlight">                      )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">601</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">602</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"scope={} sym={} explicitScope={}"</span><span class="doxyHighlight">,scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(),d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">qualifiedName</a>(),explicitScopePart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">603</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// only look at classes and members that are enums or typedefs</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">604</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlight">      (d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea422b8b811bcf8869a67732f9829d005b">Definition::TypeMember</a> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">       ((<a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>(d))-&gt;isTypedef() ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">        (<a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>(d))-&gt;isEnumerate())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">      )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">     )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a589f084c907127f8eb7da515347f2bc4">VisitedNamespaces</a> visitedNamespaces;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/accessstack">AccessStack</a> accessStack;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">613</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// test accessibility of definition within scope.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">614</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> distance = <a href="/web-doxygen/docs/api/classes/symbolresolver/#a63c2a4c6c16e4b5f9f527ab147c0ea2e">isAccessibleFromWithExpScope</a>(visitedKeys,visitedNamespaces,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">615</span><span class="doxyLineContent"><span class="doxyHighlight">                                                accessStack,scope,d,explicitScopePart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">616</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"distance={}"</span><span class="doxyHighlight">,distance);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (distance!=-1) </span><span class="doxyHighlightComment">// definition is accessible</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">618</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">619</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// see if we are dealing with a class or a typedef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">620</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a>) </span><span class="doxyHighlightComment">// d is a class</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">621</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">622</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd = <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">623</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("cd=%s\n",qPrint(cd-&gt;name()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">624</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a9eabb427f58a6631c73f76c6856694a7">isTemplateArgument</a>()) </span><span class="doxyHighlightComment">// skip classes that</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">625</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// are only there to</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">626</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// represent a template</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">627</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// argument</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">628</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">629</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//printf("is not a templ arg\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">630</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (distance&lt;minDistance) </span><span class="doxyHighlightComment">// found a definition that is "closer"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">631</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">632</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"found symbol={} at distance={} minDistance={}"</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(),distance,minDistance);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">633</span><span class="doxyLineContent"><span class="doxyHighlight">            minDistance=distance;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">634</span><span class="doxyLineContent"><span class="doxyHighlight">            bestMatch = cd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">635</span><span class="doxyLineContent"><span class="doxyHighlight">            bestTypedef = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">636</span><span class="doxyLineContent"><span class="doxyHighlight">            bestTemplSpec.<a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">clear</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">637</span><span class="doxyLineContent"><span class="doxyHighlight">            bestResolvedType = cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">qualifiedName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">638</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">639</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (distance==minDistance &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">640</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a> &amp;&amp; bestMatch &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">641</span><span class="doxyLineContent"><span class="doxyHighlight">              !<a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>-&gt;getUsedNamespaces().empty() &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">642</span><span class="doxyLineContent"><span class="doxyHighlight">              d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>()-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea35a2dfa1d3ce6c023cbddb4af2cd18bc">Definition::TypeNamespace</a> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">643</span><span class="doxyLineContent"><span class="doxyHighlight">              bestMatch-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>()==<a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">644</span><span class="doxyLineContent"><span class="doxyHighlight">              )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">645</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">646</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// in case the distance is equal it could be that a class X</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">647</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// is defined in a namespace and in the global scope. When searched</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">648</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// in the global scope the distance is 0 in both cases. We have</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">649</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// to choose one of the definitions: we choose the one in the</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">650</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// namespace if the fileScope imports namespaces and the definition</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">651</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// found was in a namespace while the best match so far isn't.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">652</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// Just a non-perfect heuristic but it could help in some situations</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">653</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// (kdecore code is an example).</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">654</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"found symbol={} at distance={} minDistance={}"</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(),distance,minDistance);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">655</span><span class="doxyLineContent"><span class="doxyHighlight">            minDistance=distance;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">656</span><span class="doxyLineContent"><span class="doxyHighlight">            bestMatch = cd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">657</span><span class="doxyLineContent"><span class="doxyHighlight">            bestTypedef = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">658</span><span class="doxyLineContent"><span class="doxyHighlight">            bestTemplSpec.<a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">clear</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">659</span><span class="doxyLineContent"><span class="doxyHighlight">            bestResolvedType = cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">qualifiedName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">660</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">661</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">662</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">663</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">664</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//printf("  is a template argument!\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">665</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">666</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea422b8b811bcf8869a67732f9829d005b">Definition::TypeMember</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">668</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md = <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">670</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"member={} isTypeDef={}"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(),md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a4bd8f9b14007a57f53918a21258c284e">isTypedef</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">671</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a4bd8f9b14007a57f53918a21258c284e">isTypedef</a>()) </span><span class="doxyHighlightComment">// d is a typedef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">672</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">673</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> args=md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">argsString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">674</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (args.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightComment">// do not expand "typedef t a[4];"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">675</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">676</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// we found a symbol at this distance, but if it didn't</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">677</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// resolve to a class, we still have to make sure that</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">678</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// something at a greater distance does not match, since</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">679</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// that symbol is hidden by this one.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">680</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (distance&lt;minDistance)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">681</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">682</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> spec;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">683</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> type;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">684</span><span class="doxyLineContent"><span class="doxyHighlight">              minDistance=distance;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">685</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *enumType = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">686</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd = <a href="#a551a021a6f4d4732e5181f8041375066">newResolveTypedef</a>(visitedKeys,scope,md,&amp;enumType,&amp;spec,&amp;type,actTemplParams);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">687</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd)  </span><span class="doxyHighlightComment">// type resolves to a class</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">688</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">689</span><span class="doxyLineContent"><span class="doxyHighlight">                <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"found symbol={} at distance={} minDistance={}"</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(),distance,minDistance);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">690</span><span class="doxyLineContent"><span class="doxyHighlight">                bestMatch = cd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">691</span><span class="doxyLineContent"><span class="doxyHighlight">                bestTypedef = md;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">692</span><span class="doxyLineContent"><span class="doxyHighlight">                bestTemplSpec = spec;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">693</span><span class="doxyLineContent"><span class="doxyHighlight">                bestResolvedType = type;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">694</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (enumType) </span><span class="doxyHighlightComment">// type resolves to a member type</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">696</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">697</span><span class="doxyLineContent"><span class="doxyHighlight">                <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"found enum"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">698</span><span class="doxyLineContent"><span class="doxyHighlight">                bestMatch = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">699</span><span class="doxyLineContent"><span class="doxyHighlight">                bestTypedef = enumType;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">700</span><span class="doxyLineContent"><span class="doxyHighlight">                bestTemplSpec = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">701</span><span class="doxyLineContent"><span class="doxyHighlight">                bestResolvedType = enumType-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">qualifiedName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">702</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">703</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>()) </span><span class="doxyHighlightComment">// external reference</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">704</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">705</span><span class="doxyLineContent"><span class="doxyHighlight">                <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"found external reference"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">706</span><span class="doxyLineContent"><span class="doxyHighlight">                bestMatch = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">707</span><span class="doxyLineContent"><span class="doxyHighlight">                bestTypedef = md;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">708</span><span class="doxyLineContent"><span class="doxyHighlight">                bestTemplSpec = spec;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">709</span><span class="doxyLineContent"><span class="doxyHighlight">                bestResolvedType = type;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">710</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">711</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">712</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">713</span><span class="doxyLineContent"><span class="doxyHighlight">                <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"no match"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">714</span><span class="doxyLineContent"><span class="doxyHighlight">                bestMatch = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">715</span><span class="doxyLineContent"><span class="doxyHighlight">                bestTypedef = md;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">716</span><span class="doxyLineContent"><span class="doxyHighlight">                bestTemplSpec.<a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">clear</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">717</span><span class="doxyLineContent"><span class="doxyHighlight">                bestResolvedType.<a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">clear</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">718</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">719</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">720</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">721</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">722</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightComment">//printf("      not the best match %d min=%d\n",distance,minDistance);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">723</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">724</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">725</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">726</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">727</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"skipping complex typedef"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">728</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">729</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">730</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ab99e728441f3ce7d5784ad6fb6df18f2">isEnumerate</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">731</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">732</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (distance&lt;minDistance)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">733</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">734</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"found enum={} at distance={} minDistance={}"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(),distance,minDistance);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">735</span><span class="doxyLineContent"><span class="doxyHighlight">            minDistance=distance;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">736</span><span class="doxyLineContent"><span class="doxyHighlight">            bestMatch = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">737</span><span class="doxyLineContent"><span class="doxyHighlight">            bestTypedef = md;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">738</span><span class="doxyLineContent"><span class="doxyHighlight">            bestTemplSpec = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">739</span><span class="doxyLineContent"><span class="doxyHighlight">            bestResolvedType = md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">qualifiedName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">740</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">741</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">742</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">743</span><span class="doxyLineContent"><span class="doxyHighlight">    } </span><span class="doxyHighlightComment">// if definition accessible</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">744</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">745</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">746</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"not accessible"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">747</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">748</span><span class="doxyLineContent"><span class="doxyHighlight">  } </span><span class="doxyHighlightComment">// if definition is a class or member</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">749</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"bestMatch sym={} type={}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">750</span><span class="doxyLineContent"><span class="doxyHighlight">      bestMatch?bestMatch-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"&lt;none&gt;"</span><span class="doxyHighlight">),bestResolvedType);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">751</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">MemberDef::argsString</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">QCString::clear</a>, <a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">Definition::definitionType</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">Definition::getOuterScope</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a>, <a href="/web-doxygen/docs/api/classes/symbolresolver/#a63c2a4c6c16e4b5f9f527ab147c0ea2e">SymbolResolver::isAccessibleFromWithExpScope</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#ab99e728441f3ce7d5784ad6fb6df18f2">MemberDef::isEnumerate</a>, <a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">Definition::isReference</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a9eabb427f58a6631c73f76c6856694a7">ClassDef::isTemplateArgument</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a4bd8f9b14007a57f53918a21258c284e">MemberDef::isTypedef</a>, <a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="#a551a021a6f4d4732e5181f8041375066">newResolveTypedef</a>, <a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">Definition::qualifiedName</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea422b8b811bcf8869a67732f9829d005b">Definition::TypeMember</a> and <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea35a2dfa1d3ce6c023cbddb4af2cd18bc">Definition::TypeNamespace</a>.</p>

</div>
</div>

### newResolveTypedef() {#a551a021a6f4d4732e5181f8041375066}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ClassDef * SymbolResolver::Private::newResolveTypedef (<a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a62fc03f5f79aa6176eb0cb02cb054ac9">VisitedKeys</a> &amp; visitedKeys, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * scope, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> ** pMemType, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> * pTemplSpec, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> * pResolvedType, const <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> * actTemplParams=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 194 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a551a021a6f4d4732e5181f8041375066">891</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *<a href="#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">892</span><span class="doxyLineContent"><span class="doxyHighlight">                  <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a62fc03f5f79aa6176eb0cb02cb054ac9">VisitedKeys</a> &amp;visitedKeys,                            </span><span class="doxyHighlightComment">// in</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">893</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * </span><span class="doxyHighlightComment">/* scope */</span><span class="doxyHighlight">,                      </span><span class="doxyHighlightComment">// in</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">894</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md,                                 </span><span class="doxyHighlightComment">// in</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">895</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> **pMemType,                          </span><span class="doxyHighlightComment">// out</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">896</span><span class="doxyLineContent"><span class="doxyHighlight">                  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> *pTemplSpec,                                </span><span class="doxyHighlightComment">// out</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">897</span><span class="doxyLineContent"><span class="doxyHighlight">                  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> *pResolvedType,                             </span><span class="doxyHighlightComment">// out</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">898</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> *actTemplParams)                  </span><span class="doxyHighlightComment">// in</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">899</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">900</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"md={}"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">qualifiedName</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">901</span><span class="doxyLineContent"><span class="doxyHighlight">  std::lock_guard&lt;std::recursive_mutex&gt; lock(<a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a1a8971085fc5238a1829570b5ca71aab">g_cacheTypedefMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">902</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isCached = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a7f317162cd72dbfd6829ee85aec91170">isTypedefValCached</a>(); </span><span class="doxyHighlightComment">// value already cached</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">903</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isCached)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">904</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">905</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"cached typedef={} resolvedTypedef={} templSpec={}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">906</span><span class="doxyLineContent"><span class="doxyHighlight">        md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a2d86b14ef7e0bae448c4ab6cb0e0bedc">getCachedTypedefVal</a>() ? md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a2d86b14ef7e0bae448c4ab6cb0e0bedc">getCachedTypedefVal</a>()-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>() : <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">907</span><span class="doxyLineContent"><span class="doxyHighlight">        md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a101fb5ed20d2c97e877e0f7b8ef07740">getCachedResolvedTypedef</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">908</span><span class="doxyLineContent"><span class="doxyHighlight">        md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a799ea114bacbfab8f6b8eb4e63564484">getCachedTypedefTemplSpec</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">909</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">910</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pTemplSpec)    *pTemplSpec    = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a799ea114bacbfab8f6b8eb4e63564484">getCachedTypedefTemplSpec</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">911</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pResolvedType) *pResolvedType = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a101fb5ed20d2c97e877e0f7b8ef07740">getCachedResolvedTypedef</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">912</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a2d86b14ef7e0bae448c4ab6cb0e0bedc">getCachedTypedefVal</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">913</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">914</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">915</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> qname = md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">qualifiedName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">916</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae906eac3154529faa0b02dabaa1b54b1">m_resolvedTypedefs</a>.find(qname.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>())!=<a href="#ae906eac3154529faa0b02dabaa1b54b1">m_resolvedTypedefs</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">917</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">918</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"already being processed"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">919</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// typedef already done</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">920</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">921</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">922</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> typedef_it = <a href="#ae906eac3154529faa0b02dabaa1b54b1">m_resolvedTypedefs</a>.emplace(qname.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),md).first; </span><span class="doxyHighlightComment">// put on the trace list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">923</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">924</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *typeClass = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a33ff70edee6691aacaeecf40a1146995">getClassDef</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">925</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> type = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a0032c6e040cdec6d9c52dc75a790a884">typeString</a>(); </span><span class="doxyHighlightComment">// get the "value" of the typedef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">926</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (typeClass &amp;&amp; typeClass-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a30f19d5b8fb17b204b9e41d19b2ca49f">isTemplate</a>() &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">927</span><span class="doxyLineContent"><span class="doxyHighlight">      actTemplParams &amp;&amp; !actTemplParams-&gt;<a href="/web-doxygen/docs/api/classes/argumentlist/#aaa15ddcfdb06a535a3398f1dc73d336d">empty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">928</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">929</span><span class="doxyLineContent"><span class="doxyHighlight">    type = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a8974bb194ed8b33e8f81653c8aacf6">substituteTemplateArgumentsInString</a>(type,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">930</span><span class="doxyLineContent"><span class="doxyHighlight">            typeClass-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a201b8f24043f9b7c7cc59d55282f6d47">templateArguments</a>(),actTemplParams);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">931</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">932</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> typedefValue = type;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">933</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> tl=</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(type.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">934</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> ip=tl-1; </span><span class="doxyHighlightComment">// remove * and &amp; at the end</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">935</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (ip&gt;=0 &amp;&amp; (type.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(ip)==</span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight"> || type.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(ip)==</span><span class="doxyHighlightCharLiteral">'&amp;'</span><span class="doxyHighlight"> || type.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(ip)==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">936</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">937</span><span class="doxyLineContent"><span class="doxyHighlight">    ip--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">938</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">939</span><span class="doxyLineContent"><span class="doxyHighlight">  type=type.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(ip+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">940</span><span class="doxyLineContent"><span class="doxyHighlight">  type.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"const "</span><span class="doxyHighlight">);  </span><span class="doxyHighlightComment">// strip leading "const"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">941</span><span class="doxyLineContent"><span class="doxyHighlight">  type.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"volatile "</span><span class="doxyHighlight">);  </span><span class="doxyHighlightComment">// strip leading "volatile"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">942</span><span class="doxyLineContent"><span class="doxyHighlight">  type.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"struct "</span><span class="doxyHighlight">); </span><span class="doxyHighlightComment">// strip leading "struct"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">943</span><span class="doxyLineContent"><span class="doxyHighlight">  type.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"union "</span><span class="doxyHighlight">);  </span><span class="doxyHighlightComment">// strip leading "union"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">944</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> sp=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">945</span><span class="doxyLineContent"><span class="doxyHighlight">  tl=</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(type.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()); </span><span class="doxyHighlightComment">// length may have been changed</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">946</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (sp&lt;tl &amp;&amp; type.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(sp)==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) sp++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">947</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *memTypeDef = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">948</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *result = <a href="#a3aea62dc3d2f6c0e0109e5aefc155a41">getResolvedTypeRec</a>(visitedKeys,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>(),type,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">949</span><span class="doxyLineContent"><span class="doxyHighlight">                                                &amp;memTypeDef,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,pResolvedType);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">950</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// if type is a typedef then return what it resolves to.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">951</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (memTypeDef &amp;&amp; memTypeDef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a4bd8f9b14007a57f53918a21258c284e">isTypedef</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">952</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">953</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"resolving typedef"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">954</span><span class="doxyLineContent"><span class="doxyHighlight">    result=<a href="#a551a021a6f4d4732e5181f8041375066">newResolveTypedef</a>(visitedKeys,<a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>,memTypeDef,pMemType,pTemplSpec,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">955</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> done;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">956</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">957</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (memTypeDef &amp;&amp; memTypeDef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ab99e728441f3ce7d5784ad6fb6df18f2">isEnumerate</a>() &amp;&amp; pMemType)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">958</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">959</span><span class="doxyLineContent"><span class="doxyHighlight">    *pMemType = memTypeDef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">960</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">961</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">962</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (result==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">963</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">964</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// try unspecialized version if type is template</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">965</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> si=type.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">966</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=type.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">967</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (si==-1 &amp;&amp; i!=-1) </span><span class="doxyHighlightComment">// typedef of a template =&gt; try the unspecialized version</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">968</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">969</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pTemplSpec) *pTemplSpec = type.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">970</span><span class="doxyLineContent"><span class="doxyHighlight">      result = <a href="#a3aea62dc3d2f6c0e0109e5aefc155a41">getResolvedTypeRec</a>(visitedKeys,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>(),type.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(i),</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,pResolvedType);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">971</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">972</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (si!=-1) </span><span class="doxyHighlightComment">// A::B</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">973</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">974</span><span class="doxyLineContent"><span class="doxyHighlight">      i=type.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">,si);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">975</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i==-1) </span><span class="doxyHighlightComment">// Something like A&lt;T&gt;::B =&gt; lookup A::B</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">976</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">977</span><span class="doxyLineContent"><span class="doxyHighlight">        i=</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(type.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">978</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">979</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// Something like A&lt;T&gt;::B&lt;S&gt; =&gt; lookup A::B, spec=&lt;S&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">980</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">981</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pTemplSpec) *pTemplSpec = type.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">982</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">983</span><span class="doxyLineContent"><span class="doxyHighlight">      result = <a href="#a3aea62dc3d2f6c0e0109e5aefc155a41">getResolvedTypeRec</a>(visitedKeys,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">984</span><span class="doxyLineContent"><span class="doxyHighlight">           <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad87c70b117b898e5077a28ba5114c8c2">stripTemplateSpecifiersFromScope</a>(type.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(i),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,pResolvedType);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">985</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">986</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">987</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">988</span><span class="doxyLineContent"><span class="doxyHighlight">done:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">989</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pResolvedType)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">990</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">991</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (result &amp;&amp; result-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">992</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">993</span><span class="doxyLineContent"><span class="doxyHighlight">      *pResolvedType = result-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">qualifiedName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">994</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sp&gt;0)    pResolvedType-&gt;<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(typedefValue.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(sp));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">995</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ip&lt;tl-1) pResolvedType-&gt;<a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">append</a>(typedefValue.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(tl-ip-1));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">996</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">997</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">998</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">999</span><span class="doxyLineContent"><span class="doxyHighlight">      *pResolvedType = typedefValue;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1000</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1001</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1002</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1003</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// remember computed value for next time</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1004</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (result &amp;&amp; result-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>()!=</span><span class="doxyHighlightStringLiteral">"&lt;code&gt;"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1005</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// this check is needed to prevent that temporary classes that are</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1006</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// introduced while parsing code fragments are being cached here.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1007</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1008</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"caching typedef relation {}-&gt;{}"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(),result-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1009</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *mdm = <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>(</span><span class="doxyHighlightKeyword">const_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(md));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1010</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdm)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1011</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1012</span><span class="doxyLineContent"><span class="doxyHighlight">      mdm-&gt;<a href="/web-doxygen/docs/api/classes/memberdefmutable/#ab95b7104c9a40aa504f08b1577b18a6f">cacheTypedefVal</a>(result,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1013</span><span class="doxyLineContent"><span class="doxyHighlight">        pTemplSpec ? *pTemplSpec : <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1014</span><span class="doxyLineContent"><span class="doxyHighlight">        pResolvedType ? *pResolvedType : <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1015</span><span class="doxyLineContent"><span class="doxyHighlight">       );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1016</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1017</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1018</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1019</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ae906eac3154529faa0b02dabaa1b54b1">m_resolvedTypedefs</a>.erase(typedef_it); </span><span class="doxyHighlightComment">// remove from the trace list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1020</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1021</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={} pTemplSpec={} pResolvedType={}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1022</span><span class="doxyLineContent"><span class="doxyHighlight">      result        ? result-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>() : <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1023</span><span class="doxyLineContent"><span class="doxyHighlight">      pTemplSpec    ? *pTemplSpec    : </span><span class="doxyHighlightStringLiteral">"&lt;nullptr&gt;"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1024</span><span class="doxyLineContent"><span class="doxyHighlight">      pResolvedType ? *pResolvedType : </span><span class="doxyHighlightStringLiteral">"&lt;nullptr&gt;"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1025</span><span class="doxyLineContent"><span class="doxyHighlight">      );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1026</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1027</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">QCString::append</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#ab95b7104c9a40aa504f08b1577b18a6f">MemberDefMutable::cacheTypedefVal</a>, <a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">Definition::definitionType</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#aaa15ddcfdb06a535a3398f1dc73d336d">ArgumentList::empty</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a>, <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a1a8971085fc5238a1829570b5ca71aab">g_cacheTypedefMutex</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a101fb5ed20d2c97e877e0f7b8ef07740">MemberDef::getCachedResolvedTypedef</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a799ea114bacbfab8f6b8eb4e63564484">MemberDef::getCachedTypedefTemplSpec</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a2d86b14ef7e0bae448c4ab6cb0e0bedc">MemberDef::getCachedTypedefVal</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a33ff70edee6691aacaeecf40a1146995">MemberDef::getClassDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">Definition::getDefFileName</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">Definition::getOuterScope</a>, <a href="#a3aea62dc3d2f6c0e0109e5aefc155a41">getResolvedTypeRec</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#ab99e728441f3ce7d5784ad6fb6df18f2">MemberDef::isEnumerate</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a30f19d5b8fb17b204b9e41d19b2ca49f">ClassDef::isTemplate</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a4bd8f9b14007a57f53918a21258c284e">MemberDef::isTypedef</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a7f317162cd72dbfd6829ee85aec91170">MemberDef::isTypedefValCached</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>, <a href="#ae906eac3154529faa0b02dabaa1b54b1">m_resolvedTypedefs</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="#a551a021a6f4d4732e5181f8041375066">newResolveTypedef</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">QCString::prepend</a>, <a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">Definition::qualifiedName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">QCString::right</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">QCString::stripPrefix</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad87c70b117b898e5077a28ba5114c8c2">stripTemplateSpecifiersFromScope</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a8974bb194ed8b33e8f81653c8aacf6">substituteTemplateArgumentsInString</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a201b8f24043f9b7c7cc59d55282f6d47">ClassDef::templateArguments</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a> and <a href="/web-doxygen/docs/api/classes/memberdef/#a0032c6e040cdec6d9c52dc75a790a884">MemberDef::typeString</a>.</p>


<p>Referenced by <a href="#aab0947e93a77169efff48326518717ab">followPath</a>, <a href="#aef9c4245c6f445e282a59005f1f6ca5a">getResolvedType</a> and <a href="#a551a021a6f4d4732e5181f8041375066">newResolveTypedef</a>.</p>

</div>
</div>

### substTypedef() {#a763d03603a7b427c9f02719fb95b2c30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString SymbolResolver::Private::substTypedef (<a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a62fc03f5f79aa6176eb0cb02cb054ac9">VisitedKeys</a> &amp; visitedKeys, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * scope, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> ** pTypeDef=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a763d03603a7b427c9f02719fb95b2c30">1529</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a763d03603a7b427c9f02719fb95b2c30">SymbolResolver::Private::substTypedef</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1530</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a62fc03f5f79aa6176eb0cb02cb054ac9">VisitedKeys</a> &amp;visitedKeys,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1531</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *scope,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1532</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> **pTypeDef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1533</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1534</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"scope={} name={}"</span><span class="doxyHighlight">,scope?scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1535</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result=name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1536</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (name.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1537</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1538</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;range = <a href="/web-doxygen/docs/api/classes/doxygen/#adcf907e4baf6aafe25d9a812c2f58e14">Doxygen::symbolMap</a>-&gt;find(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1539</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (range.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1540</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result; </span><span class="doxyHighlightComment">// no matches</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1541</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1542</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *bestMatch=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1543</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> minDistance=10000; </span><span class="doxyHighlightComment">// init at "infinite"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1544</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1545</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string key;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1546</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> maxAddrSize = 20;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1547</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> ptr_str[maxAddrSize];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1548</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> num = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a307ffe8cbc4a4aa695900441d1df49f3">qsnprintf</a>(ptr_str,maxAddrSize,</span><span class="doxyHighlightStringLiteral">"%p:"</span><span class="doxyHighlight">,(</span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> *)scope);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1549</span><span class="doxyLineContent"><span class="doxyHighlight">  assert(num&gt;0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1550</span><span class="doxyLineContent"><span class="doxyHighlight">  key.reserve(num+name.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1551</span><span class="doxyLineContent"><span class="doxyHighlight">  key+=ptr_str;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1552</span><span class="doxyLineContent"><span class="doxyHighlight">  key+=name.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1553</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1554</span><span class="doxyLineContent"><span class="doxyHighlight">    std::lock_guard lock(<a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a6514a0d5a7c5cf86b13034f038a87a77">g_substMapMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1555</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#aafc36311877f21f5997fccbb4c2a78d9">g_substMap</a>.find(key);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1556</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#aafc36311877f21f5997fccbb4c2a78d9">g_substMap</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1557</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1558</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pTypeDef) *pTypeDef = it-&gt;second.second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1559</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> it-&gt;second.first;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1560</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1561</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1562</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1563</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d : range)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1564</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1565</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// only look at members</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1566</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d-&gt;definitionType()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea422b8b811bcf8869a67732f9829d005b">Definition::TypeMember</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1567</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1568</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// that are also typedefs</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1569</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md = <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1570</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a4bd8f9b14007a57f53918a21258c284e">isTypedef</a>()) </span><span class="doxyHighlightComment">// d is a typedef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1571</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1572</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a589f084c907127f8eb7da515347f2bc4">VisitedNamespaces</a> visitedNamespaces;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1573</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/accessstack">AccessStack</a> accessStack;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1574</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// test accessibility of typedef within scope.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1575</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> distance = <a href="/web-doxygen/docs/api/classes/symbolresolver/#a63c2a4c6c16e4b5f9f527ab147c0ea2e">isAccessibleFromWithExpScope</a>(visitedKeys,visitedNamespaces,accessStack,scope,d,</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1576</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (distance!=-1 &amp;&amp; distance&lt;minDistance)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1577</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// definition is accessible and a better match</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1578</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1579</span><span class="doxyLineContent"><span class="doxyHighlight">          minDistance=distance;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1580</span><span class="doxyLineContent"><span class="doxyHighlight">          bestMatch = md;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1581</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1582</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1583</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1584</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1585</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1586</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bestMatch)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1587</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1588</span><span class="doxyLineContent"><span class="doxyHighlight">    result = bestMatch-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a0032c6e040cdec6d9c52dc75a790a884">typeString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1589</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pTypeDef) *pTypeDef=bestMatch;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1590</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1591</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1592</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// cache the result of the computation to give a faster answers next time, especially relevant</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1593</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// if `range` has many arguments (i.e. there are many symbols with the same name in different contexts)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1594</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1595</span><span class="doxyLineContent"><span class="doxyHighlight">    std::lock_guard lock(<a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a6514a0d5a7c5cf86b13034f038a87a77">g_substMapMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1596</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#aafc36311877f21f5997fccbb4c2a78d9">g_substMap</a>.emplace(key,std::make_pair(result,bestMatch));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1597</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1598</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1599</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1600</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1601</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#aafc36311877f21f5997fccbb4c2a78d9">g_substMap</a>, <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a6514a0d5a7c5cf86b13034f038a87a77">g_substMapMutex</a>, <a href="/web-doxygen/docs/api/classes/symbolresolver/#a63c2a4c6c16e4b5f9f527ab147c0ea2e">SymbolResolver::isAccessibleFromWithExpScope</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a4bd8f9b14007a57f53918a21258c284e">MemberDef::isTypedef</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a307ffe8cbc4a4aa695900441d1df49f3">qsnprintf</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#adcf907e4baf6aafe25d9a812c2f58e14">Doxygen::symbolMap</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea422b8b811bcf8869a67732f9829d005b">Definition::TypeMember</a> and <a href="/web-doxygen/docs/api/classes/memberdef/#a0032c6e040cdec6d9c52dc75a790a884">MemberDef::typeString</a>.</p>


<p>Referenced by <a href="#aab0947e93a77169efff48326518717ab">followPath</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### resolvedType {#ad7af4e916211ea5af0a6d86560c7216e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString SymbolResolver::Private::resolvedType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad7af4e916211ea5af0a6d86560c7216e">128</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>          <a href="#ad7af4e916211ea5af0a6d86560c7216e">resolvedType</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ab01c8bb71a27205b862142b2c049f9a6">reset</a>.</p>

</div>
</div>

### templateSpec {#ac446c39cc6dcbdda4dd7532c0e8e695d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString SymbolResolver::Private::templateSpec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac446c39cc6dcbdda4dd7532c0e8e695d">130</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>          <a href="#ac446c39cc6dcbdda4dd7532c0e8e695d">templateSpec</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ab01c8bb71a27205b862142b2c049f9a6">reset</a>.</p>

</div>
</div>

### typeDef {#a12df5d8fbcd835e0484e12a02eca4ceb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MemberDef* SymbolResolver::Private::typeDef = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a12df5d8fbcd835e0484e12a02eca4ceb">129</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>  *<a href="#a12df5d8fbcd835e0484e12a02eca4ceb">typeDef</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#ab01c8bb71a27205b862142b2c049f9a6">reset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_fileScope {#a3980fdf8be8cde16e3e9ef5d6b5e8498}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FileDef* SymbolResolver::Private::m_fileScope</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 224 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">224</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a>    *<a href="#a3980fdf8be8cde16e3e9ef5d6b5e8498">m_fileScope</a>;</span></span></div>

</div>


<p>Referenced by <a href="#aab0947e93a77169efff48326518717ab">followPath</a>, <a href="#a40f0f9c9cb6b6b7392ae6e695fc74671">getResolvedSymbol</a>, <a href="#a41fdc2a524c5339afd35c067a828459d">getResolvedSymbolRec</a>, <a href="#aef9c4245c6f445e282a59005f1f6ca5a">getResolvedType</a>, <a href="#a3aea62dc3d2f6c0e0109e5aefc155a41">getResolvedTypeRec</a>, <a href="#a60ffd0b23680e5318865a367b0d26871">isAccessibleFrom</a>, <a href="#a01a031ffd0a93eb06668c1e93fb57f69">isAccessibleFromWithExpScope</a>, <a href="#a551a021a6f4d4732e5181f8041375066">newResolveTypedef</a>, <a href="#a67735bb927b53dcc800ef7bce7929cb5">Private</a> and <a href="#aa553c3d55ea82c85ce0f8a65861f32f7">setFileScope</a>.</p>

</div>
</div>

### m\_resolvedTypedefs {#ae906eac3154529faa0b02dabaa1b54b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;std::string,const MemberDef*&gt; SymbolResolver::Private::m_resolvedTypedefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 225 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae906eac3154529faa0b02dabaa1b54b1">225</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unordered_map&lt;std::string,const MemberDef*&gt; <a href="#ae906eac3154529faa0b02dabaa1b54b1">m_resolvedTypedefs</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a551a021a6f4d4732e5181f8041375066">newResolveTypedef</a> and <a href="#ab01c8bb71a27205b862142b2c049f9a6">reset</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
