---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/fortranscanner-l
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `fortranscanner.l` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;stdint.h&gt;
#include &lt;map&gt;
#include &lt;vector&gt;
#include &lt;algorithm&gt;
#include &lt;stdio.h&gt;
#include &lt;stdlib.h&gt;
#include &lt;assert.h&gt;
#include &lt;ctype.h&gt;
#include "<a href="/web-doxygen/docs/api/files/src/fortranscanner-h">fortranscanner.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/entry-h">entry.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/defargs-h">defargs.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/language-h">language.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/commentscan-h">commentscan.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/pre-h">pre.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/markdown-h">markdown.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-lex-h">doxygen_lex.h</a>"
#include "fortranscanner.l.h"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/symbolmodifiers">SymbolModifiers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holds yyextra-&gt;modifiers (ie attributes) for one symbol (variable, function, etc) <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/commentinprepass">CommentInPrepass</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/fortranscanneryy-state">fortranscannerYY_state</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/fortranoutlineparser/private">Private</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">yyguts_t * <a href="#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ScanVar { <a href="#a238692c76adb8cefb158cf28754f52d6">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">InterfaceType { <a href="#af1ef2c97e255bd7f21d3b7614b283d9d">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a094e0d8bb2b1b92d7a51f8370c76a018">getAmpersandAtTheStart</a> (const char *buf, int length)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57a320e051e7596c3106c1a95ae02915">getAmpOrExclAtTheEnd</a> (const char *buf, int length, char ch)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25c73dbd285ac4ed23985634ad1a9cab">extractFromParens</a> (const QCString &amp;name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac494d47958d1f5413e97e355624ca8db">extractBind</a> (const QCString &amp;name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5edfc25f0c460f3263fdb340f7a02b03">yyread</a> (yyscan_t yyscanner, char *buf, int max_size)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f8584604e877b6eb570db94e3692a92">startCommentBlock</a> (yyscan_t yyscanner, bool)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a> (yyscan_t yyscanner, const QCString &amp;doc, bool brief)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c5f6e8cda9aa291a041f511f3a2329a">subrHandleCommentBlock</a> (yyscan_t yyscanner, const QCString &amp;doc, bool brief)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle parameter description as defined after the declaration of the parameter. <a href="#a6c5f6e8cda9aa291a041f511f3a2329a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a746c69943bdf7ff71cbd6e6aa44b875d">subrHandleCommentBlockResult</a> (yyscan_t yyscanner, const QCString &amp;doc, bool brief)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle result description as defined after the declaration of the parameter. <a href="#a746c69943bdf7ff71cbd6e6aa44b875d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f86638786429418e4c584f9b98ec3d4">addCurrentEntry</a> (yyscan_t yyscanner, bool case_insens)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>adds yyextra-&gt;current entry to yyextra-&gt;current_root and creates new yyextra-&gt;current <a href="#a1f86638786429418e4c584f9b98ec3d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ad5866bbc8d144423fe0e3f54ecb0cf">addModule</a> (yyscan_t yyscanner, const QCString &amp;name=QCString(), bool isModule=FALSE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abed27cdfdbc0b2f7e850aff746420010">addSubprogram</a> (yyscan_t yyscanner, const QCString &amp;text)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac57b965357c0cd3448f8bac617563e29">addInterface</a> (yyscan_t yyscanner, QCString name, InterfaceType type)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/structs/argument">Argument</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c050f3e9b9e8855bad36862ab3173ba">getParameter</a> (yyscan_t yyscanner, const QCString &amp;name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b2ca28396c488d5a08ead21731ed2c2">scanner_abort</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49e7bafaa071ffbe937ec1a85c484828">startScope</a> (yyscan_t yyscanner, Entry *scope)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c191151631efdf0d25fc7967f6b0434">endScope</a> (yyscan_t yyscanner, Entry *scope, bool isGlobalRoot=FALSE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bd7068dc789461b065785069d7251aa">copyEntry</a> (std::shared_ptr&lt; Entry &gt; dest, const std::shared_ptr&lt; Entry &gt; &amp;src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>used to copy entry to an interface module procedure <a href="#a6bd7068dc789461b065785069d7251aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a117a119a3d5a5d0dc330e3d6eade5c04">resolveModuleProcedures</a> (yyscan_t yyscanner, Entry *current_root)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>fill empty interface module procedures with info from corresponding module subprogs <a href="#a117a119a3d5a5d0dc330e3d6eade5c04">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e6aba48ce1a2e82d0401f666a45c1d3">resolveTypeBoundProcedures</a> (Entry *scope)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afac5fd6d0047c7134afcef46db6a4ab8">truncatePrepass</a> (yyscan_t yyscanner, int index)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab536b3c2ec35df931a4fce0dbf2e1420">pushBuffer</a> (yyscan_t yyscanner, const QCString &amp;buffer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66d8cb63c9460264113152b30a8c4afb">popBuffer</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static const <a href="/web-doxygen/docs/api/structs/commentinprepass">CommentInPrepass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58823d73b17b4a3c6b782a7e14904c77">locatePrepassComment</a> (yyscan_t yyscanner, int from, int to)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e2f432a75f34796b2cdda24ee7cb9b0">updateVariablePrepassComment</a> (yyscan_t yyscanner, int from, int to)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a146a464d8664e6fe5cd764e866726ac1">newLine</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affe329b2bcd94b04290e03afad9c97c5">initEntry</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6458e40b3ca285dc65cd5df59d63e5a5">stateToString</a> (int state)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b4acd8f05e7bebf0528ec710692f758">computeIndent</a> (const char *s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb5f8818546103e3b804ab8606b52c4a">getLexerFILE</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d80d8ed8c19744ed31163f6e7525e54">yylex</a> (yyscan_t yyscanner)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>fortran parsing states <a href="#a1d80d8ed8c19744ed31163f6e7525e54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ac86b7091ebd73f18ce4d662cd75908">insertCharacter</a> (char *contents, int length, int pos, char c)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3318a36567de3b1f36059e387a801863">prepassFixedForm</a> (const char *contents, int *hasContLine, int fixedCommentAfter)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/structs/argument">Argument</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68f2fb9c7c23aa0812e4e66ee782baee">findArgument</a> (Entry *subprog, QCString name, bool byTypeName=FALSE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a521d11026f20bc253b154ffec71d4748">applyModifiers</a> (QCString typeName, const SymbolModifiers &amp;mdfs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53849d7f7a3b6511175fd2c40be515b8">applyModifiers</a> (Argument *arg, const SymbolModifiers &amp;mdfs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae88a4d2b7afc5a1c3def9d800cc5863e">applyModifiers</a> (Entry *ent, const SymbolModifiers &amp;mdfs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a451cff71879d11897907cc8c2102bdcb">initParser</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4481d3eae9a04af883d868f23c4cbffc">parseMain</a> (yyscan_t yyscanner, const QCString &amp;fileName, const char *fileBuf, const std::shared_ptr&lt; Entry &gt; &amp;rt, FortranFormat format)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70244a0858d0601f2df6435673f01462">directionStrs</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ab2ac9fbdd02519455880a47568829b">directionParam</a>[] = ...</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d5508008cac8fb66fca3baa4e9b6584">YY_TYPEDEF_YY_SCANNER_T</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>(x)&nbsp;&nbsp;&nbsp;do { } while(0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85523a0c7d95c059d251b4e9829947aa">YY_NO_INPUT</a>&nbsp;&nbsp;&nbsp;1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae78ac56cd1f29572e967ed7636952d15">YY_NO_UNISTD_H</a>&nbsp;&nbsp;&nbsp;1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacfdca45fa4beb8b06172525a53c424a">YY_INPUT</a>(buf, result, max_size)&nbsp;&nbsp;&nbsp;result=<a href="/web-doxygen/docs/api/files/src/code-l/#a5edfc25f0c460f3263fdb340f7a02b03">yyread</a>(yyscanner,buf,max_size);</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6198b2fcf96178b24ad4efff2a3debb0">YY_USER_ACTION</a>&nbsp;&nbsp;&nbsp;yyextra-&gt;colNr+=(int)yyleng;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dfbc2208b3f32fc3d8dca63bd941c08">INVALID_ENTRY</a>&nbsp;&nbsp;&nbsp;((<a href="/web-doxygen/docs/api/classes/entry">Entry</a>*)0x8)</td>
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

### yyscan\_t {#a9484188abbc459dafcbd4c96425fa70b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef yyguts_t* yyscan_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9484188abbc459dafcbd4c96425fa70b">50</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">typedef</span><span class="doxyHighlight"> yyguts_t *<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a>;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### InterfaceType {#af1ef2c97e255bd7f21d3b7614b283d9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum InterfaceType </td>
</tr>
</table>
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
<td class="doxyEnumItemName">IF_NONE<a id="af1ef2c97e255bd7f21d3b7614b283d9da46dbf2e0f925aa7b0f3f9edd25acf5e6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IF_SPECIFIC<a id="af1ef2c97e255bd7f21d3b7614b283d9da89f0d2424cf9ae9c82a868376ceb29b9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IF_GENERIC<a id="af1ef2c97e255bd7f21d3b7614b283d9da5d1432a4cae2b52cafb669c901908aa5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IF_ABSTRACT<a id="af1ef2c97e255bd7f21d3b7614b283d9daa33f8bd097d7a6cd1210bed71c5cb937"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 87 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af1ef2c97e255bd7f21d3b7614b283d9daa33f8bd097d7a6cd1210bed71c5cb937">87</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">enum</span><span class="doxyHighlight"> <a href="#af1ef2c97e255bd7f21d3b7614b283d9d">InterfaceType</a> { <a href="#af1ef2c97e255bd7f21d3b7614b283d9da46dbf2e0f925aa7b0f3f9edd25acf5e6">IF_NONE</a>, <a href="#af1ef2c97e255bd7f21d3b7614b283d9da89f0d2424cf9ae9c82a868376ceb29b9">IF_SPECIFIC</a>, <a href="#af1ef2c97e255bd7f21d3b7614b283d9da5d1432a4cae2b52cafb669c901908aa5">IF_GENERIC</a>, <a href="#af1ef2c97e255bd7f21d3b7614b283d9daa33f8bd097d7a6cd1210bed71c5cb937">IF_ABSTRACT</a> };</span></span></div>

</div>

</div>
</div>

### ScanVar {#a238692c76adb8cefb158cf28754f52d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum ScanVar </td>
</tr>
</table>
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
<td class="doxyEnumItemName">V_IGNORE<a id="a238692c76adb8cefb158cf28754f52d6a2e626c4ec60ad2b9514c8984aa1eb3ec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">V_VARIABLE<a id="a238692c76adb8cefb158cf28754f52d6ab238d5b991ac184d0de8dca5478f5e5c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">V_PARAMETER<a id="a238692c76adb8cefb158cf28754f52d6abc50e5df37302e97005583c6ae1257a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">V_RESULT<a id="a238692c76adb8cefb158cf28754f52d6a7dd6f98b4ec3c69395dc0873ae146e40"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 86 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a238692c76adb8cefb158cf28754f52d6">86</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">enum</span><span class="doxyHighlight"> <a href="#a238692c76adb8cefb158cf28754f52d6">ScanVar</a> { <a href="#a238692c76adb8cefb158cf28754f52d6a2e626c4ec60ad2b9514c8984aa1eb3ec">V_IGNORE</a>, <a href="#a238692c76adb8cefb158cf28754f52d6ab238d5b991ac184d0de8dca5478f5e5c">V_VARIABLE</a>, <a href="#a238692c76adb8cefb158cf28754f52d6abc50e5df37302e97005583c6ae1257a3">V_PARAMETER</a>, <a href="#a238692c76adb8cefb158cf28754f52d6a7dd6f98b4ec3c69395dc0873ae146e40">V_RESULT</a>};</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### addCurrentEntry() {#a1f86638786429418e4c584f9b98ec3d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addCurrentEntry (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, bool case_insens)</td>
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

<p>adds yyextra-&gt;current entry to yyextra-&gt;current_root and creates new yyextra-&gt;current</p>

<p>Definition at line 2898 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1f86638786429418e4c584f9b98ec3d4">2898</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1f86638786429418e4c584f9b98ec3d4">addCurrentEntry</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> case_insens)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2899</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2900</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2901</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (case_insens) yyextra-&gt;current-&gt;name = yyextra-&gt;current-&gt;name.lower();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2902</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("===Adding entry %s to %s\n", qPrint(yyextra-&gt;current-&gt;name), qPrint(yyextra-&gt;current_root-&gt;name));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2903</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;last_entry = yyextra-&gt;current;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2904</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current_root-&gt;moveToSubEntryAndRefresh(yyextra-&gt;current);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2905</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#affe329b2bcd94b04290e03afad9c97c5">initEntry</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2906</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#affe329b2bcd94b04290e03afad9c97c5">initEntry</a>.</p>


<p>Referenced by <a href="#ac57b965357c0cd3448f8bac617563e29">addInterface</a>, <a href="#a4ad5866bbc8d144423fe0e3f54ecb0cf">addModule</a> and <a href="#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>.</p>

</div>
</div>

### addInterface() {#ac57b965357c0cd3448f8bac617563e29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addInterface (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name, <a href="#af1ef2c97e255bd7f21d3b7614b283d9d">InterfaceType</a> type)</td>
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




<p>Adds interface to the root entry.</p>



:::info
<p>Code was brought to this procedure from the parser, because there was/is idea to use it in several parts of the parser.</p>
:::


<p>Definition at line 2968 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac57b965357c0cd3448f8bac617563e29">2968</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac57b965357c0cd3448f8bac617563e29">addInterface</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name, <a href="#af1ef2c97e255bd7f21d3b7614b283d9d">InterfaceType</a> type)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2969</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2970</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2971</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START == Start)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2972</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2973</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4ad5866bbc8d144423fe0e3f54ecb0cf">addModule</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2974</span><span class="doxyLineContent"><span class="doxyHighlight">    yy_push_state(ModuleBody,yyscanner); </span><span class="doxyHighlightComment">//anon program</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2975</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2976</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2977</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;section = EntryType::makeClass(); </span><span class="doxyHighlightComment">// was EntryType::Interface;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2978</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;spec = <a href="/web-doxygen/docs/api/classes/typespecifier">TypeSpecifier</a>().setInterface(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2979</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;name = name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2980</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2981</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (type)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2982</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2983</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#af1ef2c97e255bd7f21d3b7614b283d9daa33f8bd097d7a6cd1210bed71c5cb937">IF_ABSTRACT</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2984</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;current-&gt;type = </span><span class="doxyHighlightStringLiteral">"abstract"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2985</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2986</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2987</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#af1ef2c97e255bd7f21d3b7614b283d9da5d1432a4cae2b52cafb669c901908aa5">IF_GENERIC</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2988</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;current-&gt;type = </span><span class="doxyHighlightStringLiteral">"generic"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2989</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2990</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2991</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#af1ef2c97e255bd7f21d3b7614b283d9da89f0d2424cf9ae9c82a868376ceb29b9">IF_SPECIFIC</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2992</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#af1ef2c97e255bd7f21d3b7614b283d9da46dbf2e0f925aa7b0f3f9edd25acf5e6">IF_NONE</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2993</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2994</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;current-&gt;type = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2995</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2996</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2997</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/* if type is part of a module, mod name is necessary for output */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2998</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((yyextra-&gt;current_root) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2999</span><span class="doxyLineContent"><span class="doxyHighlight">      (yyextra-&gt;current_root-&gt;section.isClass() ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3000</span><span class="doxyLineContent"><span class="doxyHighlight">       yyextra-&gt;current_root-&gt;section.isNamespace()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3001</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3002</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;name= yyextra-&gt;current_root-&gt;name + </span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight"> + yyextra-&gt;current-&gt;name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3003</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3004</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3005</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;fileName = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3006</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;bodyLine  = yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3007</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;startLine  = yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3008</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1f86638786429418e4c584f9b98ec3d4">addCurrentEntry</a>(yyscanner,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3009</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a1f86638786429418e4c584f9b98ec3d4">addCurrentEntry</a>, <a href="#a4ad5866bbc8d144423fe0e3f54ecb0cf">addModule</a>, <a href="#af1ef2c97e255bd7f21d3b7614b283d9daa33f8bd097d7a6cd1210bed71c5cb937">IF_ABSTRACT</a>, <a href="#af1ef2c97e255bd7f21d3b7614b283d9da5d1432a4cae2b52cafb669c901908aa5">IF_GENERIC</a>, <a href="#af1ef2c97e255bd7f21d3b7614b283d9da46dbf2e0f925aa7b0f3f9edd25acf5e6">IF_NONE</a> and <a href="#af1ef2c97e255bd7f21d3b7614b283d9da89f0d2424cf9ae9c82a868376ceb29b9">IF_SPECIFIC</a>.</p>

</div>
</div>

### addModule() {#a4ad5866bbc8d144423fe0e3f54ecb0cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addModule (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), bool isModule=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
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



<p>Definition at line 2908 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4ad5866bbc8d144423fe0e3f54ecb0cf">2908</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ad5866bbc8d144423fe0e3f54ecb0cf">addModule</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isModule)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2909</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2910</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2911</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr, </span><span class="doxyHighlightStringLiteral">"0=========&gt; got module %s\n"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(name)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2912</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2913</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isModule)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2914</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;section = EntryType::makeNamespace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2915</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2916</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;section = EntryType::makeFunction();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2917</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2918</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!name.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2919</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2920</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;name = name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2921</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2922</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2923</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2924</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fname = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2925</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> index = std::max(fname.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">), fname.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2926</span><span class="doxyLineContent"><span class="doxyHighlight">    fname = fname.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(fname.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-index-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2927</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;mainPrograms) fname += </span><span class="doxyHighlightStringLiteral">"__"</span><span class="doxyHighlight"> + <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">setNum</a>(yyextra-&gt;mainPrograms);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2928</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;mainPrograms++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2929</span><span class="doxyLineContent"><span class="doxyHighlight">    fname = fname.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(</span><span class="doxyHighlightStringLiteral">"__"</span><span class="doxyHighlight">).<a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">append</a>(</span><span class="doxyHighlightStringLiteral">"__"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2930</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;name = <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(fname, </span><span class="doxyHighlightStringLiteral">"."</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2931</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2932</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;type = </span><span class="doxyHighlightStringLiteral">"program"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2933</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;fileName  = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2934</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;bodyLine  = yyextra-&gt;lineNr; </span><span class="doxyHighlightComment">// used for source reference</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2935</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;startLine  = yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2936</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;protection = Protection::Public ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2937</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1f86638786429418e4c584f9b98ec3d4">addCurrentEntry</a>(yyscanner,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2938</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a49e7bafaa071ffbe937ec1a85c484828">startScope</a>(yyscanner,yyextra-&gt;last_entry.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2939</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a1f86638786429418e4c584f9b98ec3d4">addCurrentEntry</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">QCString::append</a>, <a href="#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">QCString::prepend</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">QCString::right</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">QCString::setNum</a>, <a href="#a49e7bafaa071ffbe937ec1a85c484828">startScope</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>.</p>


<p>Referenced by <a href="#ac57b965357c0cd3448f8bac617563e29">addInterface</a>.</p>

</div>
</div>

### addSubprogram() {#abed27cdfdbc0b2f7e850aff746420010}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addSubprogram (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
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



<p>Definition at line 2942 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abed27cdfdbc0b2f7e850aff746420010">2942</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abed27cdfdbc0b2f7e850aff746420010">addSubprogram</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2943</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2944</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2945</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr,</span><span class="doxyHighlightStringLiteral">"1=========&gt; got subprog, type: %s\n"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(text)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2946</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;subrCurrent.push_back(yyextra-&gt;current);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2947</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;section = EntryType::makeFunction();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2948</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> subtype = text; subtype=subtype.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2949</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;functionLine = (subtype.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"function"</span><span class="doxyHighlight">) != -1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2950</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;type += </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> + subtype;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2951</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;type = yyextra-&gt;current-&gt;type.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2952</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;ifType == <a href="#af1ef2c97e255bd7f21d3b7614b283d9daa33f8bd097d7a6cd1210bed71c5cb937">IF_ABSTRACT</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2953</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2954</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;virt = Specifier::Virtual;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2955</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2956</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;fileName  = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2957</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;bodyLine  = yyextra-&gt;lineNr; </span><span class="doxyHighlightComment">// used for source reference start of body of routine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2958</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;startLine  = yyextra-&gt;lineNr; </span><span class="doxyHighlightComment">// used for source reference start of definition</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2959</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;args.<a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">clear</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2960</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;argList.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2961</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;docBlock.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2962</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">QCString::clear</a>, <a href="#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="#af1ef2c97e255bd7f21d3b7614b283d9daa33f8bd097d7a6cd1210bed71c5cb937">IF_ABSTRACT</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>.</p>

</div>
</div>

### applyModifiers() {#a521d11026f20bc253b154ffec71d4748}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString applyModifiers (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> typeName, const <a href="/web-doxygen/docs/api/structs/symbolmodifiers">SymbolModifiers</a> &amp; mdfs)</td>
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




<p>Apply yyextra-&gt;modifiers stored in <em>mdfs</em> to the <em>typeName</em> string.</p>


<p>Definition at line 2411 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a521d11026f20bc253b154ffec71d4748">2411</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a521d11026f20bc253b154ffec71d4748">applyModifiers</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> typeName, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/symbolmodifiers">SymbolModifiers</a>&amp; mdfs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2412</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2413</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a3e997f886dd5832f1f8ae64aadca020c">dimension</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2414</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2415</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!typeName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) typeName += </span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2416</span><span class="doxyLineContent"><span class="doxyHighlight">    typeName += mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a3e997f886dd5832f1f8ae64aadca020c">dimension</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2417</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2418</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a60ca7cc66daff6cdae19b5d4162f77a4">direction</a>!=<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aceec8152eeb6c06b8dbe03ef14fed6a4ace26f25fe9aa85a4d1b93a09af862d8b">SymbolModifiers::NONE_D</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2419</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2420</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!typeName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) typeName += </span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2421</span><span class="doxyLineContent"><span class="doxyHighlight">    typeName += <a href="#a70244a0858d0601f2df6435673f01462">directionStrs</a>[mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a60ca7cc66daff6cdae19b5d4162f77a4">direction</a>];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2422</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2423</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aa6211c1be3fd479e53a26b498e5fc94b">optional</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2424</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2425</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!typeName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) typeName += </span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2426</span><span class="doxyLineContent"><span class="doxyHighlight">    typeName += </span><span class="doxyHighlightStringLiteral">"optional"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2427</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2428</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a3a7425ed3b345a52a97a37850cecf54d">allocatable</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2429</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2430</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!typeName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) typeName += </span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2431</span><span class="doxyLineContent"><span class="doxyHighlight">    typeName += </span><span class="doxyHighlightStringLiteral">"allocatable"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2432</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2433</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a3187a1ff0724dbcff6cf591cd815bd78">external</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2434</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2435</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!typeName.<a href="/web-doxygen/docs/api/classes/qcstring/#aeeedb2810a85c682c2f2a86bcd2355a7">contains</a>(</span><span class="doxyHighlightStringLiteral">"external"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2436</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2437</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!typeName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) typeName += </span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2438</span><span class="doxyLineContent"><span class="doxyHighlight">      typeName += </span><span class="doxyHighlightStringLiteral">"external"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2439</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2440</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2441</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a9df901b470a76a04f234ff6863f1dca1">intrinsic</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2442</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2443</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!typeName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) typeName += </span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2444</span><span class="doxyLineContent"><span class="doxyHighlight">    typeName += </span><span class="doxyHighlightStringLiteral">"intrinsic"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2445</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2446</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a3237efa8834ef0f47b9e14284e1db710">parameter</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2447</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2448</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!typeName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) typeName += </span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2449</span><span class="doxyLineContent"><span class="doxyHighlight">    typeName += </span><span class="doxyHighlightStringLiteral">"parameter"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2450</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2451</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#ac783671e5116d72c93935bb9bf7c2cb8">pointer</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2452</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2453</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!typeName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) typeName += </span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2454</span><span class="doxyLineContent"><span class="doxyHighlight">    typeName += </span><span class="doxyHighlightStringLiteral">"pointer"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2455</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2456</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a10971e3ef27a2e20c71a769c6d237807">target</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2457</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2458</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!typeName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) typeName += </span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2459</span><span class="doxyLineContent"><span class="doxyHighlight">    typeName += </span><span class="doxyHighlightStringLiteral">"target"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2460</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2461</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a25d1321a621eb7496f4e2e3ac99b0842">save</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2462</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2463</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!typeName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) typeName += </span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2464</span><span class="doxyLineContent"><span class="doxyHighlight">    typeName += </span><span class="doxyHighlightStringLiteral">"save"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2465</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2466</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a2aad749396a02ead46410d78da584e9a">deferred</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2467</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2468</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!typeName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) typeName += </span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2469</span><span class="doxyLineContent"><span class="doxyHighlight">    typeName += </span><span class="doxyHighlightStringLiteral">"deferred"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2470</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2471</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a1500769a8e0054bb142980765556c923">nonoverridable</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2472</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2473</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!typeName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) typeName += </span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2474</span><span class="doxyLineContent"><span class="doxyHighlight">    typeName += </span><span class="doxyHighlightStringLiteral">"non_overridable"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2475</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2476</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#adcd51442f97dbef24a66a86ecd231fda">nopass</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2477</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2478</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!typeName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) typeName += </span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2479</span><span class="doxyLineContent"><span class="doxyHighlight">    typeName += </span><span class="doxyHighlightStringLiteral">"nopass"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2480</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2481</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#af73c8f692ea33c3d1250adc8e4a1b946">pass</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2482</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2483</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!typeName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) typeName += </span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2484</span><span class="doxyLineContent"><span class="doxyHighlight">    typeName += </span><span class="doxyHighlightStringLiteral">"pass"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2485</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aa087f0ac7c16038e40ba11ad1b66c635">passVar</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2486</span><span class="doxyLineContent"><span class="doxyHighlight">      typeName += </span><span class="doxyHighlightStringLiteral">"("</span><span class="doxyHighlight"> + mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aa087f0ac7c16038e40ba11ad1b66c635">passVar</a> + </span><span class="doxyHighlightStringLiteral">")"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2487</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2488</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a951fe24444c6f9225d468ce28f69c044">bindVar</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2489</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2490</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!typeName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) typeName += </span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2491</span><span class="doxyLineContent"><span class="doxyHighlight">    typeName += mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a951fe24444c6f9225d468ce28f69c044">bindVar</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2492</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2493</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#add511aaa15123dd20538a4e23415b91e">protection</a> == <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a6c76745fa39de2b90353729fe62c6708ae0d7c512c0fe421f9d64e801771f9fb3">SymbolModifiers::PUBLIC</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2494</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2495</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!typeName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) typeName += </span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2496</span><span class="doxyLineContent"><span class="doxyHighlight">    typeName += </span><span class="doxyHighlightStringLiteral">"public"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2497</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2498</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#add511aaa15123dd20538a4e23415b91e">protection</a> == <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a6c76745fa39de2b90353729fe62c6708a3af5ff26f32ecc18b95bd75082789867">SymbolModifiers::PRIVATE</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2499</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2500</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!typeName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) typeName += </span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2501</span><span class="doxyLineContent"><span class="doxyHighlight">    typeName += </span><span class="doxyHighlightStringLiteral">"private"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2502</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2503</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a391410448831f7e0e967635319e16d73">protect</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2504</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2505</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!typeName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) typeName += </span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2506</span><span class="doxyLineContent"><span class="doxyHighlight">    typeName += </span><span class="doxyHighlightStringLiteral">"protected"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2507</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2508</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#af53aa7a23a005f7e861977192ea549ad">contiguous</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2509</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2510</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!typeName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) typeName += </span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2511</span><span class="doxyLineContent"><span class="doxyHighlight">    typeName += </span><span class="doxyHighlightStringLiteral">"contiguous"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2512</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2513</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a6034722aa4017fca0054462b41b4aa97">volat</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2514</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2515</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!typeName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) typeName += </span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2516</span><span class="doxyLineContent"><span class="doxyHighlight">    typeName += </span><span class="doxyHighlightStringLiteral">"volatile"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2517</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2518</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a18f0ffb7109d897a5ba0eb58ac3ace45">value</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2519</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2520</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!typeName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) typeName += </span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2521</span><span class="doxyLineContent"><span class="doxyHighlight">    typeName += </span><span class="doxyHighlightStringLiteral">"value"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2522</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2523</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2524</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> typeName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2525</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a3a7425ed3b345a52a97a37850cecf54d">SymbolModifiers::allocatable</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a951fe24444c6f9225d468ce28f69c044">SymbolModifiers::bindVar</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aeeedb2810a85c682c2f2a86bcd2355a7">QCString::contains</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#af53aa7a23a005f7e861977192ea549ad">SymbolModifiers::contiguous</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a2aad749396a02ead46410d78da584e9a">SymbolModifiers::deferred</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a3e997f886dd5832f1f8ae64aadca020c">SymbolModifiers::dimension</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a60ca7cc66daff6cdae19b5d4162f77a4">SymbolModifiers::direction</a>, <a href="#a70244a0858d0601f2df6435673f01462">directionStrs</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a3187a1ff0724dbcff6cf591cd815bd78">SymbolModifiers::external</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a9df901b470a76a04f234ff6863f1dca1">SymbolModifiers::intrinsic</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aceec8152eeb6c06b8dbe03ef14fed6a4ace26f25fe9aa85a4d1b93a09af862d8b">SymbolModifiers::NONE_D</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a1500769a8e0054bb142980765556c923">SymbolModifiers::nonoverridable</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#adcd51442f97dbef24a66a86ecd231fda">SymbolModifiers::nopass</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aa6211c1be3fd479e53a26b498e5fc94b">SymbolModifiers::optional</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a3237efa8834ef0f47b9e14284e1db710">SymbolModifiers::parameter</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#af73c8f692ea33c3d1250adc8e4a1b946">SymbolModifiers::pass</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aa087f0ac7c16038e40ba11ad1b66c635">SymbolModifiers::passVar</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#ac783671e5116d72c93935bb9bf7c2cb8">SymbolModifiers::pointer</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a6c76745fa39de2b90353729fe62c6708a3af5ff26f32ecc18b95bd75082789867">SymbolModifiers::PRIVATE</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a391410448831f7e0e967635319e16d73">SymbolModifiers::protect</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#add511aaa15123dd20538a4e23415b91e">SymbolModifiers::protection</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a6c76745fa39de2b90353729fe62c6708ae0d7c512c0fe421f9d64e801771f9fb3">SymbolModifiers::PUBLIC</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a25d1321a621eb7496f4e2e3ac99b0842">SymbolModifiers::save</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a10971e3ef27a2e20c71a769c6d237807">SymbolModifiers::target</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a18f0ffb7109d897a5ba0eb58ac3ace45">SymbolModifiers::value</a> and <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a6034722aa4017fca0054462b41b4aa97">SymbolModifiers::volat</a>.</p>


<p>Referenced by <a href="#a53849d7f7a3b6511175fd2c40be515b8">applyModifiers</a>, <a href="#ae88a4d2b7afc5a1c3def9d800cc5863e">applyModifiers</a> and <a href="#a5c191151631efdf0d25fc7967f6b0434">endScope</a>.</p>

</div>
</div>

### applyModifiers() {#a53849d7f7a3b6511175fd2c40be515b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void applyModifiers (<a href="/web-doxygen/docs/api/structs/argument">Argument</a> * arg, const <a href="/web-doxygen/docs/api/structs/symbolmodifiers">SymbolModifiers</a> &amp; mdfs)</td>
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




<p>Apply yyextra-&gt;modifiers stored in <em>mdfs</em> to the <em>arg</em> argument.</p>


<p>Definition at line 2528 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a53849d7f7a3b6511175fd2c40be515b8">2528</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a521d11026f20bc253b154ffec71d4748">applyModifiers</a>(<a href="/web-doxygen/docs/api/structs/argument">Argument</a> *arg, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/symbolmodifiers">SymbolModifiers</a>&amp; mdfs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2529</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2530</span><span class="doxyLineContent"><span class="doxyHighlight">  arg-&gt;<a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">type</a> = <a href="#a521d11026f20bc253b154ffec71d4748">applyModifiers</a>(arg-&gt;<a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">type</a>, mdfs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2531</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a521d11026f20bc253b154ffec71d4748">applyModifiers</a> and <a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">Argument::type</a>.</p>

</div>
</div>

### applyModifiers() {#ae88a4d2b7afc5a1c3def9d800cc5863e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void applyModifiers (<a href="/web-doxygen/docs/api/classes/entry">Entry</a> * ent, const <a href="/web-doxygen/docs/api/structs/symbolmodifiers">SymbolModifiers</a> &amp; mdfs)</td>
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




<p>Apply yyextra-&gt;modifiers stored in <em>mdfs</em> to the <em>ent</em> entry.</p>


<p>Definition at line 2534 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae88a4d2b7afc5a1c3def9d800cc5863e">2534</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a521d11026f20bc253b154ffec71d4748">applyModifiers</a>(<a href="/web-doxygen/docs/api/classes/entry">Entry</a> *ent, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/symbolmodifiers">SymbolModifiers</a>&amp; mdfs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2535</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2536</span><span class="doxyLineContent"><span class="doxyHighlight">  ent-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a79a9b5736630c3769e645f71dc357b9f">type</a> = <a href="#a521d11026f20bc253b154ffec71d4748">applyModifiers</a>(ent-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a79a9b5736630c3769e645f71dc357b9f">type</a>, mdfs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2537</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2538</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#add511aaa15123dd20538a4e23415b91e">protection</a> == <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a6c76745fa39de2b90353729fe62c6708ae0d7c512c0fe421f9d64e801771f9fb3">SymbolModifiers::PUBLIC</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2539</span><span class="doxyLineContent"><span class="doxyHighlight">    ent-&gt;<a href="/web-doxygen/docs/api/classes/entry/#acbb1b4e99978a710863cf9cab6c90553">protection</a> = Protection::Public;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2540</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#add511aaa15123dd20538a4e23415b91e">protection</a> == <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a6c76745fa39de2b90353729fe62c6708a3af5ff26f32ecc18b95bd75082789867">SymbolModifiers::PRIVATE</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2541</span><span class="doxyLineContent"><span class="doxyHighlight">    ent-&gt;<a href="/web-doxygen/docs/api/classes/entry/#acbb1b4e99978a710863cf9cab6c90553">protection</a> = Protection::Private;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2542</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2543</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a1500769a8e0054bb142980765556c923">nonoverridable</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2544</span><span class="doxyLineContent"><span class="doxyHighlight">    ent-&gt;<a href="/web-doxygen/docs/api/classes/entry/#aefd1b83f8d9a4b98c424a92c4bbe2d17">spec</a>.setFinal(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2545</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#adcd51442f97dbef24a66a86ecd231fda">nopass</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2546</span><span class="doxyLineContent"><span class="doxyHighlight">    ent-&gt;<a href="/web-doxygen/docs/api/classes/entry/#ae37f5e4eaf9df2a96650cca128222b09">isStatic</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2547</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdfs.<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a2aad749396a02ead46410d78da584e9a">deferred</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2548</span><span class="doxyLineContent"><span class="doxyHighlight">    ent-&gt;<a href="/web-doxygen/docs/api/classes/entry/#aaf045b9c026443fd192064117083911b">virt</a> = Specifier::Pure;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2549</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a521d11026f20bc253b154ffec71d4748">applyModifiers</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a2aad749396a02ead46410d78da584e9a">SymbolModifiers::deferred</a>, <a href="/web-doxygen/docs/api/classes/entry/#ae37f5e4eaf9df2a96650cca128222b09">Entry::isStatic</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a1500769a8e0054bb142980765556c923">SymbolModifiers::nonoverridable</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#adcd51442f97dbef24a66a86ecd231fda">SymbolModifiers::nopass</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a6c76745fa39de2b90353729fe62c6708a3af5ff26f32ecc18b95bd75082789867">SymbolModifiers::PRIVATE</a>, <a href="/web-doxygen/docs/api/classes/entry/#acbb1b4e99978a710863cf9cab6c90553">Entry::protection</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#add511aaa15123dd20538a4e23415b91e">SymbolModifiers::protection</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a6c76745fa39de2b90353729fe62c6708ae0d7c512c0fe421f9d64e801771f9fb3">SymbolModifiers::PUBLIC</a>, <a href="/web-doxygen/docs/api/classes/entry/#aefd1b83f8d9a4b98c424a92c4bbe2d17">Entry::spec</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/entry/#a79a9b5736630c3769e645f71dc357b9f">Entry::type</a> and <a href="/web-doxygen/docs/api/classes/entry/#aaf045b9c026443fd192064117083911b">Entry::virt</a>.</p>

</div>
</div>

### computeIndent() {#a2b4acd8f05e7bebf0528ec710692f758}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int computeIndent (const char * s)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1709 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2b4acd8f05e7bebf0528ec710692f758">1709</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a2b4acd8f05e7bebf0528ec710692f758">computeIndent</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1710</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1711</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> col=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1712</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> tabSize=<a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(TAB_SIZE);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1713</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1714</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1715</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1716</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1717</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">) col+=tabSize-(col%tabSize);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1718</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) col=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1719</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> col++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1720</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1721</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> col;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1722</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>.</p>

</div>
</div>

### copyEntry() {#a6bd7068dc789461b065785069d7251aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void copyEntry (std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt; dest, const std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt; &amp; src)</td>
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

<p>used to copy entry to an interface module procedure</p>

<p>Definition at line 2148 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6bd7068dc789461b065785069d7251aa">2148</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6bd7068dc789461b065785069d7251aa">copyEntry</a>(std::shared_ptr&lt;Entry&gt; dest, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::shared_ptr&lt;Entry&gt; &amp;src)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2149</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2150</span><span class="doxyLineContent"><span class="doxyHighlight">   dest-&gt;type        = src-&gt;type;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2151</span><span class="doxyLineContent"><span class="doxyHighlight">   dest-&gt;fileName    = src-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2152</span><span class="doxyLineContent"><span class="doxyHighlight">   dest-&gt;startLine   = src-&gt;startLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2153</span><span class="doxyLineContent"><span class="doxyHighlight">   dest-&gt;bodyLine    = src-&gt;bodyLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2154</span><span class="doxyLineContent"><span class="doxyHighlight">   dest-&gt;endBodyLine = src-&gt;endBodyLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2155</span><span class="doxyLineContent"><span class="doxyHighlight">   dest-&gt;args        = src-&gt;args;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2156</span><span class="doxyLineContent"><span class="doxyHighlight">   dest-&gt;argList     = src-&gt;argList;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2157</span><span class="doxyLineContent"><span class="doxyHighlight">   dest-&gt;doc         = src-&gt;doc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2158</span><span class="doxyLineContent"><span class="doxyHighlight">   dest-&gt;docLine  = src-&gt;docLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2159</span><span class="doxyLineContent"><span class="doxyHighlight">   dest-&gt;docFile  = src-&gt;docFile;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2160</span><span class="doxyLineContent"><span class="doxyHighlight">   dest-&gt;brief       = src-&gt;brief;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2161</span><span class="doxyLineContent"><span class="doxyHighlight">   dest-&gt;briefLine= src-&gt;briefLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2162</span><span class="doxyLineContent"><span class="doxyHighlight">   dest-&gt;briefFile= src-&gt;briefFile;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2163</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="#a117a119a3d5a5d0dc330e3d6eade5c04">resolveModuleProcedures</a>.</p>

</div>
</div>

### endScope() {#a5c191151631efdf0d25fc7967f6b0434}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool endScope (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, <a href="/web-doxygen/docs/api/classes/entry">Entry</a> * scope, bool isGlobalRoot=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
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




<p>Ends scope in fortran program: may update subprogram arguments or module variable attributes.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#a49e7bafaa071ffbe937ec1a85c484828">startScope()</a></p></dd>
</dl>


<p>Definition at line 2571 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5c191151631efdf0d25fc7967f6b0434">2571</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a5c191151631efdf0d25fc7967f6b0434">endScope</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,<a href="/web-doxygen/docs/api/classes/entry">Entry</a> *scope, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isGlobalRoot)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2572</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2573</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2574</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;global_scope == scope)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2575</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2576</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;global_scope = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2577</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2578</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2579</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;global_scope == <a href="#a1dfbc2208b3f32fc3d8dca63bd941c08">INVALID_ENTRY</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2580</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2581</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2582</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2583</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//cout&lt;&lt;"end scope: "&lt;&lt;scope-&gt;name&lt;&lt;endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2584</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;current_root-&gt;parent() || isGlobalRoot)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2585</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2586</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current_root= yyextra-&gt;current_root-&gt;parent(); </span><span class="doxyHighlightComment">/* end substructure */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2587</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2588</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// if (yyextra-&gt;current_root != scope)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2589</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2590</span><span class="doxyLineContent"><span class="doxyHighlight">    fprintf(stderr,</span><span class="doxyHighlightStringLiteral">"parse error in end &lt;scopename&gt;\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2591</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a7b2ca28396c488d5a08ead21731ed2c2">scanner_abort</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2592</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2593</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2594</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2595</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// create new current with possibly different defaults...</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2596</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current = std::make_shared&lt;Entry&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2597</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#affe329b2bcd94b04290e03afad9c97c5">initEntry</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2598</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2599</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// update variables or subprogram arguments with yyextra-&gt;modifiers</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2600</span><span class="doxyLineContent"><span class="doxyHighlight">  std::map&lt;std::string,SymbolModifiers&gt;&amp; mdfsMap = yyextra-&gt;modifiers[scope];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2601</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2602</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (scope-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a967db0d8493a46efab87a53d423161eb">section</a>.isFunction())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2603</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2604</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// iterate all symbol yyextra-&gt;modifiers of the scope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2605</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;kv : mdfsMap)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2606</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2607</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//cout&lt;&lt;it.key()&lt;&lt;": "&lt;&lt;qPrint(it)&lt;&lt;endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2608</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/structs/argument">Argument</a> *arg = <a href="#a68f2fb9c7c23aa0812e4e66ee782baee">findArgument</a>(scope, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(kv.first));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2609</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2610</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (arg)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2611</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2612</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a521d11026f20bc253b154ffec71d4748">applyModifiers</a>(arg, kv.second);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2613</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2614</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2615</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2616</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// find return type for function</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2617</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//cout&lt;&lt;"RETURN NAME "&lt;&lt;yyextra-&gt;modifiers[yyextra-&gt;current_root][scope-&gt;name.lower()].returnName&lt;&lt;endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2618</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> returnName = yyextra-&gt;modifiers[yyextra-&gt;current_root][scope-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a87d6afbe10ea84859ef03b6f046e34d3">name</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()].returnName.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2619</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;modifiers[scope].find(returnName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>())!=yyextra-&gt;modifiers[scope].end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2620</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2621</span><span class="doxyLineContent"><span class="doxyHighlight">      scope-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a79a9b5736630c3769e645f71dc357b9f">type</a> = yyextra-&gt;modifiers[scope][returnName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()].type; </span><span class="doxyHighlightComment">// returning type works</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2622</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a521d11026f20bc253b154ffec71d4748">applyModifiers</a>(scope, yyextra-&gt;modifiers[scope][returnName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()]); </span><span class="doxyHighlightComment">// returning array works</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2623</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2624</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2625</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2626</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (scope-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a967db0d8493a46efab87a53d423161eb">section</a>.isClass() &amp;&amp; scope-&gt;<a href="/web-doxygen/docs/api/classes/entry/#aefd1b83f8d9a4b98c424a92c4bbe2d17">spec</a>.isInterface())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2627</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightComment">// was INTERFACE_SEC</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2628</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (scope-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a4fddb6829c93f01fc0553623306ebba3">parent</a>() &amp;&amp; scope-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a4fddb6829c93f01fc0553623306ebba3">parent</a>()-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a967db0d8493a46efab87a53d423161eb">section</a>.isFunction())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2629</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightComment">// interface within function</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2630</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// iterate functions of interface and</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2631</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// try to find types for dummy(ie. argument) procedures.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2632</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//cout&lt;&lt;"Search in "&lt;&lt;scope-&gt;name&lt;&lt;endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2633</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ce : scope-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a13c49362ea71812935f0399e0f7dcf77">children</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2634</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2635</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ce-&gt;section.isFunction())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2636</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2637</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2638</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// remove prefix</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2639</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name = ce-&gt;name.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2640</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> ii = name.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2641</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ii != -1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2642</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2643</span><span class="doxyLineContent"><span class="doxyHighlight">          name.<a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">remove</a>(0, ii+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2644</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2645</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/structs/argument">Argument</a> *arg = <a href="#a68f2fb9c7c23aa0812e4e66ee782baee">findArgument</a>(scope-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a4fddb6829c93f01fc0553623306ebba3">parent</a>(), name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2646</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (arg)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2647</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2648</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// set type of dummy procedure argument to interface</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2649</span><span class="doxyLineContent"><span class="doxyHighlight">          arg-&gt;<a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">type</a> = </span><span class="doxyHighlightStringLiteral">"external "</span><span class="doxyHighlight"> + ce-&gt;type + </span><span class="doxyHighlightStringLiteral">"("</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2650</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0; i&lt;ce-&gt;argList.size(); i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2651</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2652</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i &gt; 0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2653</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2654</span><span class="doxyLineContent"><span class="doxyHighlight">              arg-&gt;<a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">type</a> = arg-&gt;<a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">type</a> + </span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2655</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2656</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;subarg = ce-&gt;argList.at(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2657</span><span class="doxyLineContent"><span class="doxyHighlight">            arg-&gt;<a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">type</a> = arg-&gt;<a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">type</a> + subarg.<a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">type</a> + </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> + subarg.<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2658</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2659</span><span class="doxyLineContent"><span class="doxyHighlight">          arg-&gt;<a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">type</a> = arg-&gt;<a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">type</a> + </span><span class="doxyHighlightStringLiteral">")"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2660</span><span class="doxyLineContent"><span class="doxyHighlight">          arg-&gt;<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a> = name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2661</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2662</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2663</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// clear all yyextra-&gt;modifiers of the scope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2664</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;modifiers.erase(scope);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2665</span><span class="doxyLineContent"><span class="doxyHighlight">      scope-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a4fddb6829c93f01fc0553623306ebba3">parent</a>()-&gt;<a href="/web-doxygen/docs/api/classes/entry/#afce092d3df4c6d51599a826e662de490">removeSubEntry</a>(scope);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2666</span><span class="doxyLineContent"><span class="doxyHighlight">      scope = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2667</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2668</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2669</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2670</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!scope-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a967db0d8493a46efab87a53d423161eb">section</a>.isFunction())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2671</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightComment">// not function section</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2672</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// iterate variables: get and apply yyextra-&gt;modifiers</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2673</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ce : scope-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a13c49362ea71812935f0399e0f7dcf77">children</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2674</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2675</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ce-&gt;section.isVariable() &amp;&amp; !ce-&gt;section.isFunction() &amp;&amp; !ce-&gt;section.isClass())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2676</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2677</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2678</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//cout&lt;&lt;ce-&gt;name&lt;&lt;", "&lt;&lt;mdfsMap.contains(ce-&gt;name.lower())&lt;&lt;mdfsMap.count()&lt;&lt;endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2679</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdfsMap.find(ce-&gt;name.lower().str())!=mdfsMap.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2680</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a521d11026f20bc253b154ffec71d4748">applyModifiers</a>(ce.get(), mdfsMap[ce-&gt;name.lower().str()]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2681</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2682</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// remove prefix for variable names</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2683</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ce-&gt;section.isVariable() || ce-&gt;section.isFunction())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2684</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2685</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a> = ce-&gt;name.findRev(</span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2686</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a> != -1) </span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2687</span><span class="doxyLineContent"><span class="doxyHighlight">          ce-&gt;name.remove(0, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2688</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2689</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2690</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2691</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2692</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// clear all yyextra-&gt;modifiers of the scope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2693</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;modifiers.erase(scope);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2694</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2695</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// resolve procedures in types</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2696</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8e6aba48ce1a2e82d0401f666a45c1d3">resolveTypeBoundProcedures</a>(scope);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2697</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2698</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2699</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a521d11026f20bc253b154ffec71d4748">applyModifiers</a>, <a href="/web-doxygen/docs/api/classes/entry/#a13c49362ea71812935f0399e0f7dcf77">Entry::children</a>, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a68f2fb9c7c23aa0812e4e66ee782baee">findArgument</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a>, <a href="#affe329b2bcd94b04290e03afad9c97c5">initEntry</a>, <a href="#a1dfbc2208b3f32fc3d8dca63bd941c08">INVALID_ENTRY</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>, <a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">Argument::name</a>, <a href="/web-doxygen/docs/api/classes/entry/#a87d6afbe10ea84859ef03b6f046e34d3">Entry::name</a>, <a href="/web-doxygen/docs/api/classes/entry/#a4fddb6829c93f01fc0553623306ebba3">Entry::parent</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">QCString::remove</a>, <a href="/web-doxygen/docs/api/classes/entry/#afce092d3df4c6d51599a826e662de490">Entry::removeSubEntry</a>, <a href="#a8e6aba48ce1a2e82d0401f666a45c1d3">resolveTypeBoundProcedures</a>, <a href="#a7b2ca28396c488d5a08ead21731ed2c2">scanner_abort</a>, <a href="/web-doxygen/docs/api/classes/entry/#a967db0d8493a46efab87a53d423161eb">Entry::section</a>, <a href="/web-doxygen/docs/api/classes/entry/#aefd1b83f8d9a4b98c424a92c4bbe2d17">Entry::spec</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">Argument::type</a> and <a href="/web-doxygen/docs/api/classes/entry/#a79a9b5736630c3769e645f71dc357b9f">Entry::type</a>.</p>


<p>Referenced by <a href="#a4481d3eae9a04af883d868f23c4cbffc">parseMain</a>.</p>

</div>
</div>

### extractBind() {#ac494d47958d1f5413e97e355624ca8db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString extractBind (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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




<p>remove useless spaces from bind statement</p>


<p>Definition at line 2229 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac494d47958d1f5413e97e355624ca8db">2229</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ac494d47958d1f5413e97e355624ca8db">extractBind</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2230</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2231</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> parensPart = <a href="#a25c73dbd285ac4ed23985634ad1a9cab">extractFromParens</a>(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2232</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (parensPart.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() == 1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2233</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2234</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"bind(C)"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2235</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2236</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2237</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2238</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//strip 'c'</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2239</span><span class="doxyLineContent"><span class="doxyHighlight">    parensPart = parensPart.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(1).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2240</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// strip ','</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2241</span><span class="doxyLineContent"><span class="doxyHighlight">    parensPart = parensPart.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(1).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2242</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// name part</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2243</span><span class="doxyLineContent"><span class="doxyHighlight">    parensPart = parensPart.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(4).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2244</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// = part</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2245</span><span class="doxyLineContent"><span class="doxyHighlight">    parensPart = parensPart.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(1).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2246</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2247</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"bind(C, name="</span><span class="doxyHighlight"> + parensPart + </span><span class="doxyHighlightStringLiteral">")"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2248</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2249</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a25c73dbd285ac4ed23985634ad1a9cab">extractFromParens</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aaca9d411d0392efd25510ca3209178d0">SymbolModifiers::operator|=</a>.</p>

</div>
</div>

### extractFromParens() {#a25c73dbd285ac4ed23985634ad1a9cab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString extractFromParens (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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




<p>Extracts string which resides within parentheses of provided string.</p>


<p>Definition at line 2209 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a25c73dbd285ac4ed23985634ad1a9cab">2209</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a25c73dbd285ac4ed23985634ad1a9cab">extractFromParens</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2210</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2211</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> extracted = name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2212</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> start = extracted.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"("</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2213</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (start != -1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2214</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2215</span><span class="doxyLineContent"><span class="doxyHighlight">    extracted.<a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">remove</a>(0, start+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2216</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2217</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a> = extracted.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightStringLiteral">")"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2218</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a> != -1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2219</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2220</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> length = extracted.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2221</span><span class="doxyLineContent"><span class="doxyHighlight">    extracted.<a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">remove</a>(<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, length);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2222</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2223</span><span class="doxyLineContent"><span class="doxyHighlight">  extracted = extracted.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2224</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2225</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> extracted;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2226</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">QCString::remove</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>.</p>


<p>Referenced by <a href="#ac494d47958d1f5413e97e355624ca8db">extractBind</a> and <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aaca9d411d0392efd25510ca3209178d0">SymbolModifiers::operator|=</a>.</p>

</div>
</div>

### findArgument() {#a68f2fb9c7c23aa0812e4e66ee782baee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Argument * findArgument (<a href="/web-doxygen/docs/api/classes/entry">Entry</a> * subprog, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name, bool byTypeName=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
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




<p>For debugging purposes.</p>


<p>Find argument with given name in <em>subprog</em> entry.</p>


<p>Definition at line 2394 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a68f2fb9c7c23aa0812e4e66ee782baee">2394</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/argument">Argument</a> *<a href="#a68f2fb9c7c23aa0812e4e66ee782baee">findArgument</a>(<a href="/web-doxygen/docs/api/classes/entry">Entry</a>* subprog, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> byTypeName = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2395</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2396</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> cname(name.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2397</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;arg : subprog-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a8326dbe669b74cf546adfa28c8ed8bf4">argList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2398</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2399</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((!byTypeName &amp;&amp; arg.<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>() == cname) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2400</span><span class="doxyLineContent"><span class="doxyHighlight">         (byTypeName &amp;&amp; arg.<a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">type</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>() == cname)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2401</span><span class="doxyLineContent"><span class="doxyHighlight">       )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2402</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2403</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> &amp;arg;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2404</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2405</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2406</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2407</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/entry/#a8326dbe669b74cf546adfa28c8ed8bf4">Entry::argList</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>, <a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">Argument::name</a> and <a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">Argument::type</a>.</p>


<p>Referenced by <a href="#a5c191151631efdf0d25fc7967f6b0434">endScope</a>.</p>

</div>
</div>

### getAmpersandAtTheStart() {#a094e0d8bb2b1b92d7a51f8370c76a018}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int getAmpersandAtTheStart (const char * buf, int length)</td>
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



<p>Definition at line 1756 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a094e0d8bb2b1b92d7a51f8370c76a018">1756</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a094e0d8bb2b1b92d7a51f8370c76a018">getAmpersandAtTheStart</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *buf, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> length)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1757</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1758</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0; i&lt;length; i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1759</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1760</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(buf[i])</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1761</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1762</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1763</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1764</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1765</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&amp;'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1766</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1767</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1768</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1769</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1770</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1771</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1772</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### getAmpOrExclAtTheEnd() {#a57a320e051e7596c3106c1a95ae02915}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int getAmpOrExclAtTheEnd (const char * buf, int length, char ch)</td>
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



<p>Definition at line 1775 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a57a320e051e7596c3106c1a95ae02915">1775</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a57a320e051e7596c3106c1a95ae02915">getAmpOrExclAtTheEnd</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *buf, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> length, </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> ch)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1776</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1777</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Avoid ampersands in string and yyextra-&gt;comments</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1778</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> parseState = Start;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1779</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> quoteSymbol = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1780</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> ampIndex = -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1781</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> commentIndex = -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1782</span><span class="doxyLineContent"><span class="doxyHighlight">  quoteSymbol = ch;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1783</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ch != </span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">) parseState = String;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1784</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1785</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0; i&lt;length &amp;&amp; parseState!=Comment; i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1786</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1787</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// When in string, skip backslashes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1788</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// Legacy code, not sure whether this is correct?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1789</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (parseState==String)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1790</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1791</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (buf[i]==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1792</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1793</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1794</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(buf[i])</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1795</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1796</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1797</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1798</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// Close string, if quote symbol matches.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1799</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// Quote symbol is set iff parseState==String</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1800</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (buf[i]==quoteSymbol)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1801</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1802</span><span class="doxyLineContent"><span class="doxyHighlight">             parseState = Start;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1803</span><span class="doxyLineContent"><span class="doxyHighlight">             quoteSymbol = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1804</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1805</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// Start new string, if not already in string or comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1806</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (parseState==Start)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1807</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1808</span><span class="doxyLineContent"><span class="doxyHighlight">            parseState = String;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1809</span><span class="doxyLineContent"><span class="doxyHighlight">            quoteSymbol = buf[i];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1810</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1811</span><span class="doxyLineContent"><span class="doxyHighlight">          ampIndex = -1; </span><span class="doxyHighlightComment">// invalidate prev ampersand</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1812</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1813</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1814</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// When in string or comment, ignore exclamation mark</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1815</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (parseState==Start)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1816</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1817</span><span class="doxyLineContent"><span class="doxyHighlight">            parseState = Comment;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1818</span><span class="doxyLineContent"><span class="doxyHighlight">            commentIndex = i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1819</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1820</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1821</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">:  </span><span class="doxyHighlightComment">// ignore whitespace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1822</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1823</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">: </span><span class="doxyHighlightComment">// this may be at the end of line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1824</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1825</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&amp;'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1826</span><span class="doxyLineContent"><span class="doxyHighlight">          ampIndex = i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1827</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1828</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1829</span><span class="doxyLineContent"><span class="doxyHighlight">          ampIndex = -1; </span><span class="doxyHighlightComment">// invalidate prev ampersand</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1830</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1831</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1832</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1833</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ampIndex&gt;=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1834</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> ampIndex;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1835</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1836</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> commentIndex;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1837</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/fortranscanner-h/#a3318a36567de3b1f36059e387a801863">prepassFixedForm</a>.</p>

</div>
</div>

### getLexerFILE() {#acb5f8818546103e3b804ab8606b52c4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getLexerFILE ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 261 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acb5f8818546103e3b804ab8606b52c4a">261</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#acb5f8818546103e3b804ab8606b52c4a">getLexerFILE</a>() {</span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> __FILE__;}</span></span></div>

</div>

</div>
</div>

### getParameter() {#a6c050f3e9b9e8855bad36862ab3173ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Argument * getParameter (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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




<p>Get the argument <em>name</em>.</p>


<p>Definition at line 3016 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6c050f3e9b9e8855bad36862ab3173ba">3016</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/argument">Argument</a> *<a href="#a6c050f3e9b9e8855bad36862ab3173ba">getParameter</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3017</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3018</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3019</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// std::cout&lt;&lt;"addFortranParameter(): "&lt;&lt;name&lt;&lt;" DOCS:"&lt;&lt;(docs.isEmpty()?QCString("null"):docs)&lt;&lt;"\n";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3020</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/argument">Argument</a> *ret = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3021</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;a:yyextra-&gt;current_root-&gt;argList)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3022</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3023</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (a.<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>()==name.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3024</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3025</span><span class="doxyLineContent"><span class="doxyHighlight">      ret=&amp;a;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3026</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("parameter found: %s\n",(const char*)name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3027</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3028</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3029</span><span class="doxyLineContent"><span class="doxyHighlight">  } </span><span class="doxyHighlightComment">// for</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3030</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> ret;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3031</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a> and <a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">Argument::name</a>.</p>


<p>Referenced by <a href="#a9e2f432a75f34796b2cdda24ee7cb9b0">updateVariablePrepassComment</a>.</p>

</div>
</div>

### handleCommentBlock() {#aa6551ba715391111267db3d5e8a3ead4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void handleCommentBlock (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; doc, bool brief)</td>
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



<p>Definition at line 3051 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa6551ba715391111267db3d5e8a3ead4">3051</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;doc,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> brief)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3052</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3053</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3054</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hideInBodyDocs = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(HIDE_IN_BODY_DOCS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3055</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;docBlockInBody &amp;&amp; hideInBodyDocs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3056</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3057</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;docBlockInBody = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3058</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3059</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3060</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr,</span><span class="doxyHighlightStringLiteral">"call parseCommentBlock [%s]\n"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(doc)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3061</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr = brief ? yyextra-&gt;current-&gt;briefLine : yyextra-&gt;current-&gt;docLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3062</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> position=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3063</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> needsEntry = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3064</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/markdown">Markdown</a> markdown(yyextra-&gt;fileName,lineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3065</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/commentscan-h/#abae3f4527720c3a0368e313ea4a5e575">GuardedSectionStack</a> guards;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3066</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> strippedDoc = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2c01679fba857523a2ffe9007352e3bf">stripIndentation</a>(doc);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3067</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> processedDoc = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(MARKDOWN_SUPPORT) ? markdown.<a href="/web-doxygen/docs/api/classes/markdown/#ad40652cc4db61282f2b0ef5202927d10">process</a>(strippedDoc,lineNr) : strippedDoc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3068</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (yyextra-&gt;commentScanner.parseCommentBlock(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3069</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;thisParser,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3070</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;docBlockInBody ? yyextra-&gt;subrCurrent.back().get() : yyextra-&gt;current.get(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3071</span><span class="doxyLineContent"><span class="doxyHighlight">        processedDoc, </span><span class="doxyHighlightComment">// text</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3072</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;fileName, </span><span class="doxyHighlightComment">// file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3073</span><span class="doxyLineContent"><span class="doxyHighlight">        lineNr,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3074</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;docBlockInBody ? <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> : brief,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3075</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;docBlockInBody ? <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> : yyextra-&gt;docBlockJavaStyle,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3076</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;docBlockInBody,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3077</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;defaultProtection,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3078</span><span class="doxyLineContent"><span class="doxyHighlight">        position,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3079</span><span class="doxyLineContent"><span class="doxyHighlight">        needsEntry,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3080</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(MARKDOWN_SUPPORT),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3081</span><span class="doxyLineContent"><span class="doxyHighlight">        &amp;guards</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3082</span><span class="doxyLineContent"><span class="doxyHighlight">        ))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3083</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3084</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr,</span><span class="doxyHighlightStringLiteral">"parseCommentBlock position=%d [%s]  needsEntry=%d\n"</span><span class="doxyHighlight">,position,doc.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()+position,needsEntry));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3085</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (needsEntry) <a href="#a1f86638786429418e4c584f9b98ec3d4">addCurrentEntry</a>(yyscanner,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3086</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3087</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr,</span><span class="doxyHighlightStringLiteral">"parseCommentBlock position=%d [%s]  needsEntry=%d\n"</span><span class="doxyHighlight">,position,doc.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()+position,needsEntry));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3088</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3089</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (needsEntry) <a href="#a1f86638786429418e4c584f9b98ec3d4">addCurrentEntry</a>(yyscanner,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3090</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;docBlockInBody = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3091</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a1f86638786429418e4c584f9b98ec3d4">addCurrentEntry</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/markdown/#ad40652cc4db61282f2b0ef5202927d10">Markdown::process</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2c01679fba857523a2ffe9007352e3bf">stripIndentation</a>.</p>


<p>Referenced by <a href="#a6c5f6e8cda9aa291a041f511f3a2329a">subrHandleCommentBlock</a> and <a href="#a746c69943bdf7ff71cbd6e6aa44b875d">subrHandleCommentBlockResult</a>.</p>

</div>
</div>

### initEntry() {#affe329b2bcd94b04290e03afad9c97c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void initEntry (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 2869 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#affe329b2bcd94b04290e03afad9c97c5">2869</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#affe329b2bcd94b04290e03afad9c97c5">initEntry</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2870</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2871</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2872</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;typeMode)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2873</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2874</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;protection = yyextra-&gt;typeProtection;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2875</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2876</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;current_root &amp;&amp; yyextra-&gt;current_root-&gt;section.isClass() &amp;&amp; yyextra-&gt;current_root-&gt;spec.isInterface())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2877</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2878</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;protection = Protection::Public;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2879</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2880</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;current_root &amp;&amp; yyextra-&gt;current_root-&gt;section.isFunction())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2881</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2882</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;protection = Protection::Private;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2883</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2884</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2885</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2886</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;protection = yyextra-&gt;defaultProtection;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2887</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2888</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;mtype      = MethodTypes::Method;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2889</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;virt       = Specifier::Normal;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2890</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;isStatic   = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2891</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;lang       = SrcLangExt::Fortran;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2892</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;commentScanner.initGroupInfo(yyextra-&gt;current.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2893</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="#a1f86638786429418e4c584f9b98ec3d4">addCurrentEntry</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#ac41321000a4a4f6ab696d4a6a88a4fef">addEntry</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a3b2171b8a9cdc055bd41d0181094f27a">addFrom</a>, <a href="#a5c191151631efdf0d25fc7967f6b0434">endScope</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a04219d02c56369b619778a94f19fd58f">newEntry</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a04219d02c56369b619778a94f19fd58f">newEntry</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a3383c871b9fd5e4b1cf4a549de88a1f3">parseCompounds</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#af3d71282d72dd7136124a4c7405f6b28">parseCompounds</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a8a8ff9e246514b6146a187f9648c2736">parseMain</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a434a1f775b7fe0a37ad69ba2499cfdfb">parseMain</a> and <a href="#a49e7bafaa071ffbe937ec1a85c484828">startScope</a>.</p>

</div>
</div>

### initParser() {#a451cff71879d11897907cc8c2102bdcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void initParser (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 2863 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a451cff71879d11897907cc8c2102bdcb">2863</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a451cff71879d11897907cc8c2102bdcb">initParser</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2864</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2865</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2866</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;last_entry.reset();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2867</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="#a4481d3eae9a04af883d868f23c4cbffc">parseMain</a>.</p>

</div>
</div>

### insertCharacter() {#a7ac86b7091ebd73f18ce4d662cd75908}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void insertCharacter (char * contents, int length, int pos, char c)</td>
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



<p>Definition at line 1855 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7ac86b7091ebd73f18ce4d662cd75908">1855</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7ac86b7091ebd73f18ce4d662cd75908">insertCharacter</a>(</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *contents, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> length, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> pos, </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1856</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1857</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// shift tail by one character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1858</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=length; i&gt;pos; i--)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1859</span><span class="doxyLineContent"><span class="doxyHighlight">    contents[i]=contents[i-1];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1860</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// set the character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1861</span><span class="doxyLineContent"><span class="doxyHighlight">  contents[pos] = c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1862</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/fortranscanner-h/#a3318a36567de3b1f36059e387a801863">prepassFixedForm</a>.</p>

</div>
</div>

### locatePrepassComment() {#a58823d73b17b4a3c6b782a7e14904c77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CommentInPrepass * locatePrepassComment (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, int from, int to)</td>
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



<p>Definition at line 1724 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a58823d73b17b4a3c6b782a7e14904c77">1724</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/commentinprepass">CommentInPrepass</a> *<a href="#a58823d73b17b4a3c6b782a7e14904c77">locatePrepassComment</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> from, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> to)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1725</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1726</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1727</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("Locate %d-%d\n", from, to);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1728</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cip : yyextra-&gt;comments)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1729</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightComment">// todo: optimize</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1730</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> c = cip.<a href="/web-doxygen/docs/api/structs/commentinprepass/#a84b0d18b00f30aa819ec490f79e24018">column</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1731</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("Candidate %d\n", c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1732</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c&gt;=from &amp;&amp; c&lt;=to)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1733</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1734</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// comment for previous variable or parameter</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1735</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> &amp;cip;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1736</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1737</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1738</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1739</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/structs/commentinprepass/#a84b0d18b00f30aa819ec490f79e24018">CommentInPrepass::column</a>.</p>


<p>Referenced by <a href="#a9e2f432a75f34796b2cdda24ee7cb9b0">updateVariablePrepassComment</a>.</p>

</div>
</div>

### newLine() {#a146a464d8664e6fe5cd764e866726ac1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void newLine (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 1700 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a146a464d8664e6fe5cd764e866726ac1">1700</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a146a464d8664e6fe5cd764e866726ac1">newLine</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1701</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1702</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1703</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;lineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1704</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;lineNr+=yyextra-&gt;lineCountPrepass;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1705</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;lineCountPrepass=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1706</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;comments.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1707</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdl/parser/charstream/#af8340206fb0e8eadbd9914fd833be6e0">vhdl::parser::CharStream::adjustBeginLineColumn</a>.</p>

</div>
</div>

### parseMain() {#a4481d3eae9a04af883d868f23c4cbffc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void parseMain (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const char * fileBuf, const std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt; &amp; rt, <a href="/web-doxygen/docs/api/files/src/types-h/#ad3f2a8c13ceee9c0aaeabf930dd88266">FortranFormat</a> format)</td>
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



<p>Definition at line 3230 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4481d3eae9a04af883d868f23c4cbffc">3230</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4481d3eae9a04af883d868f23c4cbffc">parseMain</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *fileBuf,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3231</span><span class="doxyLineContent"><span class="doxyHighlight">                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::shared_ptr&lt;Entry&gt; &amp;rt, <a href="/web-doxygen/docs/api/files/src/types-h/#ad3f2a8c13ceee9c0aaeabf930dd88266">FortranFormat</a> format)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3232</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3233</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3234</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *tmpBuf = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3235</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a451cff71879d11897907cc8c2102bdcb">initParser</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3236</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3237</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fileBuf==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> || fileBuf[0]==</span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3238</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3239</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;defaultProtection = Protection::Public;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3240</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputString = fileBuf;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3241</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputPosition = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3242</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputStringPrepass = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3243</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputPositionPrepass = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3244</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3245</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//yyextra-&gt;anonCount     = 0;  // don't reset per file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3246</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current_root  = rt.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3247</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;global_root   = rt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3248</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3249</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;isFixedForm = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5c3775d3cb6b3776c441a4451d49bb2c">recognizeFixedForm</a>(fileBuf,format);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3250</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3251</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;isFixedForm)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3252</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3253</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;fixedCommentAfter = <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(FORTRAN_COMMENT_AFTER);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3254</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Prepassing fixed form of {}\n"</span><span class="doxyHighlight">, fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3255</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("---strlen=%d\n", strlen(fileBuf));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3256</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//clock_t start=clock();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3257</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3258</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("Input fixed form string:\n%s\n", fileBuf);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3259</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("===========================\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3260</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;inputString = <a href="#a3318a36567de3b1f36059e387a801863">prepassFixedForm</a>(fileBuf, </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,yyextra-&gt;fixedCommentAfter);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3261</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dafae1c4a49dc51808b18e3091bbc85e28">Debug::FortranFixed2Free</a>,0,</span><span class="doxyHighlightStringLiteral">"======== Fixed to Free format  =========\n---- Input fixed form string ------- \n{}\n"</span><span class="doxyHighlight">, fileBuf);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3262</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dafae1c4a49dc51808b18e3091bbc85e28">Debug::FortranFixed2Free</a>,0,</span><span class="doxyHighlightStringLiteral">"---- Resulting free form string ------- \n{}\n"</span><span class="doxyHighlight">, yyextra-&gt;inputString);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3263</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("Resulting free form string:\n%s\n", yyextra-&gt;inputString);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3264</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("===========================\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3265</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3266</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//clock_t end=clock();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3267</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("CPU time used=%f\n", ((double) (end-start))/CLOCKS_PER_SEC);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3268</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3269</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;inputString[strlen(fileBuf)-1] != </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3270</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3271</span><span class="doxyLineContent"><span class="doxyHighlight">    tmpBuf = (</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *)malloc(strlen(fileBuf)+2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3272</span><span class="doxyLineContent"><span class="doxyHighlight">    strcpy(tmpBuf,fileBuf);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3273</span><span class="doxyLineContent"><span class="doxyHighlight">    tmpBuf[strlen(fileBuf)]= </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3274</span><span class="doxyLineContent"><span class="doxyHighlight">    tmpBuf[strlen(fileBuf)+1]= </span><span class="doxyHighlightCharLiteral">'\000'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3275</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;inputString = tmpBuf;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3276</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3277</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3278</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;lineNr= 1 ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3279</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;fileName = fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3280</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Parsing file {}...\n"</span><span class="doxyHighlight">,yyextra-&gt;fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3281</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3282</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;global_scope = rt.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3283</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a49e7bafaa071ffbe937ec1a85c484828">startScope</a>(yyscanner,rt.get()); </span><span class="doxyHighlightComment">// implies yyextra-&gt;current_root = rt</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3284</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a451cff71879d11897907cc8c2102bdcb">initParser</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3285</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;commentScanner.enterFile(yyextra-&gt;fileName,yyextra-&gt;lineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3286</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3287</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// add entry for the file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3288</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current          = std::make_shared&lt;Entry&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3289</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;lang    = SrcLangExt::Fortran;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3290</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;name    = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3291</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;section = EntryType::makeSource();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3292</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;file_root        = yyextra-&gt;current;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3293</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current_root-&gt;moveToSubEntryAndRefresh(yyextra-&gt;current);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3294</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;lang    = SrcLangExt::Fortran;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3295</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3296</span><span class="doxyLineContent"><span class="doxyHighlight">  fortranscannerYYrestart( </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, yyscanner );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3297</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3298</span><span class="doxyLineContent"><span class="doxyHighlight">    BEGIN( Start );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3299</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3300</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3301</span><span class="doxyLineContent"><span class="doxyHighlight">  fortranscannerYYlex(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3302</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;commentScanner.leaveFile(yyextra-&gt;fileName,yyextra-&gt;lineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3303</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3304</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;global_scope &amp;&amp; yyextra-&gt;global_scope != <a href="#a1dfbc2208b3f32fc3d8dca63bd941c08">INVALID_ENTRY</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3305</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3306</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5c191151631efdf0d25fc7967f6b0434">endScope</a>(yyscanner,yyextra-&gt;current_root, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>); </span><span class="doxyHighlightComment">// TRUE - global root</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3307</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3308</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3309</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//debugCompounds(rt); //debug</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3310</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3311</span><span class="doxyLineContent"><span class="doxyHighlight">  rt-&gt;program.str(std::string());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3312</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//delete yyextra-&gt;current; yyextra-&gt;current=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3313</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;moduleProcedures.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3314</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tmpBuf)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3315</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3316</span><span class="doxyLineContent"><span class="doxyHighlight">    free((</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)tmpBuf);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3317</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;inputString=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3318</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3319</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;isFixedForm)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3320</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3321</span><span class="doxyLineContent"><span class="doxyHighlight">    free((</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)yyextra-&gt;inputString);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3322</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;inputString=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3323</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3324</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3325</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>, <a href="#a5c191151631efdf0d25fc7967f6b0434">endScope</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dafae1c4a49dc51808b18e3091bbc85e28">Debug::FortranFixed2Free</a>, <a href="#a451cff71879d11897907cc8c2102bdcb">initParser</a>, <a href="#a1dfbc2208b3f32fc3d8dca63bd941c08">INVALID_ENTRY</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>, <a href="#a3318a36567de3b1f36059e387a801863">prepassFixedForm</a>, <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5c3775d3cb6b3776c441a4451d49bb2c">recognizeFixedForm</a>, <a href="#a49e7bafaa071ffbe937ec1a85c484828">startScope</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/coutlineparser/#a5bf5190ffb4fc52b45fc6b22895a6fbf">COutlineParser::parseInput</a>, <a href="/web-doxygen/docs/api/classes/fortranoutlineparser/#af3e1c6efa3eba5f4d30934eac0cd0aa3">FortranOutlineParser::parseInput</a>, <a href="/web-doxygen/docs/api/classes/lexoutlineparser/#ac842abb13f0168eeec20c4a6de1d79b8">LexOutlineParser::parseInput</a> and <a href="/web-doxygen/docs/api/classes/pythonoutlineparser/#a5a3b64521d1851e39a58043826b11a95">PythonOutlineParser::parseInput</a>.</p>

</div>
</div>

### pop\_state() {#a84f9bfb00f12e8fc287ed97f3e1d693c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void pop_state (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3415 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a84f9bfb00f12e8fc287ed97f3e1d693c">3415</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3416</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3417</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3418</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( yyg-&gt;yy_start_stack_ptr &lt;= 0 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3419</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(yyextra-&gt;fileName,yyextra-&gt;lineNr,</span><span class="doxyHighlightStringLiteral">"Unexpected statement '{}'"</span><span class="doxyHighlight">,yytext );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3420</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3421</span><span class="doxyLineContent"><span class="doxyHighlight">    yy_pop_state(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3422</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.</p>

</div>
</div>

### popBuffer() {#a66d8cb63c9460264113152b30a8c4afb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void popBuffer (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 2138 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a66d8cb63c9460264113152b30a8c4afb">2138</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a66d8cb63c9460264113152b30a8c4afb">popBuffer</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2139</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2140</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2141</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr, </span><span class="doxyHighlightStringLiteral">"--POP--"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2142</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;includeStackPtr --;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2143</span><span class="doxyLineContent"><span class="doxyHighlight">  yy_delete_buffer( YY_CURRENT_BUFFER, yyscanner );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2144</span><span class="doxyLineContent"><span class="doxyHighlight">  yy_switch_to_buffer( yyextra-&gt;includeStack[yyextra-&gt;includeStackPtr], yyscanner );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2145</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/fortranoutlineparser/#abbe1b29c5797729e3aa2dcd693e46755">FortranOutlineParser::parsePrototype</a>.</p>

</div>
</div>

### prepassFixedForm() {#a3318a36567de3b1f36059e387a801863}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * prepassFixedForm (const char * contents, int * hasContLine, int fixedCommentAfter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1866 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/fortranscanner-h/#a3318a36567de3b1f36059e387a801863">1866</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">* <a href="/web-doxygen/docs/api/files/src/fortranscanner-h/#a3318a36567de3b1f36059e387a801863">prepassFixedForm</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">* contents, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> *hasContLine,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> fixedCommentAfter)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1867</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1868</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> column=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1869</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> prevLineLength=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1870</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> prevLineAmpOrExclIndex=-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1871</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> skipped = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1872</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> prevQuote = </span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1873</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> thisQuote = </span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1874</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> emptyLabel=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1875</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> commented=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1876</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inSingle=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1877</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inDouble=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1878</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inBackslash=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1879</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> fullCommentLine=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1880</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> artificialComment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1881</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> spaces=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1882</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> newContentsSize = (int)strlen(contents)+3; </span><span class="doxyHighlightComment">// \000, \n (when necessary) and one spare character (to avoid reallocation)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1883</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">* newContents = (</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)malloc(newContentsSize);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1884</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> curLine = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1885</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> sizCont;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1886</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1887</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> j = -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1888</span><span class="doxyLineContent"><span class="doxyHighlight">  sizCont = strlen(contents);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1889</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;i&lt;sizCont;i++) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1890</span><span class="doxyLineContent"><span class="doxyHighlight">    column++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1891</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = contents[i];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1892</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (artificialComment &amp;&amp; c != </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1893</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1894</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c == </span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight"> &amp;&amp; spaces)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1895</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1896</span><span class="doxyLineContent"><span class="doxyHighlight">        newContents[j++] = c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1897</span><span class="doxyLineContent"><span class="doxyHighlight">        artificialComment = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1898</span><span class="doxyLineContent"><span class="doxyHighlight">        spaces = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1899</span><span class="doxyLineContent"><span class="doxyHighlight">        skipped = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1900</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1901</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1902</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c == </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || c == </span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1903</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1904</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1905</span><span class="doxyLineContent"><span class="doxyHighlight">        spaces = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1906</span><span class="doxyLineContent"><span class="doxyHighlight">        skipped++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1907</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1908</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1909</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1910</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1911</span><span class="doxyLineContent"><span class="doxyHighlight">    j++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1912</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (j&gt;=newContentsSize-3) { </span><span class="doxyHighlightComment">// check for spare characters, which may be eventually used below (by &amp; and '! ')</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1913</span><span class="doxyLineContent"><span class="doxyHighlight">      newContents = (</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)realloc(newContents, newContentsSize+1000);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1914</span><span class="doxyLineContent"><span class="doxyHighlight">      newContentsSize = newContentsSize+1000;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1915</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1916</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1917</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(c) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1918</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1919</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!fullCommentLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1920</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1921</span><span class="doxyLineContent"><span class="doxyHighlight">          prevLineLength=column;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1922</span><span class="doxyLineContent"><span class="doxyHighlight">          prevLineAmpOrExclIndex=<a href="#a57a320e051e7596c3106c1a95ae02915">getAmpOrExclAtTheEnd</a>(&amp;contents[i-prevLineLength+1], prevLineLength,prevQuote);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1923</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (prevLineAmpOrExclIndex == -1) prevLineAmpOrExclIndex = column - 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1924</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (skipped)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1925</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1926</span><span class="doxyLineContent"><span class="doxyHighlight">            prevLineAmpOrExclIndex = -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1927</span><span class="doxyLineContent"><span class="doxyHighlight">            skipped = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1928</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1929</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1930</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1931</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1932</span><span class="doxyLineContent"><span class="doxyHighlight">          prevLineLength+=column;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1933</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">/* Even though a full comment line is not really a comment line it can be seen as one. An empty line is also seen as a comment line (small bonus) */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1934</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hasContLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1935</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1936</span><span class="doxyLineContent"><span class="doxyHighlight">            hasContLine[curLine - 1] = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1937</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1938</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1939</span><span class="doxyLineContent"><span class="doxyHighlight">        artificialComment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1940</span><span class="doxyLineContent"><span class="doxyHighlight">        spaces=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1941</span><span class="doxyLineContent"><span class="doxyHighlight">        fullCommentLine=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1942</span><span class="doxyLineContent"><span class="doxyHighlight">        column=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1943</span><span class="doxyLineContent"><span class="doxyHighlight">        emptyLabel=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1944</span><span class="doxyLineContent"><span class="doxyHighlight">        commented=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1945</span><span class="doxyLineContent"><span class="doxyHighlight">        newContents[j]=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1946</span><span class="doxyLineContent"><span class="doxyHighlight">        prevQuote = thisQuote;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1947</span><span class="doxyLineContent"><span class="doxyHighlight">        curLine++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1948</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1949</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1950</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1951</span><span class="doxyLineContent"><span class="doxyHighlight">        newContents[j]=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1952</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1953</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\000'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1954</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hasContLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1955</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1956</span><span class="doxyLineContent"><span class="doxyHighlight">           free(newContents);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1957</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1958</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1959</span><span class="doxyLineContent"><span class="doxyHighlight">        newContents[j]=</span><span class="doxyHighlightCharLiteral">'\000'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1960</span><span class="doxyLineContent"><span class="doxyHighlight">        newContentsSize = (int)strlen(newContents);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1961</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (newContents[newContentsSize - 1] != </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1962</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1963</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// to be on the safe side</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1964</span><span class="doxyLineContent"><span class="doxyHighlight">          newContents = (</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)realloc(newContents, newContentsSize+2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1965</span><span class="doxyLineContent"><span class="doxyHighlight">          newContents[newContentsSize] = </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1966</span><span class="doxyLineContent"><span class="doxyHighlight">          newContents[newContentsSize + 1] = </span><span class="doxyHighlightCharLiteral">'\000'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1967</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1968</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> newContents;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1969</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1970</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1971</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1972</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((column &lt;= fixedCommentAfter) &amp;&amp; (column!=6) &amp;&amp; !commented)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1973</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1974</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// we have some special cases in respect to strings and escaped string characters</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1975</span><span class="doxyLineContent"><span class="doxyHighlight">          fullCommentLine=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1976</span><span class="doxyLineContent"><span class="doxyHighlight">          newContents[j]=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1977</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c == </span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1978</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1979</span><span class="doxyLineContent"><span class="doxyHighlight">            inBackslash = !inBackslash;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1980</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1981</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1982</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c == </span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1983</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1984</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!inDouble)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1985</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1986</span><span class="doxyLineContent"><span class="doxyHighlight">              inSingle = !inSingle;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1987</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (inSingle) thisQuote = c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1988</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> thisQuote = </span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1989</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1990</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1991</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1992</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c == </span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1993</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1994</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!inSingle)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1995</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1996</span><span class="doxyLineContent"><span class="doxyHighlight">              inDouble = !inDouble;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1997</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (inDouble) thisQuote = c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1998</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> thisQuote = </span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1999</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2000</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2001</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2002</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2003</span><span class="doxyLineContent"><span class="doxyHighlight">        inBackslash = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2004</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// fallthrough</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2005</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2006</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'C'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2007</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'c'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2008</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2009</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2010</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((column &lt;= fixedCommentAfter) &amp;&amp; (column!=6))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2011</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2012</span><span class="doxyLineContent"><span class="doxyHighlight">          emptyLabel=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2013</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (column==1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2014</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2015</span><span class="doxyLineContent"><span class="doxyHighlight">            newContents[j]=</span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2016</span><span class="doxyLineContent"><span class="doxyHighlight">            commented = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2017</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2018</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((c == </span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight">) &amp;&amp; !inDouble &amp;&amp; !inSingle)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2019</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2020</span><span class="doxyLineContent"><span class="doxyHighlight">            newContents[j]=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2021</span><span class="doxyLineContent"><span class="doxyHighlight">            commented = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2022</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2023</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2024</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2025</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!commented) fullCommentLine=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2026</span><span class="doxyLineContent"><span class="doxyHighlight">            newContents[j]=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2027</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2028</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2029</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2030</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// fallthrough</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2031</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2032</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!commented &amp;&amp; (column &lt; 6) &amp;&amp; ((c - </span><span class="doxyHighlightCharLiteral">'0'</span><span class="doxyHighlight">) &gt;= 0) &amp;&amp; ((c - </span><span class="doxyHighlightCharLiteral">'0'</span><span class="doxyHighlight">) &lt;= 9))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2033</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightComment">// remove numbers, i.e. labels from first 5 positions.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2034</span><span class="doxyLineContent"><span class="doxyHighlight">            newContents[j]=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2035</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2036</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (column==6 &amp;&amp; emptyLabel)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2037</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightComment">// continuation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2038</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!commented) fullCommentLine=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2039</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c != </span><span class="doxyHighlightCharLiteral">'0'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2040</span><span class="doxyLineContent"><span class="doxyHighlight">          { </span><span class="doxyHighlightComment">// 0 not allowed as continuation character, see f95 standard paragraph 3.3.2.3</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2041</span><span class="doxyLineContent"><span class="doxyHighlight">            newContents[j]=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2042</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2043</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (prevLineAmpOrExclIndex==-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2044</span><span class="doxyLineContent"><span class="doxyHighlight">            { </span><span class="doxyHighlightComment">// add &amp; just before end of previous line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2045</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightComment">/* first line is not a continuation line in code, just in snippets etc. */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2046</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (curLine != 1) <a href="#a7ac86b7091ebd73f18ce4d662cd75908">insertCharacter</a>(newContents, j+1, (j+1)-6-1, </span><span class="doxyHighlightCharLiteral">'&amp;'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2047</span><span class="doxyLineContent"><span class="doxyHighlight">              j++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2048</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2049</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2050</span><span class="doxyLineContent"><span class="doxyHighlight">            { </span><span class="doxyHighlightComment">// add &amp; just before end of previous line comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2051</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightComment">/* first line is not a continuation line in code, just in snippets etc. */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2052</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (curLine != 1) <a href="#a7ac86b7091ebd73f18ce4d662cd75908">insertCharacter</a>(newContents, j+1, (j+1)-6-prevLineLength+prevLineAmpOrExclIndex+skipped, </span><span class="doxyHighlightCharLiteral">'&amp;'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2053</span><span class="doxyLineContent"><span class="doxyHighlight">              skipped = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2054</span><span class="doxyLineContent"><span class="doxyHighlight">              j++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2055</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2056</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hasContLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2057</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2058</span><span class="doxyLineContent"><span class="doxyHighlight">              hasContLine[curLine - 1] = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2059</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2060</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2061</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2062</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2063</span><span class="doxyLineContent"><span class="doxyHighlight">            newContents[j]=c; </span><span class="doxyHighlightComment">// , just handle like space</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2064</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2065</span><span class="doxyLineContent"><span class="doxyHighlight">          prevLineLength=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2066</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2067</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((column &gt; fixedCommentAfter) &amp;&amp; !commented)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2068</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2069</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// first non commented non blank character after position fixedCommentAfter</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2070</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c == </span><span class="doxyHighlightCharLiteral">'&amp;'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2071</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2072</span><span class="doxyLineContent"><span class="doxyHighlight">            newContents[j]=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2073</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2074</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c != </span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2075</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2076</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// I'm not a possible start of doxygen comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2077</span><span class="doxyLineContent"><span class="doxyHighlight">            newContents[j]=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2078</span><span class="doxyLineContent"><span class="doxyHighlight">            artificialComment = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2079</span><span class="doxyLineContent"><span class="doxyHighlight">            spaces=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2080</span><span class="doxyLineContent"><span class="doxyHighlight">            skipped = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2081</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2082</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2083</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2084</span><span class="doxyLineContent"><span class="doxyHighlight">            newContents[j]=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2085</span><span class="doxyLineContent"><span class="doxyHighlight">            commented = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2086</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2087</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2088</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2089</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2090</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!commented) fullCommentLine=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2091</span><span class="doxyLineContent"><span class="doxyHighlight">          newContents[j]=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2092</span><span class="doxyLineContent"><span class="doxyHighlight">          emptyLabel=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2093</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2094</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2095</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2096</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2097</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2098</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hasContLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2099</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2100</span><span class="doxyLineContent"><span class="doxyHighlight">    free(newContents);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2101</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2102</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2103</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2104</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (j==-1) </span><span class="doxyHighlightComment">// contents was empty</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2105</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2106</span><span class="doxyLineContent"><span class="doxyHighlight">    newContents = (</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)realloc(newContents, 2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2107</span><span class="doxyLineContent"><span class="doxyHighlight">    newContents[0] = </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2108</span><span class="doxyLineContent"><span class="doxyHighlight">    newContents[1] = </span><span class="doxyHighlightCharLiteral">'\000'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2109</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2110</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (newContents[j] == </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// content ended with newline</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2111</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2112</span><span class="doxyLineContent"><span class="doxyHighlight">    newContents = (</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)realloc(newContents, j+2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2113</span><span class="doxyLineContent"><span class="doxyHighlight">    newContents[j + 1] = </span><span class="doxyHighlightCharLiteral">'\000'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2114</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2115</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// content did not end with a newline</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2116</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2117</span><span class="doxyLineContent"><span class="doxyHighlight">    newContents = (</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)realloc(newContents, j+3);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2118</span><span class="doxyLineContent"><span class="doxyHighlight">    newContents[j + 1] = </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2119</span><span class="doxyLineContent"><span class="doxyHighlight">    newContents[j + 2] = </span><span class="doxyHighlightCharLiteral">'\000'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2120</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2121</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> newContents;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2122</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a57a320e051e7596c3106c1a95ae02915">getAmpOrExclAtTheEnd</a>, <a href="#a7ac86b7091ebd73f18ce4d662cd75908">insertCharacter</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a738fe0f13b025379789e42ee04dcc54f">checkContLines</a> and <a href="#a4481d3eae9a04af883d868f23c4cbffc">parseMain</a>.</p>

</div>
</div>

### pushBuffer() {#ab536b3c2ec35df931a4fce0dbf2e1420}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void pushBuffer (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; buffer)</td>
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



<p>Definition at line 2124 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab536b3c2ec35df931a4fce0dbf2e1420">2124</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab536b3c2ec35df931a4fce0dbf2e1420">pushBuffer</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;buffer)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2125</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2126</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2127</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;includeStackCnt &lt;= yyextra-&gt;includeStackPtr)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2128</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2129</span><span class="doxyLineContent"><span class="doxyHighlight">     yyextra-&gt;includeStackCnt++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2130</span><span class="doxyLineContent"><span class="doxyHighlight">     yyextra-&gt;includeStack = (YY_BUFFER_STATE *)realloc(yyextra-&gt;includeStack, yyextra-&gt;includeStackCnt * </span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(YY_BUFFER_STATE));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2131</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2132</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;includeStack[yyextra-&gt;includeStackPtr++] = YY_CURRENT_BUFFER;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2133</span><span class="doxyLineContent"><span class="doxyHighlight">  yy_switch_to_buffer(yy_scan_string(buffer.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),yyscanner),yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2134</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2135</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr, </span><span class="doxyHighlightStringLiteral">"--PUSH--%s"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(buffer)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2136</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/fortranoutlineparser/#abbe1b29c5797729e3aa2dcd693e46755">FortranOutlineParser::parsePrototype</a>.</p>

</div>
</div>

### resolveModuleProcedures() {#a117a119a3d5a5d0dc330e3d6eade5c04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void resolveModuleProcedures (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, <a href="/web-doxygen/docs/api/classes/entry">Entry</a> * current_root)</td>
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

<p>fill empty interface module procedures with info from corresponding module subprogs</p>


<p>TODO: handle procedures in used modules</p>


<p>Definition at line 2170 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a117a119a3d5a5d0dc330e3d6eade5c04">2170</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a117a119a3d5a5d0dc330e3d6eade5c04">resolveModuleProcedures</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,<a href="/web-doxygen/docs/api/classes/entry">Entry</a> *current_root)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2171</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2172</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2173</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;moduleProcedures.empty()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2174</span><span class="doxyLineContent"><span class="doxyHighlight"> </span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2175</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// build up map of available functions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2176</span><span class="doxyLineContent"><span class="doxyHighlight">  std::map&lt;std::string,std::shared_ptr&lt;Entry&gt;&gt; procMap;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2177</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2178</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight">&amp; cf: current_root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a13c49362ea71812935f0399e0f7dcf77">children</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2179</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2180</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!cf-&gt;section.isFunction())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2181</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2182</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2183</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// remove scope from name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2184</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name = cf-&gt;name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2185</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2186</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a> = name.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2187</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a> != -1) </span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2188</span><span class="doxyLineContent"><span class="doxyHighlight">          name.<a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">remove</a>(0, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2189</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2190</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2191</span><span class="doxyLineContent"><span class="doxyHighlight">      procMap.emplace(name.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(), cf);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2192</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2193</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2194</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2195</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2196</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// for all module procedures</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2197</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight">&amp; ce1: yyextra-&gt;moduleProcedures)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2198</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2199</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (procMap.find(ce1-&gt;name.str())!=procMap.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2200</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2201</span><span class="doxyLineContent"><span class="doxyHighlight">      std::shared_ptr&lt;Entry&gt; proc = procMap[ce1-&gt;name.str()];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2202</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a6bd7068dc789461b065785069d7251aa">copyEntry</a>(ce1, proc);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2203</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2204</span><span class="doxyLineContent"><span class="doxyHighlight">  } </span><span class="doxyHighlightComment">// for all interface module procedures</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2205</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;moduleProcedures.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2206</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/entry/#a13c49362ea71812935f0399e0f7dcf77">Entry::children</a>, <a href="#a6bd7068dc789461b065785069d7251aa">copyEntry</a>, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">QCString::remove</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>

</div>
</div>

### resolveTypeBoundProcedures() {#a8e6aba48ce1a2e82d0401f666a45c1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void resolveTypeBoundProcedures (<a href="/web-doxygen/docs/api/classes/entry">Entry</a> * scope)</td>
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




<p>search for types with type bound procedures (e.g. methods) and try to resolve their arguments</p>


<p>Definition at line 2704 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8e6aba48ce1a2e82d0401f666a45c1d3">2704</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8e6aba48ce1a2e82d0401f666a45c1d3">resolveTypeBoundProcedures</a>(<a href="/web-doxygen/docs/api/classes/entry">Entry</a> *scope)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2705</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2706</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// map of all subroutines/functions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2707</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> procMapCreated = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2708</span><span class="doxyLineContent"><span class="doxyHighlight">  std::unordered_map&lt;std::string,std::shared_ptr&lt;Entry&gt;&gt; procMap;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2709</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2710</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// map of all abstract interfaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2711</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> interfMapCreated = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2712</span><span class="doxyLineContent"><span class="doxyHighlight">  std::unordered_map&lt;std::string,std::shared_ptr&lt;Entry&gt;&gt; interfMap;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2713</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2714</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// iterate over all types</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2715</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ce: scope-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a13c49362ea71812935f0399e0f7dcf77">children</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2716</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2717</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ce-&gt;section.isClass())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2718</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2719</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2720</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// handle non-"generic" non-"deferred" methods, copying the arguments from the implementation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2721</span><span class="doxyLineContent"><span class="doxyHighlight">    std::unordered_map&lt;std::string,std::shared_ptr&lt;Entry&gt;&gt; methodMap;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2722</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ct: ce-&gt;children())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2723</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2724</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ct-&gt;section.isFunction())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2725</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2726</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2727</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ct-&gt;type==</span><span class="doxyHighlightStringLiteral">"generic"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2728</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2729</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2730</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ct-&gt;virt==Specifier::Pure)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2731</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2732</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2733</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// set up the procMap</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2734</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!procMapCreated)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2735</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2736</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cf: scope-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a13c49362ea71812935f0399e0f7dcf77">children</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2737</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2738</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cf-&gt;section.isFunction())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2739</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2740</span><span class="doxyLineContent"><span class="doxyHighlight">            procMap.emplace(cf-&gt;name.str(), cf);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2741</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2742</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2743</span><span class="doxyLineContent"><span class="doxyHighlight">        procMapCreated = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2744</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2745</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2746</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// found a (non-generic) method</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2747</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> implName = ct-&gt;args;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2748</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (procMap.find(implName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>())!=procMap.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2749</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2750</span><span class="doxyLineContent"><span class="doxyHighlight">        std::shared_ptr&lt;Entry&gt; proc = procMap[implName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2751</span><span class="doxyLineContent"><span class="doxyHighlight">        ct-&gt;args = proc-&gt;args;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2752</span><span class="doxyLineContent"><span class="doxyHighlight">        ct-&gt;argList = <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a>(proc-&gt;argList);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2753</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ct-&gt;brief.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2754</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2755</span><span class="doxyLineContent"><span class="doxyHighlight">          ct-&gt;brief = proc-&gt;brief;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2756</span><span class="doxyLineContent"><span class="doxyHighlight">          ct-&gt;briefLine = proc-&gt;briefLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2757</span><span class="doxyLineContent"><span class="doxyHighlight">          ct-&gt;briefFile = proc-&gt;briefFile;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2758</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2759</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ct-&gt;doc.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2760</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2761</span><span class="doxyLineContent"><span class="doxyHighlight">          ct-&gt;doc = proc-&gt;doc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2762</span><span class="doxyLineContent"><span class="doxyHighlight">          ct-&gt;docLine = proc-&gt;docLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2763</span><span class="doxyLineContent"><span class="doxyHighlight">          ct-&gt;docFile = proc-&gt;docFile;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2764</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2765</span><span class="doxyLineContent"><span class="doxyHighlight">        methodMap.emplace(ct-&gt;name.str(), ct);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2766</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2767</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2768</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2769</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// handle "deferred" methods (pure virtual functions), duplicating with arguments from the target abstract interface</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2770</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ct: ce-&gt;children())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2771</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2772</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ct-&gt;section.isFunction())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2773</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2774</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2775</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ct-&gt;virt != Specifier::Pure)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2776</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2777</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2778</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// set up the procMap</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2779</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!interfMapCreated)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2780</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2781</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cf: scope-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a13c49362ea71812935f0399e0f7dcf77">children</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2782</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2783</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cf-&gt;section.isClass() &amp;&amp; cf-&gt;spec.isInterface() &amp;&amp; cf-&gt;type==</span><span class="doxyHighlightStringLiteral">"abstract"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2784</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2785</span><span class="doxyLineContent"><span class="doxyHighlight">            std::shared_ptr&lt;Entry&gt; ci = cf-&gt;children().front();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2786</span><span class="doxyLineContent"><span class="doxyHighlight">            interfMap.emplace(ci-&gt;name.str(), ci);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2787</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2788</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2789</span><span class="doxyLineContent"><span class="doxyHighlight">        interfMapCreated = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2790</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2791</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2792</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// found a (non-generic) method</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2793</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> implName = ct-&gt;args;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2794</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (interfMap.find(implName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>())!= interfMap.end() )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2795</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2796</span><span class="doxyLineContent"><span class="doxyHighlight">        std::shared_ptr&lt;Entry&gt; proc = interfMap[implName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2797</span><span class="doxyLineContent"><span class="doxyHighlight">        ct-&gt;args = proc-&gt;args;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2798</span><span class="doxyLineContent"><span class="doxyHighlight">        ct-&gt;argList = <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a>(proc-&gt;argList);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2799</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ct-&gt;brief.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2800</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2801</span><span class="doxyLineContent"><span class="doxyHighlight">          ct-&gt;brief = proc-&gt;brief;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2802</span><span class="doxyLineContent"><span class="doxyHighlight">          ct-&gt;briefLine = proc-&gt;briefLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2803</span><span class="doxyLineContent"><span class="doxyHighlight">          ct-&gt;briefFile = proc-&gt;briefFile;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2804</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2805</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ct-&gt;doc.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2806</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2807</span><span class="doxyLineContent"><span class="doxyHighlight">          ct-&gt;doc = proc-&gt;doc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2808</span><span class="doxyLineContent"><span class="doxyHighlight">          ct-&gt;docLine = proc-&gt;docLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2809</span><span class="doxyLineContent"><span class="doxyHighlight">          ct-&gt;docFile = proc-&gt;docFile;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2810</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2811</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2812</span><span class="doxyLineContent"><span class="doxyHighlight">        methodMap.emplace(ct-&gt;name.str(), ct);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2813</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2814</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2815</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2816</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// handle "generic" methods (that is function overloading!), duplicating with arguments from the target method of the type</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2817</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2818</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ct: ce-&gt;children())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2819</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2820</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ct-&gt;section.isFunction())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2821</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2822</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2823</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ct-&gt;type!=</span><span class="doxyHighlightStringLiteral">"generic"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2824</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2825</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2826</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// found a generic method (already duplicated for each entry by the parser)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2827</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> methodName = ct-&gt;args;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2828</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (methodMap.find(methodName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()) != methodMap.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2829</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2830</span><span class="doxyLineContent"><span class="doxyHighlight">          std::shared_ptr&lt;Entry&gt; method = methodMap[methodName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2831</span><span class="doxyLineContent"><span class="doxyHighlight">          ct-&gt;args = method-&gt;args;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2832</span><span class="doxyLineContent"><span class="doxyHighlight">          ct-&gt;argList = <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a>(method-&gt;argList);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2833</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ct-&gt;brief.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2834</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2835</span><span class="doxyLineContent"><span class="doxyHighlight">            ct-&gt;brief = method-&gt;brief;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2836</span><span class="doxyLineContent"><span class="doxyHighlight">            ct-&gt;briefLine = method-&gt;briefLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2837</span><span class="doxyLineContent"><span class="doxyHighlight">            ct-&gt;briefFile = method-&gt;briefFile;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2838</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2839</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ct-&gt;doc.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2840</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2841</span><span class="doxyLineContent"><span class="doxyHighlight">            ct-&gt;doc = method-&gt;doc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2842</span><span class="doxyLineContent"><span class="doxyHighlight">            ct-&gt;docLine = method-&gt;docLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2843</span><span class="doxyLineContent"><span class="doxyHighlight">            ct-&gt;docFile = method-&gt;docFile;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2844</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2845</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2846</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2847</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2848</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2849</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/entry/#a13c49362ea71812935f0399e0f7dcf77">Entry::children</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>


<p>Referenced by <a href="#a5c191151631efdf0d25fc7967f6b0434">endScope</a>.</p>

</div>
</div>

### scanner\_abort() {#a7b2ca28396c488d5a08ead21731ed2c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void scanner_abort (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 3384 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7b2ca28396c488d5a08ead21731ed2c2">3384</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7b2ca28396c488d5a08ead21731ed2c2">scanner_abort</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3385</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3386</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3387</span><span class="doxyLineContent"><span class="doxyHighlight">  fprintf(stderr,</span><span class="doxyHighlightStringLiteral">"********************************************************************\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3388</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;blockLineNr == -1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3389</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3390</span><span class="doxyLineContent"><span class="doxyHighlight">    fprintf(stderr,</span><span class="doxyHighlightStringLiteral">"Error in file %s line: %d, state: %d(%s)\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3391</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(yyextra-&gt;fileName),yyextra-&gt;lineNr,YY_START,<a href="/web-doxygen/docs/api/files/src/code-l/#a6458e40b3ca285dc65cd5df59d63e5a5">stateToString</a>(YY_START));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3392</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3393</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3394</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3395</span><span class="doxyLineContent"><span class="doxyHighlight">    fprintf(stderr,</span><span class="doxyHighlightStringLiteral">"Error in file %s line: %d, state: %d(%s), starting command: '%s' probable line reference: %d\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3396</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(yyextra-&gt;fileName),yyextra-&gt;lineNr,YY_START,<a href="/web-doxygen/docs/api/files/src/code-l/#a6458e40b3ca285dc65cd5df59d63e5a5">stateToString</a>(YY_START),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(yyextra-&gt;blockString),yyextra-&gt;blockLineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3397</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3398</span><span class="doxyLineContent"><span class="doxyHighlight">  fprintf(stderr,</span><span class="doxyHighlightStringLiteral">"********************************************************************\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3399</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3400</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> start=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3401</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3402</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ce : yyextra-&gt;global_root-&gt;children())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3403</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3404</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ce == yyextra-&gt;file_root) start=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3405</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (start) ce-&gt;reset();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3406</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3407</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3408</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// dummy call to avoid compiler warning</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3409</span><span class="doxyLineContent"><span class="doxyHighlight">  (void)yy_top_state(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3410</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3411</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3412</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//exit(-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3413</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a6458e40b3ca285dc65cd5df59d63e5a5">stateToString</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>


<p>Referenced by <a href="#a5c191151631efdf0d25fc7967f6b0434">endScope</a>.</p>

</div>
</div>

### startCommentBlock() {#a3f8584604e877b6eb570db94e3692a92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void startCommentBlock (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, bool brief)</td>
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



<p>Definition at line 3034 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3f8584604e877b6eb570db94e3692a92">3034</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3f8584604e877b6eb570db94e3692a92">startCommentBlock</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> brief)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3035</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3036</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3037</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (brief)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3038</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3039</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;briefFile = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3040</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;briefLine = yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3041</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3042</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3043</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3044</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;docFile = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3045</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;docLine = yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3046</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3047</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a22addf63e54e56357d7a2691022828e1">initSpecialBlock</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#aa1fd664818291e7a90ed2ba46a0f44a7">initTriDoubleQuoteBlock</a> and <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a2aa292ec6b6ea81860b3d9b00405d1cb">initTriSingleQuoteBlock</a>.</p>

</div>
</div>

### startScope() {#a49e7bafaa071ffbe937ec1a85c484828}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void startScope (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, <a href="/web-doxygen/docs/api/classes/entry">Entry</a> * scope)</td>
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




<p>Starts the new scope in fortran program. Consider using this function when starting module, interface, function or other program block.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#a5c191151631efdf0d25fc7967f6b0434">endScope()</a></p></dd>
</dl>


<p>Definition at line 2555 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a49e7bafaa071ffbe937ec1a85c484828">2555</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a49e7bafaa071ffbe937ec1a85c484828">startScope</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,<a href="/web-doxygen/docs/api/classes/entry">Entry</a> *scope)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2556</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2557</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2558</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//cout&lt;&lt;"start scope: "&lt;&lt;scope-&gt;name&lt;&lt;endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2559</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current_root= scope; </span><span class="doxyHighlightComment">/* start substructure */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2560</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2561</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;modifiers.emplace(scope, std::map&lt;std::string,SymbolModifiers&gt;());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2562</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2563</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// create new current with possibly different defaults...</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2564</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current = std::make_shared&lt;Entry&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2565</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#affe329b2bcd94b04290e03afad9c97c5">initEntry</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2566</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#affe329b2bcd94b04290e03afad9c97c5">initEntry</a>.</p>


<p>Referenced by <a href="#a4ad5866bbc8d144423fe0e3f54ecb0cf">addModule</a> and <a href="#a4481d3eae9a04af883d868f23c4cbffc">parseMain</a>.</p>

</div>
</div>

### stateToString() {#a6458e40b3ca285dc65cd5df59d63e5a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * stateToString (int state)</td>
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



<p>Definition at line 252 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>

</div>
</div>

### subrHandleCommentBlock() {#a6c5f6e8cda9aa291a041f511f3a2329a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void subrHandleCommentBlock (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; doc, bool brief)</td>
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

<p>Handle parameter description as defined after the declaration of the parameter.</p>

<p>Definition at line 3095 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6c5f6e8cda9aa291a041f511f3a2329a">3095</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6c5f6e8cda9aa291a041f511f3a2329a">subrHandleCommentBlock</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;doc,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> brief)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3096</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3097</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3098</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> loc_doc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3099</span><span class="doxyLineContent"><span class="doxyHighlight">  loc_doc = doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3100</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3101</span><span class="doxyLineContent"><span class="doxyHighlight">  std::shared_ptr&lt;Entry&gt; tmp_entry = yyextra-&gt;current;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3102</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current = yyextra-&gt;subrCurrent.back(); </span><span class="doxyHighlightComment">// temporarily switch to the entry of the subroutine / function</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3103</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3104</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Still in the specification section so no inbodyDocs yet, but parameter documentation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3105</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;inbodyDocs = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3106</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3107</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// strip \\param or @param, so we can do some extra checking. We will add it later on again.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3108</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"\\param"</span><span class="doxyHighlight">) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3109</span><span class="doxyLineContent"><span class="doxyHighlight">      !loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"@param"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3110</span><span class="doxyLineContent"><span class="doxyHighlight">     ) (void)loc_doc; </span><span class="doxyHighlightComment">// Do nothing work has been done by stripPrefix; (void)loc_doc: to overcome 'empty controlled statement' warning</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3111</span><span class="doxyLineContent"><span class="doxyHighlight">  loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3112</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3113</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// direction as defined with the declaration of the parameter</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3114</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> dir1 = yyextra-&gt;modifiers[yyextra-&gt;current_root][yyextra-&gt;argName.lower().str()].direction;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3115</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// in description [in] is specified</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3116</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(<a href="#a0ab2ac9fbdd02519455880a47568829b">directionParam</a>[<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aceec8152eeb6c06b8dbe03ef14fed6a4a61e9eb5a7ae3678a1c6254b69617f4b7">SymbolModifiers::IN</a>]) == 0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3117</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3118</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// check if with the declaration intent(in) or nothing has been specified</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3119</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((<a href="#a0ab2ac9fbdd02519455880a47568829b">directionParam</a>[dir1] == <a href="#a0ab2ac9fbdd02519455880a47568829b">directionParam</a>[<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aceec8152eeb6c06b8dbe03ef14fed6a4ace26f25fe9aa85a4d1b93a09af862d8b">SymbolModifiers::NONE_D</a>]) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3120</span><span class="doxyLineContent"><span class="doxyHighlight">        (<a href="#a0ab2ac9fbdd02519455880a47568829b">directionParam</a>[dir1] == <a href="#a0ab2ac9fbdd02519455880a47568829b">directionParam</a>[<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aceec8152eeb6c06b8dbe03ef14fed6a4a61e9eb5a7ae3678a1c6254b69617f4b7">SymbolModifiers::IN</a>]))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3121</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3122</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// strip direction</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3123</span><span class="doxyLineContent"><span class="doxyHighlight">      loc_doc = loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)strlen(<a href="#a0ab2ac9fbdd02519455880a47568829b">directionParam</a>[<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aceec8152eeb6c06b8dbe03ef14fed6a4a61e9eb5a7ae3678a1c6254b69617f4b7">SymbolModifiers::IN</a>]));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3124</span><span class="doxyLineContent"><span class="doxyHighlight">      loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3125</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// in case of empty documentation or (now) just name, consider it as no documentation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3126</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; (loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>() != yyextra-&gt;argName.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3127</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3128</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>(yyscanner,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"\n\n@param "</span><span class="doxyHighlight">) + <a href="#a0ab2ac9fbdd02519455880a47568829b">directionParam</a>[<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aceec8152eeb6c06b8dbe03ef14fed6a4a61e9eb5a7ae3678a1c6254b69617f4b7">SymbolModifiers::IN</a>] + </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> +</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3129</span><span class="doxyLineContent"><span class="doxyHighlight">                         yyextra-&gt;argName + </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> + loc_doc,brief);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3130</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3131</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3132</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3133</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3134</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// something different specified, give warning and leave error.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3135</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(yyextra-&gt;fileName,yyextra-&gt;lineNr, </span><span class="doxyHighlightStringLiteral">"Routine: {}{} inconsistency between intent attribute and documentation for parameter {}:"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3136</span><span class="doxyLineContent"><span class="doxyHighlight">             yyextra-&gt;current-&gt;name,yyextra-&gt;current-&gt;args,yyextra-&gt;argName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3137</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>(yyscanner,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"\n\n@param "</span><span class="doxyHighlight">) + <a href="#a0ab2ac9fbdd02519455880a47568829b">directionParam</a>[dir1] + </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> +</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3138</span><span class="doxyLineContent"><span class="doxyHighlight">                         yyextra-&gt;argName + </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> + loc_doc,brief);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3139</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3140</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3141</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// analogous to the [in] case, here [out] direction specified</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3142</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(<a href="#a0ab2ac9fbdd02519455880a47568829b">directionParam</a>[<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aceec8152eeb6c06b8dbe03ef14fed6a4a0238d370b0f2d73432f8021cd1c1aed1">SymbolModifiers::OUT</a>]) == 0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3143</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3144</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((<a href="#a0ab2ac9fbdd02519455880a47568829b">directionParam</a>[dir1] == <a href="#a0ab2ac9fbdd02519455880a47568829b">directionParam</a>[<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aceec8152eeb6c06b8dbe03ef14fed6a4ace26f25fe9aa85a4d1b93a09af862d8b">SymbolModifiers::NONE_D</a>]) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3145</span><span class="doxyLineContent"><span class="doxyHighlight">        (<a href="#a0ab2ac9fbdd02519455880a47568829b">directionParam</a>[dir1] == <a href="#a0ab2ac9fbdd02519455880a47568829b">directionParam</a>[<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aceec8152eeb6c06b8dbe03ef14fed6a4a0238d370b0f2d73432f8021cd1c1aed1">SymbolModifiers::OUT</a>]))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3146</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3147</span><span class="doxyLineContent"><span class="doxyHighlight">      loc_doc = loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)strlen(<a href="#a0ab2ac9fbdd02519455880a47568829b">directionParam</a>[<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aceec8152eeb6c06b8dbe03ef14fed6a4a0238d370b0f2d73432f8021cd1c1aed1">SymbolModifiers::OUT</a>]));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3148</span><span class="doxyLineContent"><span class="doxyHighlight">      loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3149</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() || (loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>() == yyextra-&gt;argName.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3150</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3151</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;current = tmp_entry;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3152</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3153</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3154</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>(yyscanner,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"\n\n@param "</span><span class="doxyHighlight">) + <a href="#a0ab2ac9fbdd02519455880a47568829b">directionParam</a>[<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aceec8152eeb6c06b8dbe03ef14fed6a4a0238d370b0f2d73432f8021cd1c1aed1">SymbolModifiers::OUT</a>] + </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> +</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3155</span><span class="doxyLineContent"><span class="doxyHighlight">                         yyextra-&gt;argName + </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> + loc_doc,brief);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3156</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3157</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3158</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3159</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(yyextra-&gt;fileName,yyextra-&gt;lineNr, </span><span class="doxyHighlightStringLiteral">"Routine: {}{} inconsistency between intent attribute and documentation for parameter {}:"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3160</span><span class="doxyLineContent"><span class="doxyHighlight">             yyextra-&gt;current-&gt;name,yyextra-&gt;current-&gt;args,yyextra-&gt;argName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3161</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>(yyscanner,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"\n\n@param "</span><span class="doxyHighlight">) + <a href="#a0ab2ac9fbdd02519455880a47568829b">directionParam</a>[dir1] + </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> +</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3162</span><span class="doxyLineContent"><span class="doxyHighlight">                         yyextra-&gt;argName + </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> + loc_doc,brief);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3163</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3164</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3165</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// analogous to the [in] case, here [in,out] direction specified</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3166</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(<a href="#a0ab2ac9fbdd02519455880a47568829b">directionParam</a>[<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aceec8152eeb6c06b8dbe03ef14fed6a4a3274f871e28c11b61c8256d20296aa27">SymbolModifiers::INOUT</a>]) == 0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3167</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3168</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((<a href="#a0ab2ac9fbdd02519455880a47568829b">directionParam</a>[dir1] == <a href="#a0ab2ac9fbdd02519455880a47568829b">directionParam</a>[<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aceec8152eeb6c06b8dbe03ef14fed6a4ace26f25fe9aa85a4d1b93a09af862d8b">SymbolModifiers::NONE_D</a>]) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3169</span><span class="doxyLineContent"><span class="doxyHighlight">        (<a href="#a0ab2ac9fbdd02519455880a47568829b">directionParam</a>[dir1] == <a href="#a0ab2ac9fbdd02519455880a47568829b">directionParam</a>[<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aceec8152eeb6c06b8dbe03ef14fed6a4a3274f871e28c11b61c8256d20296aa27">SymbolModifiers::INOUT</a>]))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3170</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3171</span><span class="doxyLineContent"><span class="doxyHighlight">      loc_doc = loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)strlen(<a href="#a0ab2ac9fbdd02519455880a47568829b">directionParam</a>[<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aceec8152eeb6c06b8dbe03ef14fed6a4a3274f871e28c11b61c8256d20296aa27">SymbolModifiers::INOUT</a>]));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3172</span><span class="doxyLineContent"><span class="doxyHighlight">      loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3173</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; (loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>() != yyextra-&gt;argName.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3174</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3175</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>(yyscanner,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"\n\n@param "</span><span class="doxyHighlight">) + <a href="#a0ab2ac9fbdd02519455880a47568829b">directionParam</a>[<a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aceec8152eeb6c06b8dbe03ef14fed6a4a3274f871e28c11b61c8256d20296aa27">SymbolModifiers::INOUT</a>] + </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> +</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3176</span><span class="doxyLineContent"><span class="doxyHighlight">                           yyextra-&gt;argName + </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> + loc_doc,brief);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3177</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3178</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3179</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3180</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3181</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(yyextra-&gt;fileName,yyextra-&gt;lineNr, </span><span class="doxyHighlightStringLiteral">"Routine: {}{} inconsistency between intent attribute and documentation for parameter {}:"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3182</span><span class="doxyLineContent"><span class="doxyHighlight">             yyextra-&gt;current-&gt;name,yyextra-&gt;current-&gt;args,yyextra-&gt;argName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3183</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>(yyscanner,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"\n\n@param "</span><span class="doxyHighlight">) + <a href="#a0ab2ac9fbdd02519455880a47568829b">directionParam</a>[dir1] + </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> +</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3184</span><span class="doxyLineContent"><span class="doxyHighlight">                         yyextra-&gt;argName + </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> + loc_doc,brief);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3185</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3186</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3187</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// analogous to the [in] case; here no direction specified</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3188</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; (loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>() != yyextra-&gt;argName.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3189</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3190</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>(yyscanner,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"\n\n@param "</span><span class="doxyHighlight">) + <a href="#a0ab2ac9fbdd02519455880a47568829b">directionParam</a>[dir1] + </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> +</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3191</span><span class="doxyLineContent"><span class="doxyHighlight">                       yyextra-&gt;argName + </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> + loc_doc,brief);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3192</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3193</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3194</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// reset yyextra-&gt;current back to the part inside the routine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3195</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current = tmp_entry;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3196</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a0ab2ac9fbdd02519455880a47568829b">directionParam</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aceec8152eeb6c06b8dbe03ef14fed6a4a61e9eb5a7ae3678a1c6254b69617f4b7">SymbolModifiers::IN</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aceec8152eeb6c06b8dbe03ef14fed6a4a3274f871e28c11b61c8256d20296aa27">SymbolModifiers::INOUT</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aceec8152eeb6c06b8dbe03ef14fed6a4ace26f25fe9aa85a4d1b93a09af862d8b">SymbolModifiers::NONE_D</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aceec8152eeb6c06b8dbe03ef14fed6a4a0238d370b0f2d73432f8021cd1c1aed1">SymbolModifiers::OUT</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">QCString::right</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">QCString::stripPrefix</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.</p>

</div>
</div>

### subrHandleCommentBlockResult() {#a746c69943bdf7ff71cbd6e6aa44b875d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void subrHandleCommentBlockResult (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; doc, bool brief)</td>
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

<p>Handle result description as defined after the declaration of the parameter.</p>

<p>Definition at line 3199 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a746c69943bdf7ff71cbd6e6aa44b875d">3199</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a746c69943bdf7ff71cbd6e6aa44b875d">subrHandleCommentBlockResult</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;doc,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> brief)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3200</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3201</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3202</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> loc_doc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3203</span><span class="doxyLineContent"><span class="doxyHighlight">  loc_doc = doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3204</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3205</span><span class="doxyLineContent"><span class="doxyHighlight">  std::shared_ptr&lt;Entry&gt; tmp_entry = yyextra-&gt;current;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3206</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current = yyextra-&gt;subrCurrent.back(); </span><span class="doxyHighlightComment">// temporarily switch to the entry of the subroutine / function</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3207</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3208</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Still in the specification section so no inbodyDocs yet, but parameter documentation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3209</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;inbodyDocs = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3210</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3211</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// strip \\returns or @returns. We will add it later on again.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3212</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"\\returns"</span><span class="doxyHighlight">) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3213</span><span class="doxyLineContent"><span class="doxyHighlight">      !loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"\\return"</span><span class="doxyHighlight">) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3214</span><span class="doxyLineContent"><span class="doxyHighlight">      !loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"@returns"</span><span class="doxyHighlight">) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3215</span><span class="doxyLineContent"><span class="doxyHighlight">      !loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"@return"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3216</span><span class="doxyLineContent"><span class="doxyHighlight">     ) (void)loc_doc; </span><span class="doxyHighlightComment">// Do nothing work has been done by stripPrefix; (void)loc_doc: to overcome 'empty controlled statement' warning</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3217</span><span class="doxyLineContent"><span class="doxyHighlight">  loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3218</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3219</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; (loc_doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>() != yyextra-&gt;argName.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3220</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3221</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>(yyscanner,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"\n\n@returns "</span><span class="doxyHighlight">) + loc_doc,brief);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3222</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3223</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3224</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// reset yyextra-&gt;current back to the part inside the routine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3225</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current = std::move(tmp_entry);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3226</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">QCString::stripPrefix</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>.</p>

</div>
</div>

### truncatePrepass() {#afac5fd6d0047c7134afcef46db6a4ab8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void truncatePrepass (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, int index)</td>
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



<p>Definition at line 1842 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afac5fd6d0047c7134afcef46db6a4ab8">1842</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afac5fd6d0047c7134afcef46db6a4ab8">truncatePrepass</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> index)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1843</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1844</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1845</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> length = yyextra-&gt;inputStringPrepass.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1846</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=index+1; i&lt;length; i++) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1847</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;inputStringPrepass[i]==</span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight"> &amp;&amp; i&lt;length-1 &amp;&amp; yyextra-&gt;inputStringPrepass[i+1]==</span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">) { </span><span class="doxyHighlightComment">// save comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1848</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;comments.emplace_back(index, yyextra-&gt;inputStringPrepass.right(length-i-2));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1849</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1850</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1851</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputStringPrepass.resize(index);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1852</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### updateVariablePrepassComment() {#a9e2f432a75f34796b2cdda24ee7cb9b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void updateVariablePrepassComment (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, int from, int to)</td>
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



<p>Definition at line 1741 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9e2f432a75f34796b2cdda24ee7cb9b0">1741</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9e2f432a75f34796b2cdda24ee7cb9b0">updateVariablePrepassComment</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> from, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> to)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1742</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1743</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1744</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/commentinprepass">CommentInPrepass</a> *c = <a href="#a58823d73b17b4a3c6b782a7e14904c77">locatePrepassComment</a>(yyscanner,from, to);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1745</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c &amp;&amp; yyextra-&gt;vtype == <a href="#a238692c76adb8cefb158cf28754f52d6ab238d5b991ac184d0de8dca5478f5e5c">V_VARIABLE</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1746</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1747</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;last_entry-&gt;brief = c-&gt;<a href="/web-doxygen/docs/api/structs/commentinprepass/#a121d4cd80b9102d3c562acbef48952ca">str</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1748</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1749</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c &amp;&amp; yyextra-&gt;vtype == <a href="#a238692c76adb8cefb158cf28754f52d6abc50e5df37302e97005583c6ae1257a3">V_PARAMETER</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1750</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1751</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/argument">Argument</a> *parameter = <a href="#a6c050f3e9b9e8855bad36862ab3173ba">getParameter</a>(yyscanner,yyextra-&gt;argName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1752</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (parameter) parameter-&gt;<a href="/web-doxygen/docs/api/structs/argument/#a5d6cd35aa392b1703acf14104b19c589">docs</a> = c-&gt;<a href="/web-doxygen/docs/api/structs/commentinprepass/#a121d4cd80b9102d3c562acbef48952ca">str</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1753</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1754</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/argument/#a5d6cd35aa392b1703acf14104b19c589">Argument::docs</a>, <a href="#a6c050f3e9b9e8855bad36862ab3173ba">getParameter</a>, <a href="#a58823d73b17b4a3c6b782a7e14904c77">locatePrepassComment</a>, <a href="/web-doxygen/docs/api/structs/commentinprepass/#a121d4cd80b9102d3c562acbef48952ca">CommentInPrepass::str</a>, <a href="#a238692c76adb8cefb158cf28754f52d6abc50e5df37302e97005583c6ae1257a3">V_PARAMETER</a> and <a href="#a238692c76adb8cefb158cf28754f52d6ab238d5b991ac184d0de8dca5478f5e5c">V_VARIABLE</a>.</p>

</div>
</div>

### yylex() {#a1d80d8ed8c19744ed31163f6e7525e54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int yylex (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>fortran parsing states</p>


<p>comment parsing states prototype parsing</p>


<p>Definition at line 369 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1d80d8ed8c19744ed31163f6e7525e54">369</a></span><span class="doxyLineContent"><span class="doxyHighlight">%%</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*-----------------------------------------------------------------------------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Prepass&gt;^{BS}[&amp;]*{BS}!.*\n</span><span class="doxyHighlight">             { </span><span class="doxyHighlightComment">/* skip lines with just comment. Note code was in free format or has been converted to it */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;lineCountPrepass ++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Prepass&gt;^{BS}\n</span><span class="doxyHighlight">                        { </span><span class="doxyHighlightComment">/* skip empty lines */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;lineCountPrepass ++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;^.*\n</span><span class="doxyHighlight">                                { </span><span class="doxyHighlightComment">// prepass: look for line continuations</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;functionLine = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr, </span><span class="doxyHighlightStringLiteral">"---%s"</span><span class="doxyHighlight">, yytext));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> indexStart = <a href="#a094e0d8bb2b1b92d7a51f8370c76a018">getAmpersandAtTheStart</a>(yytext, (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> indexEnd = <a href="#a57a320e051e7596c3106c1a95ae02915">getAmpOrExclAtTheEnd</a>(yytext, (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)yyleng, </span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (indexEnd&gt;=0 &amp;&amp; yytext[indexEnd]!=</span><span class="doxyHighlightCharLiteral">'&amp;'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">//we are only interested in amp</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">                                            indexEnd=-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (indexEnd&lt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">                                          { </span><span class="doxyHighlightComment">// ----- no ampersand as line continuation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">                                             </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START == Prepass)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">                                             { </span><span class="doxyHighlightComment">// last line in "continuation"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span><span class="doxyLineContent"><span class="doxyHighlight">                                               </span><span class="doxyHighlightComment">// Only take input after initial ampersand</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">                                               yyextra-&gt;inputStringPrepass+=(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)(yytext+(indexStart+1));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">                                               </span><span class="doxyHighlightComment">//printf("BUFFER:%s\n", (const char*)yyextra-&gt;inputStringPrepass);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">                                               <a href="#ab536b3c2ec35df931a4fce0dbf2e1420">pushBuffer</a>(yyscanner,yyextra-&gt;inputStringPrepass);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlight">                                               yyextra-&gt;colNr = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">402</span><span class="doxyLineContent"><span class="doxyHighlight">                                               <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">                                             }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">                                             </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">405</span><span class="doxyLineContent"><span class="doxyHighlight">                                             { </span><span class="doxyHighlightComment">// simple line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">406</span><span class="doxyLineContent"><span class="doxyHighlight">                                               yyextra-&gt;colNr = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">407</span><span class="doxyLineContent"><span class="doxyHighlight">                                               REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">408</span><span class="doxyLineContent"><span class="doxyHighlight">                                             }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">409</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">411</span><span class="doxyLineContent"><span class="doxyHighlight">                                          { </span><span class="doxyHighlightComment">// ----- line with continuation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">412</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START != Prepass)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">413</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">414</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;comments.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">415</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;inputStringPrepass=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yy_push_state(Prepass,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">417</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">418</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">419</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> length = yyextra-&gt;inputStringPrepass.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">421</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">// Only take input after initial ampersand</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">422</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;inputStringPrepass+=(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)(yytext+(indexStart+1));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">423</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;lineCountPrepass ++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">424</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">425</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">// cut off &amp; and remove following comment if present</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">426</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#afac5fd6d0047c7134afcef46db6a4ab8">truncatePrepass</a>(yyscanner,</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(length) + indexEnd - indexStart - 1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">427</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">428</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">429</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">430</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">431</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*------ ignore strings that are not initialization strings */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">432</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;String&gt;\"|\'</span><span class="doxyHighlight">                           { </span><span class="doxyHighlightComment">// string ends with next quote without previous backspace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">433</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yytext[0]!=yyextra-&gt;stringStartSymbol)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">434</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">435</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;colNr -= (int)yyleng;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">                                            REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span><span class="doxyLineContent"><span class="doxyHighlight">                                          } </span><span class="doxyHighlightComment">// single vs double quote</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yy_top_state(yyscanner) == Initialization ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">439</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yy_top_state(yyscanner) == ArrayInitializer)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">441</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;initializer+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">442</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;String&gt;[\x80-\xFF]*</span><span class="doxyHighlight">                    |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">446</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;String&gt;.</span><span class="doxyHighlight">                               { </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yy_top_state(yyscanner) == Initialization ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">447</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yy_top_state(yyscanner) == ArrayInitializer)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;initializer+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;\"|\'</span><span class="doxyHighlight">                                { </span><span class="doxyHighlightComment">/* string starts */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START == StrIgnore)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">                                          { yyextra-&gt;colNr -= (int)yyleng;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">                                            REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }; </span><span class="doxyHighlightComment">// ignore in simple yyextra-&gt;comments</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">457</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(YY_START,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yy_top_state(yyscanner) == Initialization ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yy_top_state(yyscanner) == ArrayInitializer)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;initializer+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;stringStartSymbol=yytext[0]; </span><span class="doxyHighlightComment">// single or double quote</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(String);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*------ ignore simple comment (not documentation yyextra-&gt;comments) */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;"!"/[^&lt;&gt;\n]</span><span class="doxyHighlight">                         {  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START == String || YY_START == DocCopyBlock)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">                                          { yyextra-&gt;colNr -= (int)yyleng;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">                                            REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">                                          } </span><span class="doxyHighlightComment">// "!" is ignored in strings</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">// skip comment line (without docu yyextra-&gt;comments "!&gt;" "!&lt;" )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">/* ignore further "!" and ignore yyextra-&gt;comments in Strings */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((YY_START != StrIgnore) &amp;&amp; (YY_START != String))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yy_push_state(YY_START,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(StrIgnore);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">479</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;debugStr=</span><span class="doxyHighlightStringLiteral">"*!"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr,</span><span class="doxyHighlightStringLiteral">"start comment %d\n"</span><span class="doxyHighlight">,yyextra-&gt;lineNr));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">                                           }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;StrIgnore&gt;.?/\n</span><span class="doxyHighlight">                        { <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner); </span><span class="doxyHighlightComment">// comment ends with endline character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr,</span><span class="doxyHighlightStringLiteral">"end comment %d %s\n"</span><span class="doxyHighlight">,yyextra-&gt;lineNr,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(yyextra-&gt;debugStr)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">                                        } </span><span class="doxyHighlightComment">// comment line ends</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;StrIgnore&gt;[\x80-\xFF]*</span><span class="doxyHighlight">                 |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;StrIgnore&gt;.</span><span class="doxyHighlight">                            { yyextra-&gt;debugStr+=yytext; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*------ use handling ------------------------------------------------------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start,ModuleBody,SubprogBody&gt;"use"{BS_}</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START == Start)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a4ad5866bbc8d144423fe0e3f54ecb0cf">addModule</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yy_push_state(ModuleBody,yyscanner); </span><span class="doxyHighlightComment">//anon program</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(Use,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Use&gt;{ID}</span><span class="doxyHighlight">                               {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr,</span><span class="doxyHighlightStringLiteral">"using dir %s\n"</span><span class="doxyHighlight">,yytext));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;name=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;name=yyextra-&gt;current-&gt;name.lower();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;fileName = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;section=EntryType::makeUsingDir();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current_root-&gt;moveToSubEntryAndRefresh(yyextra-&gt;current);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;lang = SrcLangExt::Fortran;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Use&gt;{ID}/,</span><span class="doxyHighlight">                             {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;useModuleName=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;useModuleName=yyextra-&gt;useModuleName.lower();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">513</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">514</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Use&gt;,{BS}"ONLY"</span><span class="doxyHighlight">                        { BEGIN(UseOnly);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">515</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">516</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;UseOnly&gt;{BS},{BS}</span><span class="doxyHighlight">                      {}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">517</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;UseOnly&gt;{ID}</span><span class="doxyHighlight">                           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">518</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;name= yyextra-&gt;useModuleName+</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">+yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;name=yyextra-&gt;current-&gt;name.lower();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;fileName = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">521</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;section=EntryType::makeUsingDecl();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current_root-&gt;moveToSubEntryAndRefresh(yyextra-&gt;current);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;lang = SrcLangExt::Fortran;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">525</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Use,UseOnly&gt;"\n"</span><span class="doxyHighlight">                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">526</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;colNr -= 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">527</span><span class="doxyLineContent"><span class="doxyHighlight">                                          unput(*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">528</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">529</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">530</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">531</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/* INTERFACE definitions */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">532</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start,ModuleBody,SubprogBody&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">533</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">^{BS}interface{IDSYM}+</span><span class="doxyHighlight">                  { </span><span class="doxyHighlightComment">/* variable with interface prefix */</span><span class="doxyHighlight"> }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">534</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">^{BS}interface</span><span class="doxyHighlight">                          { yyextra-&gt;ifType = <a href="#af1ef2c97e255bd7f21d3b7614b283d9da89f0d2424cf9ae9c82a868376ceb29b9">IF_SPECIFIC</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">535</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(InterfaceBody,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">536</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">// do not start a scope here, every</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">537</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">// interface body is a scope of its own</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">538</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">539</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">540</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">^{BS}abstract{BS_}interface</span><span class="doxyHighlight">             { yyextra-&gt;ifType = <a href="#af1ef2c97e255bd7f21d3b7614b283d9daa33f8bd097d7a6cd1210bed71c5cb937">IF_ABSTRACT</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">541</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(InterfaceBody,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">542</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">// do not start a scope here, every</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">543</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">// interface body is a scope of its own</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">544</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">545</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">546</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">^{BS}interface{BS_}{ID}{ARGS}?</span><span class="doxyHighlight">          { yyextra-&gt;ifType = <a href="#af1ef2c97e255bd7f21d3b7614b283d9da5d1432a4cae2b52cafb669c901908aa5">IF_GENERIC</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">547</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;bodyLine = yyextra-&gt;lineNr + yyextra-&gt;lineCountPrepass + 1; </span><span class="doxyHighlightComment">// we have to be at the line after the definition and we have to take continuation lines into account.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">548</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(InterfaceBody,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">549</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">550</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">// extract generic name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">551</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">552</span><span class="doxyLineContent"><span class="doxyHighlight">                                          name = name.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(name.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() - 9).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">553</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac57b965357c0cd3448f8bac617563e29">addInterface</a>(yyscanner,name, yyextra-&gt;ifType);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">554</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a1eb414a7080ee6bcef950eba00f991b7">startScope</a>(yyscanner,yyextra-&gt;last_entry.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">555</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">556</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">557</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">558</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;InterfaceBody&gt;^{BS}end{BS}interface({BS_}{ID})?</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">559</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">// end scope only if GENERIC interface</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">560</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;ifType == <a href="#af1ef2c97e255bd7f21d3b7614b283d9da5d1432a4cae2b52cafb669c901908aa5">IF_GENERIC</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">561</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;last_entry-&gt;parent()-&gt;endBodyLine = yyextra-&gt;lineNr - 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">563</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;ifType == <a href="#af1ef2c97e255bd7f21d3b7614b283d9da5d1432a4cae2b52cafb669c901908aa5">IF_GENERIC</a> &amp;&amp; !<a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a239ee1e47d4722402cd650ae2d0cd59f">endScope</a>(yyscanner,yyextra-&gt;current_root))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">566</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#ac3286b18a2e91b4571b97df96a118e84">yyterminate</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">567</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">568</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;ifType = <a href="#af1ef2c97e255bd7f21d3b7614b283d9da46dbf2e0f925aa7b0f3f9edd25acf5e6">IF_NONE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">569</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">570</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">571</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;InterfaceBody&gt;module{BS}procedure</span><span class="doxyHighlight">      { yy_push_state(YY_START,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">572</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(ModuleProcedure);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ModuleProcedure&gt;{ID}</span><span class="doxyHighlight">                   { <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">575</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;ifType == <a href="#af1ef2c97e255bd7f21d3b7614b283d9daa33f8bd097d7a6cd1210bed71c5cb937">IF_ABSTRACT</a> || yyextra-&gt;ifType == <a href="#af1ef2c97e255bd7f21d3b7614b283d9da89f0d2424cf9ae9c82a868376ceb29b9">IF_SPECIFIC</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">576</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">577</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#ac57b965357c0cd3448f8bac617563e29">addInterface</a>(yyscanner,name, yyextra-&gt;ifType);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">578</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a1eb414a7080ee6bcef950eba00f991b7">startScope</a>(yyscanner,yyextra-&gt;last_entry.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;section = EntryType::makeFunction();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;name = name; </span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;moduleProcedures.push_back(yyextra-&gt;current);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">584</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a1f86638786429418e4c584f9b98ec3d4">addCurrentEntry</a>(yyscanner,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">586</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ModuleProcedure&gt;"\n"</span><span class="doxyHighlight">                   { yyextra-&gt;colNr -= 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">587</span><span class="doxyLineContent"><span class="doxyHighlight">                                          unput(*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">589</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">590</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;InterfaceBody&gt;.</span><span class="doxyHighlight">                        {}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">591</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">592</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*-- Contains handling --*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">593</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;^{BS}{CONTAINS}/({BS}|\n|!|;)</span><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START == Start)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a4ad5866bbc8d144423fe0e3f54ecb0cf">addModule</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yy_push_state(ModuleBodyContains,yyscanner); </span><span class="doxyHighlightComment">//anon program</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ModuleBody&gt;^{BS}{CONTAINS}/({BS}|\n|!|;)</span><span class="doxyHighlight">   { BEGIN(ModuleBodyContains); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">601</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SubprogBody&gt;^{BS}{CONTAINS}/({BS}|\n|!|;)</span><span class="doxyHighlight">  { BEGIN(SubprogBodyContains); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">602</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;TypedefBody&gt;^{BS}{CONTAINS}/({BS}|\n|!|;)</span><span class="doxyHighlight">  { BEGIN(TypedefBodyContains); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">603</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">604</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*------ module handling ------------------------------------------------------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;block{BS}data{BS}{ID_}</span><span class="doxyHighlight">           {  </span><span class="doxyHighlightComment">//</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;vtype = <a href="#a238692c76adb8cefb158cf28754f52d6a2e626c4ec60ad2b9514c8984aa1eb3ec">V_IGNORE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(BlockData,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defaultProtection = Protection::Public;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;module|program{BS_}</span><span class="doxyHighlight">              {  </span><span class="doxyHighlightComment">//</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;vtype = <a href="#a238692c76adb8cefb158cf28754f52d6a2e626c4ec60ad2b9514c8984aa1eb3ec">V_IGNORE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yytext[0]==</span><span class="doxyHighlightCharLiteral">'m'</span><span class="doxyHighlight"> || yytext[0]==</span><span class="doxyHighlightCharLiteral">'M'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">613</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">614</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yy_push_state(<a href="/web-doxygen/docs/api/files/src/types-h/#a6dc2e6c0ceaaa530cb9859af8d37449dae55f75a29310d7b60f7ac1d390c8ae42">Module</a>,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">615</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">616</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">618</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yy_push_state(Program,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">619</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">620</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defaultProtection = Protection::Public;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">621</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">622</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;BlockData&gt;^{BS}"end"({BS}(block{BS}data)({BS_}{ID})?)?{BS}/(\n|!|;)</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// end block data</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">623</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//if (!endScope(yyscanner,yyextra-&gt;current_root))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">624</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//  yyterminate();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">625</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defaultProtection = Protection::Public;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">626</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">627</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">628</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start,ModuleBody,ModuleBodyContains&gt;"end"({BS}(module|program)({BS_}{ID})?)?{BS}/(\n|!|;)</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// end module</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">629</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a117a119a3d5a5d0dc330e3d6eade5c04">resolveModuleProcedures</a>(yyscanner,yyextra-&gt;current_root);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">630</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a239ee1e47d4722402cd650ae2d0cd59f">endScope</a>(yyscanner,yyextra-&gt;current_root))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">631</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">632</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#ac3286b18a2e91b4571b97df96a118e84">yyterminate</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">633</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">634</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defaultProtection = Protection::Public;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">635</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;global_scope)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">636</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">637</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;global_scope != <a href="#a1dfbc2208b3f32fc3d8dca63bd941c08">INVALID_ENTRY</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">638</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">639</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yy_push_state(Start,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">640</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">641</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">642</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">643</span><span class="doxyLineContent"><span class="doxyHighlight">                                              <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner); </span><span class="doxyHighlightComment">// cannot pop artrificial entry</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">644</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">645</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">646</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">647</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">648</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yy_push_state(Start,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">649</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;global_scope = <a href="#a1dfbc2208b3f32fc3d8dca63bd941c08">INVALID_ENTRY</a>; </span><span class="doxyHighlightComment">// signal that the yyextra-&gt;global_scope has already been used.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">650</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">651</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">652</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Module&gt;{ID}</span><span class="doxyHighlight">                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">653</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4ad5866bbc8d144423fe0e3f54ecb0cf">addModule</a>(yyscanner, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext), <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">654</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(ModuleBody);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">655</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">656</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Program&gt;{ID}</span><span class="doxyHighlight">                           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">657</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a4ad5866bbc8d144423fe0e3f54ecb0cf">addModule</a>(yyscanner, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext), <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">658</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(ModuleBody);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">659</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">660</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">661</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/*------- access specification --------------------------------------------------------------------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">662</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">663</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ModuleBody,TypedefBody,TypedefBodyContains&gt;private/{BS}(\n|"!")</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">664</span><span class="doxyLineContent"><span class="doxyHighlight">                                           yyextra-&gt;defaultProtection = Protection::Private;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">665</span><span class="doxyLineContent"><span class="doxyHighlight">                                           yyextra-&gt;current-&gt;protection = yyextra-&gt;defaultProtection ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">666</span><span class="doxyLineContent"><span class="doxyHighlight">                                         }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ModuleBody,TypedefBody,TypedefBodyContains&gt;public/{BS}(\n|"!")</span><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">668</span><span class="doxyLineContent"><span class="doxyHighlight">                                           yyextra-&gt;defaultProtection = Protection::Public;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">                                           yyextra-&gt;current-&gt;protection = yyextra-&gt;defaultProtection ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">670</span><span class="doxyLineContent"><span class="doxyHighlight">                                         }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">671</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">672</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*------- type definition  -------------------------------------------------------------------------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">673</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">674</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ModuleBody&gt;^{BS}type{BS}"="</span><span class="doxyHighlight">            {}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">675</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start,ModuleBody&gt;^{BS}type/[^a-z0-9_]</span><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">676</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START == Start)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">677</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">678</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a4ad5866bbc8d144423fe0e3f54ecb0cf">addModule</a>(yyscanner,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">679</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yy_push_state(ModuleBody,yyscanner); </span><span class="doxyHighlightComment">//anon program</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">680</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">681</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">682</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(<a href="/web-doxygen/docs/api/files/src/types-h/#a55cbcb91fc25e3a2e785b8a30309843ca5fede51b97a819dedf4f83bc2aacbc6a">Typedef</a>,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">683</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;protection = Protection::Package; </span><span class="doxyHighlightComment">// invalid in Fortran, replaced below</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">684</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;typeProtection = Protection::Public;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">685</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;typeMode = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">686</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">687</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Typedef&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">688</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">{COMMA}</span><span class="doxyHighlight">                                 {}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">689</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">690</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">{BS}"::"{BS}</span><span class="doxyHighlight">                            {}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">691</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">692</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">abstract</span><span class="doxyHighlight">                                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">693</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;spec.setAbstractClass(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">694</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">extends{ARGS}</span><span class="doxyHighlight">                           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">696</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> basename = <a href="#a25c73dbd285ac4ed23985634ad1a9cab">extractFromParens</a>(yytext).<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">697</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;extends.emplace_back(basename, Protection::Public, Specifier::Normal);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">698</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">699</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">public</span><span class="doxyHighlight">                                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">700</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;protection = Protection::Public;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">701</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">702</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">private</span><span class="doxyHighlight">                                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">703</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;protection = Protection::Private;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">704</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">705</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">{LANGUAGE_BIND_SPEC}</span><span class="doxyHighlight">                    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">706</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">/* ignored for now */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">707</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">708</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">{ID}</span><span class="doxyHighlight">                                    { </span><span class="doxyHighlightComment">/* type name found */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">709</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;section = EntryType::makeClass();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">710</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;spec.setStruct(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">711</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;name = yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">712</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;fileName = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">713</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;bodyLine  = yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">714</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;startLine  = yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">715</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">716</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">/* if type is part of a module, mod name is necessary for output */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">717</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;current_root &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">718</span><span class="doxyLineContent"><span class="doxyHighlight">                                              (yyextra-&gt;current_root-&gt;section.isClass() ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">719</span><span class="doxyLineContent"><span class="doxyHighlight">                                               yyextra-&gt;current_root-&gt;section.isNamespace()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">720</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">721</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;current-&gt;name = yyextra-&gt;current_root-&gt;name + </span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight"> + yyextra-&gt;current-&gt;name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">722</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">723</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">724</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">// set modifiers to allow adjusting public/private in surrounding module scope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">725</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">( yyextra-&gt;current-&gt;protection == Protection::Package )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">726</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">727</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;current-&gt;protection = yyextra-&gt;defaultProtection;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">728</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">729</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">( yyextra-&gt;current-&gt;protection == Protection::Public )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">730</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">731</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;modifiers[yyextra-&gt;current_root][yyextra-&gt;current-&gt;name.lower().str()] |= <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"public"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">732</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">733</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">( yyextra-&gt;current-&gt;protection == Protection::Private )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">734</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">735</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;modifiers[yyextra-&gt;current_root][yyextra-&gt;current-&gt;name.lower().str()] |= <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"private"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">736</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">737</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">738</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a1f86638786429418e4c584f9b98ec3d4">addCurrentEntry</a>(yyscanner,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">739</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a1eb414a7080ee6bcef950eba00f991b7">startScope</a>(yyscanner,yyextra-&gt;last_entry.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">740</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(TypedefBody);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">741</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">742</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">743</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">744</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;TypedefBodyContains&gt;{</span><span class="doxyHighlight">                  </span><span class="doxyHighlightComment">/* Type Bound Procedures */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">745</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">^{BS}PROCEDURE{ARGS}?</span><span class="doxyHighlight">                   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">746</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;type = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/classes/qcstring/#a8d6ace0deb439b916b9f97f54a6c9cc2">simplifyWhiteSpace</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">747</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">748</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">^{BS}final</span><span class="doxyHighlight">                              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">749</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;spec.setFinal(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">750</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;type = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/classes/qcstring/#a8d6ace0deb439b916b9f97f54a6c9cc2">simplifyWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">751</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">752</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">^{BS}generic</span><span class="doxyHighlight">                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">753</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;type = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/classes/qcstring/#a8d6ace0deb439b916b9f97f54a6c9cc2">simplifyWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">754</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">755</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">{COMMA}</span><span class="doxyHighlight">                                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">756</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">757</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">{ATTR_SPEC}</span><span class="doxyHighlight">                             {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">758</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;currentModifiers |= <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">759</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">760</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">{BS}"::"{BS}</span><span class="doxyHighlight">                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">761</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">762</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">{ID}</span><span class="doxyHighlight">                                    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">763</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name = yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">764</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;modifiers[yyextra-&gt;current_root][name.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()] |= yyextra-&gt;currentModifiers;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">765</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;section  = EntryType::makeFunction();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">766</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;name     = name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">767</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">// check for procedure(name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">768</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;current-&gt;type.find(</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">) != -1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">769</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">770</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;current-&gt;args = <a href="#a25c73dbd285ac4ed23985634ad1a9cab">extractFromParens</a>(yyextra-&gt;current-&gt;type).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">771</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">772</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">773</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">774</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;current-&gt;args = name.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>(); </span><span class="doxyHighlightComment">// target procedure name if no =&gt; is given</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">775</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">776</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;fileName = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">777</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;bodyLine = yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">778</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;startLine  = yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">779</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a1f86638786429418e4c584f9b98ec3d4">addCurrentEntry</a>(yyscanner,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">780</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">781</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">{BS}"=&gt;"[^(\n|\!)]*</span><span class="doxyHighlight">                     { </span><span class="doxyHighlightComment">/* Specific bindings come after the ID. */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">782</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tmp = yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">783</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = tmp.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"=&gt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">784</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">785</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">786</span><span class="doxyLineContent"><span class="doxyHighlight">                                            tmp.<a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">remove</a>(0, i+2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">787</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">788</span><span class="doxyLineContent"><span class="doxyHighlight">                                          tmp = tmp.<a href="/web-doxygen/docs/api/classes/qcstring/#a8d6ace0deb439b916b9f97f54a6c9cc2">simplifyWhiteSpace</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">789</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;last_entry-&gt;type == </span><span class="doxyHighlightStringLiteral">"generic"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">790</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">791</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">// duplicate entries for each overloaded variant</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">792</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">// (parse through medhod1,method2, methodN, ...</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">793</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">//printf("Parsing through %s for generic method %s.\n", tmp.data(), last_entry-&gt;name.data());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">794</span><span class="doxyLineContent"><span class="doxyHighlight">                                            i = tmp.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">795</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">796</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">797</span><span class="doxyLineContent"><span class="doxyHighlight">                                              <a href="#a6bd7068dc789461b065785069d7251aa">copyEntry</a>(yyextra-&gt;current, yyextra-&gt;last_entry);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">798</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;current-&gt;name = yyextra-&gt;last_entry-&gt;name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">799</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;current-&gt;section = EntryType::makeFunction();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">800</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;last_entry-&gt;args = tmp.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(i).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">801</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightComment">//printf("Found %s.\n", last_entry-&gt;args.data());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">802</span><span class="doxyLineContent"><span class="doxyHighlight">                                              <a href="#a1f86638786429418e4c584f9b98ec3d4">addCurrentEntry</a>(yyscanner,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">803</span><span class="doxyLineContent"><span class="doxyHighlight">                                              tmp = tmp.<a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">remove</a>(0,i+1).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">804</span><span class="doxyLineContent"><span class="doxyHighlight">                                              i = tmp.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">805</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">806</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">807</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//printf("Target function: %s\n", tmp.data());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">808</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;last_entry-&gt;args = tmp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">809</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">810</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">                                    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">811</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;currentModifiers = <a href="/web-doxygen/docs/api/structs/symbolmodifiers">SymbolModifiers</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">812</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a146a464d8664e6fe5cd764e866726ac1">newLine</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">813</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">814</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">815</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">816</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">817</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">818</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;TypedefBody,TypedefBodyContains&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">819</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">^{BS}"end"{BS}"type"({BS_}{ID})?{BS}/(\n|!|;)</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">/* end type definition */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">820</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;last_entry-&gt;parent()-&gt;endBodyLine = yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">821</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a239ee1e47d4722402cd650ae2d0cd59f">endScope</a>(yyscanner,yyextra-&gt;current_root))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">822</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">823</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#ac3286b18a2e91b4571b97df96a118e84">yyterminate</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">824</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">825</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;typeMode = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">826</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">827</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">828</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">^{BS}"end"{BS}/(\n|!|;)</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">/* incorrect end type definition */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">829</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(yyextra-&gt;fileName,yyextra-&gt;lineNr, </span><span class="doxyHighlightStringLiteral">"Found 'END' instead of 'END TYPE'"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">830</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;last_entry-&gt;parent()-&gt;endBodyLine = yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">831</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a239ee1e47d4722402cd650ae2d0cd59f">endScope</a>(yyscanner,yyextra-&gt;current_root))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">832</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">833</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#ac3286b18a2e91b4571b97df96a118e84">yyterminate</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">834</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">835</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;typeMode = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">836</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">837</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">838</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">839</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">840</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*------- module/global/typedef variable ---------------------------------------------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">841</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">842</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SubprogBody,SubprogBodyContains&gt;^{BS}[0-9]*{BS}"end"({BS}{SUBPROG}({BS_}{ID})?)?{BS}/(\n|!|;)</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">843</span><span class="doxyLineContent"><span class="doxyHighlight">                                           </span><span class="doxyHighlightComment">//</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">844</span><span class="doxyLineContent"><span class="doxyHighlight">                                           </span><span class="doxyHighlightComment">// ABSTRACT and specific interfaces are stored</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">845</span><span class="doxyLineContent"><span class="doxyHighlight">                                           </span><span class="doxyHighlightComment">// in a scope of their own, even if multiple</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">846</span><span class="doxyLineContent"><span class="doxyHighlight">                                           </span><span class="doxyHighlightComment">// are group in one INTERFACE/END INTERFACE block.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">847</span><span class="doxyLineContent"><span class="doxyHighlight">                                           </span><span class="doxyHighlightComment">//</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">848</span><span class="doxyLineContent"><span class="doxyHighlight">                                           </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;ifType == <a href="#af1ef2c97e255bd7f21d3b7614b283d9daa33f8bd097d7a6cd1210bed71c5cb937">IF_ABSTRACT</a> || yyextra-&gt;ifType == <a href="#af1ef2c97e255bd7f21d3b7614b283d9da89f0d2424cf9ae9c82a868376ceb29b9">IF_SPECIFIC</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">849</span><span class="doxyLineContent"><span class="doxyHighlight">                                           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">850</span><span class="doxyLineContent"><span class="doxyHighlight">                                             <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a239ee1e47d4722402cd650ae2d0cd59f">endScope</a>(yyscanner,yyextra-&gt;current_root);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">851</span><span class="doxyLineContent"><span class="doxyHighlight">                                             yyextra-&gt;last_entry-&gt;endBodyLine = yyextra-&gt;lineNr - 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">852</span><span class="doxyLineContent"><span class="doxyHighlight">                                           }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">853</span><span class="doxyLineContent"><span class="doxyHighlight">                                           yyextra-&gt;current_root-&gt;endBodyLine = yyextra-&gt;lineNr - 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">854</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">855</span><span class="doxyLineContent"><span class="doxyHighlight">                                           </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a239ee1e47d4722402cd650ae2d0cd59f">endScope</a>(yyscanner,yyextra-&gt;current_root))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">856</span><span class="doxyLineContent"><span class="doxyHighlight">                                           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">857</span><span class="doxyLineContent"><span class="doxyHighlight">                                             <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#ac3286b18a2e91b4571b97df96a118e84">yyterminate</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">858</span><span class="doxyLineContent"><span class="doxyHighlight">                                           }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">859</span><span class="doxyLineContent"><span class="doxyHighlight">                                           yyextra-&gt;subrCurrent.pop_back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">860</span><span class="doxyLineContent"><span class="doxyHighlight">                                           yyextra-&gt;vtype = <a href="#a238692c76adb8cefb158cf28754f52d6a2e626c4ec60ad2b9514c8984aa1eb3ec">V_IGNORE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">861</span><span class="doxyLineContent"><span class="doxyHighlight">                                           <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner) ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">862</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">863</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;BlockData&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">864</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">{ID}</span><span class="doxyHighlight">                                    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">865</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">866</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">867</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start,ModuleBody,TypedefBody,SubprogBody,FEnum&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">868</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">^{BS}{TYPE_SPEC}/{SEPARATE}</span><span class="doxyHighlight">             {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">869</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;last_enum.reset();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">870</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START == FEnum)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">871</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">872</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;argType = </span><span class="doxyHighlightStringLiteral">"@"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// enum marker</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">873</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">874</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">875</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">876</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;argType = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/classes/qcstring/#a8d6ace0deb439b916b9f97f54a6c9cc2">simplifyWhiteSpace</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">877</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">878</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;bodyLine = yyextra-&gt;lineNr + 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">879</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;endBodyLine = yyextra-&gt;lineNr + yyextra-&gt;lineCountPrepass;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">880</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">/* variable declaration starts */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">881</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START == Start)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">882</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">883</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a4ad5866bbc8d144423fe0e3f54ecb0cf">addModule</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">884</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yy_push_state(ModuleBody,yyscanner); </span><span class="doxyHighlightComment">//anon program</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">885</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">886</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(AttributeList,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">887</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">888</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">{EXTERNAL_STMT}/({BS}"::"|{BS_}{ID})</span><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">889</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">/* external can be a "type" or an attribute */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">890</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START == Start)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">891</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">892</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a4ad5866bbc8d144423fe0e3f54ecb0cf">addModule</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">893</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yy_push_state(ModuleBody,yyscanner); </span><span class="doxyHighlightComment">//anon program</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">894</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">895</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tmp = yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">896</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;currentModifiers |= tmp.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">897</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;argType = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/classes/qcstring/#a8d6ace0deb439b916b9f97f54a6c9cc2">simplifyWhiteSpace</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">898</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(AttributeList,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">899</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">900</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">{ATTR_STMT}/{BS_}{ID}</span><span class="doxyHighlight">                   |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">901</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">{ATTR_STMT}/{BS}"::"</span><span class="doxyHighlight">                    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">902</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">/* attribute statement starts */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">903</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr,</span><span class="doxyHighlightStringLiteral">"5=========&gt; Attribute statement: %s\n"</span><span class="doxyHighlight">, yytext));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">904</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START == Start)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">905</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">906</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a4ad5866bbc8d144423fe0e3f54ecb0cf">addModule</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">907</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yy_push_state(ModuleBody,yyscanner); </span><span class="doxyHighlightComment">//anon program</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">908</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">909</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tmp = yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">910</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;currentModifiers |= tmp.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">911</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;argType=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">912</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(YY_START,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">913</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN( AttributeList ) ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">914</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">915</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">"common"</span><span class="doxyHighlight">                                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">916</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START == Start)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">917</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">918</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a4ad5866bbc8d144423fe0e3f54ecb0cf">addModule</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">919</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yy_push_state(ModuleBody,yyscanner); </span><span class="doxyHighlightComment">//anon program</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">920</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">921</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">922</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">{ID}</span><span class="doxyHighlight">                                    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">923</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START == Start)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">924</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">925</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a4ad5866bbc8d144423fe0e3f54ecb0cf">addModule</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">926</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yy_push_state(ModuleBody,yyscanner); </span><span class="doxyHighlightComment">//anon program</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">927</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">928</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">929</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">^{BS}"type"{BS_}"is"/{BT_}</span><span class="doxyHighlight">              {}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">930</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">^{BS}"type"{BS}"="</span><span class="doxyHighlight">                      {}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">931</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">^{BS}"class"{BS_}"is"/{BT_}</span><span class="doxyHighlight">             {}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">932</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">^{BS}"class"{BS_}"default"</span><span class="doxyHighlight">              {}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">933</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">934</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;AttributeList&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">935</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">{COMMA}</span><span class="doxyHighlight">                                 {}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">936</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">{BS}</span><span class="doxyHighlight">                                    {}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">937</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">{LANGUAGE_BIND_SPEC}</span><span class="doxyHighlight">                    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">938</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;currentModifiers |= yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">939</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">940</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">{ATTR_SPEC}.</span><span class="doxyHighlight">                            { </span><span class="doxyHighlightComment">/* update yyextra-&gt;current yyextra-&gt;modifiers when it is an ATTR_SPEC and not a variable name */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">941</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">/* buyyextra-&gt;625519 */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">942</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> chr = yytext[(int)yyleng-1];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">943</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/util-h/#ae320c88a8522836f00095d566529046f">isId</a>(chr))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">944</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">945</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;colNr -= (int)yyleng;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">946</span><span class="doxyLineContent"><span class="doxyHighlight">                                            REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">947</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">948</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">949</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">950</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tmp = yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">951</span><span class="doxyLineContent"><span class="doxyHighlight">                                            tmp = tmp.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(tmp.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() - 1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">952</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;colNr -= 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">953</span><span class="doxyLineContent"><span class="doxyHighlight">                                            unput(yytext[(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)yyleng-1]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">954</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;currentModifiers |= (tmp);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">955</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">956</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">957</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">                                    { </span><span class="doxyHighlightComment">/* end attribute list */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">958</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN( FVariable );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">959</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">960</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">.</span><span class="doxyHighlight">                                       { </span><span class="doxyHighlightComment">/* unknown attribute, consider variable name */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">961</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//cout&lt;&lt;"start variables, unput "&lt;&lt;*yytext&lt;&lt;endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">962</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;colNr -= 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">963</span><span class="doxyLineContent"><span class="doxyHighlight">                                          unput(*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">964</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN( FVariable );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">965</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">966</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">967</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">968</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FVariable&gt;{BS}</span><span class="doxyHighlight">                          {}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">969</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FVariable&gt;{OPERATOR_ID}</span><span class="doxyHighlight">                 { </span><span class="doxyHighlightComment">/* parse operator access statements "public :: operator(==)" */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">970</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">971</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">/* if variable/type/etc is part of a module, mod name is necessary for output */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">972</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">// get surrounding state</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">973</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> currentState = YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">974</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">975</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> outerState = YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">976</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(currentState,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">977</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">( outerState == Start || outerState == ModuleBody )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">978</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">979</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((yyextra-&gt;current_root) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">980</span><span class="doxyLineContent"><span class="doxyHighlight">                                                (yyextra-&gt;current_root-&gt;section.isClass() ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">981</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 yyextra-&gt;current_root-&gt;section.isNamespace()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">982</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">983</span><span class="doxyLineContent"><span class="doxyHighlight">                                              name = yyextra-&gt;current_root-&gt;name + </span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight"> + name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">984</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">985</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">986</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">/* remember attributes for the symbol */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">987</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;modifiers[yyextra-&gt;current_root][name.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()] |= yyextra-&gt;currentModifiers;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">988</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">989</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FVariable&gt;{ID}</span><span class="doxyHighlight">                          { </span><span class="doxyHighlightComment">/* parse variable declaration */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">990</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//cout &lt;&lt; "5=========&gt; got variable: " &lt;&lt; yyextra-&gt;argType &lt;&lt; "::" &lt;&lt; yytext &lt;&lt; endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">991</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">/* work around for bug in QCString.replace (QCString works) */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">992</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">993</span><span class="doxyLineContent"><span class="doxyHighlight">                                          name = name.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">994</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">/* if variable/type/etc is part of a module, mod name is necessary for output */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">995</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((yyextra-&gt;current_root) &amp;&amp; yyextra-&gt;current_root-&gt;section.isNamespace())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">996</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">997</span><span class="doxyLineContent"><span class="doxyHighlight">                                            name = yyextra-&gt;current_root-&gt;name + </span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight"> + name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">998</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">999</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">/* remember attributes for the symbol */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1000</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;modifiers[yyextra-&gt;current_root][name.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()] |= yyextra-&gt;currentModifiers;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1001</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;argName= name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1002</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1003</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;vtype= <a href="#a238692c76adb8cefb158cf28754f52d6a2e626c4ec60ad2b9514c8984aa1eb3ec">V_IGNORE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1004</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;argType.isEmpty() &amp;&amp; !yyextra-&gt;current_root-&gt;section.isFunction())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1005</span><span class="doxyLineContent"><span class="doxyHighlight">                                          { </span><span class="doxyHighlightComment">// new variable entry</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1006</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;vtype = <a href="#a238692c76adb8cefb158cf28754f52d6ab238d5b991ac184d0de8dca5478f5e5c">V_VARIABLE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1007</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;current-&gt;section = EntryType::makeVariable();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1008</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;current-&gt;name = yyextra-&gt;argName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1009</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;current-&gt;type = yyextra-&gt;argType;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1010</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;current-&gt;fileName = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1011</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;current-&gt;bodyLine  = yyextra-&gt;lineNr; </span><span class="doxyHighlightComment">// used for source reference</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1012</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;current-&gt;startLine  = yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1013</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;argType == </span><span class="doxyHighlightStringLiteral">"@"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1014</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1015</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;current_root-&gt;copyToSubEntry(yyextra-&gt;current);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1016</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightComment">// add to the scope surrounding the enum (copy!)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1017</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;last_enum = yyextra-&gt;current;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1018</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;current_root-&gt;parent()-&gt;moveToSubEntryAndRefresh(yyextra-&gt;current);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1019</span><span class="doxyLineContent"><span class="doxyHighlight">                                              <a href="#affe329b2bcd94b04290e03afad9c97c5">initEntry</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1020</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1021</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1022</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1023</span><span class="doxyLineContent"><span class="doxyHighlight">                                              <a href="#a1f86638786429418e4c584f9b98ec3d4">addCurrentEntry</a>(yyscanner,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1024</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1025</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1026</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;argType.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1027</span><span class="doxyLineContent"><span class="doxyHighlight">                                          { </span><span class="doxyHighlightComment">// declaration of parameter list: add type for corr. parameter</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1028</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/structs/argument">Argument</a> *parameter = <a href="#a6c050f3e9b9e8855bad36862ab3173ba">getParameter</a>(yyscanner,yyextra-&gt;argName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1029</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (parameter)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1030</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1031</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;vtype= <a href="#a238692c76adb8cefb158cf28754f52d6abc50e5df37302e97005583c6ae1257a3">V_PARAMETER</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1032</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;argType.isEmpty()) parameter-&gt;<a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">type</a>=yyextra-&gt;argType.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1033</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;docBlock.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1034</span><span class="doxyLineContent"><span class="doxyHighlight">                                              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1035</span><span class="doxyLineContent"><span class="doxyHighlight">                                                <a href="#a6c5f6e8cda9aa291a041f511f3a2329a">subrHandleCommentBlock</a>(yyscanner,yyextra-&gt;docBlock,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1036</span><span class="doxyLineContent"><span class="doxyHighlight">                                              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1037</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1038</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">// save, it may be function return type</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1039</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (parameter)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1040</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1041</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;modifiers[yyextra-&gt;current_root][name.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()].type = yyextra-&gt;argType;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1042</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1043</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1044</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1045</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((yyextra-&gt;current_root-&gt;name.lower() == yyextra-&gt;argName.lower()) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1046</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  (yyextra-&gt;modifiers[yyextra-&gt;current_root-&gt;parent()][yyextra-&gt;current_root-&gt;name.lower().str()].returnName.lower() == yyextra-&gt;argName.lower()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1047</span><span class="doxyLineContent"><span class="doxyHighlight">                                              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1048</span><span class="doxyLineContent"><span class="doxyHighlight">                                                </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> strt = yyextra-&gt;current_root-&gt;type.find(</span><span class="doxyHighlightStringLiteral">"function"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1049</span><span class="doxyLineContent"><span class="doxyHighlight">                                                <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> lft;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1050</span><span class="doxyLineContent"><span class="doxyHighlight">                                                <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> rght;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1051</span><span class="doxyLineContent"><span class="doxyHighlight">                                                </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (strt != -1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1052</span><span class="doxyLineContent"><span class="doxyHighlight">                                                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1053</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  yyextra-&gt;vtype = <a href="#a238692c76adb8cefb158cf28754f52d6a7dd6f98b4ec3c69395dc0873ae146e40">V_RESULT</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1054</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  lft = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1055</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  rght = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1056</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (strt != 0) lft = yyextra-&gt;current_root-&gt;type.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(strt).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1057</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((yyextra-&gt;current_root-&gt;type.length() - strt - strlen(</span><span class="doxyHighlightStringLiteral">"function"</span><span class="doxyHighlight">))!= 0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1058</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1059</span><span class="doxyLineContent"><span class="doxyHighlight">                                                    rght = yyextra-&gt;current_root-&gt;type.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(yyextra-&gt;current_root-&gt;type.length() - strt - (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)strlen(</span><span class="doxyHighlightStringLiteral">"function"</span><span class="doxyHighlight">)).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1060</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1061</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  yyextra-&gt;current_root-&gt;type = lft;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1062</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rght.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() &gt; 0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1063</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1064</span><span class="doxyLineContent"><span class="doxyHighlight">                                                    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;current_root-&gt;type.length() &gt; 0) yyextra-&gt;current_root-&gt;type += </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1065</span><span class="doxyLineContent"><span class="doxyHighlight">                                                    yyextra-&gt;current_root-&gt;type += rght;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1066</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1067</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;argType.stripWhiteSpace().length() &gt; 0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1068</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1069</span><span class="doxyLineContent"><span class="doxyHighlight">                                                    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;current_root-&gt;type.length() &gt; 0) yyextra-&gt;current_root-&gt;type += </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1070</span><span class="doxyLineContent"><span class="doxyHighlight">                                                    yyextra-&gt;current_root-&gt;type += yyextra-&gt;argType.stripWhiteSpace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1071</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1072</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;current_root-&gt;type.length() &gt; 0) yyextra-&gt;current_root-&gt;type += </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1073</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  yyextra-&gt;current_root-&gt;type += </span><span class="doxyHighlightStringLiteral">"function"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1074</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;docBlock.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1075</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1076</span><span class="doxyLineContent"><span class="doxyHighlight">                                                    <a href="#a746c69943bdf7ff71cbd6e6aa44b875d">subrHandleCommentBlockResult</a>(yyscanner,yyextra-&gt;docBlock,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1077</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1078</span><span class="doxyLineContent"><span class="doxyHighlight">                                                }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1079</span><span class="doxyLineContent"><span class="doxyHighlight">                                                </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1080</span><span class="doxyLineContent"><span class="doxyHighlight">                                                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1081</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  yyextra-&gt;current_root-&gt;type += </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> + yyextra-&gt;argType.stripWhiteSpace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1082</span><span class="doxyLineContent"><span class="doxyHighlight">                                                }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1083</span><span class="doxyLineContent"><span class="doxyHighlight">                                                yyextra-&gt;current_root-&gt;type = yyextra-&gt;current_root-&gt;type.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1084</span><span class="doxyLineContent"><span class="doxyHighlight">                                                yyextra-&gt;modifiers[yyextra-&gt;current_root][name.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()].type = yyextra-&gt;current_root-&gt;type;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1085</span><span class="doxyLineContent"><span class="doxyHighlight">                                              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1086</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1087</span><span class="doxyLineContent"><span class="doxyHighlight">                                              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1088</span><span class="doxyLineContent"><span class="doxyHighlight">                                                yyextra-&gt;modifiers[yyextra-&gt;current_root][name.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()].type = yyextra-&gt;argType;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1089</span><span class="doxyLineContent"><span class="doxyHighlight">                                              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1090</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1091</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">// any accumulated doc for argument should be emptied,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1092</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">// because it is handled other way and this doc can be</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1093</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">// unexpectedly passed to the next member.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1094</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;current-&gt;doc.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1095</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;current-&gt;brief.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1096</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1097</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1098</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FVariable&gt;{ARGS}</span><span class="doxyHighlight">                        { </span><span class="doxyHighlightComment">/* dimension of the previous entry. */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1099</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name(yyextra-&gt;argName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1100</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> attr(</span><span class="doxyHighlightStringLiteral">"dimension"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1101</span><span class="doxyLineContent"><span class="doxyHighlight">                                          attr += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1102</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;modifiers[yyextra-&gt;current_root][name.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()] |= attr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1103</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1104</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FVariable&gt;{COMMA}</span><span class="doxyHighlight">                       { </span><span class="doxyHighlightComment">//printf("COMMA: %d&lt;=..&lt;=%d\n", yyextra-&gt;colNr-(int)yyleng, yyextra-&gt;colNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1105</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">// locate !&lt; comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1106</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a9e2f432a75f34796b2cdda24ee7cb9b0">updateVariablePrepassComment</a>(yyscanner,yyextra-&gt;colNr-(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)yyleng, yyextra-&gt;colNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1107</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1108</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FVariable&gt;{BS}"="</span><span class="doxyHighlight">                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1109</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(YY_START,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1110</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;initializer=</span><span class="doxyHighlightStringLiteral">"="</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1111</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;initializerScope = yyextra-&gt;initializerArrayScope = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1112</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(Initialization);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1113</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1114</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FVariable&gt;"\n"</span><span class="doxyHighlight">                          { yyextra-&gt;currentModifiers = <a href="/web-doxygen/docs/api/structs/symbolmodifiers">SymbolModifiers</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1115</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner); </span><span class="doxyHighlightComment">// end variable declaration list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1116</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a146a464d8664e6fe5cd764e866726ac1">newLine</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1117</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1118</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1119</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FVariable&gt;";".*"\n"</span><span class="doxyHighlight">                     { yyextra-&gt;currentModifiers = <a href="/web-doxygen/docs/api/structs/symbolmodifiers">SymbolModifiers</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1120</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner); </span><span class="doxyHighlightComment">// end variable declaration list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1121</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1122</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;inputStringSemi = </span><span class="doxyHighlightStringLiteral">" \n"</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1123</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;lineNr--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1124</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ab536b3c2ec35df931a4fce0dbf2e1420">pushBuffer</a>(yyscanner,yyextra-&gt;inputStringSemi);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1125</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1126</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;";".*"\n"</span><span class="doxyHighlight">                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1127</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START == FVariable) REJECT; </span><span class="doxyHighlightComment">// Just be on the safe side</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1128</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START == String) REJECT; </span><span class="doxyHighlightComment">// ";" ignored in strings</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1129</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START == StrIgnore) REJECT; </span><span class="doxyHighlightComment">// ";" ignored in regular yyextra-&gt;comments</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1130</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START == DocBlock) REJECT; </span><span class="doxyHighlightComment">// ";" ignored in documentation blocks</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1131</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;inputStringSemi = </span><span class="doxyHighlightStringLiteral">" \n"</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1132</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;lineNr--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1133</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ab536b3c2ec35df931a4fce0dbf2e1420">pushBuffer</a>(yyscanner,yyextra-&gt;inputStringSemi);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1134</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1135</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1136</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Initialization,ArrayInitializer&gt;"["</span><span class="doxyHighlight">    |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1137</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Initialization,ArrayInitializer&gt;"(/"</span><span class="doxyHighlight">   { yyextra-&gt;initializer+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1138</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;initializerArrayScope++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1139</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(ArrayInitializer); </span><span class="doxyHighlightComment">// initializer may contain comma</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1140</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1141</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ArrayInitializer&gt;"]"</span><span class="doxyHighlight">                   |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1142</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ArrayInitializer&gt;"/)"</span><span class="doxyHighlight">                  { yyextra-&gt;initializer+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1143</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;initializerArrayScope--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1144</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;initializerArrayScope&lt;=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1145</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1146</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;initializerArrayScope = 0; </span><span class="doxyHighlightComment">// just in case</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1147</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(Initialization);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1148</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1149</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1150</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ArrayInitializer&gt;.</span><span class="doxyHighlight">                     { yyextra-&gt;initializer+=yytext; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1151</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Initialization&gt;"("</span><span class="doxyHighlight">                     { yyextra-&gt;initializerScope++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1152</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;initializer+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1153</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1154</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Initialization&gt;")"</span><span class="doxyHighlight">                     { yyextra-&gt;initializerScope--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1155</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;initializer+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1156</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1157</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Initialization&gt;{COMMA}</span><span class="doxyHighlight">                 { </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;initializerScope == 0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1158</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1159</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a9e2f432a75f34796b2cdda24ee7cb9b0">updateVariablePrepassComment</a>(yyscanner,yyextra-&gt;colNr-(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)yyleng, yyextra-&gt;colNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1160</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner); </span><span class="doxyHighlightComment">// end initialization</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1161</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;last_enum)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1162</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1163</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;last_enum-&gt;initializer.str(yyextra-&gt;initializer.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1164</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1165</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1166</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1167</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;vtype == <a href="#a238692c76adb8cefb158cf28754f52d6ab238d5b991ac184d0de8dca5478f5e5c">V_VARIABLE</a>) yyextra-&gt;last_entry-&gt;initializer.str(yyextra-&gt;initializer.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1168</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1169</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1170</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1171</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1172</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;initializer+=</span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1173</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1174</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1175</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Initialization&gt;"\n"|"!"</span><span class="doxyHighlight">                { </span><span class="doxyHighlightComment">//|</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1176</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner); </span><span class="doxyHighlightComment">// end initialization</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1177</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;last_enum)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1178</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1179</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;last_enum-&gt;initializer.str(yyextra-&gt;initializer.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1180</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1181</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1182</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1183</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;vtype == <a href="#a238692c76adb8cefb158cf28754f52d6ab238d5b991ac184d0de8dca5478f5e5c">V_VARIABLE</a>) yyextra-&gt;last_entry-&gt;initializer.str(yyextra-&gt;initializer.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1184</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1185</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;colNr -= 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1186</span><span class="doxyLineContent"><span class="doxyHighlight">                                          unput(*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1187</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1188</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Initialization&gt;.</span><span class="doxyHighlight">                       { yyextra-&gt;initializer+=yytext; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1189</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1190</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;{BS}"enum"{BS}","{BS}"bind"{BS}"("{BS}"c"{BS}")"{BS}</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1191</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START == Start)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1192</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1193</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a4ad5866bbc8d144423fe0e3f54ecb0cf">addModule</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1194</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yy_push_state(ModuleBody,yyscanner); </span><span class="doxyHighlightComment">//anon program</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1195</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1196</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1197</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(FEnum,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1198</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;protection = yyextra-&gt;defaultProtection;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1199</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;typeProtection = yyextra-&gt;defaultProtection;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1200</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;typeMode = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1201</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1202</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;spec.setStruct(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1203</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;name.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1204</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;args.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1205</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;name.sprintf(</span><span class="doxyHighlightStringLiteral">"@%d"</span><span class="doxyHighlight">,yyextra-&gt;anonCount++);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1206</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1207</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;section = EntryType::makeEnum();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1208</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;fileName  = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1209</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;startLine = yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1210</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;bodyLine  = yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1211</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((yyextra-&gt;current_root) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1212</span><span class="doxyLineContent"><span class="doxyHighlight">                                              (yyextra-&gt;current_root-&gt;section.isClass() ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1213</span><span class="doxyLineContent"><span class="doxyHighlight">                                               yyextra-&gt;current_root-&gt;section.isNamespace()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1214</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1215</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;current-&gt;name = yyextra-&gt;current_root-&gt;name + </span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight"> + yyextra-&gt;current-&gt;name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1216</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1217</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1218</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a1f86638786429418e4c584f9b98ec3d4">addCurrentEntry</a>(yyscanner,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1219</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a1eb414a7080ee6bcef950eba00f991b7">startScope</a>(yyscanner,yyextra-&gt;last_entry.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1220</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN( FEnum ) ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1221</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1222</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FEnum&gt;"end"{BS}"enum"</span><span class="doxyHighlight">                   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1223</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;last_entry-&gt;parent()-&gt;endBodyLine = yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1224</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a239ee1e47d4722402cd650ae2d0cd59f">endScope</a>(yyscanner,yyextra-&gt;current_root))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1225</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1226</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#ac3286b18a2e91b4571b97df96a118e84">yyterminate</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1227</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1228</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;typeMode = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1229</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1230</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1231</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*------ fortran subroutine/function handling ------------------------------------------------------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1232</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*       Start is initial condition                                                                       */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1233</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1234</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start,ModuleBody,SubprogBody,InterfaceBody,ModuleBodyContains,SubprogBodyContains&gt;^{BS}({PREFIX}{BS_})?{TYPE_SPEC}{BS}({PREFIX}{BS_})?/{SUBPROG}{BS_}</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1235</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;ifType == <a href="#af1ef2c97e255bd7f21d3b7614b283d9daa33f8bd097d7a6cd1210bed71c5cb937">IF_ABSTRACT</a> || yyextra-&gt;ifType == <a href="#af1ef2c97e255bd7f21d3b7614b283d9da89f0d2424cf9ae9c82a868376ceb29b9">IF_SPECIFIC</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1236</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1237</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#ac57b965357c0cd3448f8bac617563e29">addInterface</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"$interface$"</span><span class="doxyHighlight">, yyextra-&gt;ifType);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1238</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a1eb414a7080ee6bcef950eba00f991b7">startScope</a>(yyscanner,yyextra-&gt;last_entry.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1239</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1240</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1241</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">// TYPE_SPEC is for old function style function result</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1242</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;type = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1243</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(SubprogPrefix,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1244</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1245</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1246</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SubprogPrefix&gt;{BS}{SUBPROG}{BS_}</span><span class="doxyHighlight">       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1247</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">// Fortran subroutine or function found</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1248</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;vtype = <a href="#a238692c76adb8cefb158cf28754f52d6a2e626c4ec60ad2b9514c8984aa1eb3ec">V_IGNORE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1249</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1250</span><span class="doxyLineContent"><span class="doxyHighlight">                                          result=result.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1251</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#abed27cdfdbc0b2f7e850aff746420010">addSubprogram</a>(yyscanner,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1252</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(Subprog);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1253</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;bodyLine = yyextra-&gt;lineNr + yyextra-&gt;lineCountPrepass + 1; </span><span class="doxyHighlightComment">// we have to be at the line after the definition and we have to take continuation lines into account.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1254</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;startLine = yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1255</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1256</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1257</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start,ModuleBody,SubprogBody,InterfaceBody,ModuleBodyContains,SubprogBodyContains&gt;^{BS}({PREFIX}{BS_})?{SUBPROG}{BS_}</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1258</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">// Fortran subroutine or function found</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1259</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;vtype = <a href="#a238692c76adb8cefb158cf28754f52d6a2e626c4ec60ad2b9514c8984aa1eb3ec">V_IGNORE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1260</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;ifType == <a href="#af1ef2c97e255bd7f21d3b7614b283d9daa33f8bd097d7a6cd1210bed71c5cb937">IF_ABSTRACT</a> || yyextra-&gt;ifType == <a href="#af1ef2c97e255bd7f21d3b7614b283d9da89f0d2424cf9ae9c82a868376ceb29b9">IF_SPECIFIC</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1261</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1262</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#ac57b965357c0cd3448f8bac617563e29">addInterface</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"$interface$"</span><span class="doxyHighlight">, yyextra-&gt;ifType);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1263</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a1eb414a7080ee6bcef950eba00f991b7">startScope</a>(yyscanner,yyextra-&gt;last_entry.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1264</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1265</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1266</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1267</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#abed27cdfdbc0b2f7e850aff746420010">addSubprogram</a>(yyscanner,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1268</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(Subprog,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1269</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;bodyLine = yyextra-&gt;lineNr + yyextra-&gt;lineCountPrepass + 1; </span><span class="doxyHighlightComment">// we have to be at the line after the definition and we have to take continuation lines into account.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1270</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;startLine = yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1271</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1272</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1273</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Subprog&gt;{BS}</span><span class="doxyHighlight">                           {   </span><span class="doxyHighlightComment">/* ignore white space */</span><span class="doxyHighlight">   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1274</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Subprog&gt;{ID}</span><span class="doxyHighlight">                           { yyextra-&gt;current-&gt;name = yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1275</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//cout &lt;&lt; "1a==========&gt; got " &lt;&lt; yyextra-&gt;current-&gt;type &lt;&lt; " " &lt;&lt; yytext &lt;&lt; " " &lt;&lt; yyextra-&gt;lineNr &lt;&lt; endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1276</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> returnName = yyextra-&gt;current-&gt;name.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1277</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">/* if type is part of a module, mod name is necessary for output */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1278</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((yyextra-&gt;current_root) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1279</span><span class="doxyLineContent"><span class="doxyHighlight">                                              (yyextra-&gt;current_root-&gt;section.isClass() ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1280</span><span class="doxyLineContent"><span class="doxyHighlight">                                               yyextra-&gt;current_root-&gt;section.isNamespace()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1281</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1282</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;current-&gt;name= yyextra-&gt;current_root-&gt;name + </span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight"> + yyextra-&gt;current-&gt;name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1283</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1284</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;modifiers[yyextra-&gt;current_root][yyextra-&gt;current-&gt;name.lower().str()].returnName = std::move(returnName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1285</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1286</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;ifType == <a href="#af1ef2c97e255bd7f21d3b7614b283d9daa33f8bd097d7a6cd1210bed71c5cb937">IF_ABSTRACT</a> || yyextra-&gt;ifType == <a href="#af1ef2c97e255bd7f21d3b7614b283d9da89f0d2424cf9ae9c82a868376ceb29b9">IF_SPECIFIC</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1287</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1288</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;current_root-&gt;name = <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1289</span><span class="doxyLineContent"><span class="doxyHighlight">                                                yyextra-&gt;current_root-&gt;name, </span><span class="doxyHighlightStringLiteral">"$interface$"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).lower());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1290</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1291</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1292</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(Parameterlist);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1293</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1294</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Parameterlist&gt;"("</span><span class="doxyHighlight">                      { yyextra-&gt;current-&gt;args = </span><span class="doxyHighlightStringLiteral">"("</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1295</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Parameterlist&gt;")"</span><span class="doxyHighlight">                      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1296</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;args += </span><span class="doxyHighlightStringLiteral">")"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1297</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;args = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a0940360aa6d41fd2496603fc565e3996">removeRedundantWhiteSpace</a>(yyextra-&gt;current-&gt;args);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1298</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a1f86638786429418e4c584f9b98ec3d4">addCurrentEntry</a>(yyscanner,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1299</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a1eb414a7080ee6bcef950eba00f991b7">startScope</a>(yyscanner,yyextra-&gt;last_entry.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1300</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(SubprogBody);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1301</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1302</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Parameterlist&gt;{COMMA}|{BS}</span><span class="doxyHighlight">             { yyextra-&gt;current-&gt;args += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1303</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/commentinprepass">CommentInPrepass</a> *c = <a href="#a58823d73b17b4a3c6b782a7e14904c77">locatePrepassComment</a>(yyscanner,yyextra-&gt;colNr-(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)yyleng, yyextra-&gt;colNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1304</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1305</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1306</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;current-&gt;argList.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1307</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1308</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;current-&gt;argList.back().docs = c-&gt;<a href="/web-doxygen/docs/api/structs/commentinprepass/#a121d4cd80b9102d3c562acbef48952ca">str</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1309</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1310</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1311</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1312</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Parameterlist&gt;{ID}</span><span class="doxyHighlight">                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1313</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//yyextra-&gt;current-&gt;type not yet available</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1314</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> param = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1315</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">// std::cout &lt;&lt; "3=========&gt; got parameter " &lt;&lt; param &lt;&lt; "\n";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1316</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;args += param;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1317</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/structs/argument">Argument</a> arg;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1318</span><span class="doxyLineContent"><span class="doxyHighlight">                                          arg.<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a> = param;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1319</span><span class="doxyLineContent"><span class="doxyHighlight">                                          arg.<a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">type</a> = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1320</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;argList.push_back(arg);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1321</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1322</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Parameterlist&gt;{NOARGS}</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1323</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a146a464d8664e6fe5cd764e866726ac1">newLine</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1324</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//printf("3=========&gt; without parameterlist \n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1325</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a1f86638786429418e4c584f9b98ec3d4">addCurrentEntry</a>(yyscanner,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1326</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a1eb414a7080ee6bcef950eba00f991b7">startScope</a>(yyscanner,yyextra-&gt;last_entry.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1327</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(SubprogBody);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1328</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1329</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SubprogBody&gt;result{BS}\({BS}{ID}</span><span class="doxyHighlight">       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1330</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;functionLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1331</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1332</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result= yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1333</span><span class="doxyLineContent"><span class="doxyHighlight">                                            result= result.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(result.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-result.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"("</span><span class="doxyHighlight">)-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1334</span><span class="doxyLineContent"><span class="doxyHighlight">                                            result= result.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1335</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;modifiers[yyextra-&gt;current_root-&gt;parent()][yyextra-&gt;current_root-&gt;name.lower().str()].returnName = result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1336</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1337</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//cout &lt;&lt; "=====&gt; got result " &lt;&lt;  result &lt;&lt; endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1338</span><span class="doxyLineContent"><span class="doxyHighlight">                                         }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1339</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1340</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*---- documentation yyextra-&gt;comments --------------------------------------------------------------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1341</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1342</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FVariable,SubprogBody,ModuleBody,TypedefBody,TypedefBodyContains&gt;"!&lt;"</span><span class="doxyHighlight">  { </span><span class="doxyHighlightComment">/* backward docu comment */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1343</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;vtype != <a href="#a238692c76adb8cefb158cf28754f52d6a2e626c4ec60ad2b9514c8984aa1eb3ec">V_IGNORE</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1344</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1345</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;current-&gt;docLine  = yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1346</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;docBlockJavaStyle = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1347</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;docBlock.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1348</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;docBlockJavaStyle = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(JAVADOC_AUTOBRIEF);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1349</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a3f8584604e877b6eb570db94e3692a92">startCommentBlock</a>(yyscanner,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1350</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yy_push_state(DocBackLine,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1351</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1352</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1353</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1354</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">/* handle out of place !&lt; comment as a normal comment */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1355</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START == String)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1356</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1357</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;colNr -= (int)yyleng;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1358</span><span class="doxyLineContent"><span class="doxyHighlight">                                              REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1359</span><span class="doxyLineContent"><span class="doxyHighlight">                                            } </span><span class="doxyHighlightComment">// "!" is ignored in strings</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1360</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">// skip comment line (without docu yyextra-&gt;comments "!&gt;" "!&lt;" )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1361</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">/* ignore further "!" and ignore yyextra-&gt;comments in Strings */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1362</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((YY_START != StrIgnore) &amp;&amp; (YY_START != String))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1363</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1364</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yy_push_state(YY_START,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1365</span><span class="doxyLineContent"><span class="doxyHighlight">                                              BEGIN(StrIgnore);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1366</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;debugStr=</span><span class="doxyHighlightStringLiteral">"*!"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1367</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1368</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1369</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1370</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocBackLine&gt;.*</span><span class="doxyHighlight">                         { </span><span class="doxyHighlightComment">// contents of yyextra-&gt;current comment line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1371</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1372</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1373</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocBackLine&gt;"\n"{BS}"!"("&lt;"|"!"+)</span><span class="doxyHighlight">      { </span><span class="doxyHighlightComment">// comment block (next line is also comment line)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1374</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock+=</span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// \n is necessary for lists</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1375</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a146a464d8664e6fe5cd764e866726ac1">newLine</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1376</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1377</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocBackLine&gt;"\n"</span><span class="doxyHighlight">                       { </span><span class="doxyHighlightComment">// comment block ends at the end of this line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1378</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//cout &lt;&lt;"3=========&gt; comment block : "&lt;&lt; yyextra-&gt;docBlock &lt;&lt; endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1379</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;colNr -= 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1380</span><span class="doxyLineContent"><span class="doxyHighlight">                                          unput(*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1381</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;vtype == <a href="#a238692c76adb8cefb158cf28754f52d6ab238d5b991ac184d0de8dca5478f5e5c">V_VARIABLE</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1382</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1383</span><span class="doxyLineContent"><span class="doxyHighlight">                                            std::shared_ptr&lt;Entry&gt; tmp_entry = yyextra-&gt;current;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1384</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">// temporarily switch to the previous entry</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1385</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;last_enum)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1386</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1387</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;current = yyextra-&gt;last_enum;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1388</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1389</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1390</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1391</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;current = yyextra-&gt;last_entry;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1392</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1393</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>(yyscanner,<a href="/web-doxygen/docs/api/files/src/util-cpp/#a2c01679fba857523a2ffe9007352e3bf">stripIndentation</a>(yyextra-&gt;docBlock),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1394</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">// switch back</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1395</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;current = std::move(tmp_entry);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1396</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1397</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;vtype == <a href="#a238692c76adb8cefb158cf28754f52d6abc50e5df37302e97005583c6ae1257a3">V_PARAMETER</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1398</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1399</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a6c5f6e8cda9aa291a041f511f3a2329a">subrHandleCommentBlock</a>(yyscanner,yyextra-&gt;docBlock,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1400</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1401</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;vtype == <a href="#a238692c76adb8cefb158cf28754f52d6a7dd6f98b4ec3c69395dc0873ae146e40">V_RESULT</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1402</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1403</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a746c69943bdf7ff71cbd6e6aa44b875d">subrHandleCommentBlockResult</a>(yyscanner,yyextra-&gt;docBlock,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1404</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1405</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1406</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1407</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1408</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1409</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start,SubprogBody,ModuleBody,TypedefBody,InterfaceBody,ModuleBodyContains,SubprogBodyContains,TypedefBodyContains,FEnum&gt;^{BS}</span><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1410</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;curIndent = <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a2b4acd8f05e7bebf0528ec710692f758">computeIndent</a>(yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1411</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1412</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start,SubprogBody,ModuleBody,TypedefBody,InterfaceBody,ModuleBodyContains,SubprogBodyContains,TypedefBodyContains,FEnum&gt;"!&gt;"</span><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1413</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(YY_START,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1414</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;docLine  = yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1415</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlockJavaStyle = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1416</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START==SubprogBody) yyextra-&gt;docBlockInBody = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1417</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1418</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlockJavaStyle = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(JAVADOC_AUTOBRIEF);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1419</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a3f8584604e877b6eb570db94e3692a92">startCommentBlock</a>(yyscanner,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1420</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(DocBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1421</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//cout &lt;&lt; "start DocBlock " &lt;&lt; endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1422</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1423</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1424</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1425</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocBlock&gt;({CMD}{CMD}){ID}/[^a-z_A-Z0-9]</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// escaped command</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1426</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1427</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1428</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocBlock&gt;{CMD}("f$"|"f["|"f{"|"f(")</span><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1429</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1430</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlockName=&amp;yytext[1];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1431</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;docBlockName.at(1)==</span><span class="doxyHighlightCharLiteral">'['</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1432</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1433</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;docBlockName.at(1)=</span><span class="doxyHighlightCharLiteral">']'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1434</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1435</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;docBlockName.at(1)==</span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1436</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1437</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;docBlockName.at(1)=</span><span class="doxyHighlightCharLiteral">'}'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1438</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1439</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;docBlockName.at(1)==</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1440</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1441</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;docBlockName.at(1)=</span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1442</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1443</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;fencedSize=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1444</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;blockString=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1445</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;blockLineNr=yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1446</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(DocCopyBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1447</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1448</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocBlock&gt;{CMD}"ifile"{B}+"\""[^\n\"]+"\""</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1449</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;fileName = &amp;yytext[6];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1450</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;fileName = yyextra-&gt;fileName.stripWhiteSpace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1451</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;fileName = yyextra-&gt;fileName.mid(1,yyextra-&gt;fileName.length()-2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1452</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1453</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1454</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocBlock&gt;{CMD}"ifile"{B}+{FILEMASK}</span><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1455</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;fileName = &amp;yytext[6];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1456</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;fileName = yyextra-&gt;fileName.stripWhiteSpace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1457</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1458</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1459</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocBlock&gt;{CMD}"iline"{LINENR}/[\n\.]</span><span class="doxyHighlight">   |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1460</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocBlock&gt;{CMD}"iline"{LINENR}{B}</span><span class="doxyHighlight">       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1461</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ok = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1462</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> nr = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(&amp;yytext[6]).<a href="/web-doxygen/docs/api/classes/qcstring/#a100a41fa6ba318b8b2ace175cd20f1eb">toInt</a>(&amp;ok);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1463</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ok)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1464</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1465</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(yyextra-&gt;fileName,yyextra-&gt;lineNr,</span><span class="doxyHighlightStringLiteral">"Invalid line number '{}' for iline command"</span><span class="doxyHighlight">,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1466</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1467</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1468</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1469</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;lineNr = nr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1470</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1471</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1472</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1473</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocBlock&gt;{B}*"&lt;"{PRE}"&gt;"</span><span class="doxyHighlight">               {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1474</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1475</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlockName=</span><span class="doxyHighlightStringLiteral">"&lt;pre&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1476</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;fencedSize=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1477</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;blockString=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1478</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;blockLineNr=yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1479</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(DocCopyBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1480</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1481</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocBlock&gt;{B}*"&lt;"&lt;CODE&gt;"&gt;"</span><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1482</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1483</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlockName=</span><span class="doxyHighlightStringLiteral">"&lt;code&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1484</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;fencedSize=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1485</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;blockString=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1486</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;blockLineNr=yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1487</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(DocCopyBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1488</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1489</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocBlock&gt;{CMD}"startuml"/[^a-z_A-Z0-9\-]</span><span class="doxyHighlight">     { </span><span class="doxyHighlightComment">// verbatim command</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1490</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1491</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlockName=</span><span class="doxyHighlightStringLiteral">"uml"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1492</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;fencedSize=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1493</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;blockString=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1494</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;blockLineNr=yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1495</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(DocCopyBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1496</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1497</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocBlock&gt;{CMD}("verbatim"|"iliteral"|"latexonly"|"htmlonly"|"xmlonly"|"manonly"|"rtfonly"|"docbookonly"|"dot"|"msc"|"code")/[^a-z_A-Z0-9\-]</span><span class="doxyHighlight">     { </span><span class="doxyHighlightComment">// verbatim command</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1498</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1499</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlockName=&amp;yytext[1];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1500</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;fencedSize=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1501</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;blockString=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1502</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;blockLineNr=yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1503</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(DocCopyBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1504</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1505</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocBlock&gt;"~~~"[~]*</span><span class="doxyHighlight">                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1506</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> pat = yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1507</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock += pat;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1508</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlockName=</span><span class="doxyHighlightStringLiteral">"~~~"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1509</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;fencedSize=pat.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1510</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;blockString=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1511</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;blockLineNr=yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1512</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(DocCopyBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1513</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1514</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocBlock&gt;"```"[`]*/(".")?[a-zA-Z0-9#_-]+</span><span class="doxyHighlight"> |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1515</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocBlock&gt;"```"[`]*/"{"[^}]+"}"</span><span class="doxyHighlight"> |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1516</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocBlock&gt;"```"[`]*</span><span class="doxyHighlight">                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1517</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> pat = yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1518</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock += pat;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1519</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlockName=</span><span class="doxyHighlightStringLiteral">"```"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1520</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;fencedSize=pat.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1521</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;blockString=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1522</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;blockLineNr=yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1523</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(DocCopyBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1524</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1525</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocBlock&gt;"\\ilinebr "{BS}</span><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1526</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> indent;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1527</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> extraSpaces = std::max(0,</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(yyleng-9-yyextra-&gt;curIndent-2));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1528</span><span class="doxyLineContent"><span class="doxyHighlight">                                          indent.<a href="/web-doxygen/docs/api/classes/qcstring/#a08003d3e6c9acc46e4d392612ba492f7">fill</a>(</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">,extraSpaces);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1529</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//printf("extraSpaces=%d\n",extraSpaces);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1530</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock += </span><span class="doxyHighlightStringLiteral">"\\ilinebr "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1531</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock += indent;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1532</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1533</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1534</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocBlock&gt;[^@*`~\/\\\n]+</span><span class="doxyHighlight">                { </span><span class="doxyHighlightComment">// any character that isn't special</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1535</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1536</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1537</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocBlock&gt;"\n"{BS}"!"("&gt;"|"!"+)</span><span class="doxyHighlight">         { </span><span class="doxyHighlightComment">// comment block (next line is also comment line)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1538</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock+=</span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// \n is necessary for lists</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1539</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a146a464d8664e6fe5cd764e866726ac1">newLine</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1540</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1541</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocBlock&gt;"\n"</span><span class="doxyHighlight">                          { </span><span class="doxyHighlightComment">// comment block ends at the end of this line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1542</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//cout &lt;&lt;"3=========&gt; comment block : "&lt;&lt; yyextra-&gt;docBlock &lt;&lt; endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1543</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;colNr -= 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1544</span><span class="doxyLineContent"><span class="doxyHighlight">                                          unput(*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1545</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>(yyscanner,<a href="/web-doxygen/docs/api/files/src/util-cpp/#a2c01679fba857523a2ffe9007352e3bf">stripIndentation</a>(yyextra-&gt;docBlock),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1546</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1547</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1548</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocBlock&gt;.</span><span class="doxyHighlight">                             { </span><span class="doxyHighlightComment">// command block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1549</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock += *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1550</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1551</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1552</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/* ---- Copy verbatim sections ------ */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1553</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1554</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocCopyBlock&gt;"&lt;/"{PRE}"&gt;"</span><span class="doxyHighlight">              { </span><span class="doxyHighlightComment">// end of a &lt;pre&gt; block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1555</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1556</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;docBlockName==</span><span class="doxyHighlightStringLiteral">"&lt;pre&gt;"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1557</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1558</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;docBlockName=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1559</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;blockString.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1560</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;blockLineNr=-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1561</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(DocBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1562</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1563</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1564</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocCopyBlock&gt;"&lt;/"{CODE}"&gt;"</span><span class="doxyHighlight">             { </span><span class="doxyHighlightComment">// end of a &lt;code&gt; block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1565</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1566</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;docBlockName==</span><span class="doxyHighlightStringLiteral">"&lt;code&gt;"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1567</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1568</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;docBlockName=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1569</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;blockString.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1570</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;blockLineNr=-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1571</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(DocBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1572</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1573</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1574</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocCopyBlock&gt;[\\@]("f$"|"f]"|"f}"|"f)")</span><span class="doxyHighlight">     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1575</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1576</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;docBlockName==&amp;yytext[1])</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1577</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1578</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;docBlockName=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1579</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;blockString.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1580</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;blockLineNr=-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1581</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(DocBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1582</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1583</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1584</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocCopyBlock&gt;[\\@]("endverbatim"|"endiliteral"|"endlatexonly"|"endhtmlonly"|"endxmlonly"|"enddocbookonly"|"endmanonly"|"endrtfonly"|"enddot"|"endmsc"|"enduml"|"endcode")/[^a-z_A-Z0-9]</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// end of verbatim block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1585</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1586</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (&amp;yytext[4]==yyextra-&gt;docBlockName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1587</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1588</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;docBlockName=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1589</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;blockString.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1590</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;blockLineNr=-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1591</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(DocBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1592</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1593</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1594</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1595</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocCopyBlock&gt;^{B}*{COMM}</span><span class="doxyHighlight">               { </span><span class="doxyHighlightComment">// start of a comment line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1596</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;docBlockName==</span><span class="doxyHighlightStringLiteral">"verbatim"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1597</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1598</span><span class="doxyLineContent"><span class="doxyHighlight">                                            REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1599</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1600</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1601</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1602</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> indent; </span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1603</span><span class="doxyLineContent"><span class="doxyHighlight">                                            indent.<a href="/web-doxygen/docs/api/classes/qcstring/#a08003d3e6c9acc46e4d392612ba492f7">fill</a>(</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a2b4acd8f05e7bebf0528ec710692f758">computeIndent</a>(yytext) + 2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1604</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;docBlock += indent;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1605</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1606</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1607</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocCopyBlock&gt;"~~~"[~]*</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1608</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> pat = yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1609</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock += pat;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1610</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;docBlockName == </span><span class="doxyHighlightStringLiteral">"~~~"</span><span class="doxyHighlight"> &amp;&amp; yyextra-&gt;fencedSize==pat.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1611</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1612</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;blockString.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1613</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;blockLineNr=-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1614</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(DocBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1615</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1616</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1617</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocCopyBlock&gt;"```"[`]*</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1618</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> pat = yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1619</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock += pat;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1620</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;docBlockName == </span><span class="doxyHighlightStringLiteral">"```"</span><span class="doxyHighlight"> &amp;&amp; yyextra-&gt;fencedSize==pat.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1621</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1622</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;blockString.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1623</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;blockLineNr=-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1624</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(DocBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1625</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1626</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1627</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1628</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocCopyBlock&gt;[^\&lt;@/\*\]!`~"\$\\\n]+</span><span class="doxyHighlight">      { </span><span class="doxyHighlightComment">// any character that is not special</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1629</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1630</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1631</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocCopyBlock&gt;\n</span><span class="doxyHighlight">                        { </span><span class="doxyHighlightComment">// newline</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1632</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock += *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1633</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a146a464d8664e6fe5cd764e866726ac1">newLine</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1634</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1635</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocCopyBlock&gt;.</span><span class="doxyHighlight">                         { </span><span class="doxyHighlightComment">// any other character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1636</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock += *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1637</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1638</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1639</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*-----Prototype parsing -------------------------------------------------------------------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1640</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Prototype&gt;{BS}{SUBPROG}{BS_}</span><span class="doxyHighlight">           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1641</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(PrototypeSubprog);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1642</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1643</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Prototype,PrototypeSubprog&gt;{BS}{SCOPENAME}?{BS}{ID}</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1644</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;name = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1645</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;name.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1646</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(PrototypeArgs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1647</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1648</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;PrototypeArgs&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1649</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">"("|")"|","|{BS_}</span><span class="doxyHighlight">                       { yyextra-&gt;current-&gt;args += yytext; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1650</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">{ID}</span><span class="doxyHighlight">                                    { yyextra-&gt;current-&gt;args += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1651</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/structs/argument">Argument</a> a;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1652</span><span class="doxyLineContent"><span class="doxyHighlight">                                          a.<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a> = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1653</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;current-&gt;argList.push_back(a);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1654</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1655</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1656</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1657</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*------------------------------------------------------------------------------------------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1658</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1659</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;"\n"</span><span class="doxyHighlight">                                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1660</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a146a464d8664e6fe5cd764e866726ac1">newLine</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1661</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//if (yyextra-&gt;debugStr.stripWhiteSpace().length() &gt; 0) cout &lt;&lt; "ignored text: " &lt;&lt; yyextra-&gt;debugStr &lt;&lt; " state: " &lt;&lt;YY_START &lt;&lt; endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1662</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;debugStr=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1663</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1664</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1665</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1666</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*---- error: EOF in wrong state --------------------------------------------------------------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1667</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1668</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;&lt;&lt;EOF&gt;&gt;</span><span class="doxyHighlight">                              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1669</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;parsingPrototype)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1670</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1671</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#ac3286b18a2e91b4571b97df96a118e84">yyterminate</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1672</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1673</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( yyextra-&gt;includeStackPtr &lt;= 0 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1674</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1675</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START!=INITIAL &amp;&amp; YY_START!=Start)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1676</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1677</span><span class="doxyLineContent"><span class="doxyHighlight">                                              <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr,</span><span class="doxyHighlightStringLiteral">"==== Error: EOF reached in wrong state (end missing)"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1678</span><span class="doxyLineContent"><span class="doxyHighlight">                                              <a href="#a7b2ca28396c488d5a08ead21731ed2c2">scanner_abort</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1679</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1680</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#ac3286b18a2e91b4571b97df96a118e84">yyterminate</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1681</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1682</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1683</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1684</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a66d8cb63c9460264113152b30a8c4afb">popBuffer</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1685</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1686</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1687</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;{LOG_OPER}</span><span class="doxyHighlight">                           { </span><span class="doxyHighlightComment">// Fortran logical comparison keywords</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1688</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1689</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;.</span><span class="doxyHighlight">                                    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1690</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//yyextra-&gt;debugStr+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1691</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//printf("I:%c\n", *yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1692</span><span class="doxyLineContent"><span class="doxyHighlight">                                        } </span><span class="doxyHighlightComment">// ignore remaining text</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1693</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1694</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/**********************************************************************************/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1695</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/**********************************************************************************/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1696</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/**********************************************************************************/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1697</span><span class="doxyLineContent"><span class="doxyHighlight">%%</span></span></div>

</div>

</div>
</div>

### yyread() {#a5edfc25f0c460f3263fdb340f7a02b03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int yyread (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, char * buf, int max_size)</td>
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



<p>Definition at line 2851 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5edfc25f0c460f3263fdb340f7a02b03">2851</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a5edfc25f0c460f3263fdb340f7a02b03">yyread</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *buf,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> max_size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2852</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2853</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2854</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> c=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2855</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ( c &lt; max_size &amp;&amp; yyextra-&gt;inputString[yyextra-&gt;inputPosition] )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2856</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2857</span><span class="doxyLineContent"><span class="doxyHighlight">    *buf = yyextra-&gt;inputString[yyextra-&gt;inputPosition++] ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2858</span><span class="doxyLineContent"><span class="doxyHighlight">    c++; buf++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2859</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2860</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2861</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### directionParam {#a0ab2ac9fbdd02519455880a47568829b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* directionParam[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
{
   "", "[in]", "[out]", "[in,out]"
}
</div>
</dd>
</dl>

<p>Definition at line 137 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0ab2ac9fbdd02519455880a47568829b">137</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a0ab2ac9fbdd02519455880a47568829b">directionParam</a>[] =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"[in]"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"[out]"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"[in,out]"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


<p>Referenced by <a href="#a6c5f6e8cda9aa291a041f511f3a2329a">subrHandleCommentBlock</a>.</p>

</div>
</div>

### directionStrs {#a70244a0858d0601f2df6435673f01462}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* directionStrs[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
{
   "", "intent(in)", "intent(out)", "intent(inout)"
}
</div>
</dd>
</dl>

<p>Definition at line 133 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a70244a0858d0601f2df6435673f01462">133</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a70244a0858d0601f2df6435673f01462">directionStrs</a>[] =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"intent(in)"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"intent(out)"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"intent(inout)"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


<p>Referenced by <a href="#a521d11026f20bc253b154ffec71d4748">applyModifiers</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DBG\_CTX {#a234e2efe67eececd88b140b46ea37463}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DBG_CTX(x)&nbsp;&nbsp;&nbsp;do { } while(0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a234e2efe67eececd88b140b46ea37463">81</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DBG_CTX(x) do { } while(0)</span></span></div>

</div>


<p>Referenced by <a href="#a4ad5866bbc8d144423fe0e3f54ecb0cf">addModule</a>, <a href="#abed27cdfdbc0b2f7e850aff746420010">addSubprogram</a> and <a href="#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>.</p>

</div>
</div>

### INVALID\_ENTRY {#a1dfbc2208b3f32fc3d8dca63bd941c08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INVALID_ENTRY&nbsp;&nbsp;&nbsp;((<a href="/web-doxygen/docs/api/classes/entry">Entry</a>*)0x8)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 264 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1dfbc2208b3f32fc3d8dca63bd941c08">264</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define INVALID_ENTRY ((Entry*)0x8)</span></span></div>

</div>


<p>Referenced by <a href="#a5c191151631efdf0d25fc7967f6b0434">endScope</a> and <a href="#a4481d3eae9a04af883d868f23c4cbffc">parseMain</a>.</p>

</div>
</div>

### YY\_INPUT {#aacfdca45fa4beb8b06172525a53c424a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define YY_INPUT(buf, result, max_size)&nbsp;&nbsp;&nbsp;result=<a href="/web-doxygen/docs/api/files/src/code-l/#a5edfc25f0c460f3263fdb340f7a02b03">yyread</a>(yyscanner,buf,max_size);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 258 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aacfdca45fa4beb8b06172525a53c424a">258</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define YY_INPUT(buf,result,max_size) result=yyread(yyscanner,buf,max_size);</span></span></div>

</div>

</div>
</div>

### YY\_NO\_INPUT {#a85523a0c7d95c059d251b4e9829947aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define YY_NO_INPUT&nbsp;&nbsp;&nbsp;1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a85523a0c7d95c059d251b4e9829947aa">83</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define YY_NO_INPUT 1</span></span></div>

</div>

</div>
</div>

### YY\_NO\_UNISTD\_H {#ae78ac56cd1f29572e967ed7636952d15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define YY_NO_UNISTD_H&nbsp;&nbsp;&nbsp;1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae78ac56cd1f29572e967ed7636952d15">84</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define YY_NO_UNISTD_H 1</span></span></div>

</div>

</div>
</div>

### YY\_TYPEDEF\_YY\_SCANNER\_T {#a5d5508008cac8fb66fca3baa4e9b6584}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define YY_TYPEDEF_YY_SCANNER_T</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5d5508008cac8fb66fca3baa4e9b6584">48</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define YY_TYPEDEF_YY_SCANNER_T</span></span></div>

</div>

</div>
</div>

### YY\_USER\_ACTION {#a6198b2fcf96178b24ad4efff2a3debb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define YY_USER_ACTION&nbsp;&nbsp;&nbsp;yyextra-&gt;colNr+=(int)yyleng;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 263 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6198b2fcf96178b24ad4efff2a3debb0">263</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define YY_USER_ACTION yyextra-&gt;colNr+=(int)yyleng;</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
