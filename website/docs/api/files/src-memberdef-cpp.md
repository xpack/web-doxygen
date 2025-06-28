---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/memberdef-cpp
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `memberdef.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;stdio.h&gt;
#include &lt;assert.h&gt;
#include &lt;mutex&gt;
#include "md5.h"
#include "<a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/code-h">code.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/htmlhelp-h">htmlhelp.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/language-h">language.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/example-h">example.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/defargs-h">defargs.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/docparser-h">docparser.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dot-h">dot.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dotcallgraph-h">dotcallgraph.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/trace-h">trace.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/memberdefimpl">MemberDefImpl</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/memberdefaliasimpl">MemberDefAliasImpl</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc503b94aed5230ca07d22e743e9c800">createMemberDef</a> (const QCString &amp;defFileName, int defLine, int defColumn, const QCString &amp;type, const QCString &amp;name, const QCString &amp;args, const QCString &amp;excp, Protection prot, Specifier virt, bool stat, Relationship related, MemberType t, const ArgumentList &amp;tal, const ArgumentList &amp;al, const QCString &amp;metaData)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Factory method to create a new instance of a <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>. <a href="#afc503b94aed5230ca07d22e743e9c800">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a792961c33915b95213d78c7366c9dcb3">createMemberDefAlias</a> (const Definition *newScope, const MemberDef *aliasMd)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac66cc6a4e1d7c053d396a641dfe15d93">addTemplateNames</a> (const QCString &amp;s, const QCString &amp;n, const QCString &amp;t)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a> (OutputList &amp;ol, const Definition *scope, const MemberDef *md)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25431a65b263de7827454ea81eb8be29">writeExceptionListImpl</a> (OutputList &amp;ol, const ClassDef *cd, const MemberDef *md, QCString const &amp;exception)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a158781f51faf723e59ca681487e4da1a">writeExceptionList</a> (OutputList &amp;ol, const ClassDef *cd, const MemberDef *md)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a422d9b60fc7fc0a5e71595c715fa944e">combineArgsAndException</a> (QCString args, QCString exception)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fcfb1e72d24be27533f0a69fd651264">simplifyTypeForTable</a> (const QCString &amp;s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a301116112cb06af3d6fa71fdb8c9b940">stripTrailingReturn</a> (const QCString &amp;trailRet)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8001f4748644d24e0537d505ef8a84a3">invalidateCachedTypesInArgumentList</a> (ArgumentList &amp;al)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a916ded3150c496785b98bbd5c2bee442">transferArgumentDocumentation</a> (ArgumentList &amp;decAl, ArgumentList &amp;defAl)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaf3303e28a7a9e34bdcfbe4bfc893cb">combineDeclarationAndDefinition</a> (MemberDefMutable *mdec, MemberDefMutable *mdef)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91959a7c929a76adaaa2d342fea73126">addDocCrossReference</a> (const MemberDef *s, const MemberDef *d)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a> (Definition *d)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadf8d5c103d1bd6ff91c784f02ebe2dd">toMemberDef</a> (DefinitionMutable *md)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac062c9356229664b77d347ac8cc94d0">toMemberDef</a> (const Definition *d)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a> (Definition *d)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a961ae6d2d358b27f1898087008b186fa">g_cachedAnonymousTypeMutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62bb009cd0c5ff54af5146380fd18f05">g_hasDetailedDescriptionMutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static const <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaa6100850ded3f073682450f105d7eb">reAnonymous</a>(R"([\w:@]*@\d+)")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e711cc7ca7ab729f5b8e1d81d88cf53">g_detectUndocumentedParamsMutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ec17e0e1fa9fc5b2ab522f618f39b88">g_docCrossReferenceMutex</a></td>
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

## Functions

### addDocCrossReference() {#a91959a7c929a76adaaa2d342fea73126}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addDocCrossReference (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * s, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l06399">6399</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91959a7c929a76adaaa2d342fea73126">6399</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a91959a7c929a76adaaa2d342fea73126">addDocCrossReference</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *s,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6400</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6401</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *src = <a href="#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>(</span><span class="doxyHighlightKeyword">const_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(s));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6402</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *dst = <a href="#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>(</span><span class="doxyHighlightKeyword">const_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(d));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6403</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (src==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> || dst==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6404</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("--&gt; addDocCrossReference src=%s,dst=%s\n",qPrint(src-&gt;name()),qPrint(dst-&gt;name()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6405</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (dst-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a4bd8f9b14007a57f53918a21258c284e">isTypedef</a>() || dst-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ab99e728441f3ce7d5784ad6fb6df18f2">isEnumerate</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// don't add types</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6406</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((dst-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#abc1862f5e87a67541a4c40403a95fd81">hasReferencedByRelation</a>() || dst-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a9e0b1dcd40b111eea088027193c2e411">hasCallerGraph</a>()) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6407</span><span class="doxyLineContent"><span class="doxyHighlight">      src-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#af589ca13a0dec56fb92038c9b2488208">isCallable</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6408</span><span class="doxyLineContent"><span class="doxyHighlight">     )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6409</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6410</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> sourceRefName = src-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a64c6a04cf0c6d2ebf56ed6959ce1f89d">sourceRefName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6411</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *mdDef = <a href="#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>(dst-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a0b88c6841076c450863bc9b57e5068d1">memberDefinition</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6412</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *mdDecl = <a href="#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>(dst-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a160b1eb96684b652bd0611e78d8fe831">memberDeclaration</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6413</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6414</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// ---- critical section</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6415</span><span class="doxyLineContent"><span class="doxyHighlight">    std::lock_guard&lt;std::mutex&gt; lock(<a href="#a6ec17e0e1fa9fc5b2ab522f618f39b88">g_docCrossReferenceMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6416</span><span class="doxyLineContent"><span class="doxyHighlight">    dst-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#aec0335ad9b4dc58dea457a3229bbaacb">addSourceReferencedBy</a>(src,sourceRefName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6417</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdDef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6418</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6419</span><span class="doxyLineContent"><span class="doxyHighlight">      mdDef-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#aec0335ad9b4dc58dea457a3229bbaacb">addSourceReferencedBy</a>(src,sourceRefName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6420</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6421</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdDecl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6422</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6423</span><span class="doxyLineContent"><span class="doxyHighlight">      mdDecl-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#aec0335ad9b4dc58dea457a3229bbaacb">addSourceReferencedBy</a>(src,sourceRefName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6424</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6425</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// ---- end critical section</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6426</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6427</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((src-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a3aedaf487c755d4749b10fa95729a2af">hasReferencesRelation</a>() || src-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a4f8eeb9656c15d74956b893e5cef255d">hasCallGraph</a>()) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6428</span><span class="doxyLineContent"><span class="doxyHighlight">      src-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#af589ca13a0dec56fb92038c9b2488208">isCallable</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6429</span><span class="doxyLineContent"><span class="doxyHighlight">     )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6430</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6431</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> sourceRefName = dst-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a64c6a04cf0c6d2ebf56ed6959ce1f89d">sourceRefName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6432</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *mdDef = <a href="#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>(src-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a0b88c6841076c450863bc9b57e5068d1">memberDefinition</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6433</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *mdDecl = <a href="#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>(src-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a160b1eb96684b652bd0611e78d8fe831">memberDeclaration</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6434</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6435</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// ---- critical section</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6436</span><span class="doxyLineContent"><span class="doxyHighlight">    std::lock_guard&lt;std::mutex&gt; lock(<a href="#a6ec17e0e1fa9fc5b2ab522f618f39b88">g_docCrossReferenceMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6437</span><span class="doxyLineContent"><span class="doxyHighlight">    src-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#a6a9e0c7716f37652c8c0e0206032b76d">addSourceReferences</a>(dst,sourceRefName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6438</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdDef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6439</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6440</span><span class="doxyLineContent"><span class="doxyHighlight">      mdDef-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#a6a9e0c7716f37652c8c0e0206032b76d">addSourceReferences</a>(dst,sourceRefName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6441</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6442</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdDecl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6443</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6444</span><span class="doxyLineContent"><span class="doxyHighlight">      mdDecl-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#a6a9e0c7716f37652c8c0e0206032b76d">addSourceReferences</a>(dst,sourceRefName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6445</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6446</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// ---- end critical section</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6447</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6448</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/definitionmutable/#aec0335ad9b4dc58dea457a3229bbaacb">DefinitionMutable::addSourceReferencedBy</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#a6a9e0c7716f37652c8c0e0206032b76d">DefinitionMutable::addSourceReferences</a>, <a href="#a6ec17e0e1fa9fc5b2ab522f618f39b88">g&#95;docCrossReferenceMutex</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a9e0b1dcd40b111eea088027193c2e411">MemberDef::hasCallerGraph</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a4f8eeb9656c15d74956b893e5cef255d">MemberDef::hasCallGraph</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#abc1862f5e87a67541a4c40403a95fd81">MemberDef::hasReferencedByRelation</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a3aedaf487c755d4749b10fa95729a2af">MemberDef::hasReferencesRelation</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#af589ca13a0dec56fb92038c9b2488208">MemberDef::isCallable</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#ab99e728441f3ce7d5784ad6fb6df18f2">MemberDef::isEnumerate</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a4bd8f9b14007a57f53918a21258c284e">MemberDef::isTypedef</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a160b1eb96684b652bd0611e78d8fe831">MemberDef::memberDeclaration</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a0b88c6841076c450863bc9b57e5068d1">MemberDef::memberDefinition</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a64c6a04cf0c6d2ebf56ed6959ce1f89d">MemberDef::sourceRefName</a> and <a href="#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/pycode-l/#a767fe9c8dd14640cc99a6f1c9e0981c7">findMemberLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ada294ec0d3d5d40d4bb74d5624c886d4">generateClassMemberLink</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a080345cfde4ece732f42ded5413ea957">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a3345ad9e2ab3a9d1b524391ae5f6c545">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#ac240a5eb77b55528937ec68a24cf4f46">getLink</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#aa3a78394ea3d7dee51703f8f0c1e3984">getLinkInScope</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a7c3e45cceb9eb4446d360eb8620eef8c">getLinkInScope</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#addab8233ce94a53e33f788e02e453790">MemberDefMutable::setFromAnonymousScope</a> and <a href="/web-doxygen/docs/api/files/src/code-l/#af2995da196faa8940cca40cfc158b9aa">writeObjCMethodCall</a>.
</div>
</div>

### addTemplateNames() {#ac66cc6a4e1d7c053d396a641dfe15d93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString addTemplateNames (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; n, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; t)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00975">975</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac66cc6a4e1d7c053d396a641dfe15d93">975</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ac66cc6a4e1d7c053d396a641dfe15d93">addTemplateNames</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;n,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">976</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">977</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">978</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> clRealName=n;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">979</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> p=0,i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">980</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((i=clRealName.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">))!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">981</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">982</span><span class="doxyLineContent"><span class="doxyHighlight">    clRealName=clRealName.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(i); </span><span class="doxyHighlightComment">// strip template specialization</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">983</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">984</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((i=clRealName.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">))!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">985</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">986</span><span class="doxyLineContent"><span class="doxyHighlight">    clRealName=clRealName.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(clRealName.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-i-2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">987</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">988</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((i=s.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(clRealName,p))!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">989</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">990</span><span class="doxyLineContent"><span class="doxyHighlight">    result+=s.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(p,i-p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">991</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> j=clRealName.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()+i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">992</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()==j || (s.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(j)!=</span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight"> &amp;&amp; !<a href="/web-doxygen/docs/api/files/src/util-h/#ae320c88a8522836f00095d566529046f">isId</a>(s.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(j))))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">993</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightComment">// add template names</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">994</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("Adding %s+%s\n",qPrint(clRealName),qPrint(t));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">995</span><span class="doxyLineContent"><span class="doxyHighlight">      result+=clRealName+t;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">996</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">997</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">998</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightComment">// template names already present</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">999</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("Adding %s\n",qPrint(clRealName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1000</span><span class="doxyLineContent"><span class="doxyHighlight">      result+=clRealName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1001</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1002</span><span class="doxyLineContent"><span class="doxyHighlight">    p=i+</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(clRealName.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1003</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1004</span><span class="doxyLineContent"><span class="doxyHighlight">  result+=s.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(s.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1005</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("addTemplateNames(%s,%s,%s)=%s\n",qPrint(s),qPrint(n),qPrint(t),qPrint(result));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1006</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1007</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a>, <a href="/web-doxygen/docs/api/files/src/util-h/#ae320c88a8522836f00095d566529046f">isId</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">QCString::right</a>.

Referenced by <a href="#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>.
</div>
</div>

### combineArgsAndException() {#a422d9b60fc7fc0a5e71595c715fa944e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString combineArgsAndException (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> args, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> exception)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l02199">2199</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a422d9b60fc7fc0a5e71595c715fa944e">2199</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a422d9b60fc7fc0a5e71595c715fa944e">combineArgsAndException</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> args,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> exception)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2200</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2201</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (exception.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> args;                      </span><span class="doxyHighlightComment">// no exception, nothing to combine args</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2202</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> pos   = args.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2203</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> eqPos = pos!=-1 ? args.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'='</span><span class="doxyHighlight">,pos) : -1;             </span><span class="doxyHighlightComment">// look for '=' in '(args) = something'</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2204</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (eqPos==-1) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> args+</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">+exception;                  </span><span class="doxyHighlightComment">// append exception at the end</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2205</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> args.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(eqPos)+</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">+exception+</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">+args.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(eqPos); </span><span class="doxyHighlightComment">// insert exception before =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2206</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>.
</div>
</div>

### combineDeclarationAndDefinition() {#abaf3303e28a7a9e34bdcfbe4bfc893cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void combineDeclarationAndDefinition (<a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> * mdec, <a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> * mdef)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l06165">6165</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abaf3303e28a7a9e34bdcfbe4bfc893cb">6165</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abaf3303e28a7a9e34bdcfbe4bfc893cb">combineDeclarationAndDefinition</a>(<a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *mdec,<a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6166</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6167</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"mdec='{}' mdef='{}' mdec.isPrototype={} mdef.isPrototype={}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6168</span><span class="doxyLineContent"><span class="doxyHighlight">              mdec-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(), mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(), mdec-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#afa756b712f45e7800617808f708c2876">isPrototype</a>(), mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#afa756b712f45e7800617808f708c2876">isPrototype</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6169</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6170</span><span class="doxyLineContent"><span class="doxyHighlight">      (mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5e6ace25ee464a601e1b3f2b8016ddad">isFunction</a>() &amp;&amp; !mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a73354ecea5b876ab8d59724b080189b4">isStatic</a>() &amp;&amp; !mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#afa756b712f45e7800617808f708c2876">isPrototype</a>()) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6171</span><span class="doxyLineContent"><span class="doxyHighlight">      (mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ad7b6f788b487058e9e6ac65b092479b9">isVariable</a>() &amp;&amp; !mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a62a3294a87e2a6e2ff4a2d52bfd3187a">isExternal</a>() &amp;&amp; !mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a73354ecea5b876ab8d59724b080189b4">isStatic</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6172</span><span class="doxyLineContent"><span class="doxyHighlight">     )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6173</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6174</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> sameNumTemplateArgs = mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a409da33c248938e57ba2135777a38628">templateArguments</a>().<a href="/web-doxygen/docs/api/classes/argumentlist/#a4d651caeb995400fad17d4ab4a020a3a">size</a>()==mdec-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a409da33c248938e57ba2135777a38628">templateArguments</a>().<a href="/web-doxygen/docs/api/classes/argumentlist/#a4d651caeb995400fad17d4ab4a020a3a">size</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6175</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6176</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;mdefAl = </span><span class="doxyHighlightKeyword">const_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a>&amp;</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">argumentList</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6177</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;mdecAl = </span><span class="doxyHighlightKeyword">const_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a>&amp;</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(mdec-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">argumentList</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6178</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sameNumTemplateArgs &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6179</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/util-cpp/#a78739b1ab728bbecd4d3e54ae90bbbce">matchArguments2</a>(mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>(),mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5036fd8ee16b186925236105029ee823">getFileDef</a>(),&amp;mdefAl,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6180</span><span class="doxyLineContent"><span class="doxyHighlight">                        mdec-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>(),mdec-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5036fd8ee16b186925236105029ee823">getFileDef</a>(),&amp;mdecAl,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6181</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">getLanguage</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6182</span><span class="doxyLineContent"><span class="doxyHighlight">                       )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6183</span><span class="doxyLineContent"><span class="doxyHighlight">       ) </span><span class="doxyHighlightComment">/* match found */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6184</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6185</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"combining definition and declaration"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6186</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6187</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(RESOLVE_UNNAMED_PARAMS))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6188</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6189</span><span class="doxyLineContent"><span class="doxyHighlight">        mdec-&gt;<a href="/web-doxygen/docs/api/classes/memberdefmutable/#a3dc3cdf4626a0d405580d45a907f1719">resolveUnnamedParameters</a>(mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6190</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6191</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6192</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// first merge argument documentation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6193</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a916ded3150c496785b98bbd5c2bee442">transferArgumentDocumentation</a>(mdecAl,mdefAl);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6194</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6195</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">/* copy documentation between function definition and declaration */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6196</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!mdec-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6197</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6198</span><span class="doxyLineContent"><span class="doxyHighlight">        mdef-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#ae704468ccbae4cbc26922db573676feb">setBriefDescription</a>(mdec-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>(),mdec-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac74d77550941a8f568ea56fecc30c873">briefFile</a>(),mdec-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8073d399d39c43e66a4b487b3e06ade1">briefLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6199</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6200</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6201</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6202</span><span class="doxyLineContent"><span class="doxyHighlight">        mdec-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#ae704468ccbae4cbc26922db573676feb">setBriefDescription</a>(mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>(),mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac74d77550941a8f568ea56fecc30c873">briefFile</a>(),mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8073d399d39c43e66a4b487b3e06ade1">briefLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6203</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6204</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6205</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6206</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("transferring docs mdef-&gt;mdec (%s-&gt;%s)\n",mdef-&gt;argsString(),mdec-&gt;argsString());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6207</span><span class="doxyLineContent"><span class="doxyHighlight">        mdec-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#a5115744bf4595f9a08a193dd41d4f4c3">setDocumentation</a>(mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>(),mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a00915f52f3b708bec07aab2b44f03d34">docFile</a>(),mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a26a4a6e3578aa6c81b2d6d77a1ce694f">docLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6208</span><span class="doxyLineContent"><span class="doxyHighlight">        mdec-&gt;<a href="/web-doxygen/docs/api/classes/memberdefmutable/#a8b1c18e7f7a27c2661cac096a24e2602">setDocsForDefinition</a>(mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a842ff86c34c3ae387d995e2597be8118">isDocsForDefinition</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6209</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdefAl.<a href="/web-doxygen/docs/api/classes/argumentlist/#a2ed5c45b3909206446aaac4f1ab6d640">hasParameters</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6210</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6211</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> mdefAlComb = <a href="/web-doxygen/docs/api/files/src/defargs-h/#a88825bfb79a9c15e54ff57415b4de54d">stringToArgumentList</a>(mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">getLanguage</a>(),mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">argsString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6212</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a916ded3150c496785b98bbd5c2bee442">transferArgumentDocumentation</a>(mdefAl,*mdefAlComb);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6213</span><span class="doxyLineContent"><span class="doxyHighlight">          mdec-&gt;<a href="/web-doxygen/docs/api/classes/memberdefmutable/#ae6b8b985f4a543215a25b698a28f4dfc">moveArgumentList</a>(std::move(mdefAlComb));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6214</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6215</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6216</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!mdec-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6217</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6218</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("transferring docs mdec-&gt;mdef (%s-&gt;%s)\n",mdec-&gt;argsString(),mdef-&gt;argsString());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6219</span><span class="doxyLineContent"><span class="doxyHighlight">        mdef-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#a5115744bf4595f9a08a193dd41d4f4c3">setDocumentation</a>(mdec-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>(),mdec-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a00915f52f3b708bec07aab2b44f03d34">docFile</a>(),mdec-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a26a4a6e3578aa6c81b2d6d77a1ce694f">docLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6220</span><span class="doxyLineContent"><span class="doxyHighlight">        mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdefmutable/#a8b1c18e7f7a27c2661cac096a24e2602">setDocsForDefinition</a>(mdec-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a842ff86c34c3ae387d995e2597be8118">isDocsForDefinition</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6221</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdecAl.<a href="/web-doxygen/docs/api/classes/argumentlist/#a2ed5c45b3909206446aaac4f1ab6d640">hasParameters</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6222</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6223</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> mdecAlComb = <a href="/web-doxygen/docs/api/files/src/defargs-h/#a88825bfb79a9c15e54ff57415b4de54d">stringToArgumentList</a>(mdec-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">getLanguage</a>(),mdec-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">argsString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6224</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a916ded3150c496785b98bbd5c2bee442">transferArgumentDocumentation</a>(mdecAl,*mdecAlComb);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6225</span><span class="doxyLineContent"><span class="doxyHighlight">          mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdefmutable/#ac1b97bdbdbe63513549b7f1585187f65">moveDeclArgumentList</a>(std::move(mdecAlComb));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6226</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6227</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6228</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#af59473951772c62b9db328e342fc2198">inbodyDocumentation</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6229</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6230</span><span class="doxyLineContent"><span class="doxyHighlight">        mdec-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#a8a4d82f0315802612dcd9732369eaa8a">setInbodyDocumentation</a>(mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#af59473951772c62b9db328e342fc2198">inbodyDocumentation</a>(),mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#af6fd6ee64e4e2599c1cb7cba93897aa7">inbodyFile</a>(),mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a74cb27736839a0e602ef5fa9bbb9deab">inbodyLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6231</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6232</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!mdec-&gt;<a href="/web-doxygen/docs/api/classes/definition/#af59473951772c62b9db328e342fc2198">inbodyDocumentation</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6233</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6234</span><span class="doxyLineContent"><span class="doxyHighlight">        mdef-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#a8a4d82f0315802612dcd9732369eaa8a">setInbodyDocumentation</a>(mdec-&gt;<a href="/web-doxygen/docs/api/classes/definition/#af59473951772c62b9db328e342fc2198">inbodyDocumentation</a>(),mdec-&gt;<a href="/web-doxygen/docs/api/classes/definition/#af6fd6ee64e4e2599c1cb7cba93897aa7">inbodyFile</a>(),mdec-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a74cb27736839a0e602ef5fa9bbb9deab">inbodyLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6235</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6236</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdec-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ad63d39480ae9ec4e71bedbb749d16a4c">getStartBodyLine</a>()!=-1 &amp;&amp; mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ad63d39480ae9ec4e71bedbb749d16a4c">getStartBodyLine</a>()==-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6237</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6238</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("body mdec-&gt;mdef %d-%d\n",mdec-&gt;getStartBodyLine(),mdef-&gt;getEndBodyLine());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6239</span><span class="doxyLineContent"><span class="doxyHighlight">        mdef-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#a21f0601d0ac0f9d245c7a40e28adc3c6">setBodySegment</a>(mdec-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>(),mdec-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ad63d39480ae9ec4e71bedbb749d16a4c">getStartBodyLine</a>(),mdec-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0b5313ad11f50b2d056fc62d81db0433">getEndBodyLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6240</span><span class="doxyLineContent"><span class="doxyHighlight">        mdef-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#acebfd2c89008fa8ef42c9ab9bf61d4b7">setBodyDef</a>(mdec-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a7ea253be90981d4a6f0cfdb6dff1d2fd">getBodyDef</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6241</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//mdef-&gt;setBodyMember(mdec);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6242</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6243</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ad63d39480ae9ec4e71bedbb749d16a4c">getStartBodyLine</a>()!=-1 &amp;&amp; mdec-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ad63d39480ae9ec4e71bedbb749d16a4c">getStartBodyLine</a>()==-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6244</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6245</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("body mdef-&gt;mdec %d-%d\n",mdef-&gt;getStartBodyLine(),mdec-&gt;getEndBodyLine());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6246</span><span class="doxyLineContent"><span class="doxyHighlight">        mdec-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#a21f0601d0ac0f9d245c7a40e28adc3c6">setBodySegment</a>(mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>(),mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ad63d39480ae9ec4e71bedbb749d16a4c">getStartBodyLine</a>(),mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0b5313ad11f50b2d056fc62d81db0433">getEndBodyLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6247</span><span class="doxyLineContent"><span class="doxyHighlight">        mdec-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#acebfd2c89008fa8ef42c9ab9bf61d4b7">setBodyDef</a>(mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a7ea253be90981d4a6f0cfdb6dff1d2fd">getBodyDef</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6248</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//mdec-&gt;setBodyMember(mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6249</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6250</span><span class="doxyLineContent"><span class="doxyHighlight">      mdec-&gt;<a href="/web-doxygen/docs/api/classes/memberdefmutable/#ab0caddb69ae9c8c18e57ee452791f483">mergeMemberSpecifiers</a>(mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ab3e5d2e532ebe2a0f45fe1a945fb4269">getMemberSpecifiers</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6251</span><span class="doxyLineContent"><span class="doxyHighlight">      mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdefmutable/#ab0caddb69ae9c8c18e57ee452791f483">mergeMemberSpecifiers</a>(mdec-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ab3e5d2e532ebe2a0f45fe1a945fb4269">getMemberSpecifiers</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6252</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6253</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// copy group info.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6254</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdec-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a43566d882fc7994385bbdaf7fe927e67">getGroupDef</a>()==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> &amp;&amp; mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a43566d882fc7994385bbdaf7fe927e67">getGroupDef</a>()!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6255</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6256</span><span class="doxyLineContent"><span class="doxyHighlight">        mdec-&gt;<a href="/web-doxygen/docs/api/classes/memberdefmutable/#ac1ea8d9adeeef3466a0b36b20aa8ca8e">setGroupDef</a>(mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a43566d882fc7994385bbdaf7fe927e67">getGroupDef</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6257</span><span class="doxyLineContent"><span class="doxyHighlight">            mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a9ed95e7cef3948c6a978540c0d48bca7">getGroupPri</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6258</span><span class="doxyLineContent"><span class="doxyHighlight">            mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a00915f52f3b708bec07aab2b44f03d34">docFile</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6259</span><span class="doxyLineContent"><span class="doxyHighlight">            mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a26a4a6e3578aa6c81b2d6d77a1ce694f">docLine</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6260</span><span class="doxyLineContent"><span class="doxyHighlight">            mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a81f5c355e27d6e159e1598be748aa4de">hasDocumentation</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6261</span><span class="doxyLineContent"><span class="doxyHighlight">            mdef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6262</span><span class="doxyLineContent"><span class="doxyHighlight">            );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6263</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6264</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a43566d882fc7994385bbdaf7fe927e67">getGroupDef</a>()==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> &amp;&amp; mdec-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a43566d882fc7994385bbdaf7fe927e67">getGroupDef</a>()!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6265</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6266</span><span class="doxyLineContent"><span class="doxyHighlight">        mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdefmutable/#ac1ea8d9adeeef3466a0b36b20aa8ca8e">setGroupDef</a>(mdec-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a43566d882fc7994385bbdaf7fe927e67">getGroupDef</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6267</span><span class="doxyLineContent"><span class="doxyHighlight">            mdec-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a9ed95e7cef3948c6a978540c0d48bca7">getGroupPri</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6268</span><span class="doxyLineContent"><span class="doxyHighlight">            mdec-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a00915f52f3b708bec07aab2b44f03d34">docFile</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6269</span><span class="doxyLineContent"><span class="doxyHighlight">            mdec-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a26a4a6e3578aa6c81b2d6d77a1ce694f">docLine</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6270</span><span class="doxyLineContent"><span class="doxyHighlight">            mdec-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a81f5c355e27d6e159e1598be748aa4de">hasDocumentation</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6271</span><span class="doxyLineContent"><span class="doxyHighlight">            mdec</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6272</span><span class="doxyLineContent"><span class="doxyHighlight">            );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6273</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6274</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6275</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6276</span><span class="doxyLineContent"><span class="doxyHighlight">      mdec-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#ac9954b7f44ce715872d177b25966e13d">mergeRefItems</a>(mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6277</span><span class="doxyLineContent"><span class="doxyHighlight">      mdef-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#ac9954b7f44ce715872d177b25966e13d">mergeRefItems</a>(mdec);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6278</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6279</span><span class="doxyLineContent"><span class="doxyHighlight">      mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdefmutable/#a2701750e59071fffc3d5dddbb59cf6a7">setMemberDeclaration</a>(mdec);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6280</span><span class="doxyLineContent"><span class="doxyHighlight">      mdec-&gt;<a href="/web-doxygen/docs/api/classes/memberdefmutable/#ac6cc1fb03bddb3993a6b3fd8c7df75ef">setMemberDefinition</a>(mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6281</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6282</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/util-cpp/#aaeb66f0aa57917b9aff55be8d61cc8c2">mergeMemberOverrideOptions</a>(mdec,mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6283</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6284</span><span class="doxyLineContent"><span class="doxyHighlight">      mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdefmutable/#ab0dd3d7e2e5060662bac9dacc0c8bc0c">addQualifiers</a>(mdec-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a78ea63aa23ada7ecd6d8c59163c3dadf">getQualifiers</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6285</span><span class="doxyLineContent"><span class="doxyHighlight">      mdec-&gt;<a href="/web-doxygen/docs/api/classes/memberdefmutable/#ab0dd3d7e2e5060662bac9dacc0c8bc0c">addQualifiers</a>(mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a78ea63aa23ada7ecd6d8c59163c3dadf">getQualifiers</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6286</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6287</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6288</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/memberdefmutable/#ab0dd3d7e2e5060662bac9dacc0c8bc0c">MemberDefMutable::addQualifiers</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">MemberDef::argsString</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">MemberDef::argumentList</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO&#95;TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO&#95;TRACE&#95;ADD</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">Definition::briefDescription</a>, <a href="/web-doxygen/docs/api/classes/definition/#ac74d77550941a8f568ea56fecc30c873">Definition::briefFile</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8073d399d39c43e66a4b487b3e06ade1">Definition::briefLine</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/classes/definition/#a00915f52f3b708bec07aab2b44f03d34">Definition::docFile</a>, <a href="/web-doxygen/docs/api/classes/definition/#a26a4a6e3578aa6c81b2d6d77a1ce694f">Definition::docLine</a>, <a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">Definition::documentation</a>, <a href="/web-doxygen/docs/api/classes/definition/#a7ea253be90981d4a6f0cfdb6dff1d2fd">Definition::getBodyDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">Definition::getDefLine</a>, <a href="/web-doxygen/docs/api/classes/definition/#a0b5313ad11f50b2d056fc62d81db0433">Definition::getEndBodyLine</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a5036fd8ee16b186925236105029ee823">MemberDef::getFileDef</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a43566d882fc7994385bbdaf7fe927e67">MemberDef::getGroupDef</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a9ed95e7cef3948c6a978540c0d48bca7">MemberDef::getGroupPri</a>, <a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">Definition::getLanguage</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#ab3e5d2e532ebe2a0f45fe1a945fb4269">MemberDef::getMemberSpecifiers</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">Definition::getOuterScope</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a78ea63aa23ada7ecd6d8c59163c3dadf">MemberDef::getQualifiers</a>, <a href="/web-doxygen/docs/api/classes/definition/#ad63d39480ae9ec4e71bedbb749d16a4c">Definition::getStartBodyLine</a>, <a href="/web-doxygen/docs/api/classes/definition/#a81f5c355e27d6e159e1598be748aa4de">Definition::hasDocumentation</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#a2ed5c45b3909206446aaac4f1ab6d640">ArgumentList::hasParameters</a>, <a href="/web-doxygen/docs/api/classes/definition/#af59473951772c62b9db328e342fc2198">Definition::inbodyDocumentation</a>, <a href="/web-doxygen/docs/api/classes/definition/#af6fd6ee64e4e2599c1cb7cba93897aa7">Definition::inbodyFile</a>, <a href="/web-doxygen/docs/api/classes/definition/#a74cb27736839a0e602ef5fa9bbb9deab">Definition::inbodyLine</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a842ff86c34c3ae387d995e2597be8118">MemberDef::isDocsForDefinition</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a62a3294a87e2a6e2ff4a2d52bfd3187a">MemberDef::isExternal</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a5e6ace25ee464a601e1b3f2b8016ddad">MemberDef::isFunction</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#afa756b712f45e7800617808f708c2876">MemberDef::isPrototype</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a73354ecea5b876ab8d59724b080189b4">MemberDef::isStatic</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#ad7b6f788b487058e9e6ac65b092479b9">MemberDef::isVariable</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a78739b1ab728bbecd4d3e54ae90bbbce">matchArguments2</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aaeb66f0aa57917b9aff55be8d61cc8c2">mergeMemberOverrideOptions</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#ab0caddb69ae9c8c18e57ee452791f483">MemberDefMutable::mergeMemberSpecifiers</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#ac9954b7f44ce715872d177b25966e13d">DefinitionMutable::mergeRefItems</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#ae6b8b985f4a543215a25b698a28f4dfc">MemberDefMutable::moveArgumentList</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#ac1b97bdbdbe63513549b7f1585187f65">MemberDefMutable::moveDeclArgumentList</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#a3dc3cdf4626a0d405580d45a907f1719">MemberDefMutable::resolveUnnamedParameters</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#acebfd2c89008fa8ef42c9ab9bf61d4b7">DefinitionMutable::setBodyDef</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#a21f0601d0ac0f9d245c7a40e28adc3c6">DefinitionMutable::setBodySegment</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#ae704468ccbae4cbc26922db573676feb">DefinitionMutable::setBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#a8b1c18e7f7a27c2661cac096a24e2602">MemberDefMutable::setDocsForDefinition</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#a5115744bf4595f9a08a193dd41d4f4c3">DefinitionMutable::setDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#ac1ea8d9adeeef3466a0b36b20aa8ca8e">MemberDefMutable::setGroupDef</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#a8a4d82f0315802612dcd9732369eaa8a">DefinitionMutable::setInbodyDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#a2701750e59071fffc3d5dddbb59cf6a7">MemberDefMutable::setMemberDeclaration</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#ac6cc1fb03bddb3993a6b3fd8c7df75ef">MemberDefMutable::setMemberDefinition</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#a4d651caeb995400fad17d4ab4a020a3a">ArgumentList::size</a>, <a href="/web-doxygen/docs/api/files/src/defargs-h/#a88825bfb79a9c15e54ff57415b4de54d">stringToArgumentList</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a409da33c248938e57ba2135777a38628">MemberDef::templateArguments</a>, <a href="#a916ded3150c496785b98bbd5c2bee442">transferArgumentDocumentation</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a443122a21e609582f590173accd789a1">ClassDefImpl::mergeCategory</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#addab8233ce94a53e33f788e02e453790">MemberDefMutable::setFromAnonymousScope</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a4ee52c8be189a58fdf71cac6164f6be1">transferFunctionDocumentation</a>.
</div>
</div>

### createMemberDef() {#afc503b94aed5230ca07d22e743e9c800}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MemberDef &gt; createMemberDef (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; defFileName, int defLine, int defColumn, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; type, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; args, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; excp, <a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> prot, <a href="/web-doxygen/docs/api/files/src/types-h/#ab16236bdd10ddf4d73a9847350f0017e">Specifier</a> virt, bool stat, <a href="/web-doxygen/docs/api/files/src/types-h/#a9d625fe894d9313ec78df1d78553f32e">Relationship</a> related, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41">MemberType</a> t, const <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp; tal, const <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp; al, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; metaData)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Factory method to create a new instance of a <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>.</p>

<p>Definition at line <a href="#l00516">516</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afc503b94aed5230ca07d22e743e9c800">516</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::unique_ptr&lt;MemberDef&gt; <a href="#afc503b94aed5230ca07d22e743e9c800">createMemberDef</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;defFileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> defLine,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> defColumn,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">517</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;type,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;args,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">518</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;excp,<a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> prot,<a href="/web-doxygen/docs/api/files/src/types-h/#ab16236bdd10ddf4d73a9847350f0017e">Specifier</a> virt,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> stat,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/files/src/types-h/#a9d625fe894d9313ec78df1d78553f32e">Relationship</a> related,<a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41">MemberType</a> t,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;tal,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;al,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;metaData)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">521</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::make_unique&lt;MemberDefImpl&gt;(defFileName,defLine,defColumn,type,name,args,excp,prot,virt,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">                           stat,related,t,tal,al,metaData);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a636b9cfb60b78163bb29dbb6f21def29">addEnumValuesToEnums</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a95106cfe8d0c8504016e0714ae0e10f7">addGlobalFunction</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ab534a27eef617922af2a5d7baafffcae">addInstance</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7ba474a85367760e0e849c9732d5fa26">addInterfaceOrServiceToServiceOrSingleton</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5c29617e942b0f91f94f5b362cb2fa67">addLocalObjCMethod</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ae11c2fb2e5b6cbe3dcd1a1b594406e93">addMemberSpecialization</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad736f00784a47fe1c1bf6317f9a1b51b">addMethodToClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a45b876ed6758069be1442e9cbae2bbd0">addOverloaded</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f2a35ddd84e986afdbc14dcba2bcf3c">addVariableToClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a704656a4d637d9f99c1adef34aafe856">addVariableToFile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#afb0da87d7d3ab2047204073d584974ad">buildDefineList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad4d18463536d31e211957c9151fdbac2">createTagLessInstance</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a582f332d778bad3d6e991a75a2448d06">MemberDefImpl::createTemplateInstanceMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1ba016192f46b348d5dbc66f8f574380">createUsingMemberImportForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a589e3e52c7dc0599e7342171a7531064">findDefineDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a82770a95f2aebec7ffee2162e3a67215">findEnums</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a> and <a href="/web-doxygen/docs/api/classes/memberdefmutable/#addab8233ce94a53e33f788e02e453790">MemberDefMutable::setFromAnonymousScope</a>.
</div>
</div>

### createMemberDefAlias() {#a792961c33915b95213d78c7366c9dcb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MemberDef &gt; createMemberDefAlias (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * newScope, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * aliasMd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00966">966</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a792961c33915b95213d78c7366c9dcb3">966</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::unique_ptr&lt;MemberDef&gt; <a href="#a792961c33915b95213d78c7366c9dcb3">createMemberDefAlias</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *newScope,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *aliasMd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">967</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">968</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> amd = std::make_unique&lt;MemberDefAliasImpl&gt;(newScope,aliasMd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">969</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("amd: name=%s displayName=%s\n",qPrint(amd-&gt;name()),qPrint(amd-&gt;displayName()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">970</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> amd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">971</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a304d98a7f2677037f3ca7f4a3efd73ed">MemberDefAliasImpl::deepCopy</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ad1c6c890ed8e8ebcfe057f3de5db4fcb">NamespaceDefImpl::insertMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a02e748da779cf061b14c27d976efdb65">insertMemberAlias</a> and <a href="/web-doxygen/docs/api/classes/memberdefmutable/#addab8233ce94a53e33f788e02e453790">MemberDefMutable::setFromAnonymousScope</a>.
</div>
</div>

### invalidateCachedTypesInArgumentList() {#a8001f4748644d24e0537d505ef8a84a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void invalidateCachedTypesInArgumentList (<a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp; al)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l06102">6102</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8001f4748644d24e0537d505ef8a84a3">6102</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8001f4748644d24e0537d505ef8a84a3">invalidateCachedTypesInArgumentList</a>(<a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;al)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6103</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6104</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;a : al)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6105</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6106</span><span class="doxyLineContent"><span class="doxyHighlight">    a.canType.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6107</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6108</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#abfde37e18a3ba2c3d2e1d9e725d4a371">MemberDefImpl::invalidateCachedArgumentTypes</a>.
</div>
</div>

### simplifyTypeForTable() {#a0fcfb1e72d24be27533f0a69fd651264}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString simplifyTypeForTable (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l03922">3922</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0fcfb1e72d24be27533f0a69fd651264">3922</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a0fcfb1e72d24be27533f0a69fd651264">simplifyTypeForTable</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3923</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3924</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> ts=<a href="/web-doxygen/docs/api/files/src/util-cpp/#a775441ec8999df6462d2813ff52b3b52">removeAnonymousScopes</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3925</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ts.<a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">endsWith</a>(</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">)) ts = ts.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(ts.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3926</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> re1(R</span><span class="doxyHighlightStringLiteral">"(\a\w*::)");       </span><span class="doxyHighlightComment">// non-template version</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3927</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> re2(R</span><span class="doxyHighlightStringLiteral">"(\a\w*&lt;[^&gt;]*&gt;::)"); </span><span class="doxyHighlightComment">// template version</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3928</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/reg/match">reg::Match</a> match;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3929</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string t = ts.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3930</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>(t,match,re2) || <a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>(t,match,re1))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3931</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3932</span><span class="doxyLineContent"><span class="doxyHighlight">    t = match.prefix().str() + match.suffix().str(); </span><span class="doxyHighlightComment">// remove the matched part</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3933</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3934</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("simplifyTypeForTable(%s)-&gt;%s\n",qPrint(s),t.c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3935</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3936</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">QCString::endsWith</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a775441ec8999df6462d2813ff52b3b52">removeAnonymousScopes</a>, <a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#aa28cb040180473ff3e2ef3e03e55cbcc">MemberDefImpl::fieldType</a>.
</div>
</div>

### stripTrailingReturn() {#a301116112cb06af3d6fa71fdb8c9b940}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString stripTrailingReturn (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; trailRet)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l04169">4169</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a301116112cb06af3d6fa71fdb8c9b940">4169</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a301116112cb06af3d6fa71fdb8c9b940">stripTrailingReturn</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;trailRet)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4170</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4171</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> ret = trailRet;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4172</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4173</span><span class="doxyLineContent"><span class="doxyHighlight">  ret = ret.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4174</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ret.<a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">startsWith</a>(</span><span class="doxyHighlightStringLiteral">"-&gt;"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4175</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4176</span><span class="doxyLineContent"><span class="doxyHighlight">    ret = ret.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(2).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4177</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> ret;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4178</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4179</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> trailRet;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4180</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">QCString::startsWith</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a31cfb988a49ee5b4f6e0f64dded34507">MemberDefImpl::warnIfUndocumentedParams</a>.
</div>
</div>

### toMemberDef() {#af5b90e1ee6115fc2c7c6ce672c3dd157}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemberDef * toMemberDef (<a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l06452">6452</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af5b90e1ee6115fc2c7c6ce672c3dd157">6452</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *<a href="#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>(<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6453</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6454</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d &amp;&amp; (</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/memberdefimpl">MemberDefImpl</a>) || </span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/memberdefaliasimpl">MemberDefAliasImpl</a>)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6455</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6456</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6457</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6458</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6459</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6460</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6461</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6462</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/files/src/code-l/#afce5972b6b52acbb18c0d79b1f0d4433">codeFolding</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a005a8e61f7c0837d79b6ac28a0e5a73b">DefinitionImpl::computeTooltip</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#ae15cbb19e2f84dafe98f527902c3e2d9">definitionToName</a>, <a href="/web-doxygen/docs/api/classes/docref/#acb234cd7235b7c61a4c6f9dfd0cd586b">DocRef::DocRef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a833bced73323c4df8e30a7491a0857b2">dumpSymbol</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a767fe9c8dd14640cc99a6f1c9e0981c7">findMemberLink</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a3345ad9e2ab3a9d1b524391ae5f6c545">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a92aa0c495ca4eb835bb914dbb5fefa35">getDefsNew</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#aab5d8e484c3bc3f37546f807d76d6ccc">MemberDefAliasImpl::getMdAlias</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#aa35f82a07125e195a28330a8b761dd53">MemberDefAliasImpl::getMdAlias</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5ecfe67024087367b33d18430021a3c0">getMemberFromSymbol</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a40f0f9c9cb6b6b7392ae6e695fc74671">SymbolResolver::Private::getResolvedSymbol</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#aef9c4245c6f445e282a59005f1f6ca5a">SymbolResolver::Private::getResolvedType</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a088166e0f872cd290425780f4b5c45f6">getSQLDocBlock</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a60ffd0b23680e5318865a367b0d26871">SymbolResolver::Private::isAccessibleFrom</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a01a031ffd0a93eb06668c1e93fb57f69">SymbolResolver::Private::isAccessibleFromWithExpScope</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a4b7d1c2724099f28c4f3a4c56c52d912">DocParser::processCopyDoc</a>, <a href="/web-doxygen/docs/api/classes/symbolresolver/#a739c707d2150c5b2115fa731694eaeec">SymbolResolver::resolveSymbol</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a653335defbae0c2b319413c2d9376458">resolveUserReferences</a>, <a href="/web-doxygen/docs/api/classes/searchindex/#ac8f6bb104126c1406d2d6e5ad368822c">SearchIndex::setCurrentDoc</a>, <a href="/web-doxygen/docs/api/classes/searchindexexternal/#adcacedbd41c269a155cadcb46deda856">SearchIndexExternal::setCurrentDoc</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#addab8233ce94a53e33f788e02e453790">MemberDefMutable::setFromAnonymousScope</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a763d03603a7b427c9f02719fb95b2c30">SymbolResolver::Private::substTypedef</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a6bab634f62d558e8d56cb84dee170cd2">DefinitionImpl::writeInlineCode</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a83984e7adf06e5e5006d61c0634d8a54">writeJavasScriptSearchDataPage</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#af2995da196faa8940cca40cfc158b9aa">writeObjCMethodCall</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#acff1068065be6bd3a5526d291555c7a6">DefinitionImpl::writeToc</a> and <a href="/web-doxygen/docs/api/classes/tooltipmanager/#a9fabdb64f4fd1b5a5fded9d7dac90c3b">TooltipManager::writeTooltips</a>.
</div>
</div>

### toMemberDef() {#aadf8d5c103d1bd6ff91c784f02ebe2dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemberDef * toMemberDef (<a href="/web-doxygen/docs/api/classes/definitionmutable">DefinitionMutable</a> * md)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l06464">6464</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aadf8d5c103d1bd6ff91c784f02ebe2dd">6464</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *<a href="#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>(<a href="/web-doxygen/docs/api/classes/definitionmutable">DefinitionMutable</a> *md)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6465</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6466</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d = <a href="/web-doxygen/docs/api/files/src/definition-cpp/#ab43e817b86eeee8909980167d1a140c8">toDefinition</a>(md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6467</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d &amp;&amp; </span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/memberdefimpl">MemberDefImpl</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6468</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6469</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6470</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6471</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6472</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6473</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6474</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6475</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/files/src/definition-cpp/#ab43e817b86eeee8909980167d1a140c8">toDefinition</a>.
</div>
</div>

### toMemberDef() {#aac062c9356229664b77d347ac8cc94d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MemberDef * toMemberDef (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l06477">6477</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aac062c9356229664b77d347ac8cc94d0">6477</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *<a href="#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6478</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6479</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d &amp;&amp; (</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/memberdefimpl">MemberDefImpl</a>) || </span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/memberdefaliasimpl">MemberDefAliasImpl</a>)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6480</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6481</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6482</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6483</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6484</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6485</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6486</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6487</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### toMemberDefMutable() {#a9ea80ba313803ae565f05ce1c8eb6bb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemberDefMutable * toMemberDefMutable (<a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l06489">6489</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9ea80ba313803ae565f05ce1c8eb6bb5">6489</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *<a href="#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>(<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6490</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6491</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d &amp;&amp; </span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/memberdefimpl">MemberDefImpl</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6492</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6493</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6494</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6495</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6496</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6497</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6498</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6499</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="#a91959a7c929a76adaaa2d342fea73126">addDocCrossReference</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a636b9cfb60b78163bb29dbb6f21def29">addEnumValuesToEnums</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a95106cfe8d0c8504016e0714ae0e10f7">addGlobalFunction</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ab534a27eef617922af2a5d7baafffcae">addInstance</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7ba474a85367760e0e849c9732d5fa26">addInterfaceOrServiceToServiceOrSingleton</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a332043aa0d664d063e7fcc0614acbeea">MemberList::addListReferences</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5c29617e942b0f91f94f5b362cb2fa67">addLocalObjCMethod</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ae11c2fb2e5b6cbe3dcd1a1b594406e93">addMemberSpecialization</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a629f6fc7b319c74df28381ca2e009d0b">addMembersToMemberGroup</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#affd271e102af38c14812ccc21a86401c">addMemberToGroups</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a0b89a353206730e5f1ce65366c49f92f">ClassDefImpl::addMemberToList</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a3e2d8e1f9b98e5cecd9414d91cb82085">FileDefImpl::addMemberToList</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a9ebc186b5b7ace2541d5e51ff8f26da1">ModuleDefImpl::addMemberToList</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a401c44767708d6a589a4b50891c3f435">NamespaceDefImpl::addMemberToList</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a3ac0043018354a90b2ce4cba4413f606">ModuleDefImpl::addMemberToModule</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a8eaf52205769b3910d40de52c5eefd51">ModuleManager::addMemberToModule</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a1f7c3408ea1bf71c19a8e593763d88f7">ClassDefImpl::addMemberToTemplateInstance</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad736f00784a47fe1c1bf6317f9a1b51b">addMethodToClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a45b876ed6758069be1442e9cbae2bbd0">addOverloaded</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f2a35ddd84e986afdbc14dcba2bcf3c">addVariableToClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a704656a4d637d9f99c1adef34aafe856">addVariableToFile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#afb0da87d7d3ab2047204073d584974ad">buildDefineList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a568741e989fcbe6cd20c1295cf9c7aed">buildTypedefList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#afee2d528ad3660fd6ab8de9e42ac6752">computeMemberRelationsForBaseClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad4d18463536d31e211957c9151fdbac2">createTagLessInstance</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a582f332d778bad3d6e991a75a2448d06">MemberDefImpl::createTemplateInstanceMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1ba016192f46b348d5dbc66f8f574380">createUsingMemberImportForClass</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7a05059f489e3c94d51aa47127ccdfed">ClassDefImpl::deepCopy</a>, <a href="/web-doxygen/docs/api/classes/membergroup/#a7814e5796402b44a7ee813a2bd5c23eb">MemberGroup::distributeMemberGroupDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a589e3e52c7dc0599e7342171a7531064">findDefineDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a10e11a9d8c5f3fc3b78bc02ebe04380c">findDEV</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab97b7f9be435590df65d9bb0d31fba06">findEnumDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a82770a95f2aebec7ffee2162e3a67215">findEnums</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a825f829ad3f2e4e1a52d8959b0ff3fb9">findFriends</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5dc8c4afa4009560979330b7c6fb2cb3">findGlobalMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#ad095317a533d0e4d883e286a5599746d">MemberList::findSectionsInDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a082d23658541704d3493a7a881583d55">flushCachedTemplateRelations</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#aad3dd00ae1c58bfc06981afcc5f14a53">flushUnresolvedRelations</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ada294ec0d3d5d40d4bb74d5624c886d4">generateClassMemberLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a3345ad9e2ab3a9d1b524391ae5f6c545">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a7c3e45cceb9eb4446d360eb8620eef8c">getLinkInScope</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7c714f2eedf0d52d8428bbcdd06b6975">ClassDefImpl::hideDerivedVariablesInPython</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a4e0a7985a36e2f35ba21be58c8285f02">incrementFlowKeyWordCount</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a4e0a7985a36e2f35ba21be58c8285f02">incrementFlowKeyWordCount</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#aad23f7d576fcba6cc66edf702842a9d3">inheritDocumentation</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a8741a4a807c8e1808f82c08f00152a2f">GroupDefImpl::insertMember</a>, <a href="/web-doxygen/docs/api/classes/membergroup/#ad7b02bac5d0ed254d5c979b19cf4ae1e">MemberGroup::insertMember</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ad1c6c890ed8e8ebcfe057f3de5db4fcb">NamespaceDefImpl::insertMember</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a04d8bdd0ceb3b8cb7ec8cf64e4731ed7">MemberDefImpl::insertReimplementedBy</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a443122a21e609582f590173accd789a1">ClassDefImpl::mergeCategory</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a39bb7d9a1e431158cb3a423215f044bb">processTagLessClasses</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#ae626c9e633e5efcf3476b1c7c847d06b">MemberList::setAnchors</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a663e4dedf84ec20ab0b682c0c762647e">MemberList::setAnonymousEnumType</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#addab8233ce94a53e33f788e02e453790">MemberDefMutable::setFromAnonymousScope</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#aa8cd9bab78377e9d6719c0b77ff07120">ClassDefImpl::setGroupDefForAllMembers</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a4ee52c8be189a58fdf71cac6164f6be1">transferFunctionDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#af9f9567b822b1cbc46ff46b5a310ceab">transferFunctionReferences</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a42120760d9d3f1ffe7d1561ef7b50a49">transferRelatedFunctionDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5234f1896d9c47e7836c34e3b03a36b0">transferStaticInstanceInitializers</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a4299844cb805de324387ae0072ea6e9d">tryAddEnumDocsToGroupMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3d2bdb9a2c2b81909c7835cece01d448">vhdlCorrectMemberProperties</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#aa86fa71c504d7676073931dcca08f3dc">MemberList::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#af29c795d264e74de8cc53f3d5c550d41">MemberList::writeDocumentationPage</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#afc394d10d64e221682e9619eef74fde5">VhdlDocGen::writePlainVHDLDeclarations</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a8cab5da1323054e47ede48e03a1420a2">MemberList::writeSimpleDocumentation</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a1c145b8082cd9865b477141ab58dcb20">VhdlDocGen::writeSource</a> and <a href="/web-doxygen/docs/api/classes/memberlist/#a20813d8313b4dfdb5a6625efc4e989ef">MemberList::writeTagFile</a>.
</div>
</div>

### transferArgumentDocumentation() {#a916ded3150c496785b98bbd5c2bee442}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void transferArgumentDocumentation (<a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp; decAl, <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp; defAl)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l06135">6135</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a916ded3150c496785b98bbd5c2bee442">6135</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a916ded3150c496785b98bbd5c2bee442">transferArgumentDocumentation</a>(<a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;decAl,<a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;defAl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6136</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6137</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> decIt = decAl.<a href="/web-doxygen/docs/api/classes/argumentlist/#acc52d012d093df1adede055164f69dc9">begin</a>(), defIt = defAl.<a href="/web-doxygen/docs/api/classes/argumentlist/#acc52d012d093df1adede055164f69dc9">begin</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6138</span><span class="doxyLineContent"><span class="doxyHighlight">            decIt!= decAl.<a href="/web-doxygen/docs/api/classes/argumentlist/#a215181845c0d9f0525806a4165c4f552">end</a>() &amp;&amp; defIt!= defAl.<a href="/web-doxygen/docs/api/classes/argumentlist/#a215181845c0d9f0525806a4165c4f552">end</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6139</span><span class="doxyLineContent"><span class="doxyHighlight">          ++decIt,               ++defIt)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6140</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6141</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;decA = *decIt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6142</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;defA = *defIt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6143</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (decA.<a href="/web-doxygen/docs/api/structs/argument/#a5d6cd35aa392b1703acf14104b19c589">docs</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; !defA.<a href="/web-doxygen/docs/api/structs/argument/#a5d6cd35aa392b1703acf14104b19c589">docs</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6144</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6145</span><span class="doxyLineContent"><span class="doxyHighlight">      decA.<a href="/web-doxygen/docs/api/structs/argument/#a5d6cd35aa392b1703acf14104b19c589">docs</a> = defA.<a href="/web-doxygen/docs/api/structs/argument/#a5d6cd35aa392b1703acf14104b19c589">docs</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6146</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6147</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (defA.<a href="/web-doxygen/docs/api/structs/argument/#a5d6cd35aa392b1703acf14104b19c589">docs</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; !decA.<a href="/web-doxygen/docs/api/structs/argument/#a5d6cd35aa392b1703acf14104b19c589">docs</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6148</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6149</span><span class="doxyLineContent"><span class="doxyHighlight">      defA.<a href="/web-doxygen/docs/api/structs/argument/#a5d6cd35aa392b1703acf14104b19c589">docs</a> = decA.<a href="/web-doxygen/docs/api/structs/argument/#a5d6cd35aa392b1703acf14104b19c589">docs</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6150</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6151</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(RESOLVE_UNNAMED_PARAMS))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6152</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6153</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (decA.<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; !defA.<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6154</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6155</span><span class="doxyLineContent"><span class="doxyHighlight">        decA.<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a> = defA.<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6156</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6157</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (defA.<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; !decA.<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6158</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6159</span><span class="doxyLineContent"><span class="doxyHighlight">        defA.<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a> = decA.<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6160</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6161</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6162</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6163</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/argumentlist/#acc52d012d093df1adede055164f69dc9">ArgumentList::begin</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/structs/argument/#a5d6cd35aa392b1703acf14104b19c589">Argument::docs</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#a215181845c0d9f0525806a4165c4f552">ArgumentList::end</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">Argument::name</a>.

Referenced by <a href="#abaf3303e28a7a9e34bdcfbe4bfc893cb">combineDeclarationAndDefinition</a>.
</div>
</div>

### writeDefArgumentList() {#a5109f6f8128e0b9169ac9b8ebe29ba64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool writeDefArgumentList (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * scope, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l01048">1048</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5109f6f8128e0b9169ac9b8ebe29ba64">1048</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *scope,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1049</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1050</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;defArgList=(md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a842ff86c34c3ae387d995e2597be8118">isDocsForDefinition</a>()) ?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1051</span><span class="doxyLineContent"><span class="doxyHighlight">                             md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">argumentList</a>() : md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#af0d0461390544ad385a962aefd88c313">declArgumentList</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1052</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("writeDefArgumentList '%s' isDocsForDefinition()=%d hasParameters()=%d (%s)\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1053</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//    qPrint(md-&gt;name()),md-&gt;isDocsForDefinition(),defArgList.hasParameters(),qPrint(argListToString(defArgList)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1054</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!defArgList.<a href="/web-doxygen/docs/api/classes/argumentlist/#a2ed5c45b3909206446aaac4f1ab6d640">hasParameters</a>() || md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#afd4a6cd84468b885049120e767b017fc">isProperty</a>() || md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a4bd8f9b14007a57f53918a21258c284e">isTypedef</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1055</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1056</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>; </span><span class="doxyHighlightComment">// member has no function like argument list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1057</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1058</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1059</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isDefine = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a8c9a34fe614f8c55edc60deaf0143f47">isDefine</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1060</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!isDefine) ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1061</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1062</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("writeDefArgList(%d)\n",defArgList-&gt;count());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1063</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a1c30d8717346992a8a9c35f2ae92271f">endMemberDocName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1064</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a297f991eafa9e368a982c936891bb79e">startParameterList</a>(!md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a146e2a27f8eee953b076a03e42ecf2b4">isObjCMethod</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1065</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("===&gt; name=%s isDefine=%d\n",qPrint(md-&gt;name()),md-&gt;isDefine());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1066</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1067</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> cName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1068</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (scope)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1069</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1070</span><span class="doxyLineContent"><span class="doxyHighlight">    cName=scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1071</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> il=cName.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1072</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> ir=cName.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1073</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (il!=-1 &amp;&amp; ir!=-1 &amp;&amp; ir&gt;il)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1074</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1075</span><span class="doxyLineContent"><span class="doxyHighlight">      cName=cName.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(il,ir-il+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1076</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("1. cName=%s\n",qPrint(cName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1077</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1078</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1079</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1080</span><span class="doxyLineContent"><span class="doxyHighlight">      cName=<a href="/web-doxygen/docs/api/files/src/util-cpp/#a5f86911d03ddead5c20dc99ef4828d17">tempArgListToString</a>((<a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>(scope))-&gt;templateArguments(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1081</span><span class="doxyLineContent"><span class="doxyHighlight">                             scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">getLanguage</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1082</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("2. cName=%s\n",qPrint(cName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1083</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1084</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// no template specifier</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1085</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1086</span><span class="doxyLineContent"><span class="doxyHighlight">      cName.<a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">clear</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1087</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1088</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1089</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("~~~ %s cName=%s\n",qPrint(md-&gt;name()),qPrint(cName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1090</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1091</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> sep = <a href="/web-doxygen/docs/api/files/src/util-cpp/#aab590e3dd52a9375bb3afe31dc6f8609">getLanguageSpecificSeparator</a>(md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">getLanguage</a>(),</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1092</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1093</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> first=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1094</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> paramTypeStarted=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1095</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> alIt = defArgList.<a href="/web-doxygen/docs/api/classes/argumentlist/#acc52d012d093df1adede055164f69dc9">begin</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1096</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (alIt!=defArgList.<a href="/web-doxygen/docs/api/classes/argumentlist/#a215181845c0d9f0525806a4165c4f552">end</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1097</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1098</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/argument">Argument</a> a = *alIt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1099</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isDefine || first)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1100</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1101</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a8db9e1278341d4eeb45328fd9967a6b5">startParameterType</a>(first,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1102</span><span class="doxyLineContent"><span class="doxyHighlight">      paramTypeStarted=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1103</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isDefine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1104</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1105</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#acb73d83bd4b05b5041de62a7336747e5">endParameterType</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1106</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#acde2fcc0d42034b7f342d12119957a81">startParameterName</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1107</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1108</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1109</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1110</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!a.<a href="/web-doxygen/docs/api/structs/argument/#aff930f2a4cb85b5616be79b81db2341f">attrib</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; !md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a146e2a27f8eee953b076a03e42ecf2b4">isObjCMethod</a>()) </span><span class="doxyHighlightComment">// argument has an IDL attribute</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1111</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1112</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(a.<a href="/web-doxygen/docs/api/structs/argument/#aff930f2a4cb85b5616be79b81db2341f">attrib</a>+</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1113</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1114</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1115</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> atype = a.<a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">type</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1116</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sep!=</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">) { atype=<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(atype,</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">,sep); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1117</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1118</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> funcPtrPos=-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1119</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1120</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a146e2a27f8eee953b076a03e42ecf2b4">isObjCMethod</a>()) { atype.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(</span><span class="doxyHighlightStringLiteral">"("</span><span class="doxyHighlight">); atype.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">append</a>(</span><span class="doxyHighlightStringLiteral">")"</span><span class="doxyHighlight">); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1121</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (atype!=</span><span class="doxyHighlightStringLiteral">"..."</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1122</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1123</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!cName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; scope &amp;&amp; scope!=<a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1124</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1125</span><span class="doxyLineContent"><span class="doxyHighlight">          atype=<a href="#ac66cc6a4e1d7c053d396a641dfe15d93">addTemplateNames</a>(atype,scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(),cName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1126</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1127</span><span class="doxyLineContent"><span class="doxyHighlight">        funcPtrPos = atype.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"*)("</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1128</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (funcPtrPos!=-1) funcPtrPos++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1129</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a>(<a href="/web-doxygen/docs/api/classes/textgeneratorolimpl">TextGeneratorOLImpl</a>(ol),scope,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a7ea253be90981d4a6f0cfdb6dff1d2fd">getBodyDef</a>(),md,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1130</span><span class="doxyLineContent"><span class="doxyHighlight">                    funcPtrPos==-1 ? atype : atype.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(funcPtrPos));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1131</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1132</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1133</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1134</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!isDefine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1135</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1136</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (paramTypeStarted)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1137</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1138</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#acb73d83bd4b05b5041de62a7336747e5">endParameterType</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1139</span><span class="doxyLineContent"><span class="doxyHighlight">        paramTypeStarted=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1140</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1141</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#acde2fcc0d42034b7f342d12119957a81">startParameterName</a>(defArgList.<a href="/web-doxygen/docs/api/classes/argumentlist/#a4d651caeb995400fad17d4ab4a020a3a">size</a>()&lt;2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1142</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1143</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1144</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1145</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a93053950ab9941273ab071bbb0646c35">endParameterName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1146</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1147</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1148</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (atype==</span><span class="doxyHighlightStringLiteral">"..."</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1149</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1150</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(atype);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1151</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1152</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!a.<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightComment">// argument has a name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1153</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1154</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(a.<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1155</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1156</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!isDefine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1157</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1158</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (funcPtrPos!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1159</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1160</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#ae6cc078977edd1e2a5ae2cf6ed64ed35">writeNonBreakableSpace</a>(1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1161</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1162</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a93053950ab9941273ab071bbb0646c35">endParameterName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1163</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1164</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a251c67c01e2bcc17814da33c186bd1f9">startParameterExtra</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1165</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (funcPtrPos!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1166</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1167</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a>(<a href="/web-doxygen/docs/api/classes/textgeneratorolimpl">TextGeneratorOLImpl</a>(ol),scope,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a7ea253be90981d4a6f0cfdb6dff1d2fd">getBodyDef</a>(),md,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1168</span><span class="doxyLineContent"><span class="doxyHighlight">                  atype.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(funcPtrPos));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1169</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1170</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!a.<a href="/web-doxygen/docs/api/structs/argument/#a9e33101befb3a977ac863d8a595ed210">array</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1171</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1172</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(a.<a href="/web-doxygen/docs/api/structs/argument/#a9e33101befb3a977ac863d8a595ed210">array</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1173</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1174</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!a.<a href="/web-doxygen/docs/api/structs/argument/#a4fe1d9319dede52f7551f59297772efa">defval</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightComment">// write the default value</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1175</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1176</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> n=a.<a href="/web-doxygen/docs/api/structs/argument/#a4fe1d9319dede52f7551f59297772efa">defval</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1177</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (scope &amp;&amp; scope!=<a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a> &amp;&amp; !cName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1178</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1179</span><span class="doxyLineContent"><span class="doxyHighlight">        n=<a href="#ac66cc6a4e1d7c053d396a641dfe15d93">addTemplateNames</a>(n,scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(),cName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1180</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1181</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a7350c12854789b59595b4ad1d40a651c">startParameterDefVal</a>(</span><span class="doxyHighlightStringLiteral">" = "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1182</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a>(<a href="/web-doxygen/docs/api/classes/textgeneratorolimpl">TextGeneratorOLImpl</a>(ol),scope,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a7ea253be90981d4a6f0cfdb6dff1d2fd">getBodyDef</a>(),md,n,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1183</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a8be0158b8b2a857157cfe92b802e0609">endParameterDefVal</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1184</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1185</span><span class="doxyLineContent"><span class="doxyHighlight">    ++alIt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1186</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (alIt!=defArgList.<a href="/web-doxygen/docs/api/classes/argumentlist/#a215181845c0d9f0525806a4165c4f552">end</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1187</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1188</span><span class="doxyLineContent"><span class="doxyHighlight">      a = *alIt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1189</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a146e2a27f8eee953b076a03e42ecf2b4">isObjCMethod</a>()) ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">); </span><span class="doxyHighlightComment">// there are more arguments</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1190</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!isDefine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1191</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1192</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> key;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1193</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a146e2a27f8eee953b076a03e42ecf2b4">isObjCMethod</a>() &amp;&amp; a.<a href="/web-doxygen/docs/api/structs/argument/#aff930f2a4cb85b5616be79b81db2341f">attrib</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()&gt;=2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1194</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1195</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//printf("Found parameter keyword %s\n",a.qPrint(attrib));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1196</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// strip [ and ]</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1197</span><span class="doxyLineContent"><span class="doxyHighlight">          key=a.<a href="/web-doxygen/docs/api/structs/argument/#aff930f2a4cb85b5616be79b81db2341f">attrib</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(1,a.<a href="/web-doxygen/docs/api/structs/argument/#aff930f2a4cb85b5616be79b81db2341f">attrib</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1198</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (key!=</span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight">) key+=</span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// for normal keywords add colon</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1199</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1200</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a0da2c95a60c78bda71d5f35d5adeb02f">endParameterExtra</a>(</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,!md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a146e2a27f8eee953b076a03e42ecf2b4">isObjCMethod</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1201</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a8db9e1278341d4eeb45328fd9967a6b5">startParameterType</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,key);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1202</span><span class="doxyLineContent"><span class="doxyHighlight">        paramTypeStarted=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1203</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1204</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// isDefine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1205</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1206</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a0da2c95a60c78bda71d5f35d5adeb02f">endParameterExtra</a>(</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1207</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1208</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1209</span><span class="doxyLineContent"><span class="doxyHighlight">    first=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1210</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1211</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (first)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1212</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1213</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#acde2fcc0d42034b7f342d12119957a81">startParameterName</a>(defArgList.<a href="/web-doxygen/docs/api/classes/argumentlist/#a4d651caeb995400fad17d4ab4a020a3a">size</a>()&lt;2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1214</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a93053950ab9941273ab071bbb0646c35">endParameterName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1215</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a251c67c01e2bcc17814da33c186bd1f9">startParameterExtra</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1216</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1217</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a0da2c95a60c78bda71d5f35d5adeb02f">endParameterExtra</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,defArgList.<a href="/web-doxygen/docs/api/classes/argumentlist/#a4d651caeb995400fad17d4ab4a020a3a">size</a>()&lt;2,!md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a146e2a27f8eee953b076a03e42ecf2b4">isObjCMethod</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1218</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a53ca4dbd8b0975ce3bf393a52a15e435">extraTypeChars</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1219</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1220</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a53ca4dbd8b0975ce3bf393a52a15e435">extraTypeChars</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1221</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1222</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (defArgList.<a href="/web-doxygen/docs/api/classes/argumentlist/#a72440ac7985da3c0c465134bc0ddd2d5">constSpecifier</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1223</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1224</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" const"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1225</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1226</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (defArgList.<a href="/web-doxygen/docs/api/classes/argumentlist/#ad03f25174e81a42a617a15195a8867b0">volatileSpecifier</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1227</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1228</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" volatile"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1229</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1230</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (defArgList.<a href="/web-doxygen/docs/api/classes/argumentlist/#a10a0f5f25aa7f3c97ac071169c85e4ac">refQualifier</a>()==<a href="/web-doxygen/docs/api/files/src/arguments-h/#a4f78d801ad01da94c75f928280228884a74accfde3d3f8e8a27c326eba229d16c">RefQualifierType::LValue</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1231</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1232</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" &amp;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1233</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1234</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (defArgList.<a href="/web-doxygen/docs/api/classes/argumentlist/#a10a0f5f25aa7f3c97ac071169c85e4ac">refQualifier</a>()==<a href="/web-doxygen/docs/api/files/src/arguments-h/#a4f78d801ad01da94c75f928280228884ac756c8b5e0e5217b000321397a40be7e">RefQualifierType::RValue</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1235</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1236</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" &amp;&amp;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1237</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1238</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!defArgList.<a href="/web-doxygen/docs/api/classes/argumentlist/#a4cb7b4a29cb7e4564014d024f8de9bc5">trailingReturnType</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1239</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1240</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a>(<a href="/web-doxygen/docs/api/classes/textgeneratorolimpl">TextGeneratorOLImpl</a>(ol), </span><span class="doxyHighlightComment">// out</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1241</span><span class="doxyLineContent"><span class="doxyHighlight">                scope,                   </span><span class="doxyHighlightComment">// scope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1242</span><span class="doxyLineContent"><span class="doxyHighlight">                md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a7ea253be90981d4a6f0cfdb6dff1d2fd">getBodyDef</a>(),        </span><span class="doxyHighlightComment">// fileScope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1243</span><span class="doxyLineContent"><span class="doxyHighlight">                md,                      </span><span class="doxyHighlightComment">// self</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1244</span><span class="doxyLineContent"><span class="doxyHighlight">                defArgList.<a href="/web-doxygen/docs/api/classes/argumentlist/#a4cb7b4a29cb7e4564014d024f8de9bc5">trailingReturnType</a>(), </span><span class="doxyHighlightComment">// text</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1245</span><span class="doxyLineContent"><span class="doxyHighlight">                <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>                    </span><span class="doxyHighlightComment">// autoBreak</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1246</span><span class="doxyLineContent"><span class="doxyHighlight">               );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1247</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1248</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1249</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1250</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ac66cc6a4e1d7c053d396a641dfe15d93">addTemplateNames</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">QCString::append</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">MemberDef::argumentList</a>, <a href="/web-doxygen/docs/api/structs/argument/#a9e33101befb3a977ac863d8a595ed210">Argument::array</a>, <a href="/web-doxygen/docs/api/structs/argument/#aff930f2a4cb85b5616be79b81db2341f">Argument::attrib</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#acc52d012d093df1adede055164f69dc9">ArgumentList::begin</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">QCString::clear</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#a72440ac7985da3c0c465134bc0ddd2d5">ArgumentList::constSpecifier</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#af0d0461390544ad385a962aefd88c313">MemberDef::declArgumentList</a>, <a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">Definition::definitionType</a>, <a href="/web-doxygen/docs/api/structs/argument/#a4fe1d9319dede52f7551f59297772efa">Argument::defval</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">OutputList::docify</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#a215181845c0d9f0525806a4165c4f552">ArgumentList::end</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a1c30d8717346992a8a9c35f2ae92271f">OutputList::endMemberDocName</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a8be0158b8b2a857157cfe92b802e0609">OutputList::endParameterDefVal</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a0da2c95a60c78bda71d5f35d5adeb02f">OutputList::endParameterExtra</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a93053950ab9941273ab071bbb0646c35">OutputList::endParameterName</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#acb73d83bd4b05b5041de62a7336747e5">OutputList::endParameterType</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a53ca4dbd8b0975ce3bf393a52a15e435">MemberDef::extraTypeChars</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a>, <a href="/web-doxygen/docs/api/classes/definition/#a7ea253be90981d4a6f0cfdb6dff1d2fd">Definition::getBodyDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">Definition::getLanguage</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aab590e3dd52a9375bb3afe31dc6f8609">getLanguageSpecificSeparator</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#a2ed5c45b3909206446aaac4f1ab6d640">ArgumentList::hasParameters</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a8c9a34fe614f8c55edc60deaf0143f47">MemberDef::isDefine</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a842ff86c34c3ae387d995e2597be8118">MemberDef::isDocsForDefinition</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a146e2a27f8eee953b076a03e42ecf2b4">MemberDef::isObjCMethod</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#afd4a6cd84468b885049120e767b017fc">MemberDef::isProperty</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a4bd8f9b14007a57f53918a21258c284e">MemberDef::isTypedef</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a>, <a href="/web-doxygen/docs/api/files/src/arguments-h/#a4f78d801ad01da94c75f928280228884a74accfde3d3f8e8a27c326eba229d16c">LValue</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">Argument::name</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">QCString::prepend</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#a10a0f5f25aa7f3c97ac071169c85e4ac">ArgumentList::refQualifier</a>, <a href="/web-doxygen/docs/api/files/src/arguments-h/#a4f78d801ad01da94c75f928280228884ac756c8b5e0e5217b000321397a40be7e">RValue</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#a4d651caeb995400fad17d4ab4a020a3a">ArgumentList::size</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a7350c12854789b59595b4ad1d40a651c">OutputList::startParameterDefVal</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a251c67c01e2bcc17814da33c186bd1f9">OutputList::startParameterExtra</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a297f991eafa9e368a982c936891bb79e">OutputList::startParameterList</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#acde2fcc0d42034b7f342d12119957a81">OutputList::startParameterName</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a8db9e1278341d4eeb45328fd9967a6b5">OutputList::startParameterType</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5f86911d03ddead5c20dc99ef4828d17">tempArgListToString</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#a4cb7b4a29cb7e4564014d024f8de9bc5">ArgumentList::trailingReturnType</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">Argument::type</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#ad03f25174e81a42a617a15195a8867b0">ArgumentList::volatileSpecifier</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ae6cc078977edd1e2a5ae2cf6ed64ed35">OutputList::writeNonBreakableSpace</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>.
</div>
</div>

### writeExceptionList() {#a158781f51faf723e59ca681487e4da1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeExceptionList (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l01291">1291</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a158781f51faf723e59ca681487e4da1a">1291</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a158781f51faf723e59ca681487e4da1a">writeExceptionList</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1292</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1293</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> exception(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a2f94a19fd2121d155de4865cf7c2fa81">excpString</a>()).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1294</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (</span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">==exception.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(0))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1295</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1296</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// this is an UNO IDL attribute - need special handling</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1297</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> index = exception.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">';'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1298</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> oldIndex = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1299</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (-1 != index) </span><span class="doxyHighlightComment">// there should be no more than 2 (set / get)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1300</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1301</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// omit '{' and ';' -&gt; "set raises (...)"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1302</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a25431a65b263de7827454ea81eb8be29">writeExceptionListImpl</a>(ol,cd,md,exception.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(oldIndex,index-oldIndex));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1303</span><span class="doxyLineContent"><span class="doxyHighlight">      oldIndex=index+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1304</span><span class="doxyLineContent"><span class="doxyHighlight">      index = exception.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">';'</span><span class="doxyHighlight">,oldIndex);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1305</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1306</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// the rest is now just '}' - omit that</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1307</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1308</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1309</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1310</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a25431a65b263de7827454ea81eb8be29">writeExceptionListImpl</a>(ol,cd,md,exception);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1311</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1312</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a2f94a19fd2121d155de4865cf7c2fa81">MemberDef::excpString</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a> and <a href="#a25431a65b263de7827454ea81eb8be29">writeExceptionListImpl</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>.
</div>
</div>

### writeExceptionListImpl() {#a25431a65b263de7827454ea81eb8be29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeExceptionListImpl (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> const &amp; exception)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l01252">1252</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a25431a65b263de7827454ea81eb8be29">1252</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a25431a65b263de7827454ea81eb8be29">writeExceptionListImpl</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1253</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight">&amp; exception)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1254</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1255</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// this is ordinary exception spec - there must be a '('</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1256</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("exception='%s'\n",qPrint(exception));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1257</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> index = exception.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1258</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1259</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1260</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a60a7f30e2f0edb92bd5ce06d1259340f">exceptionEntry</a>(exception.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(index),</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1261</span><span class="doxyLineContent"><span class="doxyHighlight">    ++index; </span><span class="doxyHighlightComment">// paren in second column so skip it here</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1262</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> comma = exception.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">','</span><span class="doxyHighlight">, index); comma!=-1; )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1263</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1264</span><span class="doxyLineContent"><span class="doxyHighlight">      ++comma; </span><span class="doxyHighlightComment">// include comma</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1265</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a>(<a href="/web-doxygen/docs/api/classes/textgeneratorolimpl">TextGeneratorOLImpl</a>(ol),cd,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a7ea253be90981d4a6f0cfdb6dff1d2fd">getBodyDef</a>(),md,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1266</span><span class="doxyLineContent"><span class="doxyHighlight">                  exception.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(index,comma-index));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1267</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a60a7f30e2f0edb92bd5ce06d1259340f">exceptionEntry</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1268</span><span class="doxyLineContent"><span class="doxyHighlight">      index=comma;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1269</span><span class="doxyLineContent"><span class="doxyHighlight">      comma = exception.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">','</span><span class="doxyHighlight">, index);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1270</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1271</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> close = exception.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">, index);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1272</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (close!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1273</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1274</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> type=<a href="/web-doxygen/docs/api/files/src/util-cpp/#a0940360aa6d41fd2496603fc565e3996">removeRedundantWhiteSpace</a>(exception.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(index,close-index));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1275</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a>(<a href="/web-doxygen/docs/api/classes/textgeneratorolimpl">TextGeneratorOLImpl</a>(ol),cd,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a7ea253be90981d4a6f0cfdb6dff1d2fd">getBodyDef</a>(),md,type);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1276</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a60a7f30e2f0edb92bd5ce06d1259340f">exceptionEntry</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1277</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1278</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1279</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1280</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>(),md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1281</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"missing ) in exception list on member {}"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1282</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1283</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1284</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// Java Exception</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1285</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1286</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1287</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a>(<a href="/web-doxygen/docs/api/classes/textgeneratorolimpl">TextGeneratorOLImpl</a>(ol),cd,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a7ea253be90981d4a6f0cfdb6dff1d2fd">getBodyDef</a>(),md,exception);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1288</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1289</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">OutputList::docify</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a60a7f30e2f0edb92bd5ce06d1259340f">OutputList::exceptionEntry</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/definition/#a7ea253be90981d4a6f0cfdb6dff1d2fd">Definition::getBodyDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">Definition::getDefFileName</a>, <a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">Definition::getDefLine</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a0940360aa6d41fd2496603fc565e3996">removeRedundantWhiteSpace</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.

Referenced by <a href="#a158781f51faf723e59ca681487e4da1a">writeExceptionList</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### g&#95;cachedAnonymousTypeMutex {#a961ae6d2d358b27f1898087008b186fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex g_cachedAnonymousTypeMutex</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l01967">1967</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a961ae6d2d358b27f1898087008b186fa">1967</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::mutex <a href="#a961ae6d2d358b27f1898087008b186fa">g_cachedAnonymousTypeMutex</a>;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a371cb64a5cbed0c787cec472f0b04857">MemberDefImpl::getClassDefOfAnonymousType</a>.
</div>
</div>

### g&#95;detectUndocumentedParamsMutex {#a8e711cc7ca7ab729f5b8e1d81d88cf53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex g_detectUndocumentedParamsMutex</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l04182">4182</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8e711cc7ca7ab729f5b8e1d81d88cf53">4182</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::mutex <a href="#a8e711cc7ca7ab729f5b8e1d81d88cf53">g_detectUndocumentedParamsMutex</a>;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ac0e3122b4e6e26ee38ef45f59aaecf05">MemberDefImpl::detectUndocumentedParams</a>.
</div>
</div>

### g&#95;docCrossReferenceMutex {#a6ec17e0e1fa9fc5b2ab522f618f39b88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex g_docCrossReferenceMutex</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l06397">6397</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6ec17e0e1fa9fc5b2ab522f618f39b88">6397</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::mutex <a href="#a6ec17e0e1fa9fc5b2ab522f618f39b88">g_docCrossReferenceMutex</a>;</span></span></div>

</div>


Referenced by <a href="#a91959a7c929a76adaaa2d342fea73126">addDocCrossReference</a>.
</div>
</div>

### g&#95;hasDetailedDescriptionMutex {#a62bb009cd0c5ff54af5146380fd18f05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex g_hasDetailedDescriptionMutex</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l02654">2654</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a62bb009cd0c5ff54af5146380fd18f05">2654</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::mutex <a href="#a62bb009cd0c5ff54af5146380fd18f05">g_hasDetailedDescriptionMutex</a>;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a4e1a986cedbc4e480499acefaf503cb7">MemberDefImpl::hasDetailedDescription</a>.
</div>
</div>

### reAnonymous {#afaa6100850ded3f073682450f105d7eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const reg::Ex reAnonymous(R"([\w:@]*@\d+)")</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l03286">3286</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#afe264a9e05a22242d446830b72b203da">MemberDefImpl::displayDefinition</a> and <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>.
</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
