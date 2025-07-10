---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/src/outputgen-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `outputgen.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;memory&gt;
#include &lt;stack&gt;
#include &lt;iostream&gt;
#include &lt;fstream&gt;
#include "<a href="/web-doxygen/docs/api/files/src/types-h">types.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/index-h">index.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/section-h">section.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/docparser-h">docparser.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/construct-h">construct.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/doclinkinfo">DocLinkInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/sourcelinkinfo">SourceLinkInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/outputcodeintf">OutputCodeIntf</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for code generators. <a href="/web-doxygen/docs/api/classes/outputcodeintf/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/outputgenerator">OutputGenerator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for shared implementation for all output generators. <a href="/web-doxygen/docs/api/classes/outputgenerator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/outputgenintf">OutputGenIntf</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract interface for output generators. <a href="/web-doxygen/docs/api/classes/outputgenintf/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">OutputType { <a href="#a4e0517338e6c4a31a2addafc06d4f3a3">...</a> }</td>
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

## Enumerations

### OutputType {#a4e0517338e6c4a31a2addafc06d4f3a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class OutputType </td>
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
<td class="doxyEnumItemName">List<a id="a4e0517338e6c4a31a2addafc06d4f3a3a4ee29ca12c7d126654bd0e5275de6135"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Html<a id="a4e0517338e6c4a31a2addafc06d4f3a3a3135f4019bee015e2d1ae7f77f9f3f64"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Latex<a id="a4e0517338e6c4a31a2addafc06d4f3a3a08e3b0db5b64cd1da774369814896b78"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Man<a id="a4e0517338e6c4a31a2addafc06d4f3a3a627661c621eab1b7b298abc47d1a250d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RTF<a id="a4e0517338e6c4a31a2addafc06d4f3a3a7da7adb1d98a6ee0f69281084f9ea9b2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Docbook<a id="a4e0517338e6c4a31a2addafc06d4f3a3a680ad2abb703e2cb60fbdddf8423315a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XML<a id="a4e0517338e6c4a31a2addafc06d4f3a3a3501bb093d363810b671059b9cfed3f8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Null<a id="a4e0517338e6c4a31a2addafc06d4f3a3abbb93ef26e3c101ff11cdd21cab08a94"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Extension<a id="a4e0517338e6c4a31a2addafc06d4f3a3a63e4e92bb7d207ca577b11c07f827279"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Recorder<a id="a4e0517338e6c4a31a2addafc06d4f3a3a1aff765143dc4bf8ef68f698234e10f6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 59 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4e0517338e6c4a31a2addafc06d4f3a3a680ad2abb703e2cb60fbdddf8423315a">59</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">enum class</span><span class="doxyHighlight"> <a href="#a4e0517338e6c4a31a2addafc06d4f3a3">OutputType</a> { <a href="#a4e0517338e6c4a31a2addafc06d4f3a3a4ee29ca12c7d126654bd0e5275de6135">List</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca3135f4019bee015e2d1ae7f77f9f3f64">Html</a>, <a href="#a4e0517338e6c4a31a2addafc06d4f3a3a08e3b0db5b64cd1da774369814896b78">Latex</a>, <a href="#a4e0517338e6c4a31a2addafc06d4f3a3a627661c621eab1b7b298abc47d1a250d">Man</a>, <a href="#a4e0517338e6c4a31a2addafc06d4f3a3a7da7adb1d98a6ee0f69281084f9ea9b2">RTF</a>, <a href="#a4e0517338e6c4a31a2addafc06d4f3a3a680ad2abb703e2cb60fbdddf8423315a">Docbook</a>, <a href="#a4e0517338e6c4a31a2addafc06d4f3a3a3501bb093d363810b671059b9cfed3f8">XML</a>, <a href="#a4e0517338e6c4a31a2addafc06d4f3a3abbb93ef26e3c101ff11cdd21cab08a94">Null</a>, <a href="#a4e0517338e6c4a31a2addafc06d4f3a3a63e4e92bb7d207ca577b11c07f827279">Extension</a>, <a href="#a4e0517338e6c4a31a2addafc06d4f3a3a1aff765143dc4bf8ef68f698234e10f6">Recorder</a> };</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
