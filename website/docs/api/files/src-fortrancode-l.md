---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/fortrancode-l
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `fortrancode.l` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;stdint.h&gt;
#include &lt;stdio.h&gt;
#include &lt;assert.h&gt;
#include &lt;ctype.h&gt;
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/defargs-h">defargs.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/classlist-h">classlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/tooltip-h">tooltip.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/fortrancode-h">fortrancode.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/fortranscanner-h">fortranscanner.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/containers-h">containers.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-lex-h">doxygen_lex.h</a>"
#include "fortrancode.l.h"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/useentry">UseEntry</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>data of an use-statement <a href="/web-doxygen/docs/api/classes/useentry/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/usemap">UseMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>module name -&gt; list of ONLY/remote entries (module name = name of the module, which can be accessed via use-directive) <a href="/web-doxygen/docs/api/classes/usemap/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/scope">Scope</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Contains names of used modules and names of local variables. <a href="/web-doxygen/docs/api/classes/scope/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/fortrancodeyy-state">fortrancodeYY_state</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/fortrancodeparser/private">Private</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a504e4bc3498a0866fed7ca24f0b6140c">getFortranNamespaceDefs</a> (const QCString &amp;mname, NamespaceDef *&amp;cd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>searches for definition of a module (Namespace) <a href="#a504e4bc3498a0866fed7ca24f0b6140c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22ca0992a85719c162c23eb696be6608">getFortranTypeDefs</a> (const QCString &amp;tname, const QCString &amp;moduleName, ClassDef *&amp;cd, const UseMap &amp;useMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>searches for definition of a type <a href="#a22ca0992a85719c162c23eb696be6608">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a> (yyscan_t yyscanner, const char *s, bool specialComment=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a> (yyscan_t yyscanner, bool specialComment=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbfcafb48c794e6885763cd94da51375">setCurrentDoc</a> (yyscan_t yyscanner, const QCString &amp;anchor)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63736112eb4c63a80176566049bbea24">addToSearchIndex</a> (yyscan_t yyscanner, const QCString &amp;text)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47b0cd13a509f44e1a1032cbf4ad69ed">startCodeLine</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22b46d1ae6472d2565e3bd435f982d16">endCodeLine</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b060f853a2545afc385b18ecc734473">nextCodeLine</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a> (yyscan_t yyscanner, const QCString &amp;text)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefd632b8f888c312d4d67dffa15f5669">writeMultiLineCodeLink</a> (yyscan_t yyscanner, OutputCodeList &amp;ol, Definition *d, const QCString &amp;text)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2111383c92568a7b28fe96bf69a9f4d2">getGenericProcedureLink</a> (yyscan_t,const ClassDef *, const QCString &amp;, OutputCodeList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>gets the link to a generic procedure which depends not on the name, but on the parameter list <a href="#a2111383c92568a7b28fe96bf69a9f4d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac240a5eb77b55528937ec68a24cf4f46">getLink</a> (yyscan_t yyscanner, const UseMap &amp;useMap, const QCString &amp;memberText, OutputCodeList &amp;ol, const QCString &amp;text)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfe5e615942afd900cff9f219424d5a5">generateLink</a> (yyscan_t yyscanner, OutputCodeList &amp;ol, const QCString &amp;lname)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a239f1eec84677be9196b0c6a9179bdd0">generateLink</a> (yyscan_t yyscanner, OutputCodeList &amp;ol, const char *lname)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a635b111e9953d65f6353bf0d7eb9fb1f">countLines</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1eb414a7080ee6bcef950eba00f991b7">startScope</a> (yyscan_t yyscanner)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>start scope <a href="#a1eb414a7080ee6bcef950eba00f991b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a239ee1e47d4722402cd650ae2d0cd59f">endScope</a> (yyscan_t yyscanner)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>end scope <a href="#a239ee1e47d4722402cd650ae2d0cd59f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e24461e4a28d3b200f27ade4dbc7a53">addUse</a> (yyscan_t yyscanner, const QCString &amp;moduleName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad36e56c8bfd19605777cd5511cd13cbb">addLocalVar</a> (yyscan_t yyscanner, const QCString &amp;varName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3d64c285d12ea68252876251ea0fc2d">getFortranDefs</a> (yyscan_t yyscanner, const QCString &amp;memberName, const QCString &amp;moduleName, const UseMap &amp;useMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>searches for definition of function memberName <a href="#aa3d64c285d12ea68252876251ea0fc2d">More...</a></p>
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
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afce5972b6b52acbb18c0d79b1f0d4433">codeFolding</a> (yyscan_t yyscanner, const Definition *d)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a738fe0f13b025379789e42ee04dcc54f">checkContLines</a> (yyscan_t yyscanner, const char *s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb8ae57c27d4106567da9d9317c2fe0b">parseFortranCode</a> (OutputCodeList &amp;, const char *, const QCString &amp;, bool, const char *, const FileDef *, int, int, bool, const MemberDef *, bool, const Definition *, bool, FortranFormat)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0517027b61f63c8a563733d6e813ad1">yy_old_start</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66a71125f0f01a2a8d1a3608807695fa">yy_my_start</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc3fff33a8db22a36f05baec1001a010">yy_end</a> = 1</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3eedc6d2e3e4c9b2bacd0f1ebeab98a">YY_NO_TOP_STATE</a>&nbsp;&nbsp;&nbsp;1</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6198b2fcf96178b24ad4efff2a3debb0">YY_USER_ACTION</a>&nbsp;&nbsp;&nbsp;{<a href="#ab0517027b61f63c8a563733d6e813ad1">yy_old_start</a> = <a href="#a66a71125f0f01a2a8d1a3608807695fa">yy_my_start</a>; <a href="#a66a71125f0f01a2a8d1a3608807695fa">yy_my_start</a> = <a href="#adc3fff33a8db22a36f05baec1001a010">yy_end</a>; <a href="#adc3fff33a8db22a36f05baec1001a010">yy_end</a> += static_cast&lt;int&gt;(yyleng);}</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a0fdbfa8e6dc0e59c2015a0f1e663c2">YY_FTN_RESET</a>&nbsp;&nbsp;&nbsp;{<a href="#ab0517027b61f63c8a563733d6e813ad1">yy_old_start</a> = 0; <a href="#a66a71125f0f01a2a8d1a3608807695fa">yy_my_start</a> = 0; <a href="#adc3fff33a8db22a36f05baec1001a010">yy_end</a> = 1;}</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a633f0b53ce61259dee93c2398f1674f0">YY_FTN_REJECT</a>&nbsp;&nbsp;&nbsp;{<a href="#adc3fff33a8db22a36f05baec1001a010">yy_end</a> = <a href="#a66a71125f0f01a2a8d1a3608807695fa">yy_my_start</a>; <a href="#a66a71125f0f01a2a8d1a3608807695fa">yy_my_start</a> = <a href="#ab0517027b61f63c8a563733d6e813ad1">yy_old_start</a>; REJECT;}</td>
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



<p>Definition at line 39 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9484188abbc459dafcbd4c96425fa70b">39</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">typedef</span><span class="doxyHighlight"> yyguts_t *<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a>;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### addLocalVar() {#ad36e56c8bfd19605777cd5511cd13cbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addLocalVar (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; varName)</td>
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



<p>Definition at line 1403 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad36e56c8bfd19605777cd5511cd13cbb">1403</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad36e56c8bfd19605777cd5511cd13cbb">addLocalVar</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;varName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1404</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1405</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1406</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;scopeStack.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1407</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1408</span><span class="doxyLineContent"><span class="doxyHighlight">    std::string lowVarName = varName.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1409</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;scopeStack.back().localVars.insert(lowVarName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1410</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;isExternal) yyextra-&gt;scopeStack.back().externalVars.insert(lowVarName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1411</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1412</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>

</div>
</div>

### addToSearchIndex() {#a63736112eb4c63a80176566049bbea24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addToSearchIndex (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
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



<p>Definition at line 901 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a63736112eb4c63a80176566049bbea24">901</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/code-l/#a63736112eb4c63a80176566049bbea24">addToSearchIndex</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> </span><span class="doxyHighlightComment">/*yyscanner*/</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">902</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">903</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/doxygen/#ae3d8cc749e66634e3902def93f814d07">Doxygen::searchIndex</a>.enabled())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">904</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">905</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/doxygen/#ae3d8cc749e66634e3902def93f814d07">Doxygen::searchIndex</a>.addWord(text,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">906</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">907</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="/web-doxygen/docs/api/classes/doxygen/#ae3d8cc749e66634e3902def93f814d07">Doxygen::searchIndex</a>.</p>

</div>
</div>

### addUse() {#a8e24461e4a28d3b200f27ade4dbc7a53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addUse (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; moduleName)</td>
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



<p>Definition at line 1396 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8e24461e4a28d3b200f27ade4dbc7a53">1396</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8e24461e4a28d3b200f27ade4dbc7a53">addUse</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;moduleName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1397</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1398</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1399</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;scopeStack.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1400</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;scopeStack.back().<a href="/web-doxygen/docs/api/classes/scope/#ae1f8159aa48746bb58e6724ff4a36619">useNames</a>.push_back(moduleName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1401</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/scope/#ae1f8159aa48746bb58e6724ff4a36619">Scope::useNames</a>.</p>

</div>
</div>

### checkContLines() {#a738fe0f13b025379789e42ee04dcc54f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void checkContLines (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const char * s)</td>
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



<p>Definition at line 1417 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a738fe0f13b025379789e42ee04dcc54f">1417</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a738fe0f13b025379789e42ee04dcc54f">checkContLines</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1418</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1419</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1420</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> numLines = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1421</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1422</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p = s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1423</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1424</span><span class="doxyLineContent"><span class="doxyHighlight">  numLines = 2; </span><span class="doxyHighlightComment">// one for element 0, one in case no \n at end</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1425</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1426</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1427</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*p == </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) numLines++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1428</span><span class="doxyLineContent"><span class="doxyHighlight">    p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1429</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1430</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1431</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;hasContLine = (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> *) malloc((numLines) * </span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1432</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (i = 0; i &lt; numLines; i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1433</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1434</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;hasContLine[i] = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1435</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1436</span><span class="doxyLineContent"><span class="doxyHighlight">  p = <a href="/web-doxygen/docs/api/files/src/fortranscanner-h/#a3318a36567de3b1f36059e387a801863">prepassFixedForm</a>(s, yyextra-&gt;hasContLine,yyextra-&gt;fixedCommentAfter);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1437</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;hasContLine[0] = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1438</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/fortranscanner-h/#a3318a36567de3b1f36059e387a801863">prepassFixedForm</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/fortrancodeparser/#ab7216957ad8abace8578d47edd8b578d">FortranCodeParser::parseCode</a>.</p>

</div>
</div>

### codeFolding() {#afce5972b6b52acbb18c0d79b1f0d4433}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void codeFolding (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d)</td>
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



<p>Definition at line 909 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afce5972b6b52acbb18c0d79b1f0d4433">909</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/code-l/#afce5972b6b52acbb18c0d79b1f0d4433">codeFolding</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">910</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">911</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(HTML_CODE_FOLDING))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">912</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">913</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">914</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!yyextra-&gt;foldStack.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">915</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">916</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *dd = yyextra-&gt;foldStack.back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">917</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (dd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0b5313ad11f50b2d056fc62d81db0433">getEndBodyLine</a>()+1==yyextra-&gt;yyLineNr) </span><span class="doxyHighlightComment">// 1 to close the section after the end of the body</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">918</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">919</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;code-&gt;endFold();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">920</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("%d:   end codeFolding for %s [%d..%d]\n",yyextra-&gt;yyLineNr,qPrint(dd-&gt;name()),dd-&gt;getStartDefLine(),dd-&gt;getEndBodyLine());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">921</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;foldStack.pop_back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">922</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">923</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">924</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">925</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">926</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">927</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">928</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">929</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">930</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startLine = d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a9d3adad7a22b7ed0ce8903571d370140">getStartDefLine</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">931</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> endLine   = d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0b5313ad11f50b2d056fc62d81db0433">getEndBodyLine</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">932</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (endLine!=-1 &amp;&amp; startLine!=endLine &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">933</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// since the end of a section is closed after the last line, we need to avoid starting a</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">934</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// new section if the previous section ends at the same line, i.e. something like</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">935</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// struct X {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">936</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// ...</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">937</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// }; struct S {  &lt;- start of S and end of X at the same line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">938</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// ...</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">939</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">940</span><span class="doxyLineContent"><span class="doxyHighlight">          (yyextra-&gt;foldStack.empty() || yyextra-&gt;foldStack.back()-&gt;getEndBodyLine()!=startLine))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">941</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">942</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("%d: start codeFolding for %s [%d..%d]\n",yyextra-&gt;yyLineNr,qPrint(d-&gt;name()),d-&gt;getStartDefLine(),d-&gt;getEndBodyLine());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">943</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;code-&gt;startFold(yyextra-&gt;yyLineNr,</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">944</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;foldStack.push_back(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">945</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">946</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">947</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">948</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/classes/definition/#a0b5313ad11f50b2d056fc62d81db0433">Definition::getEndBodyLine</a> and <a href="/web-doxygen/docs/api/classes/definition/#a9d3adad7a22b7ed0ce8903571d370140">Definition::getStartDefLine</a>.</p>

</div>
</div>

### codifyLines() {#a48a235cba4770aa3c63e252304f8b10f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void codifyLines (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
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




<p>write a code fragment 'text' that may span multiple lines, inserting line numbers for each line.</p>


<p>Definition at line 1035 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a48a235cba4770aa3c63e252304f8b10f">1035</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1036</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1037</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1038</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("codifyLines(%d,\"%s\")\n",yyextra-&gt;yyLineNr,text);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1039</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (text.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1040</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=text.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),*sp=p;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1041</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1042</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> done=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1043</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!done)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1044</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1045</span><span class="doxyLineContent"><span class="doxyHighlight">    sp=p;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1046</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++) &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) { }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1047</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1048</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1049</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;yyLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1050</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> l = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(p-sp-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1051</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string tmp(sp,l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1052</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;code-&gt;codify(tmp.c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1053</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/code-l/#a3b060f853a2545afc385b18ecc734473">nextCodeLine</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1054</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1055</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1056</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1057</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;code-&gt;codify(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(sp));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1058</span><span class="doxyLineContent"><span class="doxyHighlight">      done=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1059</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1060</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1061</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a3b060f853a2545afc385b18ecc734473">nextCodeLine</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### countLines() {#a635b111e9953d65f6353bf0d7eb9fb1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int countLines (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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




<p>counts the number of lines in the input</p>


<p>Definition at line 1349 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a635b111e9953d65f6353bf0d7eb9fb1f">1349</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/code-l/#a635b111e9953d65f6353bf0d7eb9fb1f">countLines</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1350</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1351</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1352</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=yyextra-&gt;inputString;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1353</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1354</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> count=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1355</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1356</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1357</span><span class="doxyLineContent"><span class="doxyHighlight">    p++ ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1358</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) count++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1359</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1360</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (p&gt;yyextra-&gt;inputString &amp;&amp; *(p-1)!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1361</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightComment">// last line does not end with a \n, so we add an extra</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1362</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// line and explicitly terminate the line after parsing.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1363</span><span class="doxyLineContent"><span class="doxyHighlight">    count++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1364</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1365</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> count;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1366</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### endCodeLine() {#a22b46d1ae6472d2565e3bd435f982d16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void endCodeLine (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 1012 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a22b46d1ae6472d2565e3bd435f982d16">1012</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/code-l/#a22b46d1ae6472d2565e3bd435f982d16">endCodeLine</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1013</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1014</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1015</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1016</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;code-&gt;endCodeLine();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1017</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;insideCodeLine=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1018</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>.</p>

</div>
</div>

### endFontClass() {#ab499eb5a5a3c5a6d6e40323a1d10747f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void endFontClass (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, bool specialComment=false)</td>
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



<p>Definition at line 853 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab499eb5a5a3c5a6d6e40323a1d10747f">853</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> specialComment)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">854</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">855</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">856</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;currentFontClass)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">857</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">858</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;code-&gt;endFontClass();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">859</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;currentFontClass=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">860</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">861</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (specialComment &amp;&amp; yyextra-&gt;insideSpecialComment)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">862</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">863</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;code-&gt;endSpecialComment();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">864</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;insideSpecialComment=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">865</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">866</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### endScope() {#a239ee1e47d4722402cd650ae2d0cd59f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void endScope (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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

<p>end scope</p>

<p>Definition at line 1378 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a239ee1e47d4722402cd650ae2d0cd59f">1378</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a239ee1e47d4722402cd650ae2d0cd59f">endScope</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1379</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1380</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1381</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr,</span><span class="doxyHighlightStringLiteral">"===&gt; endScope %s"</span><span class="doxyHighlight">,yytext));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1382</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;scopeStack.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1383</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1384</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr,</span><span class="doxyHighlightStringLiteral">"WARNING: fortrancode.l: stack empty!\n"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1385</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1386</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1387</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1388</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/scope">Scope</a> &amp;scope = yyextra-&gt;scopeStack.back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1389</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> ( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;name : scope.<a href="/web-doxygen/docs/api/classes/scope/#ae1f8159aa48746bb58e6724ff4a36619">useNames</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1390</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1391</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;useMembers.erase(name.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1392</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1393</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;scopeStack.pop_back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1394</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a> and <a href="/web-doxygen/docs/api/classes/scope/#ae1f8159aa48746bb58e6724ff4a36619">Scope::useNames</a>.</p>

</div>
</div>

### generateLink() {#adfe5e615942afd900cff9f219424d5a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void generateLink (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; lname)</td>
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



<p>Definition at line 1300 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adfe5e615942afd900cff9f219424d5a5">1300</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#adfe5e615942afd900cff9f219424d5a5">generateLink</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;ol, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;lname)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1301</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1302</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1303</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1304</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *nsd=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1305</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name = lname;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1306</span><span class="doxyLineContent"><span class="doxyHighlight">  name = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a0940360aa6d41fd2496603fc565e3996">removeRedundantWhiteSpace</a>(name.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1307</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1308</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check if lowercase lname is a linkable type or interface</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1309</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( (<a href="#a22ca0992a85719c162c23eb696be6608">getFortranTypeDefs</a>(name, yyextra-&gt;currentModule, cd, yyextra-&gt;useMembers)) &amp;&amp; cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">isLinkable</a>() )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1310</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1311</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( (cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ae8ba915e00984129bcbbaa4efff48b00">compoundType</a>() == <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a5261cde79065c9b6af97195e43e8073b">ClassDef::Class</a>) &amp;&amp; </span><span class="doxyHighlightComment">// was  Entry::INTERFACE_SEC) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1312</span><span class="doxyLineContent"><span class="doxyHighlight">         (<a href="#a2111383c92568a7b28fe96bf69a9f4d2">getGenericProcedureLink</a>(yyscanner, cd, name, ol)) )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1313</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1314</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//cout &lt;&lt; "=== generic procedure resolved" &lt;&lt; endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1315</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1316</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1317</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightComment">// write type or interface link</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1318</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/code-l/#a211386867df5b0f5b03dabbec2c18a6a">writeMultiLineCodeLink</a>(yyscanner, ol,cd,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1319</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/code-l/#a63736112eb4c63a80176566049bbea24">addToSearchIndex</a>(yyscanner, name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1320</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1321</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1322</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check for module</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1323</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( (<a href="#a504e4bc3498a0866fed7ca24f0b6140c">getFortranNamespaceDefs</a>(name, nsd)) &amp;&amp; nsd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">isLinkable</a>() )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1324</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightComment">// write module link</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1325</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/code-l/#a211386867df5b0f5b03dabbec2c18a6a">writeMultiLineCodeLink</a>(yyscanner,ol,nsd,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1326</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/code-l/#a63736112eb4c63a80176566049bbea24">addToSearchIndex</a>(yyscanner,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1327</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1328</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check for function/variable</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1329</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/code-l/#aa48141b866dee2454e4290a3c34d36bb">getLink</a>(yyscanner,yyextra-&gt;useMembers, name, ol, name))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1330</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1331</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//cout &lt;&lt; "=== found link for lowercase " &lt;&lt; lname &lt;&lt; endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1332</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1333</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1334</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1335</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// nothing found, just write out the word</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1336</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//startFontClass("charliteral"); //test</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1337</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1338</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//endFontClass(yyscanner); //test</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1339</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/code-l/#a63736112eb4c63a80176566049bbea24">addToSearchIndex</a>(yyscanner,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1340</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1341</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/code-l/#a63736112eb4c63a80176566049bbea24">addToSearchIndex</a>, <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a5261cde79065c9b6af97195e43e8073b">ClassDef::Class</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>, <a href="/web-doxygen/docs/api/classes/classdef/#ae8ba915e00984129bcbbaa4efff48b00">ClassDef::compoundType</a>, <a href="#a504e4bc3498a0866fed7ca24f0b6140c">getFortranNamespaceDefs</a>, <a href="#a22ca0992a85719c162c23eb696be6608">getFortranTypeDefs</a>, <a href="#a2111383c92568a7b28fe96bf69a9f4d2">getGenericProcedureLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#aa48141b866dee2454e4290a3c34d36bb">getLink</a>, <a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">Definition::isLinkable</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a0940360aa6d41fd2496603fc565e3996">removeRedundantWhiteSpace</a> and <a href="/web-doxygen/docs/api/files/src/code-l/#a211386867df5b0f5b03dabbec2c18a6a">writeMultiLineCodeLink</a>.</p>


<p>Referenced by <a href="#a239f1eec84677be9196b0c6a9179bdd0">generateLink</a> and <a href="/web-doxygen/docs/api/structs/ftvhelp/private/#a0bed14c4bee93963b64e37bb6532aad8">FTVHelp::Private::generateTree</a>.</p>

</div>
</div>

### generateLink() {#a239f1eec84677be9196b0c6a9179bdd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void generateLink (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; ol, const char * lname)</td>
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



<p>Definition at line 1343 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a239f1eec84677be9196b0c6a9179bdd0">1343</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#adfe5e615942afd900cff9f219424d5a5">generateLink</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;ol, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *lname)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1344</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1345</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adfe5e615942afd900cff9f219424d5a5">generateLink</a>(yyscanner,ol,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(lname));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1346</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#adfe5e615942afd900cff9f219424d5a5">generateLink</a>.</p>

</div>
</div>

### getFortranDefs() {#aa3d64c285d12ea68252876251ea0fc2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemberDef * getFortranDefs (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; memberName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; moduleName, const <a href="/web-doxygen/docs/api/classes/usemap">UseMap</a> &amp; useMap)</td>
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

<p>searches for definition of function memberName</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">yyscanner</td>
<td class="doxyParamItemDescription"><p>the scanner data to be used</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">memberName</td>
<td class="doxyParamItemDescription"><p>the name of the function/variable</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">moduleName</td>
<td class="doxyParamItemDescription"><p>name of enclosing module or null, if global entry</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">useMap</td>
<td class="doxyParamItemDescription"><p>map of data of USE-statement</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> pointer, if found, or nullptr otherwise</p></dd>
</dl>


<p>Definition at line 1170 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa3d64c285d12ea68252876251ea0fc2d">1170</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *<a href="#aa3d64c285d12ea68252876251ea0fc2d">getFortranDefs</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;memberName, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;moduleName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1171</span><span class="doxyLineContent"><span class="doxyHighlight">                                 </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/usemap">UseMap</a> &amp;useMap)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1172</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1173</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1174</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *potentialMd = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1175</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (memberName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">/* empty name =&gt; nothing to link */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1176</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1177</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// look in local variables</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1178</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = yyextra-&gt;scopeStack.rbegin(); it!=yyextra-&gt;scopeStack.rend(); ++it)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1179</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1180</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/scope">Scope</a> &amp;scope = *it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1181</span><span class="doxyLineContent"><span class="doxyHighlight">    std::string lowMemName = memberName.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1182</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (scope.<a href="/web-doxygen/docs/api/classes/scope/#aa482827cfef7e8fc106ac71e3abb1398">localVars</a>   .find(lowMemName)!=std::end(scope.<a href="/web-doxygen/docs/api/classes/scope/#aa482827cfef7e8fc106ac71e3abb1398">localVars</a>)     &amp;&amp;  </span><span class="doxyHighlightComment">// local var</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1183</span><span class="doxyLineContent"><span class="doxyHighlight">        scope.<a href="/web-doxygen/docs/api/classes/scope/#a5d33523531c274635347daf1d40ddc9a">externalVars</a>.find(lowMemName)==std::end(scope.<a href="/web-doxygen/docs/api/classes/scope/#a5d33523531c274635347daf1d40ddc9a">externalVars</a>))     </span><span class="doxyHighlightComment">// and not external</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1184</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1185</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1186</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1187</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1188</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1189</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// search for function</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1190</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/membername">MemberName</a> *mn = <a href="/web-doxygen/docs/api/classes/doxygen/#a6c68c48d8e3dac65c86b39ab838a5f9e">Doxygen::functionNameLinkedMap</a>-&gt;find(memberName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1191</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!mn)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1192</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1193</span><span class="doxyLineContent"><span class="doxyHighlight">    mn = <a href="/web-doxygen/docs/api/classes/doxygen/#adc3a52f780a8b6a6f0653e357b09af6b">Doxygen::memberNameLinkedMap</a>-&gt;find(memberName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1194</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1195</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1196</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mn) </span><span class="doxyHighlightComment">// name is known</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1197</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1198</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// all found functions with given name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1199</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;md : *mn)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1200</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1201</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a>  *fd=md-&gt;getFileDef();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1202</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *gd=md-&gt;getGroupDef();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1203</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd=md-&gt;getClassDef();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1204</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1205</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//cout &lt;&lt; "found link with same name: " &lt;&lt; fd-&gt;fileName() &lt;&lt; "  " &lt;&lt;  memberName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1206</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//if (md-&gt;getNamespaceDef() != 0) cout &lt;&lt; " in namespace " &lt;&lt; md-&gt;getNamespaceDef()-&gt;name();cout &lt;&lt; endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1207</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1208</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((gd &amp;&amp; gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">isLinkable</a>()) || (fd &amp;&amp; fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">isLinkable</a>()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1209</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1210</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *nspace= md-&gt;getNamespaceDef();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1211</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1212</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nspace == </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1213</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightComment">// found function in global scope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1214</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd == </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1215</span><span class="doxyLineContent"><span class="doxyHighlight">          { </span><span class="doxyHighlightComment">// Skip if bound to type</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1216</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md.get()-&gt;getFileDef() == yyextra-&gt;sourceFileDef) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> md.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1217</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!potentialMd) potentialMd = md.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1218</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1219</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1220</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (moduleName == nspace-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1221</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightComment">// found in local scope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1222</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> md.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1223</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1224</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1225</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightComment">// else search in used modules</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1226</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> usedModuleName= nspace-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1227</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> use_it = useMap.find(usedModuleName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1228</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (use_it!=useMap.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1229</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1230</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/useentry">UseEntry</a> &amp;ue = use_it-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1231</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// check if only-list exists and if current entry exists is this list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1232</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ue.<a href="/web-doxygen/docs/api/classes/useentry/#a68218c0795c329b96c69d1bf3825f6bc">onlyNames</a>.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1233</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1234</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightComment">//cout &lt;&lt; " found in module " &lt;&lt; usedModuleName &lt;&lt; " entry " &lt;&lt; memberName &lt;&lt;  endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1235</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> md.get(); </span><span class="doxyHighlightComment">// whole module used</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1236</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1237</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1238</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1239</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> ( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;name : ue.<a href="/web-doxygen/docs/api/classes/useentry/#a68218c0795c329b96c69d1bf3825f6bc">onlyNames</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1240</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1241</span><span class="doxyLineContent"><span class="doxyHighlight">                </span><span class="doxyHighlightComment">//cout &lt;&lt; " search in only: " &lt;&lt; usedModuleName &lt;&lt; ":: " &lt;&lt; memberName &lt;&lt; "==" &lt;&lt; (*it)&lt;&lt;  endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1242</span><span class="doxyLineContent"><span class="doxyHighlight">                </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (memberName == name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1243</span><span class="doxyLineContent"><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1244</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> md.get(); </span><span class="doxyHighlightComment">// found in ONLY-part of use list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1245</span><span class="doxyLineContent"><span class="doxyHighlight">                }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1246</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1247</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1248</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1249</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1250</span><span class="doxyLineContent"><span class="doxyHighlight">      } </span><span class="doxyHighlightComment">// if linkable</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1251</span><span class="doxyLineContent"><span class="doxyHighlight">    } </span><span class="doxyHighlightComment">// for</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1252</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1253</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> potentialMd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1254</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/scope/#a5d33523531c274635347daf1d40ddc9a">Scope::externalVars</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a6c68c48d8e3dac65c86b39ab838a5f9e">Doxygen::functionNameLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">Definition::isLinkable</a>, <a href="/web-doxygen/docs/api/classes/scope/#aa482827cfef7e8fc106ac71e3abb1398">Scope::localVars</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#adc3a52f780a8b6a6f0653e357b09af6b">Doxygen::memberNameLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/classes/useentry/#a68218c0795c329b96c69d1bf3825f6bc">UseEntry::onlyNames</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>


<p>Referenced by <a href="#ac240a5eb77b55528937ec68a24cf4f46">getLink</a>.</p>

</div>
</div>

### getFortranNamespaceDefs() {#a504e4bc3498a0866fed7ca24f0b6140c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool getFortranNamespaceDefs (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; mname, <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *&amp; cd)</td>
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

<p>searches for definition of a module (Namespace)</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">mname</td>
<td class="doxyParamItemDescription"><p>the name of the module</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">cd</td>
<td class="doxyParamItemDescription"><p>the entry, if found or null</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true, if module is found</p></dd>
</dl>


<p>Definition at line 1110 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a504e4bc3498a0866fed7ca24f0b6140c">1110</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a504e4bc3498a0866fed7ca24f0b6140c">getFortranNamespaceDefs</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;mname,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1111</span><span class="doxyLineContent"><span class="doxyHighlight">                               <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *&amp;cd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1112</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1113</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mname.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>; </span><span class="doxyHighlightComment">/* empty name =&gt; nothing to link */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1114</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1115</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// search for module</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1116</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((cd=<a href="/web-doxygen/docs/api/classes/doxygen/#a033b4829afda05c5eef5cd54749b19bf">Doxygen::namespaceLinkedMap</a>-&gt;find(mname))) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1117</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1118</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1119</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a033b4829afda05c5eef5cd54749b19bf">Doxygen::namespaceLinkedMap</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>


<p>Referenced by <a href="#adfe5e615942afd900cff9f219424d5a5">generateLink</a>.</p>

</div>
</div>

### getFortranTypeDefs() {#a22ca0992a85719c162c23eb696be6608}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool getFortranTypeDefs (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; tname, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; moduleName, <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *&amp; cd, const <a href="/web-doxygen/docs/api/classes/usemap">UseMap</a> &amp; useMap)</td>
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

<p>searches for definition of a type</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">tname</td>
<td class="doxyParamItemDescription"><p>the name of the type</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">moduleName</td>
<td class="doxyParamItemDescription"><p>name of enclosing module or null, if global entry</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">cd</td>
<td class="doxyParamItemDescription"><p>the entry, if found or null</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">useMap</td>
<td class="doxyParamItemDescription"><p>map of data of USE-statement</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true, if type is found</p></dd>
</dl>


<p>Definition at line 1129 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a22ca0992a85719c162c23eb696be6608">1129</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a22ca0992a85719c162c23eb696be6608">getFortranTypeDefs</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;tname, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;moduleName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1130</span><span class="doxyLineContent"><span class="doxyHighlight">                               <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *&amp;cd, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/usemap">UseMap</a> &amp;useMap)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1131</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1132</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tname.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>; </span><span class="doxyHighlightComment">/* empty name =&gt; nothing to link */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1133</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1134</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//cout &lt;&lt; "=== search for type: " &lt;&lt; tname &lt;&lt; endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1135</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1136</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// search for type</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1137</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((cd=<a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>-&gt;find(tname)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1138</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1139</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//cout &lt;&lt; "=== type found in global module" &lt;&lt; endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1140</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1141</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1142</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!moduleName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; (cd=<a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>-&gt;find(moduleName+</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">+tname)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1143</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1144</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//cout &lt;&lt; "=== type found in local module" &lt;&lt; endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1145</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1146</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1147</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1148</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1149</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;[name,useEntry] : useMap)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1150</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1151</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((cd=<a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>-&gt;find(useEntry.module+</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">+tname)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1152</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1153</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//cout &lt;&lt; "===  type found in used module" &lt;&lt; endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1154</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1155</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1156</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1157</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1158</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1159</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1160</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>


<p>Referenced by <a href="#adfe5e615942afd900cff9f219424d5a5">generateLink</a>.</p>

</div>
</div>

### getGenericProcedureLink() {#a2111383c92568a7b28fe96bf69a9f4d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool getGenericProcedureLink (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; memberText, <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; ol)</td>
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

<p>gets the link to a generic procedure which depends not on the name, but on the parameter list</p>


<div class="doxyXrefSect">
<dl class="doxyXrefSectList">
<dt class="doxyXrefSectTitle"><a href=/web-doxygen/docs/api/pages/todo/#_todo000002>Todo</a></dt>
<dd class="doxyXrefSectDescription">
<p>implementation</p>
</dd>
</dl>
</div>

<p>Definition at line 1260 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2111383c92568a7b28fe96bf69a9f4d2">1260</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a2111383c92568a7b28fe96bf69a9f4d2">getGenericProcedureLink</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> ,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1261</span><span class="doxyLineContent"><span class="doxyHighlight">                                    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1262</span><span class="doxyLineContent"><span class="doxyHighlight">                                    <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1263</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1264</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1265</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>.</p>


<p>Referenced by <a href="#adfe5e615942afd900cff9f219424d5a5">generateLink</a>.</p>

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



<p>Definition at line 223 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acb5f8818546103e3b804ab8606b52c4a">223</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#acb5f8818546103e3b804ab8606b52c4a">getLexerFILE</a>() {</span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> __FILE__;}</span></span></div>

</div>

</div>
</div>

### getLink() {#ac240a5eb77b55528937ec68a24cf4f46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool getLink (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/usemap">UseMap</a> &amp; useMap, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; memberText, <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
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



<p>Definition at line 1267 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac240a5eb77b55528937ec68a24cf4f46">1267</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/code-l/#aa48141b866dee2454e4290a3c34d36bb">getLink</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/usemap">UseMap</a> &amp;useMap, </span><span class="doxyHighlightComment">// dictionary with used modules</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1268</span><span class="doxyLineContent"><span class="doxyHighlight">                    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;memberText,  </span><span class="doxyHighlightComment">// exact member text</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1269</span><span class="doxyLineContent"><span class="doxyHighlight">                    <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;ol,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1270</span><span class="doxyLineContent"><span class="doxyHighlight">                    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1271</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1272</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1273</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1274</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> memberName= <a href="/web-doxygen/docs/api/files/src/util-cpp/#a0940360aa6d41fd2496603fc565e3996">removeRedundantWhiteSpace</a>(memberText);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1275</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1276</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((md=<a href="#aa3d64c285d12ea68252876251ea0fc2d">getFortranDefs</a>(yyscanner,memberName, yyextra-&gt;currentModule, useMap)) &amp;&amp; md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">isLinkable</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1277</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1278</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ad7b6f788b487058e9e6ac65b092479b9">isVariable</a>() &amp;&amp; (md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">getLanguage</a>()!=SrcLangExt::Fortran)) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>; </span><span class="doxyHighlightComment">// Non Fortran variables aren't handled yet,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1279</span><span class="doxyLineContent"><span class="doxyHighlight">                                                                                   </span><span class="doxyHighlightComment">// see also linkifyText in util.cpp</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1280</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1281</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d = md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>()==<a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a> ?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1282</span><span class="doxyLineContent"><span class="doxyHighlight">                          md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a7ea253be90981d4a6f0cfdb6dff1d2fd">getBodyDef</a>() : md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1283</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a43566d882fc7994385bbdaf7fe927e67">getGroupDef</a>()) d = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a43566d882fc7994385bbdaf7fe927e67">getGroupDef</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1284</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d &amp;&amp; d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">isLinkable</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1285</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1286</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;currentDefinition &amp;&amp; yyextra-&gt;currentMemberDef &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1287</span><span class="doxyLineContent"><span class="doxyHighlight">          yyextra-&gt;insideBody &amp;&amp; yyextra-&gt;collectXRefs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1288</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1289</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a91959a7c929a76adaaa2d342fea73126">addDocCrossReference</a>(yyextra-&gt;currentMemberDef,md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1290</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1291</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/code-l/#a211386867df5b0f5b03dabbec2c18a6a">writeMultiLineCodeLink</a>(yyscanner,ol,md,!text.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() ? text : memberText);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1292</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/code-l/#a63736112eb4c63a80176566049bbea24">addToSearchIndex</a>(yyscanner, !text.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() ? text : memberText);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1293</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1294</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1295</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1296</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1297</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a91959a7c929a76adaaa2d342fea73126">addDocCrossReference</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a63736112eb4c63a80176566049bbea24">addToSearchIndex</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/definition/#a7ea253be90981d4a6f0cfdb6dff1d2fd">Definition::getBodyDef</a>, <a href="#aa3d64c285d12ea68252876251ea0fc2d">getFortranDefs</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a43566d882fc7994385bbdaf7fe927e67">MemberDef::getGroupDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">Definition::getLanguage</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">Definition::getOuterScope</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">Definition::isLinkable</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#ad7b6f788b487058e9e6ac65b092479b9">MemberDef::isVariable</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a0940360aa6d41fd2496603fc565e3996">removeRedundantWhiteSpace</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/files/src/code-l/#a211386867df5b0f5b03dabbec2c18a6a">writeMultiLineCodeLink</a>.</p>

</div>
</div>

### nextCodeLine() {#a3b060f853a2545afc385b18ecc734473}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void nextCodeLine (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 1020 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3b060f853a2545afc385b18ecc734473">1020</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/code-l/#a3b060f853a2545afc385b18ecc734473">nextCodeLine</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1021</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1022</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1023</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> * fc = yyextra-&gt;currentFontClass;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1024</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a22b46d1ae6472d2565e3bd435f982d16">endCodeLine</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1025</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;yyLineNr&lt;yyextra-&gt;inputLines)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1026</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1027</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;currentFontClass = fc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1028</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/code-l/#a47b0cd13a509f44e1a1032cbf4ad69ed">startCodeLine</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1029</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1030</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/code-l/#a22b46d1ae6472d2565e3bd435f982d16">endCodeLine</a> and <a href="/web-doxygen/docs/api/files/src/code-l/#a47b0cd13a509f44e1a1032cbf4ad69ed">startCodeLine</a>.</p>

</div>
</div>

### parseFortranCode() {#abb8ae57c27d4106567da9d9317c2fe0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void parseFortranCode (<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;, const char *, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, bool, const char *, const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *, int, int, bool, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *, bool, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *, bool, <a href="/web-doxygen/docs/api/files/src/types-h/#ad3f2a8c13ceee9c0aaeabf930dd88266">FortranFormat</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1440 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abb8ae57c27d4106567da9d9317c2fe0b">1440</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abb8ae57c27d4106567da9d9317c2fe0b">parseFortranCode</a>(<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1441</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> , </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1442</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> ,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> ,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1443</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1444</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> , <a href="/web-doxygen/docs/api/files/src/types-h/#ad3f2a8c13ceee9c0aaeabf930dd88266">FortranFormat</a> )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1445</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1446</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("***parseCode() exBlock=%d exName=%s fd=%p\n",exBlock,exName,fd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1447</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1448</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1449</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

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



<p>Definition at line 1592 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a84f9bfb00f12e8fc287ed97f3e1d693c">1592</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1593</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1594</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1595</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( yyg-&gt;yy_start_stack_ptr &lt;= 0 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1596</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(yyextra-&gt;fileName,yyextra-&gt;yyLineNr,</span><span class="doxyHighlightStringLiteral">"Unexpected statement '{}'"</span><span class="doxyHighlight">,yytext );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1597</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1598</span><span class="doxyLineContent"><span class="doxyHighlight">    yy_pop_state(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1599</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.</p>

</div>
</div>

### setCurrentDoc() {#adbfcafb48c794e6885763cd94da51375}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void setCurrentDoc (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor)</td>
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



<p>Definition at line 885 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adbfcafb48c794e6885763cd94da51375">885</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/code-l/#adbfcafb48c794e6885763cd94da51375">setCurrentDoc</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">886</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">887</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">888</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/doxygen/#ae3d8cc749e66634e3902def93f814d07">Doxygen::searchIndex</a>.enabled())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">889</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">890</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;searchCtx)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">891</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">892</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/doxygen/#ae3d8cc749e66634e3902def93f814d07">Doxygen::searchIndex</a>.setCurrentDoc(yyextra-&gt;searchCtx,yyextra-&gt;searchCtx-&gt;anchor(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">893</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">894</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">895</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">896</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/doxygen/#ae3d8cc749e66634e3902def93f814d07">Doxygen::searchIndex</a>.setCurrentDoc(yyextra-&gt;sourceFileDef,anchor,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">897</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">898</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">899</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#ae3d8cc749e66634e3902def93f814d07">Doxygen::searchIndex</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### startCodeLine() {#a47b0cd13a509f44e1a1032cbf4ad69ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void startCodeLine (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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




<p>start a new line of code, inserting a line number if yyextra-&gt;sourceFileDef is TRUE. If a definition starts at the current line, then the line number is linked to the documentation of that definition.</p>


<p>Definition at line 954 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a47b0cd13a509f44e1a1032cbf4ad69ed">954</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/code-l/#a47b0cd13a509f44e1a1032cbf4ad69ed">startCodeLine</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">955</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">956</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">957</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;sourceFileDef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">958</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">959</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//QCString lineNumber,lineAnchor;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">960</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//lineNumber.sprintf("%05d",yyextra-&gt;yyLineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">961</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//lineAnchor.sprintf("l%05d",yyextra-&gt;yyLineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">962</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">963</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d = yyextra-&gt;sourceFileDef-&gt;getSourceDefinition(yyextra-&gt;yyLineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">964</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("startCodeLine %d d=%s\n", yyextra-&gt;yyLineNr,d ? qPrint(d-&gt;name()) : "&lt;null&gt;");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">965</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;includeCodeFragment &amp;&amp; d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">966</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">967</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;currentDefinition = d;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">968</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;currentMemberDef = yyextra-&gt;sourceFileDef-&gt;getSourceMember(yyextra-&gt;yyLineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">969</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;insideBody = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">970</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;endComment = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">971</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> lineAnchor;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">972</span><span class="doxyLineContent"><span class="doxyHighlight">      lineAnchor.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"l%05d"</span><span class="doxyHighlight">,yyextra-&gt;yyLineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">973</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;currentMemberDef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">974</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">975</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/code-l/#afce5972b6b52acbb18c0d79b1f0d4433">codeFolding</a>(yyscanner,yyextra-&gt;currentMemberDef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">976</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;code-&gt;writeLineNumber(yyextra-&gt;currentMemberDef-&gt;getReference(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">977</span><span class="doxyLineContent"><span class="doxyHighlight">                                yyextra-&gt;currentMemberDef-&gt;getOutputFileBase(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">978</span><span class="doxyLineContent"><span class="doxyHighlight">                                yyextra-&gt;currentMemberDef-&gt;anchor(),yyextra-&gt;yyLineNr,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">979</span><span class="doxyLineContent"><span class="doxyHighlight">                                !yyextra-&gt;includeCodeFragment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">980</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/code-l/#adbfcafb48c794e6885763cd94da51375">setCurrentDoc</a>(yyscanner,lineAnchor);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">981</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">982</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a845891c7206d40c3664b562636cdf9fc">isLinkableInProject</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">983</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">984</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/code-l/#afce5972b6b52acbb18c0d79b1f0d4433">codeFolding</a>(yyscanner,d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">985</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;code-&gt;writeLineNumber(d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">getReference</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">986</span><span class="doxyLineContent"><span class="doxyHighlight">                                d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">987</span><span class="doxyLineContent"><span class="doxyHighlight">                                <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),yyextra-&gt;yyLineNr,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">988</span><span class="doxyLineContent"><span class="doxyHighlight">                                !yyextra-&gt;includeCodeFragment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">989</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/code-l/#adbfcafb48c794e6885763cd94da51375">setCurrentDoc</a>(yyscanner,lineAnchor);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">990</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">991</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">992</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">993</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/code-l/#afce5972b6b52acbb18c0d79b1f0d4433">codeFolding</a>(yyscanner,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">994</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">995</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">996</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">997</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">998</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/code-l/#afce5972b6b52acbb18c0d79b1f0d4433">codeFolding</a>(yyscanner,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">999</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;code-&gt;writeLineNumber(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),yyextra-&gt;yyLineNr,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1000</span><span class="doxyLineContent"><span class="doxyHighlight">                                     !yyextra-&gt;includeCodeFragment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1001</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1002</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1003</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;code-&gt;startCodeLine(yyextra-&gt;yyLineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1004</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;insideCodeLine=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;  </span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1005</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;currentFontClass)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1006</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1007</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;code-&gt;startFontClass(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yyextra-&gt;currentFontClass));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1008</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1009</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/code-l/#afce5972b6b52acbb18c0d79b1f0d4433">codeFolding</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">Definition::getReference</a>, <a href="/web-doxygen/docs/api/classes/definition/#a845891c7206d40c3664b562636cdf9fc">Definition::isLinkableInProject</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#adbfcafb48c794e6885763cd94da51375">setCurrentDoc</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">QCString::sprintf</a>.</p>

</div>
</div>

### startFontClass() {#aacdc305fbdfbc50f742f71a1ec5c708a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void startFontClass (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const char * s, bool specialComment=false)</td>
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



<p>Definition at line 868 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aacdc305fbdfbc50f742f71a1ec5c708a">868</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> specialComment)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">869</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">870</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">871</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (specialComment)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">872</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">873</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;code-&gt;startSpecialComment();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">874</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;insideSpecialComment = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">875</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">876</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// if font class is already set don't stop and start it.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">877</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/qcstring-h/#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>(yyextra-&gt;currentFontClass,s)!=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">878</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">879</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">880</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;code-&gt;startFontClass(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(s));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">881</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;currentFontClass=s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">882</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">883</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>.</p>

</div>
</div>

### startScope() {#a1eb414a7080ee6bcef950eba00f991b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void startScope (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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

<p>start scope</p>

<p>Definition at line 1370 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1eb414a7080ee6bcef950eba00f991b7">1370</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1eb414a7080ee6bcef950eba00f991b7">startScope</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1371</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1372</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1373</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr, </span><span class="doxyHighlightStringLiteral">"===&gt; startScope %s"</span><span class="doxyHighlight">,yytext));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1374</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;scopeStack.emplace_back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1375</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a8cb9252694dc27b52bd30efe903f9654">findScopeFromQualifiedName</a>.</p>

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



<p>Definition at line 180 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>

</div>
</div>

### writeMultiLineCodeLink() {#aefd632b8f888c312d4d67dffa15f5669}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeMultiLineCodeLink (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; ol, <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
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




<p>writes a link to a fragment <em>text</em> that may span multiple lines, inserting line numbers for each line. If <em>text</em> contains newlines, the link will be split into multiple links with the same destination, one for each line.</p>


<p>Definition at line 1067 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aefd632b8f888c312d4d67dffa15f5669">1067</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/code-l/#a211386867df5b0f5b03dabbec2c18a6a">writeMultiLineCodeLink</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;ol,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1068</span><span class="doxyLineContent"><span class="doxyHighlight">                  <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1069</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1070</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1071</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> sourceTooltips = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(SOURCE_TOOLTIPS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1072</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;tooltipManager.addTooltip(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1073</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> ref  = d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">getReference</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1074</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> file = d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1075</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> anchor = d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1076</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tooltip;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1077</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!sourceTooltips) </span><span class="doxyHighlightComment">// fall back to simple "title" tooltips</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1078</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1079</span><span class="doxyLineContent"><span class="doxyHighlight">    tooltip = d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a5915353219702c6ea73cc1476bda793a">briefDescriptionAsTooltip</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1080</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1081</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> done=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1082</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=text.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1083</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!done)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1084</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1085</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *sp=p;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1086</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1087</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++) &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) { }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1088</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1089</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1090</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;yyLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1091</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("writeCodeLink(%s,%s,%s,%s)\n",ref,file,anchor,sp);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1092</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputcodelist/#a4fb20173014b60bceb6f75a621749f73">writeCodeLink</a>(d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac94212137110d5ca75eabad07e8ebed6">codeSymbolType</a>(),ref,file,anchor,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(sp,p-sp-1),tooltip);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1093</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/code-l/#a3b060f853a2545afc385b18ecc734473">nextCodeLine</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1094</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1095</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1096</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1097</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("writeCodeLink(%s,%s,%s,%s)\n",ref,file,anchor,sp);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1098</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputcodelist/#a4fb20173014b60bceb6f75a621749f73">writeCodeLink</a>(d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac94212137110d5ca75eabad07e8ebed6">codeSymbolType</a>(),ref,file,anchor,sp,tooltip);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1099</span><span class="doxyLineContent"><span class="doxyHighlight">      done=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1100</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1101</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1102</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">Definition::anchor</a>, <a href="/web-doxygen/docs/api/classes/definition/#a5915353219702c6ea73cc1476bda793a">Definition::briefDescriptionAsTooltip</a>, <a href="/web-doxygen/docs/api/classes/definition/#ac94212137110d5ca75eabad07e8ebed6">Definition::codeSymbolType</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">Definition::getReference</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a3b060f853a2545afc385b18ecc734473">nextCodeLine</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/classes/outputcodelist/#a4fb20173014b60bceb6f75a621749f73">OutputCodeList::writeCodeLink</a>.</p>

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



<p>Definition at line 277 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1d80d8ed8c19744ed31163f6e7525e54">277</a></span><span class="doxyLineContent"><span class="doxyHighlight">%%</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*==================================================================*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*-------- ignore ------------------------------------------------------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;{IGNORE}/{BS}"("</span><span class="doxyHighlight">                   { </span><span class="doxyHighlightComment">// do not search keywords, intrinsics... TODO: complete list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*-------- inner construct ---------------------------------------------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;{COMMANDS}/{BS}[,( \t\n]</span><span class="doxyHighlight">           {  </span><span class="doxyHighlightComment">// highlight</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">/* font class is defined e.g. in doxygen.css */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"keyword"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;{FLOW}/{BS}[,( \t\n]</span><span class="doxyHighlight">               {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;isFixedForm)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((<a href="#a66a71125f0f01a2a8d1a3608807695fa">yy_my_start</a> == 1) &amp;&amp; ((yytext[0] == </span><span class="doxyHighlightCharLiteral">'c'</span><span class="doxyHighlight">) || (yytext[0] == </span><span class="doxyHighlightCharLiteral">'C'</span><span class="doxyHighlight">))) <a href="#a633f0b53ce61259dee93c2398f1674f0">YY_FTN_REJECT</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;currentMemberDef &amp;&amp; yyextra-&gt;currentMemberDef-&gt;isFunction())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">                                            std::lock_guard&lt;std::mutex&gt; lock(<a href="/web-doxygen/docs/api/classes/doxygen/#a9ada31fbc29681eedb5f96b096ab2204">Doxygen::countFlowKeywordsMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *mdm = <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>(</span><span class="doxyHighlightKeyword">const_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(yyextra-&gt;currentMemberDef));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdm)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">                                              mdm-&gt;<a href="/web-doxygen/docs/api/classes/memberdefmutable/#a06e6f4e828cfed2d5b11f202d009b36d">incrementFlowKeyWordCount</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">/* font class is defined e.g. in doxygen.css */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"keywordflow"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;{BS}(RANK){BS_}(DEFAULT)</span><span class="doxyHighlight"> |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;{BS}(RANK)/{BS}"("{BS}([0-9]+|"*"){BS}")"</span><span class="doxyHighlight"> |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;{BS}(CASE|CLASS|TYPE){BS_}(IS|DEFAULT)</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"keywordflow"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;{BS}"end"({BS}{FLOW})/[ \t\n]</span><span class="doxyHighlight">       { </span><span class="doxyHighlightComment">// list is a bit long as not all have possible end</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"keywordflow"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;"implicit"{BS}("none"|{TYPE_SPEC})</span><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"keywordtype"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;^{BS}"namelist"/[/]</span><span class="doxyHighlight">              {  </span><span class="doxyHighlightComment">// Namelist specification</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"keywordtype"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*-------- use statement -------------------------------------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;"use"{BS_}</span><span class="doxyHighlight">                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"keywordtype"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(YY_START,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(Use);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Use&gt;"ONLY"</span><span class="doxyHighlight">                             { </span><span class="doxyHighlightComment">// TODO: rename</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"keywordtype"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(YY_START,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">347</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(UseOnly);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Use&gt;{ID}</span><span class="doxyHighlight">                               {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tmp(yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">351</span><span class="doxyLineContent"><span class="doxyHighlight">                                          tmp = tmp.lower();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;insideBody=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#adfe5e615942afd900cff9f219424d5a5">generateLink</a>(yyscanner,*yyextra-&gt;code, yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;insideBody=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">355</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">356</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">/* append module name to use dict */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;useEntry = <a href="/web-doxygen/docs/api/classes/useentry">UseEntry</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;useEntry.module = tmp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;useMembers.emplace(tmp.str(), yyextra-&gt;useEntry);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a8e24461e4a28d3b200f27ade4dbc7a53">addUse</a>(yyscanner,tmp);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">361</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Use,UseOnly,Import&gt;{BS},{BS}</span><span class="doxyHighlight">           { <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;UseOnly,Import&gt;{BS}&amp;{BS}"\n"</span><span class="doxyHighlight">           { <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;contLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a9a0fdbfa8e6dc0e59c2015a0f1e663c2">YY_FTN_RESET</a>}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">366</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;UseOnly&gt;{ID}</span><span class="doxyHighlight">                           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">367</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tmp(yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">                                          tmp = tmp.lower();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;useEntry.onlyNames.push_back(tmp);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;insideBody=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#adfe5e615942afd900cff9f219424d5a5">generateLink</a>(yyscanner,*yyextra-&gt;code, yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;insideBody=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Use,UseOnly,Import&gt;"\n"</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">                                          unput(*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a9a0fdbfa8e6dc0e59c2015a0f1e663c2">YY_FTN_RESET</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;"import"{BS}/"\n"</span><span class="doxyHighlight">                    |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;"import"{BS_}</span><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">(YY_START == String) <a href="#a633f0b53ce61259dee93c2398f1674f0">YY_FTN_REJECT</a>; </span><span class="doxyHighlightComment">// ignore in strings</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"keywordtype"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(YY_START,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(Import);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Import&gt;{ID}</span><span class="doxyHighlight">                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;insideBody=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#adfe5e615942afd900cff9f219424d5a5">generateLink</a>(yyscanner,*yyextra-&gt;code, yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;insideBody=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Import&gt;("ONLY"|"NONE"|"ALL")</span><span class="doxyHighlight">           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"keywordtype"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*-------- fortran module  -----------------------------------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;("block"{BS}"data"|"program"|"module"|"interface")/{BS_}|({COMMA}{ACCESS_SPEC})|\n</span><span class="doxyHighlight"> {  </span><span class="doxyHighlightComment">//</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a1eb414a7080ee6bcef950eba00f991b7">startScope</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"keyword"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">402</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(YY_START,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">405</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(ClassName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">406</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a773d5813108052583cde43cc8517893d">qstricmp</a>(yytext,</span><span class="doxyHighlightStringLiteral">"module"</span><span class="doxyHighlight">)) yyextra-&gt;currentModule=</span><span class="doxyHighlightStringLiteral">"module"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">407</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">408</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;("enum")/{BS_}|{BS}{COMMA}{BS}{LANGUAGE_BIND_SPEC}|\n</span><span class="doxyHighlight"> {  </span><span class="doxyHighlightComment">//</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">409</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a1eb414a7080ee6bcef950eba00f991b7">startScope</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"keyword"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">411</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">412</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">413</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(YY_START,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">414</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(ClassName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">415</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;{LANGUAGE_BIND_SPEC}</span><span class="doxyHighlight">                 {  </span><span class="doxyHighlightComment">//</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">417</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">(YY_START == String) <a href="#a633f0b53ce61259dee93c2398f1674f0">YY_FTN_REJECT</a>; </span><span class="doxyHighlightComment">// ignore in strings</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">418</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"keyword"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">419</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">421</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">422</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;("type")/{BS_}|({COMMA}({ACCESS_SPEC}|ABSTRACT|EXTENDS))|\n</span><span class="doxyHighlight"> {  </span><span class="doxyHighlightComment">//</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">423</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a1eb414a7080ee6bcef950eba00f991b7">startScope</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">424</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"keyword"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">425</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">426</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">427</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(YY_START,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">428</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(ClassName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">429</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">430</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ClassName&gt;{ID}</span><span class="doxyHighlight">                         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">431</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;currentModule == </span><span class="doxyHighlightStringLiteral">"module"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">432</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">433</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;currentModule=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">434</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;currentModule = yyextra-&gt;currentModule.lower();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">435</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#adfe5e615942afd900cff9f219424d5a5">generateLink</a>(yyscanner,*yyextra-&gt;code,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">439</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ClassName&gt;({ACCESS_SPEC}|ABSTRACT|EXTENDS)/[,:( ]</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">//| variable declaration</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"keyword"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">441</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;code-&gt;codify(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">442</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ClassName&gt;\n</span><span class="doxyHighlight">                           { </span><span class="doxyHighlightComment">// interface may be without name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">446</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a633f0b53ce61259dee93c2398f1674f0">YY_FTN_REJECT</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">447</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;^{BS}"end"({BS_}"enum").*</span><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a633f0b53ce61259dee93c2398f1674f0">YY_FTN_REJECT</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;^{BS}"end"({BS_}"type").*</span><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a633f0b53ce61259dee93c2398f1674f0">YY_FTN_REJECT</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;^{BS}"end"({BS_}"module").*</span><span class="doxyHighlight">      { </span><span class="doxyHighlightComment">// just reset yyextra-&gt;currentModule, rest is done in following rule</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;currentModule=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a633f0b53ce61259dee93c2398f1674f0">YY_FTN_REJECT</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">457</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*-------- subprog definition -------------------------------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;({PREFIX}{BS_})?{TYPE_SPEC}{BS_}({PREFIX}{BS_})?{BS}/{SUBPROG}{BS_}</span><span class="doxyHighlight">  {   </span><span class="doxyHighlightComment">// TYPE_SPEC is for old function style function result</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"keyword"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;({PREFIX}{BS_})?{SUBPROG}{BS_}</span><span class="doxyHighlight">   {  </span><span class="doxyHighlightComment">// Fortran subroutine or function found</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"keyword"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(YY_START,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(Subprog);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Subprog&gt;{ID}</span><span class="doxyHighlight">                           { </span><span class="doxyHighlightComment">// subroutine/function name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr, </span><span class="doxyHighlightStringLiteral">"===&gt; start subprogram %s\n"</span><span class="doxyHighlight">, yytext));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a1eb414a7080ee6bcef950eba00f991b7">startScope</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#adfe5e615942afd900cff9f219424d5a5">generateLink</a>(yyscanner,*yyextra-&gt;code,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Subprog&gt;"result"/{BS}"("[^)]*")"</span><span class="doxyHighlight">       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"keyword"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">479</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Subprog&gt;"("[^)]*")"</span><span class="doxyHighlight">                    { </span><span class="doxyHighlightComment">// ignore rest of line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Subprog,Subprogend&gt;"\n"</span><span class="doxyHighlight">                { <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;contLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a9a0fdbfa8e6dc0e59c2015a0f1e663c2">YY_FTN_RESET</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;"end"{BS}("block"{BS}"data"|{SUBPROG}|"module"|"program"|"enum"|"type"|"interface")?{BS}</span><span class="doxyHighlight">     {  </span><span class="doxyHighlightComment">// Fortran subroutine or function ends</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//cout &lt;&lt; "===&gt; end function " &lt;&lt; yytext &lt;&lt; endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a239ee1e47d4722402cd650ae2d0cd59f">endScope</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"keyword"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(YY_START,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(Subprogend);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Subprogend&gt;{ID}/{BS}(\n|!|;)</span><span class="doxyHighlight">           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#adfe5e615942afd900cff9f219424d5a5">generateLink</a>(yyscanner,*yyextra-&gt;code,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;"end"{BS}("block"{BS}"data"|{SUBPROG}|"module"|"program"|"enum"|"type"|"interface"){BS}/(\n|!|;)</span><span class="doxyHighlight"> {  </span><span class="doxyHighlightComment">// Fortran subroutine or function ends</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//cout &lt;&lt; "===&gt; end function " &lt;&lt; yytext &lt;&lt; endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a239ee1e47d4722402cd650ae2d0cd59f">endScope</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"keyword"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*-------- variable declaration ----------------------------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;^{BS}"real"/[,:( ]</span><span class="doxyHighlight">               { </span><span class="doxyHighlightComment">// real is a bit tricky as it is a data type but also a function.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(YY_START,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(Declaration);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">513</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"keywordtype"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">514</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;code-&gt;codify(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">515</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">516</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">517</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;{TYPE_SPEC}/[,:( ]</span><span class="doxyHighlight">               {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">518</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> typ(yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span><span class="doxyLineContent"><span class="doxyHighlight">                                          typ = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a0940360aa6d41fd2496603fc565e3996">removeRedundantWhiteSpace</a>(typ.lower());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (typ.startsWith(</span><span class="doxyHighlightStringLiteral">"real"</span><span class="doxyHighlight">)) <a href="#a633f0b53ce61259dee93c2398f1674f0">YY_FTN_REJECT</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">521</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (typ == </span><span class="doxyHighlightStringLiteral">"type"</span><span class="doxyHighlight"> || typ == </span><span class="doxyHighlightStringLiteral">"class"</span><span class="doxyHighlight"> || typ == </span><span class="doxyHighlightStringLiteral">"procedure"</span><span class="doxyHighlight">) yyextra-&gt;inTypeDecl = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(YY_START,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(Declaration);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"keywordtype"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">525</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;code-&gt;codify(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">526</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">527</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">528</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;{ATTR_SPEC}</span><span class="doxyHighlight">                      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">529</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext) == </span><span class="doxyHighlightStringLiteral">"external"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">530</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">531</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yy_push_state(YY_START,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">532</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(Declaration);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">533</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;isExternal = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">534</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">535</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"keywordtype"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">536</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;code-&gt;codify(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">537</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">538</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">539</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Declaration&gt;({TYPE_SPEC}|{ATTR_SPEC})/[,:( ]</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">//| variable declaration</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">540</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext) == </span><span class="doxyHighlightStringLiteral">"external"</span><span class="doxyHighlight">) yyextra-&gt;isExternal = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">541</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"keywordtype"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">542</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;code-&gt;codify(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">543</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">544</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">545</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Declaration&gt;{ID}</span><span class="doxyHighlight">                       { </span><span class="doxyHighlightComment">// local var</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">546</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;isFixedForm &amp;&amp; <a href="#a66a71125f0f01a2a8d1a3608807695fa">yy_my_start</a> == 1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">547</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">548</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"comment"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">549</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;code-&gt;codify(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">550</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">551</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">552</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;currentMemberDef &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">553</span><span class="doxyLineContent"><span class="doxyHighlight">                                                   ((yyextra-&gt;currentMemberDef-&gt;isFunction() &amp;&amp; (yyextra-&gt;currentMemberDef-&gt;typeString()!=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"subroutine"</span><span class="doxyHighlight">) || yyextra-&gt;inTypeDecl)) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">554</span><span class="doxyLineContent"><span class="doxyHighlight">                                                     yyextra-&gt;currentMemberDef-&gt;isVariable() || yyextra-&gt;currentMemberDef-&gt;isEnumValue()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">555</span><span class="doxyLineContent"><span class="doxyHighlight">                                                    )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">556</span><span class="doxyLineContent"><span class="doxyHighlight">                                                   )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">557</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">558</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#adfe5e615942afd900cff9f219424d5a5">generateLink</a>(yyscanner,*yyextra-&gt;code, yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">559</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">560</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">561</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;code-&gt;codify(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">563</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#ad36e56c8bfd19605777cd5511cd13cbb">addLocalVar</a>(yyscanner,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">566</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Declaration&gt;{BS}("=&gt;"|"="){BS}</span><span class="doxyHighlight">         { </span><span class="doxyHighlightComment">// Procedure binding</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">567</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(DeclarationBinding);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">568</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;code-&gt;codify(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">569</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">570</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DeclarationBinding&gt;{ID}</span><span class="doxyHighlight">                { </span><span class="doxyHighlightComment">// Type bound procedure link</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">571</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#adfe5e615942afd900cff9f219424d5a5">generateLink</a>(yyscanner,*yyextra-&gt;code, yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">572</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Declaration&gt;[(]</span><span class="doxyHighlight">                        { </span><span class="doxyHighlightComment">// start of array or type / class specification</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">575</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;bracketCount++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">576</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;code-&gt;codify(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">577</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">578</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Declaration&gt;[)]</span><span class="doxyHighlight">                        { </span><span class="doxyHighlightComment">// end array specification</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;bracketCount--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;bracketCount) yyextra-&gt;inTypeDecl = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;code-&gt;codify(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">584</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Declaration,DeclarationBinding&gt;"&amp;"</span><span class="doxyHighlight">     { </span><span class="doxyHighlightComment">// continuation line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">586</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;code-&gt;codify(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">587</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;isFixedForm)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">589</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yy_push_state(YY_START,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">590</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(DeclContLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">591</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">592</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">593</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DeclContLine&gt;"\n"</span><span class="doxyHighlight">                      { </span><span class="doxyHighlightComment">// declaration not yet finished</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;contLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;bracketCount = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a9a0fdbfa8e6dc0e59c2015a0f1e663c2">YY_FTN_RESET</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Declaration,DeclarationBinding&gt;"\n"</span><span class="doxyHighlight">    { </span><span class="doxyHighlightComment">// end declaration line (?)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">601</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;endComment)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">602</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">603</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;endComment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">604</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;bracketCount = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;contLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!(yyextra-&gt;hasContLine &amp;&amp; yyextra-&gt;hasContLine[yyextra-&gt;contLineNr - 1]))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">613</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;isExternal = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">614</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">615</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">616</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a9a0fdbfa8e6dc0e59c2015a0f1e663c2">YY_FTN_RESET</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">618</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">619</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*-------- subprog calls  -----------------------------------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">620</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">621</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;"call"{BS_}</span><span class="doxyHighlight">                      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">622</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"keyword"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">623</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">624</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">625</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(YY_START,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">626</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(SubCall);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">627</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">628</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SubCall&gt;{ID}</span><span class="doxyHighlight">                           { </span><span class="doxyHighlightComment">// subroutine call</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">629</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;insideBody=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">630</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#adfe5e615942afd900cff9f219424d5a5">generateLink</a>(yyscanner,*yyextra-&gt;code, yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">631</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;insideBody=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">632</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">633</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">634</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;{ID}{BS}/"("</span><span class="doxyHighlight">                     { </span><span class="doxyHighlightComment">// function call</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">635</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;isFixedForm &amp;&amp; <a href="#a66a71125f0f01a2a8d1a3608807695fa">yy_my_start</a> == 6)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">636</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">637</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">// fixed form continuation line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">638</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a633f0b53ce61259dee93c2398f1674f0">YY_FTN_REJECT</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">639</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">640</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/files/src/stringutil-h/#aef47e534975880014a6514745e885a99">stripWhiteSpace</a>().lower() == </span><span class="doxyHighlightStringLiteral">"type"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">641</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">642</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yy_push_state(YY_START,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">643</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(Declaration);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">644</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"keywordtype"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">645</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;code-&gt;codify(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/files/src/stringutil-h/#aef47e534975880014a6514745e885a99">stripWhiteSpace</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">646</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">647</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;code-&gt;codify(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext + 4));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">648</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">649</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">650</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">651</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;insideBody=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">652</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#adfe5e615942afd900cff9f219424d5a5">generateLink</a>(yyscanner,*yyextra-&gt;code,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">653</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;insideBody=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">654</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">655</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">656</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">657</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*-------- comments ---------------------------------------------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">658</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start,Declaration,DeclarationBinding&gt;\n?{BS}"!&gt;"|"!&lt;"</span><span class="doxyHighlight">                 { </span><span class="doxyHighlightComment">// start comment line or comment block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">659</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yytext[0] == </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">660</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">661</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;contLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">662</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#ab0517027b61f63c8a563733d6e813ad1">yy_old_start</a> = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">663</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a66a71125f0f01a2a8d1a3608807695fa">yy_my_start</a> = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">664</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#adc3fff33a8db22a36f05baec1001a010">yy_end</a> = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">665</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">666</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">// Actually we should see if ! on position 6, can be continuation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">// but the chance is very unlikely, so no effort to solve it here</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">668</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(YY_START,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(DocBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">670</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">671</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">672</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Declaration,DeclarationBinding&gt;{BS}"!&lt;"</span><span class="doxyHighlight">                   { </span><span class="doxyHighlightComment">// start comment line or comment block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">673</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(YY_START,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">674</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(DocBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">675</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">676</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">677</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">678</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocBlock&gt;.*</span><span class="doxyHighlight">                            { </span><span class="doxyHighlightComment">// contents of current comment line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">679</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">680</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">681</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocBlock&gt;"\n"{BS}("!&gt;"|"!&lt;"|"!!")</span><span class="doxyHighlight">      { </span><span class="doxyHighlightComment">// comment block (next line is also comment line)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">682</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;contLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">683</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ab0517027b61f63c8a563733d6e813ad1">yy_old_start</a> = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">684</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a66a71125f0f01a2a8d1a3608807695fa">yy_my_start</a> = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">685</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#adc3fff33a8db22a36f05baec1001a010">yy_end</a> = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">686</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">// Actually we should see if ! on position 6, can be continuation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">687</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">// but the chance is very unlikely, so no effort to solve it here</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">688</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;docBlock+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">689</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">690</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DocBlock&gt;"\n"</span><span class="doxyHighlight">                          { </span><span class="doxyHighlightComment">// comment block ends at the end of this line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">691</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">// remove special comment (default config)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">692</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;contLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">693</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"comment"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">694</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yyextra-&gt;docBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">696</span><span class="doxyLineContent"><span class="doxyHighlight">                                          unput(*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">697</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;contLineNr--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">698</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">699</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a9a0fdbfa8e6dc0e59c2015a0f1e663c2">YY_FTN_RESET</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">700</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">701</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">702</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;"!"[^&gt;&lt;\n].*|"!"$</span><span class="doxyHighlight">                    { </span><span class="doxyHighlightComment">// normal comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">703</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">(YY_START == String) <a href="#a633f0b53ce61259dee93c2398f1674f0">YY_FTN_REJECT</a>; </span><span class="doxyHighlightComment">// ignore in strings</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">704</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;isFixedForm &amp;&amp; <a href="#a66a71125f0f01a2a8d1a3608807695fa">yy_my_start</a> == 6) <a href="#a633f0b53ce61259dee93c2398f1674f0">YY_FTN_REJECT</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">705</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"comment"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">706</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">707</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">708</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">709</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">710</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;^[Cc*].*</span><span class="doxyHighlight">                             { </span><span class="doxyHighlightComment">// normal comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">711</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">(! yyextra-&gt;isFixedForm) <a href="#a633f0b53ce61259dee93c2398f1674f0">YY_FTN_REJECT</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">712</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">713</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"comment"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">714</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">715</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">716</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">717</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;"assignment"/{BS}"("{BS}"="{BS}")"</span><span class="doxyHighlight">   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">718</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">(YY_START == String) <a href="#a633f0b53ce61259dee93c2398f1674f0">YY_FTN_REJECT</a>; </span><span class="doxyHighlightComment">// ignore in strings</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">719</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"keyword"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">720</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">721</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">722</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">723</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;"operator"/{BS}"("[^)]*")"</span><span class="doxyHighlight">           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">724</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">(YY_START == String) <a href="#a633f0b53ce61259dee93c2398f1674f0">YY_FTN_REJECT</a>; </span><span class="doxyHighlightComment">// ignore in strings</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">725</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"keyword"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">726</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">727</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">728</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">729</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">730</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*------ preprocessor  --------------------------------------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">731</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;"#".*\n</span><span class="doxyHighlight">                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">732</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;isFixedForm &amp;&amp; <a href="#a66a71125f0f01a2a8d1a3608807695fa">yy_my_start</a> == 6) <a href="#a633f0b53ce61259dee93c2398f1674f0">YY_FTN_REJECT</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">733</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;contLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">734</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"preprocessor"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">735</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">736</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">737</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a9a0fdbfa8e6dc0e59c2015a0f1e663c2">YY_FTN_RESET</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">738</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">739</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*------ variable references?  -------------------------------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">740</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">741</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;"%"{BS}{ID}</span><span class="doxyHighlight">                      { </span><span class="doxyHighlightComment">// ignore references to elements</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">742</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;code-&gt;codify(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">743</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">744</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;{ID}</span><span class="doxyHighlight">                             {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">745</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;insideBody=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">746</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#adfe5e615942afd900cff9f219424d5a5">generateLink</a>(yyscanner,*yyextra-&gt;code, yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">747</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;insideBody=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">748</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">749</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*------ strings --------------------------------------------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">750</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;String&gt;\n</span><span class="doxyHighlight">                              { </span><span class="doxyHighlightComment">// string with \n inside</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">751</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;contLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">752</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;str+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">753</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"stringliteral"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">754</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yyextra-&gt;str);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">755</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">756</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;str = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">757</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a9a0fdbfa8e6dc0e59c2015a0f1e663c2">YY_FTN_RESET</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">758</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">759</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;String&gt;\"|\'</span><span class="doxyHighlight">                           { </span><span class="doxyHighlightComment">// string ends with next quote without previous backspace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">760</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">(yytext[0]!=yyextra-&gt;stringStartSymbol) <a href="#a633f0b53ce61259dee93c2398f1674f0">YY_FTN_REJECT</a>; </span><span class="doxyHighlightComment">// single vs double quote</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">761</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;str+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">762</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"stringliteral"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">763</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yyextra-&gt;str);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">764</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">765</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a84f9bfb00f12e8fc287ed97f3e1d693c">pop_state</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">766</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">767</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;String&gt;[\x80-\xFF]*</span><span class="doxyHighlight">                    |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">768</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;String&gt;.</span><span class="doxyHighlight">                               {yyextra-&gt;str+=yytext;}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">769</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">770</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;\"|\'</span><span class="doxyHighlight">                                { </span><span class="doxyHighlightComment">/* string starts */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">771</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">/* if(YY_START == StrIgnore) YY_FTN_REJECT; // ignore in simple comments */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">772</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;isFixedForm &amp;&amp; <a href="#a66a71125f0f01a2a8d1a3608807695fa">yy_my_start</a> == 6) <a href="#a633f0b53ce61259dee93c2398f1674f0">YY_FTN_REJECT</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">773</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yy_push_state(YY_START,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">774</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;stringStartSymbol=yytext[0]; </span><span class="doxyHighlightComment">// single or double quote</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">775</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(String);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">776</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;str=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">777</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">778</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*-----------------------------------------------------------------------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">779</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">780</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;\n</span><span class="doxyHighlight">                                   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">781</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;endComment)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">782</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">783</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;endComment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">784</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">785</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">786</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">787</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">788</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">// comment cannot extend over the end of a line so should always be terminated at the end of the line.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">789</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;currentFontClass &amp;&amp; !strcmp(yyextra-&gt;currentFontClass,</span><span class="doxyHighlightStringLiteral">"comment"</span><span class="doxyHighlight">)) <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">790</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">791</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;contLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">792</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a9a0fdbfa8e6dc0e59c2015a0f1e663c2">YY_FTN_RESET</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">793</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">794</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;^{BS}"type"{BS}"="</span><span class="doxyHighlight">                   { yyextra-&gt;code-&gt;codify(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext)); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">795</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">796</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;[\x80-\xFF]*</span><span class="doxyHighlight">                         { </span><span class="doxyHighlightComment">// keep utf8 characters together...</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">797</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;isFixedForm &amp;&amp; <a href="#a66a71125f0f01a2a8d1a3608807695fa">yy_my_start</a> &gt; yyextra-&gt;fixedCommentAfter)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">798</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">799</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"comment"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">800</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">801</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">802</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">803</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">804</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;code-&gt;codify(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">805</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">806</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">807</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;.</span><span class="doxyHighlight">                                    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">808</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;isFixedForm &amp;&amp; <a href="#a66a71125f0f01a2a8d1a3608807695fa">yy_my_start</a> &gt; yyextra-&gt;fixedCommentAfter)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">809</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">810</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">//yy_push_state(YY_START,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">811</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">//BEGIN(DocBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">812</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">//yyextra-&gt;docBlock=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">813</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"comment"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">814</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">815</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">816</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">817</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">818</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;code-&gt;codify(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">819</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">820</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">821</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;{LOG_OPER}</span><span class="doxyHighlight">                           { </span><span class="doxyHighlightComment">// Fortran logical comparison keywords</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">822</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;code-&gt;codify(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">823</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">824</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;&lt;&lt;EOF&gt;&gt;</span><span class="doxyHighlight">                              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">825</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START == DocBlock)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">826</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">827</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/code-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"comment"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">828</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>(yyscanner,yyextra-&gt;docBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">829</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/code-l/#ab499eb5a5a3c5a6d6e40323a1d10747f">endFontClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">830</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">831</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#ac3286b18a2e91b4571b97df96a118e84">yyterminate</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">832</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">833</span><span class="doxyLineContent"><span class="doxyHighlight">%%</span></span></div>

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



<p>Definition at line 838 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5edfc25f0c460f3263fdb340f7a02b03">838</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/code-l/#a5edfc25f0c460f3263fdb340f7a02b03">yyread</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *buf,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> max_size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">839</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">840</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">841</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> inputPosition = yyextra-&gt;inputPosition;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">842</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s = yyextra-&gt;inputString + inputPosition;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">843</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> c=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">844</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight">( c &lt; max_size &amp;&amp; *s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">845</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">846</span><span class="doxyLineContent"><span class="doxyHighlight">    *buf++ = *s++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">847</span><span class="doxyLineContent"><span class="doxyHighlight">    c++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">848</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">849</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputPosition += c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">850</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">851</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### yy\_end {#adc3fff33a8db22a36f05baec1001a010}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int yy_end = 1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adc3fff33a8db22a36f05baec1001a010">86</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#adc3fff33a8db22a36f05baec1001a010">yy_end</a>       = 1;</span></span></div>

</div>

</div>
</div>

### yy\_my\_start {#a66a71125f0f01a2a8d1a3608807695fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int yy_my_start = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a66a71125f0f01a2a8d1a3608807695fa">85</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a66a71125f0f01a2a8d1a3608807695fa">yy_my_start</a>  = 0;</span></span></div>

</div>

</div>
</div>

### yy\_old\_start {#ab0517027b61f63c8a563733d6e813ad1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int yy_old_start = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab0517027b61f63c8a563733d6e813ad1">84</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#ab0517027b61f63c8a563733d6e813ad1">yy_old_start</a> = 0;</span></span></div>

</div>

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



<p>Definition at line 71 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a234e2efe67eececd88b140b46ea37463">71</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DBG_CTX(x) do { } while(0)</span></span></div>

</div>

</div>
</div>

### YY\_FTN\_REJECT {#a633f0b53ce61259dee93c2398f1674f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define YY_FTN_REJECT&nbsp;&nbsp;&nbsp;{<a href="#adc3fff33a8db22a36f05baec1001a010">yy_end</a> = <a href="#a66a71125f0f01a2a8d1a3608807695fa">yy_my_start</a>; <a href="#a66a71125f0f01a2a8d1a3608807695fa">yy_my_start</a> = <a href="#ab0517027b61f63c8a563733d6e813ad1">yy_old_start</a>; REJECT;}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a633f0b53ce61259dee93c2398f1674f0">89</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define YY_FTN_REJECT  {yy_end = yy_my_start; yy_my_start = yy_old_start; REJECT;}</span></span></div>

</div>

</div>
</div>

### YY\_FTN\_RESET {#a9a0fdbfa8e6dc0e59c2015a0f1e663c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define YY_FTN_RESET&nbsp;&nbsp;&nbsp;{<a href="#ab0517027b61f63c8a563733d6e813ad1">yy_old_start</a> = 0; <a href="#a66a71125f0f01a2a8d1a3608807695fa">yy_my_start</a> = 0; <a href="#adc3fff33a8db22a36f05baec1001a010">yy_end</a> = 1;}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9a0fdbfa8e6dc0e59c2015a0f1e663c2">88</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define YY_FTN_RESET   {yy_old_start = 0; yy_my_start = 0; yy_end = 1;}</span></span></div>

</div>

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



<p>Definition at line 220 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aacfdca45fa4beb8b06172525a53c424a">220</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define YY_INPUT(buf,result,max_size) result=yyread(yyscanner,buf,max_size);</span></span></div>

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



<p>Definition at line 74 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a85523a0c7d95c059d251b4e9829947aa">74</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define YY_NO_INPUT 1</span></span></div>

</div>

</div>
</div>

### YY\_NO\_TOP\_STATE {#ac3eedc6d2e3e4c9b2bacd0f1ebeab98a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define YY_NO_TOP_STATE&nbsp;&nbsp;&nbsp;1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac3eedc6d2e3e4c9b2bacd0f1ebeab98a">73</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define YY_NO_TOP_STATE 1</span></span></div>

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



<p>Definition at line 75 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae78ac56cd1f29572e967ed7636952d15">75</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define YY_NO_UNISTD_H 1</span></span></div>

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




<div class="doxyXrefSect">
<dl class="doxyXrefSectList">
<dt class="doxyXrefSectTitle"><a href=/web-doxygen/docs/api/pages/todo/#_todo000001>Todo</a></dt>
<dd class="doxyXrefSectDescription">
<ul class="doxyList ">
<li>continuation lines not always recognized</li>
<li>merging of use-statements with same module name and different only-names</li>
<li>rename part of use-statement</li>
<li>links to interface functions</li>
<li>references to variables</li>
</ul>
</dd>
</dl>
</div>

<p>Definition at line 37 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5d5508008cac8fb66fca3baa4e9b6584">37</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define YY_TYPEDEF_YY_SCANNER_T</span></span></div>

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
<td class="doxyMemberName">#define YY_USER_ACTION&nbsp;&nbsp;&nbsp;{<a href="#ab0517027b61f63c8a563733d6e813ad1">yy_old_start</a> = <a href="#a66a71125f0f01a2a8d1a3608807695fa">yy_my_start</a>; <a href="#a66a71125f0f01a2a8d1a3608807695fa">yy_my_start</a> = <a href="#adc3fff33a8db22a36f05baec1001a010">yy_end</a>; <a href="#adc3fff33a8db22a36f05baec1001a010">yy_end</a> += static_cast&lt;int&gt;(yyleng);}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6198b2fcf96178b24ad4efff2a3debb0">87</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define YY_USER_ACTION {yy_old_start = yy_my_start; yy_my_start = yy_end; yy_end += static_cast&lt;int&gt;(yyleng);}</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
