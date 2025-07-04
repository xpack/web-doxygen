---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/accessstack/accesselem
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AccessElem` Struct Reference

<p>Element in the stack. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct AccessStack::AccessElem { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab2da052bba3755c04e71b097b140e76">AccessElem</a> (const Definition *d, const FileDef *f, const Definition *i)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad90353fcd3b1ecc0439af1649787f684">AccessElem</a> (const Definition *d, const FileDef *f, const Definition *i, const QCString &amp;e)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0401ace2320fe112fa2f0e93bef87753">scope</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a444c35fa65e0e9b77d6f79f4987353f1">fileScope</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8413f32dd12451d6b488a8fe48bedec3">item</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83782802ba91aead5ad5d189f5b7917b">expScope</a></td>
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

<p>Element in the stack.</p>

<p>Definition at line 61 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AccessElem() {#aab2da052bba3755c04e71b097b140e76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AccessStack::AccessElem::AccessElem (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d, const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * f, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * i)</td>
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



<p>Definition at line 63 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aab2da052bba3755c04e71b097b140e76">63</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aab2da052bba3755c04e71b097b140e76">AccessElem</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *f,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *i) : <a href="#a0401ace2320fe112fa2f0e93bef87753">scope</a>(d), <a href="#a444c35fa65e0e9b77d6f79f4987353f1">fileScope</a>(f), <a href="#a8413f32dd12451d6b488a8fe48bedec3">item</a>(i) {}</span></span></div>

</div>


<p>References <a href="#a444c35fa65e0e9b77d6f79f4987353f1">fileScope</a>, <a href="#a8413f32dd12451d6b488a8fe48bedec3">item</a> and <a href="#a0401ace2320fe112fa2f0e93bef87753">scope</a>.</p>

</div>
</div>

### AccessElem() {#ad90353fcd3b1ecc0439af1649787f684}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AccessStack::AccessElem::AccessElem (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d, const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * f, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * i, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; e)</td>
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



<p>Definition at line 64 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad90353fcd3b1ecc0439af1649787f684">64</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad90353fcd3b1ecc0439af1649787f684">AccessElem</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *f,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *i,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;e) : <a href="#a0401ace2320fe112fa2f0e93bef87753">scope</a>(d), <a href="#a444c35fa65e0e9b77d6f79f4987353f1">fileScope</a>(f), <a href="#a8413f32dd12451d6b488a8fe48bedec3">item</a>(i), <a href="#a83782802ba91aead5ad5d189f5b7917b">expScope</a>(e) {}</span></span></div>

</div>


<p>References <a href="#a83782802ba91aead5ad5d189f5b7917b">expScope</a>, <a href="#a444c35fa65e0e9b77d6f79f4987353f1">fileScope</a>, <a href="#a8413f32dd12451d6b488a8fe48bedec3">item</a> and <a href="#a0401ace2320fe112fa2f0e93bef87753">scope</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### expScope {#a83782802ba91aead5ad5d189f5b7917b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString AccessStack::AccessElem::expScope</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a83782802ba91aead5ad5d189f5b7917b">68</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a83782802ba91aead5ad5d189f5b7917b">expScope</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ad90353fcd3b1ecc0439af1649787f684">AccessElem</a>.</p>

</div>
</div>

### fileScope {#a444c35fa65e0e9b77d6f79f4987353f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FileDef* AccessStack::AccessElem::fileScope</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a444c35fa65e0e9b77d6f79f4987353f1">66</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *<a href="#a444c35fa65e0e9b77d6f79f4987353f1">fileScope</a>;</span></span></div>

</div>


<p>Referenced by <a href="#aab2da052bba3755c04e71b097b140e76">AccessElem</a> and <a href="#ad90353fcd3b1ecc0439af1649787f684">AccessElem</a>.</p>

</div>
</div>

### item {#a8413f32dd12451d6b488a8fe48bedec3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Definition* AccessStack::AccessElem::item</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8413f32dd12451d6b488a8fe48bedec3">67</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *<a href="#a8413f32dd12451d6b488a8fe48bedec3">item</a>;</span></span></div>

</div>


<p>Referenced by <a href="#aab2da052bba3755c04e71b097b140e76">AccessElem</a> and <a href="#ad90353fcd3b1ecc0439af1649787f684">AccessElem</a>.</p>

</div>
</div>

### scope {#a0401ace2320fe112fa2f0e93bef87753}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Definition* AccessStack::AccessElem::scope</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0401ace2320fe112fa2f0e93bef87753">65</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *<a href="#a0401ace2320fe112fa2f0e93bef87753">scope</a>;</span></span></div>

</div>


<p>Referenced by <a href="#aab2da052bba3755c04e71b097b140e76">AccessElem</a> and <a href="#ad90353fcd3b1ecc0439af1649787f684">AccessElem</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/symbolresolver-cpp">symbolresolver.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
