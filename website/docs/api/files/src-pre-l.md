---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/src/pre-l
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `pre.l` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;stdint.h&gt;
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
#include &lt;stack&gt;
#include &lt;deque&gt;
#include &lt;algorithm&gt;
#include &lt;utility&gt;
#include &lt;mutex&gt;
#include &lt;thread&gt;
#include &lt;cstdio&gt;
#include &lt;cassert&gt;
#include &lt;cctype&gt;
#include &lt;cerrno&gt;
#include "<a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/containers-h">containers.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/pre-h">pre.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/constexp-h">constexp.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/define-h">define.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/defargs-h">defargs.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/portable-h">portable.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/entry-h">entry.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/condparser-h">condparser.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/fileinfo-h">fileinfo.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/trace-h">trace.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/stringutil-h">stringutil.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-lex-h">doxygen_lex.h</a>"
#include "pre.l.h"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/preyy-condctx">preYY_CondCtx</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/filestate">FileState</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/preincludeinfo">PreIncludeInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/definemanager">DefineManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class that manages the defines available while preprocessing files. <a href="/web-doxygen/docs/api/classes/definemanager/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/definemanager/definesperfile">DefinesPerFile</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Local class used to hold the defines for a single file. <a href="/web-doxygen/docs/api/classes/definemanager/definesperfile/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/preyy-state">preYY_state</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/preprocessor/private">Private</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::map&lt; std::string, <a href="/web-doxygen/docs/api/classes/define">Define</a> &gt; <a href="#a0dd482007e6d1df4a67172cda7af1a61">DefineMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A dictionary of managed <a href="/web-doxygen/docs/api/classes/define">Define</a> objects. <a href="#a0dd482007e6d1df4a67172cda7af1a61">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad860c94401483cee6345e6dd71bab597">escapeAt</a> (const QCString &amp;text)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f2d544ac38e037f4572ce9163d17aed">extractTrailingComment</a> (const QCString &amp;s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61c9302d64d5e3f8a5e4638a1cdb9b7b">resolveTrigraph</a> (char c)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a> (yyscan_t yyscanner, const char *a, yy_size_t len)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ac956f197291fa939c052de93bd3d16">outputString</a> (yyscan_t yyscanner, const QCString &amp;s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a> (yyscan_t yyscanner, char c)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34739dd6d965f4701c9b7611d7c2cf9a">outputSpaces</a> (yyscan_t yyscanner, char *s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae596fa0b1fbc60f9128146cc90630101">outputSpace</a> (yyscan_t yyscanner, char c)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5614d3a5285ab7ae715d23044c1e7e4">extraSpacing</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a319a5456c54411f74e047b8dad2de802">expandMacro</a> (yyscan_t yyscanner, const QCString &amp;name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9af0795be28dcf4551e57a2a3650a552">readIncludeFile</a> (yyscan_t yyscanner, const QCString &amp;inc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2afcdad2a81b0416c9b3fb843e631222">incrLevel</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1917523a9eee16ade8021a9135d5e1da">decrLevel</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a151056056972fe928bb34e8ed2c5a4fe">setCaseDone</a> (yyscan_t yyscanner, bool value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abec6a57b1258c5230a0dde8cf6e2c91f">otherCaseDone</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3133546e20fd36ac3b7568349ce5285">computeExpression</a> (yyscan_t yyscanner, const QCString &amp;expr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ec58197ab496c7ea5a9be5edb5d6073">startCondSection</a> (yyscan_t yyscanner, const QCString &amp;sectId)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34860cedec3675010f3293403abd9bd3">endCondSection</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a157d33872a9501263b2b34cc7ced0ffa">addMacroDefinition</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a207d66f561747d53a0df54a5019cc45b">addDefine</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cd40076f3904d6c6ea657b00df39cc6">setFileName</a> (yyscan_t yyscanner, const QCString &amp;name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/define">Define</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37deceebb857c5178f2ae90e8da172f2">isDefined</a> (yyscan_t yyscanner, const QCString &amp;name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a reference to a <a href="/web-doxygen/docs/api/classes/define">Define</a> object given its name or 0 if the <a href="/web-doxygen/docs/api/classes/define">Define</a> does not exist. <a href="#a37deceebb857c5178f2ae90e8da172f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20e87c94c55f270beb04921ae491a309">determineBlockName</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static yy_size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5261e1258a952d5fa2ff996546768c9">getFenceSize</a> (char *txt, yy_size_t leng)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/filestate">FileState</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abac7d9e657d1d9ac8ccfa460710de204">checkAndOpenFile</a> (yyscan_t yyscanner, const QCString &amp;fileName, bool &amp;alreadyProcessed)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/filestate">FileState</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44966d15bb9a0624cead77c6e3c89f94">findFile</a> (yyscan_t yyscanner, const QCString &amp;fileName, bool localInclude, bool &amp;alreadyProcessed)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28d316d115be97fa510e349537535baf">getNextChar</a> (yyscan_t yyscanner, const QCString &amp;expr, QCString *rest, uint32_t &amp;pos)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1706fe9365c74e213edf9f291a23f473">getCurrentChar</a> (yyscan_t yyscanner, const QCString &amp;expr, QCString *rest, uint32_t pos)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5f2a2b1209c93f3dafe4ab22a33b844">unputChar</a> (yyscan_t yyscanner, const QCString &amp;expr, QCString *rest, uint32_t &amp;pos, char c)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bc8b7f200b9267b0c7b842ecd1f25b0">expandExpression</a> (yyscan_t yyscanner, QCString &amp;expr, QCString *rest, int pos, int level)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a085c52ce4351470497b03309e77228cc">stringize</a> (const QCString &amp;s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8262966752d5069cd91cf2ecec43afd">processConcatOperators</a> (QCString &amp;expr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a854da9613a4c1ada693e325bbdd812a1">returnCharToStream</a> (yyscan_t yyscanner, char c)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a956c6709f23acd037aa021578b5b5472">addTillEndOfString</a> (yyscan_t yyscanner, const QCString &amp;expr, QCString *rest, uint32_t &amp;pos, char term, QCString &amp;arg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8c379a1956b4f1623587160df8a0584">skipCommentMacroName</a> (yyscan_t yyscanner, const QCString &amp;expr, QCString *rest, int &amp;cc, uint32_t &amp;j, int &amp;len)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af18da14aec7b354ada7376e24ca5e6ec">replaceFunctionMacro</a> (yyscan_t yyscanner, const QCString &amp;expr, QCString *rest, int pos, int &amp;len, const Define *def, QCString &amp;result, int level)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a9b5774d3b3547b5143e86594853498">getNextId</a> (const QCString &amp;expr, int p, int *l)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a295f0fcb46dce77d4ff897094e7914">addSeparatorsIfNeeded</a> (yyscan_t yyscanner, const QCString &amp;expr, QCString &amp;resultExpr, QCString &amp;restExpr, int pos)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5a00bad9b10b8fe9542cba69f171028">processUntilMatchingTerminator</a> (const char *inputStr, QCString &amp;result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Process string or character literal. <a href="#ad5a00bad9b10b8fe9542cba69f171028">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bbb2d9191d513b9cbfb864ee2043a3c">removeIdsAndMarkers</a> (const QCString &amp;s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5ee30cbed9991fc9961669602045e88">removeMarkers</a> (const QCString &amp;s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96730086e79b6790b6269d07152a1735">forceEndCondSection</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35e7ee6baadfec49f7e85a2cf14d5deb">initPredefined</a> (yyscan_t yyscanner, const QCString &amp;fileName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa74555c39c3f592f0d6113ba0dc6aa9">g_debugMutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41d40eee862471579482f58a442f157d">g_globalDefineMutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbb87735f2e6370eeb5934dc1476cd7b">g_updateGlobals</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/definemanager">DefineManager</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a888d117646a1150fd6672a7cc9c0a81d">g_defineManager</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a246c42ffcd2228031eb52e0de54b60d5">MAX_EXPANSION_DEPTH</a>&nbsp;&nbsp;&nbsp;50</td>
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

### DefineMap {#a0dd482007e6d1df4a67172cda7af1a61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::map&lt; std::string, Define &gt; DefineMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A dictionary of managed <a href="/web-doxygen/docs/api/classes/define">Define</a> objects.</p>

<p>Definition at line 109 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0dd482007e6d1df4a67172cda7af1a61">109</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">typedef</span><span class="doxyHighlight"> std::map&lt; std::string, Define &gt; <a href="#a0dd482007e6d1df4a67172cda7af1a61">DefineMap</a>;</span></span></div>

</div>

</div>
</div>

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



<p>Definition at line 24 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9484188abbc459dafcbd4c96425fa70b">24</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">typedef</span><span class="doxyHighlight"> yyguts_t *<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a>;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### addDefine() {#a207d66f561747d53a0df54a5019cc45b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addDefine (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 3384 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a207d66f561747d53a0df54a5019cc45b">3384</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a207d66f561747d53a0df54a5019cc45b">addDefine</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3385</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3386</span><span class="doxyLineContent"><span class="doxyHighlight">  YY_EXTRA_TYPE state = preYYget_extra(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3387</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/define">Define</a> def;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3388</span><span class="doxyLineContent"><span class="doxyHighlight">  def.<a href="/web-doxygen/docs/api/classes/define/#a2ab61e312bcf057292789daa0de8bf78">name</a>       = state-&gt;defName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3389</span><span class="doxyLineContent"><span class="doxyHighlight">  def.<a href="/web-doxygen/docs/api/classes/define/#ac76e113d9f4c5b64553022777f686093">definition</a> = state-&gt;defText.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3390</span><span class="doxyLineContent"><span class="doxyHighlight">  def.<a href="/web-doxygen/docs/api/classes/define/#ad3306a44c59125a65fbf9559abe97930">nargs</a>      = state-&gt;defArgs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3391</span><span class="doxyLineContent"><span class="doxyHighlight">  def.<a href="/web-doxygen/docs/api/classes/define/#a2403c7fc667a4a5fd74c8a78560030cc">fileName</a>   = state-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3392</span><span class="doxyLineContent"><span class="doxyHighlight">  def.<a href="/web-doxygen/docs/api/classes/define/#a3f350ee951cde6b1955612af5be6a6d5">fileDef</a>    = state-&gt;yyFileDef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3393</span><span class="doxyLineContent"><span class="doxyHighlight">  def.<a href="/web-doxygen/docs/api/classes/define/#a16325de589f92470990e80e0d3cb403f">lineNr</a>     = state-&gt;yyLineNr-state-&gt;yyMLines;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3394</span><span class="doxyLineContent"><span class="doxyHighlight">  def.<a href="/web-doxygen/docs/api/classes/define/#aa3baaeb7d662ad6190da946f3a65a773">columnNr</a>   = state-&gt;yyColNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3395</span><span class="doxyLineContent"><span class="doxyHighlight">  def.<a href="/web-doxygen/docs/api/classes/define/#a1802523098fdd274fd15cd0494ad26d1">varArgs</a>    = state-&gt;defVarArgs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3396</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("newDefine: %s %s file: %s\n",qPrint(def.name),qPrint(def.definition),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3397</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//    def.fileDef ? qPrint(def.fileDef-&gt;name()) : qPrint(def.fileName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3398</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("newDefine: '%s'-&gt;'%s'\n",qPrint(def.name),qPrint(def.definition));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3399</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!def.<a href="/web-doxygen/docs/api/classes/define/#a2ab61e312bcf057292789daa0de8bf78">name</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3400</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/doxygen/#a2f51dd7f38c65ae685a20618265d5d97">Doxygen::expandAsDefinedSet</a>.find(def.<a href="/web-doxygen/docs/api/classes/define/#a2ab61e312bcf057292789daa0de8bf78">name</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>())!=<a href="/web-doxygen/docs/api/classes/doxygen/#a2f51dd7f38c65ae685a20618265d5d97">Doxygen::expandAsDefinedSet</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3401</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3402</span><span class="doxyLineContent"><span class="doxyHighlight">    def.<a href="/web-doxygen/docs/api/classes/define/#a856ae02f323f7e3f95fee4101da3904b">isPredefined</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3403</span><span class="doxyLineContent"><span class="doxyHighlight">    def.<a href="/web-doxygen/docs/api/classes/define/#ad611bbbe5c08fd5da2724916ebdec09f">expandAsDefined</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3404</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3405</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = state-&gt;localDefines.find(def.<a href="/web-doxygen/docs/api/classes/define/#a2ab61e312bcf057292789daa0de8bf78">name</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3406</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=state-&gt;localDefines.end()) </span><span class="doxyHighlightComment">// redefine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3407</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3408</span><span class="doxyLineContent"><span class="doxyHighlight">    state-&gt;localDefines.erase(it);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3409</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3410</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;localDefines.emplace(def.<a href="/web-doxygen/docs/api/classes/define/#a2ab61e312bcf057292789daa0de8bf78">name</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),def);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3411</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/define/#aa3baaeb7d662ad6190da946f3a65a773">Define::columnNr</a>, <a href="/web-doxygen/docs/api/classes/define/#ac76e113d9f4c5b64553022777f686093">Define::definition</a>, <a href="/web-doxygen/docs/api/classes/define/#ad611bbbe5c08fd5da2724916ebdec09f">Define::expandAsDefined</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a2f51dd7f38c65ae685a20618265d5d97">Doxygen::expandAsDefinedSet</a>, <a href="/web-doxygen/docs/api/classes/define/#a3f350ee951cde6b1955612af5be6a6d5">Define::fileDef</a>, <a href="/web-doxygen/docs/api/classes/define/#a2403c7fc667a4a5fd74c8a78560030cc">Define::fileName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/define/#a856ae02f323f7e3f95fee4101da3904b">Define::isPredefined</a>, <a href="/web-doxygen/docs/api/classes/define/#a16325de589f92470990e80e0d3cb403f">Define::lineNr</a>, <a href="/web-doxygen/docs/api/classes/define/#a2ab61e312bcf057292789daa0de8bf78">Define::name</a>, <a href="/web-doxygen/docs/api/classes/define/#ad3306a44c59125a65fbf9559abe97930">Define::nargs</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/classes/define/#a1802523098fdd274fd15cd0494ad26d1">Define::varArgs</a>.</p>

</div>
</div>

### addMacroDefinition() {#a157d33872a9501263b2b34cc7ced0ffa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addMacroDefinition (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 3413 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a157d33872a9501263b2b34cc7ced0ffa">3413</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a157d33872a9501263b2b34cc7ced0ffa">addMacroDefinition</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3414</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3415</span><span class="doxyLineContent"><span class="doxyHighlight">  YY_EXTRA_TYPE state = preYYget_extra(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3416</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (state-&gt;skip) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// do not add this define as it is inside a</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3417</span><span class="doxyLineContent"><span class="doxyHighlight">                      </span><span class="doxyHighlightComment">// conditional section (cond command) that is disabled.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3418</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3419</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/define">Define</a> define;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3420</span><span class="doxyLineContent"><span class="doxyHighlight">  define.<a href="/web-doxygen/docs/api/classes/define/#a2403c7fc667a4a5fd74c8a78560030cc">fileName</a> = state-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3421</span><span class="doxyLineContent"><span class="doxyHighlight">  define.<a href="/web-doxygen/docs/api/classes/define/#a16325de589f92470990e80e0d3cb403f">lineNr</a>   = state-&gt;yyLineNr - state-&gt;yyMLines;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3422</span><span class="doxyLineContent"><span class="doxyHighlight">  define.<a href="/web-doxygen/docs/api/classes/define/#aa3baaeb7d662ad6190da946f3a65a773">columnNr</a> = state-&gt;yyColNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3423</span><span class="doxyLineContent"><span class="doxyHighlight">  define.<a href="/web-doxygen/docs/api/classes/define/#a2ab61e312bcf057292789daa0de8bf78">name</a>     = state-&gt;defName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3424</span><span class="doxyLineContent"><span class="doxyHighlight">  define.<a href="/web-doxygen/docs/api/classes/define/#a1ab8e5663a0acb5c7634087fb32c67b8">args</a>     = state-&gt;defArgsStr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3425</span><span class="doxyLineContent"><span class="doxyHighlight">  define.<a href="/web-doxygen/docs/api/classes/define/#a3f350ee951cde6b1955612af5be6a6d5">fileDef</a>  = state-&gt;inputFileDef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3426</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3427</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> litText = state-&gt;defLitText;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3428</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> l=litText.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3429</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (l&gt;0 &amp;&amp; litText.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(l).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>()==</span><span class="doxyHighlightStringLiteral">"\\"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3430</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3431</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// strip first line if it only contains a slash</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3432</span><span class="doxyLineContent"><span class="doxyHighlight">    litText = litText.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(litText.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-l-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3433</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3434</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (l&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3435</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3436</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// align the items on the first line with the items on the second line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3437</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> k=l+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3438</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=litText.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()+k;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3439</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3440</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++) &amp;&amp; (c==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">)) k++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3441</span><span class="doxyLineContent"><span class="doxyHighlight">    litText=litText.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(l+1,k-l-1)+litText.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3442</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3443</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> litTextStripped = state-&gt;defLitText.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3444</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (litTextStripped.<a href="/web-doxygen/docs/api/classes/qcstring/#aeeedb2810a85c682c2f2a86bcd2355a7">contains</a>(</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)&gt;=1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3445</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3446</span><span class="doxyLineContent"><span class="doxyHighlight">    define.<a href="/web-doxygen/docs/api/classes/define/#ac76e113d9f4c5b64553022777f686093">definition</a> = litText;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3447</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3448</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3449</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3450</span><span class="doxyLineContent"><span class="doxyHighlight">    define.<a href="/web-doxygen/docs/api/classes/define/#ac76e113d9f4c5b64553022777f686093">definition</a> = litTextStripped;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3451</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3452</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3453</span><span class="doxyLineContent"><span class="doxyHighlight">    state-&gt;macroDefinitions.push_back(define);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3454</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3455</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/define/#a1ab8e5663a0acb5c7634087fb32c67b8">Define::args</a>, <a href="/web-doxygen/docs/api/classes/define/#aa3baaeb7d662ad6190da946f3a65a773">Define::columnNr</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aeeedb2810a85c682c2f2a86bcd2355a7">QCString::contains</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/define/#ac76e113d9f4c5b64553022777f686093">Define::definition</a>, <a href="/web-doxygen/docs/api/classes/define/#a3f350ee951cde6b1955612af5be6a6d5">Define::fileDef</a>, <a href="/web-doxygen/docs/api/classes/define/#a2403c7fc667a4a5fd74c8a78560030cc">Define::fileName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/define/#a16325de589f92470990e80e0d3cb403f">Define::lineNr</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/classes/define/#a2ab61e312bcf057292789daa0de8bf78">Define::name</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">QCString::right</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>.</p>

</div>
</div>

### addSeparatorsIfNeeded() {#a4a295f0fcb46dce77d4ff897094e7914}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addSeparatorsIfNeeded (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; expr, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; resultExpr, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; restExpr, int pos)</td>
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



<p>Definition at line 2881 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4a295f0fcb46dce77d4ff897094e7914">2881</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4a295f0fcb46dce77d4ff897094e7914">addSeparatorsIfNeeded</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;expr,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;resultExpr,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;restExpr,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> pos)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2882</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2883</span><span class="doxyLineContent"><span class="doxyHighlight">  YY_EXTRA_TYPE state = preYYget_extra(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2884</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!state-&gt;nospaces)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2885</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2886</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// peek back in the stream, for a colon character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2887</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> ccPrev = pos==0 || (int)expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()&lt;pos ? state-&gt;prevChar : expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(pos-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2888</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> leftSpace = ccPrev!=</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight"> &amp;&amp; ccPrev!=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> ? </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2889</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> ccNext = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2890</span><span class="doxyLineContent"><span class="doxyHighlight">    restExpr=restExpr.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2891</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (restExpr.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightComment">// peek ahead in the stream for non-whitespace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2892</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2893</span><span class="doxyLineContent"><span class="doxyHighlight">      uint32_t j=(uint32_t)resultExpr.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2894</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((ccNext=<a href="#a28d316d115be97fa510e349537535baf">getNextChar</a>(yyscanner,resultExpr,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,j))!=EOF &amp;&amp; ccNext==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) { }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2895</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ccNext != EOF) <a href="#ad5f2a2b1209c93f3dafe4ab22a33b844">unputChar</a>(yyscanner,resultExpr,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,j,(</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">)ccNext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2896</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2897</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// take first char from remainder</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2898</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2899</span><span class="doxyLineContent"><span class="doxyHighlight">      ccNext=restExpr.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2900</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2901</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// don't add whitespace before a colon</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2902</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> rightSpace = ccNext!=</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight"> &amp;&amp; ccNext!=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> ? </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2903</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("ccPrev='%c' ccNext='%c' p=%d expr=%zu restExpr='%s' left='%s' right='%s'\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2904</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//    ccPrev,ccNext,pos,expr.length(),qPrint(restExpr),qPrint(leftSpace),qPrint(rightSpace));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2905</span><span class="doxyLineContent"><span class="doxyHighlight">    resultExpr=leftSpace+resultExpr+rightSpace;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2906</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2907</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="#a28d316d115be97fa510e349537535baf">getNextChar</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a> and <a href="#ad5f2a2b1209c93f3dafe4ab22a33b844">unputChar</a>.</p>


<p>Referenced by <a href="#a1bc8b7f200b9267b0c7b842ecd1f25b0">expandExpression</a>.</p>

</div>
</div>

### addTillEndOfString() {#a956c6709f23acd037aa021578b5b5472}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addTillEndOfString (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; expr, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> * rest, uint32_t &amp; pos, char term, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; arg)</td>
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



<p>Definition at line 2525 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a956c6709f23acd037aa021578b5b5472">2525</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a956c6709f23acd037aa021578b5b5472">addTillEndOfString</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;expr,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> *rest,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2526</span><span class="doxyLineContent"><span class="doxyHighlight">                                       uint32_t &amp;pos,</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;arg)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2527</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2528</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> cc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2529</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((cc=<a href="#a28d316d115be97fa510e349537535baf">getNextChar</a>(yyscanner,expr,rest,pos))!=EOF &amp;&amp; cc!=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2530</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2531</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cc==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">) arg+=(char)cc,cc=<a href="#a28d316d115be97fa510e349537535baf">getNextChar</a>(yyscanner,expr,rest,pos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2532</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cc==<a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2533</span><span class="doxyLineContent"><span class="doxyHighlight">    arg+=(char)cc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2534</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2535</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a28d316d115be97fa510e349537535baf">getNextChar</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>.</p>


<p>Referenced by <a href="#af18da14aec7b354ada7376e24ca5e6ec">replaceFunctionMacro</a>.</p>

</div>
</div>

### checkAndOpenFile() {#abac7d9e657d1d9ac8ccfa460710de204}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; FileState &gt; checkAndOpenFile (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, bool &amp; alreadyProcessed)</td>
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



<p>Definition at line 2213 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abac7d9e657d1d9ac8ccfa460710de204">2213</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::unique_ptr&lt;FileState&gt; <a href="#abac7d9e657d1d9ac8ccfa460710de204">checkAndOpenFile</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> &amp;alreadyProcessed)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2214</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2215</span><span class="doxyLineContent"><span class="doxyHighlight">  YY_EXTRA_TYPE state = preYYget_extra(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2216</span><span class="doxyLineContent"><span class="doxyHighlight">  alreadyProcessed = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2217</span><span class="doxyLineContent"><span class="doxyHighlight">  std::unique_ptr&lt;FileState&gt; fs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2218</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("checkAndOpenFile(%s)\n",qPrint(fileName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2219</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fi(fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2220</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>() &amp;&amp; fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#ab7840bb4fca4b3d9938c1b3f0e1352ef">isFile</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2221</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2222</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> &amp;exclPatterns = <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>(EXCLUDE_PATTERNS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2223</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/util-cpp/#a5499df1f291fa1ad70e96e2848e78e2c">patternMatch</a>(fi,exclPatterns)) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2224</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2225</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> absName = fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#af69e3949475014dcdbd504d742bdf270">absFilePath</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2226</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2227</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// global guard</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2228</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (state-&gt;curlyCount==0) </span><span class="doxyHighlightComment">// not #include inside { ... }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2229</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2230</span><span class="doxyLineContent"><span class="doxyHighlight">      std::lock_guard&lt;std::mutex&gt; lock(<a href="#a41d40eee862471579482f58a442f157d">g_globalDefineMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2231</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a888d117646a1150fd6672a7cc9c0a81d">g_defineManager</a>.alreadyProcessed(absName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2232</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2233</span><span class="doxyLineContent"><span class="doxyHighlight">        alreadyProcessed = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2234</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("  already included 1\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2235</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; </span><span class="doxyHighlightComment">// already done</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2236</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2237</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2238</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// check include stack for absName</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2239</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2240</span><span class="doxyLineContent"><span class="doxyHighlight">    alreadyProcessed = std::any_of(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2241</span><span class="doxyLineContent"><span class="doxyHighlight">      state-&gt;includeStack.begin(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2242</span><span class="doxyLineContent"><span class="doxyHighlight">      state-&gt;includeStack.end(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2243</span><span class="doxyLineContent"><span class="doxyHighlight">      [absName](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::unique_ptr&lt;FileState&gt; &amp;lfs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2244</span><span class="doxyLineContent"><span class="doxyHighlight">        { return lfs-&gt;fileName==absName; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2245</span><span class="doxyLineContent"><span class="doxyHighlight">    );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2246</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2247</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (alreadyProcessed)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2248</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2249</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("  already included 2\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2250</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2251</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2252</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("#include %s\n",qPrint(absName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2253</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2254</span><span class="doxyLineContent"><span class="doxyHighlight">    fs = std::make_unique&lt;FileState&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2255</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/util-cpp/#a4d2f69fa42eae96d0b7ca66f9f0673ae">readInputFile</a>(absName,fs-&gt;fileBuf))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2256</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightComment">// error</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2257</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("  error reading\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2258</span><span class="doxyLineContent"><span class="doxyHighlight">      fs.reset();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2259</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2260</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2261</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2262</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/stringutil-h/#a7dd208e0912669ffb021565424b1bc05">addTerminalCharIfMissing</a>(fs-&gt;fileBuf,</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2263</span><span class="doxyLineContent"><span class="doxyHighlight">      fs-&gt;oldFileBuf    = state-&gt;inputBuf;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2264</span><span class="doxyLineContent"><span class="doxyHighlight">      fs-&gt;oldFileBufPos = state-&gt;inputBufPos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2265</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2266</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2267</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> fs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2268</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/fileinfo/#af69e3949475014dcdbd504d742bdf270">FileInfo::absFilePath</a>, <a href="/web-doxygen/docs/api/files/src/stringutil-h/#a7dd208e0912669ffb021565424b1bc05">addTerminalCharIfMissing</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">FileInfo::exists</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a888d117646a1150fd6672a7cc9c0a81d">g_defineManager</a>, <a href="#a41d40eee862471579482f58a442f157d">g_globalDefineMutex</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#ab7840bb4fca4b3d9938c1b3f0e1352ef">FileInfo::isFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5499df1f291fa1ad70e96e2848e78e2c">patternMatch</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a4d2f69fa42eae96d0b7ca66f9f0673ae">readInputFile</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>


<p>Referenced by <a href="#a44966d15bb9a0624cead77c6e3c89f94">findFile</a>.</p>

</div>
</div>

### computeExpression() {#ae3133546e20fd36ac3b7568349ce5285}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool computeExpression (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; expr)</td>
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




<p>compute the value of the expression in string <em>expr</em>. If needed the function may read additional characters from the input.</p>


<p>Definition at line 3351 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae3133546e20fd36ac3b7568349ce5285">3351</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae3133546e20fd36ac3b7568349ce5285">computeExpression</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;expr)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3352</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3353</span><span class="doxyLineContent"><span class="doxyHighlight">  YY_EXTRA_TYPE state = preYYget_extra(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3354</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> e=expr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3355</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> ee=expr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3356</span><span class="doxyLineContent"><span class="doxyHighlight">  ee = <a href="#ae5ee30cbed9991fc9961669602045e88">removeMarkers</a>(ee);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3357</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;expanded.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3358</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1bc8b7f200b9267b0c7b842ecd1f25b0">expandExpression</a>(yyscanner,e,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,0,0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3359</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("after expansion '%s'\n",qPrint(e));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3360</span><span class="doxyLineContent"><span class="doxyHighlight">  e = <a href="#a2bbb2d9191d513b9cbfb864ee2043a3c">removeIdsAndMarkers</a>(e);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3361</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (e.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3362</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("parsing '%s'\n",qPrint(e));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3363</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> state-&gt;constExpParser.parse(state-&gt;fileName.data(),state-&gt;yyLineNr,e.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),ee.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3364</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a1bc8b7f200b9267b0c7b842ecd1f25b0">expandExpression</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a2bbb2d9191d513b9cbfb864ee2043a3c">removeIdsAndMarkers</a>, <a href="#ae5ee30cbed9991fc9961669602045e88">removeMarkers</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>

</div>
</div>

### decrLevel() {#a1917523a9eee16ade8021a9135d5e1da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void decrLevel (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 2178 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1917523a9eee16ade8021a9135d5e1da">2178</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1917523a9eee16ade8021a9135d5e1da">decrLevel</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2179</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2180</span><span class="doxyLineContent"><span class="doxyHighlight">  YY_EXTRA_TYPE state = preYYget_extra(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2181</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("%s line %d: decrLevel %d\n",qPrint(state-&gt;fileName),state-&gt;yyLineNr,state-&gt;levelGuard.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2182</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!state-&gt;levelGuard.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2183</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2184</span><span class="doxyLineContent"><span class="doxyHighlight">    state-&gt;levelGuard.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2185</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2186</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2187</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2188</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(state-&gt;fileName,state-&gt;yyLineNr,</span><span class="doxyHighlightStringLiteral">"More #endif's than #if's found."</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2189</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2190</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/markdown/private/#a2a97ed987f163573d91e6a46363c99de">Markdown::Private::writeBlockQuote</a>.</p>

</div>
</div>

### determineBlockName() {#a20e87c94c55f270beb04921ae491a309}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void determineBlockName (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 3505 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a20e87c94c55f270beb04921ae491a309">3505</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a20e87c94c55f270beb04921ae491a309">determineBlockName</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3506</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3507</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t * yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3508</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;fenceSize=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3509</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3510</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yytext[1]==</span><span class="doxyHighlightCharLiteral">'f'</span><span class="doxyHighlight"> &amp;&amp; ((c=yytext[2])==</span><span class="doxyHighlightCharLiteral">'['</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'$'</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3511</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3512</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3513</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3514</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'['</span><span class="doxyHighlight">: yyextra-&gt;blockName=</span><span class="doxyHighlightStringLiteral">"]"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3515</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">: yyextra-&gt;blockName=</span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3516</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">: yyextra-&gt;blockName=</span><span class="doxyHighlightStringLiteral">")"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3517</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'$'</span><span class="doxyHighlight">: yyextra-&gt;blockName=</span><span class="doxyHighlightStringLiteral">"$"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3518</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3519</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3520</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;blockName=yyextra-&gt;blockName.stripWhiteSpace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3521</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3522</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3523</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3524</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> bn=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(&amp;yytext[1]).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3525</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bn==</span><span class="doxyHighlightStringLiteral">"startuml"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3526</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3527</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;blockName=</span><span class="doxyHighlightStringLiteral">"uml"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3528</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3529</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3530</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3531</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = bn.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">); </span><span class="doxyHighlightComment">// for \code{.c}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3532</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i!=-1) bn=bn.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(i).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3533</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;blockName=bn;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3534</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3535</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3536</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>.</p>

</div>
</div>

### endCondSection() {#a34860cedec3675010f3293403abd9bd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void endCondSection (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 3705 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a34860cedec3675010f3293403abd9bd3">3705</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a34860cedec3675010f3293403abd9bd3">endCondSection</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3706</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3707</span><span class="doxyLineContent"><span class="doxyHighlight">  YY_EXTRA_TYPE state = preYYget_extra(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3708</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (state-&gt;condStack.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3709</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3710</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(state-&gt;fileName,state-&gt;yyLineNr,</span><span class="doxyHighlightStringLiteral">"the \\endcond does not have a corresponding \\cond in this file"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3711</span><span class="doxyLineContent"><span class="doxyHighlight">    state-&gt;skip=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3712</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3713</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3714</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3715</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::unique_ptr&lt;preYY_CondCtx&gt; &amp;ctx = state-&gt;condStack.top();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3716</span><span class="doxyLineContent"><span class="doxyHighlight">    state-&gt;skip=ctx-&gt;skip;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3717</span><span class="doxyLineContent"><span class="doxyHighlight">    state-&gt;condStack.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3718</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3719</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("endCondSection: skip=%d stack=%d\n",state-&gt;skip,state-&gt;condStack.count());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3720</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.</p>

</div>
</div>

### escapeAt() {#ad860c94401483cee6345e6dd71bab597}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString escapeAt (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
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



<p>Definition at line 3732 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad860c94401483cee6345e6dd71bab597">3732</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ad860c94401483cee6345e6dd71bab597">escapeAt</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3733</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3734</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3735</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!text.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3736</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3737</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3738</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=text.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3739</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3740</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3741</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">) result+=</span><span class="doxyHighlightStringLiteral">"@@"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3742</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3743</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3744</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3745</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>.</p>

</div>
</div>

### expandExpression() {#a1bc8b7f200b9267b0c7b842ecd1f25b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool expandExpression (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; expr, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> * rest, int pos, int level)</td>
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




<p>performs recursive macro expansion on the string <em>expr</em> starting at position <em>pos</em>. May read additional characters from the input while re-scanning!</p>


<p>Definition at line 2913 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1bc8b7f200b9267b0c7b842ecd1f25b0">2913</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a1bc8b7f200b9267b0c7b842ecd1f25b0">expandExpression</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;expr,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> *rest,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> pos,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2914</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2915</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t * yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2916</span><span class="doxyLineContent"><span class="doxyHighlight">  YY_EXTRA_TYPE state = preYYget_extra(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2917</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("&gt;expandExpression(expr='%s',rest='%s',pos=%d,level=%d)\n",qPrint(expr),rest ? qPrint(*rest) : "", pos, level);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2918</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2919</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2920</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("&lt;expandExpression: empty\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2921</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2922</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2923</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (state-&gt;expanded.find(expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>())!=state-&gt;expanded.end() &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2924</span><span class="doxyLineContent"><span class="doxyHighlight">      level&gt;<a href="#a246c42ffcd2228031eb52e0de54b60d5">MAX_EXPANSION_DEPTH</a>) </span><span class="doxyHighlightComment">// check for too deep recursive expansions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2925</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2926</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("&lt;expandExpression: already expanded expr='%s'\n",qPrint(expr));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2927</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2928</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2929</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2930</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2931</span><span class="doxyLineContent"><span class="doxyHighlight">    state-&gt;expanded.insert(expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2932</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2933</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> macroName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2934</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> expMacro;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2935</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> definedTest=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2936</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=pos, l=0, p=0, len=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2937</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startPos = pos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2938</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> samePosCount=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2939</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((p=<a href="#a4a9b5774d3b3547b5143e86594853498">getNextId</a>(expr,i,&amp;l))!=-1) </span><span class="doxyHighlightComment">// search for an macro name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2940</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2941</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> replaced=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2942</span><span class="doxyLineContent"><span class="doxyHighlight">    macroName=expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(p,l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2943</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf(" p=%d macroName=%s\n",p,qPrint(macroName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2944</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (p&lt;2 || !(expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(p-2)==</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight"> &amp;&amp; expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(p-1)==</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">)) </span><span class="doxyHighlightComment">// no-rescan marker?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2945</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2946</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (state-&gt;expandedDict.find(macroName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>())==state-&gt;expandedDict.end()) </span><span class="doxyHighlightComment">// expand macro</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2947</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2948</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/define">Define</a> *def=<a href="#a37deceebb857c5178f2ae90e8da172f2">isDefined</a>(yyscanner,macroName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2949</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// In case EXPAND_ONLY_PREDEF is enabled prevent expansion unless the macro was explicitly</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2950</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// predefined</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2951</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;expandOnlyPredef &amp;&amp; def &amp;&amp; !def-&gt;<a href="/web-doxygen/docs/api/classes/define/#a856ae02f323f7e3f95fee4101da3904b">isPredefined</a>) def=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2952</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (macroName==</span><span class="doxyHighlightStringLiteral">"defined"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2953</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2954</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//printf("found defined inside macro definition '%s'\n",qPrint(expr.right(expr.length()-p)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2955</span><span class="doxyLineContent"><span class="doxyHighlight">          definedTest=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2956</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2957</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (definedTest) </span><span class="doxyHighlightComment">// macro name was found after defined</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2958</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2959</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (def) expMacro = </span><span class="doxyHighlightStringLiteral">" 1 "</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> expMacro = </span><span class="doxyHighlightStringLiteral">" 0 "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2960</span><span class="doxyLineContent"><span class="doxyHighlight">          replaced=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2961</span><span class="doxyLineContent"><span class="doxyHighlight">          len=l;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2962</span><span class="doxyLineContent"><span class="doxyHighlight">          definedTest=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2963</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2964</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (def &amp;&amp; def-&gt;<a href="/web-doxygen/docs/api/classes/define/#ad3306a44c59125a65fbf9559abe97930">nargs</a>==-1) </span><span class="doxyHighlightComment">// simple macro</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2965</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2966</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// substitute the definition of the macro</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2967</span><span class="doxyLineContent"><span class="doxyHighlight">          expMacro=def-&gt;<a href="/web-doxygen/docs/api/classes/define/#ac76e113d9f4c5b64553022777f686093">definition</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2968</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//expMacro=def-&gt;definition.stripWhiteSpace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2969</span><span class="doxyLineContent"><span class="doxyHighlight">          replaced=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2970</span><span class="doxyLineContent"><span class="doxyHighlight">          len=l;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2971</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//printf("simple macro expansion='%s'-&gt;'%s'\n",qPrint(macroName),qPrint(expMacro));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2972</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2973</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (def &amp;&amp; def-&gt;<a href="/web-doxygen/docs/api/classes/define/#ad3306a44c59125a65fbf9559abe97930">nargs</a>&gt;=0) </span><span class="doxyHighlightComment">// function macro</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2974</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2975</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//printf(" &gt;&gt;&gt;&gt; call replaceFunctionMacro expr='%s'\n",qPrint(expr));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2976</span><span class="doxyLineContent"><span class="doxyHighlight">          replaced=<a href="#af18da14aec7b354ada7376e24ca5e6ec">replaceFunctionMacro</a>(yyscanner,expr,rest,p+l,len,def,expMacro,level);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2977</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//printf(" &lt;&lt;&lt;&lt; call replaceFunctionMacro: replaced=%d\n",replaced);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2978</span><span class="doxyLineContent"><span class="doxyHighlight">          len+=l;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2979</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2980</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf(" macroName='%s' expMacro='%s' replaced=%d\n",qPrint(macroName),qPrint(expMacro),replaced);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2981</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2982</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (replaced) </span><span class="doxyHighlightComment">// expand the macro and rescan the expression</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2983</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2984</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//printf(" replacing '%s'-&gt;'%s'\n",qPrint(expr.mid(p,len)),qPrint(expMacro));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2985</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> resultExpr=expMacro;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2986</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> restExpr=expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-len-p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2987</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a4a295f0fcb46dce77d4ff897094e7914">addSeparatorsIfNeeded</a>(yyscanner,expr,resultExpr,restExpr,p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2988</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#ad8262966752d5069cd91cf2ecec43afd">processConcatOperators</a>(resultExpr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2989</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//printf(" macroName=%s restExpr='%s' def-&gt;nonRecursive=%d\n",qPrint(macroName),qPrint(restExpr),def-&gt;nonRecursive);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2990</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> expanded=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2991</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (def &amp;&amp; !def-&gt;<a href="/web-doxygen/docs/api/classes/define/#a673dcd69701965f0f62c73ce14dc6665">nonRecursive</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2992</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2993</span><span class="doxyLineContent"><span class="doxyHighlight">            state-&gt;expandedDict.emplace(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#ac7e12ef0c11e1acc583d1d66404c2557">toStdString</a>(macroName),def);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2994</span><span class="doxyLineContent"><span class="doxyHighlight">            expanded = <a href="#a1bc8b7f200b9267b0c7b842ecd1f25b0">expandExpression</a>(yyscanner,resultExpr,&amp;restExpr,0,level+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2995</span><span class="doxyLineContent"><span class="doxyHighlight">            state-&gt;expandedDict.erase(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#ac7e12ef0c11e1acc583d1d66404c2557">toStdString</a>(macroName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2996</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2997</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (def &amp;&amp; def-&gt;<a href="/web-doxygen/docs/api/classes/define/#a673dcd69701965f0f62c73ce14dc6665">nonRecursive</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2998</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2999</span><span class="doxyLineContent"><span class="doxyHighlight">            expanded = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3000</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3001</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (expanded)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3002</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3003</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">//printf("expanded '%s' + '%s' + '%s'\n",qPrint(expr.left(p)),qPrint(resultExpr),qPrint(restExpr));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3004</span><span class="doxyLineContent"><span class="doxyHighlight">            expr=expr.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(p)+resultExpr+restExpr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3005</span><span class="doxyLineContent"><span class="doxyHighlight">            i=p;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3006</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3007</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3008</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3009</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">//printf("not expanded '%s' + @- '%s'\n",qPrint(expr.left(p)),qPrint(expr.right(expr.length()-p)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3010</span><span class="doxyLineContent"><span class="doxyHighlight">            expr=expr.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(p)+</span><span class="doxyHighlightStringLiteral">"@-"</span><span class="doxyHighlight">+expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3011</span><span class="doxyLineContent"><span class="doxyHighlight">            i=p+l+2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3012</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3013</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3014</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// move to the next macro name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3015</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3016</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//printf(" moving to the next macro old i=%d new i=%d\n",i,p+l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3017</span><span class="doxyLineContent"><span class="doxyHighlight">          i=p+l;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3018</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3019</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3020</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// move to the next macro name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3021</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3022</span><span class="doxyLineContent"><span class="doxyHighlight">        expr=expr.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(p)+</span><span class="doxyHighlightStringLiteral">"@-"</span><span class="doxyHighlight">+expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3023</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("macro already expanded, moving to the next macro expr=%s\n",qPrint(expr));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3024</span><span class="doxyLineContent"><span class="doxyHighlight">        i=p+l+2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3025</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//i=p+l;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3026</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3027</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// check for too many inplace expansions without making progress</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3028</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i==startPos)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3029</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3030</span><span class="doxyLineContent"><span class="doxyHighlight">        samePosCount++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3031</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3032</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3033</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3034</span><span class="doxyLineContent"><span class="doxyHighlight">        startPos=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3035</span><span class="doxyLineContent"><span class="doxyHighlight">        samePosCount=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3036</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3037</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (samePosCount&gt;<a href="#a246c42ffcd2228031eb52e0de54b60d5">MAX_EXPANSION_DEPTH</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3038</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3039</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3040</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3041</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3042</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// no re-scan marker found, skip the macro name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3043</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3044</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("skipping marked macro\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3045</span><span class="doxyLineContent"><span class="doxyHighlight">      i=p+l;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3046</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3047</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3048</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("&lt;expandExpression(expr='%s',rest='%s',pos=%d,level=%d)\n",qPrint(expr),rest ? qPrint(*rest) : "", pos,level);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3049</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3050</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a4a295f0fcb46dce77d4ff897094e7914">addSeparatorsIfNeeded</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/classes/define/#ac76e113d9f4c5b64553022777f686093">Define::definition</a>, <a href="#a1bc8b7f200b9267b0c7b842ecd1f25b0">expandExpression</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a4a9b5774d3b3547b5143e86594853498">getNextId</a>, <a href="#a37deceebb857c5178f2ae90e8da172f2">isDefined</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/define/#a856ae02f323f7e3f95fee4101da3904b">Define::isPredefined</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#a246c42ffcd2228031eb52e0de54b60d5">MAX_EXPANSION_DEPTH</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/classes/define/#ad3306a44c59125a65fbf9559abe97930">Define::nargs</a>, <a href="/web-doxygen/docs/api/classes/define/#a673dcd69701965f0f62c73ce14dc6665">Define::nonRecursive</a>, <a href="#ad8262966752d5069cd91cf2ecec43afd">processConcatOperators</a>, <a href="#af18da14aec7b354ada7376e24ca5e6ec">replaceFunctionMacro</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">QCString::right</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#ac7e12ef0c11e1acc583d1d66404c2557">toStdString</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>


<p>Referenced by <a href="#ae3133546e20fd36ac3b7568349ce5285">computeExpression</a>, <a href="#a1bc8b7f200b9267b0c7b842ecd1f25b0">expandExpression</a>, <a href="#a319a5456c54411f74e047b8dad2de802">expandMacro</a> and <a href="#af18da14aec7b354ada7376e24ca5e6ec">replaceFunctionMacro</a>.</p>

</div>
</div>

### expandMacro() {#a319a5456c54411f74e047b8dad2de802}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString expandMacro (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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




<p>expands the macro definition in <em>name</em> If needed the function may read additional characters from the input</p>


<p>Definition at line 3370 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a319a5456c54411f74e047b8dad2de802">3370</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a319a5456c54411f74e047b8dad2de802">expandMacro</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3371</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3372</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3373</span><span class="doxyLineContent"><span class="doxyHighlight">  YY_EXTRA_TYPE state = preYYget_extra(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3374</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;prevChar = yyscanner-&gt;yytext_r &gt; YY_CURRENT_BUFFER_LVALUE-&gt;yy_ch_buf ? *(yyscanner-&gt;yytext_r-1) : 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3375</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> n=name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3376</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;expanded.<a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">clear</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3377</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1bc8b7f200b9267b0c7b842ecd1f25b0">expandExpression</a>(yyscanner,n,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,0,0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3378</span><span class="doxyLineContent"><span class="doxyHighlight">  n=<a href="#ae5ee30cbed9991fc9961669602045e88">removeMarkers</a>(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3379</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;prevChar=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3380</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("expandMacro '%s'-&gt;'%s'\n",qPrint(name),qPrint(n));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3381</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> n;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3382</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">QCString::clear</a>, <a href="#a1bc8b7f200b9267b0c7b842ecd1f25b0">expandExpression</a> and <a href="#ae5ee30cbed9991fc9961669602045e88">removeMarkers</a>.</p>

</div>
</div>

### extractTrailingComment() {#a4f2d544ac38e037f4572ce9163d17aed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString extractTrailingComment (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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



<p>Definition at line 2344 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4f2d544ac38e037f4572ce9163d17aed">2344</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a4f2d544ac38e037f4572ce9163d17aed">extractTrailingComment</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2345</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2346</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2347</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=(int)s.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2348</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&gt;=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2349</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2350</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c=s[i];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2351</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2352</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2353</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2354</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2355</span><span class="doxyLineContent"><span class="doxyHighlight">          i--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2356</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&gt;=0 &amp;&amp; s[i]==</span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// end of a comment block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2357</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2358</span><span class="doxyLineContent"><span class="doxyHighlight">            i--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2359</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&gt;0 &amp;&amp; !(s[i-1]==</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight"> &amp;&amp; s[i]==</span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">)) i--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2360</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2361</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2362</span><span class="doxyLineContent"><span class="doxyHighlight">              i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2363</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2364</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// only /*!&lt; ... */ or /**&lt; ... */ are treated as a comment for the macro name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2365</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// otherwise the comment is treated as part of the macro definition</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2366</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> ((s[i+1]==</span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight"> || s[i+1]==</span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight">) &amp;&amp; s[i+2]==</span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">) ? &amp;s[i-1] : </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2367</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2368</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2369</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2370</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2371</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2372</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2373</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2374</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// whitespace or line-continuation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2375</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2376</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2377</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\r'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2378</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2379</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2380</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2381</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2382</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2383</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2384</span><span class="doxyLineContent"><span class="doxyHighlight">    i--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2385</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2386</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2387</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>.</p>

</div>
</div>

### extraSpacing() {#ac5614d3a5285ab7ae715d23044c1e7e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void extraSpacing (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 3492 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac5614d3a5285ab7ae715d23044c1e7e4">3492</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac5614d3a5285ab7ae715d23044c1e7e4">extraSpacing</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3493</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3494</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t * yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3495</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;defContinue) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3496</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0; i&lt; (int)yyleng; i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3497</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3498</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yytext[i] == </span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3499</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;defExtraSpacing+=</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3500</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3501</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;defExtraSpacing+=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3502</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3503</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### findFile() {#a44966d15bb9a0624cead77c6e3c89f94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; FileState &gt; findFile (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, bool localInclude, bool &amp; alreadyProcessed)</td>
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



<p>Definition at line 2270 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a44966d15bb9a0624cead77c6e3c89f94">2270</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::unique_ptr&lt;FileState&gt; <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a6232960902cd961ee248851d0f5a189d">findFile</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> localInclude,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> &amp;alreadyProcessed)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2271</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2272</span><span class="doxyLineContent"><span class="doxyHighlight">  YY_EXTRA_TYPE state = preYYget_extra(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2273</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("** findFile(%s,%d) state-&gt;fileName=%s\n",qPrint(fileName),localInclude,qPrint(state-&gt;fileName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2274</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/namespaces/portable/#a08dc4d7f652408d7fc2eaba792796cb1">Portable::isAbsolutePath</a>(fileName))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2275</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2276</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> fs = <a href="#abac7d9e657d1d9ac8ccfa460710de204">checkAndOpenFile</a>(yyscanner,fileName,alreadyProcessed);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2277</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2278</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2279</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a3cd40076f3904d6c6ea657b00df39cc6">setFileName</a>(yyscanner,fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2280</span><span class="doxyLineContent"><span class="doxyHighlight">      state-&gt;yyLineNr=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2281</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> fs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2282</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2283</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (alreadyProcessed)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2284</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2285</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2286</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2287</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2288</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (localInclude &amp;&amp; !state-&gt;fileName.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2289</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2290</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fi(state-&gt;fileName.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2291</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2292</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2293</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> absName = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">dirPath</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>))+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2294</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> fs = <a href="#abac7d9e657d1d9ac8ccfa460710de204">checkAndOpenFile</a>(yyscanner,absName,alreadyProcessed);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2295</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2296</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2297</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a3cd40076f3904d6c6ea657b00df39cc6">setFileName</a>(yyscanner,absName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2298</span><span class="doxyLineContent"><span class="doxyHighlight">        state-&gt;yyLineNr=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2299</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> fs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2300</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2301</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (alreadyProcessed)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2302</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2303</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2304</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2305</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2306</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2307</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (state-&gt;pathList.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2308</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2309</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2310</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2311</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> path : state-&gt;pathList)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2312</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2313</span><span class="doxyLineContent"><span class="doxyHighlight">    std::string absName = (path+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+fileName).str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2314</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("  Looking for %s in %s\n",fileName,path.c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2315</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> fs = <a href="#abac7d9e657d1d9ac8ccfa460710de204">checkAndOpenFile</a>(yyscanner,absName.c_str(),alreadyProcessed);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2316</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2317</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2318</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a3cd40076f3904d6c6ea657b00df39cc6">setFileName</a>(yyscanner,absName.c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2319</span><span class="doxyLineContent"><span class="doxyHighlight">      state-&gt;yyLineNr=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2320</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("  -&gt; found it\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2321</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> fs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2322</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2323</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (alreadyProcessed)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2324</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2325</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2326</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2327</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2328</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ambig = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2329</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd=<a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>,fileName,ambig);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2330</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fd &amp;&amp; !ambig) </span><span class="doxyHighlightComment">// fallback in case the file is uniquely named in the input, use that one</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2331</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2332</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> fs = <a href="#abac7d9e657d1d9ac8ccfa460710de204">checkAndOpenFile</a>(yyscanner,fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">absFilePath</a>(),alreadyProcessed);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2333</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2334</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2335</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a3cd40076f3904d6c6ea657b00df39cc6">setFileName</a>(yyscanner,fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">absFilePath</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2336</span><span class="doxyLineContent"><span class="doxyHighlight">      state-&gt;yyLineNr=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2337</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("  -&gt; found it\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2338</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> fs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2339</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2340</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2341</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2342</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">FileDef::absFilePath</a>, <a href="#abac7d9e657d1d9ac8ccfa460710de204">checkAndOpenFile</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">FileInfo::dirPath</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">FileInfo::exists</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a08dc4d7f652408d7fc2eaba792796cb1">Portable::isAbsolutePath</a>, <a href="#a3cd40076f3904d6c6ea657b00df39cc6">setFileName</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### forceEndCondSection() {#a96730086e79b6790b6269d07152a1735}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void forceEndCondSection (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 3722 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a96730086e79b6790b6269d07152a1735">3722</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a96730086e79b6790b6269d07152a1735">forceEndCondSection</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3723</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3724</span><span class="doxyLineContent"><span class="doxyHighlight">  YY_EXTRA_TYPE state = preYYget_extra(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3725</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!state-&gt;condStack.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3726</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3727</span><span class="doxyLineContent"><span class="doxyHighlight">    state-&gt;condStack.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3728</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3729</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;skip=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3730</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/preprocessor/#ab3f6062c1f94727e3d51963720d13417">Preprocessor::processFile</a>.</p>

</div>
</div>

### getCurrentChar() {#a1706fe9365c74e213edf9f291a23f473}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int getCurrentChar (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; expr, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> * rest, uint32_t pos)</td>
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



<p>Definition at line 3790 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1706fe9365c74e213edf9f291a23f473">3790</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a1706fe9365c74e213edf9f291a23f473">getCurrentChar</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;expr,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> *rest,uint32_t pos)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3791</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3792</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("getCurrentChar(%s,%s,%d)\n",qPrint(expr),rest ? rest-&gt;data() : 0,pos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3793</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pos&lt;expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3794</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3795</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("%c=expr()\n",expr.at(pos));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3796</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(pos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3797</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3798</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rest &amp;&amp; !rest-&gt;<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3799</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3800</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> cc=rest-&gt;<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3801</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("%c=rest\n",cc);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3802</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> cc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3803</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3804</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3805</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3806</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> cc=yyinput(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3807</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a854da9613a4c1ada693e325bbdd812a1">returnCharToStream</a>(yyscanner,(</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">)cc);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3808</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("%c=yyinput()\n",cc);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3809</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> cc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3810</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3811</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a> and <a href="#a854da9613a4c1ada693e325bbdd812a1">returnCharToStream</a>.</p>


<p>Referenced by <a href="#af18da14aec7b354ada7376e24ca5e6ec">replaceFunctionMacro</a> and <a href="#af8c379a1956b4f1623587160df8a0584">skipCommentMacroName</a>.</p>

</div>
</div>

### getFenceSize() {#aa5261e1258a952d5fa2ff996546768c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">yy_size_t getFenceSize (char * txt, yy_size_t leng)</td>
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



<p>Definition at line 2139 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa5261e1258a952d5fa2ff996546768c9">2139</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> yy_size_t <a href="#aa5261e1258a952d5fa2ff996546768c9">getFenceSize</a>(</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *txt, yy_size_t leng)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2140</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2141</span><span class="doxyLineContent"><span class="doxyHighlight">  yy_size_t fenceSize = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2142</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i = 0; i &lt; leng; i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2143</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2144</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (txt[i] != </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> &amp;&amp; txt[i] != </span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight"> &amp;&amp; txt[i] != </span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2145</span><span class="doxyLineContent"><span class="doxyHighlight">     fenceSize++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2146</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2147</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> leng-fenceSize;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2148</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

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



<p>Definition at line 352 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acb5f8818546103e3b804ab8606b52c4a">352</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#acb5f8818546103e3b804ab8606b52c4a">getLexerFILE</a>() {</span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> __FILE__;}</span></span></div>

</div>

</div>
</div>

### getNextChar() {#a28d316d115be97fa510e349537535baf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int getNextChar (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; expr, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> * rest, uint32_t &amp; pos)</td>
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



<p>Definition at line 3767 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a28d316d115be97fa510e349537535baf">3767</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a28d316d115be97fa510e349537535baf">getNextChar</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;expr,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> *rest,uint32_t &amp;pos)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3768</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3769</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("getNextChar(%s,%s,%d)\n",qPrint(expr),rest ? rest-&gt;data() : 0,pos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3770</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pos&lt;expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3771</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3772</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("  expr()='%c'\n",expr.at(pos));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3773</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(pos++);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3774</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3775</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rest &amp;&amp; !rest-&gt;<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3776</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3777</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> cc=rest-&gt;<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3778</span><span class="doxyLineContent"><span class="doxyHighlight">    *rest=rest-&gt;<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(rest-&gt;<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3779</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("  rest='%c'\n",cc);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3780</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> cc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3781</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3782</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3783</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3784</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> cc=yyinput(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3785</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("  yyinput()='%c' %d\n",cc,EOF);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3786</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> cc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3787</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3788</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">QCString::right</a>.</p>


<p>Referenced by <a href="#a4a295f0fcb46dce77d4ff897094e7914">addSeparatorsIfNeeded</a>, <a href="#a956c6709f23acd037aa021578b5b5472">addTillEndOfString</a>, <a href="#af18da14aec7b354ada7376e24ca5e6ec">replaceFunctionMacro</a> and <a href="#af8c379a1956b4f1623587160df8a0584">skipCommentMacroName</a>.</p>

</div>
</div>

### getNextId() {#a4a9b5774d3b3547b5143e86594853498}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int getNextId (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; expr, int p, int * l)</td>
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




<p>returns the next identifier in string <em>expr</em> by starting at position <em>p</em>. The position of the identifier is returned (or -1 if nothing is found) and <em>l</em> is its length. Any quoted strings are skipping during the search.</p>


<p>Definition at line 2825 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4a9b5774d3b3547b5143e86594853498">2825</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a4a9b5774d3b3547b5143e86594853498">getNextId</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;expr,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> p,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> *l)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2826</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2827</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> n;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2828</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (p&lt;(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2829</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2830</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c=expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(p++);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2831</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isdigit(c)) </span><span class="doxyHighlightComment">// skip number</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2832</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2833</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (p&lt;(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() &amp;&amp; <a href="/web-doxygen/docs/api/files/src/util-h/#ae320c88a8522836f00095d566529046f">isId</a>(expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(p))) p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2834</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2835</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isalpha(c) || c==</span><span class="doxyHighlightCharLiteral">'_'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// read id</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2836</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2837</span><span class="doxyLineContent"><span class="doxyHighlight">      n=p-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2838</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (p&lt;(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() &amp;&amp; <a href="/web-doxygen/docs/api/files/src/util-h/#ae320c88a8522836f00095d566529046f">isId</a>(expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(p))) p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2839</span><span class="doxyLineContent"><span class="doxyHighlight">      *l=p-n;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2840</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> n;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2841</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2842</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// skip string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2843</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2844</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> ppc=0,pc=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2845</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (p&lt;(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()) c=expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2846</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (p&lt;(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() &amp;&amp; (c!=</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight"> || (pc==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight"> &amp;&amp; ppc!=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2847</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// continue as long as no " is found, but ignoring \", but not \\"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2848</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2849</span><span class="doxyLineContent"><span class="doxyHighlight">        ppc=pc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2850</span><span class="doxyLineContent"><span class="doxyHighlight">        pc=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2851</span><span class="doxyLineContent"><span class="doxyHighlight">        c=expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2852</span><span class="doxyLineContent"><span class="doxyHighlight">        p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2853</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2854</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (p&lt;(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()) ++p; </span><span class="doxyHighlightComment">// skip closing quote</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2855</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2856</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// skip C Comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2857</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2858</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("Found C comment at p=%d\n",p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2859</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> pc=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2860</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (p&lt;(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2861</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2862</span><span class="doxyLineContent"><span class="doxyHighlight">        c=expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2863</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">)  </span><span class="doxyHighlightComment">// Start of C comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2864</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2865</span><span class="doxyLineContent"><span class="doxyHighlight">          p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2866</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (p&lt;(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() &amp;&amp; !(pc==</span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight"> &amp;&amp; c==</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2867</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2868</span><span class="doxyLineContent"><span class="doxyHighlight">            pc=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2869</span><span class="doxyLineContent"><span class="doxyHighlight">            c=expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(p++);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2870</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2871</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2872</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2873</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("Found end of C comment at p=%d\n",p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2874</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2875</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2876</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2877</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/files/src/util-h/#ae320c88a8522836f00095d566529046f">isId</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>.</p>


<p>Referenced by <a href="#a1bc8b7f200b9267b0c7b842ecd1f25b0">expandExpression</a>.</p>

</div>
</div>

### incrLevel() {#a2afcdad2a81b0416c9b3fb843e631222}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void incrLevel (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 2171 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2afcdad2a81b0416c9b3fb843e631222">2171</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2afcdad2a81b0416c9b3fb843e631222">incrLevel</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2172</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2173</span><span class="doxyLineContent"><span class="doxyHighlight">  YY_EXTRA_TYPE state = preYYget_extra(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2174</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;levelGuard.push(</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2175</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("%s line %d: incrLevel %d\n",qPrint(yyextra-&gt;fileName),yyextra-&gt;yyLineNr,yyextra-&gt;levelGuard.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2176</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### initPredefined() {#a35e7ee6baadfec49f7e85a2cf14d5deb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void initPredefined (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName)</td>
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



<p>Definition at line 3866 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a35e7ee6baadfec49f7e85a2cf14d5deb">3866</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a35e7ee6baadfec49f7e85a2cf14d5deb">initPredefined</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3867</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3868</span><span class="doxyLineContent"><span class="doxyHighlight">  YY_EXTRA_TYPE state = preYYget_extra(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3869</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3870</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// add predefined macros</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3871</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> &amp;predefList = <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>(PREDEFINED);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3872</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ds : predefList)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3873</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3874</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i_equals=ds.find(</span><span class="doxyHighlightCharLiteral">'='</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3875</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i_obrace=ds.find(</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3876</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i_cbrace=ds.find(</span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3877</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> nonRecursive = i_equals!=std::string::npos &amp;&amp; i_equals&gt;0 &amp;&amp; ds[i_equals-1]==</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3878</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3879</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((i_obrace==0) || (i_equals==0) || (i_equals==1 &amp;&amp; ds[i_equals-1]==</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3880</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3881</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// no define name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3882</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3883</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3884</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i_obrace&lt;i_equals &amp;&amp; i_cbrace&lt;i_equals &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3885</span><span class="doxyLineContent"><span class="doxyHighlight">        i_obrace!=std::string::npos &amp;&amp; i_cbrace!=std::string::npos &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3886</span><span class="doxyLineContent"><span class="doxyHighlight">        i_obrace&lt;i_cbrace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3887</span><span class="doxyLineContent"><span class="doxyHighlight">       ) </span><span class="doxyHighlightComment">// predefined function macro definition</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3888</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3889</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> reId(R</span><span class="doxyHighlightStringLiteral">"(\a\w*)");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3890</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">      std::map&lt;std::string,int&gt; argMap;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3891</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">      std::string args  = ds.substr(i_obrace+1,i_cbrace-i_obrace-1); </span><span class="doxyHighlightComment">// part between ( and )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3892</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">   hasVarArgs = args.find(</span><span class="doxyHighlightStringLiteral">"..."</span><span class="doxyHighlight">)!=std::string::npos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3893</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("predefined function macro '%s'\n",ds.c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3894</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> count = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3895</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/reg/iterator">reg::Iterator</a> arg_it(args,reId,0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3896</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/reg/iterator">reg::Iterator</a> arg_end;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3897</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// gather the formal arguments in a dictionary</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3898</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (; arg_it!=arg_end; ++arg_it)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3899</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3900</span><span class="doxyLineContent"><span class="doxyHighlight">        argMap.emplace(arg_it-&gt;<a href="/web-doxygen/docs/api/classes/reg/match/#a97649b62cb59c9a30ce309559ad0f818">str</a>(),count++);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3901</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3902</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hasVarArgs) </span><span class="doxyHighlightComment">// add the variable argument if present</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3903</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3904</span><span class="doxyLineContent"><span class="doxyHighlight">        argMap.emplace(</span><span class="doxyHighlightStringLiteral">"__VA_ARGS__"</span><span class="doxyHighlight">,count++);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3905</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3906</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3907</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// strip definition part</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3908</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string definition;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3909</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string in=ds.substr(i_equals+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3910</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/reg/iterator">reg::Iterator</a> re_it(in,reId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3911</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/reg/iterator">reg::Iterator</a> re_end;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3912</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3913</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// substitute all occurrences of formal arguments by their</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3914</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// corresponding markers</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3915</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (; re_it!=re_end; ++re_it)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3916</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3917</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;match = *re_it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3918</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pi = match.position();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3919</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> l  = match.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3920</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pi&gt;i) definition+=in.substr(i,pi-i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3921</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3922</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = argMap.find(match.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3923</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=argMap.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3924</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3925</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> argIndex = it-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3926</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> marker;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3927</span><span class="doxyLineContent"><span class="doxyHighlight">          marker.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">" @%d "</span><span class="doxyHighlight">,argIndex);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3928</span><span class="doxyLineContent"><span class="doxyHighlight">          definition+=marker.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3929</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3930</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3931</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3932</span><span class="doxyLineContent"><span class="doxyHighlight">          definition+=match.str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3933</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3934</span><span class="doxyLineContent"><span class="doxyHighlight">        i=pi+l;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3935</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3936</span><span class="doxyLineContent"><span class="doxyHighlight">      definition+=in.substr(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3937</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3938</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// add define definition to the dictionary of defines for this file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3939</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string dname = ds.substr(0,i_obrace);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3940</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!dname.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3941</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3942</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/define">Define</a> def;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3943</span><span class="doxyLineContent"><span class="doxyHighlight">        def.<a href="/web-doxygen/docs/api/classes/define/#a2ab61e312bcf057292789daa0de8bf78">name</a>         = dname;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3944</span><span class="doxyLineContent"><span class="doxyHighlight">        def.<a href="/web-doxygen/docs/api/classes/define/#ac76e113d9f4c5b64553022777f686093">definition</a>   = definition;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3945</span><span class="doxyLineContent"><span class="doxyHighlight">        def.<a href="/web-doxygen/docs/api/classes/define/#ad3306a44c59125a65fbf9559abe97930">nargs</a>        = count;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3946</span><span class="doxyLineContent"><span class="doxyHighlight">        def.<a href="/web-doxygen/docs/api/classes/define/#a856ae02f323f7e3f95fee4101da3904b">isPredefined</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3947</span><span class="doxyLineContent"><span class="doxyHighlight">        def.<a href="/web-doxygen/docs/api/classes/define/#a673dcd69701965f0f62c73ce14dc6665">nonRecursive</a> = nonRecursive;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3948</span><span class="doxyLineContent"><span class="doxyHighlight">        def.<a href="/web-doxygen/docs/api/classes/define/#a3f350ee951cde6b1955612af5be6a6d5">fileDef</a>      = state-&gt;yyFileDef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3949</span><span class="doxyLineContent"><span class="doxyHighlight">        def.<a href="/web-doxygen/docs/api/classes/define/#a2403c7fc667a4a5fd74c8a78560030cc">fileName</a>     = fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3950</span><span class="doxyLineContent"><span class="doxyHighlight">        def.<a href="/web-doxygen/docs/api/classes/define/#a1802523098fdd274fd15cd0494ad26d1">varArgs</a>      = hasVarArgs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3951</span><span class="doxyLineContent"><span class="doxyHighlight">        state-&gt;contextDefines.emplace(def.<a href="/web-doxygen/docs/api/classes/define/#a2ab61e312bcf057292789daa0de8bf78">name</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),def);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3952</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3953</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("#define '%s' '%s' #nargs=%d hasVarArgs=%d\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3954</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//  qPrint(def.name),qPrint(def.definition),def.nargs,def.varArgs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3955</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3956</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3957</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ds.empty()) </span><span class="doxyHighlightComment">// predefined non-function macro definition</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3958</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3959</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("predefined normal macro '%s'\n",ds.c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3960</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/define">Define</a> def;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3961</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i_equals==std::string::npos) </span><span class="doxyHighlightComment">// simple define without argument</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3962</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3963</span><span class="doxyLineContent"><span class="doxyHighlight">        def.<a href="/web-doxygen/docs/api/classes/define/#a2ab61e312bcf057292789daa0de8bf78">name</a> = ds;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3964</span><span class="doxyLineContent"><span class="doxyHighlight">        def.<a href="/web-doxygen/docs/api/classes/define/#ac76e113d9f4c5b64553022777f686093">definition</a> = </span><span class="doxyHighlightStringLiteral">"1"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// substitute occurrences by 1 (true)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3965</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3966</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// simple define with argument</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3967</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3968</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> ine=</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(i_equals) - (nonRecursive ? 1 : 0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3969</span><span class="doxyLineContent"><span class="doxyHighlight">        def.<a href="/web-doxygen/docs/api/classes/define/#a2ab61e312bcf057292789daa0de8bf78">name</a> = ds.substr(0,ine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3970</span><span class="doxyLineContent"><span class="doxyHighlight">        def.<a href="/web-doxygen/docs/api/classes/define/#ac76e113d9f4c5b64553022777f686093">definition</a> = ds.substr(i_equals+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3971</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3972</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!def.<a href="/web-doxygen/docs/api/classes/define/#a2ab61e312bcf057292789daa0de8bf78">name</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3973</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3974</span><span class="doxyLineContent"><span class="doxyHighlight">        def.<a href="/web-doxygen/docs/api/classes/define/#ad3306a44c59125a65fbf9559abe97930">nargs</a> = -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3975</span><span class="doxyLineContent"><span class="doxyHighlight">        def.<a href="/web-doxygen/docs/api/classes/define/#a856ae02f323f7e3f95fee4101da3904b">isPredefined</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3976</span><span class="doxyLineContent"><span class="doxyHighlight">        def.<a href="/web-doxygen/docs/api/classes/define/#a673dcd69701965f0f62c73ce14dc6665">nonRecursive</a> = nonRecursive;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3977</span><span class="doxyLineContent"><span class="doxyHighlight">        def.<a href="/web-doxygen/docs/api/classes/define/#a3f350ee951cde6b1955612af5be6a6d5">fileDef</a>      = state-&gt;yyFileDef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3978</span><span class="doxyLineContent"><span class="doxyHighlight">        def.<a href="/web-doxygen/docs/api/classes/define/#a2403c7fc667a4a5fd74c8a78560030cc">fileName</a>     = fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3979</span><span class="doxyLineContent"><span class="doxyHighlight">        state-&gt;contextDefines.emplace(def.<a href="/web-doxygen/docs/api/classes/define/#a2ab61e312bcf057292789daa0de8bf78">name</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),def);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3980</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3981</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3982</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3983</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>, <a href="/web-doxygen/docs/api/classes/define/#ac76e113d9f4c5b64553022777f686093">Define::definition</a>, <a href="/web-doxygen/docs/api/classes/define/#a3f350ee951cde6b1955612af5be6a6d5">Define::fileDef</a>, <a href="/web-doxygen/docs/api/classes/define/#a2403c7fc667a4a5fd74c8a78560030cc">Define::fileName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/define/#a856ae02f323f7e3f95fee4101da3904b">Define::isPredefined</a>, <a href="/web-doxygen/docs/api/classes/define/#a2ab61e312bcf057292789daa0de8bf78">Define::name</a>, <a href="/web-doxygen/docs/api/classes/define/#ad3306a44c59125a65fbf9559abe97930">Define::nargs</a>, <a href="/web-doxygen/docs/api/classes/define/#a673dcd69701965f0f62c73ce14dc6665">Define::nonRecursive</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">QCString::sprintf</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/reg/match/#a97649b62cb59c9a30ce309559ad0f818">reg::Match::str</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/classes/define/#a1802523098fdd274fd15cd0494ad26d1">Define::varArgs</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/preprocessor/#ab3f6062c1f94727e3d51963720d13417">Preprocessor::processFile</a>.</p>

</div>
</div>

### isDefined() {#a37deceebb857c5178f2ae90e8da172f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Define * isDefined (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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

<p>Returns a reference to a <a href="/web-doxygen/docs/api/classes/define">Define</a> object given its name or 0 if the <a href="/web-doxygen/docs/api/classes/define">Define</a> does not exist.</p>

<p>Definition at line 3837 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a37deceebb857c5178f2ae90e8da172f2">3837</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/define">Define</a> *<a href="#a37deceebb857c5178f2ae90e8da172f2">isDefined</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3838</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3839</span><span class="doxyLineContent"><span class="doxyHighlight">  YY_EXTRA_TYPE state = preYYget_extra(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3840</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3841</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> undef = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3842</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> findDefine = [&amp;undef,&amp;name](<a href="#a0dd482007e6d1df4a67172cda7af1a61">DefineMap</a> &amp;map)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3843</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3844</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/define">Define</a> *d=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3845</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = map.find(name.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3846</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=map.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3847</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3848</span><span class="doxyLineContent"><span class="doxyHighlight">      d = &amp;it-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3849</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d-&gt;<a href="/web-doxygen/docs/api/classes/define/#afde97e0a7fadda62d088b18acc7a5a0e">undef</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3850</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3851</span><span class="doxyLineContent"><span class="doxyHighlight">        undef=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3852</span><span class="doxyLineContent"><span class="doxyHighlight">        d=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3853</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3854</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3855</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> d;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3856</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3857</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3858</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/define">Define</a> *def = findDefine(state-&gt;localDefines);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3859</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (def==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> &amp;&amp; !undef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3860</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3861</span><span class="doxyLineContent"><span class="doxyHighlight">    def = findDefine(state-&gt;contextDefines);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3862</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3863</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> def;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3864</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/classes/define/#afde97e0a7fadda62d088b18acc7a5a0e">Define::undef</a>.</p>


<p>Referenced by <a href="#a1bc8b7f200b9267b0c7b842ecd1f25b0">expandExpression</a>.</p>

</div>
</div>

### otherCaseDone() {#abec6a57b1258c5230a0dde8cf6e2c91f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool otherCaseDone (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
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



<p>Definition at line 2192 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abec6a57b1258c5230a0dde8cf6e2c91f">2192</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#abec6a57b1258c5230a0dde8cf6e2c91f">otherCaseDone</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2193</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2194</span><span class="doxyLineContent"><span class="doxyHighlight">  YY_EXTRA_TYPE state = preYYget_extra(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2195</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (state-&gt;levelGuard.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2196</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2197</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(state-&gt;fileName,state-&gt;yyLineNr,</span><span class="doxyHighlightStringLiteral">"Found an #else without a preceding #if."</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2198</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2199</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2200</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2201</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2202</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> state-&gt;levelGuard.top();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2203</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2204</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.</p>

</div>
</div>

### outputArray() {#ac2c518bb48991ade6e459a3e203e6a86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void outputArray (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const char * a, yy_size_t len)</td>
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



<p>Definition at line 3463 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac2c518bb48991ade6e459a3e203e6a86">3463</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *a,yy_size_t len)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3464</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3465</span><span class="doxyLineContent"><span class="doxyHighlight">  YY_EXTRA_TYPE state = preYYget_extra(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3466</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (state-&gt;includeStack.empty() || state-&gt;curlyCount&gt;0) (*state-&gt;outputBuf)+=std::string_view(a,len);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3467</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### outputChar() {#a4864d83d173c2deef235ab17f9c6a529}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void outputChar (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, char c)</td>
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



<p>Definition at line 3457 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4864d83d173c2deef235ab17f9c6a529">3457</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3458</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3459</span><span class="doxyLineContent"><span class="doxyHighlight">  YY_EXTRA_TYPE state = preYYget_extra(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3460</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (state-&gt;includeStack.empty() || state-&gt;curlyCount&gt;0) (*state-&gt;outputBuf)+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3461</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="#ae596fa0b1fbc60f9128146cc90630101">outputSpace</a> and <a href="#a34739dd6d965f4701c9b7611d7c2cf9a">outputSpaces</a>.</p>

</div>
</div>

### outputSpace() {#ae596fa0b1fbc60f9128146cc90630101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void outputSpace (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, char c)</td>
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



<p>Definition at line 3475 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae596fa0b1fbc60f9128146cc90630101">3475</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae596fa0b1fbc60f9128146cc90630101">outputSpace</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3476</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3477</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">) <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3478</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3479</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>.</p>

</div>
</div>

### outputSpaces() {#a34739dd6d965f4701c9b7611d7c2cf9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void outputSpaces (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, char * s)</td>
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



<p>Definition at line 3481 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a34739dd6d965f4701c9b7611d7c2cf9a">3481</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a34739dd6d965f4701c9b7611d7c2cf9a">outputSpaces</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3482</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3483</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3484</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3485</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3486</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3487</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">) <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3488</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3489</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3490</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>.</p>

</div>
</div>

### outputString() {#a3ac956f197291fa939c052de93bd3d16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void outputString (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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



<p>Definition at line 3469 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3ac956f197291fa939c052de93bd3d16">3469</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3ac956f197291fa939c052de93bd3d16">outputString</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;a)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3470</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3471</span><span class="doxyLineContent"><span class="doxyHighlight">  YY_EXTRA_TYPE state = preYYget_extra(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3472</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (state-&gt;includeStack.empty() || state-&gt;curlyCount&gt;0) (*state-&gt;outputBuf)+=a.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3473</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>


<p>Referenced by <a href="#a9af0795be28dcf4551e57a2a3650a552">readIncludeFile</a>.</p>

</div>
</div>

### processConcatOperators() {#ad8262966752d5069cd91cf2ecec43afd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void processConcatOperators (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; expr)</td>
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




<p>Execute all ## operators in expr. If the macro name before or after the operator contains a no-rescan marker (-) then this is removed (before the concatenated macro name may be expanded again.</p>


<p>Definition at line 2472 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad8262966752d5069cd91cf2ecec43afd">2472</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad8262966752d5069cd91cf2ecec43afd">processConcatOperators</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;expr)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2473</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2474</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2475</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("processConcatOperators: in='%s'\n",qPrint(expr));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2476</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string e = expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2477</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> r(R</span><span class="doxyHighlightStringLiteral">"(\s*##\s*)");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2478</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">  <a href="/web-doxygen/docs/api/classes/reg/iterator">reg::Iterator</a> <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2479</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2480</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2481</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (;;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2482</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2483</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/reg/iterator">reg::Iterator</a> it(e,r,i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2484</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2485</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2486</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;match = *it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2487</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> n = match.position();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2488</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> l = match.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2489</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("Match: '%s'\n",qPrint(expr.mid(i)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2490</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (n+l+1&lt;e.length() &amp;&amp; e[</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(n+l)]==</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight"> &amp;&amp; expr[</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(n+l+1)]==</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2491</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2492</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// remove no-rescan marker after ID</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2493</span><span class="doxyLineContent"><span class="doxyHighlight">        l+=2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2494</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2495</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("found '%s'\n",qPrint(expr.mid(n,l)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2496</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// remove the ## operator and the surrounding whitespace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2497</span><span class="doxyLineContent"><span class="doxyHighlight">      e=e.substr(0,n)+e.substr(n+l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2498</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> k=</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(n)-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2499</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (k&gt;=0 &amp;&amp; <a href="/web-doxygen/docs/api/files/src/util-h/#ae320c88a8522836f00095d566529046f">isId</a>(e[k])) k--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2500</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (k&gt;0 &amp;&amp; e[k]==</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight"> &amp;&amp; e[k-1]==</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2501</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2502</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// remove no-rescan marker before ID</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2503</span><span class="doxyLineContent"><span class="doxyHighlight">        e=e.substr(0,k-1)+e.substr(k+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2504</span><span class="doxyLineContent"><span class="doxyHighlight">        n-=2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2505</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2506</span><span class="doxyLineContent"><span class="doxyHighlight">      i=n;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2507</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2508</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2509</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2510</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2511</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2512</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2513</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2514</span><span class="doxyLineContent"><span class="doxyHighlight">  expr = e;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2515</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2516</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("processConcatOperators: out='%s'\n",qPrint(expr));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2517</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/files/src/util-h/#ae320c88a8522836f00095d566529046f">isId</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>


<p>Referenced by <a href="#a1bc8b7f200b9267b0c7b842ecd1f25b0">expandExpression</a>.</p>

</div>
</div>

### processUntilMatchingTerminator() {#ad5a00bad9b10b8fe9542cba69f171028}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * processUntilMatchingTerminator (const char * inputStr, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; result)</td>
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

<p>Process string or character literal.</p>


<p><em>inputStr</em> should point to the start of a string or character literal. the routine will return a pointer to just after the end of the literal the character making up the literal will be added to <em>result</em>.</p>


<p>Definition at line 3058 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad5a00bad9b10b8fe9542cba69f171028">3058</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#ad5a00bad9b10b8fe9542cba69f171028">processUntilMatchingTerminator</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *inputStr,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;result)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3059</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3060</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (inputStr==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> inputStr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3061</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a> = *inputStr; </span><span class="doxyHighlightComment">// capture start character of the literal</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3062</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>!=</span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight"> &amp;&amp; <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>!=</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> inputStr; </span><span class="doxyHighlightComment">// not a valid literal</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3063</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c=<a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3064</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// output start character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3065</span><span class="doxyLineContent"><span class="doxyHighlight">  result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3066</span><span class="doxyLineContent"><span class="doxyHighlight">  inputStr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3067</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*inputStr)) </span><span class="doxyHighlightComment">// while inside the literal</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3068</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3069</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==<a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>) </span><span class="doxyHighlightComment">// found end marker of the literal</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3070</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3071</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// output end character and stop</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3072</span><span class="doxyLineContent"><span class="doxyHighlight">      result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3073</span><span class="doxyLineContent"><span class="doxyHighlight">      inputStr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3074</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3075</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3076</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// escaped character, process next character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3077</span><span class="doxyLineContent"><span class="doxyHighlight">                      </span><span class="doxyHighlightComment">// as well without checking for end marker.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3078</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3079</span><span class="doxyLineContent"><span class="doxyHighlight">      result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3080</span><span class="doxyLineContent"><span class="doxyHighlight">      inputStr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3081</span><span class="doxyLineContent"><span class="doxyHighlight">      c=*inputStr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3082</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==0) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// unexpected end of string after escape character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3083</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3084</span><span class="doxyLineContent"><span class="doxyHighlight">    result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3085</span><span class="doxyLineContent"><span class="doxyHighlight">    inputStr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3086</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3087</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> inputStr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3088</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>.</p>


<p>Referenced by <a href="#a2bbb2d9191d513b9cbfb864ee2043a3c">removeIdsAndMarkers</a> and <a href="#ae5ee30cbed9991fc9961669602045e88">removeMarkers</a>.</p>

</div>
</div>

### readIncludeFile() {#a9af0795be28dcf4551e57a2a3650a552}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void readIncludeFile (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; inc)</td>
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



<p>Definition at line 3538 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9af0795be28dcf4551e57a2a3650a552">3538</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#acb71ba8a95e7beb78c1e3a685d8696ed">readIncludeFile</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;inc)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3539</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3540</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"inc={}"</span><span class="doxyHighlight">,inc);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3541</span><span class="doxyLineContent"><span class="doxyHighlight">  YY_EXTRA_TYPE state = preYYget_extra(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3542</span><span class="doxyLineContent"><span class="doxyHighlight">  uint32_t i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3543</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3544</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// find the start of the include file name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3545</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;inc.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3546</span><span class="doxyLineContent"><span class="doxyHighlight">         (inc.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(i)==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || inc.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(i)==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight"> || inc.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(i)==</span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3547</span><span class="doxyLineContent"><span class="doxyHighlight">        ) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3548</span><span class="doxyLineContent"><span class="doxyHighlight">  uint32_t s=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3549</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3550</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// was it a local include?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3551</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> localInclude = s&gt;0 &amp;&amp; inc.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(s-1)==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3552</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3553</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// find the end of the include file name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3554</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;inc.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() &amp;&amp; inc.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(i)!=</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight"> &amp;&amp; inc.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(i)!=</span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3555</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3556</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s&lt;inc.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() &amp;&amp; i&gt;s) </span><span class="doxyHighlightComment">// valid include file name found</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3557</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3558</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// extract include path+name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3559</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> incFileName=inc.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(s,i-s).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3560</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (incFileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">endsWith</a>(</span><span class="doxyHighlightStringLiteral">".exe"</span><span class="doxyHighlight">) || incFileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">endsWith</a>(</span><span class="doxyHighlightStringLiteral">".dll"</span><span class="doxyHighlight">) || incFileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">endsWith</a>(</span><span class="doxyHighlightStringLiteral">".tlb"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3561</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3562</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// skip imported binary files (e.g. M$ type libraries)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3563</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3564</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3565</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3566</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> oldFileName = state-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3567</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *oldFileDef  = state-&gt;yyFileDef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3568</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> oldLineNr        = state-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3569</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("Searching for '%s'\n",qPrint(incFileName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3570</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3571</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> absIncFileName = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a97fa1635ca734b061444c678b7525475">determineAbsoluteIncludeName</a>(state-&gt;fileName,incFileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3572</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3573</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// findFile will overwrite state-&gt;yyFileDef if found</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3574</span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;FileState&gt; fs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3575</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> alreadyProcessed = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3576</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("calling findFile(%s)\n",qPrint(incFileName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3577</span><span class="doxyLineContent"><span class="doxyHighlight">    fs=<a href="/web-doxygen/docs/api/files/src/configimpl-l/#a6232960902cd961ee248851d0f5a189d">findFile</a>(yyscanner,absIncFileName,localInclude,alreadyProcessed); </span><span class="doxyHighlightComment">// see if the absolute include file can be found</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3578</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3579</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3580</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3581</span><span class="doxyLineContent"><span class="doxyHighlight">        std::lock_guard&lt;std::mutex&gt; lock(<a href="#a41d40eee862471579482f58a442f157d">g_globalDefineMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3582</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a888d117646a1150fd6672a7cc9c0a81d">g_defineManager</a>.addInclude(oldFileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),absIncFileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3583</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3584</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3585</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("Found include file!\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3586</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daec63880706f2286cd7ca9057bf407e2f">Debug::Preprocessor</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3587</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3588</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (i=0;i&lt;state-&gt;includeStack.size();i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3589</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3590</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daec63880706f2286cd7ca9057bf407e2f">Debug::Preprocessor</a>,0,</span><span class="doxyHighlightStringLiteral">"  "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3591</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3592</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daec63880706f2286cd7ca9057bf407e2f">Debug::Preprocessor</a>,0,</span><span class="doxyHighlightStringLiteral">"#include {}: parsing...\n"</span><span class="doxyHighlight">,incFileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3593</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3594</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3595</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (state-&gt;includeStack.empty() &amp;&amp; oldFileDef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3596</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3597</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/structs/preincludeinfo">PreIncludeInfo</a> *ii = state-&gt;includeRelations.find(absIncFileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3598</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ii==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3599</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3600</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ambig = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3601</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *incFd = <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>,absIncFileName,ambig);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3602</span><span class="doxyLineContent"><span class="doxyHighlight">          state-&gt;includeRelations.add(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3603</span><span class="doxyLineContent"><span class="doxyHighlight">              absIncFileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3604</span><span class="doxyLineContent"><span class="doxyHighlight">              oldFileDef,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3605</span><span class="doxyLineContent"><span class="doxyHighlight">              ambig ? </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> : incFd,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3606</span><span class="doxyLineContent"><span class="doxyHighlight">              incFileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3607</span><span class="doxyLineContent"><span class="doxyHighlight">              localInclude,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3608</span><span class="doxyLineContent"><span class="doxyHighlight">              state-&gt;isImported</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3609</span><span class="doxyLineContent"><span class="doxyHighlight">              );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3610</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3611</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3612</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3613</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t * yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3614</span><span class="doxyLineContent"><span class="doxyHighlight">      fs-&gt;bufState = YY_CURRENT_BUFFER;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3615</span><span class="doxyLineContent"><span class="doxyHighlight">      fs-&gt;lineNr   = oldLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3616</span><span class="doxyLineContent"><span class="doxyHighlight">      fs-&gt;fileName = oldFileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3617</span><span class="doxyLineContent"><span class="doxyHighlight">      fs-&gt;curlyCount = state-&gt;curlyCount;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3618</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//state-&gt;curlyCount = 0; // don't reset counter, see issue #10997</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3619</span><span class="doxyLineContent"><span class="doxyHighlight">      fs-&gt;lexRulesPart = state-&gt;lexRulesPart;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3620</span><span class="doxyLineContent"><span class="doxyHighlight">      state-&gt;lexRulesPart = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3621</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// push the state on the stack</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3622</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/structs/filestate">FileState</a> *fs_ptr = fs.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3623</span><span class="doxyLineContent"><span class="doxyHighlight">      state-&gt;includeStack.push_back(std::move(fs));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3624</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// set the scanner to the include file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3625</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3626</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// Deal with file changes due to</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3627</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// #include's within { .. } blocks</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3628</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> lineStr(state-&gt;fileName.length()+20, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3629</span><span class="doxyLineContent"><span class="doxyHighlight">      lineStr.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"# 1 \"%s\" 1\n"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(state-&gt;fileName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3630</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a3ac956f197291fa939c052de93bd3d16">outputString</a>(yyscanner,lineStr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3631</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3632</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"Switching to include file {}"</span><span class="doxyHighlight">,incFileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3633</span><span class="doxyLineContent"><span class="doxyHighlight">      state-&gt;expectGuard=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3634</span><span class="doxyLineContent"><span class="doxyHighlight">      state-&gt;inputBuf   = &amp;fs_ptr-&gt;<a href="/web-doxygen/docs/api/structs/filestate/#a0efa7eaf2b8784e12360c89a4de3d1f5">fileBuf</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3635</span><span class="doxyLineContent"><span class="doxyHighlight">      state-&gt;inputBufPos=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3636</span><span class="doxyLineContent"><span class="doxyHighlight">      yy_switch_to_buffer(yy_create_buffer(0, <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#ae7e51116e747d3390e7a6cfc6532834c">YY_BUF_SIZE</a>, yyscanner),yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3637</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3638</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3639</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3640</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (alreadyProcessed) </span><span class="doxyHighlightComment">// if this header was already process we can just copy the stored macros</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3641</span><span class="doxyLineContent"><span class="doxyHighlight">                           </span><span class="doxyHighlightComment">// in the local context</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3642</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3643</span><span class="doxyLineContent"><span class="doxyHighlight">        std::lock_guard&lt;std::mutex&gt; lock(<a href="#a41d40eee862471579482f58a442f157d">g_globalDefineMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3644</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a888d117646a1150fd6672a7cc9c0a81d">g_defineManager</a>.addInclude(state-&gt;fileName.str(),absIncFileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3645</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a888d117646a1150fd6672a7cc9c0a81d">g_defineManager</a>.retrieve(absIncFileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),state-&gt;contextDefines);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3646</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3647</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3648</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (state-&gt;includeStack.empty() &amp;&amp; oldFileDef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3649</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3650</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/structs/preincludeinfo">PreIncludeInfo</a> *ii = state-&gt;includeRelations.find(absIncFileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3651</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ii==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3652</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3653</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ambig = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3654</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *incFd = <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>,absIncFileName,ambig);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3655</span><span class="doxyLineContent"><span class="doxyHighlight">          ii = state-&gt;includeRelations.add(absIncFileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3656</span><span class="doxyLineContent"><span class="doxyHighlight">              oldFileDef,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3657</span><span class="doxyLineContent"><span class="doxyHighlight">              ambig ? </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> : incFd,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3658</span><span class="doxyLineContent"><span class="doxyHighlight">              incFileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3659</span><span class="doxyLineContent"><span class="doxyHighlight">              localInclude,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3660</span><span class="doxyLineContent"><span class="doxyHighlight">              state-&gt;isImported</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3661</span><span class="doxyLineContent"><span class="doxyHighlight">              );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3662</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3663</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3664</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3665</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daec63880706f2286cd7ca9057bf407e2f">Debug::Preprocessor</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3666</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3667</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (i=0;i&lt;state-&gt;includeStack.size();i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3668</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3669</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daec63880706f2286cd7ca9057bf407e2f">Debug::Preprocessor</a>,0,</span><span class="doxyHighlightStringLiteral">"  "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3670</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3671</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (alreadyProcessed)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3672</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3673</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daec63880706f2286cd7ca9057bf407e2f">Debug::Preprocessor</a>,0,</span><span class="doxyHighlightStringLiteral">"#include {}: already processed! skipping...\n"</span><span class="doxyHighlight">,incFileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3674</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3675</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3676</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3677</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daec63880706f2286cd7ca9057bf407e2f">Debug::Preprocessor</a>,0,</span><span class="doxyHighlightStringLiteral">"#include {}: not found! skipping...\n"</span><span class="doxyHighlight">,incFileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3678</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3679</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("error: include file %s not found\n",yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3680</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3681</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (localInclude &amp;&amp; !state-&gt;includeStack.empty() &amp;&amp; state-&gt;curlyCount&gt;0 &amp;&amp; !alreadyProcessed) </span><span class="doxyHighlightComment">// failed to find #include inside { ... }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3682</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3683</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(state-&gt;fileName,state-&gt;yyLineNr,</span><span class="doxyHighlightStringLiteral">"include file {} not found, perhaps you forgot to add its directory to INCLUDE_PATH?"</span><span class="doxyHighlight">,incFileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3684</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3685</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3686</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3687</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a97fa1635ca734b061444c678b7525475">determineAbsoluteIncludeName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">QCString::endsWith</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/structs/filestate/#a0efa7eaf2b8784e12360c89a4de3d1f5">FileState::fileBuf</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a6232960902cd961ee248851d0f5a189d">findFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>, <a href="#a888d117646a1150fd6672a7cc9c0a81d">g_defineManager</a>, <a href="#a41d40eee862471579482f58a442f157d">g_globalDefineMutex</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="#a3ac956f197291fa939c052de93bd3d16">outputString</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daec63880706f2286cd7ca9057bf407e2f">Debug::Preprocessor</a>, <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">QCString::sprintf</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a> and <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#ae7e51116e747d3390e7a6cfc6532834c">YY_BUF_SIZE</a>.</p>

</div>
</div>

### removeIdsAndMarkers() {#a2bbb2d9191d513b9cbfb864ee2043a3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString removeIdsAndMarkers (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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




<p>replaces all occurrences of @@ in <em>s</em> by @ and removes all occurrences of @E. All identifiers found are replaced by 0L</p>


<p>Definition at line 3094 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2bbb2d9191d513b9cbfb864ee2043a3c">3094</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a2bbb2d9191d513b9cbfb864ee2043a3c">removeIdsAndMarkers</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3095</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3096</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::vector&lt;std::string&gt; signs = { </span><span class="doxyHighlightStringLiteral">"signed"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"unsigned"</span><span class="doxyHighlight"> };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3097</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">TypeInfo { std::string name; </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size; };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3098</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::vector&lt;TypeInfo&gt; types = {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3099</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"short int"</span><span class="doxyHighlight">,     </span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeywordType">short</span><span class="doxyHighlight"> int)     },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3100</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"long long int"</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeywordType">long</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">long</span><span class="doxyHighlight"> int) },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3101</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"long int"</span><span class="doxyHighlight">,      </span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeywordType">long</span><span class="doxyHighlight"> int)      },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3102</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"long long"</span><span class="doxyHighlight">,     </span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeywordType">long</span><span class="doxyHighlight"> long)     },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3103</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"long double"</span><span class="doxyHighlight">,   </span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeywordType">long</span><span class="doxyHighlight"> double)   },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3104</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"int"</span><span class="doxyHighlight">,           </span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(int)           },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3105</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"short"</span><span class="doxyHighlight">,         </span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(short)         },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3106</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"bool"</span><span class="doxyHighlight">,          </span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(bool)          },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3107</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"long"</span><span class="doxyHighlight">,          </span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(long)          },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3108</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"char"</span><span class="doxyHighlight">,          </span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(char)          },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3109</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"float"</span><span class="doxyHighlight">,         </span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(float)         },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3110</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"double"</span><span class="doxyHighlight">,        </span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(double)        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3111</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3112</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3113</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Check if string p starts with basic types ending with a ')', such as 'signed long)' or ' float )'</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3114</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// and return the pointer just past the ')' and the size of the type as a tuple.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3115</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// If the pattern is not found the tuple (nullptr,0) is returned.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3116</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> process_cast_or_sizeof = [](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p) -&gt; std::pair&lt;const char *,size_t&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3117</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3118</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *q = p;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3119</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*q==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || *q==</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">) q++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3120</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> found=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3121</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = </span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(int); </span><span class="doxyHighlightComment">// '(signed)' or '(unsigned)' is an int type</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3122</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;sgn : signs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3123</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3124</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a19faae287d13ccea75b1d5a0eb110d97">qstrncmp</a>(q,sgn.c_str(),sgn.length())==0) { q+=sgn.length(); found=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3125</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3126</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!found || *q==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || *q==</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight"> || *q==</span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// continue searching</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3127</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3128</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*q==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || *q==</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">) q++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3129</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;t : types)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3130</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3131</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a19faae287d13ccea75b1d5a0eb110d97">qstrncmp</a>(q,t.name.c_str(),t.name.length())==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3132</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3133</span><span class="doxyLineContent"><span class="doxyHighlight">          q += t.name.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3134</span><span class="doxyLineContent"><span class="doxyHighlight">          size = t.size;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3135</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3136</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3137</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3138</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*q==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || *q==</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">) q++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3139</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*q==</span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::make_pair(++q,size);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3140</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3141</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::make_pair(</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3142</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3143</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3144</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("removeIdsAndMarkers(%s)\n",qPrint(s));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3145</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3146</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3147</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inNum=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3148</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3149</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3150</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3151</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3152</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3153</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3154</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// potential cast, ignore it</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3155</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3156</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *q = process_cast_or_sizeof(p+1).first;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3157</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("potential cast:\nin:  %s\nout: %s\n",p,q);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3158</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (q)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3159</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3160</span><span class="doxyLineContent"><span class="doxyHighlight">          p=q;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3161</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3162</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3163</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3164</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'s'</span><span class="doxyHighlight"> &amp;&amp; <a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>(p,</span><span class="doxyHighlightStringLiteral">"sizeof"</span><span class="doxyHighlight">)) </span><span class="doxyHighlightComment">// sizeof(...)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3165</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3166</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *q = p+6;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3167</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*q==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || *q==</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">) q++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3168</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*q==</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3169</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3170</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> r = process_cast_or_sizeof(q+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3171</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//printf("sizeof:\nin:  %s\nout: %zu%s\n--&gt; sizeof=%zu\n",p,r.second,r.first,r.second);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3172</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (r.first)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3173</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3174</span><span class="doxyLineContent"><span class="doxyHighlight">            result+=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">setNum</a>(r.second);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3175</span><span class="doxyLineContent"><span class="doxyHighlight">            p=r.first;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3176</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3177</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3178</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3179</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3180</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3181</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// replace @@ with @ and remove @E</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3182</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3183</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*(p+1)==</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3184</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3185</span><span class="doxyLineContent"><span class="doxyHighlight">          result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3186</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3187</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*(p+1)==</span><span class="doxyHighlightCharLiteral">'E'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3188</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3189</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// skip</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3190</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3191</span><span class="doxyLineContent"><span class="doxyHighlight">        p+=2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3192</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3193</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isdigit(c)) </span><span class="doxyHighlightComment">// number</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3194</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3195</span><span class="doxyLineContent"><span class="doxyHighlight">        result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3196</span><span class="doxyLineContent"><span class="doxyHighlight">        p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3197</span><span class="doxyLineContent"><span class="doxyHighlight">        inNum=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3198</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3199</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// quoted character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3200</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3201</span><span class="doxyLineContent"><span class="doxyHighlight">        p = <a href="#ad5a00bad9b10b8fe9542cba69f171028">processUntilMatchingTerminator</a>(p,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3202</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3203</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'d'</span><span class="doxyHighlight"> &amp;&amp; !inNum) </span><span class="doxyHighlightComment">// identifier starting with a 'd'</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3204</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3205</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>(p,</span><span class="doxyHighlightStringLiteral">"defined "</span><span class="doxyHighlight">) || <a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>(p,</span><span class="doxyHighlightStringLiteral">"defined("</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3206</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightComment">// defined keyword</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3207</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3208</span><span class="doxyLineContent"><span class="doxyHighlight">          p+=7; </span><span class="doxyHighlightComment">// skip defined</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3209</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3210</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3211</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3212</span><span class="doxyLineContent"><span class="doxyHighlight">          result+=</span><span class="doxyHighlightStringLiteral">"0L"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3213</span><span class="doxyLineContent"><span class="doxyHighlight">          p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3214</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p) &amp;&amp; <a href="/web-doxygen/docs/api/files/src/util-h/#ae320c88a8522836f00095d566529046f">isId</a>(c)) p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3215</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3216</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3217</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((isalpha(c) || c==</span><span class="doxyHighlightCharLiteral">'_'</span><span class="doxyHighlight">) &amp;&amp; !inNum) </span><span class="doxyHighlightComment">// replace identifier with 0L</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3218</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3219</span><span class="doxyLineContent"><span class="doxyHighlight">        result+=</span><span class="doxyHighlightStringLiteral">"0L"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3220</span><span class="doxyLineContent"><span class="doxyHighlight">        p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3221</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p) &amp;&amp; <a href="/web-doxygen/docs/api/files/src/util-h/#ae320c88a8522836f00095d566529046f">isId</a>(c)) p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3222</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p) &amp;&amp; isspace((uint8_t)c)) p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3223</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*p==</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// undefined function macro</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3224</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3225</span><span class="doxyLineContent"><span class="doxyHighlight">          p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3226</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> count=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3227</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3228</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3229</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">) count++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3230</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3231</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3232</span><span class="doxyLineContent"><span class="doxyHighlight">              count--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3233</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (count==0) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3234</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3235</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3236</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3237</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> pc=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3238</span><span class="doxyLineContent"><span class="doxyHighlight">              c=*++p;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3239</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// start of C comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3240</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3241</span><span class="doxyLineContent"><span class="doxyHighlight">                </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*p &amp;&amp; !(pc==</span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight"> &amp;&amp; c==</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">)) </span><span class="doxyHighlightComment">// search end of comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3242</span><span class="doxyLineContent"><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3243</span><span class="doxyLineContent"><span class="doxyHighlight">                  pc=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3244</span><span class="doxyLineContent"><span class="doxyHighlight">                  c=*++p;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3245</span><span class="doxyLineContent"><span class="doxyHighlight">                }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3246</span><span class="doxyLineContent"><span class="doxyHighlight">                p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3247</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3248</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3249</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3250</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3251</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3252</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// skip C comments</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3253</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3254</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> pc=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3255</span><span class="doxyLineContent"><span class="doxyHighlight">        c=*++p;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3256</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// start of C comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3257</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3258</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*p &amp;&amp; !(pc==</span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight"> &amp;&amp; c==</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">)) </span><span class="doxyHighlightComment">// search end of comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3259</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3260</span><span class="doxyLineContent"><span class="doxyHighlight">            pc=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3261</span><span class="doxyLineContent"><span class="doxyHighlight">            c=*++p;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3262</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3263</span><span class="doxyLineContent"><span class="doxyHighlight">          p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3264</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3265</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// oops, not comment but division</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3266</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3267</span><span class="doxyLineContent"><span class="doxyHighlight">          result+=pc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3268</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> nextChar;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3269</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3270</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3271</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3272</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3273</span><span class="doxyLineContent"><span class="doxyHighlight">nextChar:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3274</span><span class="doxyLineContent"><span class="doxyHighlight">        result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3275</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> lc=(char)tolower(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3276</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/util-h/#ae320c88a8522836f00095d566529046f">isId</a>(lc) &amp;&amp; lc!=</span><span class="doxyHighlightCharLiteral">'.'</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*&amp;&amp; lc!='-' &amp;&amp; lc!='+'*/</span><span class="doxyHighlight">) inNum=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3277</span><span class="doxyLineContent"><span class="doxyHighlight">        p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3278</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3279</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3280</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3281</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("removeIdsAndMarkers(%s)=%s\n",s,qPrint(result));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3282</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3283</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/files/src/util-h/#ae320c88a8522836f00095d566529046f">isId</a>, <a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>, <a href="#ad5a00bad9b10b8fe9542cba69f171028">processUntilMatchingTerminator</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a19faae287d13ccea75b1d5a0eb110d97">qstrncmp</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">QCString::setNum</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>


<p>Referenced by <a href="#ae3133546e20fd36ac3b7568349ce5285">computeExpression</a>.</p>

</div>
</div>

### removeMarkers() {#ae5ee30cbed9991fc9961669602045e88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString removeMarkers (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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




<p>replaces all occurrences of @ in <em>s</em> by @</p>


<dl class="doxySectionUser">
<dt>assumption:</dt>
<dd><p><em>s</em> only contains pairs of @'s</p></dd>
</dl>


<p>Definition at line 3289 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae5ee30cbed9991fc9961669602045e88">3289</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ae5ee30cbed9991fc9961669602045e88">removeMarkers</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3290</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3291</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3292</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3293</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3294</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3295</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3296</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3297</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3298</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3299</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3300</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3301</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">: </span><span class="doxyHighlightComment">// replace @@ with @</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3302</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3303</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*(p+1)==</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3304</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3305</span><span class="doxyLineContent"><span class="doxyHighlight">              result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3306</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3307</span><span class="doxyLineContent"><span class="doxyHighlight">            p+=2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3308</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3309</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3310</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">: </span><span class="doxyHighlightComment">// skip C comments</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3311</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3312</span><span class="doxyLineContent"><span class="doxyHighlight">            result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3313</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> pc=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3314</span><span class="doxyLineContent"><span class="doxyHighlight">            c=*++p;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3315</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// start of C comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3316</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3317</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*p &amp;&amp; !(pc==</span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight"> &amp;&amp; c==</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">)) </span><span class="doxyHighlightComment">// search end of comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3318</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3319</span><span class="doxyLineContent"><span class="doxyHighlight">                </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*p==</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight"> &amp;&amp; *(p+1)==</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3320</span><span class="doxyLineContent"><span class="doxyHighlight">                  result+=c,p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3321</span><span class="doxyLineContent"><span class="doxyHighlight">                </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3322</span><span class="doxyLineContent"><span class="doxyHighlight">                  result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3323</span><span class="doxyLineContent"><span class="doxyHighlight">                pc=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3324</span><span class="doxyLineContent"><span class="doxyHighlight">                c=*++p;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3325</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3326</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*p) result+=c,p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3327</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3328</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3329</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3330</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">: </span><span class="doxyHighlightComment">// skip string literals</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3331</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight">: </span><span class="doxyHighlightComment">// skip char literals</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3332</span><span class="doxyLineContent"><span class="doxyHighlight">          p = <a href="#ad5a00bad9b10b8fe9542cba69f171028">processUntilMatchingTerminator</a>(p,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3333</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3334</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3335</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3336</span><span class="doxyLineContent"><span class="doxyHighlight">            result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3337</span><span class="doxyLineContent"><span class="doxyHighlight">            p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3338</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3339</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3340</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3341</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3342</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3343</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("RemoveMarkers(%s)=%s\n",s,qPrint(result));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3344</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3345</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="#ad5a00bad9b10b8fe9542cba69f171028">processUntilMatchingTerminator</a>.</p>


<p>Referenced by <a href="#ae3133546e20fd36ac3b7568349ce5285">computeExpression</a> and <a href="#a319a5456c54411f74e047b8dad2de802">expandMacro</a>.</p>

</div>
</div>

### replaceFunctionMacro() {#af18da14aec7b354ada7376e24ca5e6ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool replaceFunctionMacro (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; expr, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> * rest, int pos, int &amp; len, const <a href="/web-doxygen/docs/api/classes/define">Define</a> * def, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; result, int level)</td>
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




<p>replaces the function macro <em>def</em> whose argument list starts at <em>pos</em> in expression <em>expr</em>. Notice that this routine may scan beyond the <em>expr</em> string if needed. In that case the characters will be read from the input file. The replacement string will be returned in <em>result</em> and the length of the (unexpanded) argument list is stored in <em>len</em>.</p>


<p>Definition at line 2575 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af18da14aec7b354ada7376e24ca5e6ec">2575</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#af18da14aec7b354ada7376e24ca5e6ec">replaceFunctionMacro</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;expr,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> *rest,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> pos,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> &amp;len,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/define">Define</a> *def,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;result,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2576</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2577</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("&gt;replaceFunctionMacro(expr='%s',rest='%s',pos=%d,def='%s') level=%zu\n",qPrint(expr),rest ? qPrint(*rest) : 0,pos,qPrint(def-&gt;name),state-&gt;levelGuard.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2578</span><span class="doxyLineContent"><span class="doxyHighlight">  uint32_t j=pos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2579</span><span class="doxyLineContent"><span class="doxyHighlight">  len=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2580</span><span class="doxyLineContent"><span class="doxyHighlight">  result.<a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">clear</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2581</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> cc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2582</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2583</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af8c379a1956b4f1623587160df8a0584">skipCommentMacroName</a>(yyscanner, expr, rest, cc, j, len);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2584</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2585</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cc!=</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2586</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2587</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cc!=</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// don't add spaces for colons</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2588</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2589</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad5f2a2b1209c93f3dafe4ab22a33b844">unputChar</a>(yyscanner,expr,rest,j,</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2590</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2591</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2592</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2593</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a28d316d115be97fa510e349537535baf">getNextChar</a>(yyscanner,expr,rest,j); </span><span class="doxyHighlightComment">// eat the '(' character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2594</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2595</span><span class="doxyLineContent"><span class="doxyHighlight">  std::map&lt;std::string,std::string&gt; argTable;  </span><span class="doxyHighlightComment">// list of arguments</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2596</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> arg;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2597</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> argCount=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2598</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> done=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2599</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2600</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// PHASE 1: read the macro arguments</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2601</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (def-&gt;<a href="/web-doxygen/docs/api/classes/define/#ad3306a44c59125a65fbf9559abe97930">nargs</a>==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2602</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2603</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((cc=<a href="#a28d316d115be97fa510e349537535baf">getNextChar</a>(yyscanner,expr,rest,j))!=EOF &amp;&amp; cc!=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2604</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2605</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = (char)cc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2606</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2607</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2608</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2609</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2610</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2611</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!done &amp;&amp; (argCount&lt;def-&gt;nargs || def-&gt;<a href="/web-doxygen/docs/api/classes/define/#a1802523098fdd274fd15cd0494ad26d1">varArgs</a>) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2612</span><span class="doxyLineContent"><span class="doxyHighlight">        ((cc=<a href="#a28d316d115be97fa510e349537535baf">getNextChar</a>(yyscanner,expr,rest,j))!=EOF &amp;&amp; cc!=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2613</span><span class="doxyLineContent"><span class="doxyHighlight">          )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2614</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2615</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c=(char)cc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2616</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// argument is a function =&gt; search for matching )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2617</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2618</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lvl=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2619</span><span class="doxyLineContent"><span class="doxyHighlight">        arg+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2620</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//char term='\0';</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2621</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((cc=<a href="#a28d316d115be97fa510e349537535baf">getNextChar</a>(yyscanner,expr,rest,j))!=EOF &amp;&amp; cc!=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2622</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2623</span><span class="doxyLineContent"><span class="doxyHighlight">          c=(char)cc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2624</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//printf("processing %c: term=%c (%d)\n",c,term,term);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2625</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'\"'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// skip ('s and )'s inside strings</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2626</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2627</span><span class="doxyLineContent"><span class="doxyHighlight">            arg+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2628</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a956c6709f23acd037aa021578b5b5472">addTillEndOfString</a>(yyscanner,expr,rest,j,c,arg);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2629</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2630</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2631</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2632</span><span class="doxyLineContent"><span class="doxyHighlight">            lvl--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2633</span><span class="doxyLineContent"><span class="doxyHighlight">            arg+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2634</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lvl==0) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2635</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2636</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2637</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2638</span><span class="doxyLineContent"><span class="doxyHighlight">            lvl++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2639</span><span class="doxyLineContent"><span class="doxyHighlight">            arg+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2640</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2641</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2642</span><span class="doxyLineContent"><span class="doxyHighlight">            arg+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2643</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2644</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2645</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">','</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// last or next argument found</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2646</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2647</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">','</span><span class="doxyHighlight"> &amp;&amp; argCount==def-&gt;<a href="/web-doxygen/docs/api/classes/define/#ad3306a44c59125a65fbf9559abe97930">nargs</a>-1 &amp;&amp; def-&gt;<a href="/web-doxygen/docs/api/classes/define/#a1802523098fdd274fd15cd0494ad26d1">varArgs</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2648</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2649</span><span class="doxyLineContent"><span class="doxyHighlight">          arg=arg.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2650</span><span class="doxyLineContent"><span class="doxyHighlight">          arg+=</span><span class="doxyHighlightCharLiteral">','</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2651</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2652</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2653</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2654</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> argKey;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2655</span><span class="doxyLineContent"><span class="doxyHighlight">          argKey.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"@%d"</span><span class="doxyHighlight">,argCount++); </span><span class="doxyHighlightComment">// key name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2656</span><span class="doxyLineContent"><span class="doxyHighlight">          arg=arg.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2657</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// add argument to the lookup table</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2658</span><span class="doxyLineContent"><span class="doxyHighlight">          argTable.emplace(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#ac7e12ef0c11e1acc583d1d66404c2557">toStdString</a>(argKey), <a href="/web-doxygen/docs/api/files/src/qcstring-h/#ac7e12ef0c11e1acc583d1d66404c2557">toStdString</a>(arg));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2659</span><span class="doxyLineContent"><span class="doxyHighlight">          arg.<a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">clear</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2660</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// end of the argument list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2661</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2662</span><span class="doxyLineContent"><span class="doxyHighlight">            done=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2663</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2664</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2665</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2666</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\"'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// append literal strings</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2667</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2668</span><span class="doxyLineContent"><span class="doxyHighlight">        arg+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2669</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> found=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2670</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!found &amp;&amp; (cc=<a href="#a28d316d115be97fa510e349537535baf">getNextChar</a>(yyscanner,expr,rest,j))!=EOF &amp;&amp; cc!=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2671</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2672</span><span class="doxyLineContent"><span class="doxyHighlight">          found = cc==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2673</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cc==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2674</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2675</span><span class="doxyLineContent"><span class="doxyHighlight">            c=(char)cc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2676</span><span class="doxyLineContent"><span class="doxyHighlight">            arg+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2677</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((cc=<a href="#a28d316d115be97fa510e349537535baf">getNextChar</a>(yyscanner,expr,rest,j))==EOF || cc==0) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2678</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2679</span><span class="doxyLineContent"><span class="doxyHighlight">          c=(char)cc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2680</span><span class="doxyLineContent"><span class="doxyHighlight">          arg+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2681</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2682</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2683</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// append literal characters</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2684</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2685</span><span class="doxyLineContent"><span class="doxyHighlight">        arg+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2686</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> found=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2687</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!found &amp;&amp; (cc=<a href="#a28d316d115be97fa510e349537535baf">getNextChar</a>(yyscanner,expr,rest,j))!=EOF &amp;&amp; cc!=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2688</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2689</span><span class="doxyLineContent"><span class="doxyHighlight">          found = cc==</span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2690</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cc==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2691</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2692</span><span class="doxyLineContent"><span class="doxyHighlight">            c=(char)cc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2693</span><span class="doxyLineContent"><span class="doxyHighlight">            arg+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2694</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((cc=<a href="#a28d316d115be97fa510e349537535baf">getNextChar</a>(yyscanner,expr,rest,j))==EOF || cc==0) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2695</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2696</span><span class="doxyLineContent"><span class="doxyHighlight">          c=(char)cc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2697</span><span class="doxyLineContent"><span class="doxyHighlight">          arg+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2698</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2699</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2700</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// possible start of a comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2701</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2702</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> prevChar = </span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2703</span><span class="doxyLineContent"><span class="doxyHighlight">        arg+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2704</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((cc=<a href="#a1706fe9365c74e213edf9f291a23f473">getCurrentChar</a>(yyscanner,expr,rest,j)) == </span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// we have a comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2705</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2706</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((cc=<a href="#a28d316d115be97fa510e349537535baf">getNextChar</a>(yyscanner,expr,rest,j))!=EOF &amp;&amp; cc!=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2707</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2708</span><span class="doxyLineContent"><span class="doxyHighlight">            c=(char)cc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2709</span><span class="doxyLineContent"><span class="doxyHighlight">            arg+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2710</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c == </span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight"> &amp;&amp; prevChar == </span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// we have an end of comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2711</span><span class="doxyLineContent"><span class="doxyHighlight">            prevChar = c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2712</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2713</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2714</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2715</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// append other characters</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2716</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2717</span><span class="doxyLineContent"><span class="doxyHighlight">        arg+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2718</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2719</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2720</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2721</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2722</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// PHASE 2: apply the macro function</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2723</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (argCount==def-&gt;<a href="/web-doxygen/docs/api/classes/define/#ad3306a44c59125a65fbf9559abe97930">nargs</a> || </span><span class="doxyHighlightComment">// same number of arguments</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2724</span><span class="doxyLineContent"><span class="doxyHighlight">      (argCount&gt;=def-&gt;<a href="/web-doxygen/docs/api/classes/define/#ad3306a44c59125a65fbf9559abe97930">nargs</a>-1 &amp;&amp; def-&gt;<a href="/web-doxygen/docs/api/classes/define/#a1802523098fdd274fd15cd0494ad26d1">varArgs</a>)) </span><span class="doxyHighlightComment">// variadic macro with at least as many</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2725</span><span class="doxyLineContent"><span class="doxyHighlight">                                                </span><span class="doxyHighlightComment">// params as the non-variadic part (see bug731985)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2726</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2727</span><span class="doxyLineContent"><span class="doxyHighlight">    uint32_t k=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2728</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// substitution of all formal arguments</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2729</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> resExpr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2730</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> d=def-&gt;<a href="/web-doxygen/docs/api/classes/define/#ac76e113d9f4c5b64553022777f686093">definition</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2731</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("Macro definition: '%s'\n",qPrint(d));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2732</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inString=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2733</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (k&lt;d.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2734</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2735</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(k)==</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// maybe a marker, otherwise an escaped @</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2736</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2737</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(k+1)==</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// escaped @ =&gt; copy it (is unescaped later)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2738</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2739</span><span class="doxyLineContent"><span class="doxyHighlight">          k+=2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2740</span><span class="doxyLineContent"><span class="doxyHighlight">          resExpr+=</span><span class="doxyHighlightStringLiteral">"@@"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// we unescape these later</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2741</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2742</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(k+1)==</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// no-rescan marker</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2743</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2744</span><span class="doxyLineContent"><span class="doxyHighlight">          k+=2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2745</span><span class="doxyLineContent"><span class="doxyHighlight">          resExpr+=</span><span class="doxyHighlightStringLiteral">"@-"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2746</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2747</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// argument marker =&gt; read the argument number</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2748</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2749</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> key=</span><span class="doxyHighlightStringLiteral">"@"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2750</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hash=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2751</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> l=k-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2752</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// search for ## backward</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2753</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (l&gt;=0 &amp;&amp; d.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(l)==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">) l--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2754</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (l&gt;=0 &amp;&amp; d.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(l)==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) l--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2755</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (l&gt;0 &amp;&amp; d.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(l)==</span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight"> &amp;&amp; d.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(l-1)==</span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">) hash=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2756</span><span class="doxyLineContent"><span class="doxyHighlight">          k++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2757</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// scan the number</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2758</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (k&lt;d.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() &amp;&amp; d.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(k)&gt;=</span><span class="doxyHighlightCharLiteral">'0'</span><span class="doxyHighlight"> &amp;&amp; d.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(k)&lt;=</span><span class="doxyHighlightCharLiteral">'9'</span><span class="doxyHighlight">) key+=d.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(k++);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2759</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!hash)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2760</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2761</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// search for ## forward</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2762</span><span class="doxyLineContent"><span class="doxyHighlight">            l=k;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2763</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (l&lt;(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)d.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() &amp;&amp; d.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(l)==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">) l++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2764</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (l&lt;(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)d.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() &amp;&amp; d.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(l)==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) l++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2765</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (l&lt;(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)d.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-1 &amp;&amp; d.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(l)==</span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight"> &amp;&amp; d.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(l+1)==</span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">) hash=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2766</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2767</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//printf("request key %s result %s\n",qPrint(key),argTable[key]-&gt;data());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2768</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = argTable.find(key.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2769</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=argTable.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2770</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2771</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> substArg = it-&gt;second.c_str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2772</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">//printf("substArg='%s'\n",qPrint(substArg));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2773</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// only if no ## operator is before or after the argument</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2774</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// marker we do macro expansion.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2775</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!hash)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2776</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2777</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="#a1bc8b7f200b9267b0c7b842ecd1f25b0">expandExpression</a>(yyscanner,substArg,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,0,level+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2778</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2779</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (inString)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2780</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2781</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightComment">//printf("'%s'=stringize('%s')\n",qPrint(stringize(*subst)),subst-&gt;data());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2782</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2783</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightComment">// if the marker is inside a string (because a # was put</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2784</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightComment">// before the macro name) we must escape " and \ characters</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2785</span><span class="doxyLineContent"><span class="doxyHighlight">              resExpr+=<a href="#a085c52ce4351470497b03309e77228cc">stringize</a>(substArg);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2786</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2787</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2788</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2789</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hash &amp;&amp; substArg.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2790</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2791</span><span class="doxyLineContent"><span class="doxyHighlight">                resExpr+=</span><span class="doxyHighlightStringLiteral">"@E"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// empty argument will be remove later on</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2792</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2793</span><span class="doxyLineContent"><span class="doxyHighlight">              resExpr+=substArg;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2794</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2795</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2796</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2797</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2798</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// no marker, just copy</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2799</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2800</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!inString &amp;&amp; d.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(k)==</span><span class="doxyHighlightCharLiteral">'\"'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2801</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2802</span><span class="doxyLineContent"><span class="doxyHighlight">          inString=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>; </span><span class="doxyHighlightComment">// entering a literal string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2803</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2804</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (k&gt;2 &amp;&amp; inString &amp;&amp; d.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(k)==</span><span class="doxyHighlightCharLiteral">'\"'</span><span class="doxyHighlight"> &amp;&amp; (d.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(k-1)!=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight"> || d.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(k-2)==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2805</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2806</span><span class="doxyLineContent"><span class="doxyHighlight">          inString=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>; </span><span class="doxyHighlightComment">// leaving a literal string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2807</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2808</span><span class="doxyLineContent"><span class="doxyHighlight">        resExpr+=d.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(k++);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2809</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2810</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2811</span><span class="doxyLineContent"><span class="doxyHighlight">    len=j-pos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2812</span><span class="doxyLineContent"><span class="doxyHighlight">    result=resExpr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2813</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("&lt;replaceFunctionMacro(expr='%s',rest='%s',pos=%d,def='%s',result='%s') level=%zu return=TRUE\n",qPrint(expr),rest ? qPrint(*rest) : 0,pos,qPrint(def-&gt;name),qPrint(result),state-&gt;levelGuard.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2814</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2815</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2816</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("&lt;replaceFunctionMacro(expr='%s',rest='%s',pos=%d,def='%s',result='%s') level=%zu return=FALSE\n",qPrint(expr),rest ? qPrint(*rest) : 0,pos,qPrint(def-&gt;name),qPrint(result),state-&gt;levelGuard.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2817</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2818</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a956c6709f23acd037aa021578b5b5472">addTillEndOfString</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">QCString::clear</a>, <a href="/web-doxygen/docs/api/classes/define/#ac76e113d9f4c5b64553022777f686093">Define::definition</a>, <a href="#a1bc8b7f200b9267b0c7b842ecd1f25b0">expandExpression</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a1706fe9365c74e213edf9f291a23f473">getCurrentChar</a>, <a href="#a28d316d115be97fa510e349537535baf">getNextChar</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/define/#ad3306a44c59125a65fbf9559abe97930">Define::nargs</a>, <a href="#af8c379a1956b4f1623587160df8a0584">skipCommentMacroName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">QCString::sprintf</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="#a085c52ce4351470497b03309e77228cc">stringize</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#ac7e12ef0c11e1acc583d1d66404c2557">toStdString</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="#ad5f2a2b1209c93f3dafe4ab22a33b844">unputChar</a> and <a href="/web-doxygen/docs/api/classes/define/#a1802523098fdd274fd15cd0494ad26d1">Define::varArgs</a>.</p>


<p>Referenced by <a href="#a1bc8b7f200b9267b0c7b842ecd1f25b0">expandExpression</a>.</p>

</div>
</div>

### resolveTrigraph() {#a61c9302d64d5e3f8a5e4638a1cdb9b7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char resolveTrigraph (char c)</td>
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



<p>Definition at line 3747 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a61c9302d64d5e3f8a5e4638a1cdb9b7b">3747</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> <a href="#a61c9302d64d5e3f8a5e4638a1cdb9b7b">resolveTrigraph</a>(</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3748</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3749</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3750</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3751</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'='</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3752</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3753</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'^'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3754</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'['</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3755</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">']'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3756</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'|'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3757</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3758</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'}'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3759</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'~'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3760</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3761</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'?'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3762</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### returnCharToStream() {#a854da9613a4c1ada693e325bbdd812a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void returnCharToStream (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, char c)</td>
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



<p>Definition at line 2519 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a854da9613a4c1ada693e325bbdd812a1">2519</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a854da9613a4c1ada693e325bbdd812a1">returnCharToStream</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2520</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2521</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t * yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2522</span><span class="doxyLineContent"><span class="doxyHighlight">  unput(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2523</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="#a1706fe9365c74e213edf9f291a23f473">getCurrentChar</a> and <a href="#ad5f2a2b1209c93f3dafe4ab22a33b844">unputChar</a>.</p>

</div>
</div>

### setCaseDone() {#a151056056972fe928bb34e8ed2c5a4fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void setCaseDone (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, bool value)</td>
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



<p>Definition at line 2206 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a151056056972fe928bb34e8ed2c5a4fe">2206</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a151056056972fe928bb34e8ed2c5a4fe">setCaseDone</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> value)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2207</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2208</span><span class="doxyLineContent"><span class="doxyHighlight">  YY_EXTRA_TYPE state = preYYget_extra(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2209</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;levelGuard.top()=value;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2210</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### setFileName() {#a3cd40076f3904d6c6ea657b00df39cc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void setFileName (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



<p>Definition at line 2150 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3cd40076f3904d6c6ea657b00df39cc6">2150</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3cd40076f3904d6c6ea657b00df39cc6">setFileName</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2151</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2152</span><span class="doxyLineContent"><span class="doxyHighlight">  YY_EXTRA_TYPE state = preYYget_extra(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2153</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ambig = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2154</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fi(name.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2155</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;fileName=fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#af69e3949475014dcdbd504d742bdf270">absFilePath</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2156</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;yyFileDef=<a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>,state-&gt;fileName,ambig);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2157</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (state-&gt;yyFileDef==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// if this is not an input file check if it is an include file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2158</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2159</span><span class="doxyLineContent"><span class="doxyHighlight">    state-&gt;yyFileDef=<a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#adf89ce3e8f07b60c5344d0b24f6fe28d">Doxygen::includeNameLinkedMap</a>,state-&gt;fileName,ambig);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2160</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2161</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("setFileName(%s) state-&gt;fileName=%s state-&gt;yyFileDef=%p\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2162</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//    name,qPrint(state-&gt;fileName),state-&gt;yyFileDef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2163</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (state-&gt;yyFileDef &amp;&amp; state-&gt;yyFileDef-&gt;isReference()) state-&gt;yyFileDef=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2164</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;insideIDL = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>(state-&gt;fileName)==SrcLangExt::IDL;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2165</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;insideCS = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>(state-&gt;fileName)==SrcLangExt::CSharp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2166</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;insideFtn = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>(state-&gt;fileName)==SrcLangExt::Fortran;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2167</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/entrytype">EntryType</a> section = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a99344d48bf61e8b0948b39680259cf11">guessSection</a>(state-&gt;fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2168</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;isSource = section.isHeader() || section.isSource();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2169</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/fileinfo/#af69e3949475014dcdbd504d742bdf270">FileInfo::absFilePath</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a99344d48bf61e8b0948b39680259cf11">guessSection</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#adf89ce3e8f07b60c5344d0b24f6fe28d">Doxygen::includeNameLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>


<p>Referenced by <a href="#a44966d15bb9a0624cead77c6e3c89f94">findFile</a> and <a href="/web-doxygen/docs/api/classes/preprocessor/#ab3f6062c1f94727e3d51963720d13417">Preprocessor::processFile</a>.</p>

</div>
</div>

### skipCommentMacroName() {#af8c379a1956b4f1623587160df8a0584}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void skipCommentMacroName (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; expr, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> * rest, int &amp; cc, uint32_t &amp; j, int &amp; len)</td>
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



<p>Definition at line 2537 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af8c379a1956b4f1623587160df8a0584">2537</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af8c379a1956b4f1623587160df8a0584">skipCommentMacroName</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;expr, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> *rest,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2538</span><span class="doxyLineContent"><span class="doxyHighlight">                                 </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> &amp;cc, uint32_t &amp;j, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> &amp;len)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2539</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2540</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> changed = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2541</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2542</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">do</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2543</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2544</span><span class="doxyLineContent"><span class="doxyHighlight">    changed = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2545</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((cc=<a href="#a1706fe9365c74e213edf9f291a23f473">getCurrentChar</a>(yyscanner,expr,rest,j))!=EOF &amp;&amp; cc!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight"> &amp;&amp; isspace(cc))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2546</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2547</span><span class="doxyLineContent"><span class="doxyHighlight">      len++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2548</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a28d316d115be97fa510e349537535baf">getNextChar</a>(yyscanner,expr,rest,j);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2549</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2550</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2551</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cc==</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// possible start of a comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2552</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2553</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> prevChar = </span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2554</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a28d316d115be97fa510e349537535baf">getNextChar</a>(yyscanner,expr,rest,j);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2555</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((cc=<a href="#a1706fe9365c74e213edf9f291a23f473">getCurrentChar</a>(yyscanner,expr,rest,j))!=EOF &amp;&amp; cc == </span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// we have a comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2556</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2557</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((cc=<a href="#a28d316d115be97fa510e349537535baf">getNextChar</a>(yyscanner,expr,rest,j))!=EOF &amp;&amp; cc!=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2558</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2559</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cc == </span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight"> &amp;&amp; prevChar == </span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// we have an end of comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2560</span><span class="doxyLineContent"><span class="doxyHighlight">          prevChar = cc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2561</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2562</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cc != EOF) changed = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2563</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2564</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2565</span><span class="doxyLineContent"><span class="doxyHighlight">  } </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (changed);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2566</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a1706fe9365c74e213edf9f291a23f473">getCurrentChar</a> and <a href="#a28d316d115be97fa510e349537535baf">getNextChar</a>.</p>


<p>Referenced by <a href="#af18da14aec7b354ada7376e24ca5e6ec">replaceFunctionMacro</a>.</p>

</div>
</div>

### startCondSection() {#a0ec58197ab496c7ea5a9be5edb5d6073}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void startCondSection (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; sectId)</td>
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



<p>Definition at line 3691 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0ec58197ab496c7ea5a9be5edb5d6073">3691</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a0ec58197ab496c7ea5a9be5edb5d6073">startCondSection</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;sectId)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3692</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3693</span><span class="doxyLineContent"><span class="doxyHighlight">  YY_EXTRA_TYPE state = preYYget_extra(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3694</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("startCondSection: skip=%d stack=%d\n",state-&gt;skip,state-&gt;condStack.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3695</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/condparser">CondParser</a> prs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3696</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> expResult = prs.<a href="/web-doxygen/docs/api/classes/condparser/#af254c02cc742b034cf62a9846b7b9749">parse</a>(state-&gt;fileName.data(),state-&gt;yyLineNr,sectId.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3697</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;condStack.emplace(std::make_unique&lt;preYY_CondCtx&gt;(state-&gt;fileName,state-&gt;yyLineNr,sectId,state-&gt;skip));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3698</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!expResult)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3699</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3700</span><span class="doxyLineContent"><span class="doxyHighlight">    state-&gt;skip=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3701</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3702</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("  expResult=%d skip=%d\n",expResult,state-&gt;skip);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3703</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/condparser/#af254c02cc742b034cf62a9846b7b9749">CondParser::parse</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

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



<p>Definition at line 70 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>

</div>
</div>

### stringize() {#a085c52ce4351470497b03309e77228cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString stringize (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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



<p>Definition at line 2394 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a085c52ce4351470497b03309e77228cc">2394</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a085c52ce4351470497b03309e77228cc">stringize</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2395</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2396</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2397</span><span class="doxyLineContent"><span class="doxyHighlight">  uint32_t i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2398</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inString=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2399</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inChar=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2400</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c,pc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2401</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;s.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2402</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2403</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!inString &amp;&amp; !inChar)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2404</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2405</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;s.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() &amp;&amp; !inString &amp;&amp; !inChar)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2406</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2407</span><span class="doxyLineContent"><span class="doxyHighlight">        c=s.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(i++);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2408</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2409</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2410</span><span class="doxyLineContent"><span class="doxyHighlight">          result+=</span><span class="doxyHighlightStringLiteral">"\\\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2411</span><span class="doxyLineContent"><span class="doxyHighlight">          inString=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2412</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2413</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2414</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2415</span><span class="doxyLineContent"><span class="doxyHighlight">          result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2416</span><span class="doxyLineContent"><span class="doxyHighlight">          inChar=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2417</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2418</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2419</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2420</span><span class="doxyLineContent"><span class="doxyHighlight">          result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2421</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2422</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2423</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2424</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (inChar)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2425</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2426</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;s.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() &amp;&amp; inChar)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2427</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2428</span><span class="doxyLineContent"><span class="doxyHighlight">        c=s.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(i++);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2429</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2430</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2431</span><span class="doxyLineContent"><span class="doxyHighlight">          result+=</span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2432</span><span class="doxyLineContent"><span class="doxyHighlight">          inChar=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2433</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2434</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2435</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2436</span><span class="doxyLineContent"><span class="doxyHighlight">          result+=</span><span class="doxyHighlightStringLiteral">"\\\\"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2437</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2438</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2439</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2440</span><span class="doxyLineContent"><span class="doxyHighlight">          result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2441</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2442</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2443</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2444</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2445</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2446</span><span class="doxyLineContent"><span class="doxyHighlight">      pc=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2447</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;s.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() &amp;&amp; inString)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2448</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2449</span><span class="doxyLineContent"><span class="doxyHighlight">        c=s.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(i++);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2450</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2451</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2452</span><span class="doxyLineContent"><span class="doxyHighlight">          result+=</span><span class="doxyHighlightStringLiteral">"\\\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2453</span><span class="doxyLineContent"><span class="doxyHighlight">          inString= pc==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2454</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2455</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2456</span><span class="doxyLineContent"><span class="doxyHighlight">          result+=</span><span class="doxyHighlightStringLiteral">"\\\\"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2457</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2458</span><span class="doxyLineContent"><span class="doxyHighlight">          result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2459</span><span class="doxyLineContent"><span class="doxyHighlight">        pc=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2460</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2461</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2462</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2463</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("stringize '%s'-&gt;'%s'\n",qPrint(s),qPrint(result));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2464</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2465</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>


<p>Referenced by <a href="#af18da14aec7b354ada7376e24ca5e6ec">replaceFunctionMacro</a>.</p>

</div>
</div>

### unputChar() {#ad5f2a2b1209c93f3dafe4ab22a33b844}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void unputChar (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; expr, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> * rest, uint32_t &amp; pos, char c)</td>
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



<p>Definition at line 3813 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad5f2a2b1209c93f3dafe4ab22a33b844">3813</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad5f2a2b1209c93f3dafe4ab22a33b844">unputChar</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;expr,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> *rest,uint32_t &amp;pos,</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3814</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3815</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("unputChar(%s,%s,%d,%c)\n",qPrint(expr),rest ? rest-&gt;data() : 0,pos,c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3816</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pos&lt;expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3817</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3818</span><span class="doxyLineContent"><span class="doxyHighlight">    pos++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3819</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3820</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rest)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3821</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3822</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("  prepending '%c' to rest!\n",c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3823</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> cs[2];cs[0]=c;cs[1]=</span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3824</span><span class="doxyLineContent"><span class="doxyHighlight">    rest-&gt;<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(cs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3825</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3826</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3827</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3828</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("  yyunput()='%c'\n",c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3829</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a854da9613a4c1ada693e325bbdd812a1">returnCharToStream</a>(yyscanner,c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3830</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3831</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("result: unputChar(%s,%s,%d,%c)\n",qPrint(expr),rest ? rest-&gt;data() : 0,pos,c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3832</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">QCString::prepend</a> and <a href="#a854da9613a4c1ada693e325bbdd812a1">returnCharToStream</a>.</p>


<p>Referenced by <a href="#a4a295f0fcb46dce77d4ff897094e7914">addSeparatorsIfNeeded</a> and <a href="#af18da14aec7b354ada7376e24ca5e6ec">replaceFunctionMacro</a>.</p>

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



<p>Definition at line 455 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1d80d8ed8c19744ed31163f6e7525e54">455</a></span><span class="doxyLineContent"><span class="doxyHighlight">%%</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">457</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;\x06</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;\x00</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;\r</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;"??"[=/'()!&lt;&gt;-]</span><span class="doxyHighlight">                      { </span><span class="doxyHighlightComment">// Trigraph</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">                                          unput(<a href="#a61c9302d64d5e3f8a5e4638a1cdb9b7b">resolveTrigraph</a>(yytext[2]));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;^{B}*"#"</span><span class="doxyHighlight">                         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyColNr+=(int)yyleng;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyMLines=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;potentialDefine=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(Command);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;^("%top{"|"%{")</span><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>(yyextra-&gt;fileName)!=SrcLangExt::Lex) REJECT</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(LexCopyLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;^{Bopt}"cpp_quote"{Bopt}"("{Bopt}\"</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;insideIDL)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(IDLquote);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">479</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">                                            REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;IDLquote&gt;"\\\\"</span><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"\\"</span><span class="doxyHighlight">,1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;IDLquote&gt;"\\\""</span><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">,1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;IDLquote&gt;"\""{Bopt}")"</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(Start);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;IDLquote&gt;\n</span><span class="doxyHighlight">                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;IDLquote&gt;.</span><span class="doxyHighlight">                             {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;^{Bopt}/[^#]</span><span class="doxyHighlight">                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(CopyLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;^{B}*[a-z_A-Z\x80-\xFF][a-z_A-Z0-9\x80-\xFF]+{B}*"("[^\)\n]*")"/{BN}{1,10}*[:{]</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// constructors?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (i=(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)yyleng-1;i&gt;=0;i--)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">                                            unput(yytext[i]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(CopyLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;^{B}*[_A-Z][_A-Z0-9]+{B}*"("[^\(\)\n]*"("[^\)\n]*")"[^\)\n]*")"{B}*\n</span><span class="doxyHighlight"> | </span><span class="doxyHighlightComment">// function list macro with one (...) argument, e.g. for K_GLOBAL_STATIC_WITH_ARGS</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">513</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;^{B}*[_A-Z][_A-Z0-9]+{B}*"("[^\)\n]*")"{B}*\n</span><span class="doxyHighlight"> | </span><span class="doxyHighlightComment">// function like macro</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">514</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;^{B}*[_A-Z][_A-Z0-9]+{B}*"("[^\(\)\n]*"("[^\)\n]*")"[^\)\n]*")"/{B}*("//"|"/\*")</span><span class="doxyHighlight"> | </span><span class="doxyHighlightComment">// function list macro with one (...) argument followed by comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">515</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Start&gt;^{B}*[_A-Z][_A-Z0-9]+{B}*"("[^\)\n]*")"/{B}*("//"|"/\*")</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// function like macro followed by comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">516</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> skipFuncMacros = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(SKIP_FUNCTION_MACROS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">517</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name(yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">518</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> pos = name.find(</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pos&lt;0) pos=0; </span><span class="doxyHighlightComment">// should never happen</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span><span class="doxyLineContent"><span class="doxyHighlight">                                          name=name.left(pos).stripWhiteSpace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">521</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/define">Define</a> *def=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (skipFuncMacros &amp;&amp; !yyextra-&gt;insideFtn &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">                                              name!=</span><span class="doxyHighlightStringLiteral">"Q_PROPERTY"</span><span class="doxyHighlight"> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">525</span><span class="doxyLineContent"><span class="doxyHighlight">                                              !(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">526</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 (yyextra-&gt;includeStack.empty() || yyextra-&gt;curlyCount&gt;0) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">527</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 yyextra-&gt;macroExpansion &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">528</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 (def=<a href="#a37deceebb857c5178f2ae90e8da172f2">isDefined</a>(yyscanner,name)) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">529</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 </span><span class="doxyHighlightComment">/*macroIsAccessible(def) &amp;&amp;*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">530</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 (!yyextra-&gt;expandOnlyPredef || def-&gt;<a href="/web-doxygen/docs/api/classes/define/#a856ae02f323f7e3f95fee4101da3904b">isPredefined</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">531</span><span class="doxyLineContent"><span class="doxyHighlight">                                               )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">532</span><span class="doxyLineContent"><span class="doxyHighlight">                                             )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">533</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">534</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">// Only when ends on \n</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">535</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yytext[yyleng-1] == </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">536</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">537</span><span class="doxyLineContent"><span class="doxyHighlight">                                              <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">538</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;yyLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">539</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">540</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">541</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// don't skip</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">542</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">543</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">544</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (i=(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)yyleng-1;i&gt;=0;i--)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">545</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">546</span><span class="doxyLineContent"><span class="doxyHighlight">                                              unput(yytext[i]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">547</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">548</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(CopyLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">549</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">550</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">551</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyLine,LexCopyLine&gt;"extern"{BN}*"\""[^\"]+"\""{BN}*("{")?</span><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">552</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> text=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">553</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyLineNr+=text.<a href="/web-doxygen/docs/api/classes/qcstring/#aeeedb2810a85c682c2f2a86bcd2355a7">contains</a>(</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">554</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">555</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">556</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyLine,LexCopyLine&gt;{RAWBEGIN}</span><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">557</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;delimiter = yytext+2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">558</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;delimiter=yyextra-&gt;delimiter.left(yyextra-&gt;delimiter.length()-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">559</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">560</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(CopyRawString);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">561</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyLine,LexCopyLine&gt;"{"</span><span class="doxyHighlight">               { </span><span class="doxyHighlightComment">// count brackets inside the main file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">563</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;includeStack.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;curlyCount++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">566</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">567</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">568</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">569</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;LexCopyLine&gt;^"%}"</span><span class="doxyHighlight">                      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">570</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">571</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">572</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyLine,LexCopyLine&gt;"}"</span><span class="doxyHighlight">               { </span><span class="doxyHighlightComment">// count brackets inside the main file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;includeStack.empty() &amp;&amp; yyextra-&gt;curlyCount&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">575</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;curlyCount--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">576</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">577</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">578</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyLine,LexCopyLine&gt;"'"\\[0-7]{1,3}"'"</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyLine,LexCopyLine&gt;"'"\\."'"</span><span class="doxyHighlight">         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">584</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyLine,LexCopyLine&gt;"'"."'"</span><span class="doxyHighlight">           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">586</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">587</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyLine,LexCopyLine&gt;[$]?@\"</span><span class="doxyHighlight">           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">589</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>(yyextra-&gt;fileName)!=SrcLangExt::CSharp) REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">590</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">591</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN( CopyStringCs );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">592</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">593</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyLine,LexCopyLine&gt;\"</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>(yyextra-&gt;fileName)!=SrcLangExt::Fortran)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN( CopyString );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">601</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN( CopyStringFtnDouble );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">602</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">603</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">604</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyLine,LexCopyLine&gt;\'</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>(yyextra-&gt;fileName)!=SrcLangExt::Fortran) REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN( CopyStringFtn );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyString&gt;[^\"\\\r\n]+</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyStringCs&gt;[^\"\r\n]+</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">613</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">614</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">615</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyStringCs&gt;\"\"</span><span class="doxyHighlight">                      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">616</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">618</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyString&gt;\\.</span><span class="doxyHighlight">                         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">619</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">620</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">621</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyString,CopyStringCs&gt;\"</span><span class="doxyHighlight">             {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">622</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">623</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN( CopyLine );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">624</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">625</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyStringFtnDouble&gt;[^\"\\\r\n]+</span><span class="doxyHighlight">       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">626</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">627</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">628</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyStringFtnDouble&gt;\\.</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">629</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">630</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">631</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyStringFtnDouble&gt;\"</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">632</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">633</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN( CopyLine );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">634</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">635</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyStringFtn&gt;[^\'\\\r\n]+</span><span class="doxyHighlight">             {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">636</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">637</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">638</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyStringFtn&gt;\\.</span><span class="doxyHighlight">                      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">639</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">640</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">641</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyStringFtn&gt;\'</span><span class="doxyHighlight">                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">642</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">643</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN( CopyLine );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">644</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">645</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyRawString&gt;{RAWEND}</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">646</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">647</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> delimiter = yytext+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">648</span><span class="doxyLineContent"><span class="doxyHighlight">                                          delimiter=delimiter.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(delimiter.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">649</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (delimiter==yyextra-&gt;delimiter)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">650</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">651</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN( CopyLine );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">652</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">653</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">654</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyRawString&gt;[^)]+</span><span class="doxyHighlight">                    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">655</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">656</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">657</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyRawString&gt;.</span><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">658</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">659</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">660</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyLine,LexCopyLine&gt;{ID}/{BN}{0,80}"("</span><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">661</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;expectGuard = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">662</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/define">Define</a> *def=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">663</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//def=yyextra-&gt;globalDefineDict-&gt;find(yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">664</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//def=isDefined(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">665</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//printf("Search for define %s found=%d yyextra-&gt;includeStack.empty()=%d "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">666</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//       "yyextra-&gt;curlyCount=%d yyextra-&gt;macroExpansion=%d yyextra-&gt;expandOnlyPredef=%d "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//     "isPreDefined=%d\n",yytext,def ? 1 : 0,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">668</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//     yyextra-&gt;includeStack.empty(),yyextra-&gt;curlyCount,yyextra-&gt;macroExpansion,yyextra-&gt;expandOnlyPredef,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//     def ? def-&gt;isPredefined : -1</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">670</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//    );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">671</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((yyextra-&gt;includeStack.empty() || yyextra-&gt;curlyCount&gt;0) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">672</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;macroExpansion &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">673</span><span class="doxyLineContent"><span class="doxyHighlight">                                              (def=<a href="#a37deceebb857c5178f2ae90e8da172f2">isDefined</a>(yyscanner,yytext)) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">674</span><span class="doxyLineContent"><span class="doxyHighlight">                                              (!yyextra-&gt;expandOnlyPredef || def-&gt;<a href="/web-doxygen/docs/api/classes/define/#a856ae02f323f7e3f95fee4101da3904b">isPredefined</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">675</span><span class="doxyLineContent"><span class="doxyHighlight">                                             )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">676</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">677</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">//printf("Found it! #args=%d\n",def-&gt;nargs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">678</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;roundCount=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">679</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;defArgsStr=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">680</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (def-&gt;<a href="/web-doxygen/docs/api/classes/define/#ad3306a44c59125a65fbf9559abe97930">nargs</a>==-1) </span><span class="doxyHighlightComment">// no function macro</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">681</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">682</span><span class="doxyLineContent"><span class="doxyHighlight">                                              <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result = def-&gt;<a href="/web-doxygen/docs/api/classes/define/#a856ae02f323f7e3f95fee4101da3904b">isPredefined</a> &amp;&amp; !def-&gt;<a href="/web-doxygen/docs/api/classes/define/#ad611bbbe5c08fd5da2724916ebdec09f">expandAsDefined</a> ?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">683</span><span class="doxyLineContent"><span class="doxyHighlight">                                                def-&gt;<a href="/web-doxygen/docs/api/classes/define/#ac76e113d9f4c5b64553022777f686093">definition</a> :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">684</span><span class="doxyLineContent"><span class="doxyHighlight">                                                <a href="#a319a5456c54411f74e047b8dad2de802">expandMacro</a>(yyscanner,yyextra-&gt;defArgsStr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">685</span><span class="doxyLineContent"><span class="doxyHighlight">                                              <a href="#a3ac956f197291fa939c052de93bd3d16">outputString</a>(yyscanner,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">686</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">687</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// zero or more arguments</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">688</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">689</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;findDefArgContext = CopyLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">690</span><span class="doxyLineContent"><span class="doxyHighlight">                                              BEGIN(FindDefineArgs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">691</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">692</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">693</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">694</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">696</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">697</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">698</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyLine&gt;{RulesDelim}</span><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">699</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>(yyextra-&gt;fileName)!=SrcLangExt::Lex) REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">700</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;lexRulesPart = !yyextra-&gt;lexRulesPart;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">701</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">702</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">703</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/* start lex rule handling */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">704</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyLine&gt;{RulesSharp}</span><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">705</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;lexRulesPart) REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">706</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;curlyCount) REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">707</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">708</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(RulesPattern);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">709</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">710</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesPattern&gt;{EscapeRulesChar}</span><span class="doxyHighlight">         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">711</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">712</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">713</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesPattern&gt;{RulesCurly}</span><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">714</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">715</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">716</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesPattern&gt;{StartDouble}</span><span class="doxyHighlight">             {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">717</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">718</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;lastContext = YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">719</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(RulesDouble);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">720</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">721</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesDouble,RulesRoundDouble&gt;"\\\\"</span><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">722</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">723</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">724</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesDouble,RulesRoundDouble&gt;"\\\""</span><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">725</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">726</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">727</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesDouble&gt;"\""</span><span class="doxyHighlight">                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">728</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">729</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN( yyextra-&gt;lastContext ) ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">730</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">731</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesRoundDouble&gt;"\""</span><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">732</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">733</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(RulesRound) ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">734</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">735</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesDouble,RulesRoundDouble&gt;.</span><span class="doxyHighlight">         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">736</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">737</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">738</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesPattern&gt;{StartSquare}</span><span class="doxyHighlight">             {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">739</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">740</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;lastContext = YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">741</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(RulesSquare);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">742</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">743</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesSquare,RulesRoundSquare&gt;{CHARCE}</span><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">744</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">745</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">746</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesSquare,RulesRoundSquare&gt;"\\["</span><span class="doxyHighlight"> |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">747</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesSquare,RulesRoundSquare&gt;"\\]"</span><span class="doxyHighlight">     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">748</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">749</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">750</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesSquare&gt;"]"</span><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">751</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">752</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(RulesPattern);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">753</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">754</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesRoundSquare&gt;"]"</span><span class="doxyHighlight">                   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">755</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">756</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(RulesRound) ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">757</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">758</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesSquare,RulesRoundSquare&gt;"\\\\"</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">759</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">760</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">761</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesSquare,RulesRoundSquare&gt;.</span><span class="doxyHighlight">         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">762</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">763</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">764</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesPattern&gt;{StartRoundQuest}</span><span class="doxyHighlight">         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">765</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">766</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;lastContext = YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">767</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(RulesRoundQuest);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">768</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">769</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesRoundQuest&gt;{nl}</span><span class="doxyHighlight">                   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">770</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">771</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">772</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesRoundQuest&gt;[^)]</span><span class="doxyHighlight">                   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">773</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">774</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">775</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesRoundQuest&gt;")"</span><span class="doxyHighlight">                    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">776</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">777</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(yyextra-&gt;lastContext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">778</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">779</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesPattern&gt;{StartRound}</span><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">780</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;roundCount++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">781</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">782</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;lastContext = YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">783</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(RulesRound);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">784</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">785</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesRound&gt;{RulesCurly}</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">786</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">787</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">788</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesRound&gt;{StartSquare}</span><span class="doxyHighlight">               {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">789</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">790</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(RulesRoundSquare);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">791</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">792</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesRound&gt;{StartDouble}</span><span class="doxyHighlight">               {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">793</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">794</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(RulesRoundDouble);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">795</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">796</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesRound&gt;{EscapeRulesChar}</span><span class="doxyHighlight">           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">797</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">798</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">799</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesRound&gt;"("</span><span class="doxyHighlight">                         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">800</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;roundCount++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">801</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">802</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">803</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesRound&gt;")"</span><span class="doxyHighlight">                         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">804</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;roundCount--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">805</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">806</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;roundCount) BEGIN( yyextra-&gt;lastContext ) ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">807</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">808</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesRound&gt;{nl}</span><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">809</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">810</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">811</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesRound&gt;{B}</span><span class="doxyHighlight">                         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">812</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">813</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">814</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesRound&gt;.</span><span class="doxyHighlight">                           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">815</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">816</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">817</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesPattern&gt;{B}</span><span class="doxyHighlight">                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">818</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">819</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(CopyLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">820</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">821</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RulesPattern&gt;.</span><span class="doxyHighlight">                         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">822</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">823</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">824</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/* end lex rule handling */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">825</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyLine,LexCopyLine&gt;{ID}</span><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">826</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/define">Define</a> *def=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">827</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((yyextra-&gt;includeStack.empty() || yyextra-&gt;curlyCount&gt;0) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">828</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;macroExpansion &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">829</span><span class="doxyLineContent"><span class="doxyHighlight">                                              (def=<a href="#a37deceebb857c5178f2ae90e8da172f2">isDefined</a>(yyscanner,yytext)) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">830</span><span class="doxyLineContent"><span class="doxyHighlight">                                              def-&gt;<a href="/web-doxygen/docs/api/classes/define/#ad3306a44c59125a65fbf9559abe97930">nargs</a>==-1 &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">831</span><span class="doxyLineContent"><span class="doxyHighlight">                                              (!yyextra-&gt;expandOnlyPredef || def-&gt;<a href="/web-doxygen/docs/api/classes/define/#a856ae02f323f7e3f95fee4101da3904b">isPredefined</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">832</span><span class="doxyLineContent"><span class="doxyHighlight">                                             )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">833</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">834</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result=def-&gt;<a href="/web-doxygen/docs/api/classes/define/#a856ae02f323f7e3f95fee4101da3904b">isPredefined</a> &amp;&amp; !def-&gt;<a href="/web-doxygen/docs/api/classes/define/#ad611bbbe5c08fd5da2724916ebdec09f">expandAsDefined</a> ?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">835</span><span class="doxyLineContent"><span class="doxyHighlight">                                              def-&gt;<a href="/web-doxygen/docs/api/classes/define/#ac76e113d9f4c5b64553022777f686093">definition</a> :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">836</span><span class="doxyLineContent"><span class="doxyHighlight">                                              <a href="#a319a5456c54411f74e047b8dad2de802">expandMacro</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">837</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a3ac956f197291fa939c052de93bd3d16">outputString</a>(yyscanner,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">838</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">839</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">840</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">841</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">842</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">843</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">844</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyLine,LexCopyLine&gt;"\\"\r?/\n</span><span class="doxyHighlight">        { </span><span class="doxyHighlightComment">// strip line continuation characters</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">845</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>(yyextra-&gt;fileName)==SrcLangExt::Fortran) <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">846</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">847</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyLine,LexCopyLine&gt;\\.</span><span class="doxyHighlight">               {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">848</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">849</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">850</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyLine,LexCopyLine&gt;.</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">851</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">852</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">853</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyLine,LexCopyLine&gt;\n</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">854</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">855</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(Start);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">856</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">857</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyColNr=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">858</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">859</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FindDefineArgs&gt;"("</span><span class="doxyHighlight">                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">860</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr+=</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">861</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;roundCount++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">862</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">863</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FindDefineArgs&gt;")"</span><span class="doxyHighlight">                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">864</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr+=</span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">865</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;roundCount--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">866</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;roundCount==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">867</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">868</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result=<a href="#a319a5456c54411f74e047b8dad2de802">expandMacro</a>(yyscanner,yyextra-&gt;defArgsStr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">869</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">//printf("yyextra-&gt;defArgsStr='%s'-&gt;'%s'\n",qPrint(yyextra-&gt;defArgsStr),qPrint(result));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">870</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;findDefArgContext==CopyLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">871</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">872</span><span class="doxyLineContent"><span class="doxyHighlight">                                              <a href="#a3ac956f197291fa939c052de93bd3d16">outputString</a>(yyscanner,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">873</span><span class="doxyLineContent"><span class="doxyHighlight">                                              BEGIN(yyextra-&gt;findDefArgContext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">874</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">875</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// yyextra-&gt;findDefArgContext==IncludeID</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">876</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">877</span><span class="doxyLineContent"><span class="doxyHighlight">                                              <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#acb71ba8a95e7beb78c1e3a685d8696ed">readIncludeFile</a>(yyscanner,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">878</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;nospaces=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">879</span><span class="doxyLineContent"><span class="doxyHighlight">                                              BEGIN(Start);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">880</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">881</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">882</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">883</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/*</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">884</span><span class="doxyLineContent"><span class="doxyHighlightComment">&lt;FindDefineArgs&gt;")"{B}*"("              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">885</span><span class="doxyLineContent"><span class="doxyHighlightComment">                                          yyextra-&gt;defArgsStr+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">886</span><span class="doxyLineContent"><span class="doxyHighlightComment">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">887</span><span class="doxyLineContent"><span class="doxyHighlightComment">  */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">888</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FindDefineArgs&gt;{CHARLIT}</span><span class="doxyHighlight">               {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">889</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">890</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">891</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FindDefineArgs&gt;{CCS}[*]?</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">892</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">893</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(ArgCopyCComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">894</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">895</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FindDefineArgs&gt;{CPPC}[/!].*\n/{B}*{CPPC}[/!]</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// replace multi line C++ style comment by C style comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">896</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr+=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"/**"</span><span class="doxyHighlight">)+&amp;yytext[3];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">897</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(ArgCopyCppComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">898</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">899</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FindDefineArgs&gt;{CPPC}[/!].*\n</span><span class="doxyHighlight">          { </span><span class="doxyHighlightComment">// replace C++ single line style comment by C style comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">900</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr+=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"/**"</span><span class="doxyHighlight">)+&amp;yytext[3]+</span><span class="doxyHighlightStringLiteral">" */"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">901</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">902</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FindDefineArgs&gt;\"</span><span class="doxyHighlight">                      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">903</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr+=*yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">904</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(ReadString);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">905</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">906</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FindDefineArgs&gt;'</span><span class="doxyHighlight">                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">907</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>(yyextra-&gt;fileName)!=SrcLangExt::Fortran) REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">908</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr+=*yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">909</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(ReadString);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">910</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">911</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FindDefineArgs&gt;\n</span><span class="doxyHighlight">                      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">912</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr+=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">913</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">914</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">915</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">916</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FindDefineArgs&gt;"@"</span><span class="doxyHighlight">                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">917</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr+=</span><span class="doxyHighlightStringLiteral">"@@"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">918</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">919</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;FindDefineArgs&gt;.</span><span class="doxyHighlight">                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">920</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr+=*yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">921</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">922</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ArgCopyCComment&gt;[^*\n]+</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">923</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">924</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">925</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ArgCopyCComment&gt;{CCE}</span><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">926</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">927</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(FindDefineArgs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">928</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">929</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ArgCopyCComment&gt;\n</span><span class="doxyHighlight">                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">930</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr+=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">931</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">932</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">933</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">934</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ArgCopyCComment&gt;.</span><span class="doxyHighlight">                      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">935</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">936</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">937</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ArgCopyCppComment&gt;^{B}*</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">938</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ArgCopyCppComment&gt;{CPPC}[/!].*\n/{B}*{CPPC}[/!]</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// replace multi line C++ style comment by C style comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">939</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *startContent = &amp;yytext[3];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">940</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (startContent[0]==</span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">) startContent++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">941</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr+=startContent;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">942</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">943</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ArgCopyCppComment&gt;{CPPC}[/!].*\n</span><span class="doxyHighlight">       { </span><span class="doxyHighlightComment">// replace C++ multie line style comment by C style comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">944</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *startContent = &amp;yytext[3];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">945</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (startContent[0]==</span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">) startContent++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">946</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr+=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(startContent)+</span><span class="doxyHighlightStringLiteral">" */"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">947</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(FindDefineArgs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">948</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">949</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ArgCopyCppComment&gt;.</span><span class="doxyHighlight">                    { </span><span class="doxyHighlightComment">// unexpected character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">950</span><span class="doxyLineContent"><span class="doxyHighlight">                                          unput(*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">951</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr+=</span><span class="doxyHighlightStringLiteral">" */"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">952</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(FindDefineArgs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">953</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">954</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ReadString&gt;"\""</span><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">955</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr+=*yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">956</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(FindDefineArgs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">957</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">958</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ReadString&gt;"'"</span><span class="doxyHighlight">                         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">959</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>(yyextra-&gt;fileName)!=SrcLangExt::Fortran) REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">960</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr+=*yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">961</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(FindDefineArgs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">962</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">963</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">964</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ReadString&gt;{CPPC}|{CCS}</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">965</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">966</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">967</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ReadString&gt;\\/\r?\n</span><span class="doxyHighlight">                    { </span><span class="doxyHighlightComment">// line continuation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">968</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">969</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ReadString&gt;\\.</span><span class="doxyHighlight">                         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">970</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">971</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">972</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ReadString&gt;.</span><span class="doxyHighlight">                           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">973</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr+=*yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">974</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">975</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Command&gt;("include"|"import"){B}+/{ID}</span><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">976</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;isImported = yytext[1]==</span><span class="doxyHighlightCharLiteral">'m'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">977</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;macroExpansion)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">978</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(IncludeID);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">979</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">980</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Command&gt;("include"|"import"){B}*[&lt;"]</span><span class="doxyHighlight">   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">981</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;isImported = yytext[1]==</span><span class="doxyHighlightCharLiteral">'m'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">982</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c[2];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">983</span><span class="doxyLineContent"><span class="doxyHighlight">                                          c[0]=yytext[yyleng-1];c[1]=</span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">984</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;incName=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">985</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(Include);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">986</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">987</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Command&gt;("cmake")?"define"{B}+</span><span class="doxyHighlight">         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">988</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;potentialDefine += <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(yytext,</span><span class="doxyHighlightStringLiteral">"cmake"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"     "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">989</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//printf("!!!DefName\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">990</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyColNr+=(int)yyleng;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">991</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(DefName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">992</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">993</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Command&gt;"cmakedefine01"{B}+</span><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">994</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;potentialDefine += <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(yytext,</span><span class="doxyHighlightStringLiteral">"cmakedefine01"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"     define  "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">995</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//printf("!!!DefName\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">996</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyColNr+=(int)yyleng;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">997</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(CmakeDefName01);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">998</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">999</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Command&gt;"ifdef"/{B}*"("</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1000</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a2afcdad2a81b0416c9b3fb843e631222">incrLevel</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1001</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;guardExpr.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1002</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(DefinedExpr2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1003</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1004</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Command&gt;"ifdef"/{B}+</span><span class="doxyHighlight">                   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1005</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//printf("Pre.l: ifdef\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1006</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a2afcdad2a81b0416c9b3fb843e631222">incrLevel</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1007</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;guardExpr.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1008</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(DefinedExpr1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1009</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1010</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Command&gt;"ifndef"/{B}*"("</span><span class="doxyHighlight">               {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1011</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a2afcdad2a81b0416c9b3fb843e631222">incrLevel</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1012</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;guardExpr=</span><span class="doxyHighlightStringLiteral">"! "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1013</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(DefinedExpr2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1014</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1015</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Command&gt;"ifndef"/{B}+</span><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1016</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a2afcdad2a81b0416c9b3fb843e631222">incrLevel</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1017</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;guardExpr=</span><span class="doxyHighlightStringLiteral">"! "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1018</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(DefinedExpr1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1019</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1020</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Command&gt;"if"/[ \t(!]</span><span class="doxyHighlight">                   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1021</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a2afcdad2a81b0416c9b3fb843e631222">incrLevel</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1022</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;guardExpr.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1023</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(Guard);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1024</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1025</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Command&gt;("elif"|"else"{B}*"if")/[ \t(!]</span><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1026</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#abec6a57b1258c5230a0dde8cf6e2c91f">otherCaseDone</a>(yyscanner))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1027</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1028</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;guardExpr.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1029</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(Guard);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1030</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1031</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1032</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1033</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;ifcount=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1034</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(SkipCPPBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1035</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1036</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1037</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Command&gt;"else"/[^a-z_A-Z0-9\x80-\xFF]</span><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1038</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#abec6a57b1258c5230a0dde8cf6e2c91f">otherCaseDone</a>(yyscanner))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1039</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1040</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;ifcount=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1041</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(SkipCPPBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1042</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1043</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1044</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1045</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a151056056972fe928bb34e8ed2c5a4fe">setCaseDone</a>(yyscanner,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1046</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1047</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1048</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Command&gt;"undef"{B}+</span><span class="doxyHighlight">                    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1049</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(UndefName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1050</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1051</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Command&gt;("elif"|"else"{B}*"if")/[ \t(!]</span><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1052</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#abec6a57b1258c5230a0dde8cf6e2c91f">otherCaseDone</a>(yyscanner))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1053</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1054</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;guardExpr.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1055</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(Guard);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1056</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1057</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1058</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Command&gt;"endif"/[^a-z_A-Z0-9\x80-\xFF]</span><span class="doxyHighlight">         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1059</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//printf("Pre.l: #endif\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1060</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a1917523a9eee16ade8021a9135d5e1da">decrLevel</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1061</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1062</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Command,IgnoreLine&gt;\n</span><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1063</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1064</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(Start);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1065</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1066</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1067</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Command&gt;"pragma"{B}+"once"</span><span class="doxyHighlight">             {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1068</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;expectGuard = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1069</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;pragmaSet.find(yyextra-&gt;fileName.str())!=yyextra-&gt;pragmaSet.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1070</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1071</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1072</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(PragmaOnce);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1073</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1074</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1075</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1076</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;pragmaSet.insert(yyextra-&gt;fileName.data());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1077</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1078</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1079</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;PragmaOnce&gt;.</span><span class="doxyHighlight">                           {}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1080</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;PragmaOnce&gt;\n</span><span class="doxyHighlight">                          {}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1081</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;PragmaOnce&gt;&lt;&lt;EOF&gt;&gt;</span><span class="doxyHighlight">                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1082</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;expectGuard = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1083</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(Start);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1084</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1085</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Command&gt;{ID}</span><span class="doxyHighlight">                           { </span><span class="doxyHighlightComment">// unknown directive</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1086</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(IgnoreLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1087</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1088</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;IgnoreLine&gt;\\[\r]?\n</span><span class="doxyHighlight">                   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1089</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1090</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1091</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1092</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;IgnoreLine&gt;.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1093</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Command&gt;.</span><span class="doxyHighlight">                              { yyextra-&gt;potentialDefine += yytext[0]==</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight"> ? </span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight"> : </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1094</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyColNr+=(int)yyleng;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1095</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1096</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;UndefName&gt;{ID}</span><span class="doxyHighlight">                         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1097</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/define">Define</a> *def;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1098</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((def=<a href="#a37deceebb857c5178f2ae90e8da172f2">isDefined</a>(yyscanner,yytext))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1099</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightComment">/*&amp;&amp; !def-&gt;isPredefined*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1100</span><span class="doxyLineContent"><span class="doxyHighlight">                                              &amp;&amp; !def-&gt;<a href="/web-doxygen/docs/api/classes/define/#a673dcd69701965f0f62c73ce14dc6665">nonRecursive</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1101</span><span class="doxyLineContent"><span class="doxyHighlight">                                             )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1102</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1103</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">//printf("undefining %s\n",yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1104</span><span class="doxyLineContent"><span class="doxyHighlight">                                            def-&gt;<a href="/web-doxygen/docs/api/classes/define/#afde97e0a7fadda62d088b18acc7a5a0e">undef</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1105</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1106</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(Start);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1107</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1108</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Guard&gt;\\[\r]?\n</span><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1109</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1110</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;guardExpr+=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1111</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1112</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1113</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Guard&gt;"defined"/{B}*"("</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1114</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(DefinedExpr2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1115</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1116</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Guard&gt;"defined"/{B}+</span><span class="doxyHighlight">                   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1117</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(DefinedExpr1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1118</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1119</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Guard&gt;"true"/{B}|{B}*[\r]?\n</span><span class="doxyHighlight">           { yyextra-&gt;guardExpr+=</span><span class="doxyHighlightStringLiteral">"1L"</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1120</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Guard&gt;"false"/{B}|{B}*[\r]?\n</span><span class="doxyHighlight">          { yyextra-&gt;guardExpr+=</span><span class="doxyHighlightStringLiteral">"0L"</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1121</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Guard&gt;"not"/{B}</span><span class="doxyHighlight">                        { yyextra-&gt;guardExpr+=</span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1122</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Guard&gt;"not_eq"/{B}</span><span class="doxyHighlight">                     { yyextra-&gt;guardExpr+=</span><span class="doxyHighlightStringLiteral">"!="</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1123</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Guard&gt;"and"/{B}</span><span class="doxyHighlight">                        { yyextra-&gt;guardExpr+=</span><span class="doxyHighlightStringLiteral">"&amp;&amp;"</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1124</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Guard&gt;"or"/{B}</span><span class="doxyHighlight">                         { yyextra-&gt;guardExpr+=</span><span class="doxyHighlightStringLiteral">"||"</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1125</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Guard&gt;"bitand"/{B}</span><span class="doxyHighlight">                     { yyextra-&gt;guardExpr+=</span><span class="doxyHighlightStringLiteral">"&amp;"</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1126</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Guard&gt;"bitor"/{B}</span><span class="doxyHighlight">                      { yyextra-&gt;guardExpr+=</span><span class="doxyHighlightStringLiteral">"|"</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1127</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Guard&gt;"xor"/{B}</span><span class="doxyHighlight">                        { yyextra-&gt;guardExpr+=</span><span class="doxyHighlightStringLiteral">"^"</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1128</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Guard&gt;"compl"/{B}</span><span class="doxyHighlight">                      { yyextra-&gt;guardExpr+=</span><span class="doxyHighlightStringLiteral">"~"</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1129</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Guard&gt;{ID}</span><span class="doxyHighlight">                             { yyextra-&gt;guardExpr+=yytext; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1130</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Guard&gt;"@"</span><span class="doxyHighlight">                              { yyextra-&gt;guardExpr+=</span><span class="doxyHighlightStringLiteral">"@@"</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1131</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Guard&gt;.</span><span class="doxyHighlight">                                { yyextra-&gt;guardExpr+=*yytext; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1132</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Guard&gt;\n</span><span class="doxyHighlight">                               {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1133</span><span class="doxyLineContent"><span class="doxyHighlight">                                          unput(*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1134</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//printf("Guard: '%s'\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1135</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//    qPrint(yyextra-&gt;guardExpr));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1136</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> guard=<a href="#ae3133546e20fd36ac3b7568349ce5285">computeExpression</a>(yyscanner,yyextra-&gt;guardExpr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1137</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a151056056972fe928bb34e8ed2c5a4fe">setCaseDone</a>(yyscanner,guard);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1138</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (guard)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1139</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1140</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(Start);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1141</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1142</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1143</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1144</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;ifcount=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1145</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(SkipCPPBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1146</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1147</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1148</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefinedExpr1,DefinedExpr2&gt;\\\n</span><span class="doxyHighlight">         { yyextra-&gt;yyLineNr++; <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1149</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefinedExpr1&gt;{ID}</span><span class="doxyHighlight">                      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1150</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a37deceebb857c5178f2ae90e8da172f2">isDefined</a>(yyscanner,yytext) || yyextra-&gt;guardName==yytext)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1151</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;guardExpr+=</span><span class="doxyHighlightStringLiteral">" 1L "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1152</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1153</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;guardExpr+=</span><span class="doxyHighlightStringLiteral">" 0L "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1154</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;lastGuardName=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1155</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(Guard);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1156</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1157</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefinedExpr2&gt;{ID}</span><span class="doxyHighlight">                      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1158</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a37deceebb857c5178f2ae90e8da172f2">isDefined</a>(yyscanner,yytext) || yyextra-&gt;guardName==yytext)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1159</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;guardExpr+=</span><span class="doxyHighlightStringLiteral">" 1L "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1160</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1161</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;guardExpr+=</span><span class="doxyHighlightStringLiteral">" 0L "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1162</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;lastGuardName=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1163</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1164</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefinedExpr1,DefinedExpr2&gt;\n</span><span class="doxyHighlight">           { </span><span class="doxyHighlightComment">// should not happen, handle anyway</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1165</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1166</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;ifcount=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1167</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(SkipCPPBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1168</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1169</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefinedExpr2&gt;")"</span><span class="doxyHighlight">                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1170</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(Guard);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1171</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1172</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefinedExpr1,DefinedExpr2&gt;.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1173</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCPPBlock&gt;^{B}*"#"</span><span class="doxyHighlight">                  { BEGIN(SkipCommand); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1174</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCPPBlock&gt;^{Bopt}/[^#]</span><span class="doxyHighlight">              { BEGIN(SkipLine); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1175</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCPPBlock&gt;\n</span><span class="doxyHighlight">                        { yyextra-&gt;yyLineNr++; <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1176</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCPPBlock&gt;.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1177</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCommand&gt;"if"(("n")?("def"))?/[ \t(!]</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1178</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a2afcdad2a81b0416c9b3fb843e631222">incrLevel</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1179</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;ifcount++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1180</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//printf("#if... depth=%d\n",yyextra-&gt;ifcount);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1181</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1182</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCommand&gt;"else"</span><span class="doxyHighlight">                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1183</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//printf("Else! yyextra-&gt;ifcount=%d otherCaseDone=%d\n",yyextra-&gt;ifcount,otherCaseDone());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1184</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;ifcount==0 &amp;&amp; !<a href="#abec6a57b1258c5230a0dde8cf6e2c91f">otherCaseDone</a>(yyscanner))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1185</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1186</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a151056056972fe928bb34e8ed2c5a4fe">setCaseDone</a>(yyscanner,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1187</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">//outputChar(yyscanner,'\n');</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1188</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(Start);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1189</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1190</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1191</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCommand&gt;("elif"|"else"{B}*"if")/[ \t(!]</span><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1192</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;ifcount==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1193</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1194</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#abec6a57b1258c5230a0dde8cf6e2c91f">otherCaseDone</a>(yyscanner))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1195</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1196</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;guardExpr.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1197</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;lastGuardName.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1198</span><span class="doxyLineContent"><span class="doxyHighlight">                                              BEGIN(Guard);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1199</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1200</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1201</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1202</span><span class="doxyLineContent"><span class="doxyHighlight">                                              BEGIN(SkipCPPBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1203</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1204</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1205</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1206</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCommand&gt;"endif"</span><span class="doxyHighlight">                    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1207</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;expectGuard = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1208</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a1917523a9eee16ade8021a9135d5e1da">decrLevel</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1209</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (--yyextra-&gt;ifcount&lt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1210</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1211</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">//outputChar(yyscanner,'\n');</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1212</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(Start);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1213</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1214</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1215</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCommand&gt;\n</span><span class="doxyHighlight">                         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1216</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1217</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1218</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(SkipCPPBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1219</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1220</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCommand&gt;{ID}</span><span class="doxyHighlight">                       { </span><span class="doxyHighlightComment">// unknown directive</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1221</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(SkipLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1222</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1223</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCommand&gt;.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1224</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipLine&gt;[^'"/\n]+</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1225</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipLine&gt;{CHARLIT}</span><span class="doxyHighlight">                     { }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1226</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipLine&gt;\"</span><span class="doxyHighlight">                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1227</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(SkipString);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1228</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1229</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipLine&gt;.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1230</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipString&gt;{CPPC}/[^\n]*</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1231</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1232</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipLine,SkipCommand,SkipCPPBlock&gt;{CPPC}[^\n]*</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1233</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;lastCPPContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1234</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(RemoveCPPComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1235</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1236</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipString&gt;{CCS}/[^\n]*</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1237</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1238</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipLine,SkipCommand,SkipCPPBlock&gt;{CCS}/[^\n]*</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1239</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;lastCContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1240</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(RemoveCComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1241</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1242</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipLine&gt;\n</span><span class="doxyHighlight">                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1243</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1244</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1245</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(SkipCPPBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1246</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1247</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipString&gt;[^"\\\n]+</span><span class="doxyHighlight">                   { }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1248</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipString&gt;\\.</span><span class="doxyHighlight">                         { }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1249</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipString&gt;\"</span><span class="doxyHighlight">                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1250</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(SkipLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1251</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1252</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipString&gt;.</span><span class="doxyHighlight">                           { }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1253</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;IncludeID&gt;{ID}{Bopt}/"("</span><span class="doxyHighlight">                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1254</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;nospaces=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1255</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;roundCount=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1256</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1257</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;findDefArgContext = IncludeID;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1258</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(FindDefineArgs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1259</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1260</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;IncludeID&gt;{ID}</span><span class="doxyHighlight">                         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1261</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;nospaces=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1262</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#acb71ba8a95e7beb78c1e3a685d8696ed">readIncludeFile</a>(yyscanner,<a href="#a319a5456c54411f74e047b8dad2de802">expandMacro</a>(yyscanner,yytext));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1263</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(Start);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1264</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1265</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Include&gt;[^\"&gt;\n]+[\"&gt;]</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1266</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;incName+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1267</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;isImported)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1268</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1269</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(EndImport);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1270</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1271</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1272</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1273</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#acb71ba8a95e7beb78c1e3a685d8696ed">readIncludeFile</a>(yyscanner,yyextra-&gt;incName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1274</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(Start);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1275</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1276</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1277</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;EndImport&gt;{ENDIMPORTopt}/\n</span><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1278</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#acb71ba8a95e7beb78c1e3a685d8696ed">readIncludeFile</a>(yyscanner,yyextra-&gt;incName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1279</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(Start);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1280</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1281</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;EndImport&gt;\\[\r]?"\n"</span><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1282</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1283</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1284</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1285</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;EndImport&gt;.</span><span class="doxyHighlight">                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1286</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1287</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefName&gt;{ID}/("\\\n")*"("</span><span class="doxyHighlight">              { </span><span class="doxyHighlightComment">// define with argument</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1288</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//printf("Define() '%s'\n",yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1289</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;argMap.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1290</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgs = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1291</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1292</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defText.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1293</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defLitText.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1294</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defName = yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1295</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defVarArgs = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1296</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defExtraSpacing.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1297</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defContinue = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1298</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(DefineArg);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1299</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1300</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefName&gt;{ID}{B}+"1"/[ \r\t\n]</span><span class="doxyHighlight">          { </span><span class="doxyHighlightComment">// special case: define with 1 -&gt; can be "guard"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1301</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//printf("Define '%s'\n",yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1302</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;argMap.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1303</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgs = -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1304</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1305</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defName = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(yyleng-1).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1306</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defVarArgs = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1307</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//printf("Guard check: %s!=%s || %d\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1308</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//    qPrint(yyextra-&gt;defName),qPrint(yyextra-&gt;lastGuardName),yyextra-&gt;expectGuard);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1309</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;curlyCount&gt;0 || yyextra-&gt;defName!=yyextra-&gt;lastGuardName || !yyextra-&gt;expectGuard)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1310</span><span class="doxyLineContent"><span class="doxyHighlight">                                          { </span><span class="doxyHighlightComment">// define may appear in the output</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1311</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> def = yyextra-&gt;potentialDefine +</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1312</span><span class="doxyLineContent"><span class="doxyHighlight">                                                           yyextra-&gt;defName         ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1313</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a3ac956f197291fa939c052de93bd3d16">outputString</a>(yyscanner,def);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1314</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a34739dd6d965f4701c9b7611d7c2cf9a">outputSpaces</a>(yyscanner,yytext+yyextra-&gt;defName.length());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1315</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;quoteArg=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1316</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;insideComment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1317</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;lastGuardName.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1318</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;defText=</span><span class="doxyHighlightStringLiteral">"1"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1319</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;defLitText=</span><span class="doxyHighlightStringLiteral">"1"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1320</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(DefineText);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1321</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1322</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// define is a guard =&gt; hide</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1323</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1324</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">//printf("Found a guard %s\n",yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1325</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;defText.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1326</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;defLitText.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1327</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(Start);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1328</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1329</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;expectGuard=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1330</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1331</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefName,CmakeDefName01&gt;{ID}/{B}*"\n"</span><span class="doxyHighlight">   { </span><span class="doxyHighlightComment">// empty define</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1332</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;argMap.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1333</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgs = -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1334</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defName = yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1335</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1336</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defText.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1337</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defLitText.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1338</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defVarArgs = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1339</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//printf("Guard check: %s!=%s || %d\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1340</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//    qPrint(yyextra-&gt;defName),qPrint(yyextra-&gt;lastGuardName),yyextra-&gt;expectGuard);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1341</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;curlyCount&gt;0 || yyextra-&gt;defName!=yyextra-&gt;lastGuardName || !yyextra-&gt;expectGuard)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1342</span><span class="doxyLineContent"><span class="doxyHighlight">                                          { </span><span class="doxyHighlightComment">// define may appear in the output</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1343</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> def = yyextra-&gt;potentialDefine + yyextra-&gt;defName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1344</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a3ac956f197291fa939c052de93bd3d16">outputString</a>(yyscanner,def);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1345</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;quoteArg=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1346</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;insideComment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1347</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START == CmakeDefName01) yyextra-&gt;defText = </span><span class="doxyHighlightStringLiteral">"0"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1348</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;insideCS) yyextra-&gt;defText=</span><span class="doxyHighlightStringLiteral">"1"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// for C#, use "1" as define text</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1349</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(DefineText);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1350</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1351</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// define is a guard =&gt; hide</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1352</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1353</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">//printf("Found a guard %s\n",yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1354</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;guardName = yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1355</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;lastGuardName.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1356</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(Start);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1357</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1358</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;expectGuard=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1359</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1360</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefName&gt;{ID}/{B}*</span><span class="doxyHighlight">                      { </span><span class="doxyHighlightComment">// define with content</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1361</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//printf("Define '%s'\n",yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1362</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;argMap.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1363</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgs = -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1364</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1365</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defText.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1366</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defLitText.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1367</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defName = yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1368</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defVarArgs = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1369</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> def = yyextra-&gt;potentialDefine +</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1370</span><span class="doxyLineContent"><span class="doxyHighlight">                                                         yyextra-&gt;defName         +</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1371</span><span class="doxyLineContent"><span class="doxyHighlight">                                                         yyextra-&gt;defArgsStr      ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1372</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a3ac956f197291fa939c052de93bd3d16">outputString</a>(yyscanner,def);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1373</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;quoteArg=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1374</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;insideComment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1375</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(DefineText);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1376</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1377</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefineArg&gt;"\\\n"</span><span class="doxyHighlight">                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1378</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defExtraSpacing+=</span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1379</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defContinue = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1380</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1381</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1382</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefineArg&gt;{B}*</span><span class="doxyHighlight">                         { yyextra-&gt;defExtraSpacing+=yytext; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1383</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefineArg&gt;","{B}*</span><span class="doxyHighlight">                      { yyextra-&gt;defArgsStr+=yytext; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1384</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefineArg&gt;"("{B}*</span><span class="doxyHighlight">                      { yyextra-&gt;defArgsStr+=yytext; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1385</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefineArg&gt;{B}*")"{B}*</span><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1386</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac5614d3a5285ab7ae715d23044c1e7e4">extraSpacing</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1387</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1388</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> def = yyextra-&gt;potentialDefine +</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1389</span><span class="doxyLineContent"><span class="doxyHighlight">                                                         yyextra-&gt;defName         +</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1390</span><span class="doxyLineContent"><span class="doxyHighlight">                                                         yyextra-&gt;defArgsStr      +</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1391</span><span class="doxyLineContent"><span class="doxyHighlight">                                                         yyextra-&gt;defExtraSpacing ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1392</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a3ac956f197291fa939c052de93bd3d16">outputString</a>(yyscanner,def);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1393</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;quoteArg=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1394</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;insideComment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1395</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(DefineText);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1396</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1397</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefineArg&gt;"..."</span><span class="doxyHighlight">                        { </span><span class="doxyHighlightComment">// Variadic macro</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1398</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defVarArgs = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1399</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1400</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;argMap.emplace(std::string(</span><span class="doxyHighlightStringLiteral">"__VA_ARGS__"</span><span class="doxyHighlight">),yyextra-&gt;defArgs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1401</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgs++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1402</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1403</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefineArg&gt;{ID}{B}*("..."?)</span><span class="doxyHighlight">             {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1404</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//printf("Define addArg(%s)\n",yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1405</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> argName=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1406</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defVarArgs = yytext[yyleng-1]==</span><span class="doxyHighlightCharLiteral">'.'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1407</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;defVarArgs) </span><span class="doxyHighlightComment">// strip ellipsis</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1408</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1409</span><span class="doxyLineContent"><span class="doxyHighlight">                                            argName=argName.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(argName.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-3);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1410</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1411</span><span class="doxyLineContent"><span class="doxyHighlight">                                          argName = argName.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1412</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgsStr+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1413</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;argMap.emplace(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#ac7e12ef0c11e1acc583d1d66404c2557">toStdString</a>(argName),yyextra-&gt;defArgs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1414</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defArgs++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1415</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac5614d3a5285ab7ae715d23044c1e7e4">extraSpacing</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1416</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1417</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/*</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1418</span><span class="doxyLineContent"><span class="doxyHighlightComment">&lt;DefineText&gt;"/ **"|"/ *!"                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1419</span><span class="doxyLineContent"><span class="doxyHighlightComment">                                          yyextra-&gt;defText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1420</span><span class="doxyLineContent"><span class="doxyHighlightComment">                                          yyextra-&gt;defLitText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1421</span><span class="doxyLineContent"><span class="doxyHighlightComment">                                          yyextra-&gt;insideComment=TRUE;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1422</span><span class="doxyLineContent"><span class="doxyHighlightComment">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1423</span><span class="doxyLineContent"><span class="doxyHighlightComment">&lt;DefineText&gt;"* /"                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1424</span><span class="doxyLineContent"><span class="doxyHighlightComment">                                          yyextra-&gt;defText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1425</span><span class="doxyLineContent"><span class="doxyHighlightComment">                                          yyextra-&gt;defLitText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1426</span><span class="doxyLineContent"><span class="doxyHighlightComment">                                          yyextra-&gt;insideComment=FALSE;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1427</span><span class="doxyLineContent"><span class="doxyHighlightComment">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1428</span><span class="doxyLineContent"><span class="doxyHighlightComment">  */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1429</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefineText&gt;{CCS}[!*]?</span><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1430</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1431</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defLitText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1432</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;lastCContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1433</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;commentCount=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1434</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(CopyCComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1435</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1436</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefineText&gt;{CPPC}[!/]?</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1437</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1438</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;lastCPPContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1439</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defLitText+=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1440</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(SkipCPPComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1441</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1442</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCComment&gt;[/]?{CCE}</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1443</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yytext[0]==</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">) <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1444</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">);<a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1445</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (--yyextra-&gt;commentCount&lt;=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1446</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1447</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lastCContext==Start)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1448</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightComment">// small hack to make sure that ^... rule will</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1449</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightComment">// match when going to Start... Example: "/*...*/ some stuff..."</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1450</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1451</span><span class="doxyLineContent"><span class="doxyHighlight">                                              YY_CURRENT_BUFFER-&gt;yy_at_bol=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1452</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1453</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(yyextra-&gt;lastCContext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1454</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1455</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1456</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCComment&gt;{CPPC}("/")*</span><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1457</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1458</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1459</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCComment&gt;{CCS}</span><span class="doxyHighlight">                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1460</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">);<a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1461</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//yyextra-&gt;commentCount++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1462</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1463</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCond&gt;[\\@][\\@]</span><span class="doxyHighlight">                    { }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1464</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCond&gt;^({B}*"*"+)?{B}{0,3}"~~~"[~]*</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1465</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> markdownSupport = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(MARKDOWN_SUPPORT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1466</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!markdownSupport || !yyextra-&gt;isSpecialComment)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1467</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1468</span><span class="doxyLineContent"><span class="doxyHighlight">                                            REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1469</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1470</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1471</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1472</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;fenceChar=</span><span class="doxyHighlightCharLiteral">'~'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1473</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;fenceSize=(int)<a href="#aa5261e1258a952d5fa2ff996546768c9">getFenceSize</a>(yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1474</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(SkipCondVerbatim);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1475</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1476</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1477</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCond&gt;^({B}*"*"+)?{B}{0,3}"```"[`]*</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1478</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> markdownSupport = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(MARKDOWN_SUPPORT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1479</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!markdownSupport || !yyextra-&gt;isSpecialComment)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1480</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1481</span><span class="doxyLineContent"><span class="doxyHighlight">                                            REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1482</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1483</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1484</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1485</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;fenceChar=</span><span class="doxyHighlightCharLiteral">'`'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1486</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;fenceSize=(int)<a href="#aa5261e1258a952d5fa2ff996546768c9">getFenceSize</a>(yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1487</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(SkipCondVerbatim);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1488</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1489</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1490</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCComment&gt;^({B}*"*"+)?{B}{0,3}"~~~"[~]*</span><span class="doxyHighlight">   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1491</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> markdownSupport = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(MARKDOWN_SUPPORT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1492</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!markdownSupport || !yyextra-&gt;isSpecialComment)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1493</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1494</span><span class="doxyLineContent"><span class="doxyHighlight">                                            REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1495</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1496</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1497</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1498</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1499</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;fenceChar=</span><span class="doxyHighlightCharLiteral">'~'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1500</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;fenceSize=(int)<a href="#aa5261e1258a952d5fa2ff996546768c9">getFenceSize</a>(yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1501</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(SkipVerbatim);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1502</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1503</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1504</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCComment&gt;^({B}*"*"+)?{B}{0,3}"```"[`]*</span><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1505</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> markdownSupport = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(MARKDOWN_SUPPORT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1506</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!markdownSupport || !yyextra-&gt;isSpecialComment)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1507</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1508</span><span class="doxyLineContent"><span class="doxyHighlight">                                            REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1509</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1510</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1511</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1512</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1513</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;fenceChar=</span><span class="doxyHighlightCharLiteral">'`'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1514</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;fenceSize=(int)<a href="#aa5261e1258a952d5fa2ff996546768c9">getFenceSize</a>(yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1515</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(SkipVerbatim);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1516</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1517</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1518</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCComment&gt;[\\@]{VERBATIM_LINE}</span><span class="doxyHighlight">      |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1519</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCComment&gt;[\\@]{LITERAL_BLOCK}</span><span class="doxyHighlight">      { </span><span class="doxyHighlightComment">// escaped command</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1520</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1521</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyLineNr+=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/classes/qcstring/#aeeedb2810a85c682c2f2a86bcd2355a7">contains</a>(</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1522</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1523</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCComment&gt;{VERBATIM_LINE}.*/\n</span><span class="doxyHighlight">      { </span><span class="doxyHighlightComment">// normal command</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1524</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1525</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1526</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCComment&gt;{LITERAL_BLOCK}</span><span class="doxyHighlight">           { </span><span class="doxyHighlightComment">// normal block command</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1527</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1528</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyLineNr+=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/classes/qcstring/#aeeedb2810a85c682c2f2a86bcd2355a7">contains</a>(</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1529</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a20e87c94c55f270beb04921ae491a309">determineBlockName</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1530</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(SkipVerbatim);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1531</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1532</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCond&gt;[\\@][\\@]"cond"[ \t]+</span><span class="doxyHighlight">        {}</span><span class="doxyHighlightComment">// escaped cond command</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1533</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCond&gt;[\\@]"cond"/\n</span><span class="doxyHighlight">                |  </span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1534</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCond&gt;[\\@]"cond"[ \t]+</span><span class="doxyHighlight">             { </span><span class="doxyHighlightComment">// cond command in a skipped cond section, this section has to be skipped as well</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1535</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">// but has to be recorded to match the endcond command</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1536</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a0ec58197ab496c7ea5a9be5edb5d6073">startCondSection</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1537</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1538</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCComment&gt;"{"[ \t]*"@code"/[ \t\n]</span><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1539</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"@iliteral{code}"</span><span class="doxyHighlight">,15);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1540</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;javaBlock=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1541</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(JavaDocVerbatimCode);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1542</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1543</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCComment&gt;"{"[ \t]*"@literal"/[ \t\n]</span><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1544</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"@iliteral"</span><span class="doxyHighlight">,9);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1545</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;javaBlock=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1546</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(JavaDocVerbatimCode);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1547</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1548</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCComment,SkipCPPComment&gt;[\\@][\\@]"cond"[ \t\n]+</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// escaped cond command</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1549</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1550</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1551</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCPPComment&gt;[\\@]"cond"[ \t]+</span><span class="doxyHighlight">       { </span><span class="doxyHighlightComment">// conditional section</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1552</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;ccomment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1553</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;condCtx=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1554</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(CondLineCpp);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1555</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1556</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCComment&gt;[\\@]"cond"[ \t]+</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// conditional section</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1557</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;ccomment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1558</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;condCtx=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1559</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(CondLineC);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1560</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1561</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CondLineC,CondLineCpp&gt;[!()&amp;| \ta-z_A-Z0-9\x80-\xFF.\-]+</span><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1562</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a0ec58197ab496c7ea5a9be5edb5d6073">startCondSection</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1563</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;skip)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1564</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1565</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START==CondLineC)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1566</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1567</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightComment">// end C comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1568</span><span class="doxyLineContent"><span class="doxyHighlight">                                              <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"*/"</span><span class="doxyHighlight">,2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1569</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;ccomment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1570</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1571</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1572</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1573</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;ccomment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1574</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1575</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(SkipCond);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1576</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1577</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1578</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1579</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(yyextra-&gt;condCtx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1580</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1581</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1582</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CondLineC,CondLineCpp&gt;.</span><span class="doxyHighlight">                { </span><span class="doxyHighlightComment">// non-guard character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1583</span><span class="doxyLineContent"><span class="doxyHighlight">                                          unput(*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1584</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a0ec58197ab496c7ea5a9be5edb5d6073">startCondSection</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1585</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;skip)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1586</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1587</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START==CondLineC)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1588</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1589</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightComment">// end C comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1590</span><span class="doxyLineContent"><span class="doxyHighlight">                                              <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"*/"</span><span class="doxyHighlight">,2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1591</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;ccomment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1592</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1593</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1594</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1595</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;ccomment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1596</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1597</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(SkipCond);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1598</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1599</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1600</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1601</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(yyextra-&gt;condCtx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1602</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1603</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1604</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCComment,SkipCPPComment&gt;[\\@]"cond"{WSopt}/\n</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// no guard</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1605</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START==SkipCComment)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1606</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1607</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;ccomment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1608</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">// end C comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1609</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"*/"</span><span class="doxyHighlight">,2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1610</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1611</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1612</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1613</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;ccomment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1614</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1615</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;condCtx=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1616</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a0ec58197ab496c7ea5a9be5edb5d6073">startCondSection</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1617</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(SkipCond);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1618</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1619</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCond&gt;\n</span><span class="doxyHighlight">                            { yyextra-&gt;yyLineNr++; <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1620</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCond&gt;{VERBATIM_LINE}.*/\n</span><span class="doxyHighlight">          { }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1621</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCond&gt;{LITERAL_BLOCK}</span><span class="doxyHighlight">               {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1622</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> numNLs = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/classes/qcstring/#aeeedb2810a85c682c2f2a86bcd2355a7">contains</a>(</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1623</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyLineNr+=numNLs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1624</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = 0; i &lt; numNLs; i++) <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1625</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a20e87c94c55f270beb04921ae491a309">determineBlockName</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1626</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(SkipCondVerbatim);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1627</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1628</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1629</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCond&gt;.</span><span class="doxyHighlight">                             { }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1630</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCond&gt;[^\/\!*\\@\n]+</span><span class="doxyHighlight">                { }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1631</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCond&gt;{CPPC}[/!]</span><span class="doxyHighlight">                    { yyextra-&gt;ccomment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1632</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCond&gt;{CCS}[*!]</span><span class="doxyHighlight">                     { yyextra-&gt;ccomment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1633</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCond,SkipCComment,SkipCPPComment&gt;[\\@][\\@]"endcond"/[^a-z_A-Z0-9\x80-\xFF]</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1634</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;skip)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1635</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1636</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1637</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1638</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1639</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCond&gt;[\\@]"endcond"/[^a-z_A-Z0-9\x80-\xFF]</span><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1640</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> oldSkip = yyextra-&gt;skip;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1641</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a34860cedec3675010f3293403abd9bd3">endCondSection</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1642</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (oldSkip &amp;&amp; !yyextra-&gt;skip)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1643</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1644</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;ccomment)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1645</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1646</span><span class="doxyLineContent"><span class="doxyHighlight">                                              <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"/** "</span><span class="doxyHighlight">,4); </span><span class="doxyHighlightComment">// */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1647</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1648</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(yyextra-&gt;condCtx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1649</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1650</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1651</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCComment,SkipCPPComment&gt;[\\@]"endcond"/[^a-z_A-Z0-9\x80-\xFF]</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1652</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> oldSkip = yyextra-&gt;skip;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1653</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a34860cedec3675010f3293403abd9bd3">endCondSection</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1654</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (oldSkip &amp;&amp; !yyextra-&gt;skip)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1655</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1656</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(yyextra-&gt;condCtx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1657</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1658</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1659</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCondVerbatim&gt;{LITERAL_BLOCK_END}</span><span class="doxyHighlight">   { </span><span class="doxyHighlightComment">/* end of verbatim block */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1660</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yytext[1]==</span><span class="doxyHighlightCharLiteral">'f'</span><span class="doxyHighlight"> &amp;&amp; yyextra-&gt;blockName==&amp;yytext[2])</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1661</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1662</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(SkipCond);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1663</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1664</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (&amp;yytext[4]==yyextra-&gt;blockName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1665</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1666</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(SkipCond);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1667</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1668</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1669</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipVerbatim&gt;{LITERAL_BLOCK_END}</span><span class="doxyHighlight">       { </span><span class="doxyHighlightComment">/* end of verbatim block */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1670</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1671</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yytext[1]==</span><span class="doxyHighlightCharLiteral">'f'</span><span class="doxyHighlight"> &amp;&amp; yyextra-&gt;blockName==&amp;yytext[2])</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1672</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1673</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(SkipCComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1674</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1675</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (&amp;yytext[4]==yyextra-&gt;blockName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1676</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1677</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(SkipCComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1678</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1679</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1680</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCondVerbatim&gt;^({B}*"*"+)?{B}{0,3}"~~~"[~]*</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1681</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;fenceSize==<a href="#aa5261e1258a952d5fa2ff996546768c9">getFenceSize</a>(yytext,yyleng) &amp;&amp;  yyextra-&gt;fenceChar==</span><span class="doxyHighlightCharLiteral">'~'</span><span class="doxyHighlight">) </span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1682</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1683</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(SkipCond);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1684</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1685</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1686</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCondVerbatim&gt;^({B}*"*"+)?{B}{0,3}"```"[`]*</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1687</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;fenceSize==<a href="#aa5261e1258a952d5fa2ff996546768c9">getFenceSize</a>(yytext,yyleng) &amp;&amp;  yyextra-&gt;fenceChar==</span><span class="doxyHighlightCharLiteral">'`'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1688</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1689</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(SkipCond);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1690</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1691</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1692</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipVerbatim&gt;^({B}*"*"+)?{B}{0,3}"~~~"[~]*</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1693</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1694</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;fenceSize==<a href="#aa5261e1258a952d5fa2ff996546768c9">getFenceSize</a>(yytext,yyleng) &amp;&amp;  yyextra-&gt;fenceChar==</span><span class="doxyHighlightCharLiteral">'~'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1695</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1696</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(SkipCComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1697</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1698</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1699</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipVerbatim&gt;^({B}*"*"+)?{B}{0,3}"```"[`]*</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1700</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1701</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;fenceSize==<a href="#aa5261e1258a952d5fa2ff996546768c9">getFenceSize</a>(yytext,yyleng) &amp;&amp;  yyextra-&gt;fenceChar==</span><span class="doxyHighlightCharLiteral">'`'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1702</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1703</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(SkipCComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1704</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1705</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1706</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCondVerbatim&gt;{CCE}|{CCS}</span><span class="doxyHighlight">           { }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1707</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipVerbatim&gt;{CCE}|{CCS}</span><span class="doxyHighlight">               {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1708</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1709</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1710</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;JavaDocVerbatimCode&gt;"{"</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1711</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;javaBlock==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1712</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1713</span><span class="doxyLineContent"><span class="doxyHighlight">                                            REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1714</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1715</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1716</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1717</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;javaBlock++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1718</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1719</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1720</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1721</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;JavaDocVerbatimCode&gt;"}"</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1722</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;javaBlock==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1723</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1724</span><span class="doxyLineContent"><span class="doxyHighlight">                                            REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1725</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1726</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1727</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1728</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;javaBlock--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1729</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;javaBlock==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1730</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1731</span><span class="doxyLineContent"><span class="doxyHighlight">                                              <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">" @endiliteral "</span><span class="doxyHighlight">,14);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1732</span><span class="doxyLineContent"><span class="doxyHighlight">                                              BEGIN(SkipCComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1733</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1734</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1735</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1736</span><span class="doxyLineContent"><span class="doxyHighlight">                                              <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1737</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1738</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1739</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1740</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;JavaDocVerbatimCode&gt;\n</span><span class="doxyHighlight">                 { </span><span class="doxyHighlightComment">/* new line in verbatim block */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1741</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1742</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1743</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;JavaDocVerbatimCode&gt;.</span><span class="doxyHighlight">                  { </span><span class="doxyHighlightComment">/* any other character */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1744</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1745</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1746</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCondVerbatim&gt;[^{*\\@\x06~`\n\/]+</span><span class="doxyHighlight">   { }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1747</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCComment,SkipVerbatim&gt;[^{*\\@\x06~`\n\/]+</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1748</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1749</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1750</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCComment,SkipVerbatim,SkipCondVerbatim&gt;\n</span><span class="doxyHighlight">           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1751</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1752</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1753</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1754</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCondVerbatim&gt;.</span><span class="doxyHighlight">                     { }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1755</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCComment,SkipVerbatim&gt;.</span><span class="doxyHighlight">            { </span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1756</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1757</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1758</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyCComment&gt;[^*a-z_A-Z\x80-\xFF\n]*[^*a-z_A-Z\x80-\xFF\\\n]</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1759</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defLitText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1760</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defText+=<a href="#ad860c94401483cee6345e6dd71bab597">escapeAt</a>(yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1761</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1762</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyCComment&gt;\\[\r]?\n</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1763</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defLitText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1764</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defText+=</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1765</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1766</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyMLines++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1767</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1768</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyCComment&gt;{CCE}</span><span class="doxyHighlight">                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1769</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defLitText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1770</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1771</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(yyextra-&gt;lastCContext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1772</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1773</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyCComment&gt;\n</span><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1774</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1775</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defLitText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1776</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defText+=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1777</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1778</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RemoveCComment&gt;{CCE}{B}*"#"</span><span class="doxyHighlight">            { </span><span class="doxyHighlightComment">// see bug 594021 for a usecase for this rule</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1779</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lastCContext==SkipCPPBlock)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1780</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1781</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(SkipCommand);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1782</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1783</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1784</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1785</span><span class="doxyLineContent"><span class="doxyHighlight">                                            REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1786</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1787</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1788</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RemoveCComment&gt;{CCE}</span><span class="doxyHighlight">                   { BEGIN(yyextra-&gt;lastCContext); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1789</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RemoveCComment&gt;{CPPC}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1790</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RemoveCComment&gt;{CCS}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1791</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RemoveCComment&gt;[^*\x06\n]+</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1792</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RemoveCComment&gt;\n</span><span class="doxyHighlight">                      { yyextra-&gt;yyLineNr++; <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1793</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RemoveCComment&gt;.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1794</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCPPComment&gt;[^\n\/\\@]+</span><span class="doxyHighlight">             {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1795</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1796</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1797</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCPPComment,RemoveCPPComment&gt;\n</span><span class="doxyHighlight">     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1798</span><span class="doxyLineContent"><span class="doxyHighlight">                                          unput(*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1799</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(yyextra-&gt;lastCPPContext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1800</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1801</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCPPComment&gt;{CCS}</span><span class="doxyHighlight">                   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1802</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">);<a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1803</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1804</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCPPComment&gt;{CPPC}</span><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1805</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">);<a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1806</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1807</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCPPComment&gt;[^\x06\@\\\n]+</span><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1808</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1809</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1810</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipCPPComment&gt;.</span><span class="doxyHighlight">                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1811</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1812</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1813</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RemoveCPPComment&gt;{CCS}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1814</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RemoveCPPComment&gt;{CPPC}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1815</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RemoveCPPComment&gt;[^\x06\n]+</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1816</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;RemoveCPPComment&gt;.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1817</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefineText&gt;"#"/{IDSTART}</span><span class="doxyHighlight">               {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1818</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1819</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;quoteArg=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1820</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;idStart=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1821</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defLitText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1822</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1823</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefineText,CopyCComment&gt;{ID}</span><span class="doxyHighlight">           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1824</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defLitText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1825</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START == DefineText) <a href="#a34739dd6d965f4701c9b7611d7c2cf9a">outputSpaces</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1826</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;quoteArg)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1827</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1828</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;defText+=</span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1829</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1830</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;defArgs&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1831</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1832</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = yyextra-&gt;argMap.find(yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1833</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=yyextra-&gt;argMap.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1834</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1835</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> n = it-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1836</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;defText+=</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1837</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;defText+=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">setNum</a>(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1838</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1839</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1840</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1841</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;idStart)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1842</span><span class="doxyLineContent"><span class="doxyHighlight">                                              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1843</span><span class="doxyLineContent"><span class="doxyHighlight">                                                <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(yyextra-&gt;fileName,yyextra-&gt;yyLineNr,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1844</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  </span><span class="doxyHighlightStringLiteral">"'#' is not followed by a macro parameter '{}': '{}'"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1845</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  yyextra-&gt;defName,yyextra-&gt;defLitText.stripWhiteSpace());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1846</span><span class="doxyLineContent"><span class="doxyHighlight">                                              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1847</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;defText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1848</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1849</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1850</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1851</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1852</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;defText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1853</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1854</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;quoteArg)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1855</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1856</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;defText+=</span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1857</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1858</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;quoteArg=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1859</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;idStart=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1860</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1861</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyCComment&gt;.</span><span class="doxyHighlight">                         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1862</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defLitText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1863</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1864</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1865</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefineText&gt;\\[\r]?\n</span><span class="doxyHighlight">                   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1866</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defLitText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1867</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1868</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1869</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defText += </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1870</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1871</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyMLines++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1872</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1873</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefineText&gt;\n</span><span class="doxyHighlight">                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1874</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ae8c2c4e6dab650ca0dbc32956838ddd9">comment</a>=<a href="#a4f2d544ac38e037f4572ce9163d17aed">extractTrailingComment</a>(yyextra-&gt;defLitText);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1875</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defText = yyextra-&gt;defText.stripWhiteSpace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1876</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;defText.startsWith(</span><span class="doxyHighlightStringLiteral">"##"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1877</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1878</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(yyextra-&gt;fileName,yyextra-&gt;yyLineNr,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1879</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 </span><span class="doxyHighlightStringLiteral">"'##' cannot occur at the beginning of a macro definition '{}': '{}'"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1880</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 yyextra-&gt;defName,yyextra-&gt;defLitText.stripWhiteSpace());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1881</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1882</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;defText.endsWith(</span><span class="doxyHighlightStringLiteral">"##"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1883</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1884</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(yyextra-&gt;fileName,yyextra-&gt;yyLineNr,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1885</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 </span><span class="doxyHighlightStringLiteral">"'##' cannot occur at the end of a macro definition '{}': '{}'"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1886</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 yyextra-&gt;defName,yyextra-&gt;defLitText.stripWhiteSpace());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1887</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1888</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;defText.endsWith(</span><span class="doxyHighlightStringLiteral">"#"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1889</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1890</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(yyextra-&gt;fileName,yyextra-&gt;yyLineNr,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1891</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 </span><span class="doxyHighlightStringLiteral">"expected formal parameter after # in macro definition '{}': '{}'"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1892</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 yyextra-&gt;defName,yyextra-&gt;defLitText.stripWhiteSpace());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1893</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1894</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ae8c2c4e6dab650ca0dbc32956838ddd9">comment</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1895</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1896</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a3ac956f197291fa939c052de93bd3d16">outputString</a>(yyscanner,<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ae8c2c4e6dab650ca0dbc32956838ddd9">comment</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1897</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;defLitText=yyextra-&gt;defLitText.left(yyextra-&gt;defLitText.length()-<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ae8c2c4e6dab650ca0dbc32956838ddd9">comment</a>.length()-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1898</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1899</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1900</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defLitText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1901</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/classes/define">Define</a> *def=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1902</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//printf("Define name='%s' text='%s' litTexti='%s'\n",qPrint(yyextra-&gt;defName),qPrint(yyextra-&gt;defText),qPrint(yyextra-&gt;defLitText));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1903</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;includeStack.empty() || yyextra-&gt;curlyCount&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1904</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1905</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a157d33872a9501263b2b34cc7ced0ffa">addMacroDefinition</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1906</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1907</span><span class="doxyLineContent"><span class="doxyHighlight">                                          def=<a href="#a37deceebb857c5178f2ae90e8da172f2">isDefined</a>(yyscanner,yyextra-&gt;defName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1908</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (def==0) </span><span class="doxyHighlightComment">// new define</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1909</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1910</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">//printf("new define '%s'!\n",qPrint(yyextra-&gt;defName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1911</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a207d66f561747d53a0df54a5019cc45b">addDefine</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1912</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1913</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (def </span><span class="doxyHighlightComment">/*&amp;&amp; macroIsAccessible(def)*/</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1914</span><span class="doxyLineContent"><span class="doxyHighlight">                                               </span><span class="doxyHighlightComment">// name already exists</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1915</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1916</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">//printf("existing define!\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1917</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">//printf("define found\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1918</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (def-&gt;<a href="/web-doxygen/docs/api/classes/define/#afde97e0a7fadda62d088b18acc7a5a0e">undef</a>) </span><span class="doxyHighlightComment">// undefined name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1919</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1920</span><span class="doxyLineContent"><span class="doxyHighlight">                                              def-&gt;<a href="/web-doxygen/docs/api/classes/define/#afde97e0a7fadda62d088b18acc7a5a0e">undef</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1921</span><span class="doxyLineContent"><span class="doxyHighlight">                                              def-&gt;<a href="/web-doxygen/docs/api/classes/define/#a2ab61e312bcf057292789daa0de8bf78">name</a> = yyextra-&gt;defName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1922</span><span class="doxyLineContent"><span class="doxyHighlight">                                              def-&gt;<a href="/web-doxygen/docs/api/classes/define/#ac76e113d9f4c5b64553022777f686093">definition</a> = yyextra-&gt;defText.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1923</span><span class="doxyLineContent"><span class="doxyHighlight">                                              def-&gt;<a href="/web-doxygen/docs/api/classes/define/#ad3306a44c59125a65fbf9559abe97930">nargs</a> = yyextra-&gt;defArgs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1924</span><span class="doxyLineContent"><span class="doxyHighlight">                                              def-&gt;<a href="/web-doxygen/docs/api/classes/define/#a2403c7fc667a4a5fd74c8a78560030cc">fileName</a> = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1925</span><span class="doxyLineContent"><span class="doxyHighlight">                                              def-&gt;<a href="/web-doxygen/docs/api/classes/define/#a16325de589f92470990e80e0d3cb403f">lineNr</a> = yyextra-&gt;yyLineNr-yyextra-&gt;yyMLines;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1926</span><span class="doxyLineContent"><span class="doxyHighlight">                                              def-&gt;<a href="/web-doxygen/docs/api/classes/define/#aa3baaeb7d662ad6190da946f3a65a773">columnNr</a> = yyextra-&gt;yyColNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1927</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1928</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1929</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1930</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (def-&gt;<a href="/web-doxygen/docs/api/classes/define/#a2403c7fc667a4a5fd74c8a78560030cc">fileName</a> != yyextra-&gt;fileName &amp;&amp; !yyextra-&gt;expandOnlyPredef) <a href="#a207d66f561747d53a0df54a5019cc45b">addDefine</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1931</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightComment">//printf("error: define %s is defined more than once!\n",qPrint(yyextra-&gt;defName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1932</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1933</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1934</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;argMap.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1935</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1936</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyColNr=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1937</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;lastGuardName.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1938</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(Start);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1939</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1940</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefineText&gt;{B}*</span><span class="doxyHighlight">                        { <a href="#a3ac956f197291fa939c052de93bd3d16">outputString</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1941</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defText += </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1942</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defLitText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1943</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1944</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefineText&gt;{B}*"##"{B}*</span><span class="doxyHighlight">                { <a href="#a3ac956f197291fa939c052de93bd3d16">outputString</a>(yyscanner,<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(yytext,</span><span class="doxyHighlightStringLiteral">"##"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"  "</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1945</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defText += </span><span class="doxyHighlightStringLiteral">"##"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1946</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defLitText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1947</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1948</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefineText&gt;"@"</span><span class="doxyHighlight">                         { <a href="#a3ac956f197291fa939c052de93bd3d16">outputString</a>(yyscanner,<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(yytext,</span><span class="doxyHighlightStringLiteral">"@@"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"  "</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1949</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defText += </span><span class="doxyHighlightStringLiteral">"@@"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1950</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defLitText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1951</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1952</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefineText&gt;\"</span><span class="doxyHighlight">                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1953</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1954</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defText += *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1955</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defLitText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1956</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;insideComment)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1957</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1958</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(SkipDoubleQuote);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1959</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1960</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1961</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefineText&gt;\'</span><span class="doxyHighlight">                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1962</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1963</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defText += *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1964</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defLitText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1965</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;insideComment)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1966</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1967</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(SkipSingleQuote);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1968</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1969</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1970</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipDoubleQuote&gt;{CPPC}[/]?</span><span class="doxyHighlight">             { <a href="#a34739dd6d965f4701c9b7611d7c2cf9a">outputSpaces</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1971</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defText += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1972</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defLitText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1973</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1974</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipDoubleQuote&gt;{CCS}[*]?</span><span class="doxyHighlight">              { <a href="#a34739dd6d965f4701c9b7611d7c2cf9a">outputSpaces</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1975</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defText += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1976</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defLitText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1977</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1978</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipDoubleQuote&gt;\"</span><span class="doxyHighlight">                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1979</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1980</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defText += *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1981</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defLitText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1982</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(DefineText);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1983</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1984</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipSingleQuote,SkipDoubleQuote&gt;\\.</span><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1985</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a34739dd6d965f4701c9b7611d7c2cf9a">outputSpaces</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1986</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defText += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1987</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defLitText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1988</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1989</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipSingleQuote&gt;\'</span><span class="doxyHighlight">                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1990</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1991</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defText += *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1992</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defLitText+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1993</span><span class="doxyLineContent"><span class="doxyHighlight">                                          BEGIN(DefineText);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1994</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1995</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipDoubleQuote,SkipSingleQuote&gt;.</span><span class="doxyHighlight">      { <a href="#ae596fa0b1fbc60f9128146cc90630101">outputSpace</a>(yyscanner,yytext[0]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1996</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defText    += *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1997</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defLitText += *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1998</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1999</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;DefineText&gt;.</span><span class="doxyHighlight">                           { <a href="#ae596fa0b1fbc60f9128146cc90630101">outputSpace</a>(yyscanner,yytext[0]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2000</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defText    += *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2001</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;defLitText += *yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2002</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2003</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;&lt;EOF&gt;&gt;</span><span class="doxyHighlight">                                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2004</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/trace-h/#a5f6aa8edcd99914757600b5d3b259bb7">TRACE</a>(</span><span class="doxyHighlightStringLiteral">"End of include file"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2005</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightComment">//printf("Include stack depth=%d\n",yyextra-&gt;includeStack.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2006</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;includeStack.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2007</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2008</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/trace-h/#a5f6aa8edcd99914757600b5d3b259bb7">TRACE</a>(</span><span class="doxyHighlightStringLiteral">"Terminating scanner"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2009</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#ac3286b18a2e91b4571b97df96a118e84">yyterminate</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2010</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2011</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2012</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2013</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> toFileName = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2014</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::unique_ptr&lt;FileState&gt; &amp;fs=yyextra-&gt;includeStack.back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2015</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">//fileDefineCache-&gt;merge(yyextra-&gt;fileName,fs-&gt;fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2016</span><span class="doxyLineContent"><span class="doxyHighlight">                                            YY_BUFFER_STATE oldBuf = YY_CURRENT_BUFFER;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2017</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yy_switch_to_buffer( fs-&gt;bufState, yyscanner );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2018</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yy_delete_buffer( oldBuf, yyscanner );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2019</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;yyLineNr    = fs-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2020</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">//preYYin = fs-&gt;oldYYin;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2021</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;inputBuf    = fs-&gt;oldFileBuf;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2022</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;inputBufPos = fs-&gt;oldFileBufPos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2023</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;curlyCount  = fs-&gt;curlyCount;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2024</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a3cd40076f3904d6c6ea657b00df39cc6">setFileName</a>(yyscanner,fs-&gt;fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2025</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/files/src/trace-h/#a5f6aa8edcd99914757600b5d3b259bb7">TRACE</a>(</span><span class="doxyHighlightStringLiteral">"switching to {}"</span><span class="doxyHighlight">,yyextra-&gt;fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2026</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2027</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">// Deal with file changes due to</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2028</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">// #include's within { .. } blocks</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2029</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> lineStr(15+yyextra-&gt;fileName.length(), <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2030</span><span class="doxyLineContent"><span class="doxyHighlight">                                            lineStr.sprintf(</span><span class="doxyHighlightStringLiteral">"# %d \"%s\" 2"</span><span class="doxyHighlight">,yyextra-&gt;yyLineNr,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(yyextra-&gt;fileName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2031</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#a3ac956f197291fa939c052de93bd3d16">outputString</a>(yyscanner,lineStr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2032</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2033</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;includeStack.pop_back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2034</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2035</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2036</span><span class="doxyLineContent"><span class="doxyHighlight">                                              std::lock_guard&lt;std::mutex&gt; lock(<a href="#a41d40eee862471579482f58a442f157d">g_globalDefineMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2037</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightComment">// to avoid deadlocks we allow multiple threads to process the same header file.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2038</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightComment">// The first one to finish will store the results globally. After that the</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2039</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightComment">// next time the same file is encountered, the stored data is used and the file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2040</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightComment">// is not processed again.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2041</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a888d117646a1150fd6672a7cc9c0a81d">g_defineManager</a>.alreadyProcessed(toFileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2042</span><span class="doxyLineContent"><span class="doxyHighlight">                                              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2043</span><span class="doxyLineContent"><span class="doxyHighlight">                                                </span><span class="doxyHighlightComment">// now that the file is completely processed, prevent it from processing it again</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2044</span><span class="doxyLineContent"><span class="doxyHighlight">                                                <a href="#a888d117646a1150fd6672a7cc9c0a81d">g_defineManager</a>.addInclude(yyextra-&gt;fileName.str(),toFileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2045</span><span class="doxyLineContent"><span class="doxyHighlight">                                                <a href="#a888d117646a1150fd6672a7cc9c0a81d">g_defineManager</a>.store(toFileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),yyextra-&gt;localDefines);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2046</span><span class="doxyLineContent"><span class="doxyHighlight">                                              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2047</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2048</span><span class="doxyLineContent"><span class="doxyHighlight">                                              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2049</span><span class="doxyLineContent"><span class="doxyHighlight">                                                </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daec63880706f2286cd7ca9057bf407e2f">Debug::Preprocessor</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2050</span><span class="doxyLineContent"><span class="doxyHighlight">                                                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2051</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daec63880706f2286cd7ca9057bf407e2f">Debug::Preprocessor</a>,0,</span><span class="doxyHighlightStringLiteral">"#include {}: was already processed by another thread! not storing data...\n"</span><span class="doxyHighlight">,toFileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2052</span><span class="doxyLineContent"><span class="doxyHighlight">                                                }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2053</span><span class="doxyLineContent"><span class="doxyHighlight">                                              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2054</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2055</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightComment">// move the local macros definitions for in this file to the translation unit context</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2056</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;kv : yyextra-&gt;localDefines)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2057</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2058</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> pair = yyextra-&gt;contextDefines.insert(kv);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2059</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!pair.second) </span><span class="doxyHighlightComment">// define already in context -&gt; replace with local version</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2060</span><span class="doxyLineContent"><span class="doxyHighlight">                                              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2061</span><span class="doxyLineContent"><span class="doxyHighlight">                                                yyextra-&gt;contextDefines.erase(pair.first);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2062</span><span class="doxyLineContent"><span class="doxyHighlight">                                                yyextra-&gt;contextDefines.insert(kv);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2063</span><span class="doxyLineContent"><span class="doxyHighlight">                                              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2064</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2065</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;localDefines.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2066</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2067</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2068</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;{CCS}/{CCE}</span><span class="doxyHighlight">                          |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2069</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;{CCS}[*!]?</span><span class="doxyHighlight">                           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2070</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START==SkipVerbatim || YY_START == SkipCondVerbatim || YY_START==SkipCond || YY_START==IDLquote || YY_START == PragmaOnce)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2071</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2072</span><span class="doxyLineContent"><span class="doxyHighlight">                                            REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2073</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2074</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2075</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2076</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2077</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;lastCContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2078</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;commentCount=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2079</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyleng==3)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2080</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2081</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;isSpecialComment = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2082</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;lastGuardName.clear(); </span><span class="doxyHighlightComment">// reset guard in case the #define is documented!</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2083</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2084</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2085</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2086</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;isSpecialComment = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2087</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2088</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(SkipCComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2089</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2090</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2091</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;{CPPC}[/!]?</span><span class="doxyHighlight">                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2092</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START==SkipVerbatim || YY_START == SkipCondVerbatim || YY_START==SkipCond || <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>(yyextra-&gt;fileName)==SrcLangExt::Fortran || YY_START==IDLquote || YY_START == PragmaOnce)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2093</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2094</span><span class="doxyLineContent"><span class="doxyHighlight">                                            REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2095</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2096</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START==RulesRoundDouble)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2097</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2098</span><span class="doxyLineContent"><span class="doxyHighlight">                                            REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2099</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2100</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2101</span><span class="doxyLineContent"><span class="doxyHighlight">                                          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2102</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="#ac2c518bb48991ade6e459a3e203e6a86">outputArray</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2103</span><span class="doxyLineContent"><span class="doxyHighlight">                                            yyextra-&gt;lastCPPContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2104</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyleng==3)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2105</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2106</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;isSpecialComment = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2107</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;lastGuardName.clear(); </span><span class="doxyHighlightComment">// reset guard in case the #define is documented!</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2108</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2109</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2110</span><span class="doxyLineContent"><span class="doxyHighlight">                                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2111</span><span class="doxyLineContent"><span class="doxyHighlight">                                              yyextra-&gt;isSpecialComment = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2112</span><span class="doxyLineContent"><span class="doxyHighlight">                                            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2113</span><span class="doxyLineContent"><span class="doxyHighlight">                                            BEGIN(SkipCPPComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2114</span><span class="doxyLineContent"><span class="doxyHighlight">                                          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2115</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2116</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;\n</span><span class="doxyHighlight">                                   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2117</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2118</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;yyLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2119</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2120</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;.</span><span class="doxyHighlight">                                    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2121</span><span class="doxyLineContent"><span class="doxyHighlight">                                          yyextra-&gt;expectGuard = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2122</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="#a4864d83d173c2deef235ab17f9c6a529">outputChar</a>(yyscanner,*yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2123</span><span class="doxyLineContent"><span class="doxyHighlight">                                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2124</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2125</span><span class="doxyLineContent"><span class="doxyHighlight">%%</span></span></div>

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



<p>Definition at line 2129 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5edfc25f0c460f3263fdb340f7a02b03">2129</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/code-l/#a5edfc25f0c460f3263fdb340f7a02b03">yyread</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *buf,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> max_size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2130</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2131</span><span class="doxyLineContent"><span class="doxyHighlight">  YY_EXTRA_TYPE state = preYYget_extra(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2132</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> bytesInBuf = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(state-&gt;inputBuf-&gt;size())-state-&gt;inputBufPos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2133</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> bytesToCopy = std::min(max_size,bytesInBuf);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2134</span><span class="doxyLineContent"><span class="doxyHighlight">  memcpy(buf,state-&gt;inputBuf-&gt;data()+state-&gt;inputBufPos,bytesToCopy);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2135</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;inputBufPos+=bytesToCopy;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2136</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> bytesToCopy;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2137</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### g\_debugMutex {#afa74555c39c3f592f0d6113ba0dc6aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex g_debugMutex</td>
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



<p>Definition at line 233 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afa74555c39c3f592f0d6113ba0dc6aa9">233</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::mutex            <a href="#afa74555c39c3f592f0d6113ba0dc6aa9">g_debugMutex</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/preprocessor/#ab3f6062c1f94727e3d51963720d13417">Preprocessor::processFile</a>.</p>

</div>
</div>

### g\_defineManager {#a888d117646a1150fd6672a7cc9c0a81d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DefineManager g_defineManager</td>
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



<p>Definition at line 236 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a888d117646a1150fd6672a7cc9c0a81d">236</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definemanager">DefineManager</a>         <a href="#a888d117646a1150fd6672a7cc9c0a81d">g_defineManager</a>;</span></span></div>

</div>


<p>Referenced by <a href="#abac7d9e657d1d9ac8ccfa460710de204">checkAndOpenFile</a> and <a href="#a9af0795be28dcf4551e57a2a3650a552">readIncludeFile</a>.</p>

</div>
</div>

### g\_globalDefineMutex {#a41d40eee862471579482f58a442f157d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex g_globalDefineMutex</td>
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



<p>Definition at line 234 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a41d40eee862471579482f58a442f157d">234</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::mutex            <a href="#a41d40eee862471579482f58a442f157d">g_globalDefineMutex</a>;</span></span></div>

</div>


<p>Referenced by <a href="#abac7d9e657d1d9ac8ccfa460710de204">checkAndOpenFile</a> and <a href="#a9af0795be28dcf4551e57a2a3650a552">readIncludeFile</a>.</p>

</div>
</div>

### g\_updateGlobals {#abbb87735f2e6370eeb5934dc1476cd7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex g_updateGlobals</td>
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



<p>Definition at line 235 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abbb87735f2e6370eeb5934dc1476cd7b">235</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::mutex            <a href="#abbb87735f2e6370eeb5934dc1476cd7b">g_updateGlobals</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/preprocessor/#ab3f6062c1f94727e3d51963720d13417">Preprocessor::processFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### MAX\_EXPANSION\_DEPTH {#a246c42ffcd2228031eb52e0de54b60d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MAX_EXPANSION_DEPTH&nbsp;&nbsp;&nbsp;50</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2877 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a246c42ffcd2228031eb52e0de54b60d5">2879</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define MAX_EXPANSION_DEPTH 50</span></span></div>

</div>


<p>Referenced by <a href="#a1bc8b7f200b9267b0c7b842ecd1f25b0">expandExpression</a>.</p>

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



<p>Definition at line 349 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aacfdca45fa4beb8b06172525a53c424a">349</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define YY_INPUT(buf,result,max_size) result=yyread(yyscanner,buf,max_size);</span></span></div>

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



<p>Definition at line 68 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


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



<p>Definition at line 22 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5d5508008cac8fb66fca3baa4e9b6584">22</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define YY_TYPEDEF_YY_SCANNER_T</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
