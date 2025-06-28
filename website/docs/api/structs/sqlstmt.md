---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/sqlstmt
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `SqlStmt` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct SqlStmt { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fcb633ba93d1ad47b5072781ac76bb8">query</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">sqlite3_stmt *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a780c9b733b885100df0aa733b0c66a37">stmt</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">sqlite3 *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20465204d0f4d947d8df06808d62d3ee">db</a> = nullptr</td>
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


<p>Definition at line 508 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxySectionDef">

## Public Member Attributes

### db {#a20465204d0f4d947d8df06808d62d3ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sqlite3* SqlStmt::db = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#l00511">511</a> of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a20465204d0f4d947d8df06808d62d3ee">511</a></span><span class="doxyLineContent"><span class="doxyHighlight">  sqlite3 *<a href="#a20465204d0f4d947d8df06808d62d3ee">db</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a0ee82255bd720e88690c7cac3581f1df">prepareStatement</a> and <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#aaba2817dbf5f4afbbba5998976dbdab4">step</a>.
</div>
</div>

### query {#a0fcb633ba93d1ad47b5072781ac76bb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* SqlStmt::query = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#l00509">509</a> of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0fcb633ba93d1ad47b5072781ac76bb8">509</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">   *<a href="#a0fcb633ba93d1ad47b5072781ac76bb8">query</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a> and <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a0ee82255bd720e88690c7cac3581f1df">prepareStatement</a>.
</div>
</div>

### stmt {#a780c9b733b885100df0aa733b0c66a37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sqlite3_stmt* SqlStmt::stmt = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#l00510">510</a> of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a780c9b733b885100df0aa733b0c66a37">510</a></span><span class="doxyLineContent"><span class="doxyHighlight">  sqlite3_stmt *<a href="#a780c9b733b885100df0aa733b0c66a37">stmt</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a0ee82255bd720e88690c7cac3581f1df">prepareStatement</a> and <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#aaba2817dbf5f4afbbba5998976dbdab4">step</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this struct was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
