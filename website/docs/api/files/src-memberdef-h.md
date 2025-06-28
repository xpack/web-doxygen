---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/memberdef-h
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `memberdef.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;vector&gt;
#include &lt;memory&gt;
#include &lt;optional&gt;
#include &lt;sys/types.h&gt;
#include "<a href="/web-doxygen/docs/api/files/src/types-h">types.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/definition-h">definition.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A model of a class/file/namespace member symbol. <a href="/web-doxygen/docs/api/classes/memberdef/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afeba76c8d08f22f1e9a25423b9c5666c">toMemberDef</a> (DefinitionMutable *d)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6a75072e4ea30dec588141d8e7fe2be">addDocCrossReference</a> (const MemberDef *src, const MemberDef *dst)</td>
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

### addDocCrossReference() {#ac6a75072e4ea30dec588141d8e7fe2be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addDocCrossReference (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * src, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * dst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="#l00457">457</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#l06399">6399</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a91959a7c929a76adaaa2d342fea73126">6399</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a91959a7c929a76adaaa2d342fea73126">addDocCrossReference</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *s,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6400</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6401</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *src = <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>(</span><span class="doxyHighlightKeyword">const_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(s));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6402</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *dst = <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>(</span><span class="doxyHighlightKeyword">const_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(d));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6403</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (src==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> || dst==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6404</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("--&gt; addDocCrossReference src=%s,dst=%s\n",qPrint(src-&gt;name()),qPrint(dst-&gt;name()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6405</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (dst-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a4bd8f9b14007a57f53918a21258c284e">isTypedef</a>() || dst-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ab99e728441f3ce7d5784ad6fb6df18f2">isEnumerate</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// don't add types</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6406</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((dst-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#abc1862f5e87a67541a4c40403a95fd81">hasReferencedByRelation</a>() || dst-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a9e0b1dcd40b111eea088027193c2e411">hasCallerGraph</a>()) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6407</span><span class="doxyLineContent"><span class="doxyHighlight">      src-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#af589ca13a0dec56fb92038c9b2488208">isCallable</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6408</span><span class="doxyLineContent"><span class="doxyHighlight">     )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6409</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6410</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> sourceRefName = src-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a64c6a04cf0c6d2ebf56ed6959ce1f89d">sourceRefName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6411</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *mdDef = <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>(dst-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a0b88c6841076c450863bc9b57e5068d1">memberDefinition</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6412</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *mdDecl = <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>(dst-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a160b1eb96684b652bd0611e78d8fe831">memberDeclaration</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6413</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6414</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// ---- critical section</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6415</span><span class="doxyLineContent"><span class="doxyHighlight">    std::lock_guard&lt;std::mutex&gt; lock(<a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a6ec17e0e1fa9fc5b2ab522f618f39b88">g_docCrossReferenceMutex</a>);</span></span></div>
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
<div class="doxyCodeLine"><span class="doxyLineNumber">6432</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *mdDef = <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>(src-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a0b88c6841076c450863bc9b57e5068d1">memberDefinition</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6433</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *mdDecl = <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>(src-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a160b1eb96684b652bd0611e78d8fe831">memberDeclaration</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6434</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6435</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// ---- critical section</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6436</span><span class="doxyLineContent"><span class="doxyHighlight">    std::lock_guard&lt;std::mutex&gt; lock(<a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a6ec17e0e1fa9fc5b2ab522f618f39b88">g_docCrossReferenceMutex</a>);</span></span></div>
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


References <a href="/web-doxygen/docs/api/classes/definitionmutable/#aec0335ad9b4dc58dea457a3229bbaacb">DefinitionMutable::addSourceReferencedBy</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#a6a9e0c7716f37652c8c0e0206032b76d">DefinitionMutable::addSourceReferences</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a6ec17e0e1fa9fc5b2ab522f618f39b88">g&#95;docCrossReferenceMutex</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a9e0b1dcd40b111eea088027193c2e411">MemberDef::hasCallerGraph</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a4f8eeb9656c15d74956b893e5cef255d">MemberDef::hasCallGraph</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#abc1862f5e87a67541a4c40403a95fd81">MemberDef::hasReferencedByRelation</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a3aedaf487c755d4749b10fa95729a2af">MemberDef::hasReferencesRelation</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#af589ca13a0dec56fb92038c9b2488208">MemberDef::isCallable</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#ab99e728441f3ce7d5784ad6fb6df18f2">MemberDef::isEnumerate</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a4bd8f9b14007a57f53918a21258c284e">MemberDef::isTypedef</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a160b1eb96684b652bd0611e78d8fe831">MemberDef::memberDeclaration</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a0b88c6841076c450863bc9b57e5068d1">MemberDef::memberDefinition</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a64c6a04cf0c6d2ebf56ed6959ce1f89d">MemberDef::sourceRefName</a> and <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/pycode-l/#a767fe9c8dd14640cc99a6f1c9e0981c7">findMemberLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ada294ec0d3d5d40d4bb74d5624c886d4">generateClassMemberLink</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a080345cfde4ece732f42ded5413ea957">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a3345ad9e2ab3a9d1b524391ae5f6c545">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#ac240a5eb77b55528937ec68a24cf4f46">getLink</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#aa3a78394ea3d7dee51703f8f0c1e3984">getLinkInScope</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a7c3e45cceb9eb4446d360eb8620eef8c">getLinkInScope</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#addab8233ce94a53e33f788e02e453790">MemberDefMutable::setFromAnonymousScope</a> and <a href="/web-doxygen/docs/api/files/src/code-l/#af2995da196faa8940cca40cfc158b9aa">writeObjCMethodCall</a>.
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


<p>Declaration at line <a href="#l00456">456</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#l06165">6165</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#abaf3303e28a7a9e34bdcfbe4bfc893cb">6165</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#abaf3303e28a7a9e34bdcfbe4bfc893cb">combineDeclarationAndDefinition</a>(<a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *mdec,<a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *mdef)</span></span></div>
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
<div class="doxyCodeLine"><span class="doxyLineNumber">6193</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a916ded3150c496785b98bbd5c2bee442">transferArgumentDocumentation</a>(mdecAl,mdefAl);</span></span></div>
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
<div class="doxyCodeLine"><span class="doxyLineNumber">6212</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a916ded3150c496785b98bbd5c2bee442">transferArgumentDocumentation</a>(mdefAl,*mdefAlComb);</span></span></div>
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
<div class="doxyCodeLine"><span class="doxyLineNumber">6224</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a916ded3150c496785b98bbd5c2bee442">transferArgumentDocumentation</a>(mdecAl,*mdecAlComb);</span></span></div>
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


References <a href="/web-doxygen/docs/api/classes/memberdefmutable/#ab0dd3d7e2e5060662bac9dacc0c8bc0c">MemberDefMutable::addQualifiers</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">MemberDef::argsString</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">MemberDef::argumentList</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO&#95;TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO&#95;TRACE&#95;ADD</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">Definition::briefDescription</a>, <a href="/web-doxygen/docs/api/classes/definition/#ac74d77550941a8f568ea56fecc30c873">Definition::briefFile</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8073d399d39c43e66a4b487b3e06ade1">Definition::briefLine</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/classes/definition/#a00915f52f3b708bec07aab2b44f03d34">Definition::docFile</a>, <a href="/web-doxygen/docs/api/classes/definition/#a26a4a6e3578aa6c81b2d6d77a1ce694f">Definition::docLine</a>, <a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">Definition::documentation</a>, <a href="/web-doxygen/docs/api/classes/definition/#a7ea253be90981d4a6f0cfdb6dff1d2fd">Definition::getBodyDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">Definition::getDefLine</a>, <a href="/web-doxygen/docs/api/classes/definition/#a0b5313ad11f50b2d056fc62d81db0433">Definition::getEndBodyLine</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a5036fd8ee16b186925236105029ee823">MemberDef::getFileDef</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a43566d882fc7994385bbdaf7fe927e67">MemberDef::getGroupDef</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a9ed95e7cef3948c6a978540c0d48bca7">MemberDef::getGroupPri</a>, <a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">Definition::getLanguage</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#ab3e5d2e532ebe2a0f45fe1a945fb4269">MemberDef::getMemberSpecifiers</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">Definition::getOuterScope</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a78ea63aa23ada7ecd6d8c59163c3dadf">MemberDef::getQualifiers</a>, <a href="/web-doxygen/docs/api/classes/definition/#ad63d39480ae9ec4e71bedbb749d16a4c">Definition::getStartBodyLine</a>, <a href="/web-doxygen/docs/api/classes/definition/#a81f5c355e27d6e159e1598be748aa4de">Definition::hasDocumentation</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#a2ed5c45b3909206446aaac4f1ab6d640">ArgumentList::hasParameters</a>, <a href="/web-doxygen/docs/api/classes/definition/#af59473951772c62b9db328e342fc2198">Definition::inbodyDocumentation</a>, <a href="/web-doxygen/docs/api/classes/definition/#af6fd6ee64e4e2599c1cb7cba93897aa7">Definition::inbodyFile</a>, <a href="/web-doxygen/docs/api/classes/definition/#a74cb27736839a0e602ef5fa9bbb9deab">Definition::inbodyLine</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a842ff86c34c3ae387d995e2597be8118">MemberDef::isDocsForDefinition</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a62a3294a87e2a6e2ff4a2d52bfd3187a">MemberDef::isExternal</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a5e6ace25ee464a601e1b3f2b8016ddad">MemberDef::isFunction</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#afa756b712f45e7800617808f708c2876">MemberDef::isPrototype</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a73354ecea5b876ab8d59724b080189b4">MemberDef::isStatic</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#ad7b6f788b487058e9e6ac65b092479b9">MemberDef::isVariable</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a78739b1ab728bbecd4d3e54ae90bbbce">matchArguments2</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aaeb66f0aa57917b9aff55be8d61cc8c2">mergeMemberOverrideOptions</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#ab0caddb69ae9c8c18e57ee452791f483">MemberDefMutable::mergeMemberSpecifiers</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#ac9954b7f44ce715872d177b25966e13d">DefinitionMutable::mergeRefItems</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#ae6b8b985f4a543215a25b698a28f4dfc">MemberDefMutable::moveArgumentList</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#ac1b97bdbdbe63513549b7f1585187f65">MemberDefMutable::moveDeclArgumentList</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#a3dc3cdf4626a0d405580d45a907f1719">MemberDefMutable::resolveUnnamedParameters</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#acebfd2c89008fa8ef42c9ab9bf61d4b7">DefinitionMutable::setBodyDef</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#a21f0601d0ac0f9d245c7a40e28adc3c6">DefinitionMutable::setBodySegment</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#ae704468ccbae4cbc26922db573676feb">DefinitionMutable::setBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#a8b1c18e7f7a27c2661cac096a24e2602">MemberDefMutable::setDocsForDefinition</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#a5115744bf4595f9a08a193dd41d4f4c3">DefinitionMutable::setDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#ac1ea8d9adeeef3466a0b36b20aa8ca8e">MemberDefMutable::setGroupDef</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#a8a4d82f0315802612dcd9732369eaa8a">DefinitionMutable::setInbodyDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#a2701750e59071fffc3d5dddbb59cf6a7">MemberDefMutable::setMemberDeclaration</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#ac6cc1fb03bddb3993a6b3fd8c7df75ef">MemberDefMutable::setMemberDefinition</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#a4d651caeb995400fad17d4ab4a020a3a">ArgumentList::size</a>, <a href="/web-doxygen/docs/api/files/src/defargs-h/#a88825bfb79a9c15e54ff57415b4de54d">stringToArgumentList</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a409da33c248938e57ba2135777a38628">MemberDef::templateArguments</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a916ded3150c496785b98bbd5c2bee442">transferArgumentDocumentation</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

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

<p>Declaration at line <a href="#l00448">448</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#l00516">516</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#afc503b94aed5230ca07d22e743e9c800">516</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::unique_ptr&lt;MemberDef&gt; <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#afc503b94aed5230ca07d22e743e9c800">createMemberDef</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;defFileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> defLine,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> defColumn,</span></span></div>
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


<p>Declaration at line <a href="#l00454">454</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#l00966">966</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a792961c33915b95213d78c7366c9dcb3">966</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::unique_ptr&lt;MemberDef&gt; <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a792961c33915b95213d78c7366c9dcb3">createMemberDefAlias</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *newScope,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *aliasMd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">967</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">968</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> amd = std::make_unique&lt;MemberDefAliasImpl&gt;(newScope,aliasMd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">969</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("amd: name=%s displayName=%s\n",qPrint(amd-&gt;name()),qPrint(amd-&gt;displayName()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">970</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> amd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">971</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a304d98a7f2677037f3ca7f4a3efd73ed">MemberDefAliasImpl::deepCopy</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ad1c6c890ed8e8ebcfe057f3de5db4fcb">NamespaceDefImpl::insertMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a02e748da779cf061b14c27d976efdb65">insertMemberAlias</a> and <a href="/web-doxygen/docs/api/classes/memberdefmutable/#addab8233ce94a53e33f788e02e453790">MemberDefMutable::setFromAnonymousScope</a>.
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


<p>Declaration at line <a href="#l00439">439</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#l06452">6452</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">6452</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *<a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>(<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
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

### toMemberDef() {#afeba76c8d08f22f1e9a25423b9c5666c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemberDef * toMemberDef (<a href="/web-doxygen/docs/api/classes/definitionmutable">DefinitionMutable</a> * d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="#l00440">440</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#l06464">6464</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#aadf8d5c103d1bd6ff91c784f02ebe2dd">6464</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *<a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>(<a href="/web-doxygen/docs/api/classes/definitionmutable">DefinitionMutable</a> *md)</span></span></div>
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


<p>Declaration at line <a href="#l00441">441</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#l06477">6477</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#aac062c9356229664b77d347ac8cc94d0">6477</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *<a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
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


<p>Declaration at line <a href="#l00442">442</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#l06489">6489</a> of file <a href="/web-doxygen/docs/api/files/src/memberdef-cpp">memberdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a9ea80ba313803ae565f05ce1c8eb6bb5">6489</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *<a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>(<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
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


Referenced by <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a91959a7c929a76adaaa2d342fea73126">addDocCrossReference</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a636b9cfb60b78163bb29dbb6f21def29">addEnumValuesToEnums</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a95106cfe8d0c8504016e0714ae0e10f7">addGlobalFunction</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ab534a27eef617922af2a5d7baafffcae">addInstance</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7ba474a85367760e0e849c9732d5fa26">addInterfaceOrServiceToServiceOrSingleton</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a332043aa0d664d063e7fcc0614acbeea">MemberList::addListReferences</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5c29617e942b0f91f94f5b362cb2fa67">addLocalObjCMethod</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ae11c2fb2e5b6cbe3dcd1a1b594406e93">addMemberSpecialization</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a629f6fc7b319c74df28381ca2e009d0b">addMembersToMemberGroup</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#affd271e102af38c14812ccc21a86401c">addMemberToGroups</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a0b89a353206730e5f1ce65366c49f92f">ClassDefImpl::addMemberToList</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a3e2d8e1f9b98e5cecd9414d91cb82085">FileDefImpl::addMemberToList</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a9ebc186b5b7ace2541d5e51ff8f26da1">ModuleDefImpl::addMemberToList</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a401c44767708d6a589a4b50891c3f435">NamespaceDefImpl::addMemberToList</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a3ac0043018354a90b2ce4cba4413f606">ModuleDefImpl::addMemberToModule</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a8eaf52205769b3910d40de52c5eefd51">ModuleManager::addMemberToModule</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a1f7c3408ea1bf71c19a8e593763d88f7">ClassDefImpl::addMemberToTemplateInstance</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad736f00784a47fe1c1bf6317f9a1b51b">addMethodToClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a45b876ed6758069be1442e9cbae2bbd0">addOverloaded</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f2a35ddd84e986afdbc14dcba2bcf3c">addVariableToClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a704656a4d637d9f99c1adef34aafe856">addVariableToFile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#afb0da87d7d3ab2047204073d584974ad">buildDefineList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a568741e989fcbe6cd20c1295cf9c7aed">buildTypedefList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#afee2d528ad3660fd6ab8de9e42ac6752">computeMemberRelationsForBaseClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad4d18463536d31e211957c9151fdbac2">createTagLessInstance</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a582f332d778bad3d6e991a75a2448d06">MemberDefImpl::createTemplateInstanceMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1ba016192f46b348d5dbc66f8f574380">createUsingMemberImportForClass</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7a05059f489e3c94d51aa47127ccdfed">ClassDefImpl::deepCopy</a>, <a href="/web-doxygen/docs/api/classes/membergroup/#a7814e5796402b44a7ee813a2bd5c23eb">MemberGroup::distributeMemberGroupDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a589e3e52c7dc0599e7342171a7531064">findDefineDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a10e11a9d8c5f3fc3b78bc02ebe04380c">findDEV</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab97b7f9be435590df65d9bb0d31fba06">findEnumDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a82770a95f2aebec7ffee2162e3a67215">findEnums</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a825f829ad3f2e4e1a52d8959b0ff3fb9">findFriends</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5dc8c4afa4009560979330b7c6fb2cb3">findGlobalMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#ad095317a533d0e4d883e286a5599746d">MemberList::findSectionsInDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a082d23658541704d3493a7a881583d55">flushCachedTemplateRelations</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#aad3dd00ae1c58bfc06981afcc5f14a53">flushUnresolvedRelations</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ada294ec0d3d5d40d4bb74d5624c886d4">generateClassMemberLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a3345ad9e2ab3a9d1b524391ae5f6c545">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a7c3e45cceb9eb4446d360eb8620eef8c">getLinkInScope</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7c714f2eedf0d52d8428bbcdd06b6975">ClassDefImpl::hideDerivedVariablesInPython</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a4e0a7985a36e2f35ba21be58c8285f02">incrementFlowKeyWordCount</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a4e0a7985a36e2f35ba21be58c8285f02">incrementFlowKeyWordCount</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#aad23f7d576fcba6cc66edf702842a9d3">inheritDocumentation</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a8741a4a807c8e1808f82c08f00152a2f">GroupDefImpl::insertMember</a>, <a href="/web-doxygen/docs/api/classes/membergroup/#ad7b02bac5d0ed254d5c979b19cf4ae1e">MemberGroup::insertMember</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ad1c6c890ed8e8ebcfe057f3de5db4fcb">NamespaceDefImpl::insertMember</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a04d8bdd0ceb3b8cb7ec8cf64e4731ed7">MemberDefImpl::insertReimplementedBy</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a443122a21e609582f590173accd789a1">ClassDefImpl::mergeCategory</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a39bb7d9a1e431158cb3a423215f044bb">processTagLessClasses</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#ae626c9e633e5efcf3476b1c7c847d06b">MemberList::setAnchors</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a663e4dedf84ec20ab0b682c0c762647e">MemberList::setAnonymousEnumType</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#addab8233ce94a53e33f788e02e453790">MemberDefMutable::setFromAnonymousScope</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#aa8cd9bab78377e9d6719c0b77ff07120">ClassDefImpl::setGroupDefForAllMembers</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a4ee52c8be189a58fdf71cac6164f6be1">transferFunctionDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#af9f9567b822b1cbc46ff46b5a310ceab">transferFunctionReferences</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a42120760d9d3f1ffe7d1561ef7b50a49">transferRelatedFunctionDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5234f1896d9c47e7836c34e3b03a36b0">transferStaticInstanceInitializers</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a4299844cb805de324387ae0072ea6e9d">tryAddEnumDocsToGroupMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3d2bdb9a2c2b81909c7835cece01d448">vhdlCorrectMemberProperties</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#aa86fa71c504d7676073931dcca08f3dc">MemberList::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#af29c795d264e74de8cc53f3d5c550d41">MemberList::writeDocumentationPage</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#afc394d10d64e221682e9619eef74fde5">VhdlDocGen::writePlainVHDLDeclarations</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a8cab5da1323054e47ede48e03a1420a2">MemberList::writeSimpleDocumentation</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a1c145b8082cd9865b477141ab58dcb20">VhdlDocGen::writeSource</a> and <a href="/web-doxygen/docs/api/classes/memberlist/#a20813d8313b4dfdb5a6625efc4e989ef">MemberList::writeTagFile</a>.
</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
