---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/pyscanner-l
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `pyscanner.l` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;stdint.h&gt;
#include &lt;algorithm&gt;
#include &lt;stdio.h&gt;
#include &lt;stdlib.h&gt;
#include &lt;assert.h&gt;
#include &lt;ctype.h&gt;
#include &lt;string.h&gt;
#include "<a href="/web-doxygen/docs/api/files/src/pyscanner-h">pyscanner.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/entry-h">entry.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/defargs-h">defargs.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/language-h">language.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/commentscan-h">commentscan.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/markdown-h">markdown.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/fileinfo-h">fileinfo.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/stringutil-h">stringutil.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-lex-h">doxygen_lex.h</a>"
#include "pyscanner.l.h"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/pyscanneryy-state">pyscannerYY_state</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/pythonoutlineparser/private">Private</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04219d02c56369b619778a94f19fd58f">newEntry</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac41321000a4a4f6ab696d4a6a88a4fef">addEntry</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f97070341210413d4ebab8defffdcb8">docVariable</a> (yyscan_t yyscanner, const char *s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a851aa07f7276b7e8f4b12d2592d2eb39">newVariable</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6ecf9ac01a23dc21259b408a314f54a">addVariable</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae986dc4d2214f2b90b824521c25a2a5c">newFunction</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71aab00668419c1f9fdfeecf87e0d59f">findPackageScopeFromPath</a> (yyscan_t yyscanner, const QCString &amp;path)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b2171b8a9cdc055bd41d0181094f27a">addFrom</a> (yyscan_t yyscanner, bool all)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e782ca00a48833dff52b4b5f0a1a147">lineCount</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae479adb32c06d965a4f4baee921f0c5a">startCommentBlock</a> (yyscan_t yyscanner, bool brief)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bbc5085e6314777292116922282abf8">endOfDef</a> (yyscan_t yyscanner, int correction=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af99856e2fbe8c4e1f9ddd308cc5237de">addToString</a> (yyscan_t yyscanner, const char *s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1fd664818291e7a90ed2ba46a0f44a7">initTriDoubleQuoteBlock</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2aa292ec6b6ea81860b3d9b00405d1cb">initTriSingleQuoteBlock</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22addf63e54e56357d7a2691022828e1">initSpecialBlock</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab61319bebda3e72e8fbde5a911cccc95">searchFoundDef</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a601173b4a0fe4bb62a0e4749429ee062">searchFoundClass</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57ef3ef713c786fffec737ed9556ed63">findPackageScope</a> (yyscan_t yyscanner, const QCString &amp;fileName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bb5a3fd461f68eff332a09e9e5b0e1e">setProtection</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3d71282d72dd7136124a4c7405f6b28">parseCompounds</a> (yyscan_t yyscanner, std::shared_ptr&lt; Entry &gt; rt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a8ff9e246514b6146a187f9648c2736">parseMain</a> (yyscan_t yyscanner, const QCString &amp;fileName, const char *fileBuf, const std::shared_ptr&lt; Entry &gt; &amp;rt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e7dce846ca75b58d7010c2855a84ed6">parsePrototype</a> (yyscan_t yyscanner, const QCString &amp;text)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86da2f5e3360caa90276fc24433d9512">unput_string</a>(yytext, yyleng)&nbsp;&nbsp;&nbsp;do { for (int i=(int)yyleng-1;i&gt;=0;i--) unput(yytext[i]); } while(0)</td>
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



<p>Definition at line 31 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9484188abbc459dafcbd4c96425fa70b">31</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">typedef</span><span class="doxyHighlight"> yyguts_t *<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a>;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### addEntry() {#ac41321000a4a4f6ab696d4a6a88a4fef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addEntry (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 1825 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac41321000a4a4f6ab696d4a6a88a4fef">1825</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac41321000a4a4f6ab696d4a6a88a4fef">addEntry</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1826</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1827</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1828</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1829</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> doc        = yyextra-&gt;current-&gt;doc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1830</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> docLine    = yyextra-&gt;current-&gt;docLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1831</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> docFile    = yyextra-&gt;current-&gt;docFile;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1832</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> brief      = yyextra-&gt;current-&gt;brief;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1833</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> briefLine  = yyextra-&gt;current-&gt;briefLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1834</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> briefFile  = yyextra-&gt;current-&gt;briefFile;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1835</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1836</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;previous = yyextra-&gt;current;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1837</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current_root-&gt;moveToSubEntryAndRefresh(yyextra-&gt;current);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1838</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#affe329b2bcd94b04290e03afad9c97c5">initEntry</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1839</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1840</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;doc        = doc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1841</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;docLine    = docLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1842</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;docFile    = docFile;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1843</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;brief      = brief;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1844</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;briefLine  = briefLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1845</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;briefFile  = briefFile;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1846</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#affe329b2bcd94b04290e03afad9c97c5">initEntry</a>.</p>


<p>Referenced by <a href="#af6ecf9ac01a23dc21259b408a314f54a">addVariable</a>.</p>

</div>
</div>

### addFrom() {#a3b2171b8a9cdc055bd41d0181094f27a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addFrom (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, bool all)</td>
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



<p>Definition at line 1963 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3b2171b8a9cdc055bd41d0181094f27a">1963</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3b2171b8a9cdc055bd41d0181094f27a">addFrom</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> all)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1964</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1965</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1966</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> item=all ? yyextra-&gt;packageName : yyextra-&gt;packageName+</span><span class="doxyHighlightStringLiteral">"."</span><span class="doxyHighlight">+yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1967</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;name=<a href="/web-doxygen/docs/api/files/src/util-cpp/#a0940360aa6d41fd2496603fc565e3996">removeRedundantWhiteSpace</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(item,</span><span class="doxyHighlightStringLiteral">"."</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1968</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;fileName = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1969</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("Adding using declaration: found:%s:%d name=%s\n",qPrint(yyextra-&gt;fileName),yyextra-&gt;yyLineNr,qPrint(yyextra-&gt;current-&gt;name));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1970</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;section=all ? EntryType::makeUsingDir() : EntryType::makeUsingDecl();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1971</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current_root-&gt;moveToSubEntryAndRefresh(yyextra-&gt;current);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1972</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#affe329b2bcd94b04290e03afad9c97c5">initEntry</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1973</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#affe329b2bcd94b04290e03afad9c97c5">initEntry</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a0940360aa6d41fd2496603fc565e3996">removeRedundantWhiteSpace</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>.</p>

</div>
</div>

### addToString() {#af99856e2fbe8c4e1f9ddd308cc5237de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addToString (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const char * s)</td>
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



<p>Definition at line 2077 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af99856e2fbe8c4e1f9ddd308cc5237de">2077</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af99856e2fbe8c4e1f9ddd308cc5237de">addToString</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2078</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2079</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2080</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;copyString) (*yyextra-&gt;copyString) &lt;&lt; s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2081</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### addVariable() {#af6ecf9ac01a23dc21259b408a314f54a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addVariable (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 1888 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af6ecf9ac01a23dc21259b408a314f54a">1888</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/code-l/#ac9fd711b7dd6cbbefb87ab903e540b31">addVariable</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1889</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1890</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1891</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a3bb5a3fd461f68eff332a09e9e5b0e1e">setProtection</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1892</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;current_root-&gt;section.isCompound()) </span><span class="doxyHighlightComment">// mark as class variable</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1893</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1894</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;isStatic = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1895</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1896</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ac41321000a4a4f6ab696d4a6a88a4fef">addEntry</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1897</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#ac41321000a4a4f6ab696d4a6a88a4fef">addEntry</a>, <a href="#a3bb5a3fd461f68eff332a09e9e5b0e1e">setProtection</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

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



<p>Definition at line 1914 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2b4acd8f05e7bebf0528ec710692f758">1914</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a2b4acd8f05e7bebf0528ec710692f758">computeIndent</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1915</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1916</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> col=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1917</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> tabSize=<a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(TAB_SIZE);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1918</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1919</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1920</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1921</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1922</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) col++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1923</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">) col+=tabSize-(col%tabSize);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1924</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1925</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1926</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> col;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1927</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>.</p>

</div>
</div>

### docVariable() {#a1f97070341210413d4ebab8defffdcb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void docVariable (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const char * s)</td>
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



<p>Definition at line 1864 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1f97070341210413d4ebab8defffdcb8">1864</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1f97070341210413d4ebab8defffdcb8">docVariable</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1865</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1866</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1867</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;name = name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1868</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;section=EntryType::makeVariable();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1869</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;fileName  = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1870</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;startLine = yyextra-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1871</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;bodyLine  = yyextra-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1872</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;type.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1873</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a3bb5a3fd461f68eff332a09e9e5b0e1e">setProtection</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1874</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;checkDupEntry = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1875</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a3bb5a3fd461f68eff332a09e9e5b0e1e">setProtection</a>.</p>

</div>
</div>

### endOfDef() {#a4bbc5085e6314777292116922282abf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void endOfDef (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, int correction=0)</td>
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



<p>Definition at line 2064 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4bbc5085e6314777292116922282abf8">2064</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4bbc5085e6314777292116922282abf8">endOfDef</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> correction)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2065</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2066</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2067</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("endOfDef at=%d\n",yyextra-&gt;yyLineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2068</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;bodyEntry)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2069</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2070</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;bodyEntry-&gt;endBodyLine  = yyextra-&gt;yyLineNr-correction;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2071</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;bodyEntry = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2072</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2073</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a04219d02c56369b619778a94f19fd58f">newEntry</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2074</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//yyextra-&gt;insideConstructor = FALSE;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2075</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a04219d02c56369b619778a94f19fd58f">newEntry</a>.</p>

</div>
</div>

### findPackageScope() {#a57ef3ef713c786fffec737ed9556ed63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString findPackageScope (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName)</td>
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



<p>Definition at line 1956 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a57ef3ef713c786fffec737ed9556ed63">1956</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a57ef3ef713c786fffec737ed9556ed63">findPackageScope</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1957</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1958</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1959</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fi(fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1960</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a71aab00668419c1f9fdfeecf87e0d59f">findPackageScopeFromPath</a>(yyscanner,fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">dirPath</a>(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">).c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1961</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">FileInfo::dirPath</a>, <a href="#a71aab00668419c1f9fdfeecf87e0d59f">findPackageScopeFromPath</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>


<p>Referenced by <a href="#a8a8ff9e246514b6146a187f9648c2736">parseMain</a>.</p>

</div>
</div>

### findPackageScopeFromPath() {#a71aab00668419c1f9fdfeecf87e0d59f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString findPackageScopeFromPath (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; path)</td>
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



<p>Definition at line 1929 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a71aab00668419c1f9fdfeecf87e0d59f">1929</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a71aab00668419c1f9fdfeecf87e0d59f">findPackageScopeFromPath</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;path)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1930</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1931</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1932</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = yyextra-&gt;packageNameCache.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(path.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1933</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=yyextra-&gt;packageNameCache.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1934</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1935</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(it-&gt;second);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1936</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1937</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> pf(path.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()+</span><span class="doxyHighlightStringLiteral">"/__init__.py"</span><span class="doxyHighlight">); </span><span class="doxyHighlightComment">// found package initialization file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1938</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pf.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1939</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1940</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=path.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1941</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1942</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1943</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> scope = <a href="#a71aab00668419c1f9fdfeecf87e0d59f">findPackageScopeFromPath</a>(yyscanner,path.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(i));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1944</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!scope.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1945</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1946</span><span class="doxyLineContent"><span class="doxyHighlight">        scope+=</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1947</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1948</span><span class="doxyLineContent"><span class="doxyHighlight">      scope+=path.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(i+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1949</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;packageNameCache.emplace(path.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),scope.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1950</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> scope;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1951</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1952</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1953</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1954</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">FileInfo::exists</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="#a71aab00668419c1f9fdfeecf87e0d59f">findPackageScopeFromPath</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>


<p>Referenced by <a href="#a57ef3ef713c786fffec737ed9556ed63">findPackageScope</a> and <a href="#a71aab00668419c1f9fdfeecf87e0d59f">findPackageScopeFromPath</a>.</p>

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



<p>Definition at line 164 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acb5f8818546103e3b804ab8606b52c4a">164</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#acb5f8818546103e3b804ab8606b52c4a">getLexerFILE</a>() {</span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> __FILE__;}</span></span></div>

</div>

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



<p>Definition at line 2009 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa6551ba715391111267db3d5e8a3ead4">2009</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;doc,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> brief)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2010</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2011</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2012</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("handleCommentBlock(doc=[%s] brief=%d yyextra-&gt;docBlockInBody=%d yyextra-&gt;docBlockJavaStyle=%d\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2013</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//    qPrint(doc),brief,yyextra-&gt;docBlockInBody,yyextra-&gt;docBlockJavaStyle);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2014</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2015</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// TODO: Fix me</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2016</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;docBlockInBody=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2017</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2018</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;current-&gt;doc.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2019</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2020</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;doc=yyextra-&gt;current-&gt;doc.stripWhiteSpace()+</span><span class="doxyHighlightStringLiteral">"\n\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2021</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2022</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;docBlockInBody &amp;&amp; yyextra-&gt;previous &amp;&amp; !yyextra-&gt;previous-&gt;doc.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2023</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2024</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;previous-&gt;doc=yyextra-&gt;previous-&gt;doc.stripWhiteSpace()+</span><span class="doxyHighlightStringLiteral">"\n\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2025</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2026</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2027</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> position = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2028</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> needsEntry = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2029</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr = brief ? yyextra-&gt;current-&gt;briefLine : yyextra-&gt;current-&gt;docLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2030</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/markdown">Markdown</a> markdown(yyextra-&gt;fileName,lineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2031</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/commentscan-h/#abae3f4527720c3a0368e313ea4a5e575">GuardedSectionStack</a> guards;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2032</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> strippedDoc = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2c01679fba857523a2ffe9007352e3bf">stripIndentation</a>(doc,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2033</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("stippedDoc=[%s]\n",qPrint(strippedDoc));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2034</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> processedDoc = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(MARKDOWN_SUPPORT) ? markdown.<a href="/web-doxygen/docs/api/classes/markdown/#ad40652cc4db61282f2b0ef5202927d10">process</a>(strippedDoc,lineNr) : strippedDoc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2035</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (yyextra-&gt;commentScanner.parseCommentBlock(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2036</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;thisParser,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2037</span><span class="doxyLineContent"><span class="doxyHighlight">        (yyextra-&gt;docBlockInBody &amp;&amp; yyextra-&gt;previous) ? yyextra-&gt;previous.get() : yyextra-&gt;current.get(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2038</span><span class="doxyLineContent"><span class="doxyHighlight">        processedDoc, </span><span class="doxyHighlightComment">// text</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2039</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;fileName,   </span><span class="doxyHighlightComment">// file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2040</span><span class="doxyLineContent"><span class="doxyHighlight">        lineNr,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2041</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;docBlockInBody ? <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> : brief,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2042</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;docBlockJavaStyle, </span><span class="doxyHighlightComment">// javadoc style // or FALSE,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2043</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;docBlockInBody,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2044</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;protection,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2045</span><span class="doxyLineContent"><span class="doxyHighlight">        position,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2046</span><span class="doxyLineContent"><span class="doxyHighlight">        needsEntry,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2047</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(MARKDOWN_SUPPORT),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2048</span><span class="doxyLineContent"><span class="doxyHighlight">        &amp;guards</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2049</span><span class="doxyLineContent"><span class="doxyHighlight">       )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2050</span><span class="doxyLineContent"><span class="doxyHighlight">     ) </span><span class="doxyHighlightComment">// need to start a new entry</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2051</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2052</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (needsEntry)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2053</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2054</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a04219d02c56369b619778a94f19fd58f">newEntry</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2055</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2056</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2057</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (needsEntry)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2058</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2059</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a04219d02c56369b619778a94f19fd58f">newEntry</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2060</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2061</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2062</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a04219d02c56369b619778a94f19fd58f">newEntry</a>, <a href="/web-doxygen/docs/api/classes/markdown/#ad40652cc4db61282f2b0ef5202927d10">Markdown::process</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2c01679fba857523a2ffe9007352e3bf">stripIndentation</a>.</p>

</div>
</div>

### incLineNr() {#a062cea4ebaac0ec4861bdf89dbde1b00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void incLineNr (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 1986 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a062cea4ebaac0ec4861bdf89dbde1b00">1986</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1987</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1988</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1989</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr,</span><span class="doxyHighlightStringLiteral">"yyextra-&gt;yyLineNr=%d\n"</span><span class="doxyHighlight">,yyextra-&gt;yyLineNr));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1990</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;yyLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1991</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>.</p>

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



<p>Definition at line 1763 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#affe329b2bcd94b04290e03afad9c97c5">1763</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#affe329b2bcd94b04290e03afad9c97c5">initEntry</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1764</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1765</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1766</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//yyextra-&gt;current-&gt;python = TRUE;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1767</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;protection = yyextra-&gt;protection ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1768</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;mtype      = yyextra-&gt;mtype;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1769</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;virt       = yyextra-&gt;virt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1770</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;isStatic   = yyextra-&gt;isStatic;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1771</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;lang       = SrcLangExt::Python;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1772</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;type.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1773</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;name.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1774</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;initializer.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1775</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;commentScanner.initGroupInfo(yyextra-&gt;current.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1776</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;isStatic = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1777</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>.</p>

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



<p>Definition at line 1752 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a451cff71879d11897907cc8c2102bdcb">1752</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a451cff71879d11897907cc8c2102bdcb">initParser</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1753</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1754</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1755</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;protection = Protection::Public;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1756</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;mtype = MethodTypes::Method;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1757</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;isStatic = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1758</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;virt = Specifier::Normal;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1759</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;previous = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1760</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;packageCommentAllowed = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1761</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### initSpecialBlock() {#a22addf63e54e56357d7a2691022828e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void initSpecialBlock (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 2109 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a22addf63e54e56357d7a2691022828e1">2109</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a22addf63e54e56357d7a2691022828e1">initSpecialBlock</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2110</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2111</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2112</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;docBlockContext   = YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2113</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;docBlockInBody    = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2114</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;docBlockJavaStyle = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2115</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;docBrief = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2116</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;docBlock.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2117</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;commentIndent = yyextra-&gt;curIndent;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2118</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a3f8584604e877b6eb570db94e3692a92">startCommentBlock</a>(yyscanner,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2119</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a3f8584604e877b6eb570db94e3692a92">startCommentBlock</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### initTriDoubleQuoteBlock() {#aa1fd664818291e7a90ed2ba46a0f44a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void initTriDoubleQuoteBlock (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 2083 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa1fd664818291e7a90ed2ba46a0f44a7">2083</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa1fd664818291e7a90ed2ba46a0f44a7">initTriDoubleQuoteBlock</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2084</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2085</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2086</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;docBlockContext   = YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2087</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;docBlockInBody    = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2088</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;docBlockJavaStyle = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2089</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;docBlockSpecial   = yytext[strlen(yytext) - 1]==</span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight"> || !<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(PYTHON_DOCSTRING);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2090</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;docBlock.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2091</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;commentIndent = yyextra-&gt;curIndent;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2092</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;doubleQuote = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2093</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a3f8584604e877b6eb570db94e3692a92">startCommentBlock</a>(yyscanner,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2094</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a3f8584604e877b6eb570db94e3692a92">startCommentBlock</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### initTriSingleQuoteBlock() {#a2aa292ec6b6ea81860b3d9b00405d1cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void initTriSingleQuoteBlock (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 2096 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2aa292ec6b6ea81860b3d9b00405d1cb">2096</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2aa292ec6b6ea81860b3d9b00405d1cb">initTriSingleQuoteBlock</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2097</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2098</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2099</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;docBlockContext   = YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2100</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;docBlockInBody    = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2101</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;docBlockJavaStyle = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2102</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;docBlockSpecial   = yytext[strlen(yytext) - 1]==</span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight"> || !<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(PYTHON_DOCSTRING);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2103</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;docBlock.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2104</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;commentIndent = yyextra-&gt;curIndent;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2105</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;doubleQuote = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2106</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a3f8584604e877b6eb570db94e3692a92">startCommentBlock</a>(yyscanner,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2107</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a3f8584604e877b6eb570db94e3692a92">startCommentBlock</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### lineCount() {#a6e782ca00a48833dff52b4b5f0a1a147}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void lineCount (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 1976 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6e782ca00a48833dff52b4b5f0a1a147">1976</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#a6256e57feb94db36e0dd7c3c83c9180a">lineCount</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1977</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1978</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1979</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr,</span><span class="doxyHighlightStringLiteral">"yyextra-&gt;yyLineNr=%d\n"</span><span class="doxyHighlight">,yyextra-&gt;yyLineNr));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1980</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p = yytext; *p; ++p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1981</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1982</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;yyLineNr += (*p == </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1983</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1984</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>.</p>

</div>
</div>

### newEntry() {#a04219d02c56369b619778a94f19fd58f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void newEntry (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 1779 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a04219d02c56369b619778a94f19fd58f">1779</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a04219d02c56369b619778a94f19fd58f">newEntry</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1780</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1781</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1782</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;current-&gt;name.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1783</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1784</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#affe329b2bcd94b04290e03afad9c97c5">initEntry</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1785</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1786</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1787</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> found = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1788</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;checkDupEntry)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1789</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1790</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;v : yyextra-&gt;current_root-&gt;children())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1791</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1792</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("candidate %s&lt;-&gt;%s section=%s!\n",qPrint(v-&gt;name),qPrint(yyextra-&gt;current-&gt;name), v-&gt;section.to_string().c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1793</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (v-&gt;name==yyextra-&gt;current-&gt;name &amp;&amp; v-&gt;section==yyextra-&gt;current-&gt;section) </span><span class="doxyHighlightComment">// name is already added, don't add it again</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1794</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1795</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (v-&gt;doc.isEmpty() &amp;&amp; !yyextra-&gt;current-&gt;doc.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1796</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1797</span><span class="doxyLineContent"><span class="doxyHighlight">          v-&gt;doc       = yyextra-&gt;current-&gt;doc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1798</span><span class="doxyLineContent"><span class="doxyHighlight">          v-&gt;docLine   = yyextra-&gt;current-&gt;docLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1799</span><span class="doxyLineContent"><span class="doxyHighlight">          v-&gt;docFile   = yyextra-&gt;current-&gt;docFile;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1800</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1801</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (v-&gt;brief.isEmpty() &amp;&amp; !yyextra-&gt;current-&gt;brief.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1802</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1803</span><span class="doxyLineContent"><span class="doxyHighlight">          v-&gt;brief     = yyextra-&gt;current-&gt;brief;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1804</span><span class="doxyLineContent"><span class="doxyHighlight">          v-&gt;briefLine = yyextra-&gt;current-&gt;briefLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1805</span><span class="doxyLineContent"><span class="doxyHighlight">          v-&gt;briefFile = yyextra-&gt;current-&gt;briefFile;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1806</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1807</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (v-&gt;type.isEmpty() &amp;&amp; !yyextra-&gt;current-&gt;type.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1808</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1809</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//printf("copying type '%s' from '%s' to '%s'\n",qPrint(yyextra-&gt;current-&gt;type),qPrint(yyextra-&gt;current-&gt;name),qPrint(v-&gt;name));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1810</span><span class="doxyLineContent"><span class="doxyHighlight">          v-&gt;type      = yyextra-&gt;current-&gt;type;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1811</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1812</span><span class="doxyLineContent"><span class="doxyHighlight">        found=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1813</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1814</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1815</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1816</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1817</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!found)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1818</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1819</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;previous = yyextra-&gt;current;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1820</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current_root-&gt;moveToSubEntryAndRefresh(yyextra-&gt;current);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1821</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1822</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#affe329b2bcd94b04290e03afad9c97c5">initEntry</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1823</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#affe329b2bcd94b04290e03afad9c97c5">initEntry</a>.</p>


<p>Referenced by <a href="#a4bbc5085e6314777292116922282abf8">endOfDef</a>, <a href="#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#aae0b93eceac30fcc7b8bbb6795b588a2">handleParametersCommentBlocks</a> and <a href="#a851aa07f7276b7e8f4b12d2592d2eb39">newVariable</a>.</p>

</div>
</div>

### newFunction() {#ae986dc4d2214f2b90b824521c25a2a5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void newFunction (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 1899 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae986dc4d2214f2b90b824521c25a2a5c">1899</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae986dc4d2214f2b90b824521c25a2a5c">newFunction</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1900</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1901</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1902</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;current-&gt;name.startsWith(</span><span class="doxyHighlightStringLiteral">"__"</span><span class="doxyHighlight">) &amp;&amp; yyextra-&gt;current-&gt;name.endsWith(</span><span class="doxyHighlightStringLiteral">"__"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1903</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1904</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// special method name, see</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1905</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// http://docs.python.org/ref/specialnames.html</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1906</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;protection=Protection::Public;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1907</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1908</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1909</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1910</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a3bb5a3fd461f68eff332a09e9e5b0e1e">setProtection</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1911</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1912</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a3bb5a3fd461f68eff332a09e9e5b0e1e">setProtection</a>.</p>

</div>
</div>

### newVariable() {#a851aa07f7276b7e8f4b12d2592d2eb39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void newVariable (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 1877 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a851aa07f7276b7e8f4b12d2592d2eb39">1877</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a851aa07f7276b7e8f4b12d2592d2eb39">newVariable</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1878</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1879</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1880</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a3bb5a3fd461f68eff332a09e9e5b0e1e">setProtection</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1881</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;current_root-&gt;section.isCompound()) </span><span class="doxyHighlightComment">// mark as class variable</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1882</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1883</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;isStatic = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1884</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1885</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a04219d02c56369b619778a94f19fd58f">newEntry</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1886</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a04219d02c56369b619778a94f19fd58f">newEntry</a>, <a href="#a3bb5a3fd461f68eff332a09e9e5b0e1e">setProtection</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### parseCompounds() {#af3d71282d72dd7136124a4c7405f6b28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void parseCompounds (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt; rt)</td>
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



<p>Definition at line 2155 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af3d71282d72dd7136124a4c7405f6b28">2155</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af3d71282d72dd7136124a4c7405f6b28">parseCompounds</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,std::shared_ptr&lt;Entry&gt; rt)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2156</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2157</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2158</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("parseCompounds(%s)\n",qPrint(rt-&gt;name));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2159</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0; i&lt;rt-&gt;children().size(); ++i)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2160</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2161</span><span class="doxyLineContent"><span class="doxyHighlight">    std::shared_ptr&lt;Entry&gt; ce = rt-&gt;children()[i];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2162</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ce-&gt;program.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2163</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2164</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//fprintf(stderr,"parseCompounds: -- %s (line %d) ---------\n%s\n---------------\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2165</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//  qPrint(ce-&gt;name), ce-&gt;bodyLine, qPrint(ce-&gt;program));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2166</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// init scanner state</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2167</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;programStr = ce-&gt;program.str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2168</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;inputString = yyextra-&gt;programStr.data();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2169</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;inputPosition = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2170</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;firstPass     = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2171</span><span class="doxyLineContent"><span class="doxyHighlight">      pyscannerYYrestart( </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, yyscanner );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2172</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ce-&gt;section.isCompound())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2173</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2174</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;specialBlock = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2175</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;current_root = ce;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2176</span><span class="doxyLineContent"><span class="doxyHighlight">        BEGIN( <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">Search</a> );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2177</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2178</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ce-&gt;parent())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2179</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2180</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;current_root = rt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2181</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("Searching for member variables in %s parent=%s\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2182</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//    qPrint(ce-&gt;name),qPrint(ce-&gt;parent-&gt;name));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2183</span><span class="doxyLineContent"><span class="doxyHighlight">        BEGIN( SearchMemVars );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2184</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2185</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;fileName = ce-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2186</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;yyLineNr   = ce-&gt;bodyLine ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2187</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;current = std::make_shared&lt;Entry&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2188</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#affe329b2bcd94b04290e03afad9c97c5">initEntry</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2189</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2190</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;checkDupEntry = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2191</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2192</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name = ce-&gt;name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2193</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;commentScanner.enterCompound(yyextra-&gt;fileName,yyextra-&gt;yyLineNr,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2194</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2195</span><span class="doxyLineContent"><span class="doxyHighlight">      pyscannerYYlex(yyscanner) ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2196</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;lexInit=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2197</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2198</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;programStr.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2199</span><span class="doxyLineContent"><span class="doxyHighlight">      ce-&gt;program.str(std::string());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2200</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2201</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;commentScanner.leaveCompound(yyextra-&gt;fileName,yyextra-&gt;yyLineNr,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2202</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2203</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2204</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af3d71282d72dd7136124a4c7405f6b28">parseCompounds</a>(yyscanner,ce);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2205</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2206</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#affe329b2bcd94b04290e03afad9c97c5">initEntry</a>, <a href="#af3d71282d72dd7136124a4c7405f6b28">parseCompounds</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">Search</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/scanner-l/#a3383c871b9fd5e4b1cf4a549de88a1f3">parseCompounds</a>, <a href="#af3d71282d72dd7136124a4c7405f6b28">parseCompounds</a>, <a href="#a8a8ff9e246514b6146a187f9648c2736">parseMain</a> and <a href="/web-doxygen/docs/api/files/src/scanner-l/#a434a1f775b7fe0a37ad69ba2499cfdfb">parseMain</a>.</p>

</div>
</div>

### parseMain() {#a8a8ff9e246514b6146a187f9648c2736}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void parseMain (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const char * fileBuf, const std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt; &amp; rt)</td>
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



<p>Definition at line 2211 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8a8ff9e246514b6146a187f9648c2736">2211</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a4481d3eae9a04af883d868f23c4cbffc">parseMain</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *fileBuf,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::shared_ptr&lt;Entry&gt; &amp;rt)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2212</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2213</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2214</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a451cff71879d11897907cc8c2102bdcb">initParser</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2215</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2216</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fileBuf==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> || fileBuf[0]==</span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2217</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2218</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputString = fileBuf;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2219</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputPosition = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2220</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2221</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;protection    = Protection::Public;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2222</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;mtype         = MethodTypes::Method;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2223</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;isStatic      = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2224</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;virt          = Specifier::Normal;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2225</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current_root  = rt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2226</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;specialBlock  = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2227</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2228</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;yyLineNr      = 1 ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2229</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;fileName      = fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2230</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;checkDupEntry = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2231</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;firstPass     = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2232</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//setContext();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2233</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Parsing file {}...\n"</span><span class="doxyHighlight">,yyextra-&gt;fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2234</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2235</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fi(fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2236</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;moduleScope = <a href="#a57ef3ef713c786fffec737ed9556ed63">findPackageScope</a>(yyscanner,fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2237</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseName=fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#aec2c36ba622c46816be190eca39b94af">baseName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2238</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (baseName!=</span><span class="doxyHighlightStringLiteral">"__init__"</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// package initializer file is not a package itself</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2239</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2240</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;moduleScope.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2241</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2242</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;moduleScope+=</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2243</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2244</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;moduleScope+=baseName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2245</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2246</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2247</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// add namespaces for each scope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2248</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> scope = yyextra-&gt;moduleScope;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2249</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startPos = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2250</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> pos = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2251</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">do</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2252</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2253</span><span class="doxyLineContent"><span class="doxyHighlight">    pos = scope.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">,startPos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2254</span><span class="doxyLineContent"><span class="doxyHighlight">    startPos=pos+2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2255</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pos==-1) pos=(int)scope.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2256</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current            = std::make_shared&lt;Entry&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2257</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#affe329b2bcd94b04290e03afad9c97c5">initEntry</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2258</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;name      = scope.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(pos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2259</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;section   = EntryType::makeNamespace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2260</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;type      = </span><span class="doxyHighlightStringLiteral">"namespace"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2261</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;fileName  = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2262</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;startLine = yyextra-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2263</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;bodyLine  = yyextra-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2264</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current_root       = yyextra-&gt;current;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2265</span><span class="doxyLineContent"><span class="doxyHighlight">    rt-&gt;moveToSubEntryAndRefresh(yyextra-&gt;current);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2266</span><span class="doxyLineContent"><span class="doxyHighlight">  } </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (pos&lt;(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)scope.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2267</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2268</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a451cff71879d11897907cc8c2102bdcb">initParser</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2269</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2270</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;commentScanner.enterFile(yyextra-&gt;fileName,yyextra-&gt;yyLineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2271</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2272</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;reset();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2273</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#affe329b2bcd94b04290e03afad9c97c5">initEntry</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2274</span><span class="doxyLineContent"><span class="doxyHighlight">  pyscannerYYrestart(</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2275</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN( <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">Search</a> );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2276</span><span class="doxyLineContent"><span class="doxyHighlight">  pyscannerYYlex(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2277</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;lexInit=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2278</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2279</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;commentScanner.leaveFile(yyextra-&gt;fileName,yyextra-&gt;yyLineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2280</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2281</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;programStr.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2282</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current_root-&gt;program.str(std::string());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2283</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2284</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af3d71282d72dd7136124a4c7405f6b28">parseCompounds</a>(yyscanner, yyextra-&gt;current_root);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2285</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/fileinfo/#aec2c36ba622c46816be190eca39b94af">FileInfo::baseName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="#a57ef3ef713c786fffec737ed9556ed63">findPackageScope</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#affe329b2bcd94b04290e03afad9c97c5">initEntry</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a451cff71879d11897907cc8c2102bdcb">initParser</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>, <a href="#af3d71282d72dd7136124a4c7405f6b28">parseCompounds</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">Search</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### parsePrototype() {#a4e7dce846ca75b58d7010c2855a84ed6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void parsePrototype (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
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



<p>Definition at line 2289 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4e7dce846ca75b58d7010c2855a84ed6">2289</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4e7dce846ca75b58d7010c2855a84ed6">parsePrototype</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2290</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2291</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2292</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("**** parsePrototype(%s) begin\n",qPrint(text));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2293</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (text.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2294</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2295</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(yyextra-&gt;fileName,yyextra-&gt;yyLineNr,</span><span class="doxyHighlightStringLiteral">"Empty prototype found!"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2296</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2297</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2298</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2299</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;specialBlock = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2300</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;packageCommentAllowed = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2301</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2302</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// save scanner state</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2303</span><span class="doxyLineContent"><span class="doxyHighlight">  YY_BUFFER_STATE orgState = YY_CURRENT_BUFFER;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2304</span><span class="doxyLineContent"><span class="doxyHighlight">  yy_switch_to_buffer(yy_create_buffer(</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#ae7e51116e747d3390e7a6cfc6532834c">YY_BUF_SIZE</a>, yyscanner), yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2305</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *orgInputString = yyextra-&gt;inputString;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2306</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> orgInputPosition = yyextra-&gt;inputPosition;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2307</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2308</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// set new string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2309</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputString = text.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2310</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputPosition = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2311</span><span class="doxyLineContent"><span class="doxyHighlight">  pyscannerYYrestart( </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, yyscanner );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2312</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2313</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN( FunctionDec );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2314</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2315</span><span class="doxyLineContent"><span class="doxyHighlight">  pyscannerYYlex(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2316</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;lexInit=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2317</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2318</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;name = yyextra-&gt;current-&gt;name.stripWhiteSpace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2319</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;current-&gt;section.isMemberDoc() &amp;&amp; yyextra-&gt;current-&gt;args.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2320</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2321</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;section = EntryType::makeVariableDoc();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2322</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2323</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2324</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// restore original scanner state</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2325</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2326</span><span class="doxyLineContent"><span class="doxyHighlight">  yy_delete_buffer(YY_CURRENT_BUFFER, yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2327</span><span class="doxyLineContent"><span class="doxyHighlight">  yy_switch_to_buffer(orgState, yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2328</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2329</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputString = orgInputString;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2330</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputPosition = orgInputPosition;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2331</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2332</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("**** parsePrototype end\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2333</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a> and <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#ae7e51116e747d3390e7a6cfc6532834c">YY_BUF_SIZE</a>.</p>

</div>
</div>

### searchFoundClass() {#a601173b4a0fe4bb62a0e4749429ee062}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void searchFoundClass (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 2141 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a601173b4a0fe4bb62a0e4749429ee062">2141</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a601173b4a0fe4bb62a0e4749429ee062">searchFoundClass</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2142</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2143</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2144</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;section = EntryType::makeClass();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2145</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;argList.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2146</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;type += </span><span class="doxyHighlightStringLiteral">"class"</span><span class="doxyHighlight"> ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2147</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;fileName  = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2148</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;startLine  = yyextra-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2149</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;bodyLine  = yyextra-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2150</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;packageCommentAllowed = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2151</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>.</p>

</div>
</div>

### searchFoundDef() {#ab61319bebda3e72e8fbde5a911cccc95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void searchFoundDef (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 2121 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab61319bebda3e72e8fbde5a911cccc95">2121</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab61319bebda3e72e8fbde5a911cccc95">searchFoundDef</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2122</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2123</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2124</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;fileName  = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2125</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;startLine = yyextra-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2126</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;bodyLine  = yyextra-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2127</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;section = EntryType::makeFunction();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2128</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;lang = SrcLangExt::Python;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2129</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;virt = Specifier::Normal;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2130</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;isStatic = yyextra-&gt;isStatic;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2131</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;mtype = yyextra-&gt;mtype = MethodTypes::Method;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2132</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;type.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2133</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;name.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2134</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;args.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2135</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;argList.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2136</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;packageCommentAllowed = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2137</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;isStatic=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2138</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("searchFoundDef at=%d\n",yyextra-&gt;yyLineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2139</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>.</p>

</div>
</div>

### setProtection() {#a3bb5a3fd461f68eff332a09e9e5b0e1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void setProtection (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 1848 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3bb5a3fd461f68eff332a09e9e5b0e1e">1848</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3bb5a3fd461f68eff332a09e9e5b0e1e">setProtection</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1849</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1850</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1851</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;current-&gt;name.isEmpty() &amp;&amp; yyextra-&gt;current-&gt;name.at(0)==</span><span class="doxyHighlightCharLiteral">'_'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1852</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1853</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;current-&gt;name.at(1)==</span><span class="doxyHighlightCharLiteral">'_'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// mark as private</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1854</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1855</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;current-&gt;protection=Protection::Private;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1856</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1857</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// mark as protected</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1858</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1859</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;current-&gt;protection=Protection::Protected;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1860</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1861</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1862</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="#af6ecf9ac01a23dc21259b408a314f54a">addVariable</a>, <a href="#a1f97070341210413d4ebab8defffdcb8">docVariable</a>, <a href="#ae986dc4d2214f2b90b824521c25a2a5c">newFunction</a> and <a href="#a851aa07f7276b7e8f4b12d2592d2eb39">newVariable</a>.</p>

</div>
</div>

### startCommentBlock() {#ae479adb32c06d965a4f4baee921f0c5a}

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



<p>Definition at line 1994 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae479adb32c06d965a4f4baee921f0c5a">1994</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a3f8584604e877b6eb570db94e3692a92">startCommentBlock</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> brief)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1995</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1996</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1997</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (brief)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1998</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1999</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;briefFile = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2000</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;briefLine = yyextra-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2001</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2002</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2003</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2004</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;docFile = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2005</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;docLine = yyextra-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2006</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2007</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

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



<p>Definition at line 128 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>

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



<p>Definition at line 273 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1d80d8ed8c19744ed31163f6e7525e54">273</a></span><span class="doxyLineContent"><span class="doxyHighlight">%%</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/* ------------ Function recognition rules -------------- */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Search&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">^{B}"def"{BB}</span><span class="doxyHighlight">       { </span><span class="doxyHighlightComment">// start of a function/method definition with indent</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr,</span><span class="doxyHighlightStringLiteral">"Found def at %d\n"</span><span class="doxyHighlight">,yyextra-&gt;yyLineNr));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;indent=<a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a2b4acd8f05e7bebf0528ec710692f758">computeIndent</a>(yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#ab61319bebda3e72e8fbde5a911cccc95">searchFoundDef</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN( FunctionDec );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">^{B}"async"{BB}"def"{BB}</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// start of an async function/method definition with indent</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr,</span><span class="doxyHighlightStringLiteral">"Found async def at %d\n"</span><span class="doxyHighlight">,yyextra-&gt;yyLineNr));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;indent=<a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a2b4acd8f05e7bebf0528ec710692f758">computeIndent</a>(yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#ab61319bebda3e72e8fbde5a911cccc95">searchFoundDef</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN( FunctionDec );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"def"{BB}</span><span class="doxyHighlight">           { </span><span class="doxyHighlightComment">// start of a function/method definition</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#ab61319bebda3e72e8fbde5a911cccc95">searchFoundDef</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN( FunctionDec );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"async"{BB}"def"{BB}</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// start of a function/method definition</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#ab61319bebda3e72e8fbde5a911cccc95">searchFoundDef</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN( FunctionDec );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">^{B}"class"{BB}</span><span class="doxyHighlight">    { </span><span class="doxyHighlightComment">// start of a class definition with indent</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr,</span><span class="doxyHighlightStringLiteral">"Found class at %d\n"</span><span class="doxyHighlight">,yyextra-&gt;yyLineNr));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;indent=<a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a2b4acd8f05e7bebf0528ec710692f758">computeIndent</a>(yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#a601173b4a0fe4bb62a0e4749429ee062">searchFoundClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN( ClassDec ) ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"class"{BB}</span><span class="doxyHighlight">        {  </span><span class="doxyHighlightComment">// start of a class definition</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#a601173b4a0fe4bb62a0e4749429ee062">searchFoundClass</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN( ClassDec ) ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">^{B}"from"{BB}</span><span class="doxyHighlight">    |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"from"{BB}</span><span class="doxyHighlight">        { </span><span class="doxyHighlightComment">// start of an from import</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;packageCommentAllowed = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN( FromMod );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">^{B}"import"{BB}</span><span class="doxyHighlight">  |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"import"{BB}</span><span class="doxyHighlight">      { </span><span class="doxyHighlightComment">// start of an import statement</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;packageCommentAllowed = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN( Import );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">^{B}{IDENTIFIER}/{B}"="{B}"property"</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// property</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;section   = EntryType::makeVariable();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;mtype     = MethodTypes::Property;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;name      = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;fileName  = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;startLine = yyextra-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;bodyLine  = yyextra-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;packageCommentAllowed = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN(VariableDec);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">^{B}{IDENTIFIER}/{B}"="[^=]</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// variable</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;searchCount&gt;0) REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;indent=<a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a2b4acd8f05e7bebf0528ec710692f758">computeIndent</a>(yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;section   = EntryType::makeVariable();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;name      = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;fileName  = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;startLine = yyextra-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;bodyLine  = yyextra-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;packageCommentAllowed = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN(VariableDec);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">^{B}{IDENTIFIER}/{B}":"</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// variable</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;searchCount&gt;0) REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> ==</span><span class="doxyHighlightStringLiteral">"try"</span><span class="doxyHighlight"> || </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> == </span><span class="doxyHighlightStringLiteral">"else"</span><span class="doxyHighlight"> || </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> == </span><span class="doxyHighlightStringLiteral">"except"</span><span class="doxyHighlight"> || </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> == </span><span class="doxyHighlightStringLiteral">"finally"</span><span class="doxyHighlight">) REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;indent=<a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a2b4acd8f05e7bebf0528ec710692f758">computeIndent</a>(yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">347</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;section   = EntryType::makeVariable();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;name      = id;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;fileName  = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;startLine = yyextra-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">351</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;bodyLine  = yyextra-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;packageCommentAllowed = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN(VariableDec);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">355</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">{B}{IDENTIFIER}/({B},{B}{IDENTIFIER})*{B}")"*{B}"="[^=]</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// list of variables, we cannot place the default value</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">356</span><span class="doxyLineContent"><span class="doxyHighlight">                                                               </span><span class="doxyHighlightComment">// so we will skip it later on in a general rule</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">                                                               </span><span class="doxyHighlightComment">// Also note ")" this is to catch also (a,b). the "("</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">                                                               </span><span class="doxyHighlightComment">// is caught in the rule: [(], the ")" will be handled in [)]</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;searchCount&gt;1) REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;indent=<a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a2b4acd8f05e7bebf0528ec710692f758">computeIndent</a>(yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">361</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;section   = EntryType::makeVariable();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;name      = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;fileName  = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;startLine = yyextra-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;bodyLine  = yyextra-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">366</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;packageCommentAllowed = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">367</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="/web-doxygen/docs/api/files/src/code-l/#ac9fd711b7dd6cbbefb87ab903e540b31">addVariable</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">              { </span><span class="doxyHighlightComment">// start of a single quoted string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;stringContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;copyString=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;packageCommentAllowed = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN( SingleQuoteString );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">             { </span><span class="doxyHighlightComment">// start of a double quoted string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;stringContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;copyString=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;packageCommentAllowed = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN( DoubleQuoteString );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"@staticmethod"</span><span class="doxyHighlight">   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;isStatic=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"@"{SCOPE}"("</span><span class="doxyHighlight">     { </span><span class="doxyHighlightComment">// decorator</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#a6256e57feb94db36e0dd7c3c83c9180a">lineCount</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;decoratorRound = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;copyString=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN( Decorator );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"@"{SCOPE}</span><span class="doxyHighlight">        { </span><span class="doxyHighlightComment">// decorator</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#a6256e57feb94db36e0dd7c3c83c9180a">lineCount</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{SCRIPTCOMMENT}</span><span class="doxyHighlight">   { </span><span class="doxyHighlightComment">// Unix type script comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;yyLineNr != 1) REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{POUNDCOMMENT}</span><span class="doxyHighlight">    { </span><span class="doxyHighlightComment">// normal comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightComment">// issue 9672</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightComment">//yyextra-&gt;packageCommentAllowed = FALSE;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{IDENTIFIER}</span><span class="doxyHighlight">      { </span><span class="doxyHighlightComment">// some other identifier</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;packageCommentAllowed = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">402</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">^{BB}</span><span class="doxyHighlight">             {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;curIndent=<a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a2b4acd8f05e7bebf0528ec710692f758">computeIndent</a>(yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">405</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">406</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">407</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{NEWLINE}+</span><span class="doxyHighlight">        { </span><span class="doxyHighlightComment">// new line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">408</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#a6256e57feb94db36e0dd7c3c83c9180a">lineCount</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">409</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">411</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{TRIDOUBLEQUOTE}</span><span class="doxyHighlight">  { </span><span class="doxyHighlightComment">// start of a comment block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">412</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#aa1fd664818291e7a90ed2ba46a0f44a7">initTriDoubleQuoteBlock</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">413</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN(TripleComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">414</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">415</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{TRISINGLEQUOTE}</span><span class="doxyHighlight">  { </span><span class="doxyHighlightComment">// start of a comment block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">417</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#a2aa292ec6b6ea81860b3d9b00405d1cb">initTriSingleQuoteBlock</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">418</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN(TripleComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">419</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">421</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{B}{STARTDOCSYMS}/[^#]</span><span class="doxyHighlight">    {  </span><span class="doxyHighlightComment">// start of a special comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">422</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;curIndent=<a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a2b4acd8f05e7bebf0528ec710692f758">computeIndent</a>(yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">423</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;packageCommentAllowed = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">424</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#a22addf63e54e56357d7a2691022828e1">initSpecialBlock</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">425</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN(SpecialComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">426</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">427</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">[(]</span><span class="doxyHighlight">               { </span><span class="doxyHighlightComment">// we have to do something with (</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">428</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;searchCount++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">429</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">430</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">[)]</span><span class="doxyHighlight">               { </span><span class="doxyHighlightComment">// we have to do something with )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">431</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;searchCount&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">432</span><span class="doxyLineContent"><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">433</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;searchCount--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">434</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">435</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"="</span><span class="doxyHighlight">               {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;doc.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;brief.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">439</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{IDENTIFIER}</span><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">441</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">442</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">[^\n]</span><span class="doxyHighlight">             { </span><span class="doxyHighlightComment">// any other character...</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightComment">// This is the major default</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightComment">// that should catch everything</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightComment">// else in Body.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">446</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">447</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FromMod&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"."</span><span class="doxyHighlight">                 { </span><span class="doxyHighlightComment">// python3 style imports</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">{IDENTIFIER}({B}"."{B}{IDENTIFIER})*</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// from package import</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;packageName=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"import"{B}</span><span class="doxyHighlight">         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN(FromModItem);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">457</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">\n</span><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN(<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">Search</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">{B}</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">.</span><span class="doxyHighlight">                   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">                        unput(*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN(<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">Search</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FromModItem&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"*"</span><span class="doxyHighlight">           { </span><span class="doxyHighlightComment">// import all</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">                  <a href="#a3b2171b8a9cdc055bd41d0181094f27a">addFrom</a>(yyscanner,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">                  BEGIN(<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">Search</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlight">                }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">{IDENTIFIER}/{B}","{B}</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">                  <a href="#a3b2171b8a9cdc055bd41d0181094f27a">addFrom</a>(yyscanner,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span><span class="doxyLineContent"><span class="doxyHighlight">                }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">{IDENTIFIER}/{B}")"</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">479</span><span class="doxyLineContent"><span class="doxyHighlight">                  <a href="#a3b2171b8a9cdc055bd41d0181094f27a">addFrom</a>(yyscanner,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span><span class="doxyLineContent"><span class="doxyHighlight">                }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">{IDENTIFIER}</span><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">                  <a href="#a3b2171b8a9cdc055bd41d0181094f27a">addFrom</a>(yyscanner,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;importTuple)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">                    BEGIN(<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">Search</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">                  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">                }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">\n</span><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">                  <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;importTuple)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">                    BEGIN(<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">Search</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">                  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">                }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">{B}</span><span class="doxyHighlight">           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">                }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"("</span><span class="doxyHighlight">           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">                  yyextra-&gt;importTuple=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlight">                }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">")"</span><span class="doxyHighlight">           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span><span class="doxyLineContent"><span class="doxyHighlight">                  yyextra-&gt;importTuple=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">                  BEGIN(<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">Search</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">                }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight">           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">                }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"\\"{B}\n</span><span class="doxyHighlight">     { </span><span class="doxyHighlightComment">// line continuation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">                  <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">                }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">.</span><span class="doxyHighlight">             {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlight">                  unput(*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlight">                  BEGIN(<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">Search</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span><span class="doxyLineContent"><span class="doxyHighlight">                }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">513</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">514</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">515</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Import&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">516</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">{IDENTIFIER}({B}"."{B}{IDENTIFIER})*</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">517</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;name=<a href="/web-doxygen/docs/api/files/src/util-cpp/#a0940360aa6d41fd2496603fc565e3996">removeRedundantWhiteSpace</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(yytext,</span><span class="doxyHighlightStringLiteral">"."</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">518</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;fileName = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightComment">//printf("Adding using declaration: found:%s:%d name=%s\n",qPrint(yyextra-&gt;fileName),yyextra-&gt;yyLineNr,qPrint(yyextra-&gt;current-&gt;name));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;section=EntryType::makeUsingDecl();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">521</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current_root-&gt;moveToSubEntryAndRefresh(yyextra-&gt;current);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#affe329b2bcd94b04290e03afad9c97c5">initEntry</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN(<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">Search</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">525</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">\n</span><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">526</span><span class="doxyLineContent"><span class="doxyHighlight">                  <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">527</span><span class="doxyLineContent"><span class="doxyHighlight">                  BEGIN(<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">Search</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">528</span><span class="doxyLineContent"><span class="doxyHighlight">                }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">529</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">{B}</span><span class="doxyHighlight">           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">530</span><span class="doxyLineContent"><span class="doxyHighlight">                }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">531</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">.</span><span class="doxyHighlight">             {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">532</span><span class="doxyLineContent"><span class="doxyHighlight">                  unput(*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">533</span><span class="doxyLineContent"><span class="doxyHighlight">                  BEGIN(<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">Search</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">534</span><span class="doxyLineContent"><span class="doxyHighlight">                }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">535</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">536</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">537</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SearchMemVars&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">538</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">("cls"|"self")"."{IDENTIFIER}/{B}[,)]</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">539</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s = strchr(yytext,</span><span class="doxyHighlightCharLiteral">'.'</span><span class="doxyHighlight">); s++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">540</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr,</span><span class="doxyHighlightStringLiteral">"Found instance method variable %s in %s at %d\n"</span><span class="doxyHighlight">,s,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(yyextra-&gt;current_root-&gt;name.data(),yyextra-&gt;yyLineNr)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">541</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#a1f97070341210413d4ebab8defffdcb8">docVariable</a>(yyscanner,s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">542</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#ac41321000a4a4f6ab696d4a6a88a4fef">addEntry</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">543</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">544</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">("cls"|"self")"."{IDENTIFIER}/{B}"="</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">545</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s = strchr(yytext,</span><span class="doxyHighlightCharLiteral">'.'</span><span class="doxyHighlight">); s++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">546</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr,</span><span class="doxyHighlightStringLiteral">"Found instance method variable %s in %s at %d\n"</span><span class="doxyHighlight">,s,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(yyextra-&gt;current_root-&gt;name.data(),yyextra-&gt;yyLineNr)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">547</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#a1f97070341210413d4ebab8defffdcb8">docVariable</a>(yyscanner,s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">548</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN( SearchSkipValue  );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">549</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">550</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">("cls"|"self")"."{IDENTIFIER}/{B}":"</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// type hint</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">551</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s = strchr(yytext,</span><span class="doxyHighlightCharLiteral">'.'</span><span class="doxyHighlight">); s++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">552</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr,</span><span class="doxyHighlightStringLiteral">"Found instance method variable %s in %s at %d\n"</span><span class="doxyHighlight">,s,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(yyextra-&gt;current_root-&gt;name.data(),yyextra-&gt;yyLineNr)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">553</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#a1f97070341210413d4ebab8defffdcb8">docVariable</a>(yyscanner,s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">554</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN(TypeHint);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">555</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">556</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{TRIDOUBLEQUOTE}</span><span class="doxyHighlight">  { </span><span class="doxyHighlightComment">// start of a comment block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">557</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#aa1fd664818291e7a90ed2ba46a0f44a7">initTriDoubleQuoteBlock</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">558</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN(TripleComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">559</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">560</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">561</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{TRISINGLEQUOTE}</span><span class="doxyHighlight">  { </span><span class="doxyHighlightComment">// start of a comment block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#a2aa292ec6b6ea81860b3d9b00405d1cb">initTriSingleQuoteBlock</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">563</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN(TripleComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">566</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{STARTDOCSYMS}/[^#]</span><span class="doxyHighlight">    {  </span><span class="doxyHighlightComment">// start of a special comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">567</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#a22addf63e54e56357d7a2691022828e1">initSpecialBlock</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">568</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN(SpecialComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">569</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">570</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{POUNDCOMMENT}</span><span class="doxyHighlight">    { </span><span class="doxyHighlightComment">// #</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">571</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">572</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">               { </span><span class="doxyHighlightComment">// start of a single quoted string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;stringContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;copyString=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">575</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN( SingleQuoteString );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">576</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">577</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">              { </span><span class="doxyHighlightComment">// start of a double quoted string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">578</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;stringContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;copyString=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN( DoubleQuoteString );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">\n</span><span class="doxyHighlight">                { <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(yyscanner); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"="</span><span class="doxyHighlight">               {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">584</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;doc.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;brief.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">586</span><span class="doxyLineContent"><span class="doxyHighlight">                        unput(*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">587</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN( SearchSkipValue  );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">589</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{IDENTIFIER}</span><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// identifiers</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">590</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">[^'"\.#a-z_A-Z=\n]+</span><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// other uninteresting stuff</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">591</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">.</span><span class="doxyHighlight">                 </span><span class="doxyHighlightComment">// anything else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">592</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">593</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;TypeHint&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight">                 { </span><span class="doxyHighlightComment">// skip over start of type hint</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;braceCount=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"("|"["|"{"</span><span class="doxyHighlight">         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;current-&gt;type+=*yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;braceCount++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">601</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">602</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">")"|"]"|"}"</span><span class="doxyHighlight">         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">603</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;current-&gt;type+=*yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">604</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;braceCount--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">                 { </span><span class="doxyHighlightComment">// start of a single quoted string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;stringContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;copyString=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN( SingleQuoteString );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">                { </span><span class="doxyHighlightComment">// start of a double quoted string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;stringContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">613</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;copyString=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">614</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN( DoubleQuoteString );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">615</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">616</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"="</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;braceCount==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">618</span><span class="doxyLineContent"><span class="doxyHighlight">                          { </span><span class="doxyHighlightComment">// end of the type hint</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">619</span><span class="doxyLineContent"><span class="doxyHighlight">                            yyextra-&gt;current-&gt;type = yyextra-&gt;current-&gt;type.stripWhiteSpace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">620</span><span class="doxyLineContent"><span class="doxyHighlight">                            unput(*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">621</span><span class="doxyLineContent"><span class="doxyHighlight">                            BEGIN(SearchSkipValue);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">622</span><span class="doxyLineContent"><span class="doxyHighlight">                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">623</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">624</span><span class="doxyLineContent"><span class="doxyHighlight">                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">625</span><span class="doxyLineContent"><span class="doxyHighlight">                            yyextra-&gt;current-&gt;type+=*yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">626</span><span class="doxyLineContent"><span class="doxyHighlight">                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">627</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">628</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">\n</span><span class="doxyHighlight">                  { </span><span class="doxyHighlightComment">// end of the type hint</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">629</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;current-&gt;type = yyextra-&gt;current-&gt;type.stripWhiteSpace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">630</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">631</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#a04219d02c56369b619778a94f19fd58f">newEntry</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">632</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN(SearchMemVars);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">633</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">634</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">"\\\n"</span><span class="doxyHighlight">               {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">635</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;current-&gt;type+=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">636</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">637</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">638</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">.</span><span class="doxyHighlight">                   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">639</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;current-&gt;type+=*yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">640</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">641</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">642</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">643</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SearchSkipValue,VariableDec&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">644</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">"="</span><span class="doxyHighlight">                { </span><span class="doxyHighlightComment">// the assignment operator</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">645</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightComment">//printf("====== VariableDec at line %d\n",yyextra-&gt;yyLineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">646</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;startInit = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">647</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;initializer.str(yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">648</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;initializer &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">649</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">650</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">{B}</span><span class="doxyHighlight">                { </span><span class="doxyHighlightComment">// spaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">651</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;initializer &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">652</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">653</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">654</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">{INTNUMBER}</span><span class="doxyHighlight">        { </span><span class="doxyHighlightComment">// integer value</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">655</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;current-&gt;type.isEmpty()) yyextra-&gt;current-&gt;type = </span><span class="doxyHighlightStringLiteral">"int"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">656</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;initializer &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">657</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">658</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">{FLOATNUMBER}</span><span class="doxyHighlight">      { </span><span class="doxyHighlightComment">// floating point value</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">659</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;current-&gt;type.isEmpty()) yyextra-&gt;current-&gt;type = </span><span class="doxyHighlightStringLiteral">"float"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">660</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;initializer &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">661</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">662</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">{BOOL}</span><span class="doxyHighlight">             { </span><span class="doxyHighlightComment">// boolean value</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">663</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;current-&gt;type.isEmpty()) yyextra-&gt;current-&gt;type = </span><span class="doxyHighlightStringLiteral">"bool"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">664</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;initializer &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">665</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">666</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">{STRINGPREFIX}?"'"</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;current-&gt;type.isEmpty()) yyextra-&gt;current-&gt;type = </span><span class="doxyHighlightStringLiteral">"str"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">668</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;initializer &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;copyString=&amp;yyextra-&gt;current-&gt;initializer;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">670</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;stringContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">671</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN( SingleQuoteString );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">672</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">673</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">{STRINGPREFIX}?"\""</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">674</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;current-&gt;type.isEmpty()) yyextra-&gt;current-&gt;type = </span><span class="doxyHighlightStringLiteral">"str"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">675</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;initializer &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">676</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;copyString=&amp;yyextra-&gt;current-&gt;initializer;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">677</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;stringContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">678</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN( DoubleQuoteString );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">679</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">680</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">{TRIDOUBLEQUOTE}</span><span class="doxyHighlight">   { </span><span class="doxyHighlightComment">// start of a comment block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">681</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;current-&gt;type.isEmpty()) yyextra-&gt;current-&gt;type = </span><span class="doxyHighlightStringLiteral">"str"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">682</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;initializer &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">683</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;doubleQuote=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">684</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;copyString=&amp;yyextra-&gt;current-&gt;initializer;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">685</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;stringContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">686</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN(TripleString);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">687</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">688</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">689</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">{TRISINGLEQUOTE}</span><span class="doxyHighlight">   { </span><span class="doxyHighlightComment">// start of a comment block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">690</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;current-&gt;type.isEmpty()) yyextra-&gt;current-&gt;type = </span><span class="doxyHighlightStringLiteral">"str"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">691</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;initializer &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">692</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;doubleQuote=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">693</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;copyString=&amp;yyextra-&gt;current-&gt;initializer;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">694</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;stringContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN(TripleString);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">696</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">697</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">"("</span><span class="doxyHighlight">                { </span><span class="doxyHighlightComment">// tuple, only when direct after =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">698</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;current-&gt;mtype!=MethodTypes::Property &amp;&amp; yyextra-&gt;startInit)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">699</span><span class="doxyLineContent"><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">700</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;current-&gt;type = </span><span class="doxyHighlightStringLiteral">"tuple"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">701</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">702</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;initializer &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">703</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;atomStart=</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">704</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;atomEnd=</span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">705</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;atomCount=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">706</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;atomContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">707</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN( VariableAtom );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">708</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">709</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">"["</span><span class="doxyHighlight">                { </span><span class="doxyHighlightComment">// list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">710</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;startInit) yyextra-&gt;current-&gt;type = </span><span class="doxyHighlightStringLiteral">"list"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">711</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;initializer &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">712</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;atomStart=</span><span class="doxyHighlightCharLiteral">'['</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">713</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;atomEnd=</span><span class="doxyHighlightCharLiteral">']'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">714</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;atomCount=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">715</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;atomContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">716</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN( VariableAtom );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">717</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">718</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight">                { </span><span class="doxyHighlightComment">// dictionary</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">719</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;startInit) yyextra-&gt;current-&gt;type = </span><span class="doxyHighlightStringLiteral">"dict"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">720</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;initializer &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">721</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;atomStart=</span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">722</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;atomEnd=</span><span class="doxyHighlightCharLiteral">'}'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">723</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;atomCount=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">724</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;atomContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">725</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN( VariableAtom );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">726</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">727</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">"\\\n"</span><span class="doxyHighlight">             {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">728</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;initializer &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">729</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">730</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">731</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">{IDENTIFIER}</span><span class="doxyHighlight">       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">732</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightComment">// do something based on the type of the IDENTIFIER</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">733</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;current-&gt;type.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">734</span><span class="doxyLineContent"><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">735</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;child : yyextra-&gt;current_root-&gt;children())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">736</span><span class="doxyLineContent"><span class="doxyHighlight">                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">737</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (child-&gt;name == <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">738</span><span class="doxyLineContent"><span class="doxyHighlight">                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">739</span><span class="doxyLineContent"><span class="doxyHighlight">                               yyextra-&gt;current-&gt;type = child-&gt;type;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">740</span><span class="doxyLineContent"><span class="doxyHighlight">                               </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">741</span><span class="doxyLineContent"><span class="doxyHighlight">                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">742</span><span class="doxyLineContent"><span class="doxyHighlight">                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">743</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">744</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;startInit = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">745</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;initializer &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">746</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">747</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">.</span><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">748</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;startInit = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">749</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;initializer &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">750</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">751</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">752</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SearchSkipValue&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">753</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{STARTDOCSYMS}/[^#]</span><span class="doxyHighlight">    {  </span><span class="doxyHighlightComment">// start of a special comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">754</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#a22addf63e54e56357d7a2691022828e1">initSpecialBlock</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">755</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN(SpecialComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">756</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">757</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{POUNDCOMMENT}</span><span class="doxyHighlight">    { </span><span class="doxyHighlightComment">// #</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">758</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">759</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">\n</span><span class="doxyHighlight">                { <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">760</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#a04219d02c56369b619778a94f19fd58f">newEntry</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">761</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN(SearchMemVars);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">762</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">763</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">&lt;&lt;EOF&gt;&gt;</span><span class="doxyHighlight">           { <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">764</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#a04219d02c56369b619778a94f19fd58f">newEntry</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">765</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN(SearchMemVars);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">766</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">767</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">768</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">769</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FunctionBody&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">770</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">\n{B}/{IDENTIFIER}[^{LETTER}{DIGIT}_]</span><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">771</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr,</span><span class="doxyHighlightStringLiteral">"indent %d&lt;=%d\n"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a2b4acd8f05e7bebf0528ec710692f758">computeIndent</a>(&amp;yytext[1]),yyextra-&gt;indent));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">772</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a2b4acd8f05e7bebf0528ec710692f758">computeIndent</a>(&amp;yytext[1])&lt;=yyextra-&gt;indent)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">773</span><span class="doxyLineContent"><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">774</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a86da2f5e3360caa90276fc24433d9512">unput_string</a>(yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">775</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#a4bbc5085e6314777292116922282abf8">endOfDef</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">776</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightComment">//YY_CURRENT_BUFFER-&gt;yy_at_bol=TRUE;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">777</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN(<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">Search</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">778</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">779</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">780</span><span class="doxyLineContent"><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">781</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">782</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;current-&gt;program &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">783</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">784</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">785</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">\n{B}/"##"</span><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">786</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a2b4acd8f05e7bebf0528ec710692f758">computeIndent</a>(&amp;yytext[1])&lt;=yyextra-&gt;indent)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">787</span><span class="doxyLineContent"><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">788</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a86da2f5e3360caa90276fc24433d9512">unput_string</a>(yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">789</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#a4bbc5085e6314777292116922282abf8">endOfDef</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">790</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightComment">//YY_CURRENT_BUFFER-&gt;yy_at_bol=TRUE;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">791</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN(<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">Search</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">792</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">793</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">794</span><span class="doxyLineContent"><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">795</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">796</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;current-&gt;program &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">797</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">798</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">799</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">&lt;&lt;EOF&gt;&gt;</span><span class="doxyHighlight">           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">800</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#a4bbc5085e6314777292116922282abf8">endOfDef</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">801</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#ac3286b18a2e91b4571b97df96a118e84">yyterminate</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">802</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">803</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">^{BB}/\n</span><span class="doxyHighlight">          { </span><span class="doxyHighlightComment">// skip empty line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">804</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;program &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">805</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">806</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">^{BB}</span><span class="doxyHighlight">             { </span><span class="doxyHighlightComment">// something at indent &gt;0</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">807</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;curIndent = <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a2b4acd8f05e7bebf0528ec710692f758">computeIndent</a>(yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">808</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;curIndent&lt;=yyextra-&gt;indent)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">809</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightComment">// jumped out of the function</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">810</span><span class="doxyLineContent"><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">811</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#a4bbc5085e6314777292116922282abf8">endOfDef</a>(yyscanner,1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">812</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN(<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">Search</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">813</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">814</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">815</span><span class="doxyLineContent"><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">816</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;current-&gt;program &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">817</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">818</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">819</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">               { </span><span class="doxyHighlightComment">// start of a single quoted string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">820</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;program &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">821</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;stringContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">822</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;specialBlock = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">823</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;copyString=&amp;yyextra-&gt;current-&gt;program;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">824</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN( SingleQuoteString );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">825</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">826</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">              { </span><span class="doxyHighlightComment">// start of a double quoted string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">827</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;program &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">828</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;stringContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">829</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;specialBlock = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">830</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;copyString=&amp;yyextra-&gt;current-&gt;program;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">831</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN( DoubleQuoteString );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">832</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">833</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">[^ \t\n#'".]+</span><span class="doxyHighlight">     { </span><span class="doxyHighlightComment">// non-special stuff</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">834</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;program &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">835</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;specialBlock = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">836</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">837</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">^{POUNDCOMMENT}</span><span class="doxyHighlight">   { </span><span class="doxyHighlightComment">// normal comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">838</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;program &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">839</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">840</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"#".*</span><span class="doxyHighlight">             { </span><span class="doxyHighlightComment">// comment half way</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">841</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;program &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">842</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">843</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{NEWLINE}</span><span class="doxyHighlight">         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">844</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">845</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;program &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">846</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">847</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">.</span><span class="doxyHighlight">                 { </span><span class="doxyHighlightComment">// any character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">848</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;program &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">849</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;specialBlock = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">850</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">851</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">852</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{TRIDOUBLEQUOTE}</span><span class="doxyHighlight">  { </span><span class="doxyHighlightComment">// start of a comment block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">853</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;program &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">854</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#aa1fd664818291e7a90ed2ba46a0f44a7">initTriDoubleQuoteBlock</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">855</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN(TripleComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">856</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">857</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">858</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{TRISINGLEQUOTE}</span><span class="doxyHighlight">  { </span><span class="doxyHighlightComment">// start of a comment block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">859</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;program &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">860</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#a2aa292ec6b6ea81860b3d9b00405d1cb">initTriSingleQuoteBlock</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">861</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN(TripleComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">862</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">863</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">864</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">865</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">866</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FunctionDec&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">867</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{IDENTIFIER}</span><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">868</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightComment">//found function name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">869</span><span class="doxyLineContent"><span class="doxyHighlight">                              yyextra-&gt;current-&gt;name = yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">870</span><span class="doxyLineContent"><span class="doxyHighlight">                              yyextra-&gt;current-&gt;name = yyextra-&gt;current-&gt;name.stripWhiteSpace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">871</span><span class="doxyLineContent"><span class="doxyHighlight">                              <a href="#ae986dc4d2214f2b90b824521c25a2a5c">newFunction</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">872</span><span class="doxyLineContent"><span class="doxyHighlight">                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">873</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{B}":"{B}</span><span class="doxyHighlight">               { </span><span class="doxyHighlightComment">// function without arguments</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">874</span><span class="doxyLineContent"><span class="doxyHighlight">                              yyextra-&gt;specialBlock = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>; </span><span class="doxyHighlightComment">// expecting a docstring</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">875</span><span class="doxyLineContent"><span class="doxyHighlight">                              yyextra-&gt;bodyEntry = yyextra-&gt;current;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">876</span><span class="doxyLineContent"><span class="doxyHighlight">                              yyextra-&gt;current-&gt;bodyLine  = yyextra-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">877</span><span class="doxyLineContent"><span class="doxyHighlight">                              BEGIN(FunctionBody);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">878</span><span class="doxyLineContent"><span class="doxyHighlight">                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">879</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">880</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"-&gt;"</span><span class="doxyHighlight">                    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">881</span><span class="doxyLineContent"><span class="doxyHighlight">                              yyextra-&gt;defVal.str(std::string());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">882</span><span class="doxyLineContent"><span class="doxyHighlight">                              yyextra-&gt;braceCount = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">883</span><span class="doxyLineContent"><span class="doxyHighlight">                              BEGIN(FunctionTypeAnnotation);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">884</span><span class="doxyLineContent"><span class="doxyHighlight">                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">885</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{B}"("</span><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">886</span><span class="doxyLineContent"><span class="doxyHighlight">                              yyextra-&gt;funcParamsEnd = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">887</span><span class="doxyLineContent"><span class="doxyHighlight">                              yyextra-&gt;current-&gt;bodyLine  = yyextra-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">888</span><span class="doxyLineContent"><span class="doxyHighlight">                              BEGIN(FunctionParams);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">889</span><span class="doxyLineContent"><span class="doxyHighlight">                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">890</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">")"</span><span class="doxyHighlight">                     { </span><span class="doxyHighlightComment">// end of parameter list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">891</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;current-&gt;argList.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">892</span><span class="doxyLineContent"><span class="doxyHighlight">                              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">893</span><span class="doxyLineContent"><span class="doxyHighlight">                                yyextra-&gt;current-&gt;argList.setNoParameters(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">894</span><span class="doxyLineContent"><span class="doxyHighlight">                              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">895</span><span class="doxyLineContent"><span class="doxyHighlight">                              yyextra-&gt;current-&gt;args = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9d5c2a3aefbda0b0e684f768a380d2db">argListToString</a>(yyextra-&gt;current-&gt;argList);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">896</span><span class="doxyLineContent"><span class="doxyHighlight">                              yyextra-&gt;funcParamsEnd = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">897</span><span class="doxyLineContent"><span class="doxyHighlight">                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">898</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">899</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">900</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FunctionParams&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">901</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{BB}</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">902</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">903</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">904</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">905</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;argType.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">906</span><span class="doxyLineContent"><span class="doxyHighlight">                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">907</span><span class="doxyLineContent"><span class="doxyHighlight">                            <a href="/web-doxygen/docs/api/structs/argument">Argument</a> a;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">908</span><span class="doxyLineContent"><span class="doxyHighlight">                            a.<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a> = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">909</span><span class="doxyLineContent"><span class="doxyHighlight">                            a.<a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">type</a> = yyextra-&gt;argType;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">910</span><span class="doxyLineContent"><span class="doxyHighlight">                            yyextra-&gt;current-&gt;argList.push_back(a);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">911</span><span class="doxyLineContent"><span class="doxyHighlight">                            yyextra-&gt;argType = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">912</span><span class="doxyLineContent"><span class="doxyHighlight">                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">913</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">914</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">915</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">[\*]+</span><span class="doxyHighlight">               {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">916</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;argType = yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">917</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">918</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{IDENTIFIER}</span><span class="doxyHighlight">        { </span><span class="doxyHighlightComment">// Name of parameter</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">919</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#a6256e57feb94db36e0dd7c3c83c9180a">lineCount</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">920</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="/web-doxygen/docs/api/structs/argument">Argument</a> a;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">921</span><span class="doxyLineContent"><span class="doxyHighlight">                          a.<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a> = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">922</span><span class="doxyLineContent"><span class="doxyHighlight">                          a.<a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">type</a> = yyextra-&gt;argType;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">923</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;current-&gt;argList.push_back(a);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">924</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;argType = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">925</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">926</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"="</span><span class="doxyHighlight">                 { </span><span class="doxyHighlightComment">// default value</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">927</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightComment">// TODO: this rule is too simple, need to be able to</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">928</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightComment">// match things like =")" as well!</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">929</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;defVal.str(std::string());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">930</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;braceCount = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">931</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN(FunctionParamDefVal);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">932</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">933</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">")"</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">934</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;argType.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">935</span><span class="doxyLineContent"><span class="doxyHighlight">                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">936</span><span class="doxyLineContent"><span class="doxyHighlight">                            <a href="/web-doxygen/docs/api/structs/argument">Argument</a> a;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">937</span><span class="doxyLineContent"><span class="doxyHighlight">                            a.<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a> = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">938</span><span class="doxyLineContent"><span class="doxyHighlight">                            a.<a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">type</a> = yyextra-&gt;argType;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">939</span><span class="doxyLineContent"><span class="doxyHighlight">                            yyextra-&gt;current-&gt;argList.push_back(a);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">940</span><span class="doxyLineContent"><span class="doxyHighlight">                            yyextra-&gt;argType = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">941</span><span class="doxyLineContent"><span class="doxyHighlight">                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">942</span><span class="doxyLineContent"><span class="doxyHighlight">                          unput(*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">943</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN(FunctionDec);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">944</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">945</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">":"{B}</span><span class="doxyHighlight">             {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">946</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;defVal.str(std::string());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">947</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;braceCount = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">948</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN(FunctionAnnotation);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">949</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">950</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{POUNDCOMMENT}</span><span class="doxyHighlight">      { </span><span class="doxyHighlightComment">// a comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">951</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">952</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{PARAMNONEMPTY}</span><span class="doxyHighlight">     { </span><span class="doxyHighlightComment">// Default rule inside arguments.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">953</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">954</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">955</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">956</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">957</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FunctionTypeAnnotation&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">958</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight">                |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">959</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"["</span><span class="doxyHighlight">                |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">960</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"("</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">961</span><span class="doxyLineContent"><span class="doxyHighlight">                          ++yyextra-&gt;braceCount;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">962</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;defVal &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">963</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">964</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">                |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">965</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"]"</span><span class="doxyHighlight">                |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">966</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">")"</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">967</span><span class="doxyLineContent"><span class="doxyHighlight">                          --yyextra-&gt;braceCount;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">968</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;defVal &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">969</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">970</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">971</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;braceCount == 0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">972</span><span class="doxyLineContent"><span class="doxyHighlight">                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">973</span><span class="doxyLineContent"><span class="doxyHighlight">                            yyextra-&gt;current-&gt;type = yyextra-&gt;defVal.str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">974</span><span class="doxyLineContent"><span class="doxyHighlight">                            unput(*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">975</span><span class="doxyLineContent"><span class="doxyHighlight">                            BEGIN(FunctionDec);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">976</span><span class="doxyLineContent"><span class="doxyHighlight">                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">977</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">978</span><span class="doxyLineContent"><span class="doxyHighlight">                            yyextra-&gt;defVal &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">979</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">980</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">981</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;defVal &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">982</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;copyString=&amp;yyextra-&gt;defVal;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">983</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;stringContext=FunctionTypeAnnotation;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">984</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN(SingleQuoteString);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">985</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">986</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">               {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">987</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;defVal &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">988</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;copyString=&amp;yyextra-&gt;defVal;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">989</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;stringContext=FunctionTypeAnnotation;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">990</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN(DoubleQuoteString);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">991</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">992</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">\n</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">993</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;defVal &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">994</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">995</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">996</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">.</span><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">997</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;defVal &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">998</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">999</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1000</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1001</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FunctionAnnotation&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1002</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight">                |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1003</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"["</span><span class="doxyHighlight">                |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1004</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"("</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1005</span><span class="doxyLineContent"><span class="doxyHighlight">                          ++yyextra-&gt;braceCount;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1006</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;defVal &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1007</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1008</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">                |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1009</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"]"</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1010</span><span class="doxyLineContent"><span class="doxyHighlight">                          --yyextra-&gt;braceCount;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1011</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;defVal &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1012</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1013</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">")"</span><span class="doxyHighlight">                |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1014</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"="</span><span class="doxyHighlight">                |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1015</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1016</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;braceCount == 0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1017</span><span class="doxyLineContent"><span class="doxyHighlight">                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1018</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;current-&gt;argList.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1019</span><span class="doxyLineContent"><span class="doxyHighlight">                              yyextra-&gt;current-&gt;argList.back().type += yyextra-&gt;defVal.str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1020</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*yytext != </span><span class="doxyHighlightCharLiteral">','</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1021</span><span class="doxyLineContent"><span class="doxyHighlight">                              unput(*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1022</span><span class="doxyLineContent"><span class="doxyHighlight">                            BEGIN(FunctionParams);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1023</span><span class="doxyLineContent"><span class="doxyHighlight">                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1024</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1025</span><span class="doxyLineContent"><span class="doxyHighlight">                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1026</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*yytext == </span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1027</span><span class="doxyLineContent"><span class="doxyHighlight">                              --yyextra-&gt;braceCount;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1028</span><span class="doxyLineContent"><span class="doxyHighlight">                            yyextra-&gt;defVal &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1029</span><span class="doxyLineContent"><span class="doxyHighlight">                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1030</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1031</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1032</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;defVal &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1033</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;copyString=&amp;yyextra-&gt;defVal;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1034</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;stringContext=FunctionAnnotation;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1035</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN(SingleQuoteString);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1036</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1037</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">               {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1038</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;defVal &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1039</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;copyString=&amp;yyextra-&gt;defVal;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1040</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;stringContext=FunctionAnnotation;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1041</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN(DoubleQuoteString);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1042</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1043</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">\n</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1044</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;defVal &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1045</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1046</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1047</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">.</span><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1048</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;defVal &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1049</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1050</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1051</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1052</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FunctionParamDefVal&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1053</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight">                |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1054</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"["</span><span class="doxyHighlight">                |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1055</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"("</span><span class="doxyHighlight">                { </span><span class="doxyHighlightComment">// internal opening brace, assumption is that we have correct code so braces do match</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1056</span><span class="doxyLineContent"><span class="doxyHighlight">                          ++yyextra-&gt;braceCount;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1057</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;defVal &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1058</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1059</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">                |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1060</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"]"</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1061</span><span class="doxyLineContent"><span class="doxyHighlight">                          --yyextra-&gt;braceCount;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1062</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;defVal &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1063</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1064</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">")"</span><span class="doxyHighlight">                |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1065</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1066</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;braceCount == 0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1067</span><span class="doxyLineContent"><span class="doxyHighlight">                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1068</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;current-&gt;argList.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1069</span><span class="doxyLineContent"><span class="doxyHighlight">                              yyextra-&gt;current-&gt;argList.back().defval=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yyextra-&gt;defVal.str()).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1070</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*yytext == </span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1071</span><span class="doxyLineContent"><span class="doxyHighlight">                              unput(*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1072</span><span class="doxyLineContent"><span class="doxyHighlight">                            BEGIN(FunctionParams);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1073</span><span class="doxyLineContent"><span class="doxyHighlight">                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1074</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1075</span><span class="doxyLineContent"><span class="doxyHighlight">                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1076</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*yytext == </span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1077</span><span class="doxyLineContent"><span class="doxyHighlight">                              --yyextra-&gt;braceCount;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1078</span><span class="doxyLineContent"><span class="doxyHighlight">                            yyextra-&gt;defVal &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1079</span><span class="doxyLineContent"><span class="doxyHighlight">                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1080</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1081</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1082</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1083</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;defVal &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1084</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;copyString=&amp;yyextra-&gt;defVal;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1085</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;stringContext=FunctionParamDefVal;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1086</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN( SingleQuoteString );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1087</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1088</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">               {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1089</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;defVal &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1090</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;copyString=&amp;yyextra-&gt;defVal;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1091</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;stringContext=FunctionParamDefVal;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1092</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN( DoubleQuoteString );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1093</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1094</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">\n</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1095</span><span class="doxyLineContent"><span class="doxyHighlight">                            yyextra-&gt;defVal &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1096</span><span class="doxyLineContent"><span class="doxyHighlight">                            <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1097</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1098</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">.</span><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1099</span><span class="doxyLineContent"><span class="doxyHighlight">                            yyextra-&gt;defVal &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1100</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1101</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1102</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1103</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1104</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ClassBody&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1105</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">\n/{IDENTIFIER}{BB}</span><span class="doxyHighlight">  { </span><span class="doxyHighlightComment">// new def at indent 0</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1106</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a2b4acd8f05e7bebf0528ec710692f758">computeIndent</a>(&amp;yytext[1])&lt;=yyextra-&gt;indent)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1107</span><span class="doxyLineContent"><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1108</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1109</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (i=(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)yyleng-1;i&gt;=0;i--)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1110</span><span class="doxyLineContent"><span class="doxyHighlight">                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1111</span><span class="doxyLineContent"><span class="doxyHighlight">                            unput(yytext[i]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1112</span><span class="doxyLineContent"><span class="doxyHighlight">                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1113</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#a4bbc5085e6314777292116922282abf8">endOfDef</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1114</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightComment">//YY_CURRENT_BUFFER-&gt;yy_at_bol=TRUE;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1115</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN(<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">Search</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1116</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1117</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1118</span><span class="doxyLineContent"><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1119</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1120</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;current-&gt;program &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1121</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1122</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1123</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">\n/"##"[^#]</span><span class="doxyHighlight">       {  </span><span class="doxyHighlightComment">// start of a special comment at indent 0</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1124</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a2b4acd8f05e7bebf0528ec710692f758">computeIndent</a>(&amp;yytext[1])&lt;=yyextra-&gt;indent)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1125</span><span class="doxyLineContent"><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1126</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1127</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (i=(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)yyleng-1;i&gt;=0;i--)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1128</span><span class="doxyLineContent"><span class="doxyHighlight">                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1129</span><span class="doxyLineContent"><span class="doxyHighlight">                            unput(yytext[i]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1130</span><span class="doxyLineContent"><span class="doxyHighlight">                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1131</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#a4bbc5085e6314777292116922282abf8">endOfDef</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1132</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightComment">//YY_CURRENT_BUFFER-&gt;yy_at_bol=TRUE;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1133</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN(<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">Search</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1134</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1135</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1136</span><span class="doxyLineContent"><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1137</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1138</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;current-&gt;program &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1139</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1140</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1141</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">^{BB}/\n</span><span class="doxyHighlight">          { </span><span class="doxyHighlightComment">// skip empty line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1142</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;program &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1143</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1144</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">&lt;&lt;EOF&gt;&gt;</span><span class="doxyHighlight">           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1145</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#a4bbc5085e6314777292116922282abf8">endOfDef</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1146</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#ac3286b18a2e91b4571b97df96a118e84">yyterminate</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1147</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1148</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">^{BB}</span><span class="doxyHighlight">             { </span><span class="doxyHighlightComment">// something at indent &gt;0</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1149</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;curIndent=<a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a2b4acd8f05e7bebf0528ec710692f758">computeIndent</a>(yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1150</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr,</span><span class="doxyHighlightStringLiteral">"yyextra-&gt;curIndent=%d yyextra-&gt;indent=%d\n"</span><span class="doxyHighlight">,yyextra-&gt;curIndent,yyextra-&gt;indent));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1151</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;curIndent&lt;=yyextra-&gt;indent)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1152</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightComment">// jumped out of the class/method</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1153</span><span class="doxyLineContent"><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1154</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#a4bbc5085e6314777292116922282abf8">endOfDef</a>(yyscanner,1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1155</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;indent=yyextra-&gt;curIndent;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1156</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightComment">// make sure the next rule matches ^...</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1157</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightComment">//YY_CURRENT_BUFFER-&gt;yy_at_bol=TRUE;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1158</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightComment">//yyextra-&gt;hideClassDocs = FALSE;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1159</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN(<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">Search</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1160</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1161</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1162</span><span class="doxyLineContent"><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1163</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;current-&gt;program &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1164</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1165</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1166</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">               { </span><span class="doxyHighlightComment">// start of a single quoted string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1167</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;program &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1168</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;stringContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1169</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;specialBlock = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1170</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;copyString=&amp;yyextra-&gt;current-&gt;program;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1171</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN( SingleQuoteString );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1172</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1173</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">              { </span><span class="doxyHighlightComment">// start of a double quoted string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1174</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;program &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1175</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;stringContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1176</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;specialBlock = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1177</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;copyString=&amp;yyextra-&gt;current-&gt;program;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1178</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN( DoubleQuoteString );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1179</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1180</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">[^ \t\n#'"]+</span><span class="doxyHighlight">      { </span><span class="doxyHighlightComment">// non-special stuff</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1181</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;program &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1182</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;specialBlock = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1183</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightComment">//yyextra-&gt;hideClassDocs = FALSE;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1184</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1185</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{NEWLINE}</span><span class="doxyHighlight">         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1186</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;program &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1187</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1188</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1189</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{POUNDCOMMENT}</span><span class="doxyHighlight">    { </span><span class="doxyHighlightComment">// normal comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1190</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;program &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1191</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1192</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">.</span><span class="doxyHighlight">                 { </span><span class="doxyHighlightComment">// any character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1193</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;specialBlock = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1194</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;program &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1195</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1196</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{TRIDOUBLEQUOTE}</span><span class="doxyHighlight">  { </span><span class="doxyHighlightComment">// start of a comment block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1197</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightComment">//if (!yyextra-&gt;hideClassDocs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1198</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;program &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1199</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#aa1fd664818291e7a90ed2ba46a0f44a7">initTriDoubleQuoteBlock</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1200</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN(TripleComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1201</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1202</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1203</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{TRISINGLEQUOTE}</span><span class="doxyHighlight">  { </span><span class="doxyHighlightComment">// start of a comment block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1204</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightComment">//if (!yyextra-&gt;hideClassDocs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1205</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;program &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1206</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#a2aa292ec6b6ea81860b3d9b00405d1cb">initTriSingleQuoteBlock</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1207</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN(TripleComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1208</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1209</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1210</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1211</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ClassDec&gt;{IDENTIFIER}</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1212</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;current-&gt;type.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1213</span><span class="doxyLineContent"><span class="doxyHighlight">                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1214</span><span class="doxyLineContent"><span class="doxyHighlight">                              yyextra-&gt;current-&gt;type = </span><span class="doxyHighlightStringLiteral">"class"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1215</span><span class="doxyLineContent"><span class="doxyHighlight">                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1216</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1217</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;current-&gt;section = EntryType::makeClass();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1218</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;current-&gt;name = yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1219</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightComment">// we need to set the protectiion based on the "local" class name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1220</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#a3bb5a3fd461f68eff332a09e9e5b0e1e">setProtection</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1221</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1222</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightComment">// prepend scope in case of nested classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1223</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;current_root-&gt;section.isScope())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1224</span><span class="doxyLineContent"><span class="doxyHighlight">                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1225</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightComment">//printf("*** Prepending scope %s to class %s\n",qPrint(yyextra-&gt;current_root-&gt;name),qPrint(yyextra-&gt;current-&gt;name));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1226</span><span class="doxyLineContent"><span class="doxyHighlight">                            yyextra-&gt;current-&gt;name.prepend(yyextra-&gt;current_root-&gt;name+</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1227</span><span class="doxyLineContent"><span class="doxyHighlight">                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1228</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1229</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;current-&gt;name = yyextra-&gt;current-&gt;name.stripWhiteSpace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1230</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;current-&gt;fileName = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1231</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;docBlockContext   = YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1232</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;docBlockInBody    = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1233</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;docBlockJavaStyle = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1234</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;docBlock.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1235</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1236</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN(ClassInheritance);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1237</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1238</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1239</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ClassInheritance&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1240</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">({BB}|[\(,\)])</span><span class="doxyHighlight">      { </span><span class="doxyHighlightComment">// syntactic sugar for the list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1241</span><span class="doxyLineContent"><span class="doxyHighlight">                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1242</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1243</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight">                { </span><span class="doxyHighlightComment">// begin of the class definition</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1244</span><span class="doxyLineContent"><span class="doxyHighlight">                         yyextra-&gt;specialBlock = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>; </span><span class="doxyHighlightComment">// expecting a docstring</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1245</span><span class="doxyLineContent"><span class="doxyHighlight">                         yyextra-&gt;current-&gt;bodyLine  = yyextra-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1246</span><span class="doxyLineContent"><span class="doxyHighlight">                         yyextra-&gt;current-&gt;program.str(std::string());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1247</span><span class="doxyLineContent"><span class="doxyHighlight">                         BEGIN(ClassCaptureIndent);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1248</span><span class="doxyLineContent"><span class="doxyHighlight">                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1249</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1250</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{SCOPE}</span><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1251</span><span class="doxyLineContent"><span class="doxyHighlight">                         yyextra-&gt;current-&gt;extends.emplace_back(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1252</span><span class="doxyLineContent"><span class="doxyHighlight">                                              <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(yytext,</span><span class="doxyHighlightStringLiteral">"."</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">),Protection::Public,Specifier::Normal</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1253</span><span class="doxyLineContent"><span class="doxyHighlight">                                            );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1254</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightComment">//Has base class-do stuff</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1255</span><span class="doxyLineContent"><span class="doxyHighlight">                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1256</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">                { </span><span class="doxyHighlightComment">// start of a single quoted string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1257</span><span class="doxyLineContent"><span class="doxyHighlight">                         yyextra-&gt;stringContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1258</span><span class="doxyLineContent"><span class="doxyHighlight">                         BEGIN( SingleQuoteStringIgnore );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1259</span><span class="doxyLineContent"><span class="doxyHighlight">                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1260</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">               { </span><span class="doxyHighlightComment">// start of a double quoted string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1261</span><span class="doxyLineContent"><span class="doxyHighlight">                         yyextra-&gt;stringContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1262</span><span class="doxyLineContent"><span class="doxyHighlight">                         BEGIN( DoubleQuoteStringIgnore );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1263</span><span class="doxyLineContent"><span class="doxyHighlight">                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1264</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1265</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1266</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SingleQuoteStringIgnore&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1267</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">                { </span><span class="doxyHighlightComment">// end of a single quoted string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1268</span><span class="doxyLineContent"><span class="doxyHighlight">                         BEGIN(yyextra-&gt;stringContext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1269</span><span class="doxyLineContent"><span class="doxyHighlight">                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1270</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">.</span><span class="doxyHighlight">                  { }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1271</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1272</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DoubleQuoteStringIgnore&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1273</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">               { </span><span class="doxyHighlightComment">// end of a double quoted string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1274</span><span class="doxyLineContent"><span class="doxyHighlight">                         BEGIN(yyextra-&gt;stringContext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1275</span><span class="doxyLineContent"><span class="doxyHighlight">                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1276</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">.</span><span class="doxyHighlight">                  { }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1277</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1278</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1279</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ClassCaptureIndent&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1280</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"|({BB}"\n")</span><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1281</span><span class="doxyLineContent"><span class="doxyHighlight">                                 </span><span class="doxyHighlightComment">// Blankline - ignore, keep looking for indentation.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1282</span><span class="doxyLineContent"><span class="doxyHighlight">                                 <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#a6256e57feb94db36e0dd7c3c83c9180a">lineCount</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1283</span><span class="doxyLineContent"><span class="doxyHighlight">                                 yyextra-&gt;current-&gt;program &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1284</span><span class="doxyLineContent"><span class="doxyHighlight">                               }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1285</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1286</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{TRIDOUBLEQUOTE}</span><span class="doxyHighlight">           { </span><span class="doxyHighlightComment">// start of a comment block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1287</span><span class="doxyLineContent"><span class="doxyHighlight">                                 <a href="#aa1fd664818291e7a90ed2ba46a0f44a7">initTriDoubleQuoteBlock</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1288</span><span class="doxyLineContent"><span class="doxyHighlight">                                 yyextra-&gt;current-&gt;program &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1289</span><span class="doxyLineContent"><span class="doxyHighlight">                                 BEGIN(TripleComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1290</span><span class="doxyLineContent"><span class="doxyHighlight">                               }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1291</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{TRISINGLEQUOTE}</span><span class="doxyHighlight">           { </span><span class="doxyHighlightComment">// start of a comment block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1292</span><span class="doxyLineContent"><span class="doxyHighlight">                                 <a href="#a2aa292ec6b6ea81860b3d9b00405d1cb">initTriSingleQuoteBlock</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1293</span><span class="doxyLineContent"><span class="doxyHighlight">                                 yyextra-&gt;current-&gt;program &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1294</span><span class="doxyLineContent"><span class="doxyHighlight">                                 BEGIN(TripleComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1295</span><span class="doxyLineContent"><span class="doxyHighlight">                               }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1296</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{STARTDOCSYMS}[#]*</span><span class="doxyHighlight">         {  </span><span class="doxyHighlightComment">// start of a special comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1297</span><span class="doxyLineContent"><span class="doxyHighlight">                                 <a href="#a22addf63e54e56357d7a2691022828e1">initSpecialBlock</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1298</span><span class="doxyLineContent"><span class="doxyHighlight">                                 BEGIN(SpecialComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1299</span><span class="doxyLineContent"><span class="doxyHighlight">                               }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1300</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{POUNDCOMMENT}</span><span class="doxyHighlight">             { </span><span class="doxyHighlightComment">// ignore comment with just one #</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1301</span><span class="doxyLineContent"><span class="doxyHighlight">                               }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1302</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">^{BB}</span><span class="doxyHighlight">                      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1303</span><span class="doxyLineContent"><span class="doxyHighlight">                                 yyextra-&gt;current-&gt;program &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1304</span><span class="doxyLineContent"><span class="doxyHighlight">                                 </span><span class="doxyHighlightComment">//yyextra-&gt;current-&gt;startLine = yyextra-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1305</span><span class="doxyLineContent"><span class="doxyHighlight">                                 yyextra-&gt;curIndent=<a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a2b4acd8f05e7bebf0528ec710692f758">computeIndent</a>(yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1306</span><span class="doxyLineContent"><span class="doxyHighlight">                                 yyextra-&gt;bodyEntry = yyextra-&gt;current;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1307</span><span class="doxyLineContent"><span class="doxyHighlight">                                 <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr,</span><span class="doxyHighlightStringLiteral">"setting indent %d\n"</span><span class="doxyHighlight">,yyextra-&gt;curIndent));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1308</span><span class="doxyLineContent"><span class="doxyHighlight">                                 </span><span class="doxyHighlightComment">//printf("yyextra-&gt;current-&gt;program=[%s]\n",qPrint(yyextra-&gt;current-&gt;program));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1309</span><span class="doxyLineContent"><span class="doxyHighlight">                                 </span><span class="doxyHighlightComment">//yyextra-&gt;hideClassDocs = TRUE;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1310</span><span class="doxyLineContent"><span class="doxyHighlight">                                 BEGIN(ClassBody);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1311</span><span class="doxyLineContent"><span class="doxyHighlight">                               }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1312</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1313</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">""/({NONEMPTY}|{EXPCHAR})</span><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1314</span><span class="doxyLineContent"><span class="doxyHighlight">                                 </span><span class="doxyHighlightComment">// Just pushback an empty class, and</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1315</span><span class="doxyLineContent"><span class="doxyHighlight">                                 </span><span class="doxyHighlightComment">// resume parsing the body.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1316</span><span class="doxyLineContent"><span class="doxyHighlight">                                 <a href="#a04219d02c56369b619778a94f19fd58f">newEntry</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1317</span><span class="doxyLineContent"><span class="doxyHighlight">                                 yyextra-&gt;current-&gt;program &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1318</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1319</span><span class="doxyLineContent"><span class="doxyHighlight">                                 </span><span class="doxyHighlightComment">// printf("Failed to find indent - skipping!");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1320</span><span class="doxyLineContent"><span class="doxyHighlight">                                 BEGIN( <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">Search</a> );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1321</span><span class="doxyLineContent"><span class="doxyHighlight">                               }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1322</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1323</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1324</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1325</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;VariableDec&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1326</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">":"{B}{IDENTIFIER}</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">//typing</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1327</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;startInit = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1328</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;type = <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(yytext,</span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1329</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1330</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{STARTDOCSYMS}"&lt;"/.*</span><span class="doxyHighlight"> {  </span><span class="doxyHighlightComment">// start of a special comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1331</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;curIndent=<a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a2b4acd8f05e7bebf0528ec710692f758">computeIndent</a>(yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1332</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;packageCommentAllowed = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1333</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#a22addf63e54e56357d7a2691022828e1">initSpecialBlock</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1334</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;docBlockContext = VariableEnd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1335</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN(SpecialComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1336</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1337</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">"#".*</span><span class="doxyHighlight">              { </span><span class="doxyHighlightComment">// comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1338</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN( VariableEnd );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1339</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1340</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">\n</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1341</span><span class="doxyLineContent"><span class="doxyHighlight">                        unput(</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1342</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN( VariableEnd );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1343</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1344</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1345</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1346</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;VariableAtom&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1347</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">[\(\[\{]</span><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1348</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;initializer &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1349</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;atomStart==*yytext)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1350</span><span class="doxyLineContent"><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1351</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;atomCount++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1352</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1353</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1354</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">[\)\]\}]</span><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1355</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;initializer &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1356</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;atomEnd==*yytext)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1357</span><span class="doxyLineContent"><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1358</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;atomCount--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1359</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1360</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;atomCount==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1361</span><span class="doxyLineContent"><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1362</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;startInit = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1363</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN(yyextra-&gt;atomContext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1364</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1365</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1366</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{TRIDOUBLEQUOTE}</span><span class="doxyHighlight">  { </span><span class="doxyHighlightComment">// start of a comment block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1367</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;specialBlock = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1368</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;program &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1369</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#aa1fd664818291e7a90ed2ba46a0f44a7">initTriDoubleQuoteBlock</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1370</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN(TripleComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1371</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1372</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1373</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{TRISINGLEQUOTE}</span><span class="doxyHighlight">  { </span><span class="doxyHighlightComment">// start of a comment block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1374</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;specialBlock = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1375</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;program &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1376</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#a2aa292ec6b6ea81860b3d9b00405d1cb">initTriSingleQuoteBlock</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1377</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN(TripleComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1378</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1379</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1380</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;stringContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1381</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;initializer &lt;&lt; </span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1382</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;copyString=&amp;yyextra-&gt;current-&gt;initializer;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1383</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN( SingleQuoteString );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1384</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1385</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">               {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1386</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;stringContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1387</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;initializer &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1388</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;copyString=&amp;yyextra-&gt;current-&gt;initializer;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1389</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN( DoubleQuoteString );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1390</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1391</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">{IDENTIFIER}</span><span class="doxyHighlight">       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1392</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;initializer &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1393</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1394</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">.</span><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1395</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;initializer &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1396</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1397</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">\n</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1398</span><span class="doxyLineContent"><span class="doxyHighlight">                        yyextra-&gt;current-&gt;initializer &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1399</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1400</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1401</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1402</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1403</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1404</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;VariableEnd&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1405</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">\n</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1406</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1407</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/stringutil-h/#aef47e534975880014a6514745e885a99">stripWhiteSpace</a>(yyextra-&gt;current-&gt;initializer.str()).empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1408</span><span class="doxyLineContent"><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1409</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#a851aa07f7276b7e8f4b12d2592d2eb39">newVariable</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1410</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1411</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN(<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">Search</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1412</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1413</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">.</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1414</span><span class="doxyLineContent"><span class="doxyHighlight">                        unput(*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1415</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#a851aa07f7276b7e8f4b12d2592d2eb39">newVariable</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1416</span><span class="doxyLineContent"><span class="doxyHighlight">                        BEGIN(<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">Search</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1417</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1418</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">&lt;&lt;EOF&gt;&gt;</span><span class="doxyHighlight">           { <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#ac3286b18a2e91b4571b97df96a118e84">yyterminate</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1419</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1420</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1421</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1422</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;TripleComment&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1423</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{ENDTRIDOUBLEQUOTE}</span><span class="doxyHighlight">   |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1424</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{ENDTRISINGLEQUOTE}</span><span class="doxyHighlight">   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1425</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightComment">// printf("Expected module block %d special=%d\n",yyextra-&gt;expectModuleDocs,yyextra-&gt;specialBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1426</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;doubleQuote==(yytext[0]==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1427</span><span class="doxyLineContent"><span class="doxyHighlight">                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1428</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;specialBlock) </span><span class="doxyHighlightComment">// expecting a docstring</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1429</span><span class="doxyLineContent"><span class="doxyHighlight">                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1430</span><span class="doxyLineContent"><span class="doxyHighlight">                              <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> actualDoc=yyextra-&gt;docBlock;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1431</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;docBlockSpecial) </span><span class="doxyHighlightComment">// legacy unformatted docstring</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1432</span><span class="doxyLineContent"><span class="doxyHighlight">                              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1433</span><span class="doxyLineContent"><span class="doxyHighlight">                                </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!actualDoc.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1434</span><span class="doxyLineContent"><span class="doxyHighlight">                                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1435</span><span class="doxyLineContent"><span class="doxyHighlight">                                  <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7f982d756ed230a5a1c89755e80ee7f2">stripIndentationVerbatim</a>(actualDoc,yyextra-&gt;commentIndent);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1436</span><span class="doxyLineContent"><span class="doxyHighlight">                                  actualDoc.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(</span><span class="doxyHighlightStringLiteral">"@iverbatim\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1437</span><span class="doxyLineContent"><span class="doxyHighlight">                                  actualDoc.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">append</a>(</span><span class="doxyHighlightStringLiteral">"@endiverbatim "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1438</span><span class="doxyLineContent"><span class="doxyHighlight">                                }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1439</span><span class="doxyLineContent"><span class="doxyHighlight">                              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1440</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightComment">//printf("-------&gt; yyextra-&gt;current=%p yyextra-&gt;bodyEntry=%p\n",yyextra-&gt;current,yyextra-&gt;bodyEntry);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1441</span><span class="doxyLineContent"><span class="doxyHighlight">                              <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>(yyscanner, actualDoc, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1442</span><span class="doxyLineContent"><span class="doxyHighlight">                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1443</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;packageCommentAllowed) </span><span class="doxyHighlightComment">// expecting module docs</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1444</span><span class="doxyLineContent"><span class="doxyHighlight">                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1445</span><span class="doxyLineContent"><span class="doxyHighlight">                              <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> actualDoc=yyextra-&gt;docBlock;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1446</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;docBlockSpecial) </span><span class="doxyHighlightComment">// legacy unformatted docstring</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1447</span><span class="doxyLineContent"><span class="doxyHighlight">                              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1448</span><span class="doxyLineContent"><span class="doxyHighlight">                                </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!actualDoc.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1449</span><span class="doxyLineContent"><span class="doxyHighlight">                                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1450</span><span class="doxyLineContent"><span class="doxyHighlight">                                  <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7f982d756ed230a5a1c89755e80ee7f2">stripIndentationVerbatim</a>(actualDoc,yyextra-&gt;commentIndent);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1451</span><span class="doxyLineContent"><span class="doxyHighlight">                                  actualDoc.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(</span><span class="doxyHighlightStringLiteral">"@iverbatim\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1452</span><span class="doxyLineContent"><span class="doxyHighlight">                                  actualDoc.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">append</a>(</span><span class="doxyHighlightStringLiteral">"@endiverbatim "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1453</span><span class="doxyLineContent"><span class="doxyHighlight">                                }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1454</span><span class="doxyLineContent"><span class="doxyHighlight">                              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1455</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;moduleScope.startsWith(</span><span class="doxyHighlightStringLiteral">"__"</span><span class="doxyHighlight">) &amp;&amp;  yyextra-&gt;moduleScope.endsWith(</span><span class="doxyHighlightStringLiteral">"__"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1456</span><span class="doxyLineContent"><span class="doxyHighlight">                              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1457</span><span class="doxyLineContent"><span class="doxyHighlight">                                actualDoc.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(</span><span class="doxyHighlightStringLiteral">"\\namespace \\"</span><span class="doxyHighlight">+yyextra-&gt;moduleScope+</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1458</span><span class="doxyLineContent"><span class="doxyHighlight">                              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1459</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1460</span><span class="doxyLineContent"><span class="doxyHighlight">                              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1461</span><span class="doxyLineContent"><span class="doxyHighlight">                                actualDoc.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(</span><span class="doxyHighlightStringLiteral">"\\namespace "</span><span class="doxyHighlight">+yyextra-&gt;moduleScope+</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1462</span><span class="doxyLineContent"><span class="doxyHighlight">                              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1463</span><span class="doxyLineContent"><span class="doxyHighlight">                              <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>(yyscanner, actualDoc, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1464</span><span class="doxyLineContent"><span class="doxyHighlight">                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1465</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((yyextra-&gt;docBlockContext==ClassBody </span><span class="doxyHighlightComment">/*&amp;&amp; !yyextra-&gt;hideClassDocs*/</span><span class="doxyHighlight">) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1466</span><span class="doxyLineContent"><span class="doxyHighlight">                                yyextra-&gt;docBlockContext==FunctionBody)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1467</span><span class="doxyLineContent"><span class="doxyHighlight">                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1468</span><span class="doxyLineContent"><span class="doxyHighlight">                              yyextra-&gt;current-&gt;program &lt;&lt; yyextra-&gt;docBlock;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1469</span><span class="doxyLineContent"><span class="doxyHighlight">                              yyextra-&gt;current-&gt;program &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1470</span><span class="doxyLineContent"><span class="doxyHighlight">                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1471</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightComment">//if (yyextra-&gt;hideClassDocs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1472</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightComment">//{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1473</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightComment">//  yyextra-&gt;current-&gt;startLine = yyextra-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1474</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightComment">//}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1475</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightComment">//yyextra-&gt;hideClassDocs=FALSE;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1476</span><span class="doxyLineContent"><span class="doxyHighlight">                            BEGIN(yyextra-&gt;docBlockContext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1477</span><span class="doxyLineContent"><span class="doxyHighlight">                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1478</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1479</span><span class="doxyLineContent"><span class="doxyHighlight">                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1480</span><span class="doxyLineContent"><span class="doxyHighlight">                            yyextra-&gt;docBlock += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1481</span><span class="doxyLineContent"><span class="doxyHighlight">                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1482</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;packageCommentAllowed = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1483</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1484</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1485</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1486</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">^{BB}</span><span class="doxyHighlight">               { </span><span class="doxyHighlightComment">// leading whitespace, compensate for """! / '''!</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1487</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;firstPass &amp;&amp; yyextra-&gt;docBlockSpecial &amp;&amp; yyleng &gt;= yyextra-&gt;curIndent)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1488</span><span class="doxyLineContent"><span class="doxyHighlight">                            yyextra-&gt;docBlock += yytext + yyextra-&gt;curIndent;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1489</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1490</span><span class="doxyLineContent"><span class="doxyHighlight">                            yyextra-&gt;docBlock += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1491</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1492</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">[^"'\n \t\\@]+</span><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1493</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;docBlock += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1494</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1495</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">\n</span><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1496</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1497</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;docBlock += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1498</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1499</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{CMD}"ifile"{B}+"\""[^\n\"]+"\""</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1500</span><span class="doxyLineContent"><span class="doxyHighlight">                                    yyextra-&gt;fileName = &amp;yytext[6];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1501</span><span class="doxyLineContent"><span class="doxyHighlight">                                    yyextra-&gt;fileName = yyextra-&gt;fileName.stripWhiteSpace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1502</span><span class="doxyLineContent"><span class="doxyHighlight">                                    yyextra-&gt;fileName = yyextra-&gt;fileName.mid(1,yyextra-&gt;fileName.length()-2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1503</span><span class="doxyLineContent"><span class="doxyHighlight">                                    yyextra-&gt;docBlock+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1504</span><span class="doxyLineContent"><span class="doxyHighlight">                                  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1505</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{CMD}"ifile"{B}+{FILEMASK}</span><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1506</span><span class="doxyLineContent"><span class="doxyHighlight">                                    yyextra-&gt;fileName = &amp;yytext[6];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1507</span><span class="doxyLineContent"><span class="doxyHighlight">                                    yyextra-&gt;fileName = yyextra-&gt;fileName.stripWhiteSpace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1508</span><span class="doxyLineContent"><span class="doxyHighlight">                                    yyextra-&gt;docBlock+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1509</span><span class="doxyLineContent"><span class="doxyHighlight">                                  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1510</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{CMD}"iline"{LINENR}/[\n\.]</span><span class="doxyHighlight">   |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1511</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{CMD}"iline"{LINENR}{B}</span><span class="doxyHighlight">       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1512</span><span class="doxyLineContent"><span class="doxyHighlight">                                    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ok = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1513</span><span class="doxyLineContent"><span class="doxyHighlight">                                    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> nr = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(&amp;yytext[6]).<a href="/web-doxygen/docs/api/classes/qcstring/#a100a41fa6ba318b8b2ace175cd20f1eb">toInt</a>(&amp;ok);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1514</span><span class="doxyLineContent"><span class="doxyHighlight">                                    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ok)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1515</span><span class="doxyLineContent"><span class="doxyHighlight">                                    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1516</span><span class="doxyLineContent"><span class="doxyHighlight">                                      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(yyextra-&gt;fileName,yyextra-&gt;yyLineNr,</span><span class="doxyHighlightStringLiteral">"Invalid line number '{}' for iline command"</span><span class="doxyHighlight">,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1517</span><span class="doxyLineContent"><span class="doxyHighlight">                                    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1518</span><span class="doxyLineContent"><span class="doxyHighlight">                                    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1519</span><span class="doxyLineContent"><span class="doxyHighlight">                                    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1520</span><span class="doxyLineContent"><span class="doxyHighlight">                                      yyextra-&gt;yyLineNr = nr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1521</span><span class="doxyLineContent"><span class="doxyHighlight">                                    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1522</span><span class="doxyLineContent"><span class="doxyHighlight">                                    yyextra-&gt;docBlock+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1523</span><span class="doxyLineContent"><span class="doxyHighlight">                                  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1524</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">({CMD}{CMD}){ID}/[^a-z_A-Z0-9]</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// escaped command</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1525</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;docBlock+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1526</span><span class="doxyLineContent"><span class="doxyHighlight">                                  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1527</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">\\.</span><span class="doxyHighlight">                 { </span><span class="doxyHighlightComment">// escaped char TO be extended</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1528</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;docBlock += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1529</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1530</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">.</span><span class="doxyHighlight">                   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1531</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;docBlock += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1532</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1533</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1534</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1535</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SpecialComment&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1536</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">^{B}"#"("#")*</span><span class="doxyHighlight">       { </span><span class="doxyHighlightComment">// skip leading hashes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1537</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1538</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">\n/{B}"#"</span><span class="doxyHighlight">           { </span><span class="doxyHighlightComment">// continuation of the comment on the next line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1539</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;docBlock+=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1540</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;docBrief = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1541</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1542</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1543</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{CMD}"ifile"{B}+"\""[^\n\"]+"\""</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1544</span><span class="doxyLineContent"><span class="doxyHighlight">                                    yyextra-&gt;fileName = &amp;yytext[6];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1545</span><span class="doxyLineContent"><span class="doxyHighlight">                                    yyextra-&gt;fileName = yyextra-&gt;fileName.stripWhiteSpace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1546</span><span class="doxyLineContent"><span class="doxyHighlight">                                    yyextra-&gt;fileName = yyextra-&gt;fileName.mid(1,yyextra-&gt;fileName.length()-2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1547</span><span class="doxyLineContent"><span class="doxyHighlight">                                    yyextra-&gt;docBlock+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1548</span><span class="doxyLineContent"><span class="doxyHighlight">                                  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1549</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{CMD}"ifile"{B}+{FILEMASK}</span><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1550</span><span class="doxyLineContent"><span class="doxyHighlight">                                    yyextra-&gt;fileName = &amp;yytext[6];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1551</span><span class="doxyLineContent"><span class="doxyHighlight">                                    yyextra-&gt;fileName = yyextra-&gt;fileName.stripWhiteSpace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1552</span><span class="doxyLineContent"><span class="doxyHighlight">                                    yyextra-&gt;docBlock+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1553</span><span class="doxyLineContent"><span class="doxyHighlight">                                  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1554</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{CMD}"iline"{LINENR}/[\n\.]</span><span class="doxyHighlight">   |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1555</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{CMD}"iline"{LINENR}{B}</span><span class="doxyHighlight">       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1556</span><span class="doxyLineContent"><span class="doxyHighlight">                                    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ok = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1557</span><span class="doxyLineContent"><span class="doxyHighlight">                                    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> nr = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(&amp;yytext[6]).<a href="/web-doxygen/docs/api/classes/qcstring/#a100a41fa6ba318b8b2ace175cd20f1eb">toInt</a>(&amp;ok);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1558</span><span class="doxyLineContent"><span class="doxyHighlight">                                    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ok)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1559</span><span class="doxyLineContent"><span class="doxyHighlight">                                    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1560</span><span class="doxyLineContent"><span class="doxyHighlight">                                      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(yyextra-&gt;fileName,yyextra-&gt;yyLineNr,</span><span class="doxyHighlightStringLiteral">"Invalid line number '{}' for iline command"</span><span class="doxyHighlight">,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1561</span><span class="doxyLineContent"><span class="doxyHighlight">                                    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1562</span><span class="doxyLineContent"><span class="doxyHighlight">                                    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1563</span><span class="doxyLineContent"><span class="doxyHighlight">                                    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1564</span><span class="doxyLineContent"><span class="doxyHighlight">                                      yyextra-&gt;yyLineNr = nr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1565</span><span class="doxyLineContent"><span class="doxyHighlight">                                    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1566</span><span class="doxyLineContent"><span class="doxyHighlight">                                    yyextra-&gt;docBlock+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1567</span><span class="doxyLineContent"><span class="doxyHighlight">                                  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1568</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">({CMD}{CMD}){ID}/[^a-z_A-Z0-9]</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// escaped command</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1569</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;docBlock+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1570</span><span class="doxyLineContent"><span class="doxyHighlight">                                  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1571</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\ilinebr "{B}*</span><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1572</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> indent;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1573</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> extraSpaces = std::max(0,</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(yyleng-9-yyextra-&gt;curIndent-2));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1574</span><span class="doxyLineContent"><span class="doxyHighlight">                          indent.<a href="/web-doxygen/docs/api/classes/qcstring/#a08003d3e6c9acc46e4d392612ba492f7">fill</a>(</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">,extraSpaces);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1575</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightComment">//printf("extraSpaces=%d\n",extraSpaces);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1576</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;docBlock += </span><span class="doxyHighlightStringLiteral">"\\ilinebr "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1577</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;docBlock += indent;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1578</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1579</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">[^#\\@\n]+</span><span class="doxyHighlight">          { </span><span class="doxyHighlightComment">// any other stuff</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1580</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;docBlock+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1581</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1582</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">\n</span><span class="doxyHighlight">                  { </span><span class="doxyHighlightComment">// new line that ends the comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1583</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>(yyscanner, yyextra-&gt;docBlock, yyextra-&gt;docBrief);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1584</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;docBlockContext == VariableEnd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1585</span><span class="doxyLineContent"><span class="doxyHighlight">                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1586</span><span class="doxyLineContent"><span class="doxyHighlight">                            unput(*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1587</span><span class="doxyLineContent"><span class="doxyHighlight">                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1588</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1589</span><span class="doxyLineContent"><span class="doxyHighlight">                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1590</span><span class="doxyLineContent"><span class="doxyHighlight">                            <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1591</span><span class="doxyLineContent"><span class="doxyHighlight">                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1592</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN(yyextra-&gt;docBlockContext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1593</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1594</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">.</span><span class="doxyHighlight">                   { </span><span class="doxyHighlightComment">// anything we missed</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1595</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;docBlock+=*yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1596</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1597</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1598</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1599</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SingleQuoteString&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1600</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">\\{B}\n</span><span class="doxyHighlight">                    { </span><span class="doxyHighlightComment">// line continuation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1601</span><span class="doxyLineContent"><span class="doxyHighlight">                                 <a href="#af99856e2fbe8c4e1f9ddd308cc5237de">addToString</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1602</span><span class="doxyLineContent"><span class="doxyHighlight">                                 <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1603</span><span class="doxyLineContent"><span class="doxyHighlight">                               }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1604</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">\\.</span><span class="doxyHighlight">                        { </span><span class="doxyHighlightComment">// escaped char</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1605</span><span class="doxyLineContent"><span class="doxyHighlight">                                 <a href="#af99856e2fbe8c4e1f9ddd308cc5237de">addToString</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1606</span><span class="doxyLineContent"><span class="doxyHighlight">                               }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1607</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\"\"\""</span><span class="doxyHighlight">                   { </span><span class="doxyHighlightComment">// triple double quotes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1608</span><span class="doxyLineContent"><span class="doxyHighlight">                                 <a href="#af99856e2fbe8c4e1f9ddd308cc5237de">addToString</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1609</span><span class="doxyLineContent"><span class="doxyHighlight">                               }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1610</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">                        { </span><span class="doxyHighlightComment">// end of the string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1611</span><span class="doxyLineContent"><span class="doxyHighlight">                                 <a href="#af99856e2fbe8c4e1f9ddd308cc5237de">addToString</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1612</span><span class="doxyLineContent"><span class="doxyHighlight">                                 BEGIN(yyextra-&gt;stringContext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1613</span><span class="doxyLineContent"><span class="doxyHighlight">                               }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1614</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">[^"'\n\\]+</span><span class="doxyHighlight">                 { </span><span class="doxyHighlightComment">// normal chars</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1615</span><span class="doxyLineContent"><span class="doxyHighlight">                                 <a href="#af99856e2fbe8c4e1f9ddd308cc5237de">addToString</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1616</span><span class="doxyLineContent"><span class="doxyHighlight">                               }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1617</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">.</span><span class="doxyHighlight">                          { </span><span class="doxyHighlightComment">// normal char</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1618</span><span class="doxyLineContent"><span class="doxyHighlight">                                 <a href="#af99856e2fbe8c4e1f9ddd308cc5237de">addToString</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1619</span><span class="doxyLineContent"><span class="doxyHighlight">                               }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1620</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1621</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1622</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DoubleQuoteString&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1623</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">\\{B}\n</span><span class="doxyHighlight">                    { </span><span class="doxyHighlightComment">// line continuation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1624</span><span class="doxyLineContent"><span class="doxyHighlight">                                 <a href="#af99856e2fbe8c4e1f9ddd308cc5237de">addToString</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1625</span><span class="doxyLineContent"><span class="doxyHighlight">                                 <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1626</span><span class="doxyLineContent"><span class="doxyHighlight">                               }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1627</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">\\.</span><span class="doxyHighlight">                        { </span><span class="doxyHighlightComment">// escaped char</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1628</span><span class="doxyLineContent"><span class="doxyHighlight">                                 <a href="#af99856e2fbe8c4e1f9ddd308cc5237de">addToString</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1629</span><span class="doxyLineContent"><span class="doxyHighlight">                               }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1630</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"'''"</span><span class="doxyHighlight">                      { </span><span class="doxyHighlightComment">// triple single quotes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1631</span><span class="doxyLineContent"><span class="doxyHighlight">                                 <a href="#af99856e2fbe8c4e1f9ddd308cc5237de">addToString</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1632</span><span class="doxyLineContent"><span class="doxyHighlight">                               }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1633</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">                       { </span><span class="doxyHighlightComment">// end of the string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1634</span><span class="doxyLineContent"><span class="doxyHighlight">                                 <a href="#af99856e2fbe8c4e1f9ddd308cc5237de">addToString</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1635</span><span class="doxyLineContent"><span class="doxyHighlight">                                 BEGIN(yyextra-&gt;stringContext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1636</span><span class="doxyLineContent"><span class="doxyHighlight">                               }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1637</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">[^"'\n\\]+</span><span class="doxyHighlight">                 { </span><span class="doxyHighlightComment">// normal chars</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1638</span><span class="doxyLineContent"><span class="doxyHighlight">                                 <a href="#af99856e2fbe8c4e1f9ddd308cc5237de">addToString</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1639</span><span class="doxyLineContent"><span class="doxyHighlight">                               }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1640</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">.</span><span class="doxyHighlight">                          { </span><span class="doxyHighlightComment">// normal char</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1641</span><span class="doxyLineContent"><span class="doxyHighlight">                                 <a href="#af99856e2fbe8c4e1f9ddd308cc5237de">addToString</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1642</span><span class="doxyLineContent"><span class="doxyHighlight">                               }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1643</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1644</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1645</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;TripleString&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1646</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{ENDTRIDOUBLEQUOTE}</span><span class="doxyHighlight">    |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1647</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">{ENDTRISINGLEQUOTE}</span><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1648</span><span class="doxyLineContent"><span class="doxyHighlight">                          *yyextra-&gt;copyString &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1649</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;doubleQuote==(yytext[0]==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1650</span><span class="doxyLineContent"><span class="doxyHighlight">                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1651</span><span class="doxyLineContent"><span class="doxyHighlight">                            BEGIN(yyextra-&gt;stringContext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1652</span><span class="doxyLineContent"><span class="doxyHighlight">                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1653</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1654</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1655</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1656</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">({LONGSTRINGBLOCK})</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1657</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#a6256e57feb94db36e0dd7c3c83c9180a">lineCount</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1658</span><span class="doxyLineContent"><span class="doxyHighlight">                          *yyextra-&gt;copyString &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1659</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1660</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">\n</span><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1661</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1662</span><span class="doxyLineContent"><span class="doxyHighlight">                          *yyextra-&gt;copyString &lt;&lt; yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1663</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1664</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">.</span><span class="doxyHighlight">                   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1665</span><span class="doxyLineContent"><span class="doxyHighlight">                          *yyextra-&gt;copyString &lt;&lt; *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1666</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1667</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1668</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1669</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Decorator&gt;{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1670</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">{TRIDOUBLEQUOTE}</span><span class="doxyHighlight">     { </span><span class="doxyHighlightComment">// start of a comment block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1671</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;doubleQuote=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1672</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;decoratorCommentStr.str(std::string());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1673</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;copyString=&amp;yyextra-&gt;decoratorCommentStr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1674</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;stringContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1675</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN(TripleString);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1676</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1677</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1678</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">{TRISINGLEQUOTE}</span><span class="doxyHighlight">     { </span><span class="doxyHighlightComment">// start of a comment block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1679</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;doubleQuote=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1680</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;decoratorCommentStr.str(std::string());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1681</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;copyString=&amp;yyextra-&gt;decoratorCommentStr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1682</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;stringContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1683</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN(TripleString);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1684</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1685</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1686</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;stringContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1687</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;decoratorCommentStr.str(std::string());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1688</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;copyString=&amp;yyextra-&gt;decoratorCommentStr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1689</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN( SingleQuoteString );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1690</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1691</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1692</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;stringContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1693</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;decoratorCommentStr.str(std::string());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1694</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;copyString=&amp;yyextra-&gt;decoratorCommentStr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1695</span><span class="doxyLineContent"><span class="doxyHighlight">                          BEGIN( DoubleQuoteString );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1696</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1697</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"("</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1698</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;decoratorRound++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1699</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1700</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">")"</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1701</span><span class="doxyLineContent"><span class="doxyHighlight">                          yyextra-&gt;decoratorRound--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1702</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;decoratorRound) BEGIN( <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">Search</a> );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1703</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1704</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">\n</span><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1705</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#a062cea4ebaac0ec4861bdf89dbde1b00">incLineNr</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1706</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1707</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">.</span><span class="doxyHighlight">                   { }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1708</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1709</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1710</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/* ------------ End rules -------------- */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1711</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1712</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/*</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1713</span><span class="doxyLineContent"><span class="doxyHighlightComment">&lt;*&gt;({NONEMPTY}|{EXPCHAR}|{BB})           { // This should go one character at a time.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1714</span><span class="doxyLineContent"><span class="doxyHighlightComment">                                 // printf("[pyscanner] '%s' [ state %d ]  [line %d] no match\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1715</span><span class="doxyLineContent"><span class="doxyHighlightComment">                                 //       yytext, YY_START, yyextra-&gt;yyLineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1716</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1717</span><span class="doxyLineContent"><span class="doxyHighlightComment">                               }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1718</span><span class="doxyLineContent"><span class="doxyHighlightComment">  */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1719</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1720</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;{NEWLINE}</span><span class="doxyHighlight">                   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1721</span><span class="doxyLineContent"><span class="doxyHighlight">                                 </span><span class="doxyHighlightComment">//printf("[pyscanner] %d NEWLINE [line %d] no match\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1722</span><span class="doxyLineContent"><span class="doxyHighlight">                                 </span><span class="doxyHighlightComment">//       YY_START, yyextra-&gt;yyLineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1723</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1724</span><span class="doxyLineContent"><span class="doxyHighlight">                                 <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#a6256e57feb94db36e0dd7c3c83c9180a">lineCount</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1725</span><span class="doxyLineContent"><span class="doxyHighlight">                               }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1726</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1727</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;"'"</span><span class="doxyHighlight">                         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1728</span><span class="doxyLineContent"><span class="doxyHighlight">                                 </span><span class="doxyHighlightComment">//fprintf(stderr,"Quote: %d\n",YY_START);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1729</span><span class="doxyLineContent"><span class="doxyHighlight">                               }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1730</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1731</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;.</span><span class="doxyHighlight">                           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1732</span><span class="doxyLineContent"><span class="doxyHighlight">                                 </span><span class="doxyHighlightComment">//printf("[pyscanner] '%s' [ state %d ]  [line %d] no match\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1733</span><span class="doxyLineContent"><span class="doxyHighlight">                                 </span><span class="doxyHighlightComment">//       yytext, YY_START, yyextra-&gt;yyLineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1734</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1735</span><span class="doxyLineContent"><span class="doxyHighlight">                               }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1736</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1737</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1738</span><span class="doxyLineContent"><span class="doxyHighlight">%%</span></span></div>

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



<p>Definition at line 1742 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5edfc25f0c460f3263fdb340f7a02b03">1742</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/code-l/#a5edfc25f0c460f3263fdb340f7a02b03">yyread</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *buf,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> max_size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1743</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1744</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1745</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> c=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1746</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p = yyextra-&gt;inputString + yyextra-&gt;inputPosition;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1747</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ( c &lt; max_size &amp;&amp; *p ) { *buf++ = *p++; c++; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1748</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputPosition+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1749</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1750</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

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



<p>Definition at line 65 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a234e2efe67eececd88b140b46ea37463">65</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DBG_CTX(x) do { } while(0)</span></span></div>

</div>

</div>
</div>

### unput\_string {#a86da2f5e3360caa90276fc24433d9512}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define unput_string(yytext, yyleng)&nbsp;&nbsp;&nbsp;do { for (int i=(int)yyleng-1;i&gt;=0;i--) unput(yytext[i]); } while(0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a86da2f5e3360caa90276fc24433d9512">70</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define unput_string(yytext,yyleng) do { for (int i=(int)yyleng-1;i&gt;=0;i--) unput(yytext[i]); } while(0)</span></span></div>

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



<p>Definition at line 161 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aacfdca45fa4beb8b06172525a53c424a">161</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define YY_INPUT(buf,result,max_size) result=yyread(yyscanner,buf,max_size);</span></span></div>

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



<p>Definition at line 67 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a85523a0c7d95c059d251b4e9829947aa">67</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define YY_NO_INPUT 1</span></span></div>

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



<p>Definition at line 68 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae78ac56cd1f29572e967ed7636952d15">68</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define YY_NO_UNISTD_H 1</span></span></div>

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



<p>Definition at line 29 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5d5508008cac8fb66fca3baa4e9b6584">29</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define YY_TYPEDEF_YY_SCANNER_T</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
