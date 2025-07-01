---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/bodyinfo
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `BodyInfo` Struct Reference

Data associated with description found in the body. <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
struct BodyInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/definition-h">src/definition.h</a>&gt;
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af49dee4a07f48964799b97526d4375f0">defLine</a> = -1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
line number of the start of the definition <a href="#af49dee4a07f48964799b97526d4375f0">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13ecf2183dee65bdf06cda72cd0363a0">startLine</a> = -1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
line number of the start of the definition's body <a href="#a13ecf2183dee65bdf06cda72cd0363a0">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf40ab79b5fe12c0e46fcd272a62cf44">endLine</a> = -1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
line number of the end of the definition's body <a href="#adf40ab79b5fe12c0e46fcd272a62cf44">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0cfb0ee5215fb51b814d1a610ff15c4">fileDef</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
file definition containing the function body <a href="#ad0cfb0ee5215fb51b814d1a610ff15c4">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

Data associated with description found in the body.

Definition at line 62 of file <a href="/web-doxygen/docs/api/files/src/definition-h">definition.h</a>.

<div class="doxySectionDef">

## Public Member Attributes

### defLine {#af49dee4a07f48964799b97526d4375f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int BodyInfo::defLine = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

line number of the start of the definition

Definition at line 64 of file <a href="/web-doxygen/docs/api/files/src/definition-h">definition.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af49dee4a07f48964799b97526d4375f0">64</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">      <a href="#af49dee4a07f48964799b97526d4375f0">defLine</a> = -1;     </span><span class="doxyHighlightComment">//!&lt; line number of the start of the definition</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#a06acdab477ab34e9350220bece9f49f5">DefinitionImpl::setBodySegment</a>.
</div>
</div>

### endLine {#adf40ab79b5fe12c0e46fcd272a62cf44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int BodyInfo::endLine = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

line number of the end of the definition's body

Definition at line 66 of file <a href="/web-doxygen/docs/api/files/src/definition-h">definition.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adf40ab79b5fe12c0e46fcd272a62cf44">66</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">      <a href="#adf40ab79b5fe12c0e46fcd272a62cf44">endLine</a> = -1;     </span><span class="doxyHighlightComment">//!&lt; line number of the end of the definition's body</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#a06acdab477ab34e9350220bece9f49f5">DefinitionImpl::setBodySegment</a>.
</div>
</div>

### fileDef {#ad0cfb0ee5215fb51b814d1a610ff15c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FileDef* BodyInfo::fileDef = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

file definition containing the function body

Definition at line 67 of file <a href="/web-doxygen/docs/api/files/src/definition-h">definition.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad0cfb0ee5215fb51b814d1a610ff15c4">67</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *<a href="#ad0cfb0ee5215fb51b814d1a610ff15c4">fileDef</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;      </span><span class="doxyHighlightComment">//!&lt; file definition containing the function body</span></span></div>

</div>

</div>
</div>

### startLine {#a13ecf2183dee65bdf06cda72cd0363a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int BodyInfo::startLine = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

line number of the start of the definition's body

Definition at line 65 of file <a href="/web-doxygen/docs/api/files/src/definition-h">definition.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a13ecf2183dee65bdf06cda72cd0363a0">65</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">      <a href="#a13ecf2183dee65bdf06cda72cd0363a0">startLine</a> = -1;   </span><span class="doxyHighlightComment">//!&lt; line number of the start of the definition's body</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#a06acdab477ab34e9350220bece9f49f5">DefinitionImpl::setBodySegment</a>.
</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/definition-h">definition.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
