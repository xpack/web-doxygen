---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/scopedtypevariant
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ScopedTypeVariant` Class Reference



## Declaration

<div class="doxyDeclaration">
class ScopedTypeVariant { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">src/scopedtypevariant.h</a>&gt;
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66f97b9bcd2ee20502beceba22a1795e">GlobalDef</a> = const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84c7bf2c17468c0fde921d4f13d67035">Variant</a> = std::variant&lt; <a href="/web-doxygen/docs/api/structs/scopedtypevariant/dummydef">DummyDef</a>, <a href="/web-doxygen/docs/api/classes/localdef">LocalDef</a>, <a href="#a66f97b9bcd2ee20502beceba22a1795e">GlobalDef</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9638da4b97bf6c52460f8344b9434d4a">ScopedTypeVariant</a> (GlobalDef d=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a357301fbd8bdd91ca469624a56807852">ScopedTypeVariant</a> (const QCString &amp;name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9575908a0f5dba51df6ecff29a264f26">name</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/localdef">LocalDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fb21854450b5fcdfe884b320e72d7be">localDef</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/localdef">LocalDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4262d265c2f1401e6efd7a235e4154f8">localDef</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a5026edb5b2a84d7a612419e7737c04">globalDef</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40759daee26ba0878db5ea90bf6621ff">isDummy</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a228a7bdbbdc4ca34bc17900000b4de58">m_name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a84c7bf2c17468c0fde921d4f13d67035">Variant</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9124948a198d6821f2fb7ef01bff20ca">m_variant</a></td>
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



<p><a href="#a84c7bf2c17468c0fde921d4f13d67035">Variant</a> class for a scoped type.</p>


<p>Variants:</p>


<ul class="doxyList ">
<li><a href="/web-doxygen/docs/api/structs/scopedtypevariant/dummydef">DummyDef</a>: a type used for hiding a global type.</li>
<li><a href="/web-doxygen/docs/api/classes/localdef">LocalDef</a>: a locally defined type (e.g. found inside a function)</li>
<li><a href="#a66f97b9bcd2ee20502beceba22a1795e">GlobalDef</a>: a globally defined type (processed by doxygen in an earlier pass).</li>
</ul>

<p>Definition at line 46 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### GlobalDef {#a66f97b9bcd2ee20502beceba22a1795e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using ScopedTypeVariant::GlobalDef =  const Definition *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a66f97b9bcd2ee20502beceba22a1795e">50</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a66f97b9bcd2ee20502beceba22a1795e">GlobalDef</a> = </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *;</span></span></div>

</div>

</div>
</div>

### Variant {#a84c7bf2c17468c0fde921d4f13d67035}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using ScopedTypeVariant::Variant =  std::variant&lt;DummyDef,LocalDef,GlobalDef&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a84c7bf2c17468c0fde921d4f13d67035">51</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a84c7bf2c17468c0fde921d4f13d67035">Variant</a> = std::variant&lt;DummyDef,LocalDef,GlobalDef&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ScopedTypeVariant() {#a9638da4b97bf6c52460f8344b9434d4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScopedTypeVariant::ScopedTypeVariant (<a href="#a66f97b9bcd2ee20502beceba22a1795e">GlobalDef</a> d=nullptr)</td>
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



<p>Definition at line 52 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9638da4b97bf6c52460f8344b9434d4a">52</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">explicit</span><span class="doxyHighlight"> <a href="#a9638da4b97bf6c52460f8344b9434d4a">ScopedTypeVariant</a>(<a href="#a66f97b9bcd2ee20502beceba22a1795e">GlobalDef</a> d = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">      : <a href="#a228a7bdbbdc4ca34bc17900000b4de58">m_name</a>(d ? d-&gt;<a href="#a9575908a0f5dba51df6ecff29a264f26">name</a>() : <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>()), <a href="#a9124948a198d6821f2fb7ef01bff20ca">m_variant</a>(d ? <a href="#a84c7bf2c17468c0fde921d4f13d67035">Variant</a>(d) : <a href="#a84c7bf2c17468c0fde921d4f13d67035">Variant</a>(<a href="/web-doxygen/docs/api/structs/scopedtypevariant/dummydef">DummyDef</a>())) {}</span></span></div>

</div>


<p>References <a href="#a228a7bdbbdc4ca34bc17900000b4de58">m_name</a>, <a href="#a9124948a198d6821f2fb7ef01bff20ca">m_variant</a> and <a href="#a9575908a0f5dba51df6ecff29a264f26">name</a>.</p>

</div>
</div>

### ScopedTypeVariant() {#a357301fbd8bdd91ca469624a56807852}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScopedTypeVariant::ScopedTypeVariant (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



<p>Definition at line 54 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a357301fbd8bdd91ca469624a56807852">54</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">explicit</span><span class="doxyHighlight"> <a href="#a357301fbd8bdd91ca469624a56807852">ScopedTypeVariant</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#a9575908a0f5dba51df6ecff29a264f26">name</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">      : <a href="#a228a7bdbbdc4ca34bc17900000b4de58">m_name</a>(<a href="#a9575908a0f5dba51df6ecff29a264f26">name</a>), <a href="#a9124948a198d6821f2fb7ef01bff20ca">m_variant</a>(<a href="/web-doxygen/docs/api/classes/localdef">LocalDef</a>()) {}</span></span></div>

</div>


<p>References <a href="#a228a7bdbbdc4ca34bc17900000b4de58">m_name</a>, <a href="#a9124948a198d6821f2fb7ef01bff20ca">m_variant</a> and <a href="#a9575908a0f5dba51df6ecff29a264f26">name</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### globalDef() {#a8a5026edb5b2a84d7a612419e7737c04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Definition * ScopedTypeVariant::globalDef ()</td>
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



<p>Definition at line 59 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8a5026edb5b2a84d7a612419e7737c04">59</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *<a href="#a8a5026edb5b2a84d7a612419e7737c04">globalDef</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> pp = std::get_if&lt;GlobalDef&gt;(&amp;<a href="#a9124948a198d6821f2fb7ef01bff20ca">m_variant</a>); </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> pp ? *pp : </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">; }</span></span></div>

</div>


<p>Reference <a href="#a9124948a198d6821f2fb7ef01bff20ca">m_variant</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/code-l/#af2995da196faa8940cca40cfc158b9aa">writeObjCMethodCall</a>.</p>

</div>
</div>

### isDummy() {#a40759daee26ba0878db5ea90bf6621ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScopedTypeVariant::isDummy ()</td>
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



<p>Definition at line 60 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a40759daee26ba0878db5ea90bf6621ff">60</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a40759daee26ba0878db5ea90bf6621ff">isDummy</a>()</span><span class="doxyHighlightKeyword"> const                </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::holds_alternative&lt;DummyDef&gt;(<a href="#a9124948a198d6821f2fb7ef01bff20ca">m_variant</a>); }</span></span></div>

</div>


<p>Reference <a href="#a9124948a198d6821f2fb7ef01bff20ca">m_variant</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/pycode-l/#a080345cfde4ece732f42ded5413ea957">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a3345ad9e2ab3a9d1b524391ae5f6c545">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a908c99ff67d83138ed1f871dab4d4c12">generateMemberLink</a> and <a href="/web-doxygen/docs/api/files/src/code-l/#ab3604b365f2d78c31db8a2fae321b6a8">setCallContextForVar</a>.</p>

</div>
</div>

### localDef() {#a7fb21854450b5fcdfe884b320e72d7be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocalDef * ScopedTypeVariant::localDef ()</td>
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



<p>Definition at line 57 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7fb21854450b5fcdfe884b320e72d7be">57</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/localdef">LocalDef</a> *<a href="#a7fb21854450b5fcdfe884b320e72d7be">localDef</a>()                { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::get_if&lt;LocalDef&gt;(&amp;<a href="#a9124948a198d6821f2fb7ef01bff20ca">m_variant</a>); }</span></span></div>

</div>


<p>Reference <a href="#a9124948a198d6821f2fb7ef01bff20ca">m_variant</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/code-l/#abc8184d316956569fe02279fba78ab92">generateFunctionLink</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#abc8184d316956569fe02279fba78ab92">generateFunctionLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a908c99ff67d83138ed1f871dab4d4c12">generateMemberLink</a> and <a href="/web-doxygen/docs/api/files/src/code-l/#a7c3e45cceb9eb4446d360eb8620eef8c">getLinkInScope</a>.</p>

</div>
</div>

### localDef() {#a4262d265c2f1401e6efd7a235e4154f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LocalDef * ScopedTypeVariant::localDef ()</td>
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



<p>Definition at line 58 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4262d265c2f1401e6efd7a235e4154f8">58</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/localdef">LocalDef</a> *<a href="#a4262d265c2f1401e6efd7a235e4154f8">localDef</a>()</span><span class="doxyHighlightKeyword"> const    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::get_if&lt;LocalDef&gt;(&amp;<a href="#a9124948a198d6821f2fb7ef01bff20ca">m_variant</a>); }</span></span></div>

</div>


<p>Reference <a href="#a9124948a198d6821f2fb7ef01bff20ca">m_variant</a>.</p>

</div>
</div>

### name() {#a9575908a0f5dba51df6ecff29a264f26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ScopedTypeVariant::name ()</td>
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



<p>Definition at line 56 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9575908a0f5dba51df6ecff29a264f26">56</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a9575908a0f5dba51df6ecff29a264f26">name</a>()</span><span class="doxyHighlightKeyword"> const               </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a228a7bdbbdc4ca34bc17900000b4de58">m_name</a>; }</span></span></div>

</div>


<p>Reference <a href="#a228a7bdbbdc4ca34bc17900000b4de58">m_name</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/code-l/#a3345ad9e2ab3a9d1b524391ae5f6c545">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a908c99ff67d83138ed1f871dab4d4c12">generateMemberLink</a>, <a href="#a357301fbd8bdd91ca469624a56807852">ScopedTypeVariant</a>, <a href="#a9638da4b97bf6c52460f8344b9434d4a">ScopedTypeVariant</a> and <a href="/web-doxygen/docs/api/files/src/code-l/#ab3604b365f2d78c31db8a2fae321b6a8">setCallContextForVar</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_name {#a228a7bdbbdc4ca34bc17900000b4de58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ScopedTypeVariant::m_name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a228a7bdbbdc4ca34bc17900000b4de58">63</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a228a7bdbbdc4ca34bc17900000b4de58">m_name</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a9575908a0f5dba51df6ecff29a264f26">name</a>, <a href="#a357301fbd8bdd91ca469624a56807852">ScopedTypeVariant</a> and <a href="#a9638da4b97bf6c52460f8344b9434d4a">ScopedTypeVariant</a>.</p>

</div>
</div>

### m\_variant {#a9124948a198d6821f2fb7ef01bff20ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Variant ScopedTypeVariant::m_variant</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9124948a198d6821f2fb7ef01bff20ca">64</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a84c7bf2c17468c0fde921d4f13d67035">Variant</a> <a href="#a9124948a198d6821f2fb7ef01bff20ca">m_variant</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a8a5026edb5b2a84d7a612419e7737c04">globalDef</a>, <a href="#a40759daee26ba0878db5ea90bf6621ff">isDummy</a>, <a href="#a7fb21854450b5fcdfe884b320e72d7be">localDef</a>, <a href="#a4262d265c2f1401e6efd7a235e4154f8">localDef</a>, <a href="#a357301fbd8bdd91ca469624a56807852">ScopedTypeVariant</a> and <a href="#a9638da4b97bf6c52460f8344b9434d4a">ScopedTypeVariant</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
