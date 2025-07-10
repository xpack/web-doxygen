---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/symbolresolver
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SymbolResolver` Class Reference



## Declaration

<div class="doxyDeclaration">
class SymbolResolver { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/symbolresolver-h">src/symbolresolver.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fb03bff243edd7ac4967ff3669b8301">SymbolResolver</a> (const FileDef *fileScope=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40f6b85e30e458772ef6c5534344b0d5">~SymbolResolver</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d24640728b220c0b98554dbc7aa9d5f">resolveClass</a> (const Definition *scope, const QCString &amp;name, bool maybeUnlinkable=false, bool mayBeHidden=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the class definition matching name within the scope set. <a href="#a7d24640728b220c0b98554dbc7aa9d5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/classdefmutable">ClassDefMutable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3249c001539f0f9de46a3ec8098fbea">resolveClassMutable</a> (const Definition *scope, const QCString &amp;name, bool mayBeUnlinkable=false, bool mayBeHidden=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wrapper around resolveClass that returns a mutable interface to the class object or a nullptr if the symbol is immutable. <a href="#ab3249c001539f0f9de46a3ec8098fbea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a739c707d2150c5b2115fa731694eaeec">resolveSymbol</a> (const Definition *scope, const QCString &amp;name, const QCString &amp;args=QCString(), bool checkCV=false, bool insideCode=false, bool onlyLinkable=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the symbool definition matching name within the scope set. <a href="#a739c707d2150c5b2115fa731694eaeec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d50ab34b5f003b3ee4c1283a414eca0">isAccessibleFrom</a> (const Definition *scope, const Definition *item)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if symbol <em>item</em> is accessible from within <em>scope</em>. <a href="#a2d50ab34b5f003b3ee4c1283a414eca0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63c2a4c6c16e4b5f9f527ab147c0ea2e">isAccessibleFromWithExpScope</a> (const Definition *scope, const Definition *item, const QCString &amp;explicitScopePart)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if symbol <em>item</em> is accessible from within <em>scope</em>, where it has to match the <em>explicitScopePart</em>. <a href="#a63c2a4c6c16e4b5f9f527ab147c0ea2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accc9cb1dfddba4432265a175e5875d55">setFileScope</a> (const FileDef *fd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets or updates the file scope using when resolving symbols. <a href="#accc9cb1dfddba4432265a175e5875d55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae434934a4e3459b50310c2a1dc9dd17b">getTypedef</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>In case a call to <a href="#a7d24640728b220c0b98554dbc7aa9d5f">resolveClass()</a> resolves to a type member (e.g. <a href="#ae434934a4e3459b50310c2a1dc9dd17b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82dea93383a1eeb7005e54e013358ee0">getTemplateSpec</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>In case a call to <a href="#a7d24640728b220c0b98554dbc7aa9d5f">resolveClass()</a> points to a template specialization, the template part is return via this method. <a href="#a82dea93383a1eeb7005e54e013358ee0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f023b174a5e9064fb4afdf69a02f284">getResolvedType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>In case a call to <a href="#a7d24640728b220c0b98554dbc7aa9d5f">resolveClass()</a> points to a typedef or using declaration. <a href="#a6f023b174a5e9064fb4afdf69a02f284">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/symbolresolver/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74d53555d942680120e24d2a54022fe0">p</a></td>
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



<p>Helper class to find a class definition or check if A symbol is accessible in a given scope.</p>


<p>Definition at line 31 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-h">symbolresolver.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SymbolResolver() {#a7fb03bff243edd7ac4967ff3669b8301}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolResolver::SymbolResolver (const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fileScope=nullptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 34 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-h">symbolresolver.h</a>, definition at line 1606 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7fb03bff243edd7ac4967ff3669b8301">1606</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a7fb03bff243edd7ac4967ff3669b8301">SymbolResolver::SymbolResolver</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fileScope)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1607</span><span class="doxyLineContent"><span class="doxyHighlight">  : <a href="#a74d53555d942680120e24d2a54022fe0">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/structs/symbolresolver/private">Private</a>&gt;(fileScope))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1608</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1609</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a74d53555d942680120e24d2a54022fe0">p</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SymbolResolver() {#a40f6b85e30e458772ef6c5534344b0d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolResolver::~SymbolResolver ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 35 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-h">symbolresolver.h</a>, definition at line 1611 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a40f6b85e30e458772ef6c5534344b0d5">1611</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a40f6b85e30e458772ef6c5534344b0d5">SymbolResolver::~SymbolResolver</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1612</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1613</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getResolvedType() {#a6f023b174a5e9064fb4afdf69a02f284}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString SymbolResolver::getResolvedType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>In case a call to <a href="#a7d24640728b220c0b98554dbc7aa9d5f">resolveClass()</a> points to a typedef or using declaration.</p>


<p>The type name it resolved to is returned via this method.</p>


<p>Declaration at line 116 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-h">symbolresolver.h</a>, definition at line 1726 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6f023b174a5e9064fb4afdf69a02f284">1726</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a6f023b174a5e9064fb4afdf69a02f284">SymbolResolver::getResolvedType</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1727</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1728</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a74d53555d942680120e24d2a54022fe0">p</a>-&gt;resolvedType;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1729</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a74d53555d942680120e24d2a54022fe0">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab2ea86daea5714c6e35d4ddc62777790">getCanonicalTypeForIdentifier</a> and <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a3aea62dc3d2f6c0e0109e5aefc155a41">SymbolResolver::Private::getResolvedTypeRec</a>.</p>

</div>
</div>

### getTemplateSpec() {#a82dea93383a1eeb7005e54e013358ee0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString SymbolResolver::getTemplateSpec ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>In case a call to <a href="#a7d24640728b220c0b98554dbc7aa9d5f">resolveClass()</a> points to a template specialization, the template part is return via this method.</p>

<p>Declaration at line 111 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-h">symbolresolver.h</a>, definition at line 1721 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a82dea93383a1eeb7005e54e013358ee0">1721</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a82dea93383a1eeb7005e54e013358ee0">SymbolResolver::getTemplateSpec</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1722</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1723</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a74d53555d942680120e24d2a54022fe0">p</a>-&gt;templateSpec;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1724</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a74d53555d942680120e24d2a54022fe0">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2855c4f3905bf9bd629622f65075b558">findClassRelation</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab2ea86daea5714c6e35d4ddc62777790">getCanonicalTypeForIdentifier</a>.</p>

</div>
</div>

### getTypedef() {#ae434934a4e3459b50310c2a1dc9dd17b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MemberDef * SymbolResolver::getTypedef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>In case a call to <a href="#a7d24640728b220c0b98554dbc7aa9d5f">resolveClass()</a> resolves to a type member (e.g.</p>


<p>an enum) this method will return it.</p>


<p>Declaration at line 106 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-h">symbolresolver.h</a>, definition at line 1716 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae434934a4e3459b50310c2a1dc9dd17b">1716</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *<a href="#ae434934a4e3459b50310c2a1dc9dd17b">SymbolResolver::getTypedef</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1717</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1718</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a74d53555d942680120e24d2a54022fe0">p</a>-&gt;typeDef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1719</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a74d53555d942680120e24d2a54022fe0">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2855c4f3905bf9bd629622f65075b558">findClassRelation</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab2ea86daea5714c6e35d4ddc62777790">getCanonicalTypeForIdentifier</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a>.</p>

</div>
</div>

### isAccessibleFrom() {#a2d50ab34b5f003b3ee4c1283a414eca0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int SymbolResolver::isAccessibleFrom (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * scope, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * item)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if symbol <em>item</em> is accessible from within <em>scope</em>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>-1 if <em>item</em> is not accessible or a number indicating how many scope levels up the nearest match was found.</p></dd>
</dl>


<p>Declaration at line 85 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-h">symbolresolver.h</a>, definition at line 1685 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2d50ab34b5f003b3ee4c1283a414eca0">1685</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a2d50ab34b5f003b3ee4c1283a414eca0">SymbolResolver::isAccessibleFrom</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *scope,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *item)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1686</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1687</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"scope={} item={}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1688</span><span class="doxyLineContent"><span class="doxyHighlight">      scope?scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), item?item-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1689</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a74d53555d942680120e24d2a54022fe0">p</a>-&gt;reset();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1690</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a62fc03f5f79aa6176eb0cb02cb054ac9">VisitedKeys</a> visitedKeys;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1691</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/accessstack">AccessStack</a> accessStack;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1692</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> result = <a href="#a74d53555d942680120e24d2a54022fe0">p</a>-&gt;isAccessibleFrom(visitedKeys,accessStack,scope,item);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1693</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1694</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1695</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a> and <a href="#a74d53555d942680120e24d2a54022fe0">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a60ffd0b23680e5318865a367b0d26871">SymbolResolver::Private::isAccessibleFrom</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a01a031ffd0a93eb06668c1e93fb57f69">SymbolResolver::Private::isAccessibleFromWithExpScope</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7970104534296194ccd535117234a682">resolveTypeDef</a>.</p>

</div>
</div>

### isAccessibleFromWithExpScope() {#a63c2a4c6c16e4b5f9f527ab147c0ea2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int SymbolResolver::isAccessibleFromWithExpScope (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * scope, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * item, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; explicitScopePart)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if symbol <em>item</em> is accessible from within <em>scope</em>, where it has to match the <em>explicitScopePart</em>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>-1 if <em>item</em> is not accessible or a number indicating how many scope levels up the nearest match was found.</p></dd>
</dl>


<p>Declaration at line 93 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-h">symbolresolver.h</a>, definition at line 1697 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a63c2a4c6c16e4b5f9f527ab147c0ea2e">1697</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a63c2a4c6c16e4b5f9f527ab147c0ea2e">SymbolResolver::isAccessibleFromWithExpScope</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *scope,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *item,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1698</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;explicitScopePart)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1699</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1700</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"scope={} item={} explicitScopePart={}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1701</span><span class="doxyLineContent"><span class="doxyHighlight">      scope?scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), item?item-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), explicitScopePart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1702</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a74d53555d942680120e24d2a54022fe0">p</a>-&gt;reset();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1703</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a62fc03f5f79aa6176eb0cb02cb054ac9">VisitedKeys</a> visitedKeys;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1704</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a589f084c907127f8eb7da515347f2bc4">VisitedNamespaces</a> visitedNamespaces;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1705</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/accessstack">AccessStack</a> accessStack;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1706</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> result = <a href="#a74d53555d942680120e24d2a54022fe0">p</a>-&gt;isAccessibleFromWithExpScope(visitedKeys,visitedNamespaces,accessStack,scope,item,explicitScopePart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1707</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1708</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1709</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a> and <a href="#a74d53555d942680120e24d2a54022fe0">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5ecfe67024087367b33d18430021a3c0">getMemberFromSymbol</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a40f0f9c9cb6b6b7392ae6e695fc74671">SymbolResolver::Private::getResolvedSymbol</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#aef9c4245c6f445e282a59005f1f6ca5a">SymbolResolver::Private::getResolvedType</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a01a031ffd0a93eb06668c1e93fb57f69">SymbolResolver::Private::isAccessibleFromWithExpScope</a> and <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a763d03603a7b427c9f02719fb95b2c30">SymbolResolver::Private::substTypedef</a>.</p>

</div>
</div>

### resolveClass() {#a7d24640728b220c0b98554dbc7aa9d5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ClassDef * SymbolResolver::resolveClass (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * scope, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, bool maybeUnlinkable=false, bool mayBeHidden=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the class definition matching name within the scope set.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">scope</td>
<td class="doxyParamItemDescription"><p>The scope to search from.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">name</td>
<td class="doxyParamItemDescription"><p>The name of the symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">maybeUnlinkable</td>
<td class="doxyParamItemDescription"><p>include unlinkable symbols in the search.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">mayBeHidden</td>
<td class="doxyParamItemDescription"><p>include hidden symbols in the search.</p></td>
</tr>
</table>
</dd>
</dl>


:::info
<p>As a result of this call the getters <a href="#ae434934a4e3459b50310c2a1dc9dd17b">getTypedef()</a>, <a href="#a82dea93383a1eeb7005e54e013358ee0">getTemplateSpec()</a>, and <a href="#a6f023b174a5e9064fb4afdf69a02f284">getResolvedType()</a> are set as well.</p>
:::


<p>Declaration at line 49 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-h">symbolresolver.h</a>, definition at line 1616 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7d24640728b220c0b98554dbc7aa9d5f">1616</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *<a href="#a7d24640728b220c0b98554dbc7aa9d5f">SymbolResolver::resolveClass</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *scope,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1617</span><span class="doxyLineContent"><span class="doxyHighlight">                                             </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1618</span><span class="doxyLineContent"><span class="doxyHighlight">                                             </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> mayBeUnlinkable,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1619</span><span class="doxyLineContent"><span class="doxyHighlight">                                             </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> mayBeHidden)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1620</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1621</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"scope={} name={} mayBeUnlinkable={} mayBeHidden={}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1622</span><span class="doxyLineContent"><span class="doxyHighlight">      scope?scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), name, mayBeUnlinkable, mayBeHidden);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1623</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a74d53555d942680120e24d2a54022fe0">p</a>-&gt;reset();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1624</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1625</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> lang = scope ? scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">getLanguage</a>() : SrcLangExt::Cpp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1626</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1627</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (scope==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1628</span><span class="doxyLineContent"><span class="doxyHighlight">      (scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()!=<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1629</span><span class="doxyLineContent"><span class="doxyHighlight">       scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()!=<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea35a2dfa1d3ce6c023cbddb4af2cd18bc">Definition::TypeNamespace</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1630</span><span class="doxyLineContent"><span class="doxyHighlight">      ) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1631</span><span class="doxyLineContent"><span class="doxyHighlight">      (name.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">startsWith</a>(</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">)) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1632</span><span class="doxyLineContent"><span class="doxyHighlight">      ((lang==SrcLangExt::Java || lang==SrcLangExt::CSharp) &amp;&amp; <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(name).find(</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">)!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1633</span><span class="doxyLineContent"><span class="doxyHighlight">     )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1634</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1635</span><span class="doxyLineContent"><span class="doxyHighlight">    scope=<a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1636</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1637</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *result=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1638</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(OPTIMIZE_OUTPUT_VHDL))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1639</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1640</span><span class="doxyLineContent"><span class="doxyHighlight">    result = <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a9682735bd2cf0656eaa944f8b3e364a2">getClass</a>(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1641</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1642</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1643</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1644</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a62fc03f5f79aa6176eb0cb02cb054ac9">VisitedKeys</a> visitedKeys;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1645</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> lookupName = lang==SrcLangExt::CSharp ? <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab542c942324f159b79deed8cdca5663a">mangleCSharpGenericName</a>(name) : name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1646</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"lookup={}"</span><span class="doxyHighlight">,lookupName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1647</span><span class="doxyLineContent"><span class="doxyHighlight">    result = <a href="#a74d53555d942680120e24d2a54022fe0">p</a>-&gt;getResolvedTypeRec(visitedKeys,scope,lookupName,&amp;<a href="#a74d53555d942680120e24d2a54022fe0">p</a>-&gt;typeDef,&amp;<a href="#a74d53555d942680120e24d2a54022fe0">p</a>-&gt;templateSpec,&amp;<a href="#a74d53555d942680120e24d2a54022fe0">p</a>-&gt;resolvedType);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1648</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (result==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// for nested classes imported via tag files, the scope may not</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1649</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightComment">// present, so we check the class name directly as well.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1650</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightComment">// See also bug701314</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1651</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1652</span><span class="doxyLineContent"><span class="doxyHighlight">      result = <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a9682735bd2cf0656eaa944f8b3e364a2">getClass</a>(lookupName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1653</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1654</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1655</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!mayBeUnlinkable &amp;&amp; result &amp;&amp; !result-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">isLinkable</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1656</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1657</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!mayBeHidden || !result-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a930740d353cfe143eb9efe0d12b7f938">isHidden</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1658</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1659</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"hiding symbol {}"</span><span class="doxyHighlight">,result-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1660</span><span class="doxyLineContent"><span class="doxyHighlight">      result=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// don't link to artificial/hidden classes unless explicitly allowed</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1661</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1662</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1663</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,result?result-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1664</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1665</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">Definition::definitionType</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a9682735bd2cf0656eaa944f8b3e364a2">getClass</a>, <a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">Definition::getLanguage</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a>, <a href="/web-doxygen/docs/api/classes/definition/#a930740d353cfe143eb9efe0d12b7f938">Definition::isHidden</a>, <a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">Definition::isLinkable</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab542c942324f159b79deed8cdca5663a">mangleCSharpGenericName</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="#a74d53555d942680120e24d2a54022fe0">p</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">QCString::startsWith</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a> and <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea35a2dfa1d3ce6c023cbddb4af2cd18bc">Definition::TypeNamespace</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#aef7ec01b7eb267f9742878e12cbe99cf">findClassDefinition</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a8e0a72feb96a836fa1650fe1b9f1e39a">findClassWithinClassContext</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab2ea86daea5714c6e35d4ddc62777790">getCanonicalTypeForIdentifier</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ac5a5776af3b729d35a46d06054bc84da">isVarWithConstructor</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a11601f7b8b08cb9600482e5dc3bc51c5">normalizeNonTemplateArgumentsInString</a> and <a href="#ab3249c001539f0f9de46a3ec8098fbea">resolveClassMutable</a>.</p>

</div>
</div>

### resolveClassMutable() {#ab3249c001539f0f9de46a3ec8098fbea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClassDefMutable * SymbolResolver::resolveClassMutable (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * scope, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, bool mayBeUnlinkable=false, bool mayBeHidden=false)</td>
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

<p>Wrapper around resolveClass that returns a mutable interface to the class object or a nullptr if the symbol is immutable.</p>

<p>Definition at line 57 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-h">symbolresolver.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab3249c001539f0f9de46a3ec8098fbea">57</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/classdefmutable">ClassDefMutable</a> *<a href="#ab3249c001539f0f9de46a3ec8098fbea">resolveClassMutable</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *scope,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">                                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">                                         </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> mayBeUnlinkable=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">                                         </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> mayBeHidden=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a2d0bf73f7801534e7e2b6e5fc03ed6f5">toClassDefMutable</a>(</span><span class="doxyHighlightKeyword">const_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a7d24640728b220c0b98554dbc7aa9d5f">resolveClass</a>(scope,name,mayBeUnlinkable,mayBeHidden)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a7d24640728b220c0b98554dbc7aa9d5f">resolveClass</a> and <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a2d0bf73f7801534e7e2b6e5fc03ed6f5">toClassDefMutable</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#aa48018d80bff3d0e37cd1ff67c5972f8">ClassDefImpl::addTypeConstraint</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2855c4f3905bf9bd629622f65075b558">findClassRelation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a595b7d13e1597947419c621de298acad">findUsedClassesForClass</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a28c7c96ebabd6ec7cf5c81f01288d1e3">resolveTemplateInstanceInType</a>.</p>

</div>
</div>

### resolveSymbol() {#a739c707d2150c5b2115fa731694eaeec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Definition * SymbolResolver::resolveSymbol (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * scope, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; args=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), bool checkCV=false, bool insideCode=false, bool onlyLinkable=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the symbool definition matching name within the scope set.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">scope</td>
<td class="doxyParamItemDescription"><p>The scope to search from.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">name</td>
<td class="doxyParamItemDescription"><p>The name of the symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">args</td>
<td class="doxyParamItemDescription"><p><a href="/web-doxygen/docs/api/structs/argument">Argument</a> list associated with the symbol (for functions)</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">checkCV</td>
<td class="doxyParamItemDescription"><p>Check const/volatile qualifiers (for methods)</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">insideCode</td>
<td class="doxyParamItemDescription"><p>Is the symbol found in a code fragment</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">onlyLinkable</td>
<td class="doxyParamItemDescription"><p>Only search linkable definitions</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 73 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-h">symbolresolver.h</a>, definition at line 1667 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a739c707d2150c5b2115fa731694eaeec">1667</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *<a href="#a739c707d2150c5b2115fa731694eaeec">SymbolResolver::resolveSymbol</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *scope,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1668</span><span class="doxyLineContent"><span class="doxyHighlight">                                                </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1669</span><span class="doxyLineContent"><span class="doxyHighlight">                                                </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;args,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1670</span><span class="doxyLineContent"><span class="doxyHighlight">                                                </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> checkCV,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1671</span><span class="doxyLineContent"><span class="doxyHighlight">                                                </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> insideCode,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1672</span><span class="doxyLineContent"><span class="doxyHighlight">                                                </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> onlyLinkable)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1673</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1674</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"scope={} name={} args={} checkCV={} insideCode={}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1675</span><span class="doxyLineContent"><span class="doxyHighlight">             scope?scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), name, args, checkCV, insideCode);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1676</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a74d53555d942680120e24d2a54022fe0">p</a>-&gt;reset();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1677</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (scope==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) scope=<a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1678</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp/#a62fc03f5f79aa6176eb0cb02cb054ac9">VisitedKeys</a> visitedKeys;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1679</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *result = <a href="#a74d53555d942680120e24d2a54022fe0">p</a>-&gt;getResolvedSymbolRec(visitedKeys,scope,name,args,checkCV,insideCode,onlyLinkable,&amp;<a href="#a74d53555d942680120e24d2a54022fe0">p</a>-&gt;typeDef,&amp;<a href="#a74d53555d942680120e24d2a54022fe0">p</a>-&gt;templateSpec,&amp;<a href="#a74d53555d942680120e24d2a54022fe0">p</a>-&gt;resolvedType);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1680</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}{}"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(result?result-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">qualifiedName</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>()),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1681</span><span class="doxyLineContent"><span class="doxyHighlight">                                 <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(result &amp;&amp; result-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea422b8b811bcf8869a67732f9829d005b">Definition::TypeMember</a> ? <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>(result)-&gt;argsString() : <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1682</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1683</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">Definition::definitionType</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="#a74d53555d942680120e24d2a54022fe0">p</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>, <a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">Definition::qualifiedName</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a> and <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea422b8b811bcf8869a67732f9829d005b">Definition::TypeMember</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a043364950b2274c362fdd7e6b48d6ef6">findUsingDeclarations</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a92aa0c495ca4eb835bb914dbb5fefa35">getDefsNew</a>.</p>

</div>
</div>

### setFileScope() {#accc9cb1dfddba4432265a175e5875d55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SymbolResolver::setFileScope (const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets or updates the file scope using when resolving symbols.</p>

<p>Declaration at line 99 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-h">symbolresolver.h</a>, definition at line 1711 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#accc9cb1dfddba4432265a175e5875d55">1711</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#accc9cb1dfddba4432265a175e5875d55">SymbolResolver::setFileScope</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fileScope)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1712</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1713</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a74d53555d942680120e24d2a54022fe0">p</a>-&gt;setFileScope(fileScope);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1714</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a74d53555d942680120e24d2a54022fe0">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a92aa0c495ca4eb835bb914dbb5fefa35">getDefsNew</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#a74d53555d942680120e24d2a54022fe0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; SymbolResolver::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-h">symbolresolver.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a74d53555d942680120e24d2a54022fe0">120</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#a74d53555d942680120e24d2a54022fe0">p</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a6f023b174a5e9064fb4afdf69a02f284">getResolvedType</a>, <a href="#a82dea93383a1eeb7005e54e013358ee0">getTemplateSpec</a>, <a href="#ae434934a4e3459b50310c2a1dc9dd17b">getTypedef</a>, <a href="#a2d50ab34b5f003b3ee4c1283a414eca0">isAccessibleFrom</a>, <a href="#a63c2a4c6c16e4b5f9f527ab147c0ea2e">isAccessibleFromWithExpScope</a>, <a href="#a7d24640728b220c0b98554dbc7aa9d5f">resolveClass</a>, <a href="#a739c707d2150c5b2115fa731694eaeec">resolveSymbol</a>, <a href="#accc9cb1dfddba4432265a175e5875d55">setFileScope</a> and <a href="#a7fb03bff243edd7ac4967ff3669b8301">SymbolResolver</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/symbolresolver-h">symbolresolver.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
