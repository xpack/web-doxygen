---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/configimpl-l
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `configimpl.l` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;stdint.h&gt;
#include &lt;stdio.h&gt;
#include &lt;stdlib.h&gt;
#include &lt;assert.h&gt;
#include &lt;ctype.h&gt;
#include &lt;stdarg.h&gt;
#include &lt;errno.h&gt;
#include &lt;thread&gt;
#include &lt;algorithm&gt;
#include &lt;iostream&gt;
#include &lt;iomanip&gt;
#include &lt;cstdint&gt;
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>"
#include "version.h"
#include "<a href="/web-doxygen/docs/api/files/src/portable-h">portable.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/language-h">language.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/configoptions-h">configoptions.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/fileinfo-h">fileinfo.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dotattributes-h">dotattributes.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-lex-h">doxygen_lex.h</a>"
#include "configimpl.l.h"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/configfilestate">ConfigFileState</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c24725da6b5b59e4c8867995e84648f">configStringRecode</a> (const QCString &amp;str, const QCString &amp;fromEncoding, const QCString &amp;toEncoding)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c20e33d84d7477620edc8cdf3e3333b">containsEnvVar</a> (QCString &amp;str)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48749817b1eba2606c9762ba1bb4d43b">convertToComment</a> (const QCString &amp;s, const QCString &amp;u)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b04c2a27074eeeccf2fadb03b80fc42">convertStringToBool</a> (const QCString &amp;str, bool &amp;isValid)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3e4b97ae438d8bc8a2ae5deedd523a7">yyread</a> (char *buf, int max_size)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38bfc7b0b040cc8ceefae240aad38b94">checkEncoding</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84908cbd8715e1a9294673286a5f7b6e">stripComment</a> (const QCString &amp;s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48eae5f8b7d851992e7b3e04a01a8af3">processStoreRepl</a> (QCString &amp;storeReplStr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53f751007ffe5b7c105c3821039a970c">processString</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1004c5eacd365bb12bb64c344baeebc6">processList</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static FILE *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae6d9aa97d4044248e4537678a0a38af">tryPath</a> (const QCString &amp;path, const QCString &amp;fileName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a850b28ffc2fc2f5225b6d61b09a70dd5">substEnvVarsInStrList</a> (StringVector &amp;sl)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcf1a493801a3f065ef9ca18e7c4f6c6">substEnvVarsInString</a> (QCString &amp;s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static FILE *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6232960902cd961ee248851d0f5a189d">findFile</a> (const QCString &amp;fileName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a692163c1902febf3d5dc44644e851f26">readIncludeFile</a> (const QCString &amp;incName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a7bd1b3d14701eb97c03f3ef34deff1">yylex</a> (void)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6acafb836a24013a01bc21ab92381ad7">configFileToString</a> (const QCString &amp;name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa60539b340894c76de2aa43ef25aede5">cleanUpPaths</a> (StringVector &amp;str)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac191ad1786e980d514c4535505cf99d6">checkFileName</a> (const QCString &amp;s, const char *optionName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb0ac5ce17fb9a60710a1ad77a2ebb14">checkList</a> (const StringVector &amp;list, const char *name, bool equalRequired, bool valueRequired)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8f84f9572072b97ac930fb0f1a7ba9f">adjustBoolSetting</a> (const char *depOption, const char *optionName, bool expectedValue)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fba7b39cbe6dd4fe499dcd29ae2af0c">adjustStringSetting</a> (const char *depOption, const char *optionName, const QCString &amp;expectedValue)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16c4b1e165f06becc4b5debd88592a49">adjustColorStyleSetting</a> (const char *depOption)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ab01907c143c95a407993630bdfeba9">updateAttribute</a> (DotAttributes &amp;attr, QCString name, ConfigObsolete *value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b306c7d6514a51d731a5b581ce6c2a4">warning_str</a> = "warning: "</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adda1f8011db5f4f0ec3d8ece91cfa724">error_str</a> = "error: "</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4884b04c016cb29c59e337c3849a08fd">g_inputString</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f7e5ad6f4837038547f7d2ea8e031eb">g_inputPosition</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a> = 1</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afec8ce807dc9bf79f073fa691fafe1f8">g_yyFileName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80001906a82b0d116f334f0bb065c7a9">g_cmd</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b72791268d83dc5adf869ac258a3027">g_string</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d73b052225d65c218ae7d286d8c633a">g_list</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad33b30a9730e3f9332e7eb36152f4276">g_listStr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a848459ef910ecc5e245bc68972a9aeac">g_includePathList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::vector&lt; std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/configfilestate">ConfigFileState</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53705fefd416a984be4714f1d0ca36a6">g_includeStack</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73e0a7c37c8a540748c113811329f998">g_configUpdate</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d031dea12ce5dfc5759802ec854c2d2">g_encoding</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/configimpl">ConfigImpl</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8c998011c1de1f3c38cb48c908af98b">g_config</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940">Config::CompareMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba980278adc63976f725abf4f355309c">g_compareMode</a> = <a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940abbd47109890259c0127154db1af26c75">Config::CompareMode::Full</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24aadc37dfae7cbd3b93643cec296bab">g_localStoreRepl</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static const <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93417da3de847772a0db1c1067124b57">reEnvVar</a>(R"(\$\((\a[\w.-]*)\))")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static const <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ef2cd114dfa4c36bb86f42ec41c74ea">reEnvVarExt</a>(R"(\$\((\a[\w.-]*\(\a[\w.-]*\))\))")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static const <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8742d431dca72b48403598209fa3278">reEnvVarCMake</a>(R"(@\a\w*@)")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static const <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad46c127e61124d3dae3308327103a2b4">reEnvVar1CMake</a>(R"(\${\a\w*})")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc983123ed5d1694a014d1ea7c1f22cb">SHOW_INCLUDES</a>&nbsp;&nbsp;&nbsp;0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a641f7209d924c2c4cb24420dcd631f37">MAX_INCLUDE_DEPTH</a>&nbsp;&nbsp;&nbsp;10</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15b85de192a189d5a31cdd518e001e6e">YY_NEVER_INTERACTIVE</a>&nbsp;&nbsp;&nbsp;1</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacfdca45fa4beb8b06172525a53c424a">YY_INPUT</a>(buf, result, max_size)&nbsp;&nbsp;&nbsp;result=<a href="/web-doxygen/docs/api/files/src/code-l/#a5edfc25f0c460f3263fdb340f7a02b03">yyread</a>(buf,max_size);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a146a93da1f8efdea496a6d138d4773bc">LEX_NO_REENTRANT</a></td>
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

## Functions

### adjustBoolSetting() {#ad8f84f9572072b97ac930fb0f1a7ba9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void adjustBoolSetting (const char * depOption, const char * optionName, bool expectedValue)</td>
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



<p>Definition at line 1697 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad8f84f9572072b97ac930fb0f1a7ba9f">1697</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad8f84f9572072b97ac930fb0f1a7ba9f">adjustBoolSetting</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *depOption, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *optionName,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> expectedValue)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1698</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1699</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// lookup option by name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1700</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> ConfigValues::Info *option = ConfigValues::instance().get(optionName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1701</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (option &amp;&amp; option-&gt;type==ConfigValues::Info::Bool) </span><span class="doxyHighlightComment">// safety check</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1702</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1703</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ConfigValues::instance().*(option-&gt;value.b)!=expectedValue) </span><span class="doxyHighlightComment">// current value differs from expectation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1704</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1705</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"When enabling {} the {} option should be {}. I'll adjust it for you.\n"</span><span class="doxyHighlight">,depOption,optionName,expectedValue? </span><span class="doxyHighlightStringLiteral">"enabled"</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">"disabled"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1706</span><span class="doxyLineContent"><span class="doxyHighlight">      ConfigValues::instance().*(option-&gt;value.b)=expectedValue; </span><span class="doxyHighlightComment">// adjust option</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1707</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1708</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1709</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/namespaces/config/#a43f9512cdb148a0f68a30519debac43f">Config::checkAndCorrect</a>.</p>

</div>
</div>

### adjustColorStyleSetting() {#a16c4b1e165f06becc4b5debd88592a49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void adjustColorStyleSetting (const char * depOption)</td>
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



<p>Definition at line 1725 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a16c4b1e165f06becc4b5debd88592a49">1725</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a16c4b1e165f06becc4b5debd88592a49">adjustColorStyleSetting</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *depOption)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1726</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1727</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> updateColorStyle = [&amp;depOption](HTML_COLORSTYLE_t curStyle,HTML_COLORSTYLE_t newStyle)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1728</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1729</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"When enabling '{}' the 'HTML_COLORSTYLE' option should be either 'LIGHT' or 'DARK' but has value '{}'. I'll adjust it for you to '{}'.\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1730</span><span class="doxyLineContent"><span class="doxyHighlight">        depOption,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1731</span><span class="doxyLineContent"><span class="doxyHighlight">        HTML_COLORSTYLE_enum2str(curStyle),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1732</span><span class="doxyLineContent"><span class="doxyHighlight">        HTML_COLORSTYLE_enum2str(newStyle));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1733</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/config-h/#a8c58e5a30ece3e745e1561edd00f6c68">Config_updateEnum</a>(HTML_COLORSTYLE,newStyle);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1734</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1735</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> colorStyle = <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(HTML_COLORSTYLE);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1736</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (colorStyle)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1737</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1738</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> HTML_COLORSTYLE_t::LIGHT:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1739</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> HTML_COLORSTYLE_t::DARK:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1740</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// no adjustment needed</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1741</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1742</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> HTML_COLORSTYLE_t::AUTO_LIGHT:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1743</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> HTML_COLORSTYLE_t::TOGGLE:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1744</span><span class="doxyLineContent"><span class="doxyHighlight">      updateColorStyle(colorStyle,HTML_COLORSTYLE_t::LIGHT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1745</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1746</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> HTML_COLORSTYLE_t::AUTO_DARK:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1747</span><span class="doxyLineContent"><span class="doxyHighlight">      updateColorStyle(colorStyle,HTML_COLORSTYLE_t::DARK);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1748</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1749</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1750</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a8c58e5a30ece3e745e1561edd00f6c68">Config_updateEnum</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/namespaces/config/#a43f9512cdb148a0f68a30519debac43f">Config::checkAndCorrect</a>.</p>

</div>
</div>

### adjustStringSetting() {#a0fba7b39cbe6dd4fe499dcd29ae2af0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void adjustStringSetting (const char * depOption, const char * optionName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; expectedValue)</td>
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



<p>Definition at line 1711 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0fba7b39cbe6dd4fe499dcd29ae2af0c">1711</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0fba7b39cbe6dd4fe499dcd29ae2af0c">adjustStringSetting</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *depOption, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *optionName,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;expectedValue)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1712</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1713</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// lookup option by name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1714</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> ConfigValues::Info *option = ConfigValues::instance().get(optionName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1715</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (option &amp;&amp; option-&gt;type==ConfigValues::Info::String) </span><span class="doxyHighlightComment">// safety check</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1716</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1717</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ConfigValues::instance().*(option-&gt;value.s)!=expectedValue) </span><span class="doxyHighlightComment">// current value differs from expectation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1718</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1719</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"When enabling {} the {} option should have value '{}'. I'll adjust it for you.\n"</span><span class="doxyHighlight">,depOption,optionName,expectedValue);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1720</span><span class="doxyLineContent"><span class="doxyHighlight">      ConfigValues::instance().*(option-&gt;value.s)=expectedValue; </span><span class="doxyHighlightComment">// adjust option</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1721</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1722</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1723</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/namespaces/config/#a43f9512cdb148a0f68a30519debac43f">Config::checkAndCorrect</a>.</p>

</div>
</div>

### checkEncoding() {#a38bfc7b0b040cc8ceefae240aad38b94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void checkEncoding ()</td>
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



<p>Definition at line 726 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a38bfc7b0b040cc8ceefae240aad38b94">726</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a38bfc7b0b040cc8ceefae240aad38b94">checkEncoding</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">727</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">728</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/configstring">ConfigString</a> *option = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configstring">ConfigString</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#ac8c998011c1de1f3c38cb48c908af98b">g_config</a>-&gt;get(</span><span class="doxyHighlightStringLiteral">"DOXYFILE_ENCODING"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">729</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1d031dea12ce5dfc5759802ec854c2d2">g_encoding</a> = *option-&gt;<a href="/web-doxygen/docs/api/classes/configstring/#a995a4f0d9d2799e285fd454dddb6b0f4">valueRef</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">730</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#ac8c998011c1de1f3c38cb48c908af98b">g_config</a>, <a href="#a1d031dea12ce5dfc5759802ec854c2d2">g_encoding</a> and <a href="/web-doxygen/docs/api/classes/configstring/#a995a4f0d9d2799e285fd454dddb6b0f4">ConfigString::valueRef</a>.</p>


<p>Referenced by <a href="#a53f751007ffe5b7c105c3821039a970c">processString</a>.</p>

</div>
</div>

### checkFileName() {#ac191ad1786e980d514c4535505cf99d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool checkFileName (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s, const char * optionName)</td>
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



<p>Definition at line 1649 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac191ad1786e980d514c4535505cf99d6">1649</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ac191ad1786e980d514c4535505cf99d6">checkFileName</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *optionName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1650</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1651</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> val = s.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1652</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((val==</span><span class="doxyHighlightStringLiteral">"yes"</span><span class="doxyHighlight"> || val==</span><span class="doxyHighlightStringLiteral">"true"</span><span class="doxyHighlight">  || val==</span><span class="doxyHighlightStringLiteral">"1"</span><span class="doxyHighlight"> || val==</span><span class="doxyHighlightStringLiteral">"all"</span><span class="doxyHighlight">) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1653</span><span class="doxyLineContent"><span class="doxyHighlight">      (val==</span><span class="doxyHighlightStringLiteral">"no"</span><span class="doxyHighlight">  || val==</span><span class="doxyHighlightStringLiteral">"false"</span><span class="doxyHighlight"> || val==</span><span class="doxyHighlightStringLiteral">"0"</span><span class="doxyHighlight"> || val==</span><span class="doxyHighlightStringLiteral">"none"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1654</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1655</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"file name expected for option {}, got {} instead. Ignoring...\n"</span><span class="doxyHighlight">,optionName,s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1656</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1657</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1658</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1659</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/namespaces/config/#a43f9512cdb148a0f68a30519debac43f">Config::checkAndCorrect</a>.</p>

</div>
</div>

### checkList() {#abb0ac5ce17fb9a60710a1ad77a2ebb14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void checkList (const <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> &amp; list, const char * name, bool equalRequired, bool valueRequired)</td>
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



<p>Definition at line 1667 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abb0ac5ce17fb9a60710a1ad77a2ebb14">1667</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abb0ac5ce17fb9a60710a1ad77a2ebb14">checkList</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> &amp;list,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *name, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> equalRequired,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> valueRequired)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1668</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1669</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;s: list)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1670</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1671</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> item=s.c_str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1672</span><span class="doxyLineContent"><span class="doxyHighlight">    item=item.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1673</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=item.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'='</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1674</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i==-1 &amp;&amp; equalRequired)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1675</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1676</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Illegal format for option {}, no equal sign ('=') specified for item '{}'\n"</span><span class="doxyHighlight">,name,item);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1677</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1678</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1679</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1680</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> myName=item.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(i).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1681</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (myName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1682</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1683</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Illegal format for option {}, no name specified for item '{}'\n"</span><span class="doxyHighlight">,name,item);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1684</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1685</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (valueRequired)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1686</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1687</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> myValue=item.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(item.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-i-1).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1688</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (myValue.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1689</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1690</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Illegal format for option {}, no value specified for item '{}'\n"</span><span class="doxyHighlight">,name,item);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1691</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1692</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1693</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1694</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1695</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">QCString::right</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/namespaces/config/#a43f9512cdb148a0f68a30519debac43f">Config::checkAndCorrect</a>.</p>

</div>
</div>

### cleanUpPaths() {#aa60539b340894c76de2aa43ef25aede5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void cleanUpPaths (<a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> &amp; str)</td>
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



<p>Definition at line 1630 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa60539b340894c76de2aa43ef25aede5">1630</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa60539b340894c76de2aa43ef25aede5">cleanUpPaths</a>(<a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> &amp;str)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1631</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1632</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;i&lt;str.size();i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1633</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1634</span><span class="doxyLineContent"><span class="doxyHighlight">    std::string path = str[i];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1635</span><span class="doxyLineContent"><span class="doxyHighlight">    std::replace(path.begin(),path.end(),</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">,</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1636</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((path[0]!=</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight"> &amp;&amp; (path.size()&lt;=2 || path[1]!=</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight">)) || path[path.size()-1]!=</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1637</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1638</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fi(path);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1639</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>() &amp;&amp; fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#aa941e087c82c28ff498d9d3dec551b1f">isDir</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1640</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1641</span><span class="doxyLineContent"><span class="doxyHighlight">        path = fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#af69e3949475014dcdbd504d742bdf270">absFilePath</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1642</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (path[path.size()-1]!=</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">) path+=</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1643</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1644</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1645</span><span class="doxyLineContent"><span class="doxyHighlight">    str[i]=path;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1646</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1647</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/fileinfo/#af69e3949475014dcdbd504d742bdf270">FileInfo::absFilePath</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">FileInfo::exists</a> and <a href="/web-doxygen/docs/api/classes/fileinfo/#aa941e087c82c28ff498d9d3dec551b1f">FileInfo::isDir</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/namespaces/config/#a43f9512cdb148a0f68a30519debac43f">Config::checkAndCorrect</a>.</p>

</div>
</div>

### configFileToString() {#a6acafb836a24013a01bc21ab92381ad7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString configFileToString (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



<p>Definition at line 1569 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6acafb836a24013a01bc21ab92381ad7">1569</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a6acafb836a24013a01bc21ab92381ad7">configFileToString</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1570</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1571</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (name.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1572</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1573</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> stream2string = [](std::istream &amp;in) -&gt; std::string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1574</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1575</span><span class="doxyLineContent"><span class="doxyHighlight">    std::string ret;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1576</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> buffer[4096];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1577</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (in.read(buffer, </span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(buffer))) ret.append(buffer, </span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(buffer));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1578</span><span class="doxyLineContent"><span class="doxyHighlight">    ret.append(buffer, </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight">uint32_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(in.gcount()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1579</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ret.empty() &amp;&amp; ret[ret.length()-1]!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) ret+=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// to help the scanner</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1580</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> ret;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1581</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1582</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1583</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (name==</span><span class="doxyHighlightStringLiteral">"-"</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// read from stdin</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1584</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1585</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// read contents from stdin into contents string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1586</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> stream2string(std::cin);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1587</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1588</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// read from file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1589</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1590</span><span class="doxyLineContent"><span class="doxyHighlight">    std::ifstream f = <a href="/web-doxygen/docs/api/namespaces/portable/#a0579eaf8c245a77f1e804a3cf1b0aa73">Portable::openInputStream</a>(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1591</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!f.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1592</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1593</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/configimpl/#a0b752f150eb5a0ec002ee2a3b245bbd2">ConfigImpl::config_term</a>(</span><span class="doxyHighlightStringLiteral">"file '{}' not found or could not be opened\n"</span><span class="doxyHighlight">,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1594</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1595</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1596</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> stream2string(f);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1597</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1598</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/configimpl/#a0b752f150eb5a0ec002ee2a3b245bbd2">ConfigImpl::config_term</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="/web-doxygen/docs/api/namespaces/portable/#a0579eaf8c245a77f1e804a3cf1b0aa73">Portable::openInputStream</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/configimpl/#a5d06627b2afb76668e8315613a76b9d3">ConfigImpl::parse</a>.</p>

</div>
</div>

### configStringRecode() {#a6c24725da6b5b59e4c8867995e84648f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString configStringRecode (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fromEncoding, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; toEncoding)</td>
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



<p>Definition at line 690 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6c24725da6b5b59e4c8867995e84648f">690</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a6c24725da6b5b59e4c8867995e84648f">configStringRecode</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">691</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">692</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;inputEncoding,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">693</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;outputEncoding)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">694</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (inputEncoding.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() || outputEncoding.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() || inputEncoding==outputEncoding) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> str;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">696</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> inputSize=str.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">697</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> outputSize=inputSize*4;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">698</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> output(outputSize, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">699</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> *cd = <a href="/web-doxygen/docs/api/files/src/portable-h/#a7bc4daae6d2c3e89837c44e2c3d4dac6">portable_iconv_open</a>(outputEncoding.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),inputEncoding.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">700</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd==</span><span class="doxyHighlightKeyword">reinterpret_cast&lt;</span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(-1))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">701</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">702</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/configimpl/#a0b752f150eb5a0ec002ee2a3b245bbd2">ConfigImpl::config_term</a>(</span><span class="doxyHighlightStringLiteral">"Error: unsupported character conversion: '{}'-&gt;'{}'\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">703</span><span class="doxyLineContent"><span class="doxyHighlight">                </span><span class="doxyHighlightStringLiteral">"Check the 'DOXYFILE_ENCODING' setting in the config file!\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">704</span><span class="doxyLineContent"><span class="doxyHighlight">        inputEncoding,outputEncoding);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">705</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">706</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> iLeft=inputSize;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">707</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> oLeft=outputSize;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">708</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *inputPtr  = str.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">709</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *outputPtr = output.<a href="/web-doxygen/docs/api/classes/qcstring/#a5f5c9dc172d638c8d7b07010d100117a">rawData</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">710</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/portable-h/#a5fc5ec1eedfa06b27448863f69ee2e1d">portable_iconv</a>(cd, &amp;inputPtr, &amp;iLeft, &amp;outputPtr, &amp;oLeft))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">711</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">712</span><span class="doxyLineContent"><span class="doxyHighlight">    outputSize-=oLeft;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">713</span><span class="doxyLineContent"><span class="doxyHighlight">    output.<a href="/web-doxygen/docs/api/classes/qcstring/#a747c587f5fee7b891e52909aa309323e">resize</a>(outputSize);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">714</span><span class="doxyLineContent"><span class="doxyHighlight">    output.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(outputSize)=</span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">715</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("iconv: input size=%d output size=%d\n[%s]\n",size,newSize,qPrint(srcBuf));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">716</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">717</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">718</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">719</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/configimpl/#a0b752f150eb5a0ec002ee2a3b245bbd2">ConfigImpl::config_term</a>(</span><span class="doxyHighlightStringLiteral">"Error: failed to translate characters from {} to {}: {}\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">720</span><span class="doxyLineContent"><span class="doxyHighlight">        inputEncoding,outputEncoding,strerror(errno));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">721</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">722</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/portable-h/#a3f98144680118aada1a93d2d4ba6173b">portable_iconv_close</a>(cd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">723</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> output;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">724</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/classes/configimpl/#a0b752f150eb5a0ec002ee2a3b245bbd2">ConfigImpl::config_term</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/files/src/portable-h/#a5fc5ec1eedfa06b27448863f69ee2e1d">portable_iconv</a>, <a href="/web-doxygen/docs/api/files/src/portable-h/#a3f98144680118aada1a93d2d4ba6173b">portable_iconv_close</a>, <a href="/web-doxygen/docs/api/files/src/portable-h/#a7bc4daae6d2c3e89837c44e2c3d4dac6">portable_iconv_open</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a5f5c9dc172d638c8d7b07010d100117a">QCString::rawData</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a747c587f5fee7b891e52909aa309323e">QCString::resize</a>.</p>


<p>Referenced by <a href="#a1004c5eacd365bb12bb64c344baeebc6">processList</a>, <a href="#a48eae5f8b7d851992e7b3e04a01a8af3">processStoreRepl</a>, <a href="#a53f751007ffe5b7c105c3821039a970c">processString</a> and <a href="/web-doxygen/docs/api/classes/configoption/#a369bfd358cef4c5e7c6bf10505ec70db">ConfigOption::writeStringValue</a>.</p>

</div>
</div>

### containsEnvVar() {#a4c20e33d84d7477620edc8cdf3e3333b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool containsEnvVar (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str)</td>
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



<p>Definition at line 1393 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4c20e33d84d7477620edc8cdf3e3333b">1393</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a4c20e33d84d7477620edc8cdf3e3333b">containsEnvVar</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1394</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1395</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/reg/match">reg::Match</a> m;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1396</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string s = str.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1397</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>(s,m,<a href="#a93417da3de847772a0db1c1067124b57">reEnvVar</a>) || <a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>(s,m,<a href="#a8ef2cd114dfa4c36bb86f42ec41c74ea">reEnvVarExt</a>) || <a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>(s,m,<a href="#ad8742d431dca72b48403598209fa3278">reEnvVarCMake</a>) || <a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>(s,m,<a href="#ad46c127e61124d3dae3308327103a2b4">reEnvVar1CMake</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1398</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a93417da3de847772a0db1c1067124b57">reEnvVar</a>, <a href="#ad46c127e61124d3dae3308327103a2b4">reEnvVar1CMake</a>, <a href="#ad8742d431dca72b48403598209fa3278">reEnvVarCMake</a>, <a href="#a8ef2cd114dfa4c36bb86f42ec41c74ea">reEnvVarExt</a>, <a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/configbool/#a6d566ed793c0f4f3e3832f46954dbc86">ConfigBool::compareDoxyfile</a>, <a href="/web-doxygen/docs/api/classes/configint/#aa9ef08f8142fa34f77f5351ce0f219cf">ConfigInt::compareDoxyfile</a>, <a href="/web-doxygen/docs/api/classes/configbool/#a78783b044295f537c27c052ce85eeeed">ConfigBool::convertStrToVal</a>, <a href="/web-doxygen/docs/api/classes/configenum/#ae34a7c55e7f889b4f676bcd4b763965c">ConfigEnum::convertStrToVal</a> and <a href="/web-doxygen/docs/api/classes/configint/#a6b0d01345ae582a8ba26a294c6e1b890">ConfigInt::convertStrToVal</a>.</p>

</div>
</div>

### convertStringToBool() {#a7b04c2a27074eeeccf2fadb03b80fc42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool convertStringToBool (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str, bool &amp; isValid)</td>
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



<p>Definition at line 217 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7b04c2a27074eeeccf2fadb03b80fc42">217</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a7b04c2a27074eeeccf2fadb03b80fc42">convertStringToBool</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> &amp;isValid)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">  isValid=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> val = str.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!val.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (val==</span><span class="doxyHighlightStringLiteral">"yes"</span><span class="doxyHighlight"> || val==</span><span class="doxyHighlightStringLiteral">"true"</span><span class="doxyHighlight"> || val==</span><span class="doxyHighlightStringLiteral">"1"</span><span class="doxyHighlight"> || val==</span><span class="doxyHighlightStringLiteral">"all"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">      isValid=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (val==</span><span class="doxyHighlightStringLiteral">"no"</span><span class="doxyHighlight"> || val==</span><span class="doxyHighlightStringLiteral">"false"</span><span class="doxyHighlight"> || val==</span><span class="doxyHighlightStringLiteral">"0"</span><span class="doxyHighlight"> || val==</span><span class="doxyHighlightStringLiteral">"none"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">      isValid=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/configbool/#a78783b044295f537c27c052ce85eeeed">ConfigBool::convertStrToVal</a> and <a href="/web-doxygen/docs/api/namespaces/config/#ad27e22c157d0c2d33414923d0a41c200">Config::updateObsolete</a>.</p>

</div>
</div>

### convertToComment() {#a48749817b1eba2606c9762ba1bb4d43b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString convertToComment (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; u)</td>
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



<p>Definition at line 88 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a48749817b1eba2606c9762ba1bb4d43b">88</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a48749817b1eba2606c9762ba1bb4d43b">convertToComment</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;u)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("convertToComment(%s)=%s\n",qPrint(s),qPrint(u));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!s.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tmp=s.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=tmp.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">      result+=</span><span class="doxyHighlightStringLiteral">"#"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*p &amp;&amp; *p!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">        result+=</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">          result+=</span><span class="doxyHighlightStringLiteral">"\n#"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*p &amp;&amp; *p!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">            result+=</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">      result+=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!u.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!result.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) result+=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">    result+= u;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/configbool/#a05d11e6e431f77eca9a55cc8d161ff9d">ConfigBool::writeTemplate</a>, <a href="/web-doxygen/docs/api/classes/configenum/#a07b5a073cf6bd30f934635b0c4d6a8d7">ConfigEnum::writeTemplate</a>, <a href="/web-doxygen/docs/api/classes/configimpl/#aa7948af854eb611524c208def210db01">ConfigImpl::writeTemplate</a>, <a href="/web-doxygen/docs/api/classes/configint/#adac9662550d30efe51112c6f97485c60">ConfigInt::writeTemplate</a>, <a href="/web-doxygen/docs/api/classes/configlist/#a6ae20b6290d8e7fb7ce296fae12e9c1c">ConfigList::writeTemplate</a> and <a href="/web-doxygen/docs/api/classes/configstring/#aa4357ea1ddcbab66cfbe6bd378499065">ConfigString::writeTemplate</a>.</p>

</div>
</div>

### findFile() {#a6232960902cd961ee248851d0f5a189d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FILE * findFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName)</td>
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



<p>Definition at line 937 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6232960902cd961ee248851d0f5a189d">937</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> FILE *<a href="#a6232960902cd961ee248851d0f5a189d">findFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">938</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">939</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">940</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">941</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">942</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">943</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/namespaces/portable/#a08dc4d7f652408d7fc2eaba792796cb1">Portable::isAbsolutePath</a>(fileName))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">944</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">945</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aae6d9aa97d4044248e4537678a0a38af">tryPath</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">946</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">947</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a850b28ffc2fc2f5225b6d61b09a70dd5">substEnvVarsInStrList</a>(<a href="#a848459ef910ecc5e245bc68972a9aeac">g_includePathList</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">948</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;s : <a href="#a848459ef910ecc5e245bc68972a9aeac">g_includePathList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">949</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">950</span><span class="doxyLineContent"><span class="doxyHighlight">    FILE *f = <a href="#aae6d9aa97d4044248e4537678a0a38af">tryPath</a>(s.c_str(),fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">951</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (f) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> f;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">952</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">953</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// try cwd if g_includePathList fails</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">954</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aae6d9aa97d4044248e4537678a0a38af">tryPath</a>(</span><span class="doxyHighlightStringLiteral">"."</span><span class="doxyHighlight">,fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">955</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a848459ef910ecc5e245bc68972a9aeac">g_includePathList</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a08dc4d7f652408d7fc2eaba792796cb1">Portable::isAbsolutePath</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a850b28ffc2fc2f5225b6d61b09a70dd5">substEnvVarsInStrList</a> and <a href="#aae6d9aa97d4044248e4537678a0a38af">tryPath</a>.</p>


<p>Referenced by <a href="#a692163c1902febf3d5dc44644e851f26">readIncludeFile</a> and <a href="/web-doxygen/docs/api/files/src/pre-l/#a9af0795be28dcf4551e57a2a3650a552">readIncludeFile</a>.</p>

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



<p>Definition at line 664 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acb5f8818546103e3b804ab8606b52c4a">664</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#acb5f8818546103e3b804ab8606b52c4a">getLexerFILE</a>() {</span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> __FILE__;}</span></span></div>

</div>

</div>
</div>

### processList() {#a1004c5eacd365bb12bb64c344baeebc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void processList ()</td>
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



<p>Definition at line 828 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1004c5eacd365bb12bb64c344baeebc6">828</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1004c5eacd365bb12bb64c344baeebc6">processList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">829</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">830</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> allowCommaAsSeparator = <a href="#a80001906a82b0d116f334f0bb065c7a9">g_cmd</a>!=</span><span class="doxyHighlightStringLiteral">"PREDEFINED"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">831</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">832</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> s = <a href="#a84908cbd8715e1a9294673286a5f7b6e">stripComment</a>(<a href="#ad33b30a9730e3f9332e7eb36152f4276">g_listStr</a>.stripWhiteSpace());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">833</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> l = s.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">834</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">835</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> elemStr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">836</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> wasQuote=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">837</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">838</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// helper to push elemStr to the list and clear it</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">839</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> addElem = [&amp;elemStr,&amp;wasQuote]()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">840</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">841</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!elemStr.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">842</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">843</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> e = <a href="#a6c24725da6b5b59e4c8867995e84648f">configStringRecode</a>(elemStr,<a href="#a1d031dea12ce5dfc5759802ec854c2d2">g_encoding</a>,</span><span class="doxyHighlightStringLiteral">"UTF-8"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">844</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("Processed list element '%s'\n",qPrint(e));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">845</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (wasQuote) e = </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">+e+</span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">846</span><span class="doxyLineContent"><span class="doxyHighlight">      wasQuote = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">847</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a6d73b052225d65c218ae7d286d8c633a">g_list</a>-&gt;push_back(e.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">848</span><span class="doxyLineContent"><span class="doxyHighlight">      elemStr=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">849</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">850</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">851</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">852</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> needsSeparator=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">853</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> insideQuote=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">854</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> warned=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">855</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;i&lt;l;i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">856</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">857</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = s.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">858</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!needsSeparator &amp;&amp; c==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// escaped character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">859</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">860</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;l-1 &amp;&amp; s.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(i+1)==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// unescape the quote character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">861</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">862</span><span class="doxyLineContent"><span class="doxyHighlight">        elemStr+=</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">863</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">864</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// keep other escaped characters in escaped form</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">865</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">866</span><span class="doxyLineContent"><span class="doxyHighlight">        elemStr+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">867</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;l-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">868</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">869</span><span class="doxyLineContent"><span class="doxyHighlight">          elemStr+=s.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(i+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">870</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">871</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">872</span><span class="doxyLineContent"><span class="doxyHighlight">      i++; </span><span class="doxyHighlightComment">// skip over the escaped character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">873</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">874</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!needsSeparator &amp;&amp; c==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// quote character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">875</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">876</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!insideQuote)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">877</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">878</span><span class="doxyLineContent"><span class="doxyHighlight">        insideQuote=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">879</span><span class="doxyLineContent"><span class="doxyHighlight">        wasQuote=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">880</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">881</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// this quote ends an element</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">882</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">883</span><span class="doxyLineContent"><span class="doxyHighlight">        insideQuote=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">884</span><span class="doxyLineContent"><span class="doxyHighlight">        needsSeparator=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">885</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">886</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">887</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!insideQuote &amp;&amp; ((c==</span><span class="doxyHighlightCharLiteral">','</span><span class="doxyHighlight"> &amp;&amp; allowCommaAsSeparator) || isspace(c))) </span><span class="doxyHighlightComment">// separator</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">888</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">889</span><span class="doxyLineContent"><span class="doxyHighlight">      needsSeparator=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">890</span><span class="doxyLineContent"><span class="doxyHighlight">      addElem();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">891</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">892</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// normal content character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">893</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">894</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (needsSeparator)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">895</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">896</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!warned)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">897</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">898</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/configimpl/#aa631fde6f0b7e94b180b07252096ec12">ConfigImpl::config_warn</a>(</span><span class="doxyHighlightStringLiteral">"Invalid value for '{}' tag at line {}, file {}: Values in list '{}' are not properly space {}separated\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">899</span><span class="doxyLineContent"><span class="doxyHighlight">                    <a href="#a80001906a82b0d116f334f0bb065c7a9">g_cmd</a>,<a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>,<a href="#afec8ce807dc9bf79f073fa691fafe1f8">g_yyFileName</a>,<a href="#ad33b30a9730e3f9332e7eb36152f4276">g_listStr</a>.stripWhiteSpace(),allowCommaAsSeparator?</span><span class="doxyHighlightStringLiteral">"or comma "</span><span class="doxyHighlight">:</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">900</span><span class="doxyLineContent"><span class="doxyHighlight">          warned=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">901</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">902</span><span class="doxyLineContent"><span class="doxyHighlight">        needsSeparator=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">903</span><span class="doxyLineContent"><span class="doxyHighlight">        i--; </span><span class="doxyHighlightComment">// try the character again as part of a new element</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">904</span><span class="doxyLineContent"><span class="doxyHighlight">        addElem();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">905</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">906</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">907</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">908</span><span class="doxyLineContent"><span class="doxyHighlight">        elemStr+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">909</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">910</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">911</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">912</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// add last part</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">913</span><span class="doxyLineContent"><span class="doxyHighlight">  addElem();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">914</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (insideQuote)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">915</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">916</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/configimpl/#aa631fde6f0b7e94b180b07252096ec12">ConfigImpl::config_warn</a>(</span><span class="doxyHighlightStringLiteral">"Invalid value for '{}' tag at line {}, file {}: Values in list '{}' are not properly quoted\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">917</span><span class="doxyLineContent"><span class="doxyHighlight">                <a href="#a80001906a82b0d116f334f0bb065c7a9">g_cmd</a>,<a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>,<a href="#afec8ce807dc9bf79f073fa691fafe1f8">g_yyFileName</a>,<a href="#ad33b30a9730e3f9332e7eb36152f4276">g_listStr</a>.stripWhiteSpace());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">918</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">919</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/classes/configimpl/#aa631fde6f0b7e94b180b07252096ec12">ConfigImpl::config_warn</a>, <a href="#a6c24725da6b5b59e4c8867995e84648f">configStringRecode</a>, <a href="#a80001906a82b0d116f334f0bb065c7a9">g_cmd</a>, <a href="#a1d031dea12ce5dfc5759802ec854c2d2">g_encoding</a>, <a href="#a6d73b052225d65c218ae7d286d8c633a">g_list</a>, <a href="#ad33b30a9730e3f9332e7eb36152f4276">g_listStr</a>, <a href="#afec8ce807dc9bf79f073fa691fafe1f8">g_yyFileName</a>, <a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="#a84908cbd8715e1a9294673286a5f7b6e">stripComment</a>.</p>

</div>
</div>

### processStoreRepl() {#a48eae5f8b7d851992e7b3e04a01a8af3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void processStoreRepl (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; storeReplStr)</td>
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



<p>Definition at line 760 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a48eae5f8b7d851992e7b3e04a01a8af3">760</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a48eae5f8b7d851992e7b3e04a01a8af3">processStoreRepl</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;storeReplStr)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">761</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">762</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// strip leading and trailing whitespace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">763</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> s = <a href="#a84908cbd8715e1a9294673286a5f7b6e">stripComment</a>(storeReplStr.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">764</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// recode the string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">765</span><span class="doxyLineContent"><span class="doxyHighlight">  storeReplStr=<a href="#a6c24725da6b5b59e4c8867995e84648f">configStringRecode</a>(s,<a href="#a1d031dea12ce5dfc5759802ec854c2d2">g_encoding</a>,</span><span class="doxyHighlightStringLiteral">"UTF-8"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">766</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a6c24725da6b5b59e4c8867995e84648f">configStringRecode</a>, <a href="#a1d031dea12ce5dfc5759802ec854c2d2">g_encoding</a>, <a href="#a84908cbd8715e1a9294673286a5f7b6e">stripComment</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>.</p>

</div>
</div>

### processString() {#a53f751007ffe5b7c105c3821039a970c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void processString ()</td>
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



<p>Definition at line 768 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a53f751007ffe5b7c105c3821039a970c">768</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a53f751007ffe5b7c105c3821039a970c">processString</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">769</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">770</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// strip leading and trailing whitespace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">771</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> s = <a href="#a84908cbd8715e1a9294673286a5f7b6e">stripComment</a>(<a href="#a0b72791268d83dc5adf869ac258a3027">g_string</a>-&gt;stripWhiteSpace());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">772</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> l = s.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">773</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">774</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// remove surrounding quotes if present (and not escaped)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">775</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (l&gt;=2 &amp;&amp; s.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(0)==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight"> &amp;&amp; s.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(l-1)==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight"> &amp;&amp; </span><span class="doxyHighlightComment">// remove quotes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">776</span><span class="doxyLineContent"><span class="doxyHighlight">      (s.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(l-2)!=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight"> || (s.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(l-2)==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight"> &amp;&amp; s.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(l-3)==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">777</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">778</span><span class="doxyLineContent"><span class="doxyHighlight">    s=s.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(1,s.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">779</span><span class="doxyLineContent"><span class="doxyHighlight">    l=s.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">780</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">781</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">782</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check for invalid and/or escaped quotes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">783</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> warned=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">784</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">785</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;i&lt;l;i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">786</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">787</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = s.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">788</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// escaped character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">789</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">790</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;l-1 &amp;&amp; s.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(i+1)==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// unescape the quote character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">791</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">792</span><span class="doxyLineContent"><span class="doxyHighlight">        result+=</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">793</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">794</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// keep other escaped characters in escaped form</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">795</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">796</span><span class="doxyLineContent"><span class="doxyHighlight">        result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">797</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;l-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">798</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">799</span><span class="doxyLineContent"><span class="doxyHighlight">          result+=s.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(i+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">800</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">801</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">802</span><span class="doxyLineContent"><span class="doxyHighlight">      i++; </span><span class="doxyHighlightComment">// skip over the escaped character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">803</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">804</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// unescaped quote</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">805</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">806</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!warned)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">807</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">808</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/configimpl/#aa631fde6f0b7e94b180b07252096ec12">ConfigImpl::config_warn</a>(</span><span class="doxyHighlightStringLiteral">"Invalid value for '{}' tag at line {}, file {}: Value '{}' is not properly quoted\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">809</span><span class="doxyLineContent"><span class="doxyHighlight">                    <a href="#a80001906a82b0d116f334f0bb065c7a9">g_cmd</a>,<a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>,<a href="#afec8ce807dc9bf79f073fa691fafe1f8">g_yyFileName</a>,<a href="#a0b72791268d83dc5adf869ac258a3027">g_string</a>-&gt;stripWhiteSpace());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">810</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">811</span><span class="doxyLineContent"><span class="doxyHighlight">      warned=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">812</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">813</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// normal character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">814</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">815</span><span class="doxyLineContent"><span class="doxyHighlight">      result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">816</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">817</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">818</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">819</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// recode the string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">820</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#a0b72791268d83dc5adf869ac258a3027">g_string</a>=<a href="#a6c24725da6b5b59e4c8867995e84648f">configStringRecode</a>(result,<a href="#a1d031dea12ce5dfc5759802ec854c2d2">g_encoding</a>,</span><span class="doxyHighlightStringLiteral">"UTF-8"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">821</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">822</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// update encoding</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">823</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a38bfc7b0b040cc8ceefae240aad38b94">checkEncoding</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">824</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">825</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("Processed string '%s'\n",qPrint(g_string));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">826</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="#a38bfc7b0b040cc8ceefae240aad38b94">checkEncoding</a>, <a href="/web-doxygen/docs/api/classes/configimpl/#aa631fde6f0b7e94b180b07252096ec12">ConfigImpl::config_warn</a>, <a href="#a6c24725da6b5b59e4c8867995e84648f">configStringRecode</a>, <a href="#a80001906a82b0d116f334f0bb065c7a9">g_cmd</a>, <a href="#a1d031dea12ce5dfc5759802ec854c2d2">g_encoding</a>, <a href="#a0b72791268d83dc5adf869ac258a3027">g_string</a>, <a href="#afec8ce807dc9bf79f073fa691fafe1f8">g_yyFileName</a>, <a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a> and <a href="#a84908cbd8715e1a9294673286a5f7b6e">stripComment</a>.</p>

</div>
</div>

### readIncludeFile() {#a692163c1902febf3d5dc44644e851f26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void readIncludeFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; incName)</td>
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



<p>Definition at line 957 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a692163c1902febf3d5dc44644e851f26">957</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a692163c1902febf3d5dc44644e851f26">readIncludeFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;incName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">958</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">959</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a53705fefd416a984be4714f1d0ca36a6">g_includeStack</a>.size()==<a href="#a641f7209d924c2c4cb24420dcd631f37">MAX_INCLUDE_DEPTH</a>) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">960</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/configimpl/#a0b752f150eb5a0ec002ee2a3b245bbd2">ConfigImpl::config_term</a>(</span><span class="doxyHighlightStringLiteral">"maximum include depth ({:d}) reached, {} is not included. Aborting...\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">961</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a641f7209d924c2c4cb24420dcd631f37">MAX_INCLUDE_DEPTH</a>,incName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">962</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">963</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">964</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> inc = incName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">965</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#afcf1a493801a3f065ef9ca18e7c4f6c6">substEnvVarsInString</a>(inc);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">966</span><span class="doxyLineContent"><span class="doxyHighlight">  inc = inc.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">967</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> incLen = inc.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">968</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (incLen&gt;0 &amp;&amp; inc.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(0)==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight"> &amp;&amp; inc.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(incLen-1)==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// strip quotes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">969</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">970</span><span class="doxyLineContent"><span class="doxyHighlight">    inc=inc.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(1,incLen-2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">971</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">972</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">973</span><span class="doxyLineContent"><span class="doxyHighlight">  FILE *f;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">974</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">975</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((f=<a href="#a6232960902cd961ee248851d0f5a189d">findFile</a>(inc))) </span><span class="doxyHighlightComment">// see if the include file can be found</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">976</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">977</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// For debugging</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">978</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#if SHOW_INCLUDES</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">979</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;i&lt;<a href="#a53705fefd416a984be4714f1d0ca36a6">g_includeStack</a>.size();i++) <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"  "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">980</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"@INCLUDE = {}: parsing...\n"</span><span class="doxyHighlight">,inc);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">981</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">982</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">983</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// store the state of the old file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">984</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/configfilestate">ConfigFileState</a> *fs=</span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/configfilestate">ConfigFileState</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">985</span><span class="doxyLineContent"><span class="doxyHighlight">    fs-&gt;<a href="/web-doxygen/docs/api/structs/configfilestate/#aaacb1254715397e72db10477de158e2c">oldState</a>=YY_CURRENT_BUFFER;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">986</span><span class="doxyLineContent"><span class="doxyHighlight">    fs-&gt;<a href="/web-doxygen/docs/api/structs/configfilestate/#a41d216c2114d71fa486a48f063a88d16">lineNr</a>=<a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">987</span><span class="doxyLineContent"><span class="doxyHighlight">    fs-&gt;<a href="/web-doxygen/docs/api/structs/configfilestate/#a412089401b0967a7d7e0204cfadfef78">fileName</a>=<a href="#afec8ce807dc9bf79f073fa691fafe1f8">g_yyFileName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">988</span><span class="doxyLineContent"><span class="doxyHighlight">    fs-&gt;<a href="/web-doxygen/docs/api/structs/configfilestate/#aa5d616a4c7712d0d7be52d4a56254672">filePtr</a>=f;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">989</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// push the state on the stack</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">990</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a53705fefd416a984be4714f1d0ca36a6">g_includeStack</a>.push_back(std::unique_ptr&lt;ConfigFileState&gt;(fs));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">991</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// set the scanner to the include file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">992</span><span class="doxyLineContent"><span class="doxyHighlight">    yy_switch_to_buffer(yy_create_buffer(f, <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#ae7e51116e747d3390e7a6cfc6532834c">YY_BUF_SIZE</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">993</span><span class="doxyLineContent"><span class="doxyHighlight">    fs-&gt;<a href="/web-doxygen/docs/api/structs/configfilestate/#a219e8266c897bd4c52c76e0adc04a900">newState</a>=YY_CURRENT_BUFFER;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">994</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#afec8ce807dc9bf79f073fa691fafe1f8">g_yyFileName</a>=inc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">995</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">996</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">997</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">998</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/configimpl/#a0b752f150eb5a0ec002ee2a3b245bbd2">ConfigImpl::config_term</a>(</span><span class="doxyHighlightStringLiteral">"@INCLUDE = {}: not found!\n"</span><span class="doxyHighlight">,inc);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">999</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1000</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/classes/configimpl/#a0b752f150eb5a0ec002ee2a3b245bbd2">ConfigImpl::config_term</a>, <a href="/web-doxygen/docs/api/structs/configfilestate/#a412089401b0967a7d7e0204cfadfef78">ConfigFileState::fileName</a>, <a href="/web-doxygen/docs/api/structs/configfilestate/#aa5d616a4c7712d0d7be52d4a56254672">ConfigFileState::filePtr</a>, <a href="#a6232960902cd961ee248851d0f5a189d">findFile</a>, <a href="#a53705fefd416a984be4714f1d0ca36a6">g_includeStack</a>, <a href="#afec8ce807dc9bf79f073fa691fafe1f8">g_yyFileName</a>, <a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/structs/configfilestate/#a41d216c2114d71fa486a48f063a88d16">ConfigFileState::lineNr</a>, <a href="#a641f7209d924c2c4cb24420dcd631f37">MAX_INCLUDE_DEPTH</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>, <a href="/web-doxygen/docs/api/structs/configfilestate/#a219e8266c897bd4c52c76e0adc04a900">ConfigFileState::newState</a>, <a href="/web-doxygen/docs/api/structs/configfilestate/#aaacb1254715397e72db10477de158e2c">ConfigFileState::oldState</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>, <a href="#afcf1a493801a3f065ef9ca18e7c4f6c6">substEnvVarsInString</a> and <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#ae7e51116e747d3390e7a6cfc6532834c">YY_BUF_SIZE</a>.</p>

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



<p>Definition at line 54 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>

</div>
</div>

### stripComment() {#a84908cbd8715e1a9294673286a5f7b6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString stripComment (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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



<p>Definition at line 732 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a84908cbd8715e1a9294673286a5f7b6e">732</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a84908cbd8715e1a9294673286a5f7b6e">stripComment</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">733</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">734</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check if there is a comment at the end of the string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">735</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> insideQuote=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">736</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> l = s.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">737</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;i&lt;l;i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">738</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">739</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = s.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">740</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// skip over escaped characters</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">741</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">742</span><span class="doxyLineContent"><span class="doxyHighlight">      i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">743</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">744</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// toggle inside/outside quotation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">745</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">746</span><span class="doxyLineContent"><span class="doxyHighlight">      insideQuote=!insideQuote;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">747</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">748</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!insideQuote &amp;&amp; c==</span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// found start of a comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">749</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">750</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;l-1 &amp;&amp; s.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(i+1)==</span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// ## -&gt; user comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">751</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">752</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ac8c998011c1de1f3c38cb48c908af98b">g_config</a>-&gt;appendUserComment(s.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(i)+</span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">753</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">754</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(i).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">755</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">756</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">757</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">758</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="#ac8c998011c1de1f3c38cb48c908af98b">g_config</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>.</p>


<p>Referenced by <a href="#a1004c5eacd365bb12bb64c344baeebc6">processList</a>, <a href="#a48eae5f8b7d851992e7b3e04a01a8af3">processStoreRepl</a> and <a href="#a53f751007ffe5b7c105c3821039a970c">processString</a>.</p>

</div>
</div>

### substEnvVarsInString() {#afcf1a493801a3f065ef9ca18e7c4f6c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void substEnvVarsInString (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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



<p>Definition at line 1400 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afcf1a493801a3f065ef9ca18e7c4f6c6">1400</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afcf1a493801a3f065ef9ca18e7c4f6c6">substEnvVarsInString</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1401</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1402</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (str.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1403</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> replace = [](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;s, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> &amp;re) -&gt; std::string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1404</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1405</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/reg/iterator">reg::Iterator</a> it(s,re);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1406</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/reg/iterator">reg::Iterator</a> <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1407</span><span class="doxyLineContent"><span class="doxyHighlight">    std::string result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1408</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> p = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1409</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (; it!=<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a> ; ++it)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1410</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1411</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;match = *it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1412</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i = match.position();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1413</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> l = match.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1414</span><span class="doxyLineContent"><span class="doxyHighlight">      result+=s.substr(p,i-p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1415</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string matchContents = match[1].str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1416</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> env=<a href="/web-doxygen/docs/api/namespaces/portable/#ae1a7516287ca7c75eebc3fa7aa12e970">Portable::getenv</a>(matchContents.c_str()); </span><span class="doxyHighlightComment">// get content of $(..) match</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1417</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#afcf1a493801a3f065ef9ca18e7c4f6c6">substEnvVarsInString</a>(env); </span><span class="doxyHighlightComment">// recursively expand variables if needed.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1418</span><span class="doxyLineContent"><span class="doxyHighlight">      result+=env.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1419</span><span class="doxyLineContent"><span class="doxyHighlight">      p=i+l;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1420</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1421</span><span class="doxyLineContent"><span class="doxyHighlight">    result+=s.substr(p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1422</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1423</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1424</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1425</span><span class="doxyLineContent"><span class="doxyHighlight">  str = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(replace(replace(str.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),<a href="#a93417da3de847772a0db1c1067124b57">reEnvVar</a>),<a href="#a8ef2cd114dfa4c36bb86f42ec41c74ea">reEnvVarExt</a>)).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1426</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#ae1a7516287ca7c75eebc3fa7aa12e970">Portable::getenv</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a93417da3de847772a0db1c1067124b57">reEnvVar</a>, <a href="#a8ef2cd114dfa4c36bb86f42ec41c74ea">reEnvVarExt</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a> and <a href="#afcf1a493801a3f065ef9ca18e7c4f6c6">substEnvVarsInString</a>.</p>


<p>Referenced by <a href="#a692163c1902febf3d5dc44644e851f26">readIncludeFile</a>, <a href="/web-doxygen/docs/api/classes/configbool/#a5682d107b4ebf92ae60ea0ba5ece3c5c">ConfigBool::substEnvVars</a>, <a href="/web-doxygen/docs/api/classes/configenum/#aa71d0a927aa4726a7cb12afd35c343eb">ConfigEnum::substEnvVars</a>, <a href="/web-doxygen/docs/api/classes/configint/#af38d914b18d3ac4fb9da0180de95901d">ConfigInt::substEnvVars</a>, <a href="/web-doxygen/docs/api/classes/configstring/#a04e574eb2e0c9b5ac907f193c5909511">ConfigString::substEnvVars</a>, <a href="#afcf1a493801a3f065ef9ca18e7c4f6c6">substEnvVarsInString</a> and <a href="#a850b28ffc2fc2f5225b6d61b09a70dd5">substEnvVarsInStrList</a>.</p>

</div>
</div>

### substEnvVarsInStrList() {#a850b28ffc2fc2f5225b6d61b09a70dd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void substEnvVarsInStrList (<a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> &amp; sl)</td>
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



<p>Definition at line 1428 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a850b28ffc2fc2f5225b6d61b09a70dd5">1428</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a850b28ffc2fc2f5225b6d61b09a70dd5">substEnvVarsInStrList</a>(<a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> &amp;sl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1429</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1430</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> results;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1431</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;s : sl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1432</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1433</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result = s.c_str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1434</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> wasQuoted = ((result.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(0)==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">) &amp;&amp; (result.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(result.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-1)==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1435</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (wasQuoted)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1436</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1437</span><span class="doxyLineContent"><span class="doxyHighlight">      result = result.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(1,result.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1438</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1439</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1440</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1441</span><span class="doxyLineContent"><span class="doxyHighlight">      wasQuoted = (result.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">)!=-1) || (result.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">)!=-1) || (result.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">)!=-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1442</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1443</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// here we strip the quote again</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1444</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#afcf1a493801a3f065ef9ca18e7c4f6c6">substEnvVarsInString</a>(result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1445</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1446</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("Result %s was quoted=%d\n",qPrint(result),wasQuoted);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1447</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1448</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!wasQuoted) </span><span class="doxyHighlightComment">/* as a result of the expansion, a single string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1449</span><span class="doxyLineContent"><span class="doxyHighlightComment">                       may have expanded into a list, which we'll</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1450</span><span class="doxyLineContent"><span class="doxyHighlightComment">                       add to sl. If the original string already</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1451</span><span class="doxyLineContent"><span class="doxyHighlightComment">                       contained multiple elements no further</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1452</span><span class="doxyLineContent"><span class="doxyHighlightComment">                       splitting is done to allow quoted items with spaces! */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1453</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1454</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> l = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(result.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1455</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> p = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1456</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// skip spaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1457</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// search for a "word"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1458</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0;i&lt;l;i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1459</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1460</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1461</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// skip until start of new word</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1462</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;l &amp;&amp; ((c=result.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(i))==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">)) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1463</span><span class="doxyLineContent"><span class="doxyHighlight">        p=i; </span><span class="doxyHighlightComment">// p marks the start index of the word</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1464</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// skip until end of a word</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1465</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;l &amp;&amp; ((c=result.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(i))!=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">)) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1466</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;l) </span><span class="doxyHighlightComment">// not at the end of the string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1467</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1468</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// word within quotes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1469</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1470</span><span class="doxyLineContent"><span class="doxyHighlight">            p=i+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1471</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (i++;i&lt;l;i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1472</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1473</span><span class="doxyLineContent"><span class="doxyHighlight">              c=result.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1474</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// end quote</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1475</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1476</span><span class="doxyLineContent"><span class="doxyHighlight">                results.push_back(result.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(p,i-p).<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1477</span><span class="doxyLineContent"><span class="doxyHighlight">                p=i+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1478</span><span class="doxyLineContent"><span class="doxyHighlight">                </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1479</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1480</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// skip escaped stuff</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1481</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1482</span><span class="doxyLineContent"><span class="doxyHighlight">                i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1483</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1484</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1485</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1486</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// separator</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1487</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1488</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&gt;p) results.push_back(result.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(p,i-p).<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1489</span><span class="doxyLineContent"><span class="doxyHighlight">            p=i+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1490</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1491</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1492</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1493</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (p!=l) </span><span class="doxyHighlightComment">// add the leftover as a string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1494</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1495</span><span class="doxyLineContent"><span class="doxyHighlight">        results.push_back(result.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(l-p).<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1496</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1497</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1498</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// just goto the next element in the list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1499</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1500</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!result.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) results.push_back(result.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1501</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1502</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1503</span><span class="doxyLineContent"><span class="doxyHighlight">  sl = results;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1504</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">QCString::right</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="#afcf1a493801a3f065ef9ca18e7c4f6c6">substEnvVarsInString</a>.</p>


<p>Referenced by <a href="#a6232960902cd961ee248851d0f5a189d">findFile</a> and <a href="/web-doxygen/docs/api/classes/configlist/#a2594b00b794dad76de45054077e47952">ConfigList::substEnvVars</a>.</p>

</div>
</div>

### tryPath() {#aae6d9aa97d4044248e4537678a0a38af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FILE * tryPath (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; path, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName)</td>
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



<p>Definition at line 921 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aae6d9aa97d4044248e4537678a0a38af">921</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> FILE *<a href="#aae6d9aa97d4044248e4537678a0a38af">tryPath</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;path,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">922</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">923</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> absName=(!path.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() ? path+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+fileName : fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">924</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fi(absName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">925</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>() &amp;&amp; fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#ab7840bb4fca4b3d9938c1b3f0e1352ef">isFile</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">926</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">927</span><span class="doxyLineContent"><span class="doxyHighlight">    FILE *f=<a href="/web-doxygen/docs/api/namespaces/portable/#a4dbb08c3de409bd1a73be3da6d93ac57">Portable::fopen</a>(absName,</span><span class="doxyHighlightStringLiteral">"r"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">928</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!f) <a href="/web-doxygen/docs/api/classes/configimpl/#a2f513f81f77c64fb9b7fd78245482b42">ConfigImpl::config_err</a>(</span><span class="doxyHighlightStringLiteral">"could not open file {} for reading\n"</span><span class="doxyHighlight">,absName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">929</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> f;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">930</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">931</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">932</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/configimpl/#a2f513f81f77c64fb9b7fd78245482b42">ConfigImpl::config_err</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">FileInfo::exists</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a4dbb08c3de409bd1a73be3da6d93ac57">Portable::fopen</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#ab7840bb4fca4b3d9938c1b3f0e1352ef">FileInfo::isFile</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>


<p>Referenced by <a href="#a6232960902cd961ee248851d0f5a189d">findFile</a>.</p>

</div>
</div>

### updateAttribute() {#a1ab01907c143c95a407993630bdfeba9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void updateAttribute (<a href="/web-doxygen/docs/api/classes/dotattributes">DotAttributes</a> &amp; attr, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name, <a href="/web-doxygen/docs/api/classes/configobsolete">ConfigObsolete</a> * value)</td>
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



<p>Definition at line 2238 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1ab01907c143c95a407993630bdfeba9">2238</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1ab01907c143c95a407993630bdfeba9">updateAttribute</a>(<a href="/web-doxygen/docs/api/classes/dotattributes">DotAttributes</a>&amp; attr, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name, <a href="/web-doxygen/docs/api/classes/configobsolete">ConfigObsolete</a>* value)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2239</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2240</span><span class="doxyLineContent"><span class="doxyHighlight">  attr.<a href="/web-doxygen/docs/api/classes/dotattributes/#a379cba80b5c667d8d41d85426c4f5376">updateValue</a>(name,*value-&gt;<a href="/web-doxygen/docs/api/classes/configobsolete/#a5b2f5633d6d13cfe0c2873ab683db80e">valueStringRef</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2241</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/dotattributes/#a379cba80b5c667d8d41d85426c4f5376">DotAttributes::updateValue</a> and <a href="/web-doxygen/docs/api/classes/configobsolete/#a5b2f5633d6d13cfe0c2873ab683db80e">ConfigObsolete::valueStringRef</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/namespaces/config/#ad27e22c157d0c2d33414923d0a41c200">Config::updateObsolete</a>.</p>

</div>
</div>

### yylex() {#a9a7bd1b3d14701eb97c03f3ef34deff1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int yylex (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1017 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9a7bd1b3d14701eb97c03f3ef34deff1">1017</a></span><span class="doxyLineContent"><span class="doxyHighlight">%%</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1018</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1019</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;\0x0d</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1020</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1021</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightComment">/*-------------- Comments ---------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1022</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1023</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;"##".*"\n"</span><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1024</span><span class="doxyLineContent"><span class="doxyHighlight">                                           <a href="#ac8c998011c1de1f3c38cb48c908af98b">g_config</a>-&gt;appendUserComment(yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1025</span><span class="doxyLineContent"><span class="doxyHighlight">                                           <a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1026</span><span class="doxyLineContent"><span class="doxyHighlight">                                         }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1027</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;"#".*"\n"</span><span class="doxyHighlight">                         { </span><span class="doxyHighlightComment">/* normal comment */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1028</span><span class="doxyLineContent"><span class="doxyHighlight">                                           <a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1029</span><span class="doxyLineContent"><span class="doxyHighlight">                                         }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1030</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1031</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightComment">/*-------------- TAG start ---------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1032</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1033</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;[a-z_A-Z][a-z_A-Z0-9]*[ \t]*"="</span><span class="doxyHighlight">   { <a href="#a80001906a82b0d116f334f0bb065c7a9">g_cmd</a>=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1034</span><span class="doxyLineContent"><span class="doxyHighlight">                                           <a href="#a80001906a82b0d116f334f0bb065c7a9">g_cmd</a>=<a href="#a80001906a82b0d116f334f0bb065c7a9">g_cmd</a>.left(<a href="#a80001906a82b0d116f334f0bb065c7a9">g_cmd</a>.length()-1).stripWhiteSpace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1035</span><span class="doxyLineContent"><span class="doxyHighlight">                                           <a href="/web-doxygen/docs/api/classes/configoption">ConfigOption</a> *option = <a href="#ac8c998011c1de1f3c38cb48c908af98b">g_config</a>-&gt;get(<a href="#a80001906a82b0d116f334f0bb065c7a9">g_cmd</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1036</span><span class="doxyLineContent"><span class="doxyHighlight">                                           </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (option==0) </span><span class="doxyHighlightComment">// oops not known</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1037</span><span class="doxyLineContent"><span class="doxyHighlight">                                           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1038</span><span class="doxyLineContent"><span class="doxyHighlight">                                             <a href="/web-doxygen/docs/api/classes/configimpl/#aa631fde6f0b7e94b180b07252096ec12">ConfigImpl::config_warn</a>(</span><span class="doxyHighlightStringLiteral">"ignoring unsupported tag '{}' at line {}, file {}\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1039</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 <a href="#a80001906a82b0d116f334f0bb065c7a9">g_cmd</a>,<a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>,<a href="#afec8ce807dc9bf79f073fa691fafe1f8">g_yyFileName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1040</span><span class="doxyLineContent"><span class="doxyHighlight">                                             BEGIN(SkipInvalid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1041</span><span class="doxyLineContent"><span class="doxyHighlight">                                           }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1042</span><span class="doxyLineContent"><span class="doxyHighlight">                                           </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// known tag</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1043</span><span class="doxyLineContent"><span class="doxyHighlight">                                           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1044</span><span class="doxyLineContent"><span class="doxyHighlight">                                             option-&gt;<a href="/web-doxygen/docs/api/classes/configoption/#a5baa3fb6c4fb6ec667eb91172f3f398a">setUserComment</a>(<a href="#ac8c998011c1de1f3c38cb48c908af98b">g_config</a>-&gt;takeUserComment());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1045</span><span class="doxyLineContent"><span class="doxyHighlight">                                             option-&gt;<a href="/web-doxygen/docs/api/classes/configoption/#a0ac357ec83d2014603c8d70a00c27a33">setEncoding</a>(<a href="#a1d031dea12ce5dfc5759802ec854c2d2">g_encoding</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1046</span><span class="doxyLineContent"><span class="doxyHighlight">                                             </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(option-&gt;<a href="/web-doxygen/docs/api/classes/configoption/#af9d4d56d36500792b82fce5b11202a60">kind</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1047</span><span class="doxyLineContent"><span class="doxyHighlight">                                             {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1048</span><span class="doxyLineContent"><span class="doxyHighlight">                                               </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaade872bcb27f40e3380fb20be7cea9e57">ConfigOption::O_Info</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1049</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 </span><span class="doxyHighlightComment">// shouldn't get here!</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1050</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 BEGIN(SkipInvalid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1051</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1052</span><span class="doxyLineContent"><span class="doxyHighlight">                                               </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa18c0785bb1948fb57402ee80324ef1a7">ConfigOption::O_List</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1053</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 <a href="#a6d73b052225d65c218ae7d286d8c633a">g_list</a> = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configlist">ConfigList</a> *</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(option)-&gt;valueRef();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1054</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 <a href="#a6d73b052225d65c218ae7d286d8c633a">g_list</a>-&gt;clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1055</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 <a href="#ad33b30a9730e3f9332e7eb36152f4276">g_listStr</a>=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1056</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 BEGIN(GetStrList);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1057</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1058</span><span class="doxyLineContent"><span class="doxyHighlight">                                               </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa1ba2565ddffed94550a83a5b537e6a31">ConfigOption::O_Enum</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1059</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 <a href="#a0b72791268d83dc5adf869ac258a3027">g_string</a> = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configenum">ConfigEnum</a> *</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(option)-&gt;valueRef();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1060</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 <a href="#a0b72791268d83dc5adf869ac258a3027">g_string</a>-&gt;clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1061</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 BEGIN(GetString);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1062</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1063</span><span class="doxyLineContent"><span class="doxyHighlight">                                               </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa3aa84b958a247d79889f28f4244a7d7f">ConfigOption::O_String</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1064</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 <a href="#a0b72791268d83dc5adf869ac258a3027">g_string</a> = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configstring">ConfigString</a> *</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(option)-&gt;valueRef();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1065</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 <a href="#a0b72791268d83dc5adf869ac258a3027">g_string</a>-&gt;clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1066</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 BEGIN(GetString);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1067</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1068</span><span class="doxyLineContent"><span class="doxyHighlight">                                               </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaac029c8062b88308de12914e88e12dcd8">ConfigOption::O_Int</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1069</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 <a href="#a0b72791268d83dc5adf869ac258a3027">g_string</a> = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configint">ConfigInt</a> *</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(option)-&gt;valueStringRef();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1070</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 <a href="#a0b72791268d83dc5adf869ac258a3027">g_string</a>-&gt;clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1071</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 BEGIN(GetString);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1072</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1073</span><span class="doxyLineContent"><span class="doxyHighlight">                                               </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa306962172c18f2b309fb729e66e32e81">ConfigOption::O_Bool</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1074</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 <a href="#a0b72791268d83dc5adf869ac258a3027">g_string</a> = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configbool">ConfigBool</a> *</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(option)-&gt;valueStringRef();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1075</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 <a href="#a0b72791268d83dc5adf869ac258a3027">g_string</a>-&gt;clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1076</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 BEGIN(GetString);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1077</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1078</span><span class="doxyLineContent"><span class="doxyHighlight">                                               </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaab60c019594029c214e601ec24988d6ac">ConfigOption::O_Obsolete</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1079</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a73e0a7c37c8a540748c113811329f998">g_configUpdate</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1080</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1081</span><span class="doxyLineContent"><span class="doxyHighlight">                                                   <a href="/web-doxygen/docs/api/classes/configimpl/#aa631fde6f0b7e94b180b07252096ec12">ConfigImpl::config_warn</a>(</span><span class="doxyHighlightStringLiteral">"Tag '{}' at line {} of file '{}' has become obsolete.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1082</span><span class="doxyLineContent"><span class="doxyHighlight">                                                              </span><span class="doxyHighlightStringLiteral">"         This tag has been removed.\n"</span><span class="doxyHighlight">, <a href="#a80001906a82b0d116f334f0bb065c7a9">g_cmd</a>,<a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>,<a href="#afec8ce807dc9bf79f073fa691fafe1f8">g_yyFileName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1083</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1084</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1085</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1086</span><span class="doxyLineContent"><span class="doxyHighlight">                                                   <a href="/web-doxygen/docs/api/classes/configimpl/#aa631fde6f0b7e94b180b07252096ec12">ConfigImpl::config_warn</a>(</span><span class="doxyHighlightStringLiteral">"Tag '{}' at line {} of file '{}' has become obsolete.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1087</span><span class="doxyLineContent"><span class="doxyHighlight">                                                              </span><span class="doxyHighlightStringLiteral">"         To avoid this warning please remove this line from your configuration "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1088</span><span class="doxyLineContent"><span class="doxyHighlight">                                                              </span><span class="doxyHighlightStringLiteral">"file or upgrade it using \"doxygen -u\"\n"</span><span class="doxyHighlight">, <a href="#a80001906a82b0d116f334f0bb065c7a9">g_cmd</a>,<a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>,<a href="#afec8ce807dc9bf79f073fa691fafe1f8">g_yyFileName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1089</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1090</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configobsolete">ConfigObsolete</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(option)-&gt;markAsPresent();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1091</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configobsolete">ConfigObsolete</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(option)-&gt;orgType()==<a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa18c0785bb1948fb57402ee80324ef1a7">ConfigOption::O_List</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1092</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1093</span><span class="doxyLineContent"><span class="doxyHighlight">                                                   <a href="#a6d73b052225d65c218ae7d286d8c633a">g_list</a> = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configobsolete">ConfigObsolete</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(option)-&gt;valueListRef();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1094</span><span class="doxyLineContent"><span class="doxyHighlight">                                                   <a href="#a6d73b052225d65c218ae7d286d8c633a">g_list</a>-&gt;clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1095</span><span class="doxyLineContent"><span class="doxyHighlight">                                                   <a href="#ad33b30a9730e3f9332e7eb36152f4276">g_listStr</a>=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1096</span><span class="doxyLineContent"><span class="doxyHighlight">                                                   BEGIN(GetStrList);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1097</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1098</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1099</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1100</span><span class="doxyLineContent"><span class="doxyHighlight">                                                   <a href="#a0b72791268d83dc5adf869ac258a3027">g_string</a> = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configobsolete">ConfigObsolete</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(option)-&gt;valueStringRef();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1101</span><span class="doxyLineContent"><span class="doxyHighlight">                                                   <a href="#a0b72791268d83dc5adf869ac258a3027">g_string</a>-&gt;clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1102</span><span class="doxyLineContent"><span class="doxyHighlight">                                                   BEGIN(GetString);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1103</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1104</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1105</span><span class="doxyLineContent"><span class="doxyHighlight">                                               </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa116df5f47c0442ad31ca0193cf540701">ConfigOption::O_Disabled</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1106</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a73e0a7c37c8a540748c113811329f998">g_configUpdate</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1107</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1108</span><span class="doxyLineContent"><span class="doxyHighlight">                                                   <a href="/web-doxygen/docs/api/classes/configimpl/#aa631fde6f0b7e94b180b07252096ec12">ConfigImpl::config_warn</a>(</span><span class="doxyHighlightStringLiteral">"Tag '{}' at line {} of file '{}' belongs to an option that was not enabled at compile time.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1109</span><span class="doxyLineContent"><span class="doxyHighlight">                                                              </span><span class="doxyHighlightStringLiteral">"         This tag has been removed.\n"</span><span class="doxyHighlight">, <a href="#a80001906a82b0d116f334f0bb065c7a9">g_cmd</a>,<a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>,<a href="#afec8ce807dc9bf79f073fa691fafe1f8">g_yyFileName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1110</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1111</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1112</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1113</span><span class="doxyLineContent"><span class="doxyHighlight">                                                   <a href="/web-doxygen/docs/api/classes/configimpl/#aa631fde6f0b7e94b180b07252096ec12">ConfigImpl::config_warn</a>(</span><span class="doxyHighlightStringLiteral">"Tag '{}' at line {} of file '{}' belongs to an option that was not enabled at compile time.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1114</span><span class="doxyLineContent"><span class="doxyHighlight">                                                              </span><span class="doxyHighlightStringLiteral">"         To avoid this warning please remove this line from your configuration "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1115</span><span class="doxyLineContent"><span class="doxyHighlight">                                                            </span><span class="doxyHighlightStringLiteral">"file or upgrade it using \"doxygen -u\", or recompile doxygen with this feature enabled.\n"</span><span class="doxyHighlight">, <a href="#a80001906a82b0d116f334f0bb065c7a9">g_cmd</a>,<a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>,<a href="#afec8ce807dc9bf79f073fa691fafe1f8">g_yyFileName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1116</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1117</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 BEGIN(SkipInvalid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1118</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1119</span><span class="doxyLineContent"><span class="doxyHighlight">                                             }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1120</span><span class="doxyLineContent"><span class="doxyHighlight">                                           }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1121</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1122</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;[a-z_A-Z][a-z_A-Z0-9]*[ \t]*"+="</span><span class="doxyHighlight"> { <a href="#a80001906a82b0d116f334f0bb065c7a9">g_cmd</a>=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1123</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a80001906a82b0d116f334f0bb065c7a9">g_cmd</a>=<a href="#a80001906a82b0d116f334f0bb065c7a9">g_cmd</a>.left(<a href="#a80001906a82b0d116f334f0bb065c7a9">g_cmd</a>.length()-2).stripWhiteSpace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1124</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/configoption">ConfigOption</a> *option = <a href="#ac8c998011c1de1f3c38cb48c908af98b">g_config</a>-&gt;get(<a href="#a80001906a82b0d116f334f0bb065c7a9">g_cmd</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1125</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (option==0) </span><span class="doxyHighlightComment">// oops not known</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1126</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1127</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/classes/configimpl/#aa631fde6f0b7e94b180b07252096ec12">ConfigImpl::config_warn</a>(</span><span class="doxyHighlightStringLiteral">"ignoring unsupported tag '{}' at line {}, file {}\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1128</span><span class="doxyLineContent"><span class="doxyHighlight">                                                <a href="#a80001906a82b0d116f334f0bb065c7a9">g_cmd</a>,<a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>,<a href="#afec8ce807dc9bf79f073fa691fafe1f8">g_yyFileName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1129</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(SkipInvalid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1130</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1131</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// known tag</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1132</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1133</span><span class="doxyLineContent"><span class="doxyHighlight">                                            option-&gt;<a href="/web-doxygen/docs/api/classes/configoption/#a5baa3fb6c4fb6ec667eb91172f3f398a">setUserComment</a>(<a href="#ac8c998011c1de1f3c38cb48c908af98b">g_config</a>-&gt;takeUserComment());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1134</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(option-&gt;<a href="/web-doxygen/docs/api/classes/configoption/#af9d4d56d36500792b82fce5b11202a60">kind</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1135</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1136</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaade872bcb27f40e3380fb20be7cea9e57">ConfigOption::O_Info</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1137</span><span class="doxyLineContent"><span class="doxyHighlight">                                                </span><span class="doxyHighlightComment">// shouldn't get here!</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1138</span><span class="doxyLineContent"><span class="doxyHighlight">                                                BEGIN(SkipInvalid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1139</span><span class="doxyLineContent"><span class="doxyHighlight">                                                </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1140</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa18c0785bb1948fb57402ee80324ef1a7">ConfigOption::O_List</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1141</span><span class="doxyLineContent"><span class="doxyHighlight">                                                <a href="#a6d73b052225d65c218ae7d286d8c633a">g_list</a> = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configlist">ConfigList</a> *</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(option)-&gt;valueRef();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1142</span><span class="doxyLineContent"><span class="doxyHighlight">                                                <a href="#ad33b30a9730e3f9332e7eb36152f4276">g_listStr</a>=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1143</span><span class="doxyLineContent"><span class="doxyHighlight">                                                BEGIN(GetStrList);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1144</span><span class="doxyLineContent"><span class="doxyHighlight">                                                </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1145</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa1ba2565ddffed94550a83a5b537e6a31">ConfigOption::O_Enum</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1146</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa3aa84b958a247d79889f28f4244a7d7f">ConfigOption::O_String</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1147</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaac029c8062b88308de12914e88e12dcd8">ConfigOption::O_Int</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1148</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa306962172c18f2b309fb729e66e32e81">ConfigOption::O_Bool</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1149</span><span class="doxyLineContent"><span class="doxyHighlight">                                                <a href="/web-doxygen/docs/api/classes/configimpl/#aa631fde6f0b7e94b180b07252096ec12">ConfigImpl::config_warn</a>(</span><span class="doxyHighlightStringLiteral">"operator += not supported for '{}'. Ignoring line at line {}, file {}\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1150</span><span class="doxyLineContent"><span class="doxyHighlight">                                                    yytext,<a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>,<a href="#afec8ce807dc9bf79f073fa691fafe1f8">g_yyFileName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1151</span><span class="doxyLineContent"><span class="doxyHighlight">                                                BEGIN(SkipInvalid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1152</span><span class="doxyLineContent"><span class="doxyHighlight">                                                </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1153</span><span class="doxyLineContent"><span class="doxyHighlight">                                               </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaab60c019594029c214e601ec24988d6ac">ConfigOption::O_Obsolete</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1154</span><span class="doxyLineContent"><span class="doxyHighlight">                                                <a href="/web-doxygen/docs/api/classes/configimpl/#aa631fde6f0b7e94b180b07252096ec12">ConfigImpl::config_warn</a>(</span><span class="doxyHighlightStringLiteral">"Tag '{}' at line {} of file {} has become obsolete.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1155</span><span class="doxyLineContent"><span class="doxyHighlight">                                                            </span><span class="doxyHighlightStringLiteral">"To avoid this warning please update your configuration "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1156</span><span class="doxyLineContent"><span class="doxyHighlight">                                                            </span><span class="doxyHighlightStringLiteral">"file using \"doxygen -u\"\n"</span><span class="doxyHighlight">, <a href="#a80001906a82b0d116f334f0bb065c7a9">g_cmd</a>,<a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>,<a href="#afec8ce807dc9bf79f073fa691fafe1f8">g_yyFileName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1157</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configobsolete">ConfigObsolete</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(option)-&gt;orgType()==<a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa18c0785bb1948fb57402ee80324ef1a7">ConfigOption::O_List</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1158</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1159</span><span class="doxyLineContent"><span class="doxyHighlight">                                                   <a href="#a6d73b052225d65c218ae7d286d8c633a">g_list</a> = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configobsolete">ConfigObsolete</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(option)-&gt;valueListRef();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1160</span><span class="doxyLineContent"><span class="doxyHighlight">                                                   <a href="#ad33b30a9730e3f9332e7eb36152f4276">g_listStr</a>=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1161</span><span class="doxyLineContent"><span class="doxyHighlight">                                                   BEGIN(GetStrList);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1162</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1163</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1164</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1165</span><span class="doxyLineContent"><span class="doxyHighlight">                                                   BEGIN(SkipInvalid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1166</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1167</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1168</span><span class="doxyLineContent"><span class="doxyHighlight">                                               </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa116df5f47c0442ad31ca0193cf540701">ConfigOption::O_Disabled</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1169</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 <a href="/web-doxygen/docs/api/classes/configimpl/#aa631fde6f0b7e94b180b07252096ec12">ConfigImpl::config_warn</a>(</span><span class="doxyHighlightStringLiteral">"Tag '{}' at line {} of file {} belongs to an option that was not enabled at compile time.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1170</span><span class="doxyLineContent"><span class="doxyHighlight">                                                            </span><span class="doxyHighlightStringLiteral">"To avoid this warning please remove this line from your configuration "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1171</span><span class="doxyLineContent"><span class="doxyHighlight">                                                            </span><span class="doxyHighlightStringLiteral">"file, upgrade it using \"doxygen -u\", or recompile doxygen with this feature enabled.\n"</span><span class="doxyHighlight">, </span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1172</span><span class="doxyLineContent"><span class="doxyHighlight">                                                            <a href="#a80001906a82b0d116f334f0bb065c7a9">g_cmd</a>,<a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>,<a href="#afec8ce807dc9bf79f073fa691fafe1f8">g_yyFileName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1173</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 BEGIN(SkipInvalid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1174</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1175</span><span class="doxyLineContent"><span class="doxyHighlight">                                             }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1176</span><span class="doxyLineContent"><span class="doxyHighlight">                                           }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1177</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1178</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1179</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightComment">/*-------------- INCLUDE* ---------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1180</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1181</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;"@INCLUDE_PATH"[ \t]*"="</span><span class="doxyHighlight">         { BEGIN(GetStrList); <a href="#a6d73b052225d65c218ae7d286d8c633a">g_list</a>=&amp;<a href="#a848459ef910ecc5e245bc68972a9aeac">g_includePathList</a>; <a href="#a6d73b052225d65c218ae7d286d8c633a">g_list</a>-&gt;clear(); <a href="#ad33b30a9730e3f9332e7eb36152f4276">g_listStr</a>=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1182</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/* include a g_config file */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1183</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;"@INCLUDE"[ \t]*"="</span><span class="doxyHighlight">              { BEGIN(Include);}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1184</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;"$("{REGEX_a}({REGEX_w}|[.-])*")"</span><span class="doxyHighlight"> | </span><span class="doxyHighlightComment">// e.g. $(HOME)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1185</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;"$("{REGEX_a}({REGEX_w}|[.-])*"("{REGEX_a}({REGEX_w}|[.-])*"))"</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// e.g. $(PROGRAMFILES(X86))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1186</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a24aadc37dfae7cbd3b93643cec296bab">g_localStoreRepl</a> = yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1187</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aba980278adc63976f725abf4f355309c">g_compareMode</a> == <a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940aa0ba248fb99f2c67cce98a6822482fba">Config::CompareMode::CompressedNoEnv</a>) </span><span class="doxyHighlightComment">// the x_noenv</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1188</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1189</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(StoreRepl);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1190</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1191</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1192</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1193</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#afcf1a493801a3f065ef9ca18e7c4f6c6">substEnvVarsInString</a>(<a href="#a24aadc37dfae7cbd3b93643cec296bab">g_localStoreRepl</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1194</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a86da2f5e3360caa90276fc24433d9512">unput_string</a>(<a href="#a24aadc37dfae7cbd3b93643cec296bab">g_localStoreRepl</a>.data(),<a href="#a24aadc37dfae7cbd3b93643cec296bab">g_localStoreRepl</a>.length());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1195</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1196</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1197</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;"@"{REGEX_a}{REGEX_w}*"@"</span><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1198</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aba980278adc63976f725abf4f355309c">g_compareMode</a> == <a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940aa0ba248fb99f2c67cce98a6822482fba">Config::CompareMode::CompressedNoEnv</a>) </span><span class="doxyHighlightComment">// the x_noenv</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1199</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1200</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a24aadc37dfae7cbd3b93643cec296bab">g_localStoreRepl</a> = yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1201</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(StoreRepl);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1202</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1203</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1204</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1205</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/classes/configimpl/#aa631fde6f0b7e94b180b07252096ec12">ConfigImpl::config_warn</a>(</span><span class="doxyHighlightStringLiteral">"ignoring unknown '{}' at line {}, file {}\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1206</span><span class="doxyLineContent"><span class="doxyHighlight">                                                        yytext,<a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>,<a href="#afec8ce807dc9bf79f073fa691fafe1f8">g_yyFileName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1207</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1208</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1209</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Include&gt;([^ \"\t\r\n]+)|("\""[^\n\"]+"\"")</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1210</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#acb71ba8a95e7beb78c1e3a685d8696ed">readIncludeFile</a>(<a href="#a6c24725da6b5b59e4c8867995e84648f">configStringRecode</a>(yytext,<a href="#a1d031dea12ce5dfc5759802ec854c2d2">g_encoding</a>,</span><span class="doxyHighlightStringLiteral">"UTF-8"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1211</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(Start);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1212</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1213</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;&lt;EOF&gt;&gt;</span><span class="doxyHighlight">                                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1214</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//printf("End of include file\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1215</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//printf("Include stack depth=%d\n",g_includeStack.count());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1216</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a53705fefd416a984be4714f1d0ca36a6">g_includeStack</a>.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1217</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1218</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">//printf("Terminating scanner!\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1219</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#ac3286b18a2e91b4571b97df96a118e84">yyterminate</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1220</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1221</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1222</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1223</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;fs=<a href="#a53705fefd416a984be4714f1d0ca36a6">g_includeStack</a>.back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1224</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/namespaces/portable/#af099fa6239b4961887192d8eadfd2a44">fclose</a>(fs-&gt;filePtr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1225</span><span class="doxyLineContent"><span class="doxyHighlight">                                            YY_BUFFER_STATE oldBuf = YY_CURRENT_BUFFER;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1226</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yy_switch_to_buffer( fs-&gt;oldState );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1227</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yy_delete_buffer( oldBuf );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1228</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>=fs-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1229</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#afec8ce807dc9bf79f073fa691fafe1f8">g_yyFileName</a>=fs-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1230</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a53705fefd416a984be4714f1d0ca36a6">g_includeStack</a>.pop_back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1231</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1232</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1233</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1234</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;[a-z_A-Z0-9]+</span><span class="doxyHighlight">                    { <a href="/web-doxygen/docs/api/classes/configimpl/#aa631fde6f0b7e94b180b07252096ec12">ConfigImpl::config_warn</a>(</span><span class="doxyHighlightStringLiteral">"ignoring unknown tag '{}' at line {}, file {}\n"</span><span class="doxyHighlight">,yytext,<a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>,<a href="#afec8ce807dc9bf79f073fa691fafe1f8">g_yyFileName</a>); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1235</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightComment">/*-------------- GetString ---------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1236</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1237</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;StoreRepl&gt;\n</span><span class="doxyHighlight">                           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1238</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a24aadc37dfae7cbd3b93643cec296bab">g_localStoreRepl</a> += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1239</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a48eae5f8b7d851992e7b3e04a01a8af3">processStoreRepl</a>(<a href="#a24aadc37dfae7cbd3b93643cec296bab">g_localStoreRepl</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1240</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac8c998011c1de1f3c38cb48c908af98b">g_config</a>-&gt;appendStoreRepl(<a href="#a24aadc37dfae7cbd3b93643cec296bab">g_localStoreRepl</a> + </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1241</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a24aadc37dfae7cbd3b93643cec296bab">g_localStoreRepl</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1242</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>++; </span><span class="doxyHighlightComment">// end of string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1243</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(Start);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1244</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1245</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;StoreRepl&gt;\\[ \r\t]*\n</span><span class="doxyHighlight">                 { <a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>++; </span><span class="doxyHighlightComment">// line continuation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1246</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a24aadc37dfae7cbd3b93643cec296bab">g_localStoreRepl</a> += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1247</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1248</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;StoreRepl&gt;"\\"</span><span class="doxyHighlight">                         { </span><span class="doxyHighlightComment">// escape character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1249</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a24aadc37dfae7cbd3b93643cec296bab">g_localStoreRepl</a> += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1250</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1251</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;StoreRepl&gt;[^\n\\]+</span><span class="doxyHighlight">                     { </span><span class="doxyHighlightComment">// string part without escape characters</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1252</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a24aadc37dfae7cbd3b93643cec296bab">g_localStoreRepl</a> += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1253</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1254</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightComment">/*-------------- GetString ---------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1255</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1256</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;GetString&gt;\n</span><span class="doxyHighlight">                           { <a href="#a53f751007ffe5b7c105c3821039a970c">processString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1257</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>++; </span><span class="doxyHighlightComment">// end of string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1258</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(Start);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1259</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1260</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;GetString&gt;\\[ \r\t]*\n</span><span class="doxyHighlight">                 { <a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>++; </span><span class="doxyHighlightComment">// line continuation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1261</span><span class="doxyLineContent"><span class="doxyHighlight">                                          *<a href="#a0b72791268d83dc5adf869ac258a3027">g_string</a>+=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1262</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1263</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;GetString&gt;"\\"</span><span class="doxyHighlight">                         { </span><span class="doxyHighlightComment">// escape character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1264</span><span class="doxyLineContent"><span class="doxyHighlight">                                          *<a href="#a0b72791268d83dc5adf869ac258a3027">g_string</a>+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1265</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1266</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;GetString&gt;[^\n\\]+</span><span class="doxyHighlight">                     { </span><span class="doxyHighlightComment">// string part without escape characters</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1267</span><span class="doxyLineContent"><span class="doxyHighlight">                                          *<a href="#a0b72791268d83dc5adf869ac258a3027">g_string</a>+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1268</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1269</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1270</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightComment">/*-------------- GetStrList --------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1271</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1272</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;GetStrList&gt;\n</span><span class="doxyHighlight">                          { <a href="#a1004c5eacd365bb12bb64c344baeebc6">processList</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1273</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>++; </span><span class="doxyHighlightComment">// end of list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1274</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(Start);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1275</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1276</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;GetStrList&gt;\\[ \r\t]*\n</span><span class="doxyHighlight">                { <a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>++; </span><span class="doxyHighlightComment">// line continuation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1277</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ad33b30a9730e3f9332e7eb36152f4276">g_listStr</a>+=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1278</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1279</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;GetStrList&gt;"\\"</span><span class="doxyHighlight">                        { </span><span class="doxyHighlightComment">// escape character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1280</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ad33b30a9730e3f9332e7eb36152f4276">g_listStr</a>+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1281</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1282</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;GetStrList&gt;[^\n\\]+</span><span class="doxyHighlight">                    { </span><span class="doxyHighlightComment">// string part without escape characters</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1283</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ad33b30a9730e3f9332e7eb36152f4276">g_listStr</a>+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1284</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1285</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1286</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightComment">/*-------------- SkipInvalid --------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1287</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1288</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipInvalid&gt;\n</span><span class="doxyHighlight">                         { <a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>++; </span><span class="doxyHighlightComment">// end of list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1289</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(Start);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1290</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1291</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipInvalid&gt;\\[ \r\t]*\n</span><span class="doxyHighlight">               { <a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>++; </span><span class="doxyHighlightComment">// line continuation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1292</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1293</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipInvalid&gt;"\\"</span><span class="doxyHighlight">                       { </span><span class="doxyHighlightComment">// escape character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1294</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1295</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipInvalid&gt;[^\n\\]+</span><span class="doxyHighlight">                   { </span><span class="doxyHighlightComment">// string part without escape characters</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1296</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1297</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1298</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightComment">/*-------------- fall through -------------*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1299</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1300</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;\\[ \r\t]*\n</span><span class="doxyHighlight">                         { <a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>++; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1301</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;[ \t\r]</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1302</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;\n</span><span class="doxyHighlight">                                   { <a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>++ ; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1303</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;.</span><span class="doxyHighlight">                                    { <a href="/web-doxygen/docs/api/classes/configimpl/#aa631fde6f0b7e94b180b07252096ec12">ConfigImpl::config_warn</a>(</span><span class="doxyHighlightStringLiteral">"ignoring unknown character '{:c}' at line {}, file {}\n"</span><span class="doxyHighlight">,yytext[0],<a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>,<a href="#afec8ce807dc9bf79f073fa691fafe1f8">g_yyFileName</a>); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1304</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1305</span><span class="doxyLineContent"><span class="doxyHighlight">%%</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/commentcnv-h/#a4706ae57556b5cab395e8d2c8ec666b9">convertCppComments</a>.</p>

</div>
</div>

### yyread() {#ad3e4b97ae438d8bc8a2ae5deedd523a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int yyread (char * buf, int max_size)</td>
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



<p>Definition at line 668 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad3e4b97ae438d8bc8a2ae5deedd523a7">668</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#ad3e4b97ae438d8bc8a2ae5deedd523a7">yyread</a>(</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *buf,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> max_size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">670</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// no file included</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">671</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a53705fefd416a984be4714f1d0ca36a6">g_includeStack</a>.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">672</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">673</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> c=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">674</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a4884b04c016cb29c59e337c3849a08fd">g_inputString</a>==0) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">675</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight">( c &lt; max_size &amp;&amp; <a href="#a4884b04c016cb29c59e337c3849a08fd">g_inputString</a>[<a href="#a5f7e5ad6f4837038547f7d2ea8e031eb">g_inputPosition</a>] )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">676</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">677</span><span class="doxyLineContent"><span class="doxyHighlight">      *buf = <a href="#a4884b04c016cb29c59e337c3849a08fd">g_inputString</a>[<a href="#a5f7e5ad6f4837038547f7d2ea8e031eb">g_inputPosition</a>++] ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">678</span><span class="doxyLineContent"><span class="doxyHighlight">      c++; buf++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">679</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">680</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">681</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">682</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">683</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">684</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//assert(g_includeStack.current()-&gt;newState==YY_CURRENT_BUFFER);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">685</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(fread(buf,1,max_size,<a href="#a53705fefd416a984be4714f1d0ca36a6">g_includeStack</a>.back()-&gt;filePtr));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">686</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">687</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a53705fefd416a984be4714f1d0ca36a6">g_includeStack</a>, <a href="#a5f7e5ad6f4837038547f7d2ea8e031eb">g_inputPosition</a> and <a href="#a4884b04c016cb29c59e337c3849a08fd">g_inputString</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### error\_str {#adda1f8011db5f4f0ec3d8ece91cfa724}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* error_str = "error: "</td>
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



<p>Definition at line 57 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adda1f8011db5f4f0ec3d8ece91cfa724">57</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#adda1f8011db5f4f0ec3d8ece91cfa724">error_str</a> = </span><span class="doxyHighlightStringLiteral">"error: "</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/configimpl/#a9b70bfd9dfb25eeca6a6d9308e67a8c4">ConfigImpl::config_err_</a> and <a href="/web-doxygen/docs/api/classes/configimpl/#a4933289a8ef6b198c98c5a555fa9013f">ConfigImpl::config_term_</a>.</p>

</div>
</div>

### g\_cmd {#a80001906a82b0d116f334f0bb065c7a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString g_cmd</td>
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



<p>Definition at line 645 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a80001906a82b0d116f334f0bb065c7a9">645</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>          <a href="#a80001906a82b0d116f334f0bb065c7a9">g_cmd</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a1004c5eacd365bb12bb64c344baeebc6">processList</a> and <a href="#a53f751007ffe5b7c105c3821039a970c">processString</a>.</p>

</div>
</div>

### g\_compareMode {#aba980278adc63976f725abf4f355309c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Config::CompareMode g_compareMode = <a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940abbd47109890259c0127154db1af26c75">Config::CompareMode::Full</a></td>
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



<p>Definition at line 654 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aba980278adc63976f725abf4f355309c">654</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940">Config::CompareMode</a> <a href="#aba980278adc63976f725abf4f355309c">g_compareMode</a> = <a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940abbd47109890259c0127154db1af26c75">Config::CompareMode::Full</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/namespaces/config/#a88ed583dc36b1439108163403cc4224f">Config::parse</a>.</p>

</div>
</div>

### g\_config {#ac8c998011c1de1f3c38cb48c908af98b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConfigImpl* g_config = nullptr</td>
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



<p>Definition at line 653 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac8c998011c1de1f3c38cb48c908af98b">653</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/configimpl">ConfigImpl</a>       *<a href="#ac8c998011c1de1f3c38cb48c908af98b">g_config</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a38bfc7b0b040cc8ceefae240aad38b94">checkEncoding</a>, <a href="/web-doxygen/docs/api/namespaces/config/#a88ed583dc36b1439108163403cc4224f">Config::parse</a>, <a href="/web-doxygen/docs/api/classes/configimpl/#a574ffab8ab91f47f27b9f142cbf1bdc4">ConfigImpl::parseString</a> and <a href="#a84908cbd8715e1a9294673286a5f7b6e">stripComment</a>.</p>

</div>
</div>

### g\_configUpdate {#a73e0a7c37c8a540748c113811329f998}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool g_configUpdate = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a></td>
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



<p>Definition at line 651 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a73e0a7c37c8a540748c113811329f998">651</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">              <a href="#a73e0a7c37c8a540748c113811329f998">g_configUpdate</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/configimpl/#a574ffab8ab91f47f27b9f142cbf1bdc4">ConfigImpl::parseString</a>.</p>

</div>
</div>

### g\_encoding {#a1d031dea12ce5dfc5759802ec854c2d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString g_encoding</td>
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



<p>Definition at line 652 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1d031dea12ce5dfc5759802ec854c2d2">652</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>          <a href="#a1d031dea12ce5dfc5759802ec854c2d2">g_encoding</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a38bfc7b0b040cc8ceefae240aad38b94">checkEncoding</a>, <a href="/web-doxygen/docs/api/classes/configimpl/#a5d06627b2afb76668e8315613a76b9d3">ConfigImpl::parse</a>, <a href="#a1004c5eacd365bb12bb64c344baeebc6">processList</a>, <a href="#a48eae5f8b7d851992e7b3e04a01a8af3">processStoreRepl</a> and <a href="#a53f751007ffe5b7c105c3821039a970c">processString</a>.</p>

</div>
</div>

### g\_includePathList {#a848459ef910ecc5e245bc68972a9aeac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringVector g_includePathList</td>
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



<p>Definition at line 649 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a848459ef910ecc5e245bc68972a9aeac">649</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a>      <a href="#a848459ef910ecc5e245bc68972a9aeac">g_includePathList</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a6232960902cd961ee248851d0f5a189d">findFile</a>.</p>

</div>
</div>

### g\_includeStack {#a53705fefd416a984be4714f1d0ca36a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; std::unique_ptr&lt;ConfigFileState&gt; &gt; g_includeStack</td>
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



<p>Definition at line 650 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a53705fefd416a984be4714f1d0ca36a6">650</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::vector&lt; std::unique_ptr&lt;ConfigFileState&gt; &gt; <a href="#a53705fefd416a984be4714f1d0ca36a6">g_includeStack</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/configimpl/#a574ffab8ab91f47f27b9f142cbf1bdc4">ConfigImpl::parseString</a>, <a href="#a692163c1902febf3d5dc44644e851f26">readIncludeFile</a> and <a href="#ad3e4b97ae438d8bc8a2ae5deedd523a7">yyread</a>.</p>

</div>
</div>

### g\_inputPosition {#a5f7e5ad6f4837038547f7d2ea8e031eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int g_inputPosition = 0</td>
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



<p>Definition at line 642 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5f7e5ad6f4837038547f7d2ea8e031eb">642</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">               <a href="#a5f7e5ad6f4837038547f7d2ea8e031eb">g_inputPosition</a> = 0;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/configimpl/#a574ffab8ab91f47f27b9f142cbf1bdc4">ConfigImpl::parseString</a> and <a href="#ad3e4b97ae438d8bc8a2ae5deedd523a7">yyread</a>.</p>

</div>
</div>

### g\_inputString {#a4884b04c016cb29c59e337c3849a08fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* g_inputString = nullptr</td>
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



<p>Definition at line 641 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4884b04c016cb29c59e337c3849a08fd">641</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">       *<a href="#a4884b04c016cb29c59e337c3849a08fd">g_inputString</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/configimpl/#a574ffab8ab91f47f27b9f142cbf1bdc4">ConfigImpl::parseString</a> and <a href="#ad3e4b97ae438d8bc8a2ae5deedd523a7">yyread</a>.</p>

</div>
</div>

### g\_list {#a6d73b052225d65c218ae7d286d8c633a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringVector* g_list = nullptr</td>
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



<p>Definition at line 647 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6d73b052225d65c218ae7d286d8c633a">647</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a>     *<a href="#a6d73b052225d65c218ae7d286d8c633a">g_list</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a1004c5eacd365bb12bb64c344baeebc6">processList</a>.</p>

</div>
</div>

### g\_listStr {#ad33b30a9730e3f9332e7eb36152f4276}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString g_listStr</td>
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



<p>Definition at line 648 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad33b30a9730e3f9332e7eb36152f4276">648</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>          <a href="#ad33b30a9730e3f9332e7eb36152f4276">g_listStr</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a1004c5eacd365bb12bb64c344baeebc6">processList</a>.</p>

</div>
</div>

### g\_localStoreRepl {#a24aadc37dfae7cbd3b93643cec296bab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString g_localStoreRepl</td>
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



<p>Definition at line 655 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a24aadc37dfae7cbd3b93643cec296bab">655</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>          <a href="#a24aadc37dfae7cbd3b93643cec296bab">g_localStoreRepl</a>;</span></span></div>

</div>

</div>
</div>

### g\_string {#a0b72791268d83dc5adf869ac258a3027}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString* g_string = nullptr</td>
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



<p>Definition at line 646 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0b72791268d83dc5adf869ac258a3027">646</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>         *<a href="#a0b72791268d83dc5adf869ac258a3027">g_string</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a53f751007ffe5b7c105c3821039a970c">processString</a>.</p>

</div>
</div>

### g\_yyFileName {#afec8ce807dc9bf79f073fa691fafe1f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString g_yyFileName</td>
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



<p>Definition at line 644 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afec8ce807dc9bf79f073fa691fafe1f8">644</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>          <a href="#afec8ce807dc9bf79f073fa691fafe1f8">g_yyFileName</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/configimpl/#a574ffab8ab91f47f27b9f142cbf1bdc4">ConfigImpl::parseString</a>, <a href="#a1004c5eacd365bb12bb64c344baeebc6">processList</a>, <a href="#a53f751007ffe5b7c105c3821039a970c">processString</a> and <a href="#a692163c1902febf3d5dc44644e851f26">readIncludeFile</a>.</p>

</div>
</div>

### g\_yyLineNr {#ada427227e611310f718c3d614f32d032}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int g_yyLineNr = 1</td>
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



<p>Definition at line 643 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ada427227e611310f718c3d614f32d032">643</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">               <a href="#ada427227e611310f718c3d614f32d032">g_yyLineNr</a> = 1;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/configimpl/#a574ffab8ab91f47f27b9f142cbf1bdc4">ConfigImpl::parseString</a>, <a href="#a1004c5eacd365bb12bb64c344baeebc6">processList</a>, <a href="#a53f751007ffe5b7c105c3821039a970c">processString</a> and <a href="#a692163c1902febf3d5dc44644e851f26">readIncludeFile</a>.</p>

</div>
</div>

### reEnvVar {#a93417da3de847772a0db1c1067124b57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const reg::Ex reEnvVar(R"(\$\((\a[\w.-]*)\))")</td>
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



<p>Definition at line 1388 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<p>Referenced by <a href="#a4c20e33d84d7477620edc8cdf3e3333b">containsEnvVar</a> and <a href="#afcf1a493801a3f065ef9ca18e7c4f6c6">substEnvVarsInString</a>.</p>

</div>
</div>

### reEnvVar1CMake {#ad46c127e61124d3dae3308327103a2b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const reg::Ex reEnvVar1CMake(R"(\${\a\w*})")</td>
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



<p>Definition at line 1391 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<p>Referenced by <a href="#a4c20e33d84d7477620edc8cdf3e3333b">containsEnvVar</a>.</p>

</div>
</div>

### reEnvVarCMake {#ad8742d431dca72b48403598209fa3278}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const reg::Ex reEnvVarCMake(R"(@\a\w*@)")</td>
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



<p>Definition at line 1390 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<p>Referenced by <a href="#a4c20e33d84d7477620edc8cdf3e3333b">containsEnvVar</a>.</p>

</div>
</div>

### reEnvVarExt {#a8ef2cd114dfa4c36bb86f42ec41c74ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const reg::Ex reEnvVarExt(R"(\$\((\a[\w.-]*\(\a[\w.-]*\))\))")</td>
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



<p>Definition at line 1389 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<p>Referenced by <a href="#a4c20e33d84d7477620edc8cdf3e3333b">containsEnvVar</a> and <a href="#afcf1a493801a3f065ef9ca18e7c4f6c6">substEnvVarsInString</a>.</p>

</div>
</div>

### warning\_str {#a4b306c7d6514a51d731a5b581ce6c2a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* warning_str = "warning: "</td>
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



<p>Definition at line 56 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4b306c7d6514a51d731a5b581ce6c2a4">56</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a4b306c7d6514a51d731a5b581ce6c2a4">warning_str</a> = </span><span class="doxyHighlightStringLiteral">"warning: "</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/configimpl/#ace74e2339d8c059f2842d934b8da1238">ConfigImpl::config_warn_</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### LEX\_NO\_REENTRANT {#a146a93da1f8efdea496a6d138d4773bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LEX_NO_REENTRANT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 665 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a146a93da1f8efdea496a6d138d4773bc">665</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define LEX_NO_REENTRANT</span></span></div>

</div>

</div>
</div>

### MAX\_INCLUDE\_DEPTH {#a641f7209d924c2c4cb24420dcd631f37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MAX_INCLUDE_DEPTH&nbsp;&nbsp;&nbsp;10</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a641f7209d924c2c4cb24420dcd631f37">83</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define MAX_INCLUDE_DEPTH 10</span></span></div>

</div>


<p>Referenced by <a href="#a692163c1902febf3d5dc44644e851f26">readIncludeFile</a>.</p>

</div>
</div>

### SHOW\_INCLUDES {#abc983123ed5d1694a014d1ea7c1f22cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SHOW_INCLUDES&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abc983123ed5d1694a014d1ea7c1f22cb">52</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define SHOW_INCLUDES 0</span></span></div>

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



<p>Definition at line 657 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a86da2f5e3360caa90276fc24433d9512">657</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define unput_string(yytext,yyleng) do { for (int i=(int)yyleng-1;i&gt;=0;i--) unput(yytext[i]); } while(0)</span></span></div>

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
<td class="doxyMemberName">#define YY_INPUT(buf, result, max_size)&nbsp;&nbsp;&nbsp;result=<a href="/web-doxygen/docs/api/files/src/code-l/#a5edfc25f0c460f3263fdb340f7a02b03">yyread</a>(buf,max_size);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 661 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aacfdca45fa4beb8b06172525a53c424a">661</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define YY_INPUT(buf,result,max_size) result=yyread(buf,max_size);</span></span></div>

</div>

</div>
</div>

### YY\_NEVER\_INTERACTIVE {#a15b85de192a189d5a31cdd518e001e6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define YY_NEVER_INTERACTIVE&nbsp;&nbsp;&nbsp;1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a15b85de192a189d5a31cdd518e001e6e">84</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define YY_NEVER_INTERACTIVE 1</span></span></div>

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



<p>Definition at line 48 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a85523a0c7d95c059d251b4e9829947aa">48</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define YY_NO_INPUT 1</span></span></div>

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



<p>Definition at line 49 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae78ac56cd1f29572e967ed7636952d15">49</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define YY_NO_UNISTD_H 1</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
