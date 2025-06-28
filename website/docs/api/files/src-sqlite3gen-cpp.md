---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/sqlite3gen-cpp
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `sqlite3gen.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;stdlib.h&gt;
#include &lt;stdio.h&gt;
#include &lt;sstream&gt;
#include "settings.h"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/sqlite3gen-h">sqlite3gen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/docparser-h">docparser.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/language-h">language.h</a>"
#include "version.h"
#include "<a href="/web-doxygen/docs/api/files/src/dot-h">dot.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/classlist-h">classlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/filename-h">filename.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/pagedef-h">pagedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/section-h">section.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/fileinfo-h">fileinfo.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/datetime-h">datetime.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>"
#include &lt;sys/stat.h&gt;
#include &lt;string.h&gt;
#include &lt;sqlite3.h&gt;
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/textgeneratorsqlite3impl">TextGeneratorSqlite3Impl</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/refid">Refid</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a> (SqlStmt &amp;s, const char *name, const QCString &amp;value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a> (SqlStmt &amp;s, const char *name, int value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a> (SqlStmt &amp;s, bool getRowId=FALSE, bool select=FALSE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a> (QCString name, bool local=TRUE, bool found=TRUE, int type=1)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e33b2ef2c8bf323a8a2f1d4bb13a5ca">recordMetadata</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct <a href="/web-doxygen/docs/api/structs/refid">Refid</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a> (const QCString &amp;refid)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06d5fa6f8acbfef6705314884b6e6800">memberdefExists</a> (struct Refid refid)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a696974b4a7902e4137be55d5337d20">memberdefIncomplete</a> (struct Refid refid, const MemberDef *md)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19ff8cd8130e662be4112bc914f7b50b">compounddefExists</a> (struct Refid refid)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a204b468b29a5d8ae8cf305cc08766eb7">insertMemberReference</a> (struct Refid src_refid, struct Refid dst_refid, const char *context)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae10406df98d50bc1f5d58c0be3427202">insertMemberReference</a> (const MemberDef *src, const MemberDef *dst, const char *context)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a9064a0bd3f19c550c68c5839dec5a6">insertMemberFunctionParams</a> (int memberdef_id, const MemberDef *md, const Definition *def)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ff307313c1b28d89ef63fef3590ad36">insertMemberDefineParams</a> (int memberdef_id, const MemberDef *md, const Definition *def)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affa42bdf0b91c838fe0215b4e6afb7b5">associateMember</a> (const MemberDef *md, struct Refid member_refid, struct Refid scope_refid)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8acb7287be03115c56196dd1a1085225">stripQualifiers</a> (QCString &amp;typeStr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ee82255bd720e88690c7cac3581f1df">prepareStatement</a> (sqlite3 *db, SqlStmt &amp;s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c243ba2fe5dbbef9eae72870cb045ff">prepareStatements</a> (sqlite3 *db)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34ac47cfb391a052b41a678d475c77f2">beginTransaction</a> (sqlite3 *db)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bbbc5fdf231deaba7d34b3427583572">endTransaction</a> (sqlite3 *db)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af385f460786d8d70b91b640dc78de575">pragmaTuning</a> (sqlite3 *db)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2413f906680d7e55e863d1f4d7385a84">initializeTables</a> (sqlite3 *db)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9037481dd7efb932a1f5dc142922330">initializeViews</a> (sqlite3 *db)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b94451a3cd1a0d6cc44e2a9a2118481">writeInnerClasses</a> (const ClassLinkedRefMap &amp;cl, struct Refid outer_refid)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46ef1ad7fcb0bd63228beb9a14e7f4bd">writeInnerConcepts</a> (const ConceptLinkedRefMap &amp;cl, struct Refid outer_refid)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68dad0e13a83b4eb9046a6e6588a855f">writeInnerModules</a> (const ModuleLinkedRefMap &amp;ml, struct Refid outer_refid)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b9d2814806d6388bddc5f4c141d8fbf">writeInnerPages</a> (const PageLinkedRefMap &amp;pl, struct Refid outer_refid)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a472ea2a1d309024f061e7d48d1dd3839">writeInnerGroups</a> (const GroupList &amp;gl, struct Refid outer_refid)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e4b392824ade3c727f39d6717bdc97f">writeInnerFiles</a> (const FileList &amp;fl, struct Refid outer_refid)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1e096e657dc0a4918d8ad80ffa233a8">writeInnerDirs</a> (const DirList &amp;dl, struct Refid outer_refid)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a597b4509789d2af90e78fe008fa832ab">writeInnerNamespaces</a> (const NamespaceLinkedRefMap &amp;nl, struct Refid outer_refid)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f2bd54985a7da4e6c800829305bece1">writeTemplateArgumentList</a> (const ArgumentList &amp;al, const Definition *scope, const FileDef *fileScope)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbab9cdf5d958b7f7ac7b736428974dd">writeMemberTemplateLists</a> (const MemberDef *md)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a751d93630bc7cb9fa396ce5322fc9aab">writeTemplateList</a> (const ClassDef *cd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48aeba774bb636ba277d83e94b205291">writeTemplateList</a> (const ConceptDef *cd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a088166e0f872cd290425780f4b5c45f6">getSQLDocBlock</a> (const Definition *scope, const Definition *def, const QCString &amp;doc, const QCString &amp;fileName, int lineNr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a309fe09ee4c594f158d4e9873ca1e6b6">getSQLDesc</a> (SqlStmt &amp;s, const char *col, const QCString &amp;value, const Definition *def)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f1e96e7c65daf0f86a31c45077697c4">getSQLDescCompound</a> (SqlStmt &amp;s, const char *col, const QCString &amp;value, const Definition *def)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a> (const MemberDef *md, struct Refid scope_refid, const Definition *def)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a268c5eeaffe97a7ec76839a084b8e6fb">generateSqlite3Section</a> (const Definition *d, const MemberList *ml, struct Refid scope_refid, const char *, const QCString &amp;=QCString(), const QCString &amp;=QCString())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92be09d6ea0ae352da3d441abed04f30">associateAllClassMembers</a> (const ClassDef *cd, struct Refid scope_refid)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a> (const ClassDef *cd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3889d30b147517190ccd9c1ebb9ca785">generateSqlite3ForConcept</a> (const ConceptDef *cd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b0628c4001ddb19730a764b29b0be44">generateSqlite3ForModule</a> (const ModuleDef *mod)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5597180db00f8bb26d51d9b3b409241">generateSqlite3ForNamespace</a> (const NamespaceDef *nd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7139b08c0c942d65c6bcb8402a8b142">generateSqlite3ForFile</a> (const FileDef *fd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a> (const GroupDef *gd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96d60ce1da0cc36d049c1a2bbc174178">generateSqlite3ForDir</a> (const DirDef *dd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb4c1aeb9fc32917845d0d05a52cb478">generateSqlite3ForPage</a> (const PageDef *pd, bool isExample)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static sqlite3 *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac13e6fab478750b5fc094a78e8fcb149">openDbConnection</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5b36a2f93dadba9f8c7d762564154e1">generateSqlite3</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b91ef07fa780f5b7c37c73863df5e11">table_schema</a>[][2]</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b595d98aef36283b3ea75fdd312ed5c">view_schema</a>[][2]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac593dfdd38adfad8de3e87c2405f65b2">meta_insert</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c15b3b9b3db6bf609838c68c915d80a">incl_insert</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e3e98a7897963c61baf003aab5fecfa">incl_select</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains_insert</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8c2b376b75f41e8807c6db20df8de47">path_select</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3954473f4ed653652992317306a884b">path_insert</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af21d2af0294b7e22f02b098a43ec276d">refid_select</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f9a714e57e3f2d5b40ca9e2b5e1edf2">refid_insert</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a669c1f1c7bd2b5cfe3bc3e9294e81be9">xrefs_insert</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ef03b7de5c740c3ad04b46fee17e6e0">reimplements_insert</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5786eb5fdd727a497982eb3b0901680">memberdef_exists</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2aef529ba9a8abda7c5dbe9f9c2b183b">memberdef_incomplete</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dd6736df9437b0372601f0fc9256cdc">memberdef_update_decl</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a996b41f0018348eb70cb369999032333">memberdef_update_def</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ff598f38ef2dad027845c7abaa65592">member_insert</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a162bb86dfaf3254e93b1274353cd1cbf">compounddef_exists</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33e0611a73afb936b8c97c6812e64029">compoundref_insert</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5615e9549a34565e146c795f7879a70c">param_select</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeff7609bbf258f9fe7bb792def0251d6">param_insert</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fd0d6eb855cc81bc77248083bc52316">memberdef_param_insert</a> = ...</td>
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

</table>


<div class="doxySectionDef">

## Functions

### associateAllClassMembers() {#a92be09d6ea0ae352da3d441abed04f30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void associateAllClassMembers (const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, struct <a href="/web-doxygen/docs/api/structs/refid">Refid</a> scope_refid)</td>
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


<p>Definition at line 1898 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a92be09d6ea0ae352da3d441abed04f30">1898</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a92be09d6ea0ae352da3d441abed04f30">associateAllClassMembers</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd, </span><span class="doxyHighlightKeyword">struct</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/refid">Refid</a> scope_refid)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1899</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1900</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mni : cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ac8f58a78e8196768f3ddd17e645cf7f9">memberNameInfoLinkedMap</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1901</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1902</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mi : *mni)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1903</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1904</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md = mi-&gt;memberDef();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1905</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> qrefid = md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>() + </span><span class="doxyHighlightStringLiteral">"_1"</span><span class="doxyHighlight"> + md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1906</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#affa42bdf0b91c838fe0215b4e6afb7b5">associateMember</a>(md, <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(qrefid), scope_refid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1907</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1908</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1909</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">Definition::anchor</a>, <a href="#affa42bdf0b91c838fe0215b4e6afb7b5">associateMember</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a> and <a href="/web-doxygen/docs/api/classes/classdef/#ac8f58a78e8196768f3ddd17e645cf7f9">ClassDef::memberNameInfoLinkedMap</a>.

Referenced by <a href="#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>.
</div>
</div>

### associateMember() {#affa42bdf0b91c838fe0215b4e6afb7b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void associateMember (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md, struct <a href="/web-doxygen/docs/api/structs/refid">Refid</a> member_refid, struct <a href="/web-doxygen/docs/api/structs/refid">Refid</a> scope_refid)</td>
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


<p>Definition at line 1121 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#affa42bdf0b91c838fe0215b4e6afb7b5">1121</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#affa42bdf0b91c838fe0215b4e6afb7b5">associateMember</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md, </span><span class="doxyHighlightKeyword">struct</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/refid">Refid</a> member_refid, </span><span class="doxyHighlightKeyword">struct</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/refid">Refid</a> scope_refid)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1122</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1123</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// TODO: skip EnumValue only to guard against recording refids and member records</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1124</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// for enumvalues until we can support documenting them as entities.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1125</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">memberType</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a29785ae7827639b31b629cc7f9c150e0">MemberType::EnumValue</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1126</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8f18141678a6bf5fb86e8de29bc0f1cd">isAnonymous</a>()) </span><span class="doxyHighlightComment">// skip anonymous members</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1127</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1128</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a7ff598f38ef2dad027845c7abaa65592">member_insert</a>, </span><span class="doxyHighlightStringLiteral">":scope_rowid"</span><span class="doxyHighlight">, scope_refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1129</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a7ff598f38ef2dad027845c7abaa65592">member_insert</a>, </span><span class="doxyHighlightStringLiteral">":memberdef_rowid"</span><span class="doxyHighlight">, member_refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1130</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1131</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a7ff598f38ef2dad027845c7abaa65592">member_insert</a>, </span><span class="doxyHighlightStringLiteral">":prot"</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ab266b88c02dd8d5089b29d501b412c5d">protection</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1132</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a7ff598f38ef2dad027845c7abaa65592">member_insert</a>, </span><span class="doxyHighlightStringLiteral">":virt"</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ae450a2be776cc5d05726bab8354f6d62">virtualness</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1133</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#a7ff598f38ef2dad027845c7abaa65592">member_insert</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1134</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1135</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a29785ae7827639b31b629cc7f9c150e0">EnumValue</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8f18141678a6bf5fb86e8de29bc0f1cd">Definition::isAnonymous</a>, <a href="#a7ff598f38ef2dad027845c7abaa65592">member&#95;insert</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">MemberDef::memberType</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#ab266b88c02dd8d5089b29d501b412c5d">MemberDef::protection</a>, <a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">Refid::rowid</a>, <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a> and <a href="/web-doxygen/docs/api/classes/memberdef/#ae450a2be776cc5d05726bab8354f6d62">MemberDef::virtualness</a>.

Referenced by <a href="#a92be09d6ea0ae352da3d441abed04f30">associateAllClassMembers</a> and <a href="#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>.
</div>
</div>

### beginTransaction() {#a34ac47cfb391a052b41a678d475c77f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void beginTransaction (sqlite3 * db)</td>
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


<p>Definition at line 1194 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a34ac47cfb391a052b41a678d475c77f2">1194</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a34ac47cfb391a052b41a678d475c77f2">beginTransaction</a>(sqlite3 *db)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1195</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1196</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> * sErrMsg = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1197</span><span class="doxyLineContent"><span class="doxyHighlight">  sqlite3_exec(db, </span><span class="doxyHighlightStringLiteral">"BEGIN TRANSACTION"</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, &amp;sErrMsg);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1198</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="#ae5b36a2f93dadba9f8c7d762564154e1">generateSqlite3</a>.
</div>
</div>

### bindIntParameter() {#af69029d3e47b3f8a0515b21e6562e6d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool bindIntParameter (<a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> &amp; s, const char * name, int value)</td>
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


<p>Definition at line 877 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af69029d3e47b3f8a0515b21e6562e6d7">877</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> &amp;s,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *name,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> value)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">878</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">879</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> idx = sqlite3_bind_parameter_index(s.<a href="/web-doxygen/docs/api/structs/sqlstmt/#a780c9b733b885100df0aa733b0c66a37">stmt</a>, name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">880</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (idx==0) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">881</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"sqlite3_bind_parameter_index({})[{}] failed to find column: {}\n"</span><span class="doxyHighlight">, name, s.<a href="/web-doxygen/docs/api/structs/sqlstmt/#a0fcb633ba93d1ad47b5072781ac76bb8">query</a>, sqlite3_errmsg(s.<a href="/web-doxygen/docs/api/structs/sqlstmt/#a20465204d0f4d947d8df06808d62d3ee">db</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">882</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">883</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">884</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> rv = sqlite3_bind_int(s.<a href="/web-doxygen/docs/api/structs/sqlstmt/#a780c9b733b885100df0aa733b0c66a37">stmt</a>, idx, value);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">885</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rv!=SQLITE_OK) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">886</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"sqlite3_bind_int({})[{}] failed: {}\n"</span><span class="doxyHighlight">, name, s.<a href="/web-doxygen/docs/api/structs/sqlstmt/#a0fcb633ba93d1ad47b5072781ac76bb8">query</a>, sqlite3_errmsg(s.<a href="/web-doxygen/docs/api/structs/sqlstmt/#a20465204d0f4d947d8df06808d62d3ee">db</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">887</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">888</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">889</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">890</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/structs/sqlstmt/#a20465204d0f4d947d8df06808d62d3ee">SqlStmt::db</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/structs/sqlstmt/#a0fcb633ba93d1ad47b5072781ac76bb8">SqlStmt::query</a> and <a href="/web-doxygen/docs/api/structs/sqlstmt/#a780c9b733b885100df0aa733b0c66a37">SqlStmt::stmt</a>.

Referenced by <a href="#affa42bdf0b91c838fe0215b4e6afb7b5">associateMember</a>, <a href="#a19ff8cd8130e662be4112bc914f7b50b">compounddefExists</a>, <a href="#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>, <a href="#a3889d30b147517190ccd9c1ebb9ca785">generateSqlite3ForConcept</a>, <a href="#a96d60ce1da0cc36d049c1a2bbc174178">generateSqlite3ForDir</a>, <a href="#ae7139b08c0c942d65c6bcb8402a8b142">generateSqlite3ForFile</a>, <a href="#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a>, <a href="#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="#a2b0628c4001ddb19730a764b29b0be44">generateSqlite3ForModule</a>, <a href="#ad5597180db00f8bb26d51d9b3b409241">generateSqlite3ForNamespace</a>, <a href="#aeb4c1aeb9fc32917845d0d05a52cb478">generateSqlite3ForPage</a>, <a href="#a6ff307313c1b28d89ef63fef3590ad36">insertMemberDefineParams</a>, <a href="#a3a9064a0bd3f19c550c68c5839dec5a6">insertMemberFunctionParams</a>, <a href="#a204b468b29a5d8ae8cf305cc08766eb7">insertMemberReference</a>, <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>, <a href="#a06d5fa6f8acbfef6705314884b6e6800">memberdefExists</a>, <a href="#a2a696974b4a7902e4137be55d5337d20">memberdefIncomplete</a>, <a href="#a3b94451a3cd1a0d6cc44e2a9a2118481">writeInnerClasses</a>, <a href="#a46ef1ad7fcb0bd63228beb9a14e7f4bd">writeInnerConcepts</a>, <a href="#ad1e096e657dc0a4918d8ad80ffa233a8">writeInnerDirs</a>, <a href="#a9e4b392824ade3c727f39d6717bdc97f">writeInnerFiles</a>, <a href="#a472ea2a1d309024f061e7d48d1dd3839">writeInnerGroups</a>, <a href="#a68dad0e13a83b4eb9046a6e6588a855f">writeInnerModules</a>, <a href="#a597b4509789d2af90e78fe008fa832ab">writeInnerNamespaces</a> and <a href="#a4b9d2814806d6388bddc5f4c141d8fbf">writeInnerPages</a>.
</div>
</div>

### bindTextParameter() {#a31980a5e7ccfb3be84828d1c106c4d1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool bindTextParameter (<a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> &amp; s, const char * name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; value)</td>
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


<p>Definition at line 862 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a31980a5e7ccfb3be84828d1c106c4d1a">862</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> &amp;s,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *name,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;value)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">863</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">864</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> idx = sqlite3_bind_parameter_index(s.<a href="/web-doxygen/docs/api/structs/sqlstmt/#a780c9b733b885100df0aa733b0c66a37">stmt</a>, name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">865</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (idx==0) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">866</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"sqlite3_bind_parameter_index({})[{}] failed: {}\n"</span><span class="doxyHighlight">, name, s.<a href="/web-doxygen/docs/api/structs/sqlstmt/#a0fcb633ba93d1ad47b5072781ac76bb8">query</a>, sqlite3_errmsg(s.<a href="/web-doxygen/docs/api/structs/sqlstmt/#a20465204d0f4d947d8df06808d62d3ee">db</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">867</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">868</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">869</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> rv = sqlite3_bind_text(s.<a href="/web-doxygen/docs/api/structs/sqlstmt/#a780c9b733b885100df0aa733b0c66a37">stmt</a>, idx, value.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(), -1, SQLITE_TRANSIENT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">870</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rv!=SQLITE_OK) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">871</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"sqlite3_bind_text({})[{}] failed: {}\n"</span><span class="doxyHighlight">, name, s.<a href="/web-doxygen/docs/api/structs/sqlstmt/#a0fcb633ba93d1ad47b5072781ac76bb8">query</a>, sqlite3_errmsg(s.<a href="/web-doxygen/docs/api/structs/sqlstmt/#a20465204d0f4d947d8df06808d62d3ee">db</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">872</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">873</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">874</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">875</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/structs/sqlstmt/#a20465204d0f4d947d8df06808d62d3ee">SqlStmt::db</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/structs/sqlstmt/#a0fcb633ba93d1ad47b5072781ac76bb8">SqlStmt::query</a> and <a href="/web-doxygen/docs/api/structs/sqlstmt/#a780c9b733b885100df0aa733b0c66a37">SqlStmt::stmt</a>.

Referenced by <a href="#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>, <a href="#a3889d30b147517190ccd9c1ebb9ca785">generateSqlite3ForConcept</a>, <a href="#a96d60ce1da0cc36d049c1a2bbc174178">generateSqlite3ForDir</a>, <a href="#ae7139b08c0c942d65c6bcb8402a8b142">generateSqlite3ForFile</a>, <a href="#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a>, <a href="#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="#a2b0628c4001ddb19730a764b29b0be44">generateSqlite3ForModule</a>, <a href="#ad5597180db00f8bb26d51d9b3b409241">generateSqlite3ForNamespace</a>, <a href="#aeb4c1aeb9fc32917845d0d05a52cb478">generateSqlite3ForPage</a>, <a href="#a309fe09ee4c594f158d4e9873ca1e6b6">getSQLDesc</a>, <a href="#a4f1e96e7c65daf0f86a31c45077697c4">getSQLDescCompound</a>, <a href="#a6ff307313c1b28d89ef63fef3590ad36">insertMemberDefineParams</a>, <a href="#a3a9064a0bd3f19c550c68c5839dec5a6">insertMemberFunctionParams</a>, <a href="#a204b468b29a5d8ae8cf305cc08766eb7">insertMemberReference</a>, <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>, <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>, <a href="#a0e33b2ef2c8bf323a8a2f1d4bb13a5ca">recordMetadata</a> and <a href="#a8f2bd54985a7da4e6c800829305bece1">writeTemplateArgumentList</a>.
</div>
</div>

### compounddefExists() {#a19ff8cd8130e662be4112bc914f7b50b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool compounddefExists (struct <a href="/web-doxygen/docs/api/structs/refid">Refid</a> refid)</td>
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


<p>Definition at line 983 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a19ff8cd8130e662be4112bc914f7b50b">983</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a19ff8cd8130e662be4112bc914f7b50b">compounddefExists</a>(</span><span class="doxyHighlightKeyword">struct</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/refid">Refid</a> <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">984</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">985</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a162bb86dfaf3254e93b1274353cd1cbf">compounddef_exists</a>,</span><span class="doxyHighlightStringLiteral">":rowid"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>.rowid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">986</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> test = <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#a162bb86dfaf3254e93b1274353cd1cbf">compounddef_exists</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">987</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> test ? true : </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">988</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>, <a href="#a162bb86dfaf3254e93b1274353cd1cbf">compounddef&#95;exists</a>, <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">Refid::refid</a>, <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>, <a href="#a3889d30b147517190ccd9c1ebb9ca785">generateSqlite3ForConcept</a>, <a href="#a96d60ce1da0cc36d049c1a2bbc174178">generateSqlite3ForDir</a>, <a href="#ae7139b08c0c942d65c6bcb8402a8b142">generateSqlite3ForFile</a>, <a href="#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a>, <a href="#a2b0628c4001ddb19730a764b29b0be44">generateSqlite3ForModule</a>, <a href="#ad5597180db00f8bb26d51d9b3b409241">generateSqlite3ForNamespace</a> and <a href="#aeb4c1aeb9fc32917845d0d05a52cb478">generateSqlite3ForPage</a>.
</div>
</div>

### endTransaction() {#a7bbbc5fdf231deaba7d34b3427583572}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void endTransaction (sqlite3 * db)</td>
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


<p>Definition at line 1200 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7bbbc5fdf231deaba7d34b3427583572">1200</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7bbbc5fdf231deaba7d34b3427583572">endTransaction</a>(sqlite3 *db)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1201</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1202</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> * sErrMsg = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1203</span><span class="doxyLineContent"><span class="doxyHighlight">  sqlite3_exec(db, </span><span class="doxyHighlightStringLiteral">"END TRANSACTION"</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, &amp;sErrMsg);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1204</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="#ae5b36a2f93dadba9f8c7d762564154e1">generateSqlite3</a>.
</div>
</div>

### generateSqlite3() {#ae5b36a2f93dadba9f8c7d762564154e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void generateSqlite3 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 2587 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae5b36a2f93dadba9f8c7d762564154e1">2587</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae5b36a2f93dadba9f8c7d762564154e1">generateSqlite3</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2588</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2589</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2590</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + namespaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2591</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + files</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2592</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + groups</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2593</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + related pages</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2594</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + examples</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2595</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + main page</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2596</span><span class="doxyLineContent"><span class="doxyHighlight">  sqlite3 *db = <a href="#ac13e6fab478750b5fc094a78e8fcb149">openDbConnection</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2597</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (db==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2598</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2599</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2600</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2601</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2602</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor"># ifdef SQLITE3_DEBUG</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2603</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// debug: show all executed statements</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2604</span><span class="doxyLineContent"><span class="doxyHighlight">  sqlite3_trace(db, &amp;sqlLog, </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2605</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor"># endif</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2606</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2607</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a34ac47cfb391a052b41a678d475c77f2">beginTransaction</a>(db);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2608</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af385f460786d8d70b91b640dc78de575">pragmaTuning</a>(db);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2609</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2610</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (-1==<a href="#a2413f906680d7e55e863d1f4d7385a84">initializeTables</a>(db))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2611</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2612</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2613</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( -1 == <a href="#a5c243ba2fe5dbbef9eae72870cb045ff">prepareStatements</a>(db) )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2614</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2615</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"sqlite generator: prepareStatements failed!\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2616</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2617</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2618</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2619</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0e33b2ef2c8bf323a8a2f1d4bb13a5ca">recordMetadata</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2620</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2621</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2622</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cd : *<a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2623</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2624</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Generating Sqlite3 output for class {}\n"</span><span class="doxyHighlight">,cd-&gt;name());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2625</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>(cd.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2626</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2627</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2628</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + concepts</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2629</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cd : *<a href="/web-doxygen/docs/api/classes/doxygen/#a0de9b52b3098ea1a4bee5e248e8287c8">Doxygen::conceptLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2630</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2631</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Generating Sqlite3 output for concept {}\n"</span><span class="doxyHighlight">,cd-&gt;name());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2632</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a3889d30b147517190ccd9c1ebb9ca785">generateSqlite3ForConcept</a>(cd.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2633</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2634</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2635</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + modules</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2636</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mod : <a href="/web-doxygen/docs/api/classes/modulemanager/#a4f48cf5d05907a6acc4b9c6ddec752b7">ModuleManager::instance</a>().modules())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2637</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2638</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Generating Sqlite3 output for module {}\n"</span><span class="doxyHighlight">,mod-&gt;name());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2639</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a2b0628c4001ddb19730a764b29b0be44">generateSqlite3ForModule</a>(mod.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2640</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2641</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2642</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + namespaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2643</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;nd : *<a href="/web-doxygen/docs/api/classes/doxygen/#a033b4829afda05c5eef5cd54749b19bf">Doxygen::namespaceLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2644</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2645</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Generating Sqlite3 output for namespace {}\n"</span><span class="doxyHighlight">,nd-&gt;name());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2646</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad5597180db00f8bb26d51d9b3b409241">generateSqlite3ForNamespace</a>(nd.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2647</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2648</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2649</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + files</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2650</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;fn : *<a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2651</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2652</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;fd : *fn)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2653</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2654</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Generating Sqlite3 output for file {}\n"</span><span class="doxyHighlight">,fd-&gt;name());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2655</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ae7139b08c0c942d65c6bcb8402a8b142">generateSqlite3ForFile</a>(fd.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2656</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2657</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2658</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2659</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + groups</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2660</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;gd : *<a href="/web-doxygen/docs/api/classes/doxygen/#afd89d49084b42d085e9d40fc2636da9c">Doxygen::groupLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2661</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2662</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Generating Sqlite3 output for group {}\n"</span><span class="doxyHighlight">,gd-&gt;name());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2663</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a>(gd.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2664</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2665</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2666</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + page</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2667</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;pd : *<a href="/web-doxygen/docs/api/classes/doxygen/#abd2756663a014ee48e1660d32a48cac5">Doxygen::pageLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2668</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2669</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Generating Sqlite3 output for page {}\n"</span><span class="doxyHighlight">,pd-&gt;name());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2670</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aeb4c1aeb9fc32917845d0d05a52cb478">generateSqlite3ForPage</a>(pd.get(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2671</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2672</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2673</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + dirs</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2674</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;dd : *<a href="/web-doxygen/docs/api/classes/doxygen/#ad179803c33ab064adfd6adf681a0a805">Doxygen::dirLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2675</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2676</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Generating Sqlite3 output for dir {}\n"</span><span class="doxyHighlight">,dd-&gt;name());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2677</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a96d60ce1da0cc36d049c1a2bbc174178">generateSqlite3ForDir</a>(dd.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2678</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2679</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2680</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + examples</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2681</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;pd : *<a href="/web-doxygen/docs/api/classes/doxygen/#a6cfac206c42a62e6e3ba66d5d4e4a471">Doxygen::exampleLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2682</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2683</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Generating Sqlite3 output for example {}\n"</span><span class="doxyHighlight">,pd-&gt;name());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2684</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aeb4c1aeb9fc32917845d0d05a52cb478">generateSqlite3ForPage</a>(pd.get(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2685</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2686</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2687</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + main page</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2688</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/doxygen/#a2cc3616eca3e3c550a211d8b1eaf4661">Doxygen::mainPage</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2689</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2690</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Generating Sqlite3 output for the main page\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2691</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aeb4c1aeb9fc32917845d0d05a52cb478">generateSqlite3ForPage</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#a2cc3616eca3e3c550a211d8b1eaf4661">Doxygen::mainPage</a>.get(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2692</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2693</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2694</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// TODO: copied from initializeSchema; not certain if we should say/do more</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2695</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// if there's a failure here?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2696</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (-1==<a href="#aa9037481dd7efb932a1f5dc142922330">initializeViews</a>(db))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2697</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2698</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2699</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7bbbc5fdf231deaba7d34b3427583572">endTransaction</a>(db);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2700</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a34ac47cfb391a052b41a678d475c77f2">beginTransaction</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a0de9b52b3098ea1a4bee5e248e8287c8">Doxygen::conceptLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#ad179803c33ab064adfd6adf681a0a805">Doxygen::dirLinkedMap</a>, <a href="#a7bbbc5fdf231deaba7d34b3427583572">endTransaction</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a6cfac206c42a62e6e3ba66d5d4e4a471">Doxygen::exampleLinkedMap</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>, <a href="#a3889d30b147517190ccd9c1ebb9ca785">generateSqlite3ForConcept</a>, <a href="#a96d60ce1da0cc36d049c1a2bbc174178">generateSqlite3ForDir</a>, <a href="#ae7139b08c0c942d65c6bcb8402a8b142">generateSqlite3ForFile</a>, <a href="#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a>, <a href="#a2b0628c4001ddb19730a764b29b0be44">generateSqlite3ForModule</a>, <a href="#ad5597180db00f8bb26d51d9b3b409241">generateSqlite3ForNamespace</a>, <a href="#aeb4c1aeb9fc32917845d0d05a52cb478">generateSqlite3ForPage</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#afd89d49084b42d085e9d40fc2636da9c">Doxygen::groupLinkedMap</a>, <a href="#a2413f906680d7e55e863d1f4d7385a84">initializeTables</a>, <a href="#aa9037481dd7efb932a1f5dc142922330">initializeViews</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a4f48cf5d05907a6acc4b9c6ddec752b7">ModuleManager::instance</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a2cc3616eca3e3c550a211d8b1eaf4661">Doxygen::mainPage</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a033b4829afda05c5eef5cd54749b19bf">Doxygen::namespaceLinkedMap</a>, <a href="#ac13e6fab478750b5fc094a78e8fcb149">openDbConnection</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#abd2756663a014ee48e1660d32a48cac5">Doxygen::pageLinkedMap</a>, <a href="#af385f460786d8d70b91b640dc78de575">pragmaTuning</a>, <a href="#a5c243ba2fe5dbbef9eae72870cb045ff">prepareStatements</a>, <a href="#a0e33b2ef2c8bf323a8a2f1d4bb13a5ca">recordMetadata</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>.
</div>
</div>

### generateSqlite3ForClass() {#ac7b3f73c86e8a751ed2fd61e9d0cc2e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void generateSqlite3ForClass (const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd)</td>
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


<p>Definition at line 1914 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">1914</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1915</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1916</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// NOTE: Skeptical about XML's version of these</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1917</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// 'x' marks missing items XML claims to include</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1918</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1919</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + brief description</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1920</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + detailed description</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1921</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + template argument list(s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1922</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + include file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1923</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + member groups</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1924</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// x inheritance DOT diagram</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1925</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + list of direct super classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1926</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + list of direct sub classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1927</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + list of inner classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1928</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// x collaboration DOT diagram</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1929</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + list of all members</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1930</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// x user defined member sections</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1931</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// x standard member sections</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1932</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// x detailed member documentation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1933</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - examples using the class</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1934</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1935</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>())        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// skip external references.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1936</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a930740d353cfe143eb9efe0d12b7f938">isHidden</a>())           </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// skip hidden classes.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1937</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8f18141678a6bf5fb86e8de29bc0f1cd">isAnonymous</a>())        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// skip anonymous compounds.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1938</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ad03b3f6196640021e3c44d7b1eb9e924">isImplicitTemplateInstance</a>())  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// skip generated template instances.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1939</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1940</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a> = <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1941</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1942</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// can omit a class that already has a refid</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1943</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">(!<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>.created &amp;&amp; <a href="#a19ff8cd8130e662be4112bc914f7b50b">compounddefExists</a>(<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>)){</span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1944</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1945</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":rowid"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>.rowid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1946</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1947</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":name"</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1948</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":title"</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#afb51998523ff484408b2a96fd4f3fced">title</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1949</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":kind"</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a239fe977638806153345cd2411c28062">compoundTypeString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1950</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":prot"</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a759c68ae0af03a49aff1a86d383af68d">protection</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1951</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1952</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> file_id = <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>(cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1953</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":file_id"</span><span class="doxyHighlight">,file_id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1954</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":line"</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1955</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":column"</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#adf0e1ff0eec62741a8ee5d768589ab01">getDefColumn</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1956</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1957</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + include file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1958</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/*</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1959</span><span class="doxyLineContent"><span class="doxyHighlightComment">  TODO: I wonder if this can actually be cut (just here)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1960</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1961</span><span class="doxyLineContent"><span class="doxyHighlightComment">  We were adding this "include" to the "includes" table alongside</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1962</span><span class="doxyLineContent"><span class="doxyHighlightComment">  other includes (from a FileDef). However, FileDef and ClassDef are using</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1963</span><span class="doxyLineContent"><span class="doxyHighlightComment">  "includes" nodes in very a different way:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1964</span><span class="doxyLineContent"><span class="doxyHighlightComment">  - With FileDef, it means the file includes another.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1965</span><span class="doxyLineContent"><span class="doxyHighlightComment">  - With ClassDef, it means you should include this file to use this class.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1966</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1967</span><span class="doxyLineContent"><span class="doxyHighlightComment">  Because of this difference, I added a column to compounddef, header_id, and</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1968</span><span class="doxyLineContent"><span class="doxyHighlightComment">  linked it back to the appropriate file. We could just add a nullable text</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1969</span><span class="doxyLineContent"><span class="doxyHighlightComment">  column that would hold a string equivalent to what the HTML docs include,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1970</span><span class="doxyLineContent"><span class="doxyHighlightComment">  but the logic for generating it is embedded in</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1971</span><span class="doxyLineContent"><span class="doxyHighlightComment">  ClassDef::writeIncludeFiles(OutputList &amp;ol).</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1972</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1973</span><span class="doxyLineContent"><span class="doxyHighlightComment">  That said, at least on the handful of test sets I have, header_id == file_id,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1974</span><span class="doxyLineContent"><span class="doxyHighlightComment">  suggesting it could be cut and clients might be able to reconstruct it from</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1975</span><span class="doxyLineContent"><span class="doxyHighlightComment">  other values if there's a solid heuristic for *when a class will</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1976</span><span class="doxyLineContent"><span class="doxyHighlightComment">  have a header file*.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1977</span><span class="doxyLineContent"><span class="doxyHighlightComment">  */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1978</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/includeinfo">IncludeInfo</a> *ii=cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#af0c57a31c5cbef35d12de99e88745f66">includeInfo</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1979</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ii)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1980</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1981</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> nm = ii-&gt;<a href="/web-doxygen/docs/api/structs/includeinfo/#a0f8b77f07d748ea1612db5d4c47c5c37">includeName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1982</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nm.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; ii-&gt;<a href="/web-doxygen/docs/api/structs/includeinfo/#ac9ea4d136292663b672a8aeec5944548">fileDef</a>) nm = ii-&gt;<a href="/web-doxygen/docs/api/structs/includeinfo/#ac9ea4d136292663b672a8aeec5944548">fileDef</a>-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#ad7d5e7ac753d7247cfaad5be9ea3eaec">docName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1983</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!nm.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1984</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1985</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> header_id=-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1986</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ii-&gt;<a href="/web-doxygen/docs/api/structs/includeinfo/#ac9ea4d136292663b672a8aeec5944548">fileDef</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1987</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1988</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>(ii-&gt;<a href="/web-doxygen/docs/api/structs/includeinfo/#ac9ea4d136292663b672a8aeec5944548">fileDef</a>-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">absFilePath</a>(),!ii-&gt;<a href="/web-doxygen/docs/api/structs/includeinfo/#ac9ea4d136292663b672a8aeec5944548">fileDef</a>-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1989</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1990</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((</span><span class="doxyHighlightStringLiteral">"-----&gt; ClassDef includeInfo for %s\n"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(nm)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1991</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((</span><span class="doxyHighlightStringLiteral">"       local    : %d\n"</span><span class="doxyHighlight">, ii-&gt;local));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1992</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((</span><span class="doxyHighlightStringLiteral">"       imported : %d\n"</span><span class="doxyHighlight">, ii-&gt;imported));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1993</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ii-&gt;<a href="/web-doxygen/docs/api/structs/includeinfo/#ac9ea4d136292663b672a8aeec5944548">fileDef</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1994</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1995</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((</span><span class="doxyHighlightStringLiteral">"header: %s\n"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(ii-&gt;<a href="/web-doxygen/docs/api/structs/includeinfo/#ac9ea4d136292663b672a8aeec5944548">fileDef</a>-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">absFilePath</a>())));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1996</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1997</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((</span><span class="doxyHighlightStringLiteral">"       file_id  : %d\n"</span><span class="doxyHighlight">, file_id));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1998</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((</span><span class="doxyHighlightStringLiteral">"       header_id: %d\n"</span><span class="doxyHighlight">, header_id));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1999</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2000</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">(header_id!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2001</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2002</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":header_id"</span><span class="doxyHighlight">,header_id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2003</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2004</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2005</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2006</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2007</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4f1e96e7c65daf0f86a31c45077697c4">getSQLDescCompound</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":briefdescription"</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>(),cd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2008</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4f1e96e7c65daf0f86a31c45077697c4">getSQLDescCompound</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":detaileddescription"</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>(),cd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2009</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2010</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2011</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2012</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + list of direct super classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2013</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;bcd : cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a38001a11a297629e363c0db5b1968ab3">baseClasses</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2014</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2015</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> base_refid = <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(bcd.classDef-&gt;getOutputFileBase());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2016</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> derived_refid = <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2017</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a33e0611a73afb936b8c97c6812e64029">compoundref_insert</a>,</span><span class="doxyHighlightStringLiteral">":base_rowid"</span><span class="doxyHighlight">, base_refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2018</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a33e0611a73afb936b8c97c6812e64029">compoundref_insert</a>,</span><span class="doxyHighlightStringLiteral">":derived_rowid"</span><span class="doxyHighlight">, derived_refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2019</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a33e0611a73afb936b8c97c6812e64029">compoundref_insert</a>,</span><span class="doxyHighlightStringLiteral">":prot"</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(bcd.prot));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2020</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a33e0611a73afb936b8c97c6812e64029">compoundref_insert</a>,</span><span class="doxyHighlightStringLiteral">":virt"</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(bcd.virt));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2021</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#a33e0611a73afb936b8c97c6812e64029">compoundref_insert</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2022</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2023</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2024</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + list of direct sub classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2025</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;bcd : cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#afdeec11149bf831c4c6dd297f7c4e34d">subClasses</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2026</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2027</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> derived_refid = <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(bcd.classDef-&gt;getOutputFileBase());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2028</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> base_refid = <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2029</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a33e0611a73afb936b8c97c6812e64029">compoundref_insert</a>,</span><span class="doxyHighlightStringLiteral">":base_rowid"</span><span class="doxyHighlight">, base_refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2030</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a33e0611a73afb936b8c97c6812e64029">compoundref_insert</a>,</span><span class="doxyHighlightStringLiteral">":derived_rowid"</span><span class="doxyHighlight">, derived_refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2031</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a33e0611a73afb936b8c97c6812e64029">compoundref_insert</a>,</span><span class="doxyHighlightStringLiteral">":prot"</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(bcd.prot));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2032</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a33e0611a73afb936b8c97c6812e64029">compoundref_insert</a>,</span><span class="doxyHighlightStringLiteral">":virt"</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(bcd.virt));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2033</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#a33e0611a73afb936b8c97c6812e64029">compoundref_insert</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2034</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2035</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2036</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + list of inner classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2037</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a3b94451a3cd1a0d6cc44e2a9a2118481">writeInnerClasses</a>(cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#aeb64dc8f57c5d07f1b1d55bc560a7004">getClasses</a>(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2038</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2039</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + template argument list(s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2040</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a751d93630bc7cb9fa396ce5322fc9aab">writeTemplateList</a>(cd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2041</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2042</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + member groups</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2043</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mg : cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#add2c3b56273ce664bbaeb0ce1c8f420c">getMemberGroups</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2044</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2045</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a268c5eeaffe97a7ec76839a084b8e6fb">generateSqlite3Section</a>(cd,&amp;mg-&gt;members(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>,</span><span class="doxyHighlightStringLiteral">"user-defined"</span><span class="doxyHighlight">,mg-&gt;header(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2046</span><span class="doxyLineContent"><span class="doxyHighlight">        mg-&gt;documentation());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2047</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2048</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2049</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// this is just a list of *local* members</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2050</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ml : cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a283e841b3eb34d0ba2e0e106a4e3ad59">getMemberLists</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2051</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2052</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ml-&gt;<a href="/web-doxygen/docs/api/classes/memberlist/#aa31a7d651481862036f72381f7e2a96d">listType</a>().<a href="/web-doxygen/docs/api/classes/memberlisttype/#a58f94802953a4bc845068c864d42d76e">isDetailed</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2053</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2054</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a268c5eeaffe97a7ec76839a084b8e6fb">generateSqlite3Section</a>(cd,ml.get(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>,</span><span class="doxyHighlightStringLiteral">"user-defined"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2055</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2056</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2057</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2058</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + list of all members</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2059</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a92be09d6ea0ae352da3d441abed04f30">associateAllClassMembers</a>(cd, <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2060</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">FileDef::absFilePath</a>, <a href="#a92be09d6ea0ae352da3d441abed04f30">associateAllClassMembers</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a38001a11a297629e363c0db5b1968ab3">ClassDef::baseClasses</a>, <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>, <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">Definition::briefDescription</a>, <a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef&#95;insert</a>, <a href="#a19ff8cd8130e662be4112bc914f7b50b">compounddefExists</a>, <a href="#a33e0611a73afb936b8c97c6812e64029">compoundref&#95;insert</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a239fe977638806153345cd2411c28062">ClassDef::compoundTypeString</a>, <a href="#a234e2efe67eececd88b140b46ea37463">DBG&#95;CTX</a>, <a href="/web-doxygen/docs/api/classes/filedef/#ad7d5e7ac753d7247cfaad5be9ea3eaec">FileDef::docName</a>, <a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">Definition::documentation</a>, <a href="/web-doxygen/docs/api/structs/includeinfo/#ac9ea4d136292663b672a8aeec5944548">IncludeInfo::fileDef</a>, <a href="#a268c5eeaffe97a7ec76839a084b8e6fb">generateSqlite3Section</a>, <a href="/web-doxygen/docs/api/classes/classdef/#aeb64dc8f57c5d07f1b1d55bc560a7004">ClassDef::getClasses</a>, <a href="/web-doxygen/docs/api/classes/definition/#adf0e1ff0eec62741a8ee5d768589ab01">Definition::getDefColumn</a>, <a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">Definition::getDefFileName</a>, <a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">Definition::getDefLine</a>, <a href="/web-doxygen/docs/api/classes/classdef/#add2c3b56273ce664bbaeb0ce1c8f420c">ClassDef::getMemberGroups</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a283e841b3eb34d0ba2e0e106a4e3ad59">ClassDef::getMemberLists</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="#a4f1e96e7c65daf0f86a31c45077697c4">getSQLDescCompound</a>, <a href="/web-doxygen/docs/api/classes/classdef/#af0c57a31c5cbef35d12de99e88745f66">ClassDef::includeInfo</a>, <a href="/web-doxygen/docs/api/structs/includeinfo/#a0f8b77f07d748ea1612db5d4c47c5c37">IncludeInfo::includeName</a>, <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>, <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8f18141678a6bf5fb86e8de29bc0f1cd">Definition::isAnonymous</a>, <a href="/web-doxygen/docs/api/classes/memberlisttype/#a58f94802953a4bc845068c864d42d76e">MemberListType::isDetailed</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/definition/#a930740d353cfe143eb9efe0d12b7f938">Definition::isHidden</a>, <a href="/web-doxygen/docs/api/classes/classdef/#ad03b3f6196640021e3c44d7b1eb9e924">ClassDef::isImplicitTemplateInstance</a>, <a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">Definition::isReference</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#aa31a7d651481862036f72381f7e2a96d">MemberList::listType</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a759c68ae0af03a49aff1a86d383af68d">ClassDef::protection</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>, <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">Refid::refid</a>, <a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">Refid::rowid</a>, <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>, <a href="/web-doxygen/docs/api/classes/classdef/#afdeec11149bf831c4c6dd297f7c4e34d">ClassDef::subClasses</a>, <a href="/web-doxygen/docs/api/classes/classdef/#afb51998523ff484408b2a96fd4f3fced">ClassDef::title</a>, <a href="#a3b94451a3cd1a0d6cc44e2a9a2118481">writeInnerClasses</a> and <a href="#a751d93630bc7cb9fa396ce5322fc9aab">writeTemplateList</a>.

Referenced by <a href="#ae5b36a2f93dadba9f8c7d762564154e1">generateSqlite3</a>.
</div>
</div>

### generateSqlite3ForConcept() {#a3889d30b147517190ccd9c1ebb9ca785}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void generateSqlite3ForConcept (const <a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a> * cd)</td>
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


<p>Definition at line 2062 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3889d30b147517190ccd9c1ebb9ca785">2062</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3889d30b147517190ccd9c1ebb9ca785">generateSqlite3ForConcept</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a> *cd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2063</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2064</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>() || cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a930740d353cfe143eb9efe0d12b7f938">isHidden</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// skip external references</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2065</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2066</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a> = <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2067</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">(!<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>.created &amp;&amp; <a href="#a19ff8cd8130e662be4112bc914f7b50b">compounddefExists</a>(<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>)){</span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2068</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":rowid"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>.rowid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2069</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":name"</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2070</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":kind"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"concept"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2071</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2072</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> file_id = <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>(cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2073</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":file_id"</span><span class="doxyHighlight">,file_id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2074</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":line"</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2075</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":column"</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#adf0e1ff0eec62741a8ee5d768589ab01">getDefColumn</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2076</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2077</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4f1e96e7c65daf0f86a31c45077697c4">getSQLDescCompound</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":briefdescription"</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>(),cd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2078</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4f1e96e7c65daf0f86a31c45077697c4">getSQLDescCompound</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":detaileddescription"</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>(),cd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2079</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2080</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2081</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2082</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + template argument list(s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2083</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a751d93630bc7cb9fa396ce5322fc9aab">writeTemplateList</a>(cd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2084</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>, <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">Definition::briefDescription</a>, <a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef&#95;insert</a>, <a href="#a19ff8cd8130e662be4112bc914f7b50b">compounddefExists</a>, <a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">Definition::documentation</a>, <a href="/web-doxygen/docs/api/classes/definition/#adf0e1ff0eec62741a8ee5d768589ab01">Definition::getDefColumn</a>, <a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">Definition::getDefFileName</a>, <a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">Definition::getDefLine</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="#a4f1e96e7c65daf0f86a31c45077697c4">getSQLDescCompound</a>, <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>, <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>, <a href="/web-doxygen/docs/api/classes/definition/#a930740d353cfe143eb9efe0d12b7f938">Definition::isHidden</a>, <a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">Definition::isReference</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">Refid::refid</a>, <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a> and <a href="#a751d93630bc7cb9fa396ce5322fc9aab">writeTemplateList</a>.

Referenced by <a href="#ae5b36a2f93dadba9f8c7d762564154e1">generateSqlite3</a>.
</div>
</div>

### generateSqlite3ForDir() {#a96d60ce1da0cc36d049c1a2bbc174178}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void generateSqlite3ForDir (const <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> * dd)</td>
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


<p>Definition at line 2423 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a96d60ce1da0cc36d049c1a2bbc174178">2423</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a96d60ce1da0cc36d049c1a2bbc174178">generateSqlite3ForDir</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> *dd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2424</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2425</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + dirs</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2426</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + files</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2427</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + briefdescription</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2428</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + detaileddescription</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2429</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + location (below uses file_id, line, column; XML just uses file)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2430</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (dd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// skip external references</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2431</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2432</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a> = <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(dd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2433</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">(!<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>.created &amp;&amp; <a href="#a19ff8cd8130e662be4112bc914f7b50b">compounddefExists</a>(<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>)){</span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2434</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":rowid"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>.rowid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2435</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2436</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":name"</span><span class="doxyHighlight">,dd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac4741f70f06baac174cf71b3e11d06ac">displayName</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2437</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":kind"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"dir"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2438</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2439</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> file_id = <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>(dd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2440</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":file_id"</span><span class="doxyHighlight">,file_id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2441</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2442</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/*</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2443</span><span class="doxyLineContent"><span class="doxyHighlightComment">  line and column are weird here, but:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2444</span><span class="doxyLineContent"><span class="doxyHighlightComment">  - dir goes into compounddef with all of the others</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2445</span><span class="doxyLineContent"><span class="doxyHighlightComment">  - the semantics would be fine if we set them to NULL here</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2446</span><span class="doxyLineContent"><span class="doxyHighlightComment">  - but defining line and column as NOT NULL is an important promise</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2447</span><span class="doxyLineContent"><span class="doxyHighlightComment">    for other compounds, so I don't want to loosen it</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2448</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2449</span><span class="doxyLineContent"><span class="doxyHighlightComment">  For reference, the queries return 1</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2450</span><span class="doxyLineContent"><span class="doxyHighlightComment">  0 or -1 make more sense, but I see that as a change for DirDef.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2451</span><span class="doxyLineContent"><span class="doxyHighlightComment">  */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2452</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":line"</span><span class="doxyHighlight">,dd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2453</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":column"</span><span class="doxyHighlight">,dd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#adf0e1ff0eec62741a8ee5d768589ab01">getDefColumn</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2454</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2455</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a309fe09ee4c594f158d4e9873ca1e6b6">getSQLDesc</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":briefdescription"</span><span class="doxyHighlight">,dd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>(),dd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2456</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a309fe09ee4c594f158d4e9873ca1e6b6">getSQLDesc</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":detaileddescription"</span><span class="doxyHighlight">,dd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>(),dd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2457</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2458</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2459</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2460</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + files</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2461</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad1e096e657dc0a4918d8ad80ffa233a8">writeInnerDirs</a>(dd-&gt;<a href="/web-doxygen/docs/api/classes/dirdef/#abc75cce4fc67690a3ebbd158e3d63938">subDirs</a>(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2462</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2463</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + files</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2464</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a9e4b392824ade3c727f39d6717bdc97f">writeInnerFiles</a>(dd-&gt;<a href="/web-doxygen/docs/api/classes/dirdef/#af40b99e4906aef816aa768682712df74">getFiles</a>(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2465</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>, <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">Definition::briefDescription</a>, <a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef&#95;insert</a>, <a href="#a19ff8cd8130e662be4112bc914f7b50b">compounddefExists</a>, <a href="/web-doxygen/docs/api/classes/definition/#ac4741f70f06baac174cf71b3e11d06ac">Definition::displayName</a>, <a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">Definition::documentation</a>, <a href="/web-doxygen/docs/api/classes/definition/#adf0e1ff0eec62741a8ee5d768589ab01">Definition::getDefColumn</a>, <a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">Definition::getDefFileName</a>, <a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">Definition::getDefLine</a>, <a href="/web-doxygen/docs/api/classes/dirdef/#af40b99e4906aef816aa768682712df74">DirDef::getFiles</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="#a309fe09ee4c594f158d4e9873ca1e6b6">getSQLDesc</a>, <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>, <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>, <a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">Definition::isReference</a>, <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">Refid::refid</a>, <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>, <a href="/web-doxygen/docs/api/classes/dirdef/#abc75cce4fc67690a3ebbd158e3d63938">DirDef::subDirs</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="#ad1e096e657dc0a4918d8ad80ffa233a8">writeInnerDirs</a> and <a href="#a9e4b392824ade3c727f39d6717bdc97f">writeInnerFiles</a>.

Referenced by <a href="#ae5b36a2f93dadba9f8c7d762564154e1">generateSqlite3</a>.
</div>
</div>

### generateSqlite3ForFile() {#ae7139b08c0c942d65c6bcb8402a8b142}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void generateSqlite3ForFile (const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd)</td>
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


<p>Definition at line 2199 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae7139b08c0c942d65c6bcb8402a8b142">2199</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae7139b08c0c942d65c6bcb8402a8b142">generateSqlite3ForFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2200</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2201</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + includes files</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2202</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + includedby files</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2203</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// x include graph</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2204</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// x included by graph</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2205</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + contained class definitions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2206</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + contained namespace definitions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2207</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + member groups</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2208</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + normal members</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2209</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + brief desc</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2210</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + detailed desc</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2211</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// x source code</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2212</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + location (file_id, line, column)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2213</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - number of lines</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2214</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2215</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// skip external references</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2216</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2217</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a> = <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2218</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">(!<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>.created &amp;&amp; <a href="#a19ff8cd8130e662be4112bc914f7b50b">compounddefExists</a>(<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>)){</span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2219</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":rowid"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>.rowid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2220</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2221</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":name"</span><span class="doxyHighlight">,fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2222</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":title"</span><span class="doxyHighlight">,fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#aa1e5932865d564d3ff08ba5174387303">title</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2223</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":kind"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"file"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2224</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2225</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> file_id = <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>(fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2226</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":file_id"</span><span class="doxyHighlight">,file_id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2227</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":line"</span><span class="doxyHighlight">,fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2228</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":column"</span><span class="doxyHighlight">,fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#adf0e1ff0eec62741a8ee5d768589ab01">getDefColumn</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2229</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2230</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a309fe09ee4c594f158d4e9873ca1e6b6">getSQLDesc</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":briefdescription"</span><span class="doxyHighlight">,fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>(),fd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2231</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a309fe09ee4c594f158d4e9873ca1e6b6">getSQLDesc</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":detaileddescription"</span><span class="doxyHighlight">,fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>(),fd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2232</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2233</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2234</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2235</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + includes files</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2236</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ii : fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#aaa1fd01a880dff1fb1724a1dd209693f">includeFileList</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2237</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2238</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> src_id=<a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>(fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">absFilePath</a>(),!fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2239</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> dst_id=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2240</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> dst_path;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2241</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isLocal = (ii.kind &amp; <a href="/web-doxygen/docs/api/files/src/filedef-h/#abdab8bf385a3fe5d1f569c32428c2863">IncludeKind_LocalMask</a>)!=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2242</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2243</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">(ii.fileDef) </span><span class="doxyHighlightComment">// found file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2244</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2245</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">(ii.fileDef-&gt;isReference())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2246</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2247</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// strip tagfile from path</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2248</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tagfile = ii.fileDef-&gt;getReference();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2249</span><span class="doxyLineContent"><span class="doxyHighlight">        dst_path = ii.fileDef-&gt;absFilePath();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2250</span><span class="doxyLineContent"><span class="doxyHighlight">        dst_path.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(tagfile+</span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2251</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2252</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2253</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2254</span><span class="doxyLineContent"><span class="doxyHighlight">        dst_path = ii.fileDef-&gt;absFilePath();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2255</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2256</span><span class="doxyLineContent"><span class="doxyHighlight">      dst_id = <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>(dst_path,isLocal);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2257</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2258</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// can't find file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2259</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2260</span><span class="doxyLineContent"><span class="doxyHighlight">      dst_id = <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>(ii.includeName,isLocal,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2261</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2262</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2263</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((</span><span class="doxyHighlightStringLiteral">"-----&gt; FileDef includeInfo for %s\n"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(ii.includeName)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2264</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((</span><span class="doxyHighlightStringLiteral">"       local:    %d\n"</span><span class="doxyHighlight">, isLocal));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2265</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((</span><span class="doxyHighlightStringLiteral">"       imported: %d\n"</span><span class="doxyHighlight">, (ii.kind &amp; <a href="/web-doxygen/docs/api/files/src/filedef-h/#a5eeca59091b422e472c7ccbe7abb337c">IncludeKind_ImportMask</a>)!=0));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2266</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">(ii.fileDef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2267</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2268</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((</span><span class="doxyHighlightStringLiteral">"include: %s\n"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(ii.fileDef-&gt;absFilePath())));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2269</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2270</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((</span><span class="doxyHighlightStringLiteral">"       src_id  : %d\n"</span><span class="doxyHighlight">, src_id));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2271</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((</span><span class="doxyHighlightStringLiteral">"       dst_id: %d\n"</span><span class="doxyHighlight">, dst_id));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2272</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2273</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a1e3e98a7897963c61baf003aab5fecfa">incl_select</a>,</span><span class="doxyHighlightStringLiteral">":local"</span><span class="doxyHighlight">,isLocal);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2274</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a1e3e98a7897963c61baf003aab5fecfa">incl_select</a>,</span><span class="doxyHighlightStringLiteral">":src_id"</span><span class="doxyHighlight">,src_id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2275</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a1e3e98a7897963c61baf003aab5fecfa">incl_select</a>,</span><span class="doxyHighlightStringLiteral">":dst_id"</span><span class="doxyHighlight">,dst_id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2276</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#a1e3e98a7897963c61baf003aab5fecfa">incl_select</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)==0) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2277</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a9c15b3b9b3db6bf609838c68c915d80a">incl_insert</a>,</span><span class="doxyHighlightStringLiteral">":local"</span><span class="doxyHighlight">,isLocal);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2278</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a9c15b3b9b3db6bf609838c68c915d80a">incl_insert</a>,</span><span class="doxyHighlightStringLiteral">":src_id"</span><span class="doxyHighlight">,src_id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2279</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a9c15b3b9b3db6bf609838c68c915d80a">incl_insert</a>,</span><span class="doxyHighlightStringLiteral">":dst_id"</span><span class="doxyHighlight">,dst_id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2280</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#a9c15b3b9b3db6bf609838c68c915d80a">incl_insert</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2281</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2282</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2283</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2284</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + includedby files</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2285</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ii : fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#ae9c6fecec7ff96fded91315943519a25">includedByFileList</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2286</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2287</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> dst_id=<a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>(fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">absFilePath</a>(),!fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2288</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> src_id=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2289</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> src_path;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2290</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isLocal = (ii.kind &amp; <a href="/web-doxygen/docs/api/files/src/filedef-h/#abdab8bf385a3fe5d1f569c32428c2863">IncludeKind_LocalMask</a>)!=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2291</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2292</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">(ii.fileDef) </span><span class="doxyHighlightComment">// found file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2293</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2294</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">(ii.fileDef-&gt;isReference())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2295</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2296</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// strip tagfile from path</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2297</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tagfile = ii.fileDef-&gt;getReference();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2298</span><span class="doxyLineContent"><span class="doxyHighlight">        src_path = ii.fileDef-&gt;absFilePath();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2299</span><span class="doxyLineContent"><span class="doxyHighlight">        src_path.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(tagfile+</span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2300</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2301</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2302</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2303</span><span class="doxyLineContent"><span class="doxyHighlight">        src_path = ii.fileDef-&gt;absFilePath();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2304</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2305</span><span class="doxyLineContent"><span class="doxyHighlight">      src_id = <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>(src_path,isLocal);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2306</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2307</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// can't find file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2308</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2309</span><span class="doxyLineContent"><span class="doxyHighlight">      src_id = <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>(ii.includeName,isLocal,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2310</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2311</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2312</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a1e3e98a7897963c61baf003aab5fecfa">incl_select</a>,</span><span class="doxyHighlightStringLiteral">":local"</span><span class="doxyHighlight">,isLocal);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2313</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a1e3e98a7897963c61baf003aab5fecfa">incl_select</a>,</span><span class="doxyHighlightStringLiteral">":src_id"</span><span class="doxyHighlight">,src_id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2314</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a1e3e98a7897963c61baf003aab5fecfa">incl_select</a>,</span><span class="doxyHighlightStringLiteral">":dst_id"</span><span class="doxyHighlight">,dst_id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2315</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#a1e3e98a7897963c61baf003aab5fecfa">incl_select</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)==0) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2316</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a9c15b3b9b3db6bf609838c68c915d80a">incl_insert</a>,</span><span class="doxyHighlightStringLiteral">":local"</span><span class="doxyHighlight">,isLocal);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2317</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a9c15b3b9b3db6bf609838c68c915d80a">incl_insert</a>,</span><span class="doxyHighlightStringLiteral">":src_id"</span><span class="doxyHighlight">,src_id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2318</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a9c15b3b9b3db6bf609838c68c915d80a">incl_insert</a>,</span><span class="doxyHighlightStringLiteral">":dst_id"</span><span class="doxyHighlight">,dst_id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2319</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#a9c15b3b9b3db6bf609838c68c915d80a">incl_insert</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2320</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2321</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2322</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2323</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + contained class definitions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2324</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a3b94451a3cd1a0d6cc44e2a9a2118481">writeInnerClasses</a>(fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a82f5e81b574bc9e6635cfdd4d8ee2dfe">getClasses</a>(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2325</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2326</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + contained concept definitions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2327</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a46ef1ad7fcb0bd63228beb9a14e7f4bd">writeInnerConcepts</a>(fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#ae622a5297d0810cc339d335b07aae7c0">getConcepts</a>(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2328</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2329</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + contained namespace definitions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2330</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a597b4509789d2af90e78fe008fa832ab">writeInnerNamespaces</a>(fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a049235b5e182aa2c71db539c6d0896d3">getNamespaces</a>(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2331</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2332</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + member groups</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2333</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mg : fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a11c922f32703c5ddc3e4b9d47cea33a3">getMemberGroups</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2334</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2335</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a268c5eeaffe97a7ec76839a084b8e6fb">generateSqlite3Section</a>(fd,&amp;mg-&gt;members(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>,</span><span class="doxyHighlightStringLiteral">"user-defined"</span><span class="doxyHighlight">,mg-&gt;header(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2336</span><span class="doxyLineContent"><span class="doxyHighlight">          mg-&gt;documentation());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2337</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2338</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2339</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + normal members</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2340</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ml : fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#abe37d079d39eda03281588a4ebecbef6">getMemberLists</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2341</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2342</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ml-&gt;<a href="/web-doxygen/docs/api/classes/memberlist/#aa31a7d651481862036f72381f7e2a96d">listType</a>().<a href="/web-doxygen/docs/api/classes/memberlisttype/#af02c040fbca839a74c6f9cfafb54d6f7">isDeclaration</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2343</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2344</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a268c5eeaffe97a7ec76839a084b8e6fb">generateSqlite3Section</a>(fd,ml.get(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>,</span><span class="doxyHighlightStringLiteral">"user-defined"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2345</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2346</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2347</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">FileDef::absFilePath</a>, <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>, <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">Definition::briefDescription</a>, <a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef&#95;insert</a>, <a href="#a19ff8cd8130e662be4112bc914f7b50b">compounddefExists</a>, <a href="#a234e2efe67eececd88b140b46ea37463">DBG&#95;CTX</a>, <a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">Definition::documentation</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a268c5eeaffe97a7ec76839a084b8e6fb">generateSqlite3Section</a>, <a href="/web-doxygen/docs/api/classes/filedef/#a82f5e81b574bc9e6635cfdd4d8ee2dfe">FileDef::getClasses</a>, <a href="/web-doxygen/docs/api/classes/filedef/#ae622a5297d0810cc339d335b07aae7c0">FileDef::getConcepts</a>, <a href="/web-doxygen/docs/api/classes/definition/#adf0e1ff0eec62741a8ee5d768589ab01">Definition::getDefColumn</a>, <a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">Definition::getDefFileName</a>, <a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">Definition::getDefLine</a>, <a href="/web-doxygen/docs/api/classes/filedef/#a11c922f32703c5ddc3e4b9d47cea33a3">FileDef::getMemberGroups</a>, <a href="/web-doxygen/docs/api/classes/filedef/#abe37d079d39eda03281588a4ebecbef6">FileDef::getMemberLists</a>, <a href="/web-doxygen/docs/api/classes/filedef/#a049235b5e182aa2c71db539c6d0896d3">FileDef::getNamespaces</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="#a309fe09ee4c594f158d4e9873ca1e6b6">getSQLDesc</a>, <a href="#a9c15b3b9b3db6bf609838c68c915d80a">incl&#95;insert</a>, <a href="#a1e3e98a7897963c61baf003aab5fecfa">incl&#95;select</a>, <a href="/web-doxygen/docs/api/classes/filedef/#ae9c6fecec7ff96fded91315943519a25">FileDef::includedByFileList</a>, <a href="/web-doxygen/docs/api/classes/filedef/#aaa1fd01a880dff1fb1724a1dd209693f">FileDef::includeFileList</a>, <a href="/web-doxygen/docs/api/files/src/filedef-h/#a5eeca59091b422e472c7ccbe7abb337c">IncludeKind&#95;ImportMask</a>, <a href="/web-doxygen/docs/api/files/src/filedef-h/#abdab8bf385a3fe5d1f569c32428c2863">IncludeKind&#95;LocalMask</a>, <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>, <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>, <a href="/web-doxygen/docs/api/classes/memberlisttype/#af02c040fbca839a74c6f9cfafb54d6f7">MemberListType::isDeclaration</a>, <a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">Definition::isReference</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#aa31a7d651481862036f72381f7e2a96d">MemberList::listType</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>, <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">Refid::refid</a>, <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">QCString::stripPrefix</a>, <a href="/web-doxygen/docs/api/classes/filedef/#aa1e5932865d564d3ff08ba5174387303">FileDef::title</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="#a3b94451a3cd1a0d6cc44e2a9a2118481">writeInnerClasses</a>, <a href="#a46ef1ad7fcb0bd63228beb9a14e7f4bd">writeInnerConcepts</a> and <a href="#a597b4509789d2af90e78fe008fa832ab">writeInnerNamespaces</a>.

Referenced by <a href="#ae5b36a2f93dadba9f8c7d762564154e1">generateSqlite3</a>.
</div>
</div>

### generateSqlite3ForGroup() {#a44a2f9f4ba14ceb381c325b3438febd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void generateSqlite3ForGroup (const <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> * gd)</td>
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


<p>Definition at line 2350 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a44a2f9f4ba14ceb381c325b3438febd8">2350</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *gd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2351</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2352</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + members</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2353</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + member groups</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2354</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + files</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2355</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2356</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + namespaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2357</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - packages</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2358</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + pages</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2359</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + child groups</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2360</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - examples</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2361</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + brief description</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2362</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + detailed description</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2363</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2364</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// skip external references.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2365</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2366</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a> = <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2367</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">(!<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>.created &amp;&amp; <a href="#a19ff8cd8130e662be4112bc914f7b50b">compounddefExists</a>(<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>)){</span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2368</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":rowid"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>.rowid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2369</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2370</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":name"</span><span class="doxyHighlight">,gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2371</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":title"</span><span class="doxyHighlight">,gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a2caedefd187d92eb8c4afe01d403456e">groupTitle</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2372</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":kind"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"group"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2373</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2374</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> file_id = <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>(gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2375</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":file_id"</span><span class="doxyHighlight">,file_id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2376</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":line"</span><span class="doxyHighlight">,gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2377</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":column"</span><span class="doxyHighlight">,gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#adf0e1ff0eec62741a8ee5d768589ab01">getDefColumn</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2378</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2379</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a309fe09ee4c594f158d4e9873ca1e6b6">getSQLDesc</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":briefdescription"</span><span class="doxyHighlight">,gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>(),gd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2380</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a309fe09ee4c594f158d4e9873ca1e6b6">getSQLDesc</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":detaileddescription"</span><span class="doxyHighlight">,gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>(),gd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2381</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2382</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2383</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2384</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + files</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2385</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a9e4b392824ade3c727f39d6717bdc97f">writeInnerFiles</a>(gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a2cb0a3622503ad4232eabc2b7ff86753">getFiles</a>(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2386</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2387</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2388</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a3b94451a3cd1a0d6cc44e2a9a2118481">writeInnerClasses</a>(gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#adc93620cc6002b6e7919565cb32b29ed">getClasses</a>(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2389</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2390</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + concepts</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2391</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a46ef1ad7fcb0bd63228beb9a14e7f4bd">writeInnerConcepts</a>(gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a927445c6f77b990c4b7ea29e93a7837e">getConcepts</a>(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2392</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2393</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + modules</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2394</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a68dad0e13a83b4eb9046a6e6588a855f">writeInnerModules</a>(gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#afae9211266248f6c26c5fabf1c4415b0">getModules</a>(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2395</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2396</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + namespaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2397</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a597b4509789d2af90e78fe008fa832ab">writeInnerNamespaces</a>(gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a9ac892052b696a7c561f7dfa7be68f72">getNamespaces</a>(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2398</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2399</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + pages</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2400</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4b9d2814806d6388bddc5f4c141d8fbf">writeInnerPages</a>(gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a97d9ddba395f4c011a01966dc7a61568">getPages</a>(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2401</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2402</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + groups</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2403</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a472ea2a1d309024f061e7d48d1dd3839">writeInnerGroups</a>(gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a29954976b38072020da6c0c0dbde6520">getSubGroups</a>(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2404</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2405</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + member groups</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2406</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mg : gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a8a9fe05d4375b4571d822141ba498bf2">getMemberGroups</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2407</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2408</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a268c5eeaffe97a7ec76839a084b8e6fb">generateSqlite3Section</a>(gd,&amp;mg-&gt;members(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>,</span><span class="doxyHighlightStringLiteral">"user-defined"</span><span class="doxyHighlight">,mg-&gt;header(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2409</span><span class="doxyLineContent"><span class="doxyHighlight">        mg-&gt;documentation());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2410</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2411</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2412</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + members</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2413</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ml : gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a2d174d39f8e75953f384736d3effaad8">getMemberLists</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2414</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2415</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ml-&gt;<a href="/web-doxygen/docs/api/classes/memberlist/#aa31a7d651481862036f72381f7e2a96d">listType</a>().<a href="/web-doxygen/docs/api/classes/memberlisttype/#af02c040fbca839a74c6f9cfafb54d6f7">isDeclaration</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2416</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2417</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a268c5eeaffe97a7ec76839a084b8e6fb">generateSqlite3Section</a>(gd,ml.get(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>,</span><span class="doxyHighlightStringLiteral">"user-defined"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2418</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2419</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2420</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>, <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">Definition::briefDescription</a>, <a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef&#95;insert</a>, <a href="#a19ff8cd8130e662be4112bc914f7b50b">compounddefExists</a>, <a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">Definition::documentation</a>, <a href="#a268c5eeaffe97a7ec76839a084b8e6fb">generateSqlite3Section</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#adc93620cc6002b6e7919565cb32b29ed">GroupDef::getClasses</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#a927445c6f77b990c4b7ea29e93a7837e">GroupDef::getConcepts</a>, <a href="/web-doxygen/docs/api/classes/definition/#adf0e1ff0eec62741a8ee5d768589ab01">Definition::getDefColumn</a>, <a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">Definition::getDefFileName</a>, <a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">Definition::getDefLine</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#a2cb0a3622503ad4232eabc2b7ff86753">GroupDef::getFiles</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#a8a9fe05d4375b4571d822141ba498bf2">GroupDef::getMemberGroups</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#a2d174d39f8e75953f384736d3effaad8">GroupDef::getMemberLists</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#afae9211266248f6c26c5fabf1c4415b0">GroupDef::getModules</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#a9ac892052b696a7c561f7dfa7be68f72">GroupDef::getNamespaces</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#a97d9ddba395f4c011a01966dc7a61568">GroupDef::getPages</a>, <a href="#a309fe09ee4c594f158d4e9873ca1e6b6">getSQLDesc</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#a29954976b38072020da6c0c0dbde6520">GroupDef::getSubGroups</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#a2caedefd187d92eb8c4afe01d403456e">GroupDef::groupTitle</a>, <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>, <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>, <a href="/web-doxygen/docs/api/classes/memberlisttype/#af02c040fbca839a74c6f9cfafb54d6f7">MemberListType::isDeclaration</a>, <a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">Definition::isReference</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#aa31a7d651481862036f72381f7e2a96d">MemberList::listType</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">Refid::refid</a>, <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>, <a href="#a3b94451a3cd1a0d6cc44e2a9a2118481">writeInnerClasses</a>, <a href="#a46ef1ad7fcb0bd63228beb9a14e7f4bd">writeInnerConcepts</a>, <a href="#a9e4b392824ade3c727f39d6717bdc97f">writeInnerFiles</a>, <a href="#a472ea2a1d309024f061e7d48d1dd3839">writeInnerGroups</a>, <a href="#a68dad0e13a83b4eb9046a6e6588a855f">writeInnerModules</a>, <a href="#a597b4509789d2af90e78fe008fa832ab">writeInnerNamespaces</a> and <a href="#a4b9d2814806d6388bddc5f4c141d8fbf">writeInnerPages</a>.

Referenced by <a href="#ae5b36a2f93dadba9f8c7d762564154e1">generateSqlite3</a>.
</div>
</div>

### generateSqlite3ForMember() {#ae37a1510e5c7b3f007b41d8f8c152e9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void generateSqlite3ForMember (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md, struct <a href="/web-doxygen/docs/api/structs/refid">Refid</a> scope_refid, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * def)</td>
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


<p>Definition at line 1553 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae37a1510e5c7b3f007b41d8f8c152e9f">1553</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md, </span><span class="doxyHighlightKeyword">struct</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/refid">Refid</a> scope_refid, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *def)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1554</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1555</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + declaration/definition arg lists</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1556</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + reimplements</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1557</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + reimplementedBy</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1558</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - exceptions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1559</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + const/volatile specifiers</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1560</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - examples</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1561</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + source definition</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1562</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + source references</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1563</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + source referenced by</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1564</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - body code</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1565</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + template arguments</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1566</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//     (templateArguments(), definitionTemplateParameterLists())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1567</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - call graph</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1568</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1569</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// enum values are written as part of the enum</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1570</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">memberType</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a29785ae7827639b31b629cc7f9c150e0">MemberType::EnumValue</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1571</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a930740d353cfe143eb9efe0d12b7f938">isHidden</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1572</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1573</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> memType;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1574</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1575</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// memberdef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1576</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> qrefid = md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>() + </span><span class="doxyHighlightStringLiteral">"_1"</span><span class="doxyHighlight"> + md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1577</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a> = <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(qrefid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1578</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1579</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#affa42bdf0b91c838fe0215b4e6afb7b5">associateMember</a>(md, <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>, scope_refid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1580</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1581</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// compacting duplicate defs</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1582</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">(!<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>.created &amp;&amp; <a href="#a06d5fa6f8acbfef6705314884b6e6800">memberdefExists</a>(<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>) &amp;&amp; <a href="#a2a696974b4a7902e4137be55d5337d20">memberdefIncomplete</a>(<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>, md))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1583</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1584</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">/*</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1585</span><span class="doxyLineContent"><span class="doxyHighlightComment">    For performance, ideal to skip a member we've already added.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1586</span><span class="doxyLineContent"><span class="doxyHighlightComment">    Unfortunately, we can have two memberdefs with the same refid documenting</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1587</span><span class="doxyLineContent"><span class="doxyHighlightComment">    the declaration and definition. memberdefIncomplete() uses the 'inline'</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1588</span><span class="doxyLineContent"><span class="doxyHighlightComment">    value to figure this out. Once we get to this point, we should *only* be</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1589</span><span class="doxyLineContent"><span class="doxyHighlightComment">    seeing the *other* type of def/decl, so we'll set inline to a new value (2),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1590</span><span class="doxyLineContent"><span class="doxyHighlightComment">    indicating that this entry covers both inline types.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1591</span><span class="doxyLineContent"><span class="doxyHighlightComment">    */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1592</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> memberdef_update;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1593</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1594</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// definitions have bodyfile/start/end</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1595</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ad63d39480ae9ec4e71bedbb749d16a4c">getStartBodyLine</a>()!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1596</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1597</span><span class="doxyLineContent"><span class="doxyHighlight">      memberdef_update = <a href="#a996b41f0018348eb70cb369999032333">memberdef_update_def</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1598</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> bodyfile_id = <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>(md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a7ea253be90981d4a6f0cfdb6dff1d2fd">getBodyDef</a>()-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">absFilePath</a>(),!md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a7ea253be90981d4a6f0cfdb6dff1d2fd">getBodyDef</a>()-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1599</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bodyfile_id == -1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1600</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1601</span><span class="doxyLineContent"><span class="doxyHighlight">          sqlite3_clear_bindings(memberdef_update.<a href="/web-doxygen/docs/api/structs/sqlstmt/#a780c9b733b885100df0aa733b0c66a37">stmt</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1602</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1603</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1604</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1605</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(memberdef_update,</span><span class="doxyHighlightStringLiteral">":bodyfile_id"</span><span class="doxyHighlight">,bodyfile_id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1606</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(memberdef_update,</span><span class="doxyHighlightStringLiteral">":bodystart"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ad63d39480ae9ec4e71bedbb749d16a4c">getStartBodyLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1607</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(memberdef_update,</span><span class="doxyHighlightStringLiteral">":bodyend"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0b5313ad11f50b2d056fc62d81db0433">getEndBodyLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1608</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1609</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1610</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// declarations don't</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1611</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1612</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1613</span><span class="doxyLineContent"><span class="doxyHighlight">      memberdef_update = <a href="#a9dd6736df9437b0372601f0fc9256cdc">memberdef_update_decl</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1614</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>() != -1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1615</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1616</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> file_id = <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>(md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>(),!md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1617</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (file_id!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1618</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1619</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(memberdef_update,</span><span class="doxyHighlightStringLiteral">":file_id"</span><span class="doxyHighlight">,file_id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1620</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(memberdef_update,</span><span class="doxyHighlightStringLiteral">":line"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1621</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(memberdef_update,</span><span class="doxyHighlightStringLiteral">":column"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#adf0e1ff0eec62741a8ee5d768589ab01">getDefColumn</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1622</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1623</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1624</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1625</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1626</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(memberdef_update, </span><span class="doxyHighlightStringLiteral">":rowid"</span><span class="doxyHighlight">, refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1627</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// value 2 indicates we've seen "both" inline types.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1628</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(memberdef_update,</span><span class="doxyHighlightStringLiteral">":inline"</span><span class="doxyHighlight">, 2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1629</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1630</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">/* in case both are used, append/prepend descriptions */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1631</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a309fe09ee4c594f158d4e9873ca1e6b6">getSQLDesc</a>(memberdef_update,</span><span class="doxyHighlightStringLiteral">":briefdescription"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>(),md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1632</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a309fe09ee4c594f158d4e9873ca1e6b6">getSQLDesc</a>(memberdef_update,</span><span class="doxyHighlightStringLiteral">":detaileddescription"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>(),md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1633</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a309fe09ee4c594f158d4e9873ca1e6b6">getSQLDesc</a>(memberdef_update,</span><span class="doxyHighlightStringLiteral">":inbodydescription"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#af59473951772c62b9db328e342fc2198">inbodyDocumentation</a>(),md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1634</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1635</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(memberdef_update,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1636</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1637</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// don't think we need to repeat params; should have from first encounter</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1638</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1639</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// + source references</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1640</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// The cross-references in initializers only work when both the src and dst</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1641</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// are defined.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1642</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> refList = md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#af21ed7be937dbdb153d5ccab3d9abf12">getReferencesMembers</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1643</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;rmd : refList)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1644</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1645</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a204b468b29a5d8ae8cf305cc08766eb7">insertMemberReference</a>(md,rmd, </span><span class="doxyHighlightStringLiteral">"inline"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1646</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1647</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// + source referenced by</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1648</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> refByList = md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ad3359130ee4ef83bdf7ce453fb3d1525">getReferencedByMembers</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1649</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;rmd : refByList)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1650</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1651</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a204b468b29a5d8ae8cf305cc08766eb7">insertMemberReference</a>(rmd,md, </span><span class="doxyHighlightStringLiteral">"inline"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1652</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1653</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1654</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1655</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1656</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":rowid"</span><span class="doxyHighlight">, refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1657</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":kind"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#aca314e25245ec3b08f1a55068c2fbeff">memberTypeName</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1658</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":prot"</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ab266b88c02dd8d5089b29d501b412c5d">protection</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1659</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1660</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":static"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a73354ecea5b876ab8d59724b080189b4">isStatic</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1661</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":extern"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a62a3294a87e2a6e2ff4a2d52bfd3187a">isExternal</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1662</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1663</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isFunc=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1664</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">memberType</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1665</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1666</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a86408593c34af77fdd90df932f8b5261">MemberType::Function</a>: </span><span class="doxyHighlightComment">// fall through</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1667</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a085fea7abdc5d904fe69a3081efd7398">MemberType::Signal</a>:   </span><span class="doxyHighlightComment">// fall through</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1668</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a930a91848917f92cf7e2f8d744fa4177">MemberType::Friend</a>:   </span><span class="doxyHighlightComment">// fall through</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1669</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41ad8be171b26c1f1b456fea317076584ab">MemberType::DCOP</a>:     </span><span class="doxyHighlightComment">// fall through</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1670</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a9234cc57c43f272b55a94b0069fe62d1">MemberType::Slot</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1671</span><span class="doxyLineContent"><span class="doxyHighlight">      isFunc=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1672</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1673</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1674</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1675</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1676</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1677</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isFunc)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1678</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1679</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;al = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">argumentList</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1680</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":const"</span><span class="doxyHighlight">,al.<a href="/web-doxygen/docs/api/classes/argumentlist/#a72440ac7985da3c0c465134bc0ddd2d5">constSpecifier</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1681</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":volatile"</span><span class="doxyHighlight">,al.<a href="/web-doxygen/docs/api/classes/argumentlist/#ad03f25174e81a42a617a15195a8867b0">volatileSpecifier</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1682</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":explicit"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a0aa8429875443e986e04e34624c5c0c8">isExplicit</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1683</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":inline"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a509e150708bb48d4bafaa1146cf1eadc">isInline</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1684</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":final"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#aef0c62b7d85f8eff11657f9a7e3f87f4">isFinal</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1685</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":sealed"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a1b3f4fc396e748b60fd3f4057f0bba21">isSealed</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1686</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":new"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a0ceb921ed3647329a26b0c9ce434658d">isNew</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1687</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":optional"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ab41ecacc3c433253d893d6baded01de0">isOptional</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1688</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":required"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a62549140ec2a398af9b6a72c63aad7d5">isRequired</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1689</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1690</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":virt"</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ae450a2be776cc5d05726bab8354f6d62">virtualness</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1691</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1692</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1693</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">memberType</a>() == <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a47c14840d8e15331fa420b9b2f757cd9">MemberType::Variable</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1694</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1695</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":mutable"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#af448f46a30d6337ef678db352dd244e3">isMutable</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1696</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":initonly"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a02a894331323ad650cd3b748ce9d604b">isInitonly</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1697</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":attribute"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a62780d0d926b1c17801dbba81921336a">isAttribute</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1698</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":property"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#afd4a6cd84468b885049120e767b017fc">isProperty</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1699</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":readonly"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a8679a7213fda9304814aa989c731a4a9">isReadonly</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1700</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":bound"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a86bb29ff5f9e049343bdb990b08ff9a3">isBound</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1701</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":removable"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a7ebd90ccb692199c14ef91526df6d534">isRemovable</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1702</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":constrained"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a80a42e55d42df534c9da463015872d41">isConstrained</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1703</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":transient"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#aafb531645493ceda329fc922748401be">isTransient</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1704</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":maybevoid"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a18b343dd677e74a1ecb5723fbb746395">isMaybeVoid</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1705</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":maybedefault"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a735ac6b44a83924b761bdac676eb4184">isMaybeDefault</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1706</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":maybeambiguous"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a581d0d2acf3c99191e1a5f3cb5f95ce6">isMaybeAmbiguous</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1707</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a79b45e3c4c595bebe2c1e65e965c6d39">bitfieldString</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1708</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1709</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> bitfield = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a79b45e3c4c595bebe2c1e65e965c6d39">bitfieldString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1710</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bitfield.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(0)==</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight">) bitfield=bitfield.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1711</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":bitfield"</span><span class="doxyHighlight">,bitfield.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1712</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1713</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1714</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">memberType</a>() == <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a5ad234cb2cde4266195252a23ca7d84e">MemberType::Property</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1715</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1716</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":readable"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#abf0cad08f28ef0b4e73fd13baefa56a8">isReadable</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1717</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":writable"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a562a056cb102eb78ad78fffe455a2db9">isWritable</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1718</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":gettable"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#aba4783c1fa6a84a2beb2b4dad7000616">isGettable</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1719</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":privategettable"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a594fe47b12073b186b7f1e4d8e2b1d56">isPrivateGettable</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1720</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":protectedgettable"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#aa69883d56b1adfe457130d7c96873ba7">isProtectedGettable</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1721</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":settable"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a44b6a11c61d72073dcfc17d85a303ac5">isSettable</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1722</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":privatesettable"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a787020ca6fc65ea0cc13f5721d166420">isPrivateSettable</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1723</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":protectedsettable"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#aa51dd090dc6e2d111145cc04e9e3f7fe">isProtectedSettable</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1724</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1725</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a09bc44df807bfe787766e6268b991732">isAssign</a>() || md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a6548961c5a9f2003ec5425bea0249ad2">isCopy</a>() || md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a4902c8d45c53057b6b421a22821d999b">isRetain</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1726</span><span class="doxyLineContent"><span class="doxyHighlight">     || md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#adbdbd0e3d3630af579a02e97e162a328">isStrong</a>() || md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ac14124f33e6513789346a840f5e49385">isWeak</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1727</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1728</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> accessor=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1729</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a09bc44df807bfe787766e6268b991732">isAssign</a>())      accessor = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1730</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a6548961c5a9f2003ec5425bea0249ad2">isCopy</a>())   accessor = 2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1731</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a4902c8d45c53057b6b421a22821d999b">isRetain</a>()) accessor = 3;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1732</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#adbdbd0e3d3630af579a02e97e162a328">isStrong</a>()) accessor = 4;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1733</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ac14124f33e6513789346a840f5e49385">isWeak</a>())   accessor = 5;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1734</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1735</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":accessor"</span><span class="doxyHighlight">,accessor);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1736</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1737</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":read"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ab8d7b70952b14c1f6af79a16f122a6c9">getReadAccessor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1738</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":write"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a7638dcb798738c331ba2c2567118ceb6">getWriteAccessor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1739</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1740</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">memberType</a>() == <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41aa4ecfc70574394990cf17bd83df499f7">MemberType::Event</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1741</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1742</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":addable"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a496b02cff3e89cc59eab5139a9211475">isAddable</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1743</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":removable"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a7ebd90ccb692199c14ef91526df6d534">isRemovable</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1744</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":raisable"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a7e0e45a5885e55221f756a8e3153fb8a">isRaisable</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1745</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1746</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1747</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *rmd = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a735862f449c091668f1fc86004aab3a2">reimplements</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1748</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rmd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1749</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1750</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> qreimplemented_refid = rmd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>() + </span><span class="doxyHighlightStringLiteral">"_1"</span><span class="doxyHighlight"> + rmd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1751</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1752</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> reimplemented_refid = <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(qreimplemented_refid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1753</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1754</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a6ef03b7de5c740c3ad04b46fee17e6e0">reimplements_insert</a>,</span><span class="doxyHighlightStringLiteral">":memberdef_rowid"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>.rowid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1755</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a6ef03b7de5c740c3ad04b46fee17e6e0">reimplements_insert</a>,</span><span class="doxyHighlightStringLiteral">":reimplemented_rowid"</span><span class="doxyHighlight">, reimplemented_refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1756</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#a6ef03b7de5c740c3ad04b46fee17e6e0">reimplements_insert</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1757</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1758</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1759</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + declaration/definition arg lists</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1760</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">memberType</a>()!=<a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a9312cc2f02f42764c70c3713f80fe219">MemberType::Define</a> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1761</span><span class="doxyLineContent"><span class="doxyHighlight">      md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">memberType</a>()!=<a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a2958e521f3da6b41059c4369a34a2a23">MemberType::Enumeration</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1762</span><span class="doxyLineContent"><span class="doxyHighlight">     )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1763</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1764</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">memberType</a>()!=<a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a5fede51b97a819dedf4f83bc2aacbc6a">MemberType::Typedef</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1765</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1766</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#adbab9cdf5d958b7f7ac7b736428974dd">writeMemberTemplateLists</a>(md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1767</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1768</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> typeStr = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a0032c6e040cdec6d9c52dc75a790a884">typeString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1769</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a8acb7287be03115c56196dd1a1085225">stripQualifiers</a>(typeStr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1770</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> list;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1771</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a>(<a href="/web-doxygen/docs/api/classes/textgeneratorsqlite3impl">TextGeneratorSqlite3Impl</a>(list), def, md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a7ea253be90981d4a6f0cfdb6dff1d2fd">getBodyDef</a>(),md,typeStr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1772</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!typeStr.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1773</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1774</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":type"</span><span class="doxyHighlight">,typeStr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1775</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1776</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1777</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a1bc15da1d36aef0514a095c9ff485618">definition</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1778</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1779</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":definition"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a1bc15da1d36aef0514a095c9ff485618">definition</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1780</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1781</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1782</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">argsString</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1783</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1784</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":argsstring"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">argsString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1785</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1786</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1787</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1788</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":name"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1789</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1790</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Extract references from initializer</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1791</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ab0edc949c11ffd04ae0f79b8850b1586">hasMultiLineInitializer</a>() || md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#aa7bcaaff6e07e660a124d779a1300218">hasOneLineInitializer</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1792</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1793</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":initializer"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#afe9302d711e627fdd4e9eb7c393ceeb5">initializer</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1794</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1795</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> list;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1796</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a>(<a href="/web-doxygen/docs/api/classes/textgeneratorsqlite3impl">TextGeneratorSqlite3Impl</a>(list),def,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a7ea253be90981d4a6f0cfdb6dff1d2fd">getBodyDef</a>(),md,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#afe9302d711e627fdd4e9eb7c393ceeb5">initializer</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1797</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;s : list)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1798</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1799</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a7ea253be90981d4a6f0cfdb6dff1d2fd">getBodyDef</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1800</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1801</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((</span><span class="doxyHighlightStringLiteral">"initializer:%s %s %s %d\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1802</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>()),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1803</span><span class="doxyLineContent"><span class="doxyHighlight">              s.c_str(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1804</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a7ea253be90981d4a6f0cfdb6dff1d2fd">getBodyDef</a>()-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>()),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1805</span><span class="doxyLineContent"><span class="doxyHighlight">              md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ad63d39480ae9ec4e71bedbb749d16a4c">getStartBodyLine</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1806</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> qsrc_refid = md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>() + </span><span class="doxyHighlightStringLiteral">"_1"</span><span class="doxyHighlight"> + md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1807</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> src_refid = <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(qsrc_refid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1808</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> dst_refid = <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(s.c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1809</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a204b468b29a5d8ae8cf305cc08766eb7">insertMemberReference</a>(src_refid,dst_refid, </span><span class="doxyHighlightStringLiteral">"initializer"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1810</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1811</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1812</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1813</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1814</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( !md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a68246f42d892a0cd4e1b5248d8f8f947">getScopeString</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1815</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1816</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":scope"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a68246f42d892a0cd4e1b5248d8f8f947">getScopeString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1817</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1818</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1819</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// +Brief, detailed and inbody description</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1820</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a309fe09ee4c594f158d4e9873ca1e6b6">getSQLDesc</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":briefdescription"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>(),md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1821</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a309fe09ee4c594f158d4e9873ca1e6b6">getSQLDesc</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":detaileddescription"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>(),md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1822</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a309fe09ee4c594f158d4e9873ca1e6b6">getSQLDesc</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":inbodydescription"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#af59473951772c62b9db328e342fc2198">inbodyDocumentation</a>(),md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1823</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1824</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// File location</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1825</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>() != -1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1826</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1827</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> file_id = <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>(md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>(),!md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1828</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (file_id!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1829</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1830</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":file_id"</span><span class="doxyHighlight">,file_id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1831</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":line"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1832</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":column"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#adf0e1ff0eec62741a8ee5d768589ab01">getDefColumn</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1833</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1834</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// definitions also have bodyfile/start/end</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1835</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ad63d39480ae9ec4e71bedbb749d16a4c">getStartBodyLine</a>()!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1836</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1837</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> bodyfile_id = <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>(md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a7ea253be90981d4a6f0cfdb6dff1d2fd">getBodyDef</a>()-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">absFilePath</a>(),!md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a7ea253be90981d4a6f0cfdb6dff1d2fd">getBodyDef</a>()-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1838</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bodyfile_id == -1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1839</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1840</span><span class="doxyLineContent"><span class="doxyHighlight">            sqlite3_clear_bindings(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>.stmt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1841</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1842</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1843</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1844</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":bodyfile_id"</span><span class="doxyHighlight">,bodyfile_id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1845</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":bodystart"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ad63d39480ae9ec4e71bedbb749d16a4c">getStartBodyLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1846</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,</span><span class="doxyHighlightStringLiteral">":bodyend"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0b5313ad11f50b2d056fc62d81db0433">getEndBodyLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1847</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1848</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1849</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1850</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1851</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1852</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> memberdef_id=<a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1853</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1854</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isFunc)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1855</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1856</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a3a9064a0bd3f19c550c68c5839dec5a6">insertMemberFunctionParams</a>(memberdef_id,md,def);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1857</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1858</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">memberType</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a9312cc2f02f42764c70c3713f80fe219">MemberType::Define</a> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1859</span><span class="doxyLineContent"><span class="doxyHighlight">          !md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">argsString</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1860</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1861</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6ff307313c1b28d89ef63fef3590ad36">insertMemberDefineParams</a>(memberdef_id,md,def);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1862</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1863</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1864</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + source references</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1865</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// The cross-references in initializers only work when both the src and dst</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1866</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// are defined.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1867</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;refmd : md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#af21ed7be937dbdb153d5ccab3d9abf12">getReferencesMembers</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1868</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1869</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a204b468b29a5d8ae8cf305cc08766eb7">insertMemberReference</a>(md,refmd, </span><span class="doxyHighlightStringLiteral">"inline"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1870</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1871</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + source referenced by</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1872</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;refmd : md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ad3359130ee4ef83bdf7ce453fb3d1525">getReferencedByMembers</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1873</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1874</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a204b468b29a5d8ae8cf305cc08766eb7">insertMemberReference</a>(refmd,md, </span><span class="doxyHighlightStringLiteral">"inline"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1875</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1876</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">FileDef::absFilePath</a>, <a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">Definition::anchor</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">MemberDef::argsString</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">MemberDef::argumentList</a>, <a href="#affa42bdf0b91c838fe0215b4e6afb7b5">associateMember</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>, <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a79b45e3c4c595bebe2c1e65e965c6d39">MemberDef::bitfieldString</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">Definition::briefDescription</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#a72440ac7985da3c0c465134bc0ddd2d5">ArgumentList::constSpecifier</a>, <a href="#a234e2efe67eececd88b140b46ea37463">DBG&#95;CTX</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41ad8be171b26c1f1b456fea317076584ab">DCOP</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a9312cc2f02f42764c70c3713f80fe219">Define</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a1bc15da1d36aef0514a095c9ff485618">MemberDef::definition</a>, <a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">Definition::documentation</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a2958e521f3da6b41059c4369a34a2a23">Enumeration</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a29785ae7827639b31b629cc7f9c150e0">EnumValue</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41aa4ecfc70574394990cf17bd83df499f7">Event</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a930a91848917f92cf7e2f8d744fa4177">Friend</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a86408593c34af77fdd90df932f8b5261">Function</a>, <a href="/web-doxygen/docs/api/classes/definition/#a7ea253be90981d4a6f0cfdb6dff1d2fd">Definition::getBodyDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#adf0e1ff0eec62741a8ee5d768589ab01">Definition::getDefColumn</a>, <a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">Definition::getDefFileName</a>, <a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">Definition::getDefLine</a>, <a href="/web-doxygen/docs/api/classes/definition/#a0b5313ad11f50b2d056fc62d81db0433">Definition::getEndBodyLine</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#ab8d7b70952b14c1f6af79a16f122a6c9">MemberDef::getReadAccessor</a>, <a href="/web-doxygen/docs/api/classes/definition/#ad3359130ee4ef83bdf7ce453fb3d1525">Definition::getReferencedByMembers</a>, <a href="/web-doxygen/docs/api/classes/definition/#af21ed7be937dbdb153d5ccab3d9abf12">Definition::getReferencesMembers</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a68246f42d892a0cd4e1b5248d8f8f947">MemberDef::getScopeString</a>, <a href="#a309fe09ee4c594f158d4e9873ca1e6b6">getSQLDesc</a>, <a href="/web-doxygen/docs/api/classes/definition/#ad63d39480ae9ec4e71bedbb749d16a4c">Definition::getStartBodyLine</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a7638dcb798738c331ba2c2567118ceb6">MemberDef::getWriteAccessor</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#ab0edc949c11ffd04ae0f79b8850b1586">MemberDef::hasMultiLineInitializer</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#aa7bcaaff6e07e660a124d779a1300218">MemberDef::hasOneLineInitializer</a>, <a href="/web-doxygen/docs/api/classes/definition/#af59473951772c62b9db328e342fc2198">Definition::inbodyDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#afe9302d711e627fdd4e9eb7c393ceeb5">MemberDef::initializer</a>, <a href="#a6ff307313c1b28d89ef63fef3590ad36">insertMemberDefineParams</a>, <a href="#a3a9064a0bd3f19c550c68c5839dec5a6">insertMemberFunctionParams</a>, <a href="#a204b468b29a5d8ae8cf305cc08766eb7">insertMemberReference</a>, <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>, <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a496b02cff3e89cc59eab5139a9211475">MemberDef::isAddable</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a09bc44df807bfe787766e6268b991732">MemberDef::isAssign</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a62780d0d926b1c17801dbba81921336a">MemberDef::isAttribute</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a86bb29ff5f9e049343bdb990b08ff9a3">MemberDef::isBound</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a80a42e55d42df534c9da463015872d41">MemberDef::isConstrained</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a6548961c5a9f2003ec5425bea0249ad2">MemberDef::isCopy</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a0aa8429875443e986e04e34624c5c0c8">MemberDef::isExplicit</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a62a3294a87e2a6e2ff4a2d52bfd3187a">MemberDef::isExternal</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#aef0c62b7d85f8eff11657f9a7e3f87f4">MemberDef::isFinal</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#aba4783c1fa6a84a2beb2b4dad7000616">MemberDef::isGettable</a>, <a href="/web-doxygen/docs/api/classes/definition/#a930740d353cfe143eb9efe0d12b7f938">Definition::isHidden</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a02a894331323ad650cd3b748ce9d604b">MemberDef::isInitonly</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a509e150708bb48d4bafaa1146cf1eadc">MemberDef::isInline</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a581d0d2acf3c99191e1a5f3cb5f95ce6">MemberDef::isMaybeAmbiguous</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a735ac6b44a83924b761bdac676eb4184">MemberDef::isMaybeDefault</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a18b343dd677e74a1ecb5723fbb746395">MemberDef::isMaybeVoid</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#af448f46a30d6337ef678db352dd244e3">MemberDef::isMutable</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a0ceb921ed3647329a26b0c9ce434658d">MemberDef::isNew</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#ab41ecacc3c433253d893d6baded01de0">MemberDef::isOptional</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a594fe47b12073b186b7f1e4d8e2b1d56">MemberDef::isPrivateGettable</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a787020ca6fc65ea0cc13f5721d166420">MemberDef::isPrivateSettable</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#afd4a6cd84468b885049120e767b017fc">MemberDef::isProperty</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#aa69883d56b1adfe457130d7c96873ba7">MemberDef::isProtectedGettable</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#aa51dd090dc6e2d111145cc04e9e3f7fe">MemberDef::isProtectedSettable</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a7e0e45a5885e55221f756a8e3153fb8a">MemberDef::isRaisable</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#abf0cad08f28ef0b4e73fd13baefa56a8">MemberDef::isReadable</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a8679a7213fda9304814aa989c731a4a9">MemberDef::isReadonly</a>, <a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">Definition::isReference</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a7ebd90ccb692199c14ef91526df6d534">MemberDef::isRemovable</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a62549140ec2a398af9b6a72c63aad7d5">MemberDef::isRequired</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a4902c8d45c53057b6b421a22821d999b">MemberDef::isRetain</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a1b3f4fc396e748b60fd3f4057f0bba21">MemberDef::isSealed</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a44b6a11c61d72073dcfc17d85a303ac5">MemberDef::isSettable</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a73354ecea5b876ab8d59724b080189b4">MemberDef::isStatic</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#adbdbd0e3d3630af579a02e97e162a328">MemberDef::isStrong</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#aafb531645493ceda329fc922748401be">MemberDef::isTransient</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#ac14124f33e6513789346a840f5e49385">MemberDef::isWeak</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a562a056cb102eb78ad78fffe455a2db9">MemberDef::isWritable</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a>, <a href="#a044bf3040887411b780222535ef94942">memberdef&#95;insert</a>, <a href="#a9dd6736df9437b0372601f0fc9256cdc">memberdef&#95;update&#95;decl</a>, <a href="#a996b41f0018348eb70cb369999032333">memberdef&#95;update&#95;def</a>, <a href="#a06d5fa6f8acbfef6705314884b6e6800">memberdefExists</a>, <a href="#a2a696974b4a7902e4137be55d5337d20">memberdefIncomplete</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">MemberDef::memberType</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#aca314e25245ec3b08f1a55068c2fbeff">MemberDef::memberTypeName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a5ad234cb2cde4266195252a23ca7d84e">Property</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#ab266b88c02dd8d5089b29d501b412c5d">MemberDef::protection</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>, <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">Refid::refid</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a735862f449c091668f1fc86004aab3a2">MemberDef::reimplements</a>, <a href="#a6ef03b7de5c740c3ad04b46fee17e6e0">reimplements&#95;insert</a>, <a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">Refid::rowid</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a085fea7abdc5d904fe69a3081efd7398">Signal</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a9234cc57c43f272b55a94b0069fe62d1">Slot</a>, <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>, <a href="/web-doxygen/docs/api/structs/sqlstmt/#a780c9b733b885100df0aa733b0c66a37">SqlStmt::stmt</a>, <a href="#a8acb7287be03115c56196dd1a1085225">stripQualifiers</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a5fede51b97a819dedf4f83bc2aacbc6a">Typedef</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a0032c6e040cdec6d9c52dc75a790a884">MemberDef::typeString</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a47c14840d8e15331fa420b9b2f757cd9">Variable</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#ae450a2be776cc5d05726bab8354f6d62">MemberDef::virtualness</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#ad03f25174e81a42a617a15195a8867b0">ArgumentList::volatileSpecifier</a> and <a href="#adbab9cdf5d958b7f7ac7b736428974dd">writeMemberTemplateLists</a>.

Referenced by <a href="#a268c5eeaffe97a7ec76839a084b8e6fb">generateSqlite3Section</a>.
</div>
</div>

### generateSqlite3ForModule() {#a2b0628c4001ddb19730a764b29b0be44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void generateSqlite3ForModule (const <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> * mod)</td>
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


<p>Definition at line 2086 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2b0628c4001ddb19730a764b29b0be44">2086</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2b0628c4001ddb19730a764b29b0be44">generateSqlite3ForModule</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *mod)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2087</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2088</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + contained class definitions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2089</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + contained concept definitions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2090</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + member groups</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2091</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + normal members</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2092</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + brief desc</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2093</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + detailed desc</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2094</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + location (file_id, line, column)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2095</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - exports</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2096</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + used files</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2097</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2098</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mod-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>() || mod-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a930740d353cfe143eb9efe0d12b7f938">isHidden</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2099</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a> = <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(mod-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2100</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">(!<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>.created &amp;&amp; <a href="#a19ff8cd8130e662be4112bc914f7b50b">compounddefExists</a>(<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>)){</span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2101</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":rowid"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>.rowid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2102</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":name"</span><span class="doxyHighlight">,mod-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2103</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":kind"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"module"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2104</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2105</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> file_id = <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>(mod-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2106</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":file_id"</span><span class="doxyHighlight">,file_id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2107</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":line"</span><span class="doxyHighlight">,mod-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2108</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":column"</span><span class="doxyHighlight">,mod-&gt;<a href="/web-doxygen/docs/api/classes/definition/#adf0e1ff0eec62741a8ee5d768589ab01">getDefColumn</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2109</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2110</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4f1e96e7c65daf0f86a31c45077697c4">getSQLDescCompound</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":briefdescription"</span><span class="doxyHighlight">,mod-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>(),mod);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2111</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4f1e96e7c65daf0f86a31c45077697c4">getSQLDescCompound</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":detaileddescription"</span><span class="doxyHighlight">,mod-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>(),mod);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2112</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2113</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2114</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2115</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + contained class definitions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2116</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a3b94451a3cd1a0d6cc44e2a9a2118481">writeInnerClasses</a>(mod-&gt;<a href="/web-doxygen/docs/api/classes/moduledef/#aeb422153b08d7da56d56a96acba60370">getClasses</a>(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2117</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2118</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + contained concept definitions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2119</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a46ef1ad7fcb0bd63228beb9a14e7f4bd">writeInnerConcepts</a>(mod-&gt;<a href="/web-doxygen/docs/api/classes/moduledef/#ade149e97f8df65bf64a4833caa43c6de">getConcepts</a>(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2120</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2121</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + member groups</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2122</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mg : mod-&gt;<a href="/web-doxygen/docs/api/classes/moduledef/#a58b6c98c1199174f0cb721735c589d67">getMemberGroups</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2123</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2124</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a268c5eeaffe97a7ec76839a084b8e6fb">generateSqlite3Section</a>(mod,&amp;mg-&gt;members(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>,</span><span class="doxyHighlightStringLiteral">"user-defined"</span><span class="doxyHighlight">,mg-&gt;header(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2125</span><span class="doxyLineContent"><span class="doxyHighlight">        mg-&gt;documentation());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2126</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2127</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2128</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + normal members</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2129</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ml : mod-&gt;<a href="/web-doxygen/docs/api/classes/moduledef/#aabba3ab3dd5ccde53dc5208a768e237d">getMemberLists</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2130</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2131</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ml-&gt;<a href="/web-doxygen/docs/api/classes/memberlist/#aa31a7d651481862036f72381f7e2a96d">listType</a>().<a href="/web-doxygen/docs/api/classes/memberlisttype/#af02c040fbca839a74c6f9cfafb54d6f7">isDeclaration</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2132</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2133</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a268c5eeaffe97a7ec76839a084b8e6fb">generateSqlite3Section</a>(mod,ml.get(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>,</span><span class="doxyHighlightStringLiteral">"user-defined"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2134</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2135</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2136</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2137</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + files</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2138</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a9e4b392824ade3c727f39d6717bdc97f">writeInnerFiles</a>(mod-&gt;<a href="/web-doxygen/docs/api/classes/moduledef/#ac88969f1e19df5e0444bcef41af2ed79">getUsedFiles</a>(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2139</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>, <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">Definition::briefDescription</a>, <a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef&#95;insert</a>, <a href="#a19ff8cd8130e662be4112bc914f7b50b">compounddefExists</a>, <a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">Definition::documentation</a>, <a href="#a268c5eeaffe97a7ec76839a084b8e6fb">generateSqlite3Section</a>, <a href="/web-doxygen/docs/api/classes/moduledef/#aeb422153b08d7da56d56a96acba60370">ModuleDef::getClasses</a>, <a href="/web-doxygen/docs/api/classes/moduledef/#ade149e97f8df65bf64a4833caa43c6de">ModuleDef::getConcepts</a>, <a href="/web-doxygen/docs/api/classes/definition/#adf0e1ff0eec62741a8ee5d768589ab01">Definition::getDefColumn</a>, <a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">Definition::getDefFileName</a>, <a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">Definition::getDefLine</a>, <a href="/web-doxygen/docs/api/classes/moduledef/#a58b6c98c1199174f0cb721735c589d67">ModuleDef::getMemberGroups</a>, <a href="/web-doxygen/docs/api/classes/moduledef/#aabba3ab3dd5ccde53dc5208a768e237d">ModuleDef::getMemberLists</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="#a4f1e96e7c65daf0f86a31c45077697c4">getSQLDescCompound</a>, <a href="/web-doxygen/docs/api/classes/moduledef/#ac88969f1e19df5e0444bcef41af2ed79">ModuleDef::getUsedFiles</a>, <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>, <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>, <a href="/web-doxygen/docs/api/classes/memberlisttype/#af02c040fbca839a74c6f9cfafb54d6f7">MemberListType::isDeclaration</a>, <a href="/web-doxygen/docs/api/classes/definition/#a930740d353cfe143eb9efe0d12b7f938">Definition::isHidden</a>, <a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">Definition::isReference</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#aa31a7d651481862036f72381f7e2a96d">MemberList::listType</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">Refid::refid</a>, <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>, <a href="#a3b94451a3cd1a0d6cc44e2a9a2118481">writeInnerClasses</a>, <a href="#a46ef1ad7fcb0bd63228beb9a14e7f4bd">writeInnerConcepts</a> and <a href="#a9e4b392824ade3c727f39d6717bdc97f">writeInnerFiles</a>.

Referenced by <a href="#ae5b36a2f93dadba9f8c7d762564154e1">generateSqlite3</a>.
</div>
</div>

### generateSqlite3ForNamespace() {#ad5597180db00f8bb26d51d9b3b409241}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void generateSqlite3ForNamespace (const <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> * nd)</td>
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


<p>Definition at line 2142 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad5597180db00f8bb26d51d9b3b409241">2142</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad5597180db00f8bb26d51d9b3b409241">generateSqlite3ForNamespace</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *nd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2143</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2144</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + contained class definitions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2145</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + contained namespace definitions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2146</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + member groups</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2147</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + normal members</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2148</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + brief desc</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2149</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + detailed desc</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2150</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + location (file_id, line, column)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2151</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - files containing (parts of) the namespace definition</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2152</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2153</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>() || nd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a930740d353cfe143eb9efe0d12b7f938">isHidden</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// skip external references</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2154</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a> = <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(nd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2155</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">(!<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>.created &amp;&amp; <a href="#a19ff8cd8130e662be4112bc914f7b50b">compounddefExists</a>(<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>)){</span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2156</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":rowid"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>.rowid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2157</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2158</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":name"</span><span class="doxyHighlight">,nd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2159</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":title"</span><span class="doxyHighlight">,nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#ac592520c3e9e8f2e633b2fae7375ccae">title</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2160</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":kind"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"namespace"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2161</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2162</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> file_id = <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>(nd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2163</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":file_id"</span><span class="doxyHighlight">,file_id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2164</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":line"</span><span class="doxyHighlight">,nd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2165</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":column"</span><span class="doxyHighlight">,nd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#adf0e1ff0eec62741a8ee5d768589ab01">getDefColumn</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2166</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2167</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4f1e96e7c65daf0f86a31c45077697c4">getSQLDescCompound</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":briefdescription"</span><span class="doxyHighlight">,nd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>(),nd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2168</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4f1e96e7c65daf0f86a31c45077697c4">getSQLDescCompound</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":detaileddescription"</span><span class="doxyHighlight">,nd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>(),nd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2169</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2170</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2171</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2172</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + contained class definitions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2173</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a3b94451a3cd1a0d6cc44e2a9a2118481">writeInnerClasses</a>(nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#ad43237a69f056b45fc87beed091688d5">getClasses</a>(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2174</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2175</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + contained concept definitions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2176</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a46ef1ad7fcb0bd63228beb9a14e7f4bd">writeInnerConcepts</a>(nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#a393d5ddac9a98c0f829b7866cce931dc">getConcepts</a>(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2177</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2178</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + contained namespace definitions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2179</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a597b4509789d2af90e78fe008fa832ab">writeInnerNamespaces</a>(nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#a948889b7a35fb82ebcdf2598a63e1d8d">getNamespaces</a>(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2180</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2181</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + member groups</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2182</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mg : nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#aedf62c808c557f44997b866855615199">getMemberGroups</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2183</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2184</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a268c5eeaffe97a7ec76839a084b8e6fb">generateSqlite3Section</a>(nd,&amp;mg-&gt;members(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>,</span><span class="doxyHighlightStringLiteral">"user-defined"</span><span class="doxyHighlight">,mg-&gt;header(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2185</span><span class="doxyLineContent"><span class="doxyHighlight">        mg-&gt;documentation());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2186</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2187</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2188</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + normal members</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2189</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ml : nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#a8d1b06c7331164f6562cb5f19d69c023">getMemberLists</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2190</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2191</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ml-&gt;<a href="/web-doxygen/docs/api/classes/memberlist/#aa31a7d651481862036f72381f7e2a96d">listType</a>().<a href="/web-doxygen/docs/api/classes/memberlisttype/#af02c040fbca839a74c6f9cfafb54d6f7">isDeclaration</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2192</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2193</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a268c5eeaffe97a7ec76839a084b8e6fb">generateSqlite3Section</a>(nd,ml.get(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>,</span><span class="doxyHighlightStringLiteral">"user-defined"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2194</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2195</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2196</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>, <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">Definition::briefDescription</a>, <a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef&#95;insert</a>, <a href="#a19ff8cd8130e662be4112bc914f7b50b">compounddefExists</a>, <a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">Definition::documentation</a>, <a href="#a268c5eeaffe97a7ec76839a084b8e6fb">generateSqlite3Section</a>, <a href="/web-doxygen/docs/api/classes/namespacedef/#ad43237a69f056b45fc87beed091688d5">NamespaceDef::getClasses</a>, <a href="/web-doxygen/docs/api/classes/namespacedef/#a393d5ddac9a98c0f829b7866cce931dc">NamespaceDef::getConcepts</a>, <a href="/web-doxygen/docs/api/classes/definition/#adf0e1ff0eec62741a8ee5d768589ab01">Definition::getDefColumn</a>, <a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">Definition::getDefFileName</a>, <a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">Definition::getDefLine</a>, <a href="/web-doxygen/docs/api/classes/namespacedef/#aedf62c808c557f44997b866855615199">NamespaceDef::getMemberGroups</a>, <a href="/web-doxygen/docs/api/classes/namespacedef/#a8d1b06c7331164f6562cb5f19d69c023">NamespaceDef::getMemberLists</a>, <a href="/web-doxygen/docs/api/classes/namespacedef/#a948889b7a35fb82ebcdf2598a63e1d8d">NamespaceDef::getNamespaces</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="#a4f1e96e7c65daf0f86a31c45077697c4">getSQLDescCompound</a>, <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>, <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>, <a href="/web-doxygen/docs/api/classes/memberlisttype/#af02c040fbca839a74c6f9cfafb54d6f7">MemberListType::isDeclaration</a>, <a href="/web-doxygen/docs/api/classes/definition/#a930740d353cfe143eb9efe0d12b7f938">Definition::isHidden</a>, <a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">Definition::isReference</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#aa31a7d651481862036f72381f7e2a96d">MemberList::listType</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">Refid::refid</a>, <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>, <a href="/web-doxygen/docs/api/classes/namespacedef/#ac592520c3e9e8f2e633b2fae7375ccae">NamespaceDef::title</a>, <a href="#a3b94451a3cd1a0d6cc44e2a9a2118481">writeInnerClasses</a>, <a href="#a46ef1ad7fcb0bd63228beb9a14e7f4bd">writeInnerConcepts</a> and <a href="#a597b4509789d2af90e78fe008fa832ab">writeInnerNamespaces</a>.

Referenced by <a href="#ae5b36a2f93dadba9f8c7d762564154e1">generateSqlite3</a>.
</div>
</div>

### generateSqlite3ForPage() {#aeb4c1aeb9fc32917845d0d05a52cb478}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void generateSqlite3ForPage (const <a href="/web-doxygen/docs/api/classes/pagedef">PageDef</a> * pd, bool isExample)</td>
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


<p>Definition at line 2468 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aeb4c1aeb9fc32917845d0d05a52cb478">2468</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aeb4c1aeb9fc32917845d0d05a52cb478">generateSqlite3ForPage</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/pagedef">PageDef</a> *pd,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isExample)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2469</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2470</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2471</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + title</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2472</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + brief description</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2473</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + documentation (detailed description)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2474</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + inbody documentation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2475</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + sub pages</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2476</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// skip external references.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2477</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2478</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// TODO: do we more special handling if isExample?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2479</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2480</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> qrefid = pd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2481</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pd-&gt;<a href="/web-doxygen/docs/api/classes/pagedef/#acd024899a0d21128490483d8cce009a1">getGroupDef</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2482</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2483</span><span class="doxyLineContent"><span class="doxyHighlight">    qrefid+=</span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight">+pd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2484</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2485</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (qrefid==</span><span class="doxyHighlightStringLiteral">"index"</span><span class="doxyHighlight">) qrefid=</span><span class="doxyHighlightStringLiteral">"indexpage"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// to prevent overwriting the generated index page.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2486</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2487</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a> = <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(qrefid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2488</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2489</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// can omit a page that already has a refid</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2490</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">(!<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>.created &amp;&amp; <a href="#a19ff8cd8130e662be4112bc914f7b50b">compounddefExists</a>(<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>)){</span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2491</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2492</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":rowid"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>.rowid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2493</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2494</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":name"</span><span class="doxyHighlight">,pd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2495</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2496</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> title;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2497</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pd==<a href="/web-doxygen/docs/api/classes/doxygen/#a2cc3616eca3e3c550a211d8b1eaf4661">Doxygen::mainPage</a>.get()) </span><span class="doxyHighlightComment">// main page is special</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2498</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2499</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/util-cpp/#a1d56f22de057d96035949f029dd6e4e8">mainPageHasTitle</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2500</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2501</span><span class="doxyLineContent"><span class="doxyHighlight">      title = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a747a6ad366ae4d5d42f0c551079d0bf5">filterTitle</a>(<a href="/web-doxygen/docs/api/files/src/util-cpp/#afb36c9b4d9962a775c9113434fedd520">convertCharEntitiesToUTF8</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#a2cc3616eca3e3c550a211d8b1eaf4661">Doxygen::mainPage</a>-&gt;title()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2502</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2503</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2504</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2505</span><span class="doxyLineContent"><span class="doxyHighlight">      title = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(PROJECT_NAME);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2506</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2507</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2508</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2509</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2510</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> *si = <a href="/web-doxygen/docs/api/classes/sectionmanager/#afcf31c2b2bad467541c924342b08773d">SectionManager::instance</a>().<a href="/web-doxygen/docs/api/classes/linkedmap/#ad7659775b7de962b4fe0921456baf4f4">find</a>(pd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2511</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (si)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2512</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2513</span><span class="doxyLineContent"><span class="doxyHighlight">      title = si-&gt;<a href="/web-doxygen/docs/api/classes/sectioninfo/#ac6aefd1d628bbdb94dc3b8e176a72f9b">title</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2514</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2515</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (title.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2516</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2517</span><span class="doxyLineContent"><span class="doxyHighlight">      title = pd-&gt;<a href="/web-doxygen/docs/api/classes/pagedef/#aae487f3fd3ce36b104cb6b82e287cfaa">title</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2518</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2519</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2520</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2521</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + title</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2522</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":title"</span><span class="doxyHighlight">,title);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2523</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2524</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":kind"</span><span class="doxyHighlight">, isExample ? </span><span class="doxyHighlightStringLiteral">"example"</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">"page"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2525</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2526</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> file_id = <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>(pd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2527</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2528</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":file_id"</span><span class="doxyHighlight">,file_id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2529</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":line"</span><span class="doxyHighlight">,pd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2530</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":column"</span><span class="doxyHighlight">,pd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#adf0e1ff0eec62741a8ee5d768589ab01">getDefColumn</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2531</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2532</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + brief description</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2533</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a309fe09ee4c594f158d4e9873ca1e6b6">getSQLDesc</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":briefdescription"</span><span class="doxyHighlight">,pd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>(),pd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2534</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + documentation (detailed description)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2535</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a309fe09ee4c594f158d4e9873ca1e6b6">getSQLDesc</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>,</span><span class="doxyHighlightStringLiteral">":detaileddescription"</span><span class="doxyHighlight">,pd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>(),pd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2536</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2537</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2538</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + sub pages</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2539</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4b9d2814806d6388bddc5f4c141d8fbf">writeInnerPages</a>(pd-&gt;<a href="/web-doxygen/docs/api/classes/pagedef/#a6d750d1618399ff76e2fbc0d4b74e62f">getSubPages</a>(),<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2540</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>, <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">Definition::briefDescription</a>, <a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef&#95;insert</a>, <a href="#a19ff8cd8130e662be4112bc914f7b50b">compounddefExists</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#afb36c9b4d9962a775c9113434fedd520">convertCharEntitiesToUTF8</a>, <a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">Definition::documentation</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a747a6ad366ae4d5d42f0c551079d0bf5">filterTitle</a>, <a href="/web-doxygen/docs/api/classes/linkedmap/#ad7659775b7de962b4fe0921456baf4f4">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>, <a href="/web-doxygen/docs/api/classes/definition/#adf0e1ff0eec62741a8ee5d768589ab01">Definition::getDefColumn</a>, <a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">Definition::getDefFileName</a>, <a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">Definition::getDefLine</a>, <a href="/web-doxygen/docs/api/classes/pagedef/#acd024899a0d21128490483d8cce009a1">PageDef::getGroupDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="#a309fe09ee4c594f158d4e9873ca1e6b6">getSQLDesc</a>, <a href="/web-doxygen/docs/api/classes/pagedef/#a6d750d1618399ff76e2fbc0d4b74e62f">PageDef::getSubPages</a>, <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>, <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>, <a href="/web-doxygen/docs/api/classes/sectionmanager/#afcf31c2b2bad467541c924342b08773d">SectionManager::instance</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">Definition::isReference</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a2cc3616eca3e3c550a211d8b1eaf4661">Doxygen::mainPage</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1d56f22de057d96035949f029dd6e4e8">mainPageHasTitle</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">Refid::refid</a>, <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>, <a href="/web-doxygen/docs/api/classes/pagedef/#aae487f3fd3ce36b104cb6b82e287cfaa">PageDef::title</a>, <a href="/web-doxygen/docs/api/classes/sectioninfo/#ac6aefd1d628bbdb94dc3b8e176a72f9b">SectionInfo::title</a> and <a href="#a4b9d2814806d6388bddc5f4c141d8fbf">writeInnerPages</a>.

Referenced by <a href="#ae5b36a2f93dadba9f8c7d762564154e1">generateSqlite3</a>.
</div>
</div>

### generateSqlite3Section() {#a268c5eeaffe97a7ec76839a084b8e6fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void generateSqlite3Section (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d, const <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> * ml, struct <a href="/web-doxygen/docs/api/structs/refid">Refid</a> scope_refid, const char *, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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


<p>Definition at line 1878 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a268c5eeaffe97a7ec76839a084b8e6fb">1878</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a268c5eeaffe97a7ec76839a084b8e6fb">generateSqlite3Section</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1879</span><span class="doxyLineContent"><span class="doxyHighlight">                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> *ml,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1880</span><span class="doxyLineContent"><span class="doxyHighlight">                      </span><span class="doxyHighlightKeyword">struct</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/refid">Refid</a> scope_refid,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1881</span><span class="doxyLineContent"><span class="doxyHighlight">                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> * </span><span class="doxyHighlightComment">/*kind*/</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1882</span><span class="doxyLineContent"><span class="doxyHighlight">                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; </span><span class="doxyHighlightComment">/*header*/</span><span class="doxyHighlight">=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1883</span><span class="doxyLineContent"><span class="doxyHighlight">                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; </span><span class="doxyHighlightComment">/*documentation*/</span><span class="doxyHighlight">=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1884</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1885</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ml==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1886</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;md : *ml)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1887</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1888</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// TODO: necessary? just tracking what xmlgen does; xmlgen says:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1889</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// namespace members are also inserted in the file scope, but</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1890</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// to prevent this duplication in the XML output, we filter those here.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1891</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()!=<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea203462c7d34ced15beac624562c2708e">Definition::TypeFile</a> || md-&gt;getNamespaceDef()==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1892</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1893</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>(md, scope_refid, d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1894</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1895</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1896</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">Definition::definitionType</a>, <a href="#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a> and <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea203462c7d34ced15beac624562c2708e">Definition::TypeFile</a>.

Referenced by <a href="#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>, <a href="#ae7139b08c0c942d65c6bcb8402a8b142">generateSqlite3ForFile</a>, <a href="#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a>, <a href="#a2b0628c4001ddb19730a764b29b0be44">generateSqlite3ForModule</a> and <a href="#ad5597180db00f8bb26d51d9b3b409241">generateSqlite3ForNamespace</a>.
</div>
</div>

### getSQLDesc() {#a309fe09ee4c594f158d4e9873ca1e6b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void getSQLDesc (<a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> &amp; s, const char * col, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; value, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * def)</td>
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


<p>Definition at line 1448 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a309fe09ee4c594f158d4e9873ca1e6b6">1448</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a309fe09ee4c594f158d4e9873ca1e6b6">getSQLDesc</a>(<a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> &amp;s,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *col,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;value,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *def)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1449</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1450</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1451</span><span class="doxyLineContent"><span class="doxyHighlight">    s,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1452</span><span class="doxyLineContent"><span class="doxyHighlight">    col,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1453</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a088166e0f872cd290425780f4b5c45f6">getSQLDocBlock</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1454</span><span class="doxyLineContent"><span class="doxyHighlight">      def-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1455</span><span class="doxyLineContent"><span class="doxyHighlight">      def,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1456</span><span class="doxyLineContent"><span class="doxyHighlight">      value,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1457</span><span class="doxyLineContent"><span class="doxyHighlight">      def-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a00915f52f3b708bec07aab2b44f03d34">docFile</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1458</span><span class="doxyLineContent"><span class="doxyHighlight">      def-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a26a4a6e3578aa6c81b2d6d77a1ce694f">docLine</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1459</span><span class="doxyLineContent"><span class="doxyHighlight">    )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1460</span><span class="doxyLineContent"><span class="doxyHighlight">  );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1461</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>, <a href="/web-doxygen/docs/api/classes/definition/#a00915f52f3b708bec07aab2b44f03d34">Definition::docFile</a>, <a href="/web-doxygen/docs/api/classes/definition/#a26a4a6e3578aa6c81b2d6d77a1ce694f">Definition::docLine</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">Definition::getOuterScope</a> and <a href="#a088166e0f872cd290425780f4b5c45f6">getSQLDocBlock</a>.

Referenced by <a href="#a96d60ce1da0cc36d049c1a2bbc174178">generateSqlite3ForDir</a>, <a href="#ae7139b08c0c942d65c6bcb8402a8b142">generateSqlite3ForFile</a>, <a href="#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a>, <a href="#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a> and <a href="#aeb4c1aeb9fc32917845d0d05a52cb478">generateSqlite3ForPage</a>.
</div>
</div>

### getSQLDescCompound() {#a4f1e96e7c65daf0f86a31c45077697c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void getSQLDescCompound (<a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> &amp; s, const char * col, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; value, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * def)</td>
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


<p>Definition at line 1463 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4f1e96e7c65daf0f86a31c45077697c4">1463</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4f1e96e7c65daf0f86a31c45077697c4">getSQLDescCompound</a>(<a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> &amp;s,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *col,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;value,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *def)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1464</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1465</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1466</span><span class="doxyLineContent"><span class="doxyHighlight">    s,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1467</span><span class="doxyLineContent"><span class="doxyHighlight">    col,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1468</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a088166e0f872cd290425780f4b5c45f6">getSQLDocBlock</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1469</span><span class="doxyLineContent"><span class="doxyHighlight">      def,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1470</span><span class="doxyLineContent"><span class="doxyHighlight">      def,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1471</span><span class="doxyLineContent"><span class="doxyHighlight">      value,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1472</span><span class="doxyLineContent"><span class="doxyHighlight">      def-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a00915f52f3b708bec07aab2b44f03d34">docFile</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1473</span><span class="doxyLineContent"><span class="doxyHighlight">      def-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a26a4a6e3578aa6c81b2d6d77a1ce694f">docLine</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1474</span><span class="doxyLineContent"><span class="doxyHighlight">    )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1475</span><span class="doxyLineContent"><span class="doxyHighlight">  );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1476</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>, <a href="/web-doxygen/docs/api/classes/definition/#a00915f52f3b708bec07aab2b44f03d34">Definition::docFile</a>, <a href="/web-doxygen/docs/api/classes/definition/#a26a4a6e3578aa6c81b2d6d77a1ce694f">Definition::docLine</a> and <a href="#a088166e0f872cd290425780f4b5c45f6">getSQLDocBlock</a>.

Referenced by <a href="#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>, <a href="#a3889d30b147517190ccd9c1ebb9ca785">generateSqlite3ForConcept</a>, <a href="#a2b0628c4001ddb19730a764b29b0be44">generateSqlite3ForModule</a> and <a href="#ad5597180db00f8bb26d51d9b3b409241">generateSqlite3ForNamespace</a>.
</div>
</div>

### getSQLDocBlock() {#a088166e0f872cd290425780f4b5c45f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString getSQLDocBlock (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * scope, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * def, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; doc, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, int lineNr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1412 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a088166e0f872cd290425780f4b5c45f6">1412</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a088166e0f872cd290425780f4b5c45f6">getSQLDocBlock</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *scope,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1413</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *def,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1414</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;doc,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1415</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1416</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1417</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1418</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1419</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1420</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1421</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> parser { <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a7a169cbf0edeed85c90868675799b875">createDocParser</a>() };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1422</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> ast    { <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1423</span><span class="doxyLineContent"><span class="doxyHighlight">                *parser.get(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1424</span><span class="doxyLineContent"><span class="doxyHighlight">                fileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1425</span><span class="doxyLineContent"><span class="doxyHighlight">                lineNr,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1426</span><span class="doxyLineContent"><span class="doxyHighlight">                scope,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1427</span><span class="doxyLineContent"><span class="doxyHighlight">                <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>(def),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1428</span><span class="doxyLineContent"><span class="doxyHighlight">                doc,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1429</span><span class="doxyLineContent"><span class="doxyHighlight">                <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1430</span><span class="doxyLineContent"><span class="doxyHighlight">                <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1431</span><span class="doxyLineContent"><span class="doxyHighlight">                <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1432</span><span class="doxyLineContent"><span class="doxyHighlight">                <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1433</span><span class="doxyLineContent"><span class="doxyHighlight">                <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1434</span><span class="doxyLineContent"><span class="doxyHighlight">              };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1435</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> astImpl = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/docnodeast">DocNodeAST</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(ast.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1436</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (astImpl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1437</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1438</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> xmlCodeList;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1439</span><span class="doxyLineContent"><span class="doxyHighlight">    xmlCodeList.<a href="/web-doxygen/docs/api/classes/outputcodelist/#a60b7d69b02fe400d0111a3321c9f0265">add</a>&lt;<a href="/web-doxygen/docs/api/classes/xmlcodegenerator">XMLCodeGenerator</a>&gt;(&amp;t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1440</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// create a parse tree visitor for XML</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1441</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/xmldocvisitor">XmlDocVisitor</a> visitor(t,xmlCodeList,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1442</span><span class="doxyLineContent"><span class="doxyHighlight">        scope ? scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#adbe53b15923a143881154dd7c0f04f9b">getDefFileExtension</a>() : <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1443</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(visitor,astImpl-&gt;root);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1444</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1445</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/util-cpp/#afb36c9b4d9962a775c9113434fedd520">convertCharEntitiesToUTF8</a>(t.<a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">str</a>().c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1446</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/outputcodelist/#a60b7d69b02fe400d0111a3321c9f0265">OutputCodeList::add</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#afb36c9b4d9962a775c9113434fedd520">convertCharEntitiesToUTF8</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a7a169cbf0edeed85c90868675799b875">createDocParser</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/definition/#adbe53b15923a143881154dd7c0f04f9b">Definition::getDefFileExtension</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">TextStream::str</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>.

Referenced by <a href="#a309fe09ee4c594f158d4e9873ca1e6b6">getSQLDesc</a> and <a href="#a4f1e96e7c65daf0f86a31c45077697c4">getSQLDescCompound</a>.
</div>
</div>

### initializeTables() {#a2413f906680d7e55e863d1f4d7385a84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int initializeTables (sqlite3 * db)</td>
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


<p>Definition at line 1214 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2413f906680d7e55e863d1f4d7385a84">1214</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a2413f906680d7e55e863d1f4d7385a84">initializeTables</a>(sqlite3* db)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1215</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1216</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Initializing DB schema (tables)...\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1217</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> k = 0; k &lt; </span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(<a href="#a7b91ef07fa780f5b7c37c73863df5e11">table_schema</a>) / </span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(<a href="#a7b91ef07fa780f5b7c37c73863df5e11">table_schema</a>[0]); k++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1218</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1219</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *q = <a href="#a7b91ef07fa780f5b7c37c73863df5e11">table_schema</a>[k][1];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1220</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *errmsg = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1221</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> rc = sqlite3_exec(db, q, </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, &amp;errmsg);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1222</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rc != SQLITE_OK)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1223</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1224</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"failed to execute query: {}\n\t{}\n"</span><span class="doxyHighlight">, q, errmsg);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1225</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1226</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1227</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1228</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1229</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a> and <a href="#a7b91ef07fa780f5b7c37c73863df5e11">table&#95;schema</a>.

Referenced by <a href="#ae5b36a2f93dadba9f8c7d762564154e1">generateSqlite3</a>.
</div>
</div>

### initializeViews() {#aa9037481dd7efb932a1f5dc142922330}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int initializeViews (sqlite3 * db)</td>
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


<p>Definition at line 1231 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa9037481dd7efb932a1f5dc142922330">1231</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#aa9037481dd7efb932a1f5dc142922330">initializeViews</a>(sqlite3* db)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1232</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1233</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Initializing DB schema (views)...\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1234</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> k = 0; k &lt; </span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(<a href="#a9b595d98aef36283b3ea75fdd312ed5c">view_schema</a>) / </span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(<a href="#a9b595d98aef36283b3ea75fdd312ed5c">view_schema</a>[0]); k++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1235</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1236</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *q = <a href="#a9b595d98aef36283b3ea75fdd312ed5c">view_schema</a>[k][1];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1237</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *errmsg = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1238</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> rc = sqlite3_exec(db, q, </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, &amp;errmsg);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1239</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rc != SQLITE_OK)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1240</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1241</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"failed to execute query: {}\n\t{}\n"</span><span class="doxyHighlight">, q, errmsg);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1242</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1243</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1244</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1245</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1246</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a> and <a href="#a9b595d98aef36283b3ea75fdd312ed5c">view&#95;schema</a>.

Referenced by <a href="#ae5b36a2f93dadba9f8c7d762564154e1">generateSqlite3</a>.
</div>
</div>

### insertMemberDefineParams() {#a6ff307313c1b28d89ef63fef3590ad36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void insertMemberDefineParams (int memberdef_id, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * def)</td>
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


<p>Definition at line 1097 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6ff307313c1b28d89ef63fef3590ad36">1097</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6ff307313c1b28d89ef63fef3590ad36">insertMemberDefineParams</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> memberdef_id,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *def)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1098</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1099</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">argumentList</a>().<a href="/web-doxygen/docs/api/classes/argumentlist/#aaa15ddcfdb06a535a3398f1dc73d336d">empty</a>()) </span><span class="doxyHighlightComment">// special case for "foo()" to</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1100</span><span class="doxyLineContent"><span class="doxyHighlight">                                    </span><span class="doxyHighlightComment">// distinguish it from "foo".</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1101</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1102</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((</span><span class="doxyHighlightStringLiteral">"no params\n"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1103</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1104</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1105</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1106</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;a : md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">argumentList</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1107</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1108</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#aeff7609bbf258f9fe7bb792def0251d6">param_insert</a>,</span><span class="doxyHighlightStringLiteral">":defname"</span><span class="doxyHighlight">,a.type);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1109</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> param_id=<a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#aeff7609bbf258f9fe7bb792def0251d6">param_insert</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1110</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (param_id==-1) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1111</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1112</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1113</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1114</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a9fd0d6eb855cc81bc77248083bc52316">memberdef_param_insert</a>,</span><span class="doxyHighlightStringLiteral">":memberdef_id"</span><span class="doxyHighlight">,memberdef_id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1115</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a9fd0d6eb855cc81bc77248083bc52316">memberdef_param_insert</a>,</span><span class="doxyHighlightStringLiteral">":param_id"</span><span class="doxyHighlight">,param_id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1116</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#a9fd0d6eb855cc81bc77248083bc52316">memberdef_param_insert</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1117</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1118</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1119</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">MemberDef::argumentList</a>, <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>, <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>, <a href="#a234e2efe67eececd88b140b46ea37463">DBG&#95;CTX</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#aaa15ddcfdb06a535a3398f1dc73d336d">ArgumentList::empty</a>, <a href="#a9fd0d6eb855cc81bc77248083bc52316">memberdef&#95;param&#95;insert</a>, <a href="#aeff7609bbf258f9fe7bb792def0251d6">param&#95;insert</a>, <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>.
</div>
</div>

### insertMemberFunctionParams() {#a3a9064a0bd3f19c550c68c5839dec5a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void insertMemberFunctionParams (int memberdef_id, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * def)</td>
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


<p>Definition at line 1021 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3a9064a0bd3f19c550c68c5839dec5a6">1021</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3a9064a0bd3f19c550c68c5839dec5a6">insertMemberFunctionParams</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> memberdef_id, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *def)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1022</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1023</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;declAl = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#af0d0461390544ad385a962aefd88c313">declArgumentList</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1024</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;defAl = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">argumentList</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1025</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (declAl.<a href="/web-doxygen/docs/api/classes/argumentlist/#a4d651caeb995400fad17d4ab4a020a3a">size</a>()&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1026</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1027</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> defIt = defAl.<a href="/web-doxygen/docs/api/classes/argumentlist/#acc52d012d093df1adede055164f69dc9">begin</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1028</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;a : declAl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1029</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1030</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//const Argument *defArg = defAli.current();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1031</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/argument">Argument</a> *defArg = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1032</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (defIt!=defAl.<a href="/web-doxygen/docs/api/classes/argumentlist/#a215181845c0d9f0525806a4165c4f552">end</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1033</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1034</span><span class="doxyLineContent"><span class="doxyHighlight">        defArg = &amp;(*defIt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1035</span><span class="doxyLineContent"><span class="doxyHighlight">        ++defIt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1036</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1037</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1038</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!a.attrib.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1039</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1040</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#a5615e9549a34565e146c795f7879a70c">param_select</a>,</span><span class="doxyHighlightStringLiteral">":attributes"</span><span class="doxyHighlight">,a.attrib);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1041</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#aeff7609bbf258f9fe7bb792def0251d6">param_insert</a>,</span><span class="doxyHighlightStringLiteral">":attributes"</span><span class="doxyHighlight">,a.attrib);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1042</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1043</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!a.type.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1044</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1045</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> list;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1046</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a>(<a href="/web-doxygen/docs/api/classes/textgeneratorsqlite3impl">TextGeneratorSqlite3Impl</a>(list),def,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a7ea253be90981d4a6f0cfdb6dff1d2fd">getBodyDef</a>(),md,a.type);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1047</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1048</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;s : list)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1049</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1050</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> qsrc_refid = md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>() + </span><span class="doxyHighlightStringLiteral">"_1"</span><span class="doxyHighlight"> + md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1051</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> src_refid = <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(qsrc_refid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1052</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> dst_refid = <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(s.c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1053</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a204b468b29a5d8ae8cf305cc08766eb7">insertMemberReference</a>(src_refid,dst_refid, </span><span class="doxyHighlightStringLiteral">"argument"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1054</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1055</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#a5615e9549a34565e146c795f7879a70c">param_select</a>,</span><span class="doxyHighlightStringLiteral">":type"</span><span class="doxyHighlight">,a.type);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1056</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#aeff7609bbf258f9fe7bb792def0251d6">param_insert</a>,</span><span class="doxyHighlightStringLiteral">":type"</span><span class="doxyHighlight">,a.type);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1057</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1058</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!a.name.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1059</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1060</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#a5615e9549a34565e146c795f7879a70c">param_select</a>,</span><span class="doxyHighlightStringLiteral">":declname"</span><span class="doxyHighlight">,a.name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1061</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#aeff7609bbf258f9fe7bb792def0251d6">param_insert</a>,</span><span class="doxyHighlightStringLiteral">":declname"</span><span class="doxyHighlight">,a.name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1062</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1063</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (defArg &amp;&amp; !defArg-&gt;<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; defArg-&gt;<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a>!=a.name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1064</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1065</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#a5615e9549a34565e146c795f7879a70c">param_select</a>,</span><span class="doxyHighlightStringLiteral">":defname"</span><span class="doxyHighlight">,defArg-&gt;<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1066</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#aeff7609bbf258f9fe7bb792def0251d6">param_insert</a>,</span><span class="doxyHighlightStringLiteral">":defname"</span><span class="doxyHighlight">,defArg-&gt;<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1067</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1068</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!a.array.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1069</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1070</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#a5615e9549a34565e146c795f7879a70c">param_select</a>,</span><span class="doxyHighlightStringLiteral">":array"</span><span class="doxyHighlight">,a.array);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1071</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#aeff7609bbf258f9fe7bb792def0251d6">param_insert</a>,</span><span class="doxyHighlightStringLiteral">":array"</span><span class="doxyHighlight">,a.array);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1072</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1073</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!a.defval.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1074</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1075</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> list;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1076</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a>(<a href="/web-doxygen/docs/api/classes/textgeneratorsqlite3impl">TextGeneratorSqlite3Impl</a>(list),def,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a7ea253be90981d4a6f0cfdb6dff1d2fd">getBodyDef</a>(),md,a.defval);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1077</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#a5615e9549a34565e146c795f7879a70c">param_select</a>,</span><span class="doxyHighlightStringLiteral">":defval"</span><span class="doxyHighlight">,a.defval);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1078</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#aeff7609bbf258f9fe7bb792def0251d6">param_insert</a>,</span><span class="doxyHighlightStringLiteral">":defval"</span><span class="doxyHighlight">,a.defval);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1079</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1080</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1081</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> param_id=<a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#a5615e9549a34565e146c795f7879a70c">param_select</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1082</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (param_id==0) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1083</span><span class="doxyLineContent"><span class="doxyHighlight">        param_id=<a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#aeff7609bbf258f9fe7bb792def0251d6">param_insert</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1084</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1085</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (param_id==-1) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1086</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((</span><span class="doxyHighlightStringLiteral">"error INSERT params failed\n"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1087</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1088</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1089</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1090</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a9fd0d6eb855cc81bc77248083bc52316">memberdef_param_insert</a>,</span><span class="doxyHighlightStringLiteral">":memberdef_id"</span><span class="doxyHighlight">,memberdef_id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1091</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a9fd0d6eb855cc81bc77248083bc52316">memberdef_param_insert</a>,</span><span class="doxyHighlightStringLiteral">":param_id"</span><span class="doxyHighlight">,param_id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1092</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#a9fd0d6eb855cc81bc77248083bc52316">memberdef_param_insert</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1093</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1094</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1095</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">Definition::anchor</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">MemberDef::argumentList</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#acc52d012d093df1adede055164f69dc9">ArgumentList::begin</a>, <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>, <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>, <a href="#a234e2efe67eececd88b140b46ea37463">DBG&#95;CTX</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#af0d0461390544ad385a962aefd88c313">MemberDef::declArgumentList</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#a215181845c0d9f0525806a4165c4f552">ArgumentList::end</a>, <a href="/web-doxygen/docs/api/classes/definition/#a7ea253be90981d4a6f0cfdb6dff1d2fd">Definition::getBodyDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="#a204b468b29a5d8ae8cf305cc08766eb7">insertMemberReference</a>, <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a>, <a href="#a9fd0d6eb855cc81bc77248083bc52316">memberdef&#95;param&#95;insert</a>, <a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">Argument::name</a>, <a href="#aeff7609bbf258f9fe7bb792def0251d6">param&#95;insert</a>, <a href="#a5615e9549a34565e146c795f7879a70c">param&#95;select</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#a4d651caeb995400fad17d4ab4a020a3a">ArgumentList::size</a>, <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>.
</div>
</div>

### insertMemberReference() {#a204b468b29a5d8ae8cf305cc08766eb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool insertMemberReference (struct <a href="/web-doxygen/docs/api/structs/refid">Refid</a> src_refid, struct <a href="/web-doxygen/docs/api/structs/refid">Refid</a> dst_refid, const char * context)</td>
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


<p>Definition at line 990 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a204b468b29a5d8ae8cf305cc08766eb7">990</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a204b468b29a5d8ae8cf305cc08766eb7">insertMemberReference</a>(</span><span class="doxyHighlightKeyword">struct</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/refid">Refid</a> src_refid, </span><span class="doxyHighlightKeyword">struct</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/refid">Refid</a> dst_refid, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *context)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">991</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">992</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (src_refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>==-1||dst_refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>==-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">993</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">994</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">995</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">996</span><span class="doxyLineContent"><span class="doxyHighlight">     !<a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a669c1f1c7bd2b5cfe3bc3e9294e81be9">xrefs_insert</a>,</span><span class="doxyHighlightStringLiteral">":src_rowid"</span><span class="doxyHighlight">,src_refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">997</span><span class="doxyLineContent"><span class="doxyHighlight">     !<a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a669c1f1c7bd2b5cfe3bc3e9294e81be9">xrefs_insert</a>,</span><span class="doxyHighlightStringLiteral">":dst_rowid"</span><span class="doxyHighlight">,dst_refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">998</span><span class="doxyLineContent"><span class="doxyHighlight">     )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">999</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1000</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1001</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1002</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1003</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1004</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#a669c1f1c7bd2b5cfe3bc3e9294e81be9">xrefs_insert</a>,</span><span class="doxyHighlightStringLiteral">":context"</span><span class="doxyHighlight">,context);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1005</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1006</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1007</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#a669c1f1c7bd2b5cfe3bc3e9294e81be9">xrefs_insert</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1008</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1009</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>, <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>, <a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">Refid::rowid</a>, <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a> and <a href="#a669c1f1c7bd2b5cfe3bc3e9294e81be9">xrefs&#95;insert</a>.

Referenced by <a href="#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="#a3a9064a0bd3f19c550c68c5839dec5a6">insertMemberFunctionParams</a> and <a href="#ae10406df98d50bc1f5d58c0be3427202">insertMemberReference</a>.
</div>
</div>

### insertMemberReference() {#ae10406df98d50bc1f5d58c0be3427202}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void insertMemberReference (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * src, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * dst, const char * context)</td>
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


<p>Definition at line 1011 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae10406df98d50bc1f5d58c0be3427202">1011</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a204b468b29a5d8ae8cf305cc08766eb7">insertMemberReference</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *src, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *dst, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *context)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1012</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1013</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> qdst_refid = dst-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>() + </span><span class="doxyHighlightStringLiteral">"_1"</span><span class="doxyHighlight"> + dst-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1014</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> qsrc_refid = src-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>() + </span><span class="doxyHighlightStringLiteral">"_1"</span><span class="doxyHighlight"> + src-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1015</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1016</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> src_refid = <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(qsrc_refid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1017</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> dst_refid = <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(qdst_refid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1018</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a204b468b29a5d8ae8cf305cc08766eb7">insertMemberReference</a>(src_refid,dst_refid,context);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1019</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">Definition::anchor</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="#a204b468b29a5d8ae8cf305cc08766eb7">insertMemberReference</a> and <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>.
</div>
</div>

### insertPath() {#a5335bb36c398920d8075493f1aedc119}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int insertPath (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name, bool local=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, bool found=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, int type=1)</td>
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


<p>Definition at line 910 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5335bb36c398920d8075493f1aedc119">910</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> local=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> found=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> type=1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">911</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">912</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> rowid=-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">913</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (name==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> rowid;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">914</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">915</span><span class="doxyLineContent"><span class="doxyHighlight">  name = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8c90a81fbaf02ad9af7387f3ed1c20c1">stripFromPath</a>(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">916</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">917</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#ae8c2b376b75f41e8807c6db20df8de47">path_select</a>,</span><span class="doxyHighlightStringLiteral">":name"</span><span class="doxyHighlight">,name.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">918</span><span class="doxyLineContent"><span class="doxyHighlight">  rowid=<a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#ae8c2b376b75f41e8807c6db20df8de47">path_select</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">919</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rowid==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">920</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">921</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#ab3954473f4ed653652992317306a884b">path_insert</a>,</span><span class="doxyHighlightStringLiteral">":name"</span><span class="doxyHighlight">,name.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">922</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#ab3954473f4ed653652992317306a884b">path_insert</a>,</span><span class="doxyHighlightStringLiteral">":type"</span><span class="doxyHighlight">,type);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">923</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#ab3954473f4ed653652992317306a884b">path_insert</a>,</span><span class="doxyHighlightStringLiteral">":local"</span><span class="doxyHighlight">,local?1:0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">924</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#ab3954473f4ed653652992317306a884b">path_insert</a>,</span><span class="doxyHighlightStringLiteral">":found"</span><span class="doxyHighlight">,found?1:0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">925</span><span class="doxyLineContent"><span class="doxyHighlight">    rowid=<a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#ab3954473f4ed653652992317306a884b">path_insert</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">926</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">927</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> rowid;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">928</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>, <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="#ab3954473f4ed653652992317306a884b">path&#95;insert</a>, <a href="#ae8c2b376b75f41e8807c6db20df8de47">path&#95;select</a>, <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8c90a81fbaf02ad9af7387f3ed1c20c1">stripFromPath</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>, <a href="#a3889d30b147517190ccd9c1ebb9ca785">generateSqlite3ForConcept</a>, <a href="#a96d60ce1da0cc36d049c1a2bbc174178">generateSqlite3ForDir</a>, <a href="#ae7139b08c0c942d65c6bcb8402a8b142">generateSqlite3ForFile</a>, <a href="#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a>, <a href="#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="#a2b0628c4001ddb19730a764b29b0be44">generateSqlite3ForModule</a>, <a href="#ad5597180db00f8bb26d51d9b3b409241">generateSqlite3ForNamespace</a> and <a href="#aeb4c1aeb9fc32917845d0d05a52cb478">generateSqlite3ForPage</a>.
</div>
</div>

### insertRefid() {#a9557f25eb205a966e712f8a709d73b5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct Refid insertRefid (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; refid)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 948 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9557f25eb205a966e712f8a709d73b5f">948</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">949</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">950</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/refid">Refid</a> ret;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">951</span><span class="doxyLineContent"><span class="doxyHighlight">  ret.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>=-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">952</span><span class="doxyLineContent"><span class="doxyHighlight">  ret.<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>=<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">953</span><span class="doxyLineContent"><span class="doxyHighlight">  ret.<a href="/web-doxygen/docs/api/structs/refid/#a4eebe0fd7dffced627148d23da169ad0">created</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">954</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> ret;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">955</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">956</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#af21d2af0294b7e22f02b098a43ec276d">refid_select</a>,</span><span class="doxyHighlightStringLiteral">":refid"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">957</span><span class="doxyLineContent"><span class="doxyHighlight">  ret.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>=<a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#af21d2af0294b7e22f02b098a43ec276d">refid_select</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">958</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ret.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">959</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">960</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#a3f9a714e57e3f2d5b40ca9e2b5e1edf2">refid_insert</a>,</span><span class="doxyHighlightStringLiteral">":refid"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">961</span><span class="doxyLineContent"><span class="doxyHighlight">    ret.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>=<a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#a3f9a714e57e3f2d5b40ca9e2b5e1edf2">refid_insert</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">962</span><span class="doxyLineContent"><span class="doxyHighlight">    ret.<a href="/web-doxygen/docs/api/structs/refid/#a4eebe0fd7dffced627148d23da169ad0">created</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">963</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">964</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">965</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> ret;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">966</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>, <a href="/web-doxygen/docs/api/structs/refid/#a4eebe0fd7dffced627148d23da169ad0">Refid::created</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">Refid::refid</a>, <a href="#a3f9a714e57e3f2d5b40ca9e2b5e1edf2">refid&#95;insert</a>, <a href="#af21d2af0294b7e22f02b098a43ec276d">refid&#95;select</a>, <a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">Refid::rowid</a>, <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="#a92be09d6ea0ae352da3d441abed04f30">associateAllClassMembers</a>, <a href="#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>, <a href="#a3889d30b147517190ccd9c1ebb9ca785">generateSqlite3ForConcept</a>, <a href="#a96d60ce1da0cc36d049c1a2bbc174178">generateSqlite3ForDir</a>, <a href="#ae7139b08c0c942d65c6bcb8402a8b142">generateSqlite3ForFile</a>, <a href="#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a>, <a href="#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="#a2b0628c4001ddb19730a764b29b0be44">generateSqlite3ForModule</a>, <a href="#ad5597180db00f8bb26d51d9b3b409241">generateSqlite3ForNamespace</a>, <a href="#aeb4c1aeb9fc32917845d0d05a52cb478">generateSqlite3ForPage</a>, <a href="#a3a9064a0bd3f19c550c68c5839dec5a6">insertMemberFunctionParams</a>, <a href="#ae10406df98d50bc1f5d58c0be3427202">insertMemberReference</a>, <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>, <a href="#a3b94451a3cd1a0d6cc44e2a9a2118481">writeInnerClasses</a>, <a href="#a46ef1ad7fcb0bd63228beb9a14e7f4bd">writeInnerConcepts</a>, <a href="#ad1e096e657dc0a4918d8ad80ffa233a8">writeInnerDirs</a>, <a href="#a9e4b392824ade3c727f39d6717bdc97f">writeInnerFiles</a>, <a href="#a472ea2a1d309024f061e7d48d1dd3839">writeInnerGroups</a>, <a href="#a68dad0e13a83b4eb9046a6e6588a855f">writeInnerModules</a>, <a href="#a597b4509789d2af90e78fe008fa832ab">writeInnerNamespaces</a> and <a href="#a4b9d2814806d6388bddc5f4c141d8fbf">writeInnerPages</a>.
</div>
</div>

### memberdefExists() {#a06d5fa6f8acbfef6705314884b6e6800}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool memberdefExists (struct <a href="/web-doxygen/docs/api/structs/refid">Refid</a> refid)</td>
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


<p>Definition at line 968 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a06d5fa6f8acbfef6705314884b6e6800">968</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a06d5fa6f8acbfef6705314884b6e6800">memberdefExists</a>(</span><span class="doxyHighlightKeyword">struct</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/refid">Refid</a> <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">969</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">970</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#ad5786eb5fdd727a497982eb3b0901680">memberdef_exists</a>,</span><span class="doxyHighlightStringLiteral">":rowid"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>.rowid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">971</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> test = <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#ad5786eb5fdd727a497982eb3b0901680">memberdef_exists</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">972</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> test ? true : </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">973</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>, <a href="#ad5786eb5fdd727a497982eb3b0901680">memberdef&#95;exists</a>, <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">Refid::refid</a>, <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>.
</div>
</div>

### memberdefIncomplete() {#a2a696974b4a7902e4137be55d5337d20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool memberdefIncomplete (struct <a href="/web-doxygen/docs/api/structs/refid">Refid</a> refid, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md)</td>
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


<p>Definition at line 975 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2a696974b4a7902e4137be55d5337d20">975</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a2a696974b4a7902e4137be55d5337d20">memberdefIncomplete</a>(</span><span class="doxyHighlightKeyword">struct</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/refid">Refid</a> <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>* md)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">976</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">977</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a2aef529ba9a8abda7c5dbe9f9c2b183b">memberdef_incomplete</a>,</span><span class="doxyHighlightStringLiteral">":rowid"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">refid</a>.rowid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">978</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a2aef529ba9a8abda7c5dbe9f9c2b183b">memberdef_incomplete</a>,</span><span class="doxyHighlightStringLiteral">":new_inline"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a509e150708bb48d4bafaa1146cf1eadc">isInline</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">979</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> test = <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#a2aef529ba9a8abda7c5dbe9f9c2b183b">memberdef_incomplete</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">980</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> test ? true : </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">981</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a509e150708bb48d4bafaa1146cf1eadc">MemberDef::isInline</a>, <a href="#a2aef529ba9a8abda7c5dbe9f9c2b183b">memberdef&#95;incomplete</a>, <a href="/web-doxygen/docs/api/structs/refid/#a903566363990a0b5295f2e8e6816f50c">Refid::refid</a>, <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>.
</div>
</div>

### openDbConnection() {#ac13e6fab478750b5fc094a78e8fcb149}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sqlite3 * openDbConnection ()</td>
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


<p>Definition at line 2543 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac13e6fab478750b5fc094a78e8fcb149">2543</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> sqlite3* <a href="#ac13e6fab478750b5fc094a78e8fcb149">openDbConnection</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2544</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2545</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2546</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> outputDirectory = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(SQLITE3_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2547</span><span class="doxyLineContent"><span class="doxyHighlight">  sqlite3 *db = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2548</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2549</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> rc = sqlite3_initialize();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2550</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rc != SQLITE_OK)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2551</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2552</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"sqlite3_initialize failed\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2553</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2554</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2555</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2556</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string dbFileName = </span><span class="doxyHighlightStringLiteral">"doxygen_sqlite3.db"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2557</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fi(outputDirectory.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+dbFileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2558</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2559</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2560</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2561</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(SQLITE3_RECREATE_DB))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2562</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2563</span><span class="doxyLineContent"><span class="doxyHighlight">       <a href="/web-doxygen/docs/api/classes/dir">Dir</a>().<a href="/web-doxygen/docs/api/classes/dir/#a5a64060f8e1731e8f00da7e8f7051e4b">remove</a>(fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#af69e3949475014dcdbd504d742bdf270">absFilePath</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2564</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2565</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2566</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2567</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"doxygen_sqlite3.db already exists! Rename, remove, or archive it to regenerate\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2568</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2569</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2570</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2571</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2572</span><span class="doxyLineContent"><span class="doxyHighlight">  rc = sqlite3_open_v2(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2573</span><span class="doxyLineContent"><span class="doxyHighlight">    fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#af69e3949475014dcdbd504d742bdf270">absFilePath</a>().c_str(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2574</span><span class="doxyLineContent"><span class="doxyHighlight">    &amp;db,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2575</span><span class="doxyLineContent"><span class="doxyHighlight">    SQLITE_OPEN_READWRITE | SQLITE_OPEN_CREATE,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2576</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">nullptr</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2577</span><span class="doxyLineContent"><span class="doxyHighlight">  );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2578</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rc != SQLITE_OK)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2579</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2580</span><span class="doxyLineContent"><span class="doxyHighlight">    sqlite3_close(db);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2581</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Database open failed: doxygen_sqlite3.db\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2582</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2583</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> db;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2584</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/fileinfo/#af69e3949475014dcdbd504d742bdf270">FileInfo::absFilePath</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">FileInfo::exists</a>, <a href="/web-doxygen/docs/api/classes/dir/#a5a64060f8e1731e8f00da7e8f7051e4b">Dir::remove</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.

Referenced by <a href="#ae5b36a2f93dadba9f8c7d762564154e1">generateSqlite3</a>.
</div>
</div>

### pragmaTuning() {#af385f460786d8d70b91b640dc78de575}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void pragmaTuning (sqlite3 * db)</td>
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


<p>Definition at line 1206 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af385f460786d8d70b91b640dc78de575">1206</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af385f460786d8d70b91b640dc78de575">pragmaTuning</a>(sqlite3 *db)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1207</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1208</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> * sErrMsg = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1209</span><span class="doxyLineContent"><span class="doxyHighlight">  sqlite3_exec(db, </span><span class="doxyHighlightStringLiteral">"PRAGMA synchronous = OFF"</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, &amp;sErrMsg);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1210</span><span class="doxyLineContent"><span class="doxyHighlight">  sqlite3_exec(db, </span><span class="doxyHighlightStringLiteral">"PRAGMA journal_mode = MEMORY"</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, &amp;sErrMsg);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1211</span><span class="doxyLineContent"><span class="doxyHighlight">  sqlite3_exec(db, </span><span class="doxyHighlightStringLiteral">"PRAGMA temp_store = MEMORY;"</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, &amp;sErrMsg);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1212</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="#ae5b36a2f93dadba9f8c7d762564154e1">generateSqlite3</a>.
</div>
</div>

### prepareStatement() {#a0ee82255bd720e88690c7cac3581f1df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int prepareStatement (sqlite3 * db, <a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> &amp; s)</td>
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


<p>Definition at line 1149 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0ee82255bd720e88690c7cac3581f1df">1149</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a0ee82255bd720e88690c7cac3581f1df">prepareStatement</a>(sqlite3 *db, <a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1150</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1151</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> rc = sqlite3_prepare_v2(db,s.<a href="/web-doxygen/docs/api/structs/sqlstmt/#a0fcb633ba93d1ad47b5072781ac76bb8">query</a>,-1,&amp;s.<a href="/web-doxygen/docs/api/structs/sqlstmt/#a780c9b733b885100df0aa733b0c66a37">stmt</a>,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1152</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rc!=SQLITE_OK)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1153</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1154</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"prepare failed for:\n  {}\n  {}\n"</span><span class="doxyHighlight">, s.<a href="/web-doxygen/docs/api/structs/sqlstmt/#a0fcb633ba93d1ad47b5072781ac76bb8">query</a>, sqlite3_errmsg(db));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1155</span><span class="doxyLineContent"><span class="doxyHighlight">    s.<a href="/web-doxygen/docs/api/structs/sqlstmt/#a20465204d0f4d947d8df06808d62d3ee">db</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1156</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1157</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1158</span><span class="doxyLineContent"><span class="doxyHighlight">  s.<a href="/web-doxygen/docs/api/structs/sqlstmt/#a20465204d0f4d947d8df06808d62d3ee">db</a> = db;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1159</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> rc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1160</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/structs/sqlstmt/#a20465204d0f4d947d8df06808d62d3ee">SqlStmt::db</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/structs/sqlstmt/#a0fcb633ba93d1ad47b5072781ac76bb8">SqlStmt::query</a> and <a href="/web-doxygen/docs/api/structs/sqlstmt/#a780c9b733b885100df0aa733b0c66a37">SqlStmt::stmt</a>.

Referenced by <a href="#a5c243ba2fe5dbbef9eae72870cb045ff">prepareStatements</a>.
</div>
</div>

### prepareStatements() {#a5c243ba2fe5dbbef9eae72870cb045ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int prepareStatements (sqlite3 * db)</td>
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


<p>Definition at line 1162 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5c243ba2fe5dbbef9eae72870cb045ff">1162</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a5c243ba2fe5dbbef9eae72870cb045ff">prepareStatements</a>(sqlite3 *db)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1163</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1164</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1165</span><span class="doxyLineContent"><span class="doxyHighlight">  -1==<a href="#a0ee82255bd720e88690c7cac3581f1df">prepareStatement</a>(db, <a href="#ac593dfdd38adfad8de3e87c2405f65b2">meta_insert</a>) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1166</span><span class="doxyLineContent"><span class="doxyHighlight">  -1==<a href="#a0ee82255bd720e88690c7cac3581f1df">prepareStatement</a>(db, <a href="#ad5786eb5fdd727a497982eb3b0901680">memberdef_exists</a>) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1167</span><span class="doxyLineContent"><span class="doxyHighlight">  -1==<a href="#a0ee82255bd720e88690c7cac3581f1df">prepareStatement</a>(db, <a href="#a2aef529ba9a8abda7c5dbe9f9c2b183b">memberdef_incomplete</a>) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1168</span><span class="doxyLineContent"><span class="doxyHighlight">  -1==<a href="#a0ee82255bd720e88690c7cac3581f1df">prepareStatement</a>(db, <a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1169</span><span class="doxyLineContent"><span class="doxyHighlight">  -1==<a href="#a0ee82255bd720e88690c7cac3581f1df">prepareStatement</a>(db, <a href="#a996b41f0018348eb70cb369999032333">memberdef_update_def</a>) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1170</span><span class="doxyLineContent"><span class="doxyHighlight">  -1==<a href="#a0ee82255bd720e88690c7cac3581f1df">prepareStatement</a>(db, <a href="#a9dd6736df9437b0372601f0fc9256cdc">memberdef_update_decl</a>) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1171</span><span class="doxyLineContent"><span class="doxyHighlight">  -1==<a href="#a0ee82255bd720e88690c7cac3581f1df">prepareStatement</a>(db, <a href="#a7ff598f38ef2dad027845c7abaa65592">member_insert</a>) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1172</span><span class="doxyLineContent"><span class="doxyHighlight">  -1==<a href="#a0ee82255bd720e88690c7cac3581f1df">prepareStatement</a>(db, <a href="#ab3954473f4ed653652992317306a884b">path_insert</a>) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1173</span><span class="doxyLineContent"><span class="doxyHighlight">  -1==<a href="#a0ee82255bd720e88690c7cac3581f1df">prepareStatement</a>(db, <a href="#ae8c2b376b75f41e8807c6db20df8de47">path_select</a>) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1174</span><span class="doxyLineContent"><span class="doxyHighlight">  -1==<a href="#a0ee82255bd720e88690c7cac3581f1df">prepareStatement</a>(db, <a href="#a3f9a714e57e3f2d5b40ca9e2b5e1edf2">refid_insert</a>) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1175</span><span class="doxyLineContent"><span class="doxyHighlight">  -1==<a href="#a0ee82255bd720e88690c7cac3581f1df">prepareStatement</a>(db, <a href="#af21d2af0294b7e22f02b098a43ec276d">refid_select</a>) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1176</span><span class="doxyLineContent"><span class="doxyHighlight">  -1==<a href="#a0ee82255bd720e88690c7cac3581f1df">prepareStatement</a>(db, <a href="#a9c15b3b9b3db6bf609838c68c915d80a">incl_insert</a>)||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1177</span><span class="doxyLineContent"><span class="doxyHighlight">  -1==<a href="#a0ee82255bd720e88690c7cac3581f1df">prepareStatement</a>(db, <a href="#a1e3e98a7897963c61baf003aab5fecfa">incl_select</a>)||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1178</span><span class="doxyLineContent"><span class="doxyHighlight">  -1==<a href="#a0ee82255bd720e88690c7cac3581f1df">prepareStatement</a>(db, <a href="#aeff7609bbf258f9fe7bb792def0251d6">param_insert</a>) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1179</span><span class="doxyLineContent"><span class="doxyHighlight">  -1==<a href="#a0ee82255bd720e88690c7cac3581f1df">prepareStatement</a>(db, <a href="#a5615e9549a34565e146c795f7879a70c">param_select</a>) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1180</span><span class="doxyLineContent"><span class="doxyHighlight">  -1==<a href="#a0ee82255bd720e88690c7cac3581f1df">prepareStatement</a>(db, <a href="#a669c1f1c7bd2b5cfe3bc3e9294e81be9">xrefs_insert</a>) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1181</span><span class="doxyLineContent"><span class="doxyHighlight">  -1==<a href="#a0ee82255bd720e88690c7cac3581f1df">prepareStatement</a>(db, <a href="#a6ef03b7de5c740c3ad04b46fee17e6e0">reimplements_insert</a>) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1182</span><span class="doxyLineContent"><span class="doxyHighlight">  -1==<a href="#a0ee82255bd720e88690c7cac3581f1df">prepareStatement</a>(db, <a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains_insert</a>) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1183</span><span class="doxyLineContent"><span class="doxyHighlight">  -1==<a href="#a0ee82255bd720e88690c7cac3581f1df">prepareStatement</a>(db, <a href="#a162bb86dfaf3254e93b1274353cd1cbf">compounddef_exists</a>) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1184</span><span class="doxyLineContent"><span class="doxyHighlight">  -1==<a href="#a0ee82255bd720e88690c7cac3581f1df">prepareStatement</a>(db, <a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1185</span><span class="doxyLineContent"><span class="doxyHighlight">  -1==<a href="#a0ee82255bd720e88690c7cac3581f1df">prepareStatement</a>(db, <a href="#a33e0611a73afb936b8c97c6812e64029">compoundref_insert</a>) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1186</span><span class="doxyLineContent"><span class="doxyHighlight">  -1==<a href="#a0ee82255bd720e88690c7cac3581f1df">prepareStatement</a>(db, <a href="#a9fd0d6eb855cc81bc77248083bc52316">memberdef_param_insert</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1187</span><span class="doxyLineContent"><span class="doxyHighlight">  )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1188</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1189</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1190</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1191</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1192</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a162bb86dfaf3254e93b1274353cd1cbf">compounddef&#95;exists</a>, <a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef&#95;insert</a>, <a href="#a33e0611a73afb936b8c97c6812e64029">compoundref&#95;insert</a>, <a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains&#95;insert</a>, <a href="#a9c15b3b9b3db6bf609838c68c915d80a">incl&#95;insert</a>, <a href="#a1e3e98a7897963c61baf003aab5fecfa">incl&#95;select</a>, <a href="#a7ff598f38ef2dad027845c7abaa65592">member&#95;insert</a>, <a href="#ad5786eb5fdd727a497982eb3b0901680">memberdef&#95;exists</a>, <a href="#a2aef529ba9a8abda7c5dbe9f9c2b183b">memberdef&#95;incomplete</a>, <a href="#a044bf3040887411b780222535ef94942">memberdef&#95;insert</a>, <a href="#a9fd0d6eb855cc81bc77248083bc52316">memberdef&#95;param&#95;insert</a>, <a href="#a9dd6736df9437b0372601f0fc9256cdc">memberdef&#95;update&#95;decl</a>, <a href="#a996b41f0018348eb70cb369999032333">memberdef&#95;update&#95;def</a>, <a href="#ac593dfdd38adfad8de3e87c2405f65b2">meta&#95;insert</a>, <a href="#aeff7609bbf258f9fe7bb792def0251d6">param&#95;insert</a>, <a href="#a5615e9549a34565e146c795f7879a70c">param&#95;select</a>, <a href="#ab3954473f4ed653652992317306a884b">path&#95;insert</a>, <a href="#ae8c2b376b75f41e8807c6db20df8de47">path&#95;select</a>, <a href="#a0ee82255bd720e88690c7cac3581f1df">prepareStatement</a>, <a href="#a3f9a714e57e3f2d5b40ca9e2b5e1edf2">refid&#95;insert</a>, <a href="#af21d2af0294b7e22f02b098a43ec276d">refid&#95;select</a>, <a href="#a6ef03b7de5c740c3ad04b46fee17e6e0">reimplements&#95;insert</a> and <a href="#a669c1f1c7bd2b5cfe3bc3e9294e81be9">xrefs&#95;insert</a>.

Referenced by <a href="#ae5b36a2f93dadba9f8c7d762564154e1">generateSqlite3</a>.
</div>
</div>

### recordMetadata() {#a0e33b2ef2c8bf323a8a2f1d4bb13a5ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void recordMetadata ()</td>
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


<p>Definition at line 930 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0e33b2ef2c8bf323a8a2f1d4bb13a5ca">930</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e33b2ef2c8bf323a8a2f1d4bb13a5ca">recordMetadata</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">931</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">932</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#ac593dfdd38adfad8de3e87c2405f65b2">meta_insert</a>,</span><span class="doxyHighlightStringLiteral">":doxygen_version"</span><span class="doxyHighlight">,getFullVersion());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">933</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#ac593dfdd38adfad8de3e87c2405f65b2">meta_insert</a>,</span><span class="doxyHighlightStringLiteral">":schema_version"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"0.2.1"</span><span class="doxyHighlight">); </span><span class="doxyHighlightComment">//TODO: this should be a constant somewhere; not sure where</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">934</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#ac593dfdd38adfad8de3e87c2405f65b2">meta_insert</a>,</span><span class="doxyHighlightStringLiteral">":generated_at"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/datetime-cpp/#a28a0c3252d0f0f28c0611cbc3268b003">dateToString</a>(<a href="/web-doxygen/docs/api/files/src/datetime-h/#a20573bf423b169aa9100035b297c28fea8cf10d2341ed01492506085688270c1e">DateTimeType::DateTime</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">935</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#ac593dfdd38adfad8de3e87c2405f65b2">meta_insert</a>,</span><span class="doxyHighlightStringLiteral">":generated_on"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/datetime-cpp/#a28a0c3252d0f0f28c0611cbc3268b003">dateToString</a>(<a href="/web-doxygen/docs/api/files/src/datetime-h/#a20573bf423b169aa9100035b297c28fea44749712dbec183e983dcd78a7736c41">DateTimeType::Date</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">936</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#ac593dfdd38adfad8de3e87c2405f65b2">meta_insert</a>,</span><span class="doxyHighlightStringLiteral">":project_name"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(PROJECT_NAME));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">937</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#ac593dfdd38adfad8de3e87c2405f65b2">meta_insert</a>,</span><span class="doxyHighlightStringLiteral">":project_number"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(PROJECT_NUMBER));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">938</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#ac593dfdd38adfad8de3e87c2405f65b2">meta_insert</a>,</span><span class="doxyHighlightStringLiteral">":project_brief"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(PROJECT_BRIEF));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">939</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#ac593dfdd38adfad8de3e87c2405f65b2">meta_insert</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">940</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="/web-doxygen/docs/api/files/src/datetime-h/#a20573bf423b169aa9100035b297c28fea44749712dbec183e983dcd78a7736c41">Date</a>, <a href="/web-doxygen/docs/api/files/src/datetime-h/#a20573bf423b169aa9100035b297c28fea8cf10d2341ed01492506085688270c1e">DateTime</a>, <a href="/web-doxygen/docs/api/files/src/datetime-cpp/#a28a0c3252d0f0f28c0611cbc3268b003">dateToString</a>, <a href="#ac593dfdd38adfad8de3e87c2405f65b2">meta&#95;insert</a> and <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>.

Referenced by <a href="#ae5b36a2f93dadba9f8c7d762564154e1">generateSqlite3</a>.
</div>
</div>

### step() {#aaba2817dbf5f4afbbba5998976dbdab4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int step (<a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> &amp; s, bool getRowId=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, bool select=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
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


<p>Definition at line 892 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaba2817dbf5f4afbbba5998976dbdab4">892</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> &amp;s,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> getRowId=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> select=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">893</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">894</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> rowid=-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">895</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> rc = sqlite3_step(s.<a href="/web-doxygen/docs/api/structs/sqlstmt/#a780c9b733b885100df0aa733b0c66a37">stmt</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">896</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rc!=SQLITE_DONE &amp;&amp; rc!=SQLITE_ROW)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">897</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">898</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((</span><span class="doxyHighlightStringLiteral">"sqlite3_step: %s (rc: %d)\n"</span><span class="doxyHighlight">, sqlite3_errmsg(s.<a href="/web-doxygen/docs/api/structs/sqlstmt/#a20465204d0f4d947d8df06808d62d3ee">db</a>), rc));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">899</span><span class="doxyLineContent"><span class="doxyHighlight">    sqlite3_reset(s.<a href="/web-doxygen/docs/api/structs/sqlstmt/#a780c9b733b885100df0aa733b0c66a37">stmt</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">900</span><span class="doxyLineContent"><span class="doxyHighlight">    sqlite3_clear_bindings(s.<a href="/web-doxygen/docs/api/structs/sqlstmt/#a780c9b733b885100df0aa733b0c66a37">stmt</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">901</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">902</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">903</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (getRowId &amp;&amp; select) rowid = sqlite3_column_int(s.<a href="/web-doxygen/docs/api/structs/sqlstmt/#a780c9b733b885100df0aa733b0c66a37">stmt</a>, 0); </span><span class="doxyHighlightComment">// works on selects, doesn't on inserts</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">904</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (getRowId &amp;&amp; !select) rowid = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(sqlite3_last_insert_rowid(s.<a href="/web-doxygen/docs/api/structs/sqlstmt/#a20465204d0f4d947d8df06808d62d3ee">db</a>)); </span><span class="doxyHighlightComment">//works on inserts, doesn't on selects</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">905</span><span class="doxyLineContent"><span class="doxyHighlight">  sqlite3_reset(s.<a href="/web-doxygen/docs/api/structs/sqlstmt/#a780c9b733b885100df0aa733b0c66a37">stmt</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">906</span><span class="doxyLineContent"><span class="doxyHighlight">  sqlite3_clear_bindings(s.<a href="/web-doxygen/docs/api/structs/sqlstmt/#a780c9b733b885100df0aa733b0c66a37">stmt</a>); </span><span class="doxyHighlightComment">// XXX When should this really be called</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">907</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> rowid;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">908</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/structs/sqlstmt/#a20465204d0f4d947d8df06808d62d3ee">SqlStmt::db</a>, <a href="#a234e2efe67eececd88b140b46ea37463">DBG&#95;CTX</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="/web-doxygen/docs/api/structs/sqlstmt/#a780c9b733b885100df0aa733b0c66a37">SqlStmt::stmt</a>.

Referenced by <a href="#affa42bdf0b91c838fe0215b4e6afb7b5">associateMember</a>, <a href="#a19ff8cd8130e662be4112bc914f7b50b">compounddefExists</a>, <a href="#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>, <a href="#a3889d30b147517190ccd9c1ebb9ca785">generateSqlite3ForConcept</a>, <a href="#a96d60ce1da0cc36d049c1a2bbc174178">generateSqlite3ForDir</a>, <a href="#ae7139b08c0c942d65c6bcb8402a8b142">generateSqlite3ForFile</a>, <a href="#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a>, <a href="#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="#a2b0628c4001ddb19730a764b29b0be44">generateSqlite3ForModule</a>, <a href="#ad5597180db00f8bb26d51d9b3b409241">generateSqlite3ForNamespace</a>, <a href="#aeb4c1aeb9fc32917845d0d05a52cb478">generateSqlite3ForPage</a>, <a href="#a6ff307313c1b28d89ef63fef3590ad36">insertMemberDefineParams</a>, <a href="#a3a9064a0bd3f19c550c68c5839dec5a6">insertMemberFunctionParams</a>, <a href="#a204b468b29a5d8ae8cf305cc08766eb7">insertMemberReference</a>, <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a>, <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>, <a href="#a06d5fa6f8acbfef6705314884b6e6800">memberdefExists</a>, <a href="#a2a696974b4a7902e4137be55d5337d20">memberdefIncomplete</a>, <a href="#a0e33b2ef2c8bf323a8a2f1d4bb13a5ca">recordMetadata</a>, <a href="#a3b94451a3cd1a0d6cc44e2a9a2118481">writeInnerClasses</a>, <a href="#a46ef1ad7fcb0bd63228beb9a14e7f4bd">writeInnerConcepts</a>, <a href="#ad1e096e657dc0a4918d8ad80ffa233a8">writeInnerDirs</a>, <a href="#a9e4b392824ade3c727f39d6717bdc97f">writeInnerFiles</a>, <a href="#a472ea2a1d309024f061e7d48d1dd3839">writeInnerGroups</a>, <a href="#a68dad0e13a83b4eb9046a6e6588a855f">writeInnerModules</a>, <a href="#a597b4509789d2af90e78fe008fa832ab">writeInnerNamespaces</a>, <a href="#a4b9d2814806d6388bddc5f4c141d8fbf">writeInnerPages</a> and <a href="#a8f2bd54985a7da4e6c800829305bece1">writeTemplateArgumentList</a>.
</div>
</div>

### stripQualifiers() {#a8acb7287be03115c56196dd1a1085225}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void stripQualifiers (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; typeStr)</td>
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


<p>Definition at line 1137 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8acb7287be03115c56196dd1a1085225">1137</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8acb7287be03115c56196dd1a1085225">stripQualifiers</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;typeStr)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1138</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1139</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> done=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1140</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!done)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1141</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1142</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">      (typeStr.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"static "</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1143</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (typeStr.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"virtual "</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1144</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (typeStr==</span><span class="doxyHighlightStringLiteral">"virtual"</span><span class="doxyHighlight">) typeStr=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1145</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> done=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1146</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1147</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">QCString::stripPrefix</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>.
</div>
</div>

### writeInnerClasses() {#a3b94451a3cd1a0d6cc44e2a9a2118481}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeInnerClasses (const <a href="/web-doxygen/docs/api/classes/classlinkedrefmap">ClassLinkedRefMap</a> &amp; cl, struct <a href="/web-doxygen/docs/api/structs/refid">Refid</a> outer_refid)</td>
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


<p>Definition at line 1261 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3b94451a3cd1a0d6cc44e2a9a2118481">1261</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3b94451a3cd1a0d6cc44e2a9a2118481">writeInnerClasses</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classlinkedrefmap">ClassLinkedRefMap</a> &amp;cl, </span><span class="doxyHighlightKeyword">struct</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/refid">Refid</a> outer_refid)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1262</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1263</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cd : cl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1264</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1265</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!cd-&gt;isHidden() &amp;&amp; !cd-&gt;isAnonymous())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1266</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1267</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> inner_refid = <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(cd-&gt;getOutputFileBase());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1268</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1269</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains_insert</a>,</span><span class="doxyHighlightStringLiteral">":inner_rowid"</span><span class="doxyHighlight">, inner_refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1270</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains_insert</a>,</span><span class="doxyHighlightStringLiteral">":outer_rowid"</span><span class="doxyHighlight">, outer_refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1271</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains_insert</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1272</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1273</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1274</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>, <a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains&#95;insert</a>, <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>, <a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">Refid::rowid</a> and <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>.

Referenced by <a href="#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>, <a href="#ae7139b08c0c942d65c6bcb8402a8b142">generateSqlite3ForFile</a>, <a href="#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a>, <a href="#a2b0628c4001ddb19730a764b29b0be44">generateSqlite3ForModule</a> and <a href="#ad5597180db00f8bb26d51d9b3b409241">generateSqlite3ForNamespace</a>.
</div>
</div>

### writeInnerConcepts() {#a46ef1ad7fcb0bd63228beb9a14e7f4bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeInnerConcepts (const <a href="/web-doxygen/docs/api/classes/conceptlinkedrefmap">ConceptLinkedRefMap</a> &amp; cl, struct <a href="/web-doxygen/docs/api/structs/refid">Refid</a> outer_refid)</td>
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


<p>Definition at line 1276 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a46ef1ad7fcb0bd63228beb9a14e7f4bd">1276</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a46ef1ad7fcb0bd63228beb9a14e7f4bd">writeInnerConcepts</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/conceptlinkedrefmap">ConceptLinkedRefMap</a> &amp;cl, </span><span class="doxyHighlightKeyword">struct</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/refid">Refid</a> outer_refid)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1277</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1278</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cd : cl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1279</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1280</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> inner_refid = <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(cd-&gt;getOutputFileBase());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1281</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1282</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains_insert</a>,</span><span class="doxyHighlightStringLiteral">":inner_rowid"</span><span class="doxyHighlight">, inner_refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1283</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains_insert</a>,</span><span class="doxyHighlightStringLiteral">":outer_rowid"</span><span class="doxyHighlight">, outer_refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1284</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains_insert</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1285</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1286</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>, <a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains&#95;insert</a>, <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>, <a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">Refid::rowid</a> and <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>.

Referenced by <a href="#ae7139b08c0c942d65c6bcb8402a8b142">generateSqlite3ForFile</a>, <a href="#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a>, <a href="#a2b0628c4001ddb19730a764b29b0be44">generateSqlite3ForModule</a> and <a href="#ad5597180db00f8bb26d51d9b3b409241">generateSqlite3ForNamespace</a>.
</div>
</div>

### writeInnerDirs() {#ad1e096e657dc0a4918d8ad80ffa233a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeInnerDirs (const <a href="/web-doxygen/docs/api/classes/dirlist">DirList</a> &amp; dl, struct <a href="/web-doxygen/docs/api/structs/refid">Refid</a> outer_refid)</td>
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


<p>Definition at line 1339 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad1e096e657dc0a4918d8ad80ffa233a8">1339</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad1e096e657dc0a4918d8ad80ffa233a8">writeInnerDirs</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dirlist">DirList</a> &amp;dl, </span><span class="doxyHighlightKeyword">struct</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/refid">Refid</a> outer_refid)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1340</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1341</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> subdir : dl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1342</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1343</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> inner_refid = <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(subdir-&gt;getOutputFileBase());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1344</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1345</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains_insert</a>,</span><span class="doxyHighlightStringLiteral">":inner_rowid"</span><span class="doxyHighlight">, inner_refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1346</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains_insert</a>,</span><span class="doxyHighlightStringLiteral">":outer_rowid"</span><span class="doxyHighlight">, outer_refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1347</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains_insert</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1348</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1349</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>, <a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains&#95;insert</a>, <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>, <a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">Refid::rowid</a> and <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>.

Referenced by <a href="#a96d60ce1da0cc36d049c1a2bbc174178">generateSqlite3ForDir</a>.
</div>
</div>

### writeInnerFiles() {#a9e4b392824ade3c727f39d6717bdc97f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeInnerFiles (const <a href="/web-doxygen/docs/api/classes/filelist">FileList</a> &amp; fl, struct <a href="/web-doxygen/docs/api/structs/refid">Refid</a> outer_refid)</td>
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


<p>Definition at line 1327 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9e4b392824ade3c727f39d6717bdc97f">1327</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9e4b392824ade3c727f39d6717bdc97f">writeInnerFiles</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filelist">FileList</a> &amp;fl, </span><span class="doxyHighlightKeyword">struct</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/refid">Refid</a> outer_refid)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1328</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1329</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;fd: fl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1330</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1331</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> inner_refid = <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(fd-&gt;getOutputFileBase());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1332</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1333</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains_insert</a>,</span><span class="doxyHighlightStringLiteral">":inner_rowid"</span><span class="doxyHighlight">, inner_refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1334</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains_insert</a>,</span><span class="doxyHighlightStringLiteral">":outer_rowid"</span><span class="doxyHighlight">, outer_refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1335</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains_insert</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1336</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1337</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>, <a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains&#95;insert</a>, <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>, <a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">Refid::rowid</a> and <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>.

Referenced by <a href="#a96d60ce1da0cc36d049c1a2bbc174178">generateSqlite3ForDir</a>, <a href="#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a> and <a href="#a2b0628c4001ddb19730a764b29b0be44">generateSqlite3ForModule</a>.
</div>
</div>

### writeInnerGroups() {#a472ea2a1d309024f061e7d48d1dd3839}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeInnerGroups (const <a href="/web-doxygen/docs/api/classes/grouplist">GroupList</a> &amp; gl, struct <a href="/web-doxygen/docs/api/structs/refid">Refid</a> outer_refid)</td>
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


<p>Definition at line 1315 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a472ea2a1d309024f061e7d48d1dd3839">1315</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a472ea2a1d309024f061e7d48d1dd3839">writeInnerGroups</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/grouplist">GroupList</a> &amp;gl, </span><span class="doxyHighlightKeyword">struct</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/refid">Refid</a> outer_refid)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1316</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1317</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;sgd : gl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1318</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1319</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> inner_refid = <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(sgd-&gt;getOutputFileBase());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1320</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1321</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains_insert</a>,</span><span class="doxyHighlightStringLiteral">":inner_rowid"</span><span class="doxyHighlight">, inner_refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1322</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains_insert</a>,</span><span class="doxyHighlightStringLiteral">":outer_rowid"</span><span class="doxyHighlight">, outer_refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1323</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains_insert</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1324</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1325</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>, <a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains&#95;insert</a>, <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>, <a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">Refid::rowid</a> and <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>.

Referenced by <a href="#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a>.
</div>
</div>

### writeInnerModules() {#a68dad0e13a83b4eb9046a6e6588a855f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeInnerModules (const <a href="/web-doxygen/docs/api/classes/modulelinkedrefmap">ModuleLinkedRefMap</a> &amp; ml, struct <a href="/web-doxygen/docs/api/structs/refid">Refid</a> outer_refid)</td>
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


<p>Definition at line 1288 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a68dad0e13a83b4eb9046a6e6588a855f">1288</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a68dad0e13a83b4eb9046a6e6588a855f">writeInnerModules</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/modulelinkedrefmap">ModuleLinkedRefMap</a> &amp;ml, </span><span class="doxyHighlightKeyword">struct</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/refid">Refid</a> outer_refid)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1289</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1290</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mod : ml)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1291</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1292</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> inner_refid = <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(mod-&gt;getOutputFileBase());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1293</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1294</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains_insert</a>,</span><span class="doxyHighlightStringLiteral">":inner_rowid"</span><span class="doxyHighlight">, inner_refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1295</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains_insert</a>,</span><span class="doxyHighlightStringLiteral">":outer_rowid"</span><span class="doxyHighlight">, outer_refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1296</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains_insert</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1297</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1298</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>, <a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains&#95;insert</a>, <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>, <a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">Refid::rowid</a> and <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>.

Referenced by <a href="#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a>.
</div>
</div>

### writeInnerNamespaces() {#a597b4509789d2af90e78fe008fa832ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeInnerNamespaces (const <a href="/web-doxygen/docs/api/classes/namespacelinkedrefmap">NamespaceLinkedRefMap</a> &amp; nl, struct <a href="/web-doxygen/docs/api/structs/refid">Refid</a> outer_refid)</td>
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


<p>Definition at line 1351 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a597b4509789d2af90e78fe008fa832ab">1351</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a597b4509789d2af90e78fe008fa832ab">writeInnerNamespaces</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/namespacelinkedrefmap">NamespaceLinkedRefMap</a> &amp;nl, </span><span class="doxyHighlightKeyword">struct</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/refid">Refid</a> outer_refid)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1352</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1353</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;nd : nl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1354</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1355</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!nd-&gt;isHidden() &amp;&amp; !nd-&gt;isAnonymous())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1356</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1357</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> inner_refid = <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(nd-&gt;getOutputFileBase());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1358</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1359</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains_insert</a>,</span><span class="doxyHighlightStringLiteral">":inner_rowid"</span><span class="doxyHighlight">,inner_refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1360</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains_insert</a>,</span><span class="doxyHighlightStringLiteral">":outer_rowid"</span><span class="doxyHighlight">,outer_refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1361</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains_insert</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1362</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1363</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1364</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>, <a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains&#95;insert</a>, <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>, <a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">Refid::rowid</a> and <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>.

Referenced by <a href="#ae7139b08c0c942d65c6bcb8402a8b142">generateSqlite3ForFile</a>, <a href="#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a> and <a href="#ad5597180db00f8bb26d51d9b3b409241">generateSqlite3ForNamespace</a>.
</div>
</div>

### writeInnerPages() {#a4b9d2814806d6388bddc5f4c141d8fbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeInnerPages (const <a href="/web-doxygen/docs/api/classes/pagelinkedrefmap">PageLinkedRefMap</a> &amp; pl, struct <a href="/web-doxygen/docs/api/structs/refid">Refid</a> outer_refid)</td>
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


<p>Definition at line 1301 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4b9d2814806d6388bddc5f4c141d8fbf">1301</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4b9d2814806d6388bddc5f4c141d8fbf">writeInnerPages</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/pagelinkedrefmap">PageLinkedRefMap</a> &amp;pl, </span><span class="doxyHighlightKeyword">struct</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/refid">Refid</a> outer_refid)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1302</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1303</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;pd : pl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1304</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1305</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/refid">Refid</a> inner_refid = <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1306</span><span class="doxyLineContent"><span class="doxyHighlight">      pd-&gt;getGroupDef() ? pd-&gt;getOutputFileBase()+</span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight">+pd-&gt;name() : pd-&gt;getOutputFileBase()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1307</span><span class="doxyLineContent"><span class="doxyHighlight">    );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1308</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1309</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains_insert</a>,</span><span class="doxyHighlightStringLiteral">":inner_rowid"</span><span class="doxyHighlight">, inner_refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1310</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>(<a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains_insert</a>,</span><span class="doxyHighlightStringLiteral">":outer_rowid"</span><span class="doxyHighlight">, outer_refid.<a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">rowid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1311</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains_insert</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1312</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1313</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#af69029d3e47b3f8a0515b21e6562e6d7">bindIntParameter</a>, <a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains&#95;insert</a>, <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>, <a href="/web-doxygen/docs/api/structs/refid/#a93bc6ab2eb0fd66836894b58b5d2ea76">Refid::rowid</a> and <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>.

Referenced by <a href="#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a> and <a href="#aeb4c1aeb9fc32917845d0d05a52cb478">generateSqlite3ForPage</a>.
</div>
</div>

### writeMemberTemplateLists() {#adbab9cdf5d958b7f7ac7b736428974dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeMemberTemplateLists (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md)</td>
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


<p>Definition at line 1397 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adbab9cdf5d958b7f7ac7b736428974dd">1397</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#adbab9cdf5d958b7f7ac7b736428974dd">writeMemberTemplateLists</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1398</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1399</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8f2bd54985a7da4e6c800829305bece1">writeTemplateArgumentList</a>(md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a409da33c248938e57ba2135777a38628">templateArguments</a>(),md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a33ff70edee6691aacaeecf40a1146995">getClassDef</a>(),md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5036fd8ee16b186925236105029ee823">getFileDef</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1400</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/memberdef/#a33ff70edee6691aacaeecf40a1146995">MemberDef::getClassDef</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a5036fd8ee16b186925236105029ee823">MemberDef::getFileDef</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a409da33c248938e57ba2135777a38628">MemberDef::templateArguments</a> and <a href="#a8f2bd54985a7da4e6c800829305bece1">writeTemplateArgumentList</a>.

Referenced by <a href="#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>.
</div>
</div>

### writeTemplateArgumentList() {#a8f2bd54985a7da4e6c800829305bece1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeTemplateArgumentList (const <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp; al, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * scope, const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fileScope)</td>
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


<p>Definition at line 1367 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8f2bd54985a7da4e6c800829305bece1">1367</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8f2bd54985a7da4e6c800829305bece1">writeTemplateArgumentList</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;al,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1368</span><span class="doxyLineContent"><span class="doxyHighlight">                                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * scope,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1369</span><span class="doxyLineContent"><span class="doxyHighlight">                                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fileScope)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1370</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1371</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;a : al)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1372</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1373</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!a.type.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1374</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1375</span><span class="doxyLineContent"><span class="doxyHighlightComment">//#warning linkifyText(TextGeneratorXMLImpl(t),scope,fileScope,0,a.type);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1376</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#a5615e9549a34565e146c795f7879a70c">param_select</a>,</span><span class="doxyHighlightStringLiteral">":type"</span><span class="doxyHighlight">,a.type);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1377</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#aeff7609bbf258f9fe7bb792def0251d6">param_insert</a>,</span><span class="doxyHighlightStringLiteral">":type"</span><span class="doxyHighlight">,a.type);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1378</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1379</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!a.name.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1380</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1381</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#a5615e9549a34565e146c795f7879a70c">param_select</a>,</span><span class="doxyHighlightStringLiteral">":declname"</span><span class="doxyHighlight">,a.name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1382</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#aeff7609bbf258f9fe7bb792def0251d6">param_insert</a>,</span><span class="doxyHighlightStringLiteral">":declname"</span><span class="doxyHighlight">,a.name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1383</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#a5615e9549a34565e146c795f7879a70c">param_select</a>,</span><span class="doxyHighlightStringLiteral">":defname"</span><span class="doxyHighlight">,a.name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1384</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#aeff7609bbf258f9fe7bb792def0251d6">param_insert</a>,</span><span class="doxyHighlightStringLiteral">":defname"</span><span class="doxyHighlight">,a.name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1385</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1386</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!a.defval.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1387</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1388</span><span class="doxyLineContent"><span class="doxyHighlightComment">//#warning linkifyText(TextGeneratorXMLImpl(t),scope,fileScope,0,a.defval);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1389</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#a5615e9549a34565e146c795f7879a70c">param_select</a>,</span><span class="doxyHighlightStringLiteral">":defval"</span><span class="doxyHighlight">,a.defval);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1390</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>(<a href="#aeff7609bbf258f9fe7bb792def0251d6">param_insert</a>,</span><span class="doxyHighlightStringLiteral">":defval"</span><span class="doxyHighlight">,a.defval);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1391</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1392</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#a5615e9549a34565e146c795f7879a70c">param_select</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1393</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a>(<a href="#aeff7609bbf258f9fe7bb792def0251d6">param_insert</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1394</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1395</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a31980a5e7ccfb3be84828d1c106c4d1a">bindTextParameter</a>, <a href="#aeff7609bbf258f9fe7bb792def0251d6">param&#95;insert</a>, <a href="#a5615e9549a34565e146c795f7879a70c">param&#95;select</a>, <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="#adbab9cdf5d958b7f7ac7b736428974dd">writeMemberTemplateLists</a>, <a href="#a751d93630bc7cb9fa396ce5322fc9aab">writeTemplateList</a> and <a href="#a48aeba774bb636ba277d83e94b205291">writeTemplateList</a>.
</div>
</div>

### writeTemplateList() {#a751d93630bc7cb9fa396ce5322fc9aab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeTemplateList (const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd)</td>
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


<p>Definition at line 1402 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a751d93630bc7cb9fa396ce5322fc9aab">1402</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a751d93630bc7cb9fa396ce5322fc9aab">writeTemplateList</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1403</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1404</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8f2bd54985a7da4e6c800829305bece1">writeTemplateArgumentList</a>(cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a201b8f24043f9b7c7cc59d55282f6d47">templateArguments</a>(),cd,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#aed4a0864e51e5a3ac616f6c8e10f56c6">getFileDef</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1405</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/classdef/#aed4a0864e51e5a3ac616f6c8e10f56c6">ClassDef::getFileDef</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a201b8f24043f9b7c7cc59d55282f6d47">ClassDef::templateArguments</a> and <a href="#a8f2bd54985a7da4e6c800829305bece1">writeTemplateArgumentList</a>.

Referenced by <a href="#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a> and <a href="#a3889d30b147517190ccd9c1ebb9ca785">generateSqlite3ForConcept</a>.
</div>
</div>

### writeTemplateList() {#a48aeba774bb636ba277d83e94b205291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeTemplateList (const <a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a> * cd)</td>
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


<p>Definition at line 1407 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a48aeba774bb636ba277d83e94b205291">1407</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a751d93630bc7cb9fa396ce5322fc9aab">writeTemplateList</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a> *cd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1408</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1409</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8f2bd54985a7da4e6c800829305bece1">writeTemplateArgumentList</a>(cd-&gt;<a href="/web-doxygen/docs/api/classes/conceptdef/#a3dc85d76254ee240faaf13633a0639ba">getTemplateParameterList</a>(),cd,cd-&gt;<a href="/web-doxygen/docs/api/classes/conceptdef/#aeb0ed9ee2cbf2c93f995d74cc66d5399">getFileDef</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1410</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/conceptdef/#aeb0ed9ee2cbf2c93f995d74cc66d5399">ConceptDef::getFileDef</a>, <a href="/web-doxygen/docs/api/classes/conceptdef/#a3dc85d76254ee240faaf13633a0639ba">ConceptDef::getTemplateParameterList</a> and <a href="#a8f2bd54985a7da4e6c800829305bece1">writeTemplateArgumentList</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### compounddef&#95;exists {#a162bb86dfaf3254e93b1274353cd1cbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SqlStmt compounddef_exists</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">={
  "SELECT EXISTS ("
    "SELECT &#42; FROM compounddef WHERE rowid = :rowid"
  ")"
  ,nullptr
}
</div>
</dd>
</dl>

<p>Definition at line 791 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a162bb86dfaf3254e93b1274353cd1cbf">791</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> <a href="#a162bb86dfaf3254e93b1274353cd1cbf">compounddef_exists</a>={</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">792</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"SELECT EXISTS ("</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">793</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"SELECT * FROM compounddef WHERE rowid = :rowid"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">794</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">")"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">795</span><span class="doxyLineContent"><span class="doxyHighlight">  ,</span><span class="doxyHighlightKeyword">nullptr</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">796</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


Referenced by <a href="#a19ff8cd8130e662be4112bc914f7b50b">compounddefExists</a> and <a href="#a5c243ba2fe5dbbef9eae72870cb045ff">prepareStatements</a>.
</div>
</div>

### compounddef&#95;insert {#af3ea29d4c1a5d7adfb8e60de9a471f5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SqlStmt compounddef_insert</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 760 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">760</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> <a href="#af3ea29d4c1a5d7adfb8e60de9a471f5f">compounddef_insert</a>={</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">761</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"INSERT INTO compounddef "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">762</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"("</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">763</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"rowid,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">764</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"name,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">765</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"title,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">766</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"kind,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">767</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"prot,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">768</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"file_id,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">769</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"line,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">770</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"column,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">771</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"header_id,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">772</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"briefdescription,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">773</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"detaileddescription"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">774</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">")"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">775</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"VALUES "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">776</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"("</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">777</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":rowid,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">778</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":name,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">779</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":title,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">780</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":kind,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">781</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":prot,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">782</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":file_id,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">783</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":line,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">784</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":column,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">785</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":header_id,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">786</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":briefdescription,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">787</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":detaileddescription"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">788</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">")"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">789</span><span class="doxyLineContent"><span class="doxyHighlight">  ,</span><span class="doxyHighlightKeyword">nullptr</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">790</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


Referenced by <a href="#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>, <a href="#a3889d30b147517190ccd9c1ebb9ca785">generateSqlite3ForConcept</a>, <a href="#a96d60ce1da0cc36d049c1a2bbc174178">generateSqlite3ForDir</a>, <a href="#ae7139b08c0c942d65c6bcb8402a8b142">generateSqlite3ForFile</a>, <a href="#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a>, <a href="#a2b0628c4001ddb19730a764b29b0be44">generateSqlite3ForModule</a>, <a href="#ad5597180db00f8bb26d51d9b3b409241">generateSqlite3ForNamespace</a>, <a href="#aeb4c1aeb9fc32917845d0d05a52cb478">generateSqlite3ForPage</a> and <a href="#a5c243ba2fe5dbbef9eae72870cb045ff">prepareStatements</a>.
</div>
</div>

### compoundref&#95;insert {#a33e0611a73afb936b8c97c6812e64029}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SqlStmt compoundref_insert</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">={
  "INSERT INTO compoundref "
    "( base&#95;rowid, derived&#95;rowid, prot, virt ) "
  "VALUES "
    "(:base&#95;rowid,:derived&#95;rowid,:prot,:virt )"
  ,nullptr
}
</div>
</dd>
</dl>

<p>Definition at line 798 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a33e0611a73afb936b8c97c6812e64029">798</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> <a href="#a33e0611a73afb936b8c97c6812e64029">compoundref_insert</a>={</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">799</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"INSERT INTO compoundref "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">800</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"( base_rowid, derived_rowid, prot, virt ) "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">801</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"VALUES "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">802</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"(:base_rowid,:derived_rowid,:prot,:virt )"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">803</span><span class="doxyLineContent"><span class="doxyHighlight">  ,</span><span class="doxyHighlightKeyword">nullptr</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">804</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


Referenced by <a href="#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a> and <a href="#a5c243ba2fe5dbbef9eae72870cb045ff">prepareStatements</a>.
</div>
</div>

### contains&#95;insert {#a99ccc174540ee8c15b0f0c296dc5159e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SqlStmt contains_insert</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">={
  "INSERT INTO contains "
    "( inner&#95;rowid, outer&#95;rowid )"
  "VALUES "
    "(:inner&#95;rowid,:outer&#95;rowid )"
  ,nullptr
}
</div>
</dd>
</dl>

<p>Definition at line 539 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a99ccc174540ee8c15b0f0c296dc5159e">539</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> <a href="#a99ccc174540ee8c15b0f0c296dc5159e">contains_insert</a>={</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">540</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"INSERT INTO contains "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">541</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"( inner_rowid, outer_rowid )"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">542</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"VALUES "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">543</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"(:inner_rowid,:outer_rowid )"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">544</span><span class="doxyLineContent"><span class="doxyHighlight">  ,</span><span class="doxyHighlightKeyword">nullptr</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">545</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


Referenced by <a href="#a5c243ba2fe5dbbef9eae72870cb045ff">prepareStatements</a>, <a href="#a3b94451a3cd1a0d6cc44e2a9a2118481">writeInnerClasses</a>, <a href="#a46ef1ad7fcb0bd63228beb9a14e7f4bd">writeInnerConcepts</a>, <a href="#ad1e096e657dc0a4918d8ad80ffa233a8">writeInnerDirs</a>, <a href="#a9e4b392824ade3c727f39d6717bdc97f">writeInnerFiles</a>, <a href="#a472ea2a1d309024f061e7d48d1dd3839">writeInnerGroups</a>, <a href="#a68dad0e13a83b4eb9046a6e6588a855f">writeInnerModules</a>, <a href="#a597b4509789d2af90e78fe008fa832ab">writeInnerNamespaces</a> and <a href="#a4b9d2814806d6388bddc5f4c141d8fbf">writeInnerPages</a>.
</div>
</div>

### incl&#95;insert {#a9c15b3b9b3db6bf609838c68c915d80a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SqlStmt incl_insert</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  "INSERT INTO includes "
    "( local, src&#95;id, dst&#95;id ) "
  "VALUES "
    "(:local,:src&#95;id,:dst&#95;id )"
  ,nullptr
}
</div>
</dd>
</dl>

<p>Definition at line 526 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9c15b3b9b3db6bf609838c68c915d80a">526</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> <a href="#a9c15b3b9b3db6bf609838c68c915d80a">incl_insert</a> = {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">527</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"INSERT INTO includes "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">528</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"( local, src_id, dst_id ) "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">529</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"VALUES "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">530</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"(:local,:src_id,:dst_id )"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">531</span><span class="doxyLineContent"><span class="doxyHighlight">  ,</span><span class="doxyHighlightKeyword">nullptr</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">532</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


Referenced by <a href="#ae7139b08c0c942d65c6bcb8402a8b142">generateSqlite3ForFile</a> and <a href="#a5c243ba2fe5dbbef9eae72870cb045ff">prepareStatements</a>.
</div>
</div>

### incl&#95;select {#a1e3e98a7897963c61baf003aab5fecfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SqlStmt incl_select</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  "SELECT COUNT(&#42;) FROM includes WHERE "
  "local=:local AND src&#95;id=:src&#95;id AND dst&#95;id=:dst&#95;id"
  ,nullptr
}
</div>
</dd>
</dl>

<p>Definition at line 533 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1e3e98a7897963c61baf003aab5fecfa">533</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> <a href="#a1e3e98a7897963c61baf003aab5fecfa">incl_select</a> = {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">534</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"SELECT COUNT(*) FROM includes WHERE "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">535</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"local=:local AND src_id=:src_id AND dst_id=:dst_id"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">536</span><span class="doxyLineContent"><span class="doxyHighlight">  ,</span><span class="doxyHighlightKeyword">nullptr</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">537</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


Referenced by <a href="#ae7139b08c0c942d65c6bcb8402a8b142">generateSqlite3ForFile</a> and <a href="#a5c243ba2fe5dbbef9eae72870cb045ff">prepareStatements</a>.
</div>
</div>

### member&#95;insert {#a7ff598f38ef2dad027845c7abaa65592}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SqlStmt member_insert</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">={
  "INSERT INTO member "
    "( scope&#95;rowid, memberdef&#95;rowid, prot, virt ) "
  "VALUES "
    "(:scope&#95;rowid,:memberdef&#95;rowid,:prot,:virt )"
  ,nullptr
}
</div>
</dd>
</dl>

<p>Definition at line 752 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7ff598f38ef2dad027845c7abaa65592">752</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> <a href="#a7ff598f38ef2dad027845c7abaa65592">member_insert</a>={</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">753</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"INSERT INTO member "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">754</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"( scope_rowid, memberdef_rowid, prot, virt ) "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">755</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"VALUES "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">756</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"(:scope_rowid,:memberdef_rowid,:prot,:virt )"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">757</span><span class="doxyLineContent"><span class="doxyHighlight">  ,</span><span class="doxyHighlightKeyword">nullptr</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">758</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


Referenced by <a href="#affa42bdf0b91c838fe0215b4e6afb7b5">associateMember</a> and <a href="#a5c243ba2fe5dbbef9eae72870cb045ff">prepareStatements</a>.
</div>
</div>

### memberdef&#95;exists {#ad5786eb5fdd727a497982eb3b0901680}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SqlStmt memberdef_exists</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">={
  "SELECT EXISTS (SELECT &#42; FROM memberdef WHERE rowid = :rowid)"
  ,nullptr
}
</div>
</dd>
</dl>

<p>Definition at line 586 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad5786eb5fdd727a497982eb3b0901680">586</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> <a href="#ad5786eb5fdd727a497982eb3b0901680">memberdef_exists</a>={</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">587</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"SELECT EXISTS (SELECT * FROM memberdef WHERE rowid = :rowid)"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlight">  ,</span><span class="doxyHighlightKeyword">nullptr</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">589</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


Referenced by <a href="#a06d5fa6f8acbfef6705314884b6e6800">memberdefExists</a> and <a href="#a5c243ba2fe5dbbef9eae72870cb045ff">prepareStatements</a>.
</div>
</div>

### memberdef&#95;incomplete {#a2aef529ba9a8abda7c5dbe9f9c2b183b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SqlStmt memberdef_incomplete</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">={
  "SELECT EXISTS ("
    "SELECT &#42; FROM memberdef WHERE "
    "rowid = :rowid AND inline != 2 AND inline != :new&#95;inline"
  ")"
  ,nullptr
}
</div>
</dd>
</dl>

<p>Definition at line 591 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2aef529ba9a8abda7c5dbe9f9c2b183b">591</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> <a href="#a2aef529ba9a8abda7c5dbe9f9c2b183b">memberdef_incomplete</a>={</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">592</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"SELECT EXISTS ("</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">593</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"SELECT * FROM memberdef WHERE "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"rowid = :rowid AND inline != 2 AND inline != :new_inline"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">")"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">  ,</span><span class="doxyHighlightKeyword">nullptr</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


Referenced by <a href="#a2a696974b4a7902e4137be55d5337d20">memberdefIncomplete</a> and <a href="#a5c243ba2fe5dbbef9eae72870cb045ff">prepareStatements</a>.
</div>
</div>

### memberdef&#95;insert {#a044bf3040887411b780222535ef94942}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SqlStmt memberdef_insert</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 599 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a044bf3040887411b780222535ef94942">599</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> <a href="#a044bf3040887411b780222535ef94942">memberdef_insert</a>={</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"INSERT INTO memberdef "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">601</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"("</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">602</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"rowid,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">603</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"name,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">604</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"definition,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"type,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"argsstring,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"scope,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"initializer,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"bitfield,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"read,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"write,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"prot,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">613</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"static,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">614</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"extern,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">615</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"const,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">616</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"explicit,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"inline,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">618</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"final,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">619</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"sealed,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">620</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"new,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">621</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"optional,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">622</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"required,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">623</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"volatile,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">624</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"virt,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">625</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"mutable,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">626</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"initonly,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">627</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"attribute,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">628</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"property,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">629</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"readonly,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">630</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"bound,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">631</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"constrained,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">632</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"transient,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">633</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"maybevoid,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">634</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"maybedefault,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">635</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"maybeambiguous,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">636</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"readable,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">637</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"writable,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">638</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"gettable,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">639</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"protectedsettable,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">640</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"protectedgettable,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">641</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"settable,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">642</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"privatesettable,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">643</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"privategettable,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">644</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"accessor,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">645</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"addable,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">646</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"removable,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">647</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"raisable,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">648</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"kind,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">649</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"bodystart,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">650</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"bodyend,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">651</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"bodyfile_id,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">652</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"file_id,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">653</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"line,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">654</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"column,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">655</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"detaileddescription,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">656</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"briefdescription,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">657</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"inbodydescription"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">658</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">")"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">659</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"VALUES "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">660</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"("</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">661</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":rowid,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">662</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":name,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">663</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":definition,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">664</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":type,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">665</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":argsstring,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">666</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":scope,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":initializer,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">668</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":bitfield,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":read,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">670</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":write,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">671</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":prot,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">672</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":static,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">673</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":extern,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">674</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":const,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">675</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":explicit,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">676</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":inline,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">677</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":final,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">678</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":sealed,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">679</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":new,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">680</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":optional,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">681</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":required,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">682</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":volatile,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">683</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":virt,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">684</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":mutable,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">685</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":initonly,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">686</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":attribute,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">687</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":property,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">688</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":readonly,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">689</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":bound,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">690</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":constrained,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">691</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":transient,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">692</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":maybevoid,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">693</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":maybedefault,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">694</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":maybeambiguous,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":readable,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">696</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":writable,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">697</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":gettable,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">698</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":protectedsettable,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">699</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":protectedgettable,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">700</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":settable,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">701</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":privatesettable,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">702</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":privategettable,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">703</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":accessor,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">704</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":addable,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">705</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":removable,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">706</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":raisable,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">707</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":kind,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">708</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":bodystart,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">709</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":bodyend,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">710</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":bodyfile_id,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">711</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":file_id,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">712</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":line,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">713</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":column,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">714</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":detaileddescription,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">715</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":briefdescription,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">716</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">":inbodydescription"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">717</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">")"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">718</span><span class="doxyLineContent"><span class="doxyHighlight">  ,</span><span class="doxyHighlightKeyword">nullptr</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">719</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


Referenced by <a href="#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a> and <a href="#a5c243ba2fe5dbbef9eae72870cb045ff">prepareStatements</a>.
</div>
</div>

### memberdef&#95;param&#95;insert {#a9fd0d6eb855cc81bc77248083bc52316}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SqlStmt memberdef_param_insert</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">={
  "INSERT INTO memberdef&#95;param "
    "( memberdef&#95;id, param&#95;id)"
  "VALUES "
    "(:memberdef&#95;id,:param&#95;id)"
  ,nullptr
}
</div>
</dd>
</dl>

<p>Definition at line 825 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9fd0d6eb855cc81bc77248083bc52316">825</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> <a href="#a9fd0d6eb855cc81bc77248083bc52316">memberdef_param_insert</a>={</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">826</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"INSERT INTO memberdef_param "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">827</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"( memberdef_id, param_id)"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">828</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"VALUES "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">829</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"(:memberdef_id,:param_id)"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">830</span><span class="doxyLineContent"><span class="doxyHighlight">  ,</span><span class="doxyHighlightKeyword">nullptr</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">831</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


Referenced by <a href="#a6ff307313c1b28d89ef63fef3590ad36">insertMemberDefineParams</a>, <a href="#a3a9064a0bd3f19c550c68c5839dec5a6">insertMemberFunctionParams</a> and <a href="#a5c243ba2fe5dbbef9eae72870cb045ff">prepareStatements</a>.
</div>
</div>

### memberdef&#95;update&#95;decl {#a9dd6736df9437b0372601f0fc9256cdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SqlStmt memberdef_update_decl</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">={
  "UPDATE memberdef SET "
    "inline = :inline,"
    "file&#95;id = :file&#95;id,"
    "line = :line,"
    "column = :column,"
    "detaileddescription = 'Declaration: ' || :detaileddescription || 'Definition: ' || detaileddescription,"
    "briefdescription = 'Declaration: ' || :briefdescription || 'Definition: ' || briefdescription,"
    "inbodydescription = 'Declaration: ' || :inbodydescription || 'Definition: ' || inbodydescription "
  "WHERE rowid = :rowid"
  ,nullptr
}
</div>
</dd>
</dl>

<p>Definition at line 727 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9dd6736df9437b0372601f0fc9256cdc">727</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> <a href="#a9dd6736df9437b0372601f0fc9256cdc">memberdef_update_decl</a>={</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">728</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"UPDATE memberdef SET "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">729</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"inline = :inline,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">730</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"file_id = :file_id,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">731</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"line = :line,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">732</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"column = :column,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">733</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"detaileddescription = 'Declaration: ' || :detaileddescription || 'Definition: ' || detaileddescription,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">734</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"briefdescription = 'Declaration: ' || :briefdescription || 'Definition: ' || briefdescription,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">735</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"inbodydescription = 'Declaration: ' || :inbodydescription || 'Definition: ' || inbodydescription "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">736</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"WHERE rowid = :rowid"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">737</span><span class="doxyLineContent"><span class="doxyHighlight">  ,</span><span class="doxyHighlightKeyword">nullptr</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">738</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


Referenced by <a href="#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a> and <a href="#a5c243ba2fe5dbbef9eae72870cb045ff">prepareStatements</a>.
</div>
</div>

### memberdef&#95;update&#95;def {#a996b41f0018348eb70cb369999032333}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SqlStmt memberdef_update_def</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">={
  "UPDATE memberdef SET "
    "inline = :inline,"
    "bodystart = :bodystart,"
    "bodyend = :bodyend,"
    "bodyfile&#95;id = :bodyfile&#95;id,"
    "detaileddescription = 'Declaration: ' || detaileddescription || 'Definition: ' || :detaileddescription,"
    "briefdescription = 'Declaration: ' || briefdescription || 'Definition: ' || :briefdescription,"
    "inbodydescription = 'Declaration: ' || inbodydescription || 'Definition: ' || :inbodydescription "
  "WHERE rowid = :rowid"
  ,nullptr
}
</div>
</dd>
</dl>

<p>Definition at line 739 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a996b41f0018348eb70cb369999032333">739</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> <a href="#a996b41f0018348eb70cb369999032333">memberdef_update_def</a>={</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">740</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"UPDATE memberdef SET "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">741</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"inline = :inline,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">742</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"bodystart = :bodystart,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">743</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"bodyend = :bodyend,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">744</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"bodyfile_id = :bodyfile_id,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">745</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"detaileddescription = 'Declaration: ' || detaileddescription || 'Definition: ' || :detaileddescription,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">746</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"briefdescription = 'Declaration: ' || briefdescription || 'Definition: ' || :briefdescription,"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">747</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"inbodydescription = 'Declaration: ' || inbodydescription || 'Definition: ' || :inbodydescription "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">748</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"WHERE rowid = :rowid"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">749</span><span class="doxyLineContent"><span class="doxyHighlight">  ,</span><span class="doxyHighlightKeyword">nullptr</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">750</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


Referenced by <a href="#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a> and <a href="#a5c243ba2fe5dbbef9eae72870cb045ff">prepareStatements</a>.
</div>
</div>

### meta&#95;insert {#ac593dfdd38adfad8de3e87c2405f65b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SqlStmt meta_insert</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  "INSERT INTO meta "
    "( doxygen&#95;version, schema&#95;version, generated&#95;at, generated&#95;on, project&#95;name, project&#95;number, project&#95;brief )"
  "VALUES "
    "(:doxygen&#95;version,:schema&#95;version,:generated&#95;at,:generated&#95;on,:project&#95;name,:project&#95;number,:project&#95;brief )"
  ,nullptr
}
</div>
</dd>
</dl>

<p>Definition at line 518 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac593dfdd38adfad8de3e87c2405f65b2">518</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> <a href="#ac593dfdd38adfad8de3e87c2405f65b2">meta_insert</a> = {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"INSERT INTO meta "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"( doxygen_version, schema_version, generated_at, generated_on, project_name, project_number, project_brief )"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">521</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"VALUES "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"(:doxygen_version,:schema_version,:generated_at,:generated_on,:project_name,:project_number,:project_brief )"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">  ,</span><span class="doxyHighlightKeyword">nullptr</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


Referenced by <a href="#a5c243ba2fe5dbbef9eae72870cb045ff">prepareStatements</a> and <a href="#a0e33b2ef2c8bf323a8a2f1d4bb13a5ca">recordMetadata</a>.
</div>
</div>

### param&#95;insert {#aeff7609bbf258f9fe7bb792def0251d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SqlStmt param_insert</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  "INSERT INTO param "
    "( attributes, type, declname, defname, array, defval, briefdescription ) "
  "VALUES "
    "(:attributes,:type,:declname,:defname,:array,:defval,:briefdescription)"
  ,nullptr
}
</div>
</dd>
</dl>

<p>Definition at line 817 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aeff7609bbf258f9fe7bb792def0251d6">817</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> <a href="#aeff7609bbf258f9fe7bb792def0251d6">param_insert</a> = {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">818</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"INSERT INTO param "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">819</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"( attributes, type, declname, defname, array, defval, briefdescription ) "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">820</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"VALUES "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">821</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"(:attributes,:type,:declname,:defname,:array,:defval,:briefdescription)"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">822</span><span class="doxyLineContent"><span class="doxyHighlight">  ,</span><span class="doxyHighlightKeyword">nullptr</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">823</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


Referenced by <a href="#a6ff307313c1b28d89ef63fef3590ad36">insertMemberDefineParams</a>, <a href="#a3a9064a0bd3f19c550c68c5839dec5a6">insertMemberFunctionParams</a>, <a href="#a5c243ba2fe5dbbef9eae72870cb045ff">prepareStatements</a> and <a href="#a8f2bd54985a7da4e6c800829305bece1">writeTemplateArgumentList</a>.
</div>
</div>

### param&#95;select {#a5615e9549a34565e146c795f7879a70c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SqlStmt param_select</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  "SELECT rowid FROM param WHERE "
    "(attributes IS NULL OR attributes=:attributes) AND "
    "(type IS NULL OR type=:type) AND "
    "(declname IS NULL OR declname=:declname) AND "
    "(defname IS NULL OR defname=:defname) AND "
    "(array IS NULL OR array=:array) AND "
    "(defval IS NULL OR defval=:defval) AND "
    "(briefdescription IS NULL OR briefdescription=:briefdescription)"
  ,nullptr
}
</div>
</dd>
</dl>

<p>Definition at line 806 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5615e9549a34565e146c795f7879a70c">806</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> <a href="#a5615e9549a34565e146c795f7879a70c">param_select</a> = {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">807</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"SELECT rowid FROM param WHERE "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">808</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"(attributes IS NULL OR attributes=:attributes) AND "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">809</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"(type IS NULL OR type=:type) AND "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">810</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"(declname IS NULL OR declname=:declname) AND "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">811</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"(defname IS NULL OR defname=:defname) AND "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">812</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"(array IS NULL OR array=:array) AND "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">813</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"(defval IS NULL OR defval=:defval) AND "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">814</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"(briefdescription IS NULL OR briefdescription=:briefdescription)"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">815</span><span class="doxyLineContent"><span class="doxyHighlight">  ,</span><span class="doxyHighlightKeyword">nullptr</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">816</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


Referenced by <a href="#a3a9064a0bd3f19c550c68c5839dec5a6">insertMemberFunctionParams</a>, <a href="#a5c243ba2fe5dbbef9eae72870cb045ff">prepareStatements</a> and <a href="#a8f2bd54985a7da4e6c800829305bece1">writeTemplateArgumentList</a>.
</div>
</div>

### path&#95;insert {#ab3954473f4ed653652992317306a884b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SqlStmt path_insert</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  "INSERT INTO path "
    "( type, local, found, name )"
  "VALUES "
    "(:type,:local,:found,:name )"
  ,nullptr
}
</div>
</dd>
</dl>

<p>Definition at line 551 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab3954473f4ed653652992317306a884b">551</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> <a href="#ab3954473f4ed653652992317306a884b">path_insert</a> = {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">552</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"INSERT INTO path "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">553</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"( type, local, found, name )"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">554</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"VALUES "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">555</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"(:type,:local,:found,:name )"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">556</span><span class="doxyLineContent"><span class="doxyHighlight">  ,</span><span class="doxyHighlightKeyword">nullptr</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">557</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


Referenced by <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a> and <a href="#a5c243ba2fe5dbbef9eae72870cb045ff">prepareStatements</a>.
</div>
</div>

### path&#95;select {#ae8c2b376b75f41e8807c6db20df8de47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SqlStmt path_select</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  "SELECT rowid FROM path WHERE name=:name"
  ,nullptr
}
</div>
</dd>
</dl>

<p>Definition at line 547 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae8c2b376b75f41e8807c6db20df8de47">547</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> <a href="#ae8c2b376b75f41e8807c6db20df8de47">path_select</a> = {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">548</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"SELECT rowid FROM path WHERE name=:name"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">549</span><span class="doxyLineContent"><span class="doxyHighlight">  ,</span><span class="doxyHighlightKeyword">nullptr</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">550</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


Referenced by <a href="#a5335bb36c398920d8075493f1aedc119">insertPath</a> and <a href="#a5c243ba2fe5dbbef9eae72870cb045ff">prepareStatements</a>.
</div>
</div>

### refid&#95;insert {#a3f9a714e57e3f2d5b40ca9e2b5e1edf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SqlStmt refid_insert</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  "INSERT INTO refid "
    "( refid )"
  "VALUES "
    "(:refid )"
  ,nullptr
}
</div>
</dd>
</dl>

<p>Definition at line 563 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3f9a714e57e3f2d5b40ca9e2b5e1edf2">563</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> <a href="#a3f9a714e57e3f2d5b40ca9e2b5e1edf2">refid_insert</a> = {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"INSERT INTO refid "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"( refid )"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">566</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"VALUES "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">567</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"(:refid )"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">568</span><span class="doxyLineContent"><span class="doxyHighlight">  ,</span><span class="doxyHighlightKeyword">nullptr</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">569</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


Referenced by <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a> and <a href="#a5c243ba2fe5dbbef9eae72870cb045ff">prepareStatements</a>.
</div>
</div>

### refid&#95;select {#af21d2af0294b7e22f02b098a43ec276d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SqlStmt refid_select</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=  {
  "SELECT rowid FROM refid WHERE refid=:refid"
  ,nullptr
}
</div>
</dd>
</dl>

<p>Definition at line 559 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af21d2af0294b7e22f02b098a43ec276d">559</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> <a href="#af21d2af0294b7e22f02b098a43ec276d">refid_select</a> =  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">560</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"SELECT rowid FROM refid WHERE refid=:refid"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">561</span><span class="doxyLineContent"><span class="doxyHighlight">  ,</span><span class="doxyHighlightKeyword">nullptr</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


Referenced by <a href="#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a> and <a href="#a5c243ba2fe5dbbef9eae72870cb045ff">prepareStatements</a>.
</div>
</div>

### reimplements&#95;insert {#a6ef03b7de5c740c3ad04b46fee17e6e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SqlStmt reimplements_insert</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  "INSERT INTO reimplements "
    "( memberdef&#95;rowid, reimplemented&#95;rowid )"
  "VALUES "
    "(:memberdef&#95;rowid,:reimplemented&#95;rowid )"
  ,nullptr
}
</div>
</dd>
</dl>

<p>Definition at line 578 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6ef03b7de5c740c3ad04b46fee17e6e0">578</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> <a href="#a6ef03b7de5c740c3ad04b46fee17e6e0">reimplements_insert</a>= {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"INSERT INTO reimplements "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"( memberdef_rowid, reimplemented_rowid )"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"VALUES "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"(:memberdef_rowid,:reimplemented_rowid )"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">  ,</span><span class="doxyHighlightKeyword">nullptr</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">584</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


Referenced by <a href="#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a> and <a href="#a5c243ba2fe5dbbef9eae72870cb045ff">prepareStatements</a>.
</div>
</div>

### table&#95;schema {#a7b91ef07fa780f5b7c37c73863df5e11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* table_schema[][2]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 77 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7b91ef07fa780f5b7c37c73863df5e11">77</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> * <a href="#a7b91ef07fa780f5b7c37c73863df5e11">table_schema</a>[][2] = {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/* TABLES */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"meta"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"CREATE TABLE IF NOT EXISTS meta (\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t-- Information about this db and how it was generated.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t-- Doxygen info\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tdoxygen_version    TEXT PRIMARY KEY NOT NULL,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">/*</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlightComment">      Doxygen's version is likely to rollover much faster than the schema, and</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlightComment">      at least until it becomes a core output format, we might want to make</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlightComment">      fairly large schema changes even on minor iterations for Doxygen itself.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlightComment">      If these tools just track a predefined semver schema version that can</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlightComment">      iterate independently, it *might* not be as hard to keep them in sync?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlightComment">      */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tschema_version     TEXT NOT NULL, -- Schema-specific semver\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t-- run info\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tgenerated_at       TEXT NOT NULL,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tgenerated_on       TEXT NOT NULL,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t-- project info\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tproject_name       TEXT NOT NULL,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tproject_number     TEXT,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tproject_brief      TEXT\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">");"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"includes"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"CREATE TABLE IF NOT EXISTS includes (\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t-- #include relations.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\trowid        INTEGER PRIMARY KEY AUTOINCREMENT NOT NULL,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tlocal        INTEGER NOT NULL,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tsrc_id       INTEGER NOT NULL REFERENCES path, -- File id of the includer.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tdst_id       INTEGER NOT NULL REFERENCES path, -- File id of the includee.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">/*</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlightComment">      In theory we could include name here to be informationally equivalent</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlightComment">      with the XML, but I don't see an obvious use for it.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlightComment">      */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tUNIQUE(local, src_id, dst_id) ON CONFLICT IGNORE\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">");"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"contains"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"CREATE TABLE IF NOT EXISTS contains (\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t-- inner/outer relations (file, namespace, dir, class, group, page)\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\trowid        INTEGER PRIMARY KEY AUTOINCREMENT NOT NULL,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tinner_rowid  INTEGER NOT NULL REFERENCES compounddef,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\touter_rowid  INTEGER NOT NULL REFERENCES compounddef\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">");"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/* TODO: Path can also share rowids with refid/compounddef/def. (It could</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlightComment">   *       even collapse into that table...)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlightComment">   *</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlightComment">   * I took a first swing at this by changing insertPath() to:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlightComment">   * - accept a FileDef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlightComment">   * - make its own call to insertRefid</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlightComment">   * - return a refid struct.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlightComment">   *</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlightComment">   * I rolled this back when I had trouble getting a FileDef for all types</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlightComment">   * (PageDef in particular).</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlightComment">   *</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlightComment">   * Note: all columns referencing path would need an update.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlightComment">   */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"path"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"CREATE TABLE IF NOT EXISTS path (\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t-- Paths of source files and includes.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\trowid        INTEGER PRIMARY KEY AUTOINCREMENT NOT NULL,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\ttype         INTEGER NOT NULL, -- 1:file 2:dir\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tlocal        INTEGER NOT NULL,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tfound        INTEGER NOT NULL,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tname         TEXT NOT NULL\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">");"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"refid"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"CREATE TABLE IF NOT EXISTS refid (\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t-- Distinct refid for all documented entities.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\trowid        INTEGER PRIMARY KEY AUTOINCREMENT NOT NULL,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\trefid        TEXT NOT NULL UNIQUE\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">");"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"xrefs"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"CREATE TABLE IF NOT EXISTS xrefs (\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t-- Cross-reference relation\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t-- (combines xml &lt;referencedby&gt; and &lt;references&gt; nodes).\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\trowid        INTEGER PRIMARY KEY AUTOINCREMENT NOT NULL,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tsrc_rowid    INTEGER NOT NULL REFERENCES refid, -- referrer id.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tdst_rowid    INTEGER NOT NULL REFERENCES refid, -- referee id.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tcontext      TEXT NOT NULL, -- inline, argument, initializer\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t-- Just need to know they link; ignore duplicates.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tUNIQUE(src_rowid, dst_rowid, context) ON CONFLICT IGNORE\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">");\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"memberdef"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"CREATE TABLE IF NOT EXISTS memberdef (\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t-- All processed identifiers.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\trowid                INTEGER PRIMARY KEY NOT NULL,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tname                 TEXT NOT NULL,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tdefinition           TEXT,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\ttype                 TEXT,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\targsstring           TEXT,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tscope                TEXT,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tinitializer          TEXT,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tbitfield             TEXT,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tread                 TEXT,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\twrite                TEXT,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tprot                 INTEGER DEFAULT 0, -- 0:public 1:protected 2:private 3:package\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tstatic               INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\textern               INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tconst                INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\texplicit             INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tinline               INTEGER DEFAULT 0, -- 0:no 1:yes 2:both (set after encountering inline and not-inline)\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tfinal                INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tsealed               INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tnew                  INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\toptional             INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\trequired             INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tvolatile             INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tvirt                 INTEGER DEFAULT 0, -- 0:no 1:virtual 2:pure-virtual\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tmutable              INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tinitonly             INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tattribute            INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tproperty             INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\treadonly             INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tbound                INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tconstrained          INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\ttransient            INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tmaybevoid            INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tmaybedefault         INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tmaybeambiguous       INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\treadable             INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\twritable             INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tgettable             INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tprivategettable      INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tprotectedgettable    INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tsettable             INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tprivatesettable      INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tprotectedsettable    INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\taccessor             INTEGER DEFAULT 0, -- 0:no 1:assign 2:copy 3:retain 4:string 5:weak\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\taddable              INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tremovable            INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\traisable             INTEGER DEFAULT 0, -- 0:no 1:yes\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tkind                 TEXT NOT NULL, -- 'macro definition' 'function' 'variable' 'typedef' 'enumeration' 'enumvalue' 'signal' 'slot' 'friend' 'dcop' 'property' 'event' 'interface' 'service'\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tbodystart            INTEGER DEFAULT 0, -- starting line of definition\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tbodyend              INTEGER DEFAULT 0, -- ending line of definition\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tbodyfile_id          INTEGER REFERENCES path, -- file of definition\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tfile_id              INTEGER NOT NULL REFERENCES path,  -- file where this identifier is located\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tline                 INTEGER NOT NULL,  -- line where this identifier is located\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tcolumn               INTEGER NOT NULL,  -- column where this identifier is located\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tdetaileddescription  TEXT,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tbriefdescription     TEXT,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tinbodydescription    TEXT,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tFOREIGN KEY (rowid) REFERENCES refid (rowid)\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">");"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"member"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"CREATE TABLE IF NOT EXISTS member (\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t-- Memberdef &lt;-&gt; containing compound relation.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t-- Similar to XML listofallmembers.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\trowid            INTEGER PRIMARY KEY AUTOINCREMENT NOT NULL,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tscope_rowid      INTEGER NOT NULL REFERENCES compounddef,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tmemberdef_rowid  INTEGER NOT NULL REFERENCES memberdef,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tprot             INTEGER NOT NULL,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tvirt             INTEGER NOT NULL,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tUNIQUE(scope_rowid, memberdef_rowid)\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">");"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"reimplements"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"CREATE TABLE IF NOT EXISTS reimplements (\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t-- Inherited member reimplementation relations.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\trowid                  INTEGER PRIMARY KEY AUTOINCREMENT NOT NULL,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tmemberdef_rowid        INTEGER NOT NULL REFERENCES memberdef, -- reimplementing memberdef id.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\treimplemented_rowid    INTEGER NOT NULL REFERENCES memberdef, -- reimplemented memberdef id.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tUNIQUE(memberdef_rowid, reimplemented_rowid) ON CONFLICT IGNORE\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">");\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"compounddef"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"CREATE TABLE IF NOT EXISTS compounddef (\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t-- Class/struct definitions.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\trowid                INTEGER PRIMARY KEY NOT NULL,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tname                 TEXT NOT NULL,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\ttitle                TEXT,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// probably won't be empty '' or unknown, but the source *could* return them...</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tkind                 TEXT NOT NULL, -- 'category' 'class' 'constants' 'dir' 'enum' 'example' 'exception' 'file' 'group' 'interface' 'library' 'module' 'namespace' 'package' 'page' 'protocol' 'service' 'singleton' 'struct' 'type' 'union' 'unknown' ''\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tprot                 INTEGER,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tfile_id              INTEGER NOT NULL REFERENCES path,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tline                 INTEGER NOT NULL,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tcolumn               INTEGER NOT NULL,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\theader_id            INTEGER REFERENCES path,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tdetaileddescription  TEXT,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tbriefdescription     TEXT,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tFOREIGN KEY (rowid) REFERENCES refid (rowid)\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">");"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"compoundref"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"CREATE TABLE IF NOT EXISTS compoundref (\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t-- Inheritance relation.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\trowid          INTEGER PRIMARY KEY AUTOINCREMENT NOT NULL,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tbase_rowid     INTEGER NOT NULL REFERENCES compounddef,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tderived_rowid  INTEGER NOT NULL REFERENCES compounddef,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tprot           INTEGER NOT NULL,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tvirt           INTEGER NOT NULL,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tUNIQUE(base_rowid, derived_rowid)\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">");"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"param"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"CREATE TABLE IF NOT EXISTS param (\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t-- All processed parameters.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\trowid        INTEGER PRIMARY KEY AUTOINCREMENT NOT NULL,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tattributes   TEXT,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\ttype         TEXT,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tdeclname     TEXT,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tdefname      TEXT,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tarray        TEXT,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tdefval       TEXT,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tbriefdescription TEXT\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">");"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"CREATE UNIQUE INDEX idx_param ON param\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t(type, defname);"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"memberdef_param"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"CREATE TABLE IF NOT EXISTS memberdef_param (\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t-- Junction table for memberdef parameters.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\trowid        INTEGER PRIMARY KEY AUTOINCREMENT NOT NULL,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tmemberdef_id INTEGER NOT NULL REFERENCES memberdef,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tparam_id     INTEGER NOT NULL REFERENCES param\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">");"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


Referenced by <a href="#a2413f906680d7e55e863d1f4d7385a84">initializeTables</a>.
</div>
</div>

### view&#95;schema {#a9b595d98aef36283b3ea75fdd312ed5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* view_schema[][2]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 301 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9b595d98aef36283b3ea75fdd312ed5c">301</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> * <a href="#a9b595d98aef36283b3ea75fdd312ed5c">view_schema</a>[][2] = {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/* VIEWS *</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlightComment">  We'll set these up AFTER we build the database, so that they can be indexed,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlightComment">  but so we don't have to pay a performance penalty for inserts as we build.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlightComment">  */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">/*</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlightComment">    Makes all reference/relation tables easier to use. For example:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlightComment">    1 query xrefs and join this view on either xrefs.dst_rowid=def.rowid or</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlightComment">       xrefs.src_rowid=def.rowid</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlightComment">    2 get everything you need to output a list of references to/from an entity</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlightComment">    Also supports simple name search/lookup for both compound and member types.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlightComment">    NOTES:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlightComment">    - summary for compounds generalizes title and briefdescription because</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span><span class="doxyLineContent"><span class="doxyHighlightComment">      there's no single field that works as a quick introduction for both</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlightComment">      pages and classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlightComment">    - May be value in eventually extending this to fulltext or levenshtein</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlightComment">      distance-driven lookup/search, but I'm avoiding these for now as it</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlightComment">      takes some effort to enable them.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlightComment">    */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"def"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"CREATE VIEW IF NOT EXISTS def (\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t-- Combined summary of all -def types for easier joins.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\trowid,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\trefid,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tkind,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tname,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tsummary"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">")\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"as SELECT \n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\trefid.rowid,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\trefid.refid,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tmemberdef.kind,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tmemberdef.name,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tmemberdef.briefdescription \n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"FROM refid \n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"JOIN memberdef ON refid.rowid=memberdef.rowid \n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"UNION ALL \n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"SELECT \n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\trefid.rowid,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\trefid.refid,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tcompounddef.kind,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tcompounddef.name,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tCASE \n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">347</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightStringLiteral">"\t\tWHEN briefdescription IS NOT NULL \n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightStringLiteral">"\t\tTHEN briefdescription \n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightStringLiteral">"\t\tELSE title \n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tEND summary\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">351</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"FROM refid \n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"JOIN compounddef ON refid.rowid=compounddef.rowid;"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">355</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"local_file"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">356</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"CREATE VIEW IF NOT EXISTS local_file (\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t-- File paths found within the project.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\trowid,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tfound,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tname\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">361</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">")\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"as SELECT \n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tpath.rowid,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tpath.found,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tpath.name\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">366</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"FROM path WHERE path.type=1 AND path.local=1 AND path.found=1;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">367</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"external_file"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"CREATE VIEW IF NOT EXISTS external_file (\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t-- File paths outside the project (found or not).\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\trowid,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tfound,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tname\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">")\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"as SELECT \n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tpath.rowid,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tpath.found,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tpath.name\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"FROM path WHERE path.type=1 AND path.local=0;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"inline_xrefs"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"CREATE VIEW IF NOT EXISTS inline_xrefs (\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t-- Crossrefs from inline member source.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\trowid,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tsrc_rowid,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tdst_rowid\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">")\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"as SELECT \n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\txrefs.rowid,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\txrefs.src_rowid,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\txrefs.dst_rowid\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"FROM xrefs WHERE xrefs.context='inline';\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"argument_xrefs"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"CREATE VIEW IF NOT EXISTS argument_xrefs (\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t-- Crossrefs from member def/decl arguments\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\trowid,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tsrc_rowid,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">402</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tdst_rowid\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">")\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"as SELECT \n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">405</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\txrefs.rowid,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">406</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\txrefs.src_rowid,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">407</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\txrefs.dst_rowid\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">408</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"FROM xrefs WHERE xrefs.context='argument';\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">409</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">411</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"initializer_xrefs"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">412</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"CREATE VIEW IF NOT EXISTS initializer_xrefs (\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">413</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t-- Crossrefs from member initializers\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">414</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\trowid,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">415</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tsrc_rowid,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tdst_rowid\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">417</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">")\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">418</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"as SELECT \n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">419</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\txrefs.rowid,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\txrefs.src_rowid,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">421</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\txrefs.dst_rowid\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">422</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"FROM xrefs WHERE xrefs.context='initializer';\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">423</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">424</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">425</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"inner_outer"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">426</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"CREATE VIEW IF NOT EXISTS inner_outer\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">427</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t-- Joins 'contains' relations to simplify inner/outer 'rel' queries.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">428</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"as SELECT \n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">429</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tinner.*,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">430</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\touter.*\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">431</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"FROM def as inner\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">432</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tJOIN contains ON inner.rowid=contains.inner_rowid\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">433</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tJOIN def AS outer ON outer.rowid=contains.outer_rowid;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">434</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">435</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"rel"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"CREATE VIEW IF NOT EXISTS rel (\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t-- Boolean indicator of relations available for a given entity.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">439</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t-- Join to (compound-|member-)def to find fetch-worthy relations.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\trowid,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">441</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\treimplemented,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">442</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\treimplements,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tinnercompounds,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\toutercompounds,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tinnerpages,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">446</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\touterpages,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">447</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tinnerdirs,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\touterdirs,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tinnerfiles,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\touterfiles,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tinnerclasses,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\touterclasses,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tinnernamespaces,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\touternamespaces,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tinnergroups,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\toutergroups,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">457</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tmembers,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tcompounds,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tsubclasses,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tsuperclasses,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tlinks_in,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tlinks_out,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\targument_links_in,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\targument_links_out,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tinitializer_links_in,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tinitializer_links_out\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">")\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"as SELECT \n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tdef.rowid,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tEXISTS (SELECT rowid FROM reimplements WHERE reimplemented_rowid=def.rowid),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tEXISTS (SELECT rowid FROM reimplements WHERE memberdef_rowid=def.rowid),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t-- rowid/kind for inner, [rowid:1/kind:1] for outer\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tEXISTS (SELECT * FROM inner_outer WHERE [rowid:1]=def.rowid),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tEXISTS (SELECT * FROM inner_outer WHERE rowid=def.rowid),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tEXISTS (SELECT * FROM inner_outer WHERE [rowid:1]=def.rowid AND kind='page'),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tEXISTS (SELECT * FROM inner_outer WHERE rowid=def.rowid AND [kind:1]='page'),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tEXISTS (SELECT * FROM inner_outer WHERE [rowid:1]=def.rowid AND kind='dir'),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tEXISTS (SELECT * FROM inner_outer WHERE rowid=def.rowid AND [kind:1]='dir'),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">479</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tEXISTS (SELECT * FROM inner_outer WHERE [rowid:1]=def.rowid AND kind='file'),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tEXISTS (SELECT * FROM inner_outer WHERE rowid=def.rowid AND [kind:1]='file'),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tEXISTS (SELECT * FROM inner_outer WHERE [rowid:1]=def.rowid AND kind in (\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightStringLiteral">"'category','class','enum','exception','interface','module','protocol',\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightStringLiteral">"'service','singleton','struct','type','union'\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">")),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tEXISTS (SELECT * FROM inner_outer WHERE rowid=def.rowid AND [kind:1] in (\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightStringLiteral">"'category','class','enum','exception','interface','module','protocol',\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightStringLiteral">"'service','singleton','struct','type','union'\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">")),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tEXISTS (SELECT * FROM inner_outer WHERE [rowid:1]=def.rowid AND kind='namespace'),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tEXISTS (SELECT * FROM inner_outer WHERE rowid=def.rowid AND [kind:1]='namespace'),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tEXISTS (SELECT * FROM inner_outer WHERE [rowid:1]=def.rowid AND kind='group'),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tEXISTS (SELECT * FROM inner_outer WHERE rowid=def.rowid AND [kind:1]='group'),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tEXISTS (SELECT rowid FROM member WHERE scope_rowid=def.rowid),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tEXISTS (SELECT rowid FROM member WHERE memberdef_rowid=def.rowid),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tEXISTS (SELECT rowid FROM compoundref WHERE base_rowid=def.rowid),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tEXISTS (SELECT rowid FROM compoundref WHERE derived_rowid=def.rowid),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tEXISTS (SELECT rowid FROM inline_xrefs WHERE dst_rowid=def.rowid),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tEXISTS (SELECT rowid FROM inline_xrefs WHERE src_rowid=def.rowid),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tEXISTS (SELECT rowid FROM argument_xrefs WHERE dst_rowid=def.rowid),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tEXISTS (SELECT rowid FROM argument_xrefs WHERE src_rowid=def.rowid),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tEXISTS (SELECT rowid FROM initializer_xrefs WHERE dst_rowid=def.rowid),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tEXISTS (SELECT rowid FROM initializer_xrefs WHERE src_rowid=def.rowid)\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"FROM def ORDER BY def.rowid;"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


Referenced by <a href="#aa9037481dd7efb932a1f5dc142922330">initializeViews</a>.
</div>
</div>

### xrefs&#95;insert {#a669c1f1c7bd2b5cfe3bc3e9294e81be9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SqlStmt xrefs_insert</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  "INSERT INTO xrefs "
    "( src&#95;rowid, dst&#95;rowid, context )"
  "VALUES "
    "(:src&#95;rowid,:dst&#95;rowid,:context )"
  ,nullptr
}
</div>
</dd>
</dl>

<p>Definition at line 571 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a669c1f1c7bd2b5cfe3bc3e9294e81be9">571</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/sqlstmt">SqlStmt</a> <a href="#a669c1f1c7bd2b5cfe3bc3e9294e81be9">xrefs_insert</a>= {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">572</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"INSERT INTO xrefs "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"( src_rowid, dst_rowid, context )"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightStringLiteral">"VALUES "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">575</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"(:src_rowid,:dst_rowid,:context )"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">576</span><span class="doxyLineContent"><span class="doxyHighlight">  ,</span><span class="doxyHighlightKeyword">nullptr</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">577</span><span class="doxyLineContent"><span class="doxyHighlight">};</span><span class="doxyHighlightComment">//////////////////////////////////////////////////////</span></span></div>

</div>


Referenced by <a href="#a204b468b29a5d8ae8cf305cc08766eb7">insertMemberReference</a> and <a href="#a5c243ba2fe5dbbef9eae72870cb045ff">prepareStatements</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DBG&#95;CTX {#a234e2efe67eececd88b140b46ea37463}

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


<p>Definition at line 67 of file <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp">sqlite3gen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a234e2efe67eececd88b140b46ea37463">67</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#  define DBG_CTX(x) do { } while(0)</span></span></div>

</div>


Referenced by <a href="#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>, <a href="#ae7139b08c0c942d65c6bcb8402a8b142">generateSqlite3ForFile</a>, <a href="#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="#a6ff307313c1b28d89ef63fef3590ad36">insertMemberDefineParams</a>, <a href="#a3a9064a0bd3f19c550c68c5839dec5a6">insertMemberFunctionParams</a>, <a href="#aaba2817dbf5f4afbbba5998976dbdab4">step</a> and <a href="/web-doxygen/docs/api/classes/textgeneratorsqlite3impl/#a0e2b894cd2ac80ba0d240f864f5a301e">TextGeneratorSqlite3Impl::writeBreak</a>.
</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
