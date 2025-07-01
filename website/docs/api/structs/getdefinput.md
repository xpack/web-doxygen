---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/getdefinput
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `GetDefInput` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct GetDefInput { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/util-h">src/util.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bd3ea4bc572352d9c09a1544ae8efe9">GetDefInput</a> (const QCString &amp;scName, const QCString &amp;memName, const QCString &amp;a)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11e7c24c8b7efbaf60e694bc1cd350ff">scopeName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bfecea6939098158f6f238eb40155b8">memberName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a485cc8b33f7f8e7fd855f6dc8e94a87d">args</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0170bc46f0d1f1fab7a3177ea7ffc63d">forceEmptyScope</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a50bcd2159cda2d38e272e4aba79c74">currentFile</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e145754020e4907684f7363696d3634">checkCV</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2036bcaa16603f1a5c8006c91a0fa05b">insideCode</a> = false</td>
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


Definition at line 109 of file <a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>.

<div class="doxySectionDef">

## Public Constructors

### GetDefInput() {#a3bd3ea4bc572352d9c09a1544ae8efe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GetDefInput::GetDefInput (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; scName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; memName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; a)</td>
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



Definition at line 111 of file <a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3bd3ea4bc572352d9c09a1544ae8efe9">111</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a3bd3ea4bc572352d9c09a1544ae8efe9">GetDefInput</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;scName,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;memName,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;a) :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a11e7c24c8b7efbaf60e694bc1cd350ff">scopeName</a>(scName),<a href="#a4bfecea6939098158f6f238eb40155b8">memberName</a>(memName),<a href="#a485cc8b33f7f8e7fd855f6dc8e94a87d">args</a>(a) {}</span></span></div>

</div>


References <a href="#a485cc8b33f7f8e7fd855f6dc8e94a87d">args</a>, <a href="#a4bfecea6939098158f6f238eb40155b8">memberName</a> and <a href="#a11e7c24c8b7efbaf60e694bc1cd350ff">scopeName</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### args {#a485cc8b33f7f8e7fd855f6dc8e94a87d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString GetDefInput::args</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 115 of file <a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a485cc8b33f7f8e7fd855f6dc8e94a87d">115</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a485cc8b33f7f8e7fd855f6dc8e94a87d">args</a>;</span></span></div>

</div>


Referenced by <a href="#a3bd3ea4bc572352d9c09a1544ae8efe9">GetDefInput</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab5d70bf9e42fcc2766efb0655ff317e0">getDefs</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a92aa0c495ca4eb835bb914dbb5fefa35">getDefsNew</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>.
</div>
</div>

### checkCV {#a3e145754020e4907684f7363696d3634}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GetDefInput::checkCV = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 118 of file <a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3e145754020e4907684f7363696d3634">118</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a3e145754020e4907684f7363696d3634">checkCV</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/docparser/#aa75d3dc0424c6b364222f7f357406e62">DocParser::findDocsForMemberOrCompound</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab5d70bf9e42fcc2766efb0655ff317e0">getDefs</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a92aa0c495ca4eb835bb914dbb5fefa35">getDefsNew</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2bb57904806cf057f0d38374a63209ea">resolveRef</a>.
</div>
</div>

### currentFile {#a0a50bcd2159cda2d38e272e4aba79c74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FileDef* GetDefInput::currentFile = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 117 of file <a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0a50bcd2159cda2d38e272e4aba79c74">117</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *<a href="#a0a50bcd2159cda2d38e272e4aba79c74">currentFile</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab5d70bf9e42fcc2766efb0655ff317e0">getDefs</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a92aa0c495ca4eb835bb914dbb5fefa35">getDefsNew</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#aa3a78394ea3d7dee51703f8f0c1e3984">getLinkInScope</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a7c3e45cceb9eb4446d360eb8620eef8c">getLinkInScope</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2bb57904806cf057f0d38374a63209ea">resolveRef</a>.
</div>
</div>

### forceEmptyScope {#a0170bc46f0d1f1fab7a3177ea7ffc63d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GetDefInput::forceEmptyScope = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 116 of file <a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0170bc46f0d1f1fab7a3177ea7ffc63d">116</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a0170bc46f0d1f1fab7a3177ea7ffc63d">forceEmptyScope</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab5d70bf9e42fcc2766efb0655ff317e0">getDefs</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2bb57904806cf057f0d38374a63209ea">resolveRef</a>.
</div>
</div>

### insideCode {#a2036bcaa16603f1a5c8006c91a0fa05b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GetDefInput::insideCode = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 119 of file <a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2036bcaa16603f1a5c8006c91a0fa05b">119</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a2036bcaa16603f1a5c8006c91a0fa05b">insideCode</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a92aa0c495ca4eb835bb914dbb5fefa35">getDefsNew</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#aa3a78394ea3d7dee51703f8f0c1e3984">getLinkInScope</a> and <a href="/web-doxygen/docs/api/files/src/code-l/#a7c3e45cceb9eb4446d360eb8620eef8c">getLinkInScope</a>.
</div>
</div>

### memberName {#a4bfecea6939098158f6f238eb40155b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString GetDefInput::memberName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 114 of file <a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4bfecea6939098158f6f238eb40155b8">114</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a4bfecea6939098158f6f238eb40155b8">memberName</a>;</span></span></div>

</div>


Referenced by <a href="#a3bd3ea4bc572352d9c09a1544ae8efe9">GetDefInput</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab5d70bf9e42fcc2766efb0655ff317e0">getDefs</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a92aa0c495ca4eb835bb914dbb5fefa35">getDefsNew</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>.
</div>
</div>

### scopeName {#a11e7c24c8b7efbaf60e694bc1cd350ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString GetDefInput::scopeName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 113 of file <a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a11e7c24c8b7efbaf60e694bc1cd350ff">113</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a11e7c24c8b7efbaf60e694bc1cd350ff">scopeName</a>;</span></span></div>

</div>


Referenced by <a href="#a3bd3ea4bc572352d9c09a1544ae8efe9">GetDefInput</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab5d70bf9e42fcc2766efb0655ff317e0">getDefs</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a92aa0c495ca4eb835bb914dbb5fefa35">getDefsNew</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a> and <a href="/web-doxygen/docs/api/files/src/code-l/#a7c3e45cceb9eb4446d360eb8620eef8c">getLinkInScope</a>.
</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/util-h">util.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
