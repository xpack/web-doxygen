---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/filedef-h
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `filedef.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;memory&gt;
#include &lt;unordered_set&gt;
#include "<a href="/web-doxygen/docs/api/files/src/definition-h">definition.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/containers-h">containers.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/includeinfo">IncludeInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class representing the data associated with a #include statement. <a href="/web-doxygen/docs/api/structs/includeinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/includeinfolist">IncludeInfoList</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/filedef">FileDef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A model of a file symbol. <a href="/web-doxygen/docs/api/classes/filedef/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/filelist">FileList</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/filesindir">FilesInDir</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affcfa8308cbb34c7e5dbf239c664da35">FileDefSet</a> = std::unordered_set&lt; const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">IncludeKind : uint32_t { <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8">...</a> }</td>
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

## Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1492c7341fbed961ee09ec93dd5b9de4">operator|</a> (IncludeKind a, IncludeKind b)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1409c607daae02eeb3741c5f7346ba17">operator|</a> (uint32_t a, IncludeKind b)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59a2dd7de4021b68c61edf8d63c9bdd6">operator&amp;</a> (IncludeKind a, uint32_t mask)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29b4da465017ea752ef6d376a091a5b8">includeStatement</a> (SrcLangExt lang, IncludeKind kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7af9a5628546bbd3c1e8aff7d1b102db">includeOpen</a> (SrcLangExt lang, IncludeKind kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20c0bc843d92509665072eae19b394ea">includeClose</a> (SrcLangExt lang, IncludeKind kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fc838fe6dfe16aaf92455e8cb066d59">compareFileDefs</a> (const FileDef *fd1, const FileDef *fd2)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57b6a9dbcf3240c5a691f37564ef89ad">createFileDef</a> (const QCString &amp;p, const QCString &amp;n, const QCString &amp;ref=QCString(), const QCString &amp;dn=QCString())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4114c484f3ccea1048608b9caa9f51de">toFileDef</a> (Definition *d)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd196021d20bc081fa1dd91c57164837">toFileDef</a> (const Definition *d)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdab8bf385a3fe5d1f569c32428c2863">IncludeKind_LocalMask</a> = <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a72f604ea2eef74f27164fe740e67847b">IncludeKind::IncludeLocal</a>     | <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8aaf0b778b0e0af69011f06c8734fdb891">IncludeKind::ImportLocalObjC</a>  | <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a2dbc22c9108714bfd4417e558b7b82e2">IncludeKind::ImportLocal</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa33e018d950b5a3ce71969b727fbc66">IncludeKind_SystemMask</a> = <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8ab0ead0aebf84f57889aab39d528f34b4">IncludeKind::IncludeSystem</a>    | <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a850b5d27cd4e40d0405c4b7a0d76ab94">IncludeKind::ImportSystemObjC</a> | <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8ac597d64b5224025af7bef1aad3172845">IncludeKind::ImportSystem</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eeca59091b422e472c7ccbe7abb337c">IncludeKind_ImportMask</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f83257cf012e77790524a29bd32c037">IncludeKind_ObjCMask</a> = <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a850b5d27cd4e40d0405c4b7a0d76ab94">IncludeKind::ImportSystemObjC</a> | <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8aaf0b778b0e0af69011f06c8734fdb891">IncludeKind::ImportLocalObjC</a></td>
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

### FileDefSet {#affcfa8308cbb34c7e5dbf239c664da35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using FileDefSet =  std::unordered_set&lt;const FileDef*&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00044">44</a> of file <a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#affcfa8308cbb34c7e5dbf239c664da35">44</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#affcfa8308cbb34c7e5dbf239c664da35">FileDefSet</a> = std::unordered_set&lt;const FileDef*&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### IncludeKind {#a52a98ac8d3b93b98e9371611d4b9dcb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class IncludeKind : uint32_t</td>
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
<td class="doxyEnumItemName">IncludeSystem<a id="a52a98ac8d3b93b98e9371611d4b9dcb8ab0ead0aebf84f57889aab39d528f34b4"></a></td>
<td class="doxyEnumItemDescription"><p> (= 0x0001)</p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IncludeLocal<a id="a52a98ac8d3b93b98e9371611d4b9dcb8a72f604ea2eef74f27164fe740e67847b"></a></td>
<td class="doxyEnumItemDescription"><p> (= 0x0002)</p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImportSystemObjC<a id="a52a98ac8d3b93b98e9371611d4b9dcb8a850b5d27cd4e40d0405c4b7a0d76ab94"></a></td>
<td class="doxyEnumItemDescription"><p> (= 0x0004)</p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImportLocalObjC<a id="a52a98ac8d3b93b98e9371611d4b9dcb8aaf0b778b0e0af69011f06c8734fdb891"></a></td>
<td class="doxyEnumItemDescription"><p> (= 0x0008)</p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImportSystem<a id="a52a98ac8d3b93b98e9371611d4b9dcb8ac597d64b5224025af7bef1aad3172845"></a></td>
<td class="doxyEnumItemDescription"><p> (= 0x0010)</p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImportLocal<a id="a52a98ac8d3b93b98e9371611d4b9dcb8a2dbc22c9108714bfd4417e558b7b82e2"></a></td>
<td class="doxyEnumItemDescription"><p> (= 0x0020)</p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImportModule<a id="a52a98ac8d3b93b98e9371611d4b9dcb8a57522338dd8bf2361634a923a2b71b81"></a></td>
<td class="doxyEnumItemDescription"><p> (= 0x0040)</p></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line <a href="#l00046">46</a> of file <a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// bits</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a52a98ac8d3b93b98e9371611d4b9dcb8ab0ead0aebf84f57889aab39d528f34b4">49</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8ab0ead0aebf84f57889aab39d528f34b4">IncludeSystem</a>     = 0x0001,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a72f604ea2eef74f27164fe740e67847b">50</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a72f604ea2eef74f27164fe740e67847b">IncludeLocal</a>      = 0x0002,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a850b5d27cd4e40d0405c4b7a0d76ab94">51</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a850b5d27cd4e40d0405c4b7a0d76ab94">ImportSystemObjC</a>  = 0x0004,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a52a98ac8d3b93b98e9371611d4b9dcb8aaf0b778b0e0af69011f06c8734fdb891">52</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8aaf0b778b0e0af69011f06c8734fdb891">ImportLocalObjC</a>   = 0x0008,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a52a98ac8d3b93b98e9371611d4b9dcb8ac597d64b5224025af7bef1aad3172845">53</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8ac597d64b5224025af7bef1aad3172845">ImportSystem</a>      = 0x0010, </span><span class="doxyHighlightComment">// C++20 header import</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a2dbc22c9108714bfd4417e558b7b82e2">54</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a2dbc22c9108714bfd4417e558b7b82e2">ImportLocal</a>       = 0x0020, </span><span class="doxyHighlightComment">// C++20 header import</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a57522338dd8bf2361634a923a2b71b81">55</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a57522338dd8bf2361634a923a2b71b81">ImportModule</a>      = 64  </span><span class="doxyHighlightComment">// C++20/Java module import</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Operators

### operator&amp;() {#a59a2dd7de4021b68c61edf8d63c9bdd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t operator&amp; (<a href="#a52a98ac8d3b93b98e9371611d4b9dcb8">IncludeKind</a> a, uint32_t mask)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00060">60</a> of file <a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a59a2dd7de4021b68c61edf8d63c9bdd6">60</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">constexpr</span><span class="doxyHighlight"> uint32_t <a href="#a59a2dd7de4021b68c61edf8d63c9bdd6">operator&amp;</a>(<a href="#a52a98ac8d3b93b98e9371611d4b9dcb8">IncludeKind</a> a, uint32_t mask) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight">uint32_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(a) &amp; mask; }</span></span></div>

</div>

</div>
</div>

### operator|() {#a1492c7341fbed961ee09ec93dd5b9de4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t operator| (<a href="#a52a98ac8d3b93b98e9371611d4b9dcb8">IncludeKind</a> a, <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8">IncludeKind</a> b)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00058">58</a> of file <a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1492c7341fbed961ee09ec93dd5b9de4">58</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">constexpr</span><span class="doxyHighlight"> uint32_t <a href="#a1492c7341fbed961ee09ec93dd5b9de4">operator|</a>(<a href="#a52a98ac8d3b93b98e9371611d4b9dcb8">IncludeKind</a> a, <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8">IncludeKind</a> b) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight">uint32_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(a) | </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight">uint32_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(b); }</span></span></div>

</div>

</div>
</div>

### operator|() {#a1409c607daae02eeb3741c5f7346ba17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t operator| (uint32_t a, <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8">IncludeKind</a> b)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00059">59</a> of file <a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1409c607daae02eeb3741c5f7346ba17">59</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">constexpr</span><span class="doxyHighlight"> uint32_t <a href="#a1492c7341fbed961ee09ec93dd5b9de4">operator|</a>(uint32_t a, <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8">IncludeKind</a> b) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> a | </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight">uint32_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(b); }</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### compareFileDefs() {#a3fc838fe6dfe16aaf92455e8cb066d59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool compareFileDefs (const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd1, const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="#l00088">88</a> of file <a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#l01925">1925</a> of file <a href="/web-doxygen/docs/api/files/src/filedef-cpp">filedef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3fc838fe6dfe16aaf92455e8cb066d59">1925</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3fc838fe6dfe16aaf92455e8cb066d59">compareFileDefs</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1926</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1927</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a07e4a8b28f58e46b010e22651c87eb3c">qstricmp_sort</a>(fd1-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(),fd2-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>()) &lt; 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1928</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a07e4a8b28f58e46b010e22651c87eb3c">qstricmp&#95;sort</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ada60e602f7b5c873829b42ae6638a389">DirDefImpl::sort</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a32155fdad3f4843c5d8743c037bf4846">writeFileIndex</a>.
</div>
</div>

### createFileDef() {#a57b6a9dbcf3240c5a691f37564ef89ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; FileDef &gt; createFileDef (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; p, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; n, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; dn=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="#l00212">212</a> of file <a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#l00268">268</a> of file <a href="/web-doxygen/docs/api/files/src/filedef-cpp">filedef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">268</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::unique_ptr&lt;FileDef&gt; <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;p,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;n,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;dn)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::make_unique&lt;FileDefImpl&gt;(p,n,ref,dn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a9a2a4b0accaef9069229937226e60b10">anonymous&#95;namespace{tagreader.cpp}::TagFileParser::buildLists</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a5826ce8044be2553216f205ef64ead74">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a1abe1e85619493e4e99240d290c3bdd2">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#abfd0aac31a863e63e61dc67da22a349c">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#af32530eae2ce36e648a925f28f1ca781">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#ade1c6d00759ad30078d9f5a51cbfc009">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a41c844f5b9078d32e11a14b45b6f5c2d">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a103c34bd91c4bf67cadfca22f2b61466">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a611ec420e06726e8061f4fe83c3f8a6f">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#ac315ddf81b73a005764278a3c190d1a4">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a75e708a4ea1b27587678f424211b8b62">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a32d2017f02e0835ea865360773ac1eda">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#ac219ce4773970158e118d1d3b57ebd78">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/filedef/#ad43c4d8ba9857b32e92ca529152e4958">FileDef::overrideIncludedByGraph</a>, <a href="/web-doxygen/docs/api/classes/ccodeparser/#a106ea78aa6382f5b06dbd2563d5b99e4">CCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/fortrancodeparser/#ab7216957ad8abace8578d47edd8b578d">FortranCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/lexcodeparser/#a907e618c99ef07aa00fc0604062e3929">LexCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/pythoncodeparser/#a7f8b5638c6d0424a1de9bc6905041ab2">PythonCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/sqlcodeparser/#ad4cfac05d7a0c2354cdb90992b1e0248">SQLCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/vhdlcodeparser/#a49ff704e68bb7562a054bd1c7f8bba09">VHDLCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/xmlcodeparser/#a1e7283cd50a9220c8381cbdf953702ca">XMLCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/codefragmentmanager/#a1aa709870f1258a753c2b952f95175be">CodeFragmentManager::parseCodeFragment</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab1c5d97fd966b1d6996e5c4ce21c88b1">readDir</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#adfb0efa72e3e5ed08b1881ccd8332e5e">readFileOrDirectory</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a256c275d3b654245e85d7c04e8f417b9">writeGraphInfo</a>.
</div>
</div>

### includeClose() {#a20c0bc843d92509665072eae19b394ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString includeClose (<a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang, <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8">IncludeKind</a> kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="#l00071">71</a> of file <a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#l00086">86</a> of file <a href="/web-doxygen/docs/api/files/src/filedef-cpp">filedef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a20c0bc843d92509665072eae19b394ea">86</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a20c0bc843d92509665072eae19b394ea">includeClose</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang,<a href="#a52a98ac8d3b93b98e9371611d4b9dcb8">IncludeKind</a> kind)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lang==SrcLangExt::IDL) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"\";"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lang==SrcLangExt::Java) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">";"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (kind)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a2dbc22c9108714bfd4417e558b7b82e2">IncludeKind::ImportLocal</a>:       </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"\";"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8aaf0b778b0e0af69011f06c8734fdb891">IncludeKind::ImportLocalObjC</a>:   </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a72f604ea2eef74f27164fe740e67847b">IncludeKind::IncludeLocal</a>:      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8ac597d64b5224025af7bef1aad3172845">IncludeKind::ImportSystem</a>:      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"&gt;;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a850b5d27cd4e40d0405c4b7a0d76ab94">IncludeKind::ImportSystemObjC</a>:  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8ab0ead0aebf84f57889aab39d528f34b4">IncludeKind::IncludeSystem</a>:     </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a57522338dd8bf2361634a923a2b71b81">IncludeKind::ImportModule</a>:      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">";"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a2dbc22c9108714bfd4417e558b7b82e2">ImportLocal</a>, <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8aaf0b778b0e0af69011f06c8734fdb891">ImportLocalObjC</a>, <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a57522338dd8bf2361634a923a2b71b81">ImportModule</a>, <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8ac597d64b5224025af7bef1aad3172845">ImportSystem</a>, <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a850b5d27cd4e40d0405c4b7a0d76ab94">ImportSystemObjC</a>, <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a72f604ea2eef74f27164fe740e67847b">IncludeLocal</a> and <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8ab0ead0aebf84f57889aab39d528f34b4">IncludeSystem</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#acb75f1220490ed9d0cce2344fc25bc96">ClassDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a13b863cddb2d53345fcc53835249bad9">ConceptDefImpl::writeIncludeFiles</a> and <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7274693641d802ed217bdc46b91db227">FileDefImpl::writeIncludeFiles</a>.
</div>
</div>

### includeOpen() {#a7af9a5628546bbd3c1e8aff7d1b102db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString includeOpen (<a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang, <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8">IncludeKind</a> kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="#l00070">70</a> of file <a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#l00073">73</a> of file <a href="/web-doxygen/docs/api/files/src/filedef-cpp">filedef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a7af9a5628546bbd3c1e8aff7d1b102db">73</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a7af9a5628546bbd3c1e8aff7d1b102db">includeOpen</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang,<a href="#a52a98ac8d3b93b98e9371611d4b9dcb8">IncludeKind</a> kind)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lang==SrcLangExt::Java || kind==<a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a57522338dd8bf2361634a923a2b71b81">IncludeKind::ImportModule</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((kind &amp; <a href="#abdab8bf385a3fe5d1f569c32428c2863">IncludeKind_LocalMask</a>) || (lang==SrcLangExt::IDL))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"&lt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a57522338dd8bf2361634a923a2b71b81">ImportModule</a> and <a href="#abdab8bf385a3fe5d1f569c32428c2863">IncludeKind&#95;LocalMask</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#acb75f1220490ed9d0cce2344fc25bc96">ClassDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a13b863cddb2d53345fcc53835249bad9">ConceptDefImpl::writeIncludeFiles</a> and <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7274693641d802ed217bdc46b91db227">FileDefImpl::writeIncludeFiles</a>.
</div>
</div>

### includeStatement() {#a29b4da465017ea752ef6d376a091a5b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString includeStatement (<a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang, <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8">IncludeKind</a> kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="#l00069">69</a> of file <a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#l00056">56</a> of file <a href="/web-doxygen/docs/api/files/src/filedef-cpp">filedef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a29b4da465017ea752ef6d376a091a5b8">56</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a29b4da465017ea752ef6d376a091a5b8">includeStatement</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang,<a href="#a52a98ac8d3b93b98e9371611d4b9dcb8">IncludeKind</a> kind)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isIDLorJava = lang==SrcLangExt::IDL || lang==SrcLangExt::Java;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isIDLorJava || (kind &amp; <a href="#a5eeca59091b422e472c7ccbe7abb337c">IncludeKind_ImportMask</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"import "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (kind &amp; <a href="#a0f83257cf012e77790524a29bd32c037">IncludeKind_ObjCMask</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"#import "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"#include "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a5eeca59091b422e472c7ccbe7abb337c">IncludeKind&#95;ImportMask</a> and <a href="#a0f83257cf012e77790524a29bd32c037">IncludeKind&#95;ObjCMask</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#acb75f1220490ed9d0cce2344fc25bc96">ClassDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a13b863cddb2d53345fcc53835249bad9">ConceptDefImpl::writeIncludeFiles</a> and <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7274693641d802ed217bdc46b91db227">FileDefImpl::writeIncludeFiles</a>.
</div>
</div>

### toFileDef() {#a4114c484f3ccea1048608b9caa9f51de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FileDef * toFileDef (<a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="#l00217">217</a> of file <a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#l01932">1932</a> of file <a href="/web-doxygen/docs/api/files/src/filedef-cpp">filedef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a4114c484f3ccea1048608b9caa9f51de">1932</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *<a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a4114c484f3ccea1048608b9caa9f51de">toFileDef</a>(<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1933</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1934</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1935</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d &amp;&amp; </span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/filedefimpl">FileDefImpl</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1936</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1937</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/filedef">FileDef</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1938</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1939</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1940</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1941</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1942</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1943</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/docsets/#a68e99525be1bdf8596ca067a014e9931">DocSets::addIndexItem</a>, <a href="/web-doxygen/docs/api/classes/doclink/#ac29d67178173446fbc14dd28378daec3">DocLink::DocLink</a>, <a href="/web-doxygen/docs/api/classes/docref/#acb234cd7235b7c61a4c6f9dfd0cd586b">DocRef::DocRef</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a67d97db3c717b89b9a6211ae48e9273b">findModuleDef</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#aab0947e93a77169efff48326518717ab">SymbolResolver::Private::followPath</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#a2945edc16c199a62e84ee85d81b9c854">generateJSTree</a>, <a href="/web-doxygen/docs/api/structs/ftvhelp/private/#a0bed14c4bee93963b64e37bb6532aad8">FTVHelp::Private::generateTree</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a41fdc2a524c5339afd35c067a828459d">SymbolResolver::Private::getResolvedSymbolRec</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a2b2971ad53e50d90ca4affca6a6e1d67">DocParser::handleLinkedWord</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ad1c6c890ed8e8ebcfe057f3de5db4fcb">NamespaceDefImpl::insertMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a02e748da779cf061b14c27d976efdb65">insertMemberAlias</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a60ffd0b23680e5318865a367b0d26871">SymbolResolver::Private::isAccessibleFrom</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a31ba3cfbe898329d92215b8314227b0d">ClassDefImpl::moveTo</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a263db4e9ffc625509018045b0345b31c">MemberDefImpl::moveTo</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#ad4c47fcf278c5cb6b23e82b584413ee8">DefinitionImpl::navigationPathAsString</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#a4e52d619e02e6a48b41aa65affcac398">node2URL</a>, <a href="/web-doxygen/docs/api/classes/filedef/#ad43c4d8ba9857b32e92ca529152e4958">FileDef::overrideIncludedByGraph</a>, <a href="/web-doxygen/docs/api/classes/searchindex/#ac8f6bb104126c1406d2d6e5ad368822c">SearchIndex::setCurrentDoc</a> and <a href="/web-doxygen/docs/api/classes/searchindexexternal/#adcacedbd41c269a155cadcb46deda856">SearchIndexExternal::setCurrentDoc</a>.
</div>
</div>

### toFileDef() {#acd196021d20bc081fa1dd91c57164837}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FileDef * toFileDef (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="#l00218">218</a> of file <a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#l01945">1945</a> of file <a href="/web-doxygen/docs/api/files/src/filedef-cpp">filedef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/filedef-cpp/#acd196021d20bc081fa1dd91c57164837">1945</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *<a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a4114c484f3ccea1048608b9caa9f51de">toFileDef</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1946</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1947</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1948</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d &amp;&amp; </span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/filedefimpl">FileDefImpl</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1949</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1950</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/filedef">FileDef</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1951</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1952</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1953</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1954</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1955</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1956</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### IncludeKind&#95;ImportMask {#a5eeca59091b422e472c7ccbe7abb337c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t IncludeKind_ImportMask</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a850b5d27cd4e40d0405c4b7a0d76ab94">IncludeKind::ImportSystemObjC</a> | <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8aaf0b778b0e0af69011f06c8734fdb891">IncludeKind::ImportLocalObjC</a>  | <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8ac597d64b5224025af7bef1aad3172845">IncludeKind::ImportSystem</a> |
                                            <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a2dbc22c9108714bfd4417e558b7b82e2">IncludeKind::ImportLocal</a>      | <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a57522338dd8bf2361634a923a2b71b81">IncludeKind::ImportModule</a>
</div>
</dd>
</dl>

<p>Definition at line <a href="#l00065">65</a> of file <a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5eeca59091b422e472c7ccbe7abb337c">65</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">constexpr</span><span class="doxyHighlight"> uint32_t <a href="#a5eeca59091b422e472c7ccbe7abb337c">IncludeKind_ImportMask</a> = <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a850b5d27cd4e40d0405c4b7a0d76ab94">IncludeKind::ImportSystemObjC</a> | <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8aaf0b778b0e0af69011f06c8734fdb891">IncludeKind::ImportLocalObjC</a>  | <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8ac597d64b5224025af7bef1aad3172845">IncludeKind::ImportSystem</a> |</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae7139b08c0c942d65c6bcb8402a8b142">generateSqlite3ForFile</a>, <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a29b4da465017ea752ef6d376a091a5b8">includeStatement</a> and <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#aa2872f3c154bf7c3cfa319bcf83e3fac">includeTagFileAttributes</a>.
</div>
</div>

### IncludeKind&#95;LocalMask {#abdab8bf385a3fe5d1f569c32428c2863}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t IncludeKind_LocalMask = <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a72f604ea2eef74f27164fe740e67847b">IncludeKind::IncludeLocal</a>     | <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8aaf0b778b0e0af69011f06c8734fdb891">IncludeKind::ImportLocalObjC</a>  | <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a2dbc22c9108714bfd4417e558b7b82e2">IncludeKind::ImportLocal</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00063">63</a> of file <a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abdab8bf385a3fe5d1f569c32428c2863">63</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">constexpr</span><span class="doxyHighlight"> uint32_t <a href="#abdab8bf385a3fe5d1f569c32428c2863">IncludeKind_LocalMask</a>  = <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a72f604ea2eef74f27164fe740e67847b">IncludeKind::IncludeLocal</a>     | <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8aaf0b778b0e0af69011f06c8734fdb891">IncludeKind::ImportLocalObjC</a>  | <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a2dbc22c9108714bfd4417e558b7b82e2">IncludeKind::ImportLocal</a>;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae7139b08c0c942d65c6bcb8402a8b142">generateSqlite3ForFile</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a541a7f1681d4e6c18ba0fb4902f2b9d3">generateXMLForFile</a>, <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a7af9a5628546bbd3c1e8aff7d1b102db">includeOpen</a>, <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#aa2872f3c154bf7c3cfa319bcf83e3fac">includeTagFileAttributes</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a8961a6e2496115a7cde0222c4ee213d6">writeIncludeInfo</a>.
</div>
</div>

### IncludeKind&#95;ObjCMask {#a0f83257cf012e77790524a29bd32c037}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t IncludeKind_ObjCMask = <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a850b5d27cd4e40d0405c4b7a0d76ab94">IncludeKind::ImportSystemObjC</a> | <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8aaf0b778b0e0af69011f06c8734fdb891">IncludeKind::ImportLocalObjC</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00067">67</a> of file <a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0f83257cf012e77790524a29bd32c037">67</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">constexpr</span><span class="doxyHighlight"> uint32_t <a href="#a0f83257cf012e77790524a29bd32c037">IncludeKind_ObjCMask</a>   = <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a850b5d27cd4e40d0405c4b7a0d76ab94">IncludeKind::ImportSystemObjC</a> | <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8aaf0b778b0e0af69011f06c8734fdb891">IncludeKind::ImportLocalObjC</a>;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a29b4da465017ea752ef6d376a091a5b8">includeStatement</a> and <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#aa2872f3c154bf7c3cfa319bcf83e3fac">includeTagFileAttributes</a>.
</div>
</div>

### IncludeKind&#95;SystemMask {#aaa33e018d950b5a3ce71969b727fbc66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t IncludeKind_SystemMask = <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8ab0ead0aebf84f57889aab39d528f34b4">IncludeKind::IncludeSystem</a>    | <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a850b5d27cd4e40d0405c4b7a0d76ab94">IncludeKind::ImportSystemObjC</a> | <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8ac597d64b5224025af7bef1aad3172845">IncludeKind::ImportSystem</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00064">64</a> of file <a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaa33e018d950b5a3ce71969b727fbc66">64</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">constexpr</span><span class="doxyHighlight"> uint32_t <a href="#aaa33e018d950b5a3ce71969b727fbc66">IncludeKind_SystemMask</a> = <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8ab0ead0aebf84f57889aab39d528f34b4">IncludeKind::IncludeSystem</a>    | <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8a850b5d27cd4e40d0405c4b7a0d76ab94">IncludeKind::ImportSystemObjC</a> | <a href="#a52a98ac8d3b93b98e9371611d4b9dcb8ac597d64b5224025af7bef1aad3172845">IncludeKind::ImportSystem</a>;</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
