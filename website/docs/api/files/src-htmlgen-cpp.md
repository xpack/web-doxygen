---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/htmlgen-cpp
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `htmlgen.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;stdlib.h&gt;
#include &lt;assert.h&gt;
#include &lt;mutex&gt;
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/diagram-h">diagram.h</a>"
#include "version.h"
#include "<a href="/web-doxygen/docs/api/files/src/dot-h">dot.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dotcallgraph-h">dotcallgraph.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dotclassgraph-h">dotclassgraph.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dotdirdeps-h">dotdirdeps.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-h">dotgfxhierarchytable.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-h">dotgroupcollaboration.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h">dotincldepgraph.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/language-h">language.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/htmlhelp-h">htmlhelp.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/docparser-h">docparser.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/htmldocvisitor-h">htmldocvisitor.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/pagedef-h">pagedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/image-h">image.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/ftvhelp-h">ftvhelp.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/resourcemgr-h">resourcemgr.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/tooltip-h">tooltip.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/fileinfo-h">fileinfo.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/utf8-h">utf8.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/indexlist-h">indexlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/datetime-h">datetime.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/portable-h">portable.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/stringutil-h">stringutil.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5924fde57d9d6dd319193f24735d748">writeClientSearchBox</a> (TextStream &amp;t, const QCString &amp;relPath)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a589d7504a995d3f00ae97b7684d588eb">writeServerSearchBox</a> (TextStream &amp;t, const QCString &amp;relPath, bool highlightSearch)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a880152a6988921d6248a7640983bef9e">getConvertLatexMacro</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert a set of LaTeX commands <span class="doxyComputerOutput">\(re)newcommand</span> to a form readable by MathJax LaTeX syntax: <a href="#a880152a6988921d6248a7640983bef9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa474343ce62c6bd88db53d9924b223a0">getSearchBox</a> (bool serverSide, QCString relPath, bool highlightSearch)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac61bfc9dccd1552c036f2a3aabcd6b2c">substituteHtmlKeywords</a> (const QCString &amp;file, const QCString &amp;str, const QCString &amp;title, const QCString &amp;relPath, const QCString &amp;navPath=QCString())</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f990fbb2a5c7d2c30dcf0425e578546">fillColorStyleMap</a> (const QCString &amp;definitions, StringUnorderedMap &amp;map)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac082e13d5df852dc8a34fd6e84668dff">fillColorStyleMaps</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f3978430bdfefcb92e25f2da8854f45">replaceVariables</a> (const QCString &amp;input)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7339dc7ff25bcb7a9fbea1d671a16da">writeDefaultStyleSheet</a> (TextStream &amp;t)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5f89137286ceb01d9c5a1a14a36d8e1">startSectionHeader</a> (TextStream &amp;t, const QCString &amp;relPath, int sectionCount)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2e58dbdf23ed7a1c24f10c4c81ec544">endSectionHeader</a> (TextStream &amp;t)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5de92e3118bc2a62d1f43598d1cb2028">startSectionSummary</a> (TextStream &amp;t, int sectionCount)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5b4dc7827454fb9508e9a7ee4e663e8">endSectionSummary</a> (TextStream &amp;t)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34e1ea8704b315e66086811539bd1a5f">startSectionContent</a> (TextStream &amp;t, int sectionCount)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95a7a96e259bc6213901ea61ae4ca431">endSectionContent</a> (TextStream &amp;t)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cd9e00e6fd36cfbc6a66324910eb618">startQuickIndexList</a> (TextStream &amp;t, bool topLevel=TRUE)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ec23d311243e38a80245d1f87084e11">endQuickIndexList</a> (TextStream &amp;t)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a607223d8bf91989cb35218acc2b95e3c">startQuickIndexItem</a> (TextStream &amp;t, const QCString &amp;l, bool hl, bool, const QCString &amp;relPath)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac40c99ba15be25abad2d514413a088b7">endQuickIndexItem</a> (TextStream &amp;t, const QCString &amp;l)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd84b4b4ce1b0ba6b03bc8d8e84e4c8c">quickLinkVisible</a> (LayoutNavEntry::Kind kind)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd16443590d430ed27faa06521ec03e4">renderQuickLinksAsTree</a> (TextStream &amp;t, const QCString &amp;relPath, LayoutNavEntry *root)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d45214fe7f759039bfd8cc7b37abbf5">renderQuickLinksAsTabs</a> (TextStream &amp;t, const QCString &amp;relPath, LayoutNavEntry *hlEntry, LayoutNavEntry::Kind kind, bool highlightParent, bool highlightSearch)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a891e19196667b0ff8421e74ccf682140">writeDefaultQuickLinks</a> (TextStream &amp;t, HighlightedItem hli, const QCString &amp;file, const QCString &amp;relPath, bool extraTabs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3498eed8e2e90303039a4e2245c319d3">g_header</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a357af50f3d94adbe34df93d23e5bdd44">g_header_file</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a932663422cdebc372564c94056bf0a7e">g_footer_file</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ef18a9e8d540c96bde81562abb60e42">g_footer</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e0395c7f64c90455b817813fdaf3952">g_mathjax_code</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe3baaa3e5fc0455cd443d1722191cf5">g_latex_macro</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr auto</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1748a7403991604b7f600589b77f9937">hex</a> ="0123456789ABCDEF"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static const <a href="/web-doxygen/docs/api/structs/selectionmarkerinfo">SelectionMarkerInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a789823b9d7598023371f64ac0da067da">htmlMarkerInfo</a> = { '&lt;', "&lt;!--BEGIN ",10,"&lt;!--END ",8,"--&gt;",3 }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/files/src/containers-h/#ae9221c0a3b5a2b23e4d7d2cbb8e0d66e">StringUnorderedMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac52a9791b71e7f3ccfb32256329e3594">g_lightMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/files/src/containers-h/#ae9221c0a3b5a2b23e4d7d2cbb8e0d66e">StringUnorderedMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0f7f0e27ca0e60d44a291398f2b0375">g_darkMap</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2a13506b949e3ae461c03411a8ff36b">g_indexLock</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(x)</td>
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

### endQuickIndexItem() {#ac40c99ba15be25abad2d514413a088b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void endQuickIndexItem (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; l)</td>
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


<p>Definition at line <a href="#l02682">2682</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac40c99ba15be25abad2d514413a088b7">2682</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac40c99ba15be25abad2d514413a088b7">endQuickIndexItem</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;l)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2683</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2684</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/span&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2685</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!l.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/a&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2686</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/li&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2687</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>.

Referenced by <a href="#a6d45214fe7f759039bfd8cc7b37abbf5">renderQuickLinksAsTabs</a>.
</div>
</div>

### endQuickIndexList() {#a3ec23d311243e38a80245d1f87084e11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void endQuickIndexList (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
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


<p>Definition at line <a href="#l02655">2655</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3ec23d311243e38a80245d1f87084e11">2655</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3ec23d311243e38a80245d1f87084e11">endQuickIndexList</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2656</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2657</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DISABLE_INDEX))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2658</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2659</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;/ul&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2660</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;/div&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2661</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2662</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2663</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2664</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/ul&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2665</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2666</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>.

Referenced by <a href="#a6d45214fe7f759039bfd8cc7b37abbf5">renderQuickLinksAsTabs</a> and <a href="#acd16443590d430ed27faa06521ec03e4">renderQuickLinksAsTree</a>.
</div>
</div>

### endSectionContent() {#a95a7a96e259bc6213901ea61ae4ca431}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void endSectionContent (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
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


<p>Definition at line <a href="#l01965">1965</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a95a7a96e259bc6213901ea61ae4ca431">1965</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a95a7a96e259bc6213901ea61ae4ca431">endSectionContent</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1966</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1967</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//t &lt;&lt; "&lt;!-- endSectionContent --&gt;";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1968</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1969</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/htmlgenerator/#add957a1f68cc9b99a4c57caa58b33a9b">HtmlGenerator::endCallGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a6e132b23d93e17c4e30b815977a5c865">HtmlGenerator::endClassDiagram</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a603fd2d86e322ea4018747febe523edf">HtmlGenerator::endDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a8bf91873a8da583cfbb47b15806c0ae4">HtmlGenerator::endDotGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aabf59d930dff9f6aa46e3e5674678a35">HtmlGenerator::endGroupCollaboration</a> and <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ac78029628ccb4f7aef7ca0c4cbce0ae3">HtmlGenerator::endInclDepGraph</a>.
</div>
</div>

### endSectionHeader() {#ae2e58dbdf23ed7a1c24f10c4c81ec544}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void endSectionHeader (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
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


<p>Definition at line <a href="#l01921">1921</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae2e58dbdf23ed7a1c24f10c4c81ec544">1921</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae2e58dbdf23ed7a1c24f10c4c81ec544">endSectionHeader</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1922</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1923</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//t &lt;&lt; "&lt;!-- endSectionHeader --&gt;";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1924</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1925</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/htmlgenerator/#add957a1f68cc9b99a4c57caa58b33a9b">HtmlGenerator::endCallGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a6e132b23d93e17c4e30b815977a5c865">HtmlGenerator::endClassDiagram</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a603fd2d86e322ea4018747febe523edf">HtmlGenerator::endDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a8bf91873a8da583cfbb47b15806c0ae4">HtmlGenerator::endDotGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aabf59d930dff9f6aa46e3e5674678a35">HtmlGenerator::endGroupCollaboration</a> and <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ac78029628ccb4f7aef7ca0c4cbce0ae3">HtmlGenerator::endInclDepGraph</a>.
</div>
</div>

### endSectionSummary() {#ae5b4dc7827454fb9508e9a7ee4e663e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void endSectionSummary (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
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


<p>Definition at line <a href="#l01939">1939</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae5b4dc7827454fb9508e9a7ee4e663e8">1939</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae5b4dc7827454fb9508e9a7ee4e663e8">endSectionSummary</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1940</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1941</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//t &lt;&lt; "&lt;!-- endSectionSummary --&gt;";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1942</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> dynamicSections = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(HTML_DYNAMIC_SECTIONS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1943</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (dynamicSections)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1944</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1945</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1946</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1947</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/htmlgenerator/#add957a1f68cc9b99a4c57caa58b33a9b">HtmlGenerator::endCallGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a6e132b23d93e17c4e30b815977a5c865">HtmlGenerator::endClassDiagram</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a603fd2d86e322ea4018747febe523edf">HtmlGenerator::endDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a8bf91873a8da583cfbb47b15806c0ae4">HtmlGenerator::endDotGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aabf59d930dff9f6aa46e3e5674678a35">HtmlGenerator::endGroupCollaboration</a> and <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ac78029628ccb4f7aef7ca0c4cbce0ae3">HtmlGenerator::endInclDepGraph</a>.
</div>
</div>

### fillColorStyleMap() {#a2f990fbb2a5c7d2c30dcf0425e578546}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void fillColorStyleMap (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; definitions, <a href="/web-doxygen/docs/api/files/src/containers-h/#ae9221c0a3b5a2b23e4d7d2cbb8e0d66e">StringUnorderedMap</a> &amp; map)</td>
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


<p>Definition at line <a href="#l00627">627</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2f990fbb2a5c7d2c30dcf0425e578546">627</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2f990fbb2a5c7d2c30dcf0425e578546">fillColorStyleMap</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;definitions,<a href="/web-doxygen/docs/api/files/src/containers-h/#ae9221c0a3b5a2b23e4d7d2cbb8e0d66e">StringUnorderedMap</a> &amp;map)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">628</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">629</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> p=0,i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">630</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((i=definitions.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">,p))!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">631</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">632</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> line = definitions.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(p,i-p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">633</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (line.<a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">startsWith</a>(</span><span class="doxyHighlightStringLiteral">"--"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">634</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">635</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> separator = line.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">636</span><span class="doxyLineContent"><span class="doxyHighlight">      assert(separator!=-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">637</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string key = line.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(separator).<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">638</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> semi = line.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightCharLiteral">';'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">639</span><span class="doxyLineContent"><span class="doxyHighlight">      assert(semi!=-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">640</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string value = line.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(separator+1,semi-separator-1).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">641</span><span class="doxyLineContent"><span class="doxyHighlight">      map.emplace(key,value);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">642</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("var(%s)=%s\n",qPrint(key),qPrint(value));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">643</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">644</span><span class="doxyLineContent"><span class="doxyHighlight">    p=i+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">645</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">646</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">QCString::startsWith</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>.

Referenced by <a href="#ac082e13d5df852dc8a34fd6e84668dff">fillColorStyleMaps</a>.
</div>
</div>

### fillColorStyleMaps() {#ac082e13d5df852dc8a34fd6e84668dff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void fillColorStyleMaps ()</td>
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


<p>Definition at line <a href="#l00648">648</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac082e13d5df852dc8a34fd6e84668dff">648</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac082e13d5df852dc8a34fd6e84668dff">fillColorStyleMaps</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">649</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">650</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/resourcemgr">ResourceMgr</a> &amp;mgr = <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">651</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> colorStyle = <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(HTML_COLORSTYLE);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">652</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (colorStyle==HTML_COLORSTYLE_t::LIGHT)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">653</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">654</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a2f990fbb2a5c7d2c30dcf0425e578546">fillColorStyleMap</a>(<a href="/web-doxygen/docs/api/files/src/util-cpp/#af10f5e35396e550af824e3029bab8dd4">replaceColorMarkers</a>(mgr.<a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">getAsString</a>(</span><span class="doxyHighlightStringLiteral">"lightmode_settings.css"</span><span class="doxyHighlight">)),<a href="#ac52a9791b71e7f3ccfb32256329e3594">g_lightMap</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">655</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">656</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (colorStyle==HTML_COLORSTYLE_t::DARK)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">657</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">658</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a2f990fbb2a5c7d2c30dcf0425e578546">fillColorStyleMap</a>(<a href="/web-doxygen/docs/api/files/src/util-cpp/#af10f5e35396e550af824e3029bab8dd4">replaceColorMarkers</a>(mgr.<a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">getAsString</a>(</span><span class="doxyHighlightStringLiteral">"darkmode_settings.css"</span><span class="doxyHighlight">)),<a href="#ae0f7f0e27ca0e60d44a291398f2b0375">g_darkMap</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">659</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">660</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config&#95;getEnum</a>, <a href="#a2f990fbb2a5c7d2c30dcf0425e578546">fillColorStyleMap</a>, <a href="#ae0f7f0e27ca0e60d44a291398f2b0375">g&#95;darkMap</a>, <a href="#ac52a9791b71e7f3ccfb32256329e3594">g&#95;lightMap</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">ResourceMgr::getAsString</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#af10f5e35396e550af824e3029bab8dd4">replaceColorMarkers</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a0c4c6cd48e43f74bf258851f8b109faf">HtmlGenerator::init</a> and <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9e0dc4a7197da8f8aa16b96d1c958ab2">HtmlGenerator::writeStyleSheetFile</a>.
</div>
</div>

### getConvertLatexMacro() {#a880152a6988921d6248a7640983bef9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString getConvertLatexMacro ()</td>
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
<p>Convert a set of LaTeX commands <span class="doxyComputerOutput">\(re)newcommand</span> to a form readable by MathJax LaTeX syntax:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">\newcommand{\cmd}{replacement}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  or</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">\renewcommand{\cmd}{replacement}</span></span></div>

</div>


<p>MathJax syntax:</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">cmd: "{replacement}"</span></span></div>

</div>


<p>LaTeX syntax:</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">\newcommand{\cmd}[nr]{replacement}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  or</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">\renewcommand{\cmd}[nr]{replacement}</span></span></div>

</div>


<p>MathJax syntax:</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">cmd: ["{replacement}",nr]</span></span></div>

</div>


<p>Definition at line <a href="#l00149">149</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a880152a6988921d6248a7640983bef9e">149</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a880152a6988921d6248a7640983bef9e">getConvertLatexMacro</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> macrofile = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(FORMULA_MACROFILE);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (macrofile.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> s = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a71d0079fa5936a41b6ff2d1ca5eb5480">fileToString</a>(macrofile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">  macrofile = <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a>(macrofile.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()).<a href="/web-doxygen/docs/api/classes/fileinfo/#af69e3949475014dcdbd504d742bdf270">absFilePath</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = s.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/growbuf">GrowBuf</a> out(size);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *data = s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> line = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> cnt = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> nr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i &lt; size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">    nr = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// skip initial white space, but count lines</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i &lt; size &amp;&amp; (data[i] == </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || data[i] == </span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight"> || data[i] == </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i] == </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) line++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">      i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i &gt;= size) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// check for \newcommand or \renewcommand</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i] != </span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(macrofile,line, </span><span class="doxyHighlightStringLiteral">"file contains non valid code, expected '\\' got '{:c}'"</span><span class="doxyHighlight">,data[i]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">    i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>(data+i,</span><span class="doxyHighlightStringLiteral">"newcommand"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">      i += strlen(</span><span class="doxyHighlightStringLiteral">"newcommand"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>(data+i,</span><span class="doxyHighlightStringLiteral">"renewcommand"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">      i += strlen(</span><span class="doxyHighlightStringLiteral">"renewcommand"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(macrofile,line, </span><span class="doxyHighlightStringLiteral">"file contains non valid code, expected 'newcommand' or 'renewcommand'"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// handle {cmd}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i] != </span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(macrofile,line, </span><span class="doxyHighlightStringLiteral">"file contains non valid code, expected '{{' got '{:c}'"</span><span class="doxyHighlight">,data[i]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">    i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i] != </span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(macrofile,line, </span><span class="doxyHighlightStringLiteral">"file contains non valid code, expected '\\' got '{:c}'"</span><span class="doxyHighlight">,data[i]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">    i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// run till }, i.e. cmd</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">    out.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(</span><span class="doxyHighlightStringLiteral">"    "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i &lt; size &amp;&amp; (data[i] != </span><span class="doxyHighlightCharLiteral">'}'</span><span class="doxyHighlight">)) out.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(data[i++]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i &gt;= size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(macrofile,line, </span><span class="doxyHighlightStringLiteral">"file contains non valid code, no closing '}}' for command"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">    out.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">    out.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">    i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i] == </span><span class="doxyHighlightCharLiteral">'['</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// handle [nr]</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// run till ]</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">      out.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(</span><span class="doxyHighlightCharLiteral">'['</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">      i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i &lt; size &amp;&amp; (data[i] != </span><span class="doxyHighlightCharLiteral">']'</span><span class="doxyHighlight">)) nr += data[i++];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i &gt;= size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(macrofile,line, </span><span class="doxyHighlightStringLiteral">"file contains non valid code, no closing ']'"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">      i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i] != </span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(macrofile,line, </span><span class="doxyHighlightStringLiteral">"file contains non valid code, expected '[' or '{{' got '{:c}'"</span><span class="doxyHighlight">,data[i]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// handle {replacement}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// retest as the '[' part might have advanced so we can have a new '{'</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i] != </span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(macrofile,line, </span><span class="doxyHighlightStringLiteral">"file contains non valid code, expected '{{' got '{:c}'"</span><span class="doxyHighlight">,data[i]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">    out.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">    out.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(</span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">    i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// run till }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">    cnt = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i &lt; size &amp;&amp; cnt)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(data[i])</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">          out.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">); </span><span class="doxyHighlightComment">// need to escape it for MathJax js code</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">          out.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">          i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i] == </span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// we have an escaped backslash</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">            out.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">            out.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">            i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i] != </span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">) out.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(data[i++]); </span><span class="doxyHighlightComment">// double quote handled separately</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">          cnt++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">          out.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(data[i++]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'}'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">          cnt--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cnt) out.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(data[i]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">          i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">          out.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">); </span><span class="doxyHighlightComment">// need to escape it for MathJax js code</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">          out.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(data[i++]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">          line++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">          out.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(data[i++]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">          out.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(data[i++]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i &gt; size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(macrofile,line, </span><span class="doxyHighlightStringLiteral">"file contains non valid code, no closing '}}' for replacement"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">    out.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(</span><span class="doxyHighlightCharLiteral">'}'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">    out.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!nr.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">      out.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(</span><span class="doxyHighlightCharLiteral">','</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">      out.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(nr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!nr.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">      out.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(</span><span class="doxyHighlightCharLiteral">']'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">    out.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(</span><span class="doxyHighlightCharLiteral">','</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">    out.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">  out.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> out.<a href="/web-doxygen/docs/api/classes/growbuf/#a88d6408723b8c1a58187f24da81dfd5e">get</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/fileinfo/#af69e3949475014dcdbd504d742bdf270">FileInfo::absFilePath</a>, <a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">GrowBuf::addChar</a>, <a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">GrowBuf::addStr</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a71d0079fa5936a41b6ff2d1ca5eb5480">fileToString</a>, <a href="/web-doxygen/docs/api/classes/growbuf/#a88d6408723b8c1a58187f24da81dfd5e">GrowBuf::get</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal&#95;at</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/htmlgenerator/#af3ae2deb6a25b4b0307edd25ad66896f">HtmlGenerator::getMathJaxMacros</a> and <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a0c4c6cd48e43f74bf258851f8b109faf">HtmlGenerator::init</a>.
</div>
</div>

### getSearchBox() {#aa474343ce62c6bd88db53d9924b223a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString getSearchBox (bool serverSide, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> relPath, bool highlightSearch)</td>
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


<p>Definition at line <a href="#l00309">309</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa474343ce62c6bd88db53d9924b223a0">309</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#aa474343ce62c6bd88db53d9924b223a0">getSearchBox</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> serverSide, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> relPath, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> highlightSearch)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (serverSide)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a589d7504a995d3f00ae97b7684d588eb">writeServerSearchBox</a>(t, relPath, highlightSearch);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae5924fde57d9d6dd319193f24735d748">writeClientSearchBox</a>(t, relPath);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> t.<a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">TextStream::str</a>, <a href="#ae5924fde57d9d6dd319193f24735d748">writeClientSearchBox</a> and <a href="#a589d7504a995d3f00ae97b7684d588eb">writeServerSearchBox</a>.

Referenced by <a href="#ac61bfc9dccd1552c036f2a3aabcd6b2c">substituteHtmlKeywords</a>.
</div>
</div>

### quickLinkVisible() {#acd84b4b4ce1b0ba6b03bc8d8e84e4c8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool quickLinkVisible (<a href="/web-doxygen/docs/api/structs/layoutnaventry/#aef36305dd829f7cde87ca203ae647c7c">LayoutNavEntry::Kind</a> kind)</td>
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


<p>Definition at line <a href="#l02689">2689</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acd84b4b4ce1b0ba6b03bc8d8e84e4c8c">2689</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#acd84b4b4ce1b0ba6b03bc8d8e84e4c8c">quickLinkVisible</a>(<a href="/web-doxygen/docs/api/structs/layoutnaventry/#aef36305dd829f7cde87ca203ae647c7c">LayoutNavEntry::Kind</a> kind)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2690</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2691</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;index = <a href="/web-doxygen/docs/api/classes/index/#ab53e77b97daee95a50bafc51a13cf942">Index::instance</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2692</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> showNamespaces = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(SHOW_NAMESPACES);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2693</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> showFiles = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(SHOW_FILES);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2694</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (kind)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2695</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2696</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::MainPage:           </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2697</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::User:               </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2698</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::UserGroup:          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2699</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::Pages:              </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> index.numIndexedPages()&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2700</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::Topics:             </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> index.numDocumentedGroups()&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2701</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::Modules:            </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> index.numDocumentedModules()&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2702</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::ModuleList:         </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> index.numDocumentedModules()&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2703</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::ModuleMembers:      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> index.numDocumentedModuleMembers(<a href="/web-doxygen/docs/api/namespaces/modulememberhighlight/#ad9dbe63064ec2d350612e68216a18d12ac42c0d575d3dc42c53935916d9a23866">ModuleMemberHighlight::All</a>)&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2704</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::Namespaces:         </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> showNamespaces &amp;&amp; index.numDocumentedNamespaces()&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2705</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::NamespaceList:      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> showNamespaces &amp;&amp; index.numDocumentedNamespaces()&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2706</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::NamespaceMembers:   </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> showNamespaces &amp;&amp; index.numDocumentedNamespaceMembers(<a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca361bea90e10d43996b1baed4e51cbd62">NamespaceMemberHighlight::All</a>)&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2707</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::Concepts:           </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> index.numDocumentedConcepts()&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2708</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::Classes:            </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> index.numAnnotatedClasses()&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2709</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::ClassList:          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> index.numAnnotatedClasses()&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2710</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::ClassIndex:         </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> index.numAnnotatedClasses()&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2711</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::ClassHierarchy:     </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> index.numHierarchyClasses()&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2712</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::ClassMembers:       </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> index.numDocumentedClassMembers(<a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba525098ea62cbd9b913ceea1265eade0d">ClassMemberHighlight::All</a>)&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2713</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::Files:              </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> showFiles &amp;&amp; index.numDocumentedFiles()&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2714</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::FileList:           </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> showFiles &amp;&amp; index.numDocumentedFiles()&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2715</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::FileGlobals:        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> showFiles &amp;&amp; index.numDocumentedFileMembers(<a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a54838102aa091836d1d3f2d8153a775b">FileMemberHighlight::All</a>)&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2716</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::Examples:           </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> !<a href="/web-doxygen/docs/api/classes/doxygen/#a6cfac206c42a62e6e3ba66d5d4e4a471">Doxygen::exampleLinkedMap</a>-&gt;empty();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2717</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::Interfaces:         </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> index.numAnnotatedInterfaces()&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2718</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::InterfaceList:      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> index.numAnnotatedInterfaces()&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2719</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::InterfaceIndex:     </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> index.numAnnotatedInterfaces()&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2720</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::InterfaceHierarchy: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> index.numHierarchyInterfaces()&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2721</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::Structs:            </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> index.numAnnotatedStructs()&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2722</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::StructList:         </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> index.numAnnotatedStructs()&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2723</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::StructIndex:        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> index.numAnnotatedStructs()&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2724</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::Exceptions:         </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> index.numAnnotatedExceptions()&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2725</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::ExceptionList:      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> index.numAnnotatedExceptions()&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2726</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::ExceptionIndex:     </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> index.numAnnotatedExceptions()&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2727</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::ExceptionHierarchy: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> index.numHierarchyExceptions()&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2728</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> LayoutNavEntry::None:             </span><span class="doxyHighlightComment">// should never happen, means not properly initialized</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2729</span><span class="doxyLineContent"><span class="doxyHighlight">      assert(kind != LayoutNavEntry::None);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2730</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2731</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2732</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2733</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/namespaces/classmemberhighlight/#a6048197e058a0592b709901a26fd5beba525098ea62cbd9b913ceea1265eade0d">ClassMemberHighlight::All</a>, <a href="/web-doxygen/docs/api/namespaces/filememberhighlight/#a399c1e21b2b7261ec5f1a5d7ec196550a54838102aa091836d1d3f2d8153a775b">FileMemberHighlight::All</a>, <a href="/web-doxygen/docs/api/namespaces/modulememberhighlight/#ad9dbe63064ec2d350612e68216a18d12ac42c0d575d3dc42c53935916d9a23866">ModuleMemberHighlight::All</a>, <a href="/web-doxygen/docs/api/namespaces/namespacememberhighlight/#a021f146e1894f62e142ba38537ccfb7ca361bea90e10d43996b1baed4e51cbd62">NamespaceMemberHighlight::All</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a6cfac206c42a62e6e3ba66d5d4e4a471">Doxygen::exampleLinkedMap</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/index/#ab53e77b97daee95a50bafc51a13cf942">Index::instance</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a191edf3c31405fc032d0277a553cea99">renderQuickLinksAsJs</a>, <a href="#a6d45214fe7f759039bfd8cc7b37abbf5">renderQuickLinksAsTabs</a> and <a href="#acd16443590d430ed27faa06521ec03e4">renderQuickLinksAsTree</a>.
</div>
</div>

### renderQuickLinksAsTabs() {#a6d45214fe7f759039bfd8cc7b37abbf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void renderQuickLinksAsTabs (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath, <a href="/web-doxygen/docs/api/structs/layoutnaventry">LayoutNavEntry</a> * hlEntry, <a href="/web-doxygen/docs/api/structs/layoutnaventry/#aef36305dd829f7cde87ca203ae647c7c">LayoutNavEntry::Kind</a> kind, bool highlightParent, bool highlightSearch)</td>
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


<p>Definition at line <a href="#l02764">2764</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6d45214fe7f759039bfd8cc7b37abbf5">2764</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6d45214fe7f759039bfd8cc7b37abbf5">renderQuickLinksAsTabs</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;relPath,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2765</span><span class="doxyLineContent"><span class="doxyHighlight">                             <a href="/web-doxygen/docs/api/structs/layoutnaventry">LayoutNavEntry</a> *hlEntry,<a href="/web-doxygen/docs/api/structs/layoutnaventry/#aef36305dd829f7cde87ca203ae647c7c">LayoutNavEntry::Kind</a> kind,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2766</span><span class="doxyLineContent"><span class="doxyHighlight">                             </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> highlightParent,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> highlightSearch)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2767</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2768</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hlEntry-&gt;<a href="/web-doxygen/docs/api/structs/layoutnaventry/#a61a2adf7ec0abb42e49fa07b77eb1690">parent</a>()) </span><span class="doxyHighlightComment">// first draw the tabs for the parent of hlEntry</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2769</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2770</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6d45214fe7f759039bfd8cc7b37abbf5">renderQuickLinksAsTabs</a>(t,relPath,hlEntry-&gt;<a href="/web-doxygen/docs/api/structs/layoutnaventry/#a61a2adf7ec0abb42e49fa07b77eb1690">parent</a>(),kind,highlightParent,highlightSearch);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2771</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2772</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hlEntry-&gt;<a href="/web-doxygen/docs/api/structs/layoutnaventry/#a61a2adf7ec0abb42e49fa07b77eb1690">parent</a>() &amp;&amp; !hlEntry-&gt;<a href="/web-doxygen/docs/api/structs/layoutnaventry/#a61a2adf7ec0abb42e49fa07b77eb1690">parent</a>()-&gt;<a href="/web-doxygen/docs/api/structs/layoutnaventry/#a2111e544a2355f2b2a6592819b21b232">children</a>().empty()) </span><span class="doxyHighlightComment">// draw tabs for row containing hlEntry</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2773</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2774</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> topLevel = hlEntry-&gt;<a href="/web-doxygen/docs/api/structs/layoutnaventry/#a61a2adf7ec0abb42e49fa07b77eb1690">parent</a>()-&gt;<a href="/web-doxygen/docs/api/structs/layoutnaventry/#a61a2adf7ec0abb42e49fa07b77eb1690">parent</a>()==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2775</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> count=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2776</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;entry : hlEntry-&gt;<a href="/web-doxygen/docs/api/structs/layoutnaventry/#a61a2adf7ec0abb42e49fa07b77eb1690">parent</a>()-&gt;<a href="/web-doxygen/docs/api/structs/layoutnaventry/#a2111e544a2355f2b2a6592819b21b232">children</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2777</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2778</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (entry-&gt;visible() &amp;&amp; <a href="#acd84b4b4ce1b0ba6b03bc8d8e84e4c8c">quickLinkVisible</a>(entry-&gt;kind())) count++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2779</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2780</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (count&gt;0) </span><span class="doxyHighlightComment">// at least one item is visible</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2781</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2782</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5cd9e00e6fd36cfbc6a66324910eb618">startQuickIndexList</a>(t,topLevel);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2783</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;entry : hlEntry-&gt;<a href="/web-doxygen/docs/api/structs/layoutnaventry/#a61a2adf7ec0abb42e49fa07b77eb1690">parent</a>()-&gt;<a href="/web-doxygen/docs/api/structs/layoutnaventry/#a2111e544a2355f2b2a6592819b21b232">children</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2784</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2785</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (entry-&gt;visible() &amp;&amp; <a href="#acd84b4b4ce1b0ba6b03bc8d8e84e4c8c">quickLinkVisible</a>(entry-&gt;kind()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2786</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2787</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> url = entry-&gt;url();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2788</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a607223d8bf91989cb35218acc2b95e3c">startQuickIndexItem</a>(t,url,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2789</span><span class="doxyLineContent"><span class="doxyHighlight">              entry.get()==hlEntry  &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2790</span><span class="doxyLineContent"><span class="doxyHighlight">              (!entry-&gt;children().empty() ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2791</span><span class="doxyLineContent"><span class="doxyHighlight">               (entry-&gt;kind()==kind &amp;&amp; !highlightParent)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2792</span><span class="doxyLineContent"><span class="doxyHighlight">              ),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2793</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,relPath);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2794</span><span class="doxyLineContent"><span class="doxyHighlight">          t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-h/#a3eea3729e8c341a13f1976a0ffea49be">fixSpaces</a>(entry-&gt;title());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2795</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#ac40c99ba15be25abad2d514413a088b7">endQuickIndexItem</a>(t,url);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2796</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2797</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2798</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hlEntry-&gt;<a href="/web-doxygen/docs/api/structs/layoutnaventry/#a61a2adf7ec0abb42e49fa07b77eb1690">parent</a>()==<a href="/web-doxygen/docs/api/classes/layoutdocmanager/#a87bc2288833b8769bd03e47c58fbba6a">LayoutDocManager::instance</a>().rootNavEntry()) </span><span class="doxyHighlightComment">// first row is special as it contains the search box</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2799</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2800</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> searchEngine      = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(SEARCHENGINE);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2801</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> serverBasedSearch = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(SERVER_BASED_SEARCH);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2802</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> disableIndex      = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DISABLE_INDEX);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2803</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> generateTreeView  = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_TREEVIEW);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2804</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> fullSidebar       = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(FULL_SIDEBAR);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2805</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// case where DISABLE_INDEX=NO &amp; GENERATE_TREEVIEW=YES &amp; FULL_SIDEBAR=YES has search box in the side panel</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2806</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (searchEngine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2807</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2808</span><span class="doxyLineContent"><span class="doxyHighlight">          t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;li&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2809</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (disableIndex || !generateTreeView || !fullSidebar)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2810</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2811</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!serverBasedSearch) </span><span class="doxyHighlightComment">// pure client side search</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2812</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2813</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="#ae5924fde57d9d6dd319193f24735d748">writeClientSearchBox</a>(t,relPath);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2814</span><span class="doxyLineContent"><span class="doxyHighlight">              t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;/li&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2815</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2816</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// server based search</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2817</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2818</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="#a589d7504a995d3f00ae97b7684d588eb">writeServerSearchBox</a>(t,relPath,highlightSearch);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2819</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!highlightSearch)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2820</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2821</span><span class="doxyLineContent"><span class="doxyHighlight">                t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;/li&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2822</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2823</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2824</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2825</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2826</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2827</span><span class="doxyLineContent"><span class="doxyHighlight">            t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;/li&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2828</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2829</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2830</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!highlightSearch || <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(FULL_SIDEBAR))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2831</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// on the search page the index will be ended by the page itself if the search box is part of the navigation bar</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2832</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2833</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a3ec23d311243e38a80245d1f87084e11">endQuickIndexList</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2834</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2835</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2836</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// normal case for other rows than first one</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2837</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2838</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a3ec23d311243e38a80245d1f87084e11">endQuickIndexList</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2839</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2840</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2841</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2842</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/structs/layoutnaventry/#a2111e544a2355f2b2a6592819b21b232">LayoutNavEntry::children</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="#ac40c99ba15be25abad2d514413a088b7">endQuickIndexItem</a>, <a href="#a3ec23d311243e38a80245d1f87084e11">endQuickIndexList</a>, <a href="/web-doxygen/docs/api/files/src/util-h/#a3eea3729e8c341a13f1976a0ffea49be">fixSpaces</a>, <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#a87bc2288833b8769bd03e47c58fbba6a">LayoutDocManager::instance</a>, <a href="/web-doxygen/docs/api/structs/layoutnaventry/#a61a2adf7ec0abb42e49fa07b77eb1690">LayoutNavEntry::parent</a>, <a href="#acd84b4b4ce1b0ba6b03bc8d8e84e4c8c">quickLinkVisible</a>, <a href="#a6d45214fe7f759039bfd8cc7b37abbf5">renderQuickLinksAsTabs</a>, <a href="#a607223d8bf91989cb35218acc2b95e3c">startQuickIndexItem</a>, <a href="#a5cd9e00e6fd36cfbc6a66324910eb618">startQuickIndexList</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="#ae5924fde57d9d6dd319193f24735d748">writeClientSearchBox</a> and <a href="#a589d7504a995d3f00ae97b7684d588eb">writeServerSearchBox</a>.

Referenced by <a href="#a6d45214fe7f759039bfd8cc7b37abbf5">renderQuickLinksAsTabs</a> and <a href="#a891e19196667b0ff8421e74ccf682140">writeDefaultQuickLinks</a>.
</div>
</div>

### renderQuickLinksAsTree() {#acd16443590d430ed27faa06521ec03e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void renderQuickLinksAsTree (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath, <a href="/web-doxygen/docs/api/structs/layoutnaventry">LayoutNavEntry</a> * root)</td>
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


<p>Definition at line <a href="#l02735">2735</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acd16443590d430ed27faa06521ec03e4">2735</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acd16443590d430ed27faa06521ec03e4">renderQuickLinksAsTree</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;relPath,<a href="/web-doxygen/docs/api/structs/layoutnaventry">LayoutNavEntry</a> *root)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2736</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2737</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2738</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> count=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2739</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;entry : root-&gt;<a href="/web-doxygen/docs/api/structs/layoutnaventry/#a2111e544a2355f2b2a6592819b21b232">children</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2740</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2741</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (entry-&gt;visible() &amp;&amp; <a href="#acd84b4b4ce1b0ba6b03bc8d8e84e4c8c">quickLinkVisible</a>(entry-&gt;kind())) count++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2742</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2743</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (count&gt;0) </span><span class="doxyHighlightComment">// at least one item is visible</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2744</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2745</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5cd9e00e6fd36cfbc6a66324910eb618">startQuickIndexList</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2746</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;entry : root-&gt;<a href="/web-doxygen/docs/api/structs/layoutnaventry/#a2111e544a2355f2b2a6592819b21b232">children</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2747</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2748</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (entry-&gt;visible() &amp;&amp; <a href="#acd84b4b4ce1b0ba6b03bc8d8e84e4c8c">quickLinkVisible</a>(entry-&gt;kind()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2749</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2750</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> url = entry-&gt;url();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2751</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;li&gt;&lt;a href=\""</span><span class="doxyHighlight"> &lt;&lt; relPath &lt;&lt; url &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;&lt;span&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2752</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-h/#a3eea3729e8c341a13f1976a0ffea49be">fixSpaces</a>(entry-&gt;title());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2753</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/span&gt;&lt;/a&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2754</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// recursive into child list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2755</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#acd16443590d430ed27faa06521ec03e4">renderQuickLinksAsTree</a>(t,relPath,entry.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2756</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/li&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2757</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2758</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2759</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a3ec23d311243e38a80245d1f87084e11">endQuickIndexList</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2760</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2761</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/structs/layoutnaventry/#a2111e544a2355f2b2a6592819b21b232">LayoutNavEntry::children</a>, <a href="#a3ec23d311243e38a80245d1f87084e11">endQuickIndexList</a>, <a href="/web-doxygen/docs/api/files/src/util-h/#a3eea3729e8c341a13f1976a0ffea49be">fixSpaces</a>, <a href="#acd84b4b4ce1b0ba6b03bc8d8e84e4c8c">quickLinkVisible</a>, <a href="#acd16443590d430ed27faa06521ec03e4">renderQuickLinksAsTree</a> and <a href="#a5cd9e00e6fd36cfbc6a66324910eb618">startQuickIndexList</a>.

Referenced by <a href="#acd16443590d430ed27faa06521ec03e4">renderQuickLinksAsTree</a> and <a href="#a891e19196667b0ff8421e74ccf682140">writeDefaultQuickLinks</a>.
</div>
</div>

### replaceVariables() {#a2f3978430bdfefcb92e25f2da8854f45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString replaceVariables (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; input)</td>
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


<p>Definition at line <a href="#l00662">662</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2f3978430bdfefcb92e25f2da8854f45">662</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a2f3978430bdfefcb92e25f2da8854f45">replaceVariables</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;input)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">663</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">664</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> doReplacements = [&amp;input](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/containers-h/#ae9221c0a3b5a2b23e4d7d2cbb8e0d66e">StringUnorderedMap</a> &amp;mapping) -&gt; <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">665</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">666</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/growbuf">GrowBuf</a> output;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> p=0,i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">668</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((i=input.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"var("</span><span class="doxyHighlight">,p))!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">670</span><span class="doxyLineContent"><span class="doxyHighlight">      output.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(input.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()+p,i-p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">671</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> j=input.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">")"</span><span class="doxyHighlight">,i+4);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">672</span><span class="doxyLineContent"><span class="doxyHighlight">      assert(j!=-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">673</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = mapping.find(input.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(i+4,j-i-4).<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()); </span><span class="doxyHighlightComment">// find variable</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">674</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it==mapping.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">675</span><span class="doxyLineContent"><span class="doxyHighlight">      {                            </span><span class="doxyHighlightComment">// should be found</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">676</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"failed to find value variable {}. It is not longer defined in doxygen.css\n"</span><span class="doxyHighlight">,input.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(i+4,j-i-4));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">677</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">678</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">679</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">680</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("replace '%s' by '%s'\n",qPrint(input.mid(i+4,j-i-4)),qPrint(it-&gt;second));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">681</span><span class="doxyLineContent"><span class="doxyHighlight">        output.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(it-&gt;second);                          </span><span class="doxyHighlightComment">// add it value</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">682</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">683</span><span class="doxyLineContent"><span class="doxyHighlight">      p=j+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">684</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">685</span><span class="doxyLineContent"><span class="doxyHighlight">    output.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(input.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()+p,input.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">686</span><span class="doxyLineContent"><span class="doxyHighlight">    output.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">687</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> output.<a href="/web-doxygen/docs/api/classes/growbuf/#a88d6408723b8c1a58187f24da81dfd5e">get</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">688</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">689</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">690</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> colorStyle = <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(HTML_COLORSTYLE);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">691</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (colorStyle==HTML_COLORSTYLE_t::LIGHT)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">692</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">693</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> doReplacements(<a href="#ac52a9791b71e7f3ccfb32256329e3594">g_lightMap</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">694</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (colorStyle==HTML_COLORSTYLE_t::DARK)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">696</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">697</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> doReplacements(<a href="#ae0f7f0e27ca0e60d44a291398f2b0375">g_darkMap</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">698</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">699</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">700</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">701</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> input;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">702</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">703</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">GrowBuf::addChar</a>, <a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">GrowBuf::addStr</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config&#95;getEnum</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="#ae0f7f0e27ca0e60d44a291398f2b0375">g&#95;darkMap</a>, <a href="#ac52a9791b71e7f3ccfb32256329e3594">g&#95;lightMap</a>, <a href="/web-doxygen/docs/api/classes/growbuf/#a88d6408723b8c1a58187f24da81dfd5e">GrowBuf::get</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a3874b75d86f996ce7d7ca32bea785c56">HtmlGenerator::getNavTreeCss</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a0c4c6cd48e43f74bf258851f8b109faf">HtmlGenerator::init</a>, <a href="#ac7339dc7ff25bcb7a9fbea1d671a16da">writeDefaultStyleSheet</a> and <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9114c68d96141e80c08efdd497fc010e">HtmlGenerator::writeSearchData</a>.
</div>
</div>

### startQuickIndexItem() {#a607223d8bf91989cb35218acc2b95e3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void startQuickIndexItem (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; l, bool hl, bool, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath)</td>
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


<p>Definition at line <a href="#l02668">2668</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a607223d8bf91989cb35218acc2b95e3c">2668</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a607223d8bf91989cb35218acc2b95e3c">startQuickIndexItem</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;l,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2669</span><span class="doxyLineContent"><span class="doxyHighlight">                                </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hl,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*compact*/</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2670</span><span class="doxyLineContent"><span class="doxyHighlight">                                </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;relPath)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2671</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2672</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;li"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2673</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2674</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2675</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">" class=\"current\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2676</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2677</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2678</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!l.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;a href=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3a775021310e25718452bfe250b2f999">correctURL</a>(l,relPath) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2679</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;span&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2680</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3a775021310e25718452bfe250b2f999">correctURL</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>.

Referenced by <a href="#a6d45214fe7f759039bfd8cc7b37abbf5">renderQuickLinksAsTabs</a>.
</div>
</div>

### startQuickIndexList() {#a5cd9e00e6fd36cfbc6a66324910eb618}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void startQuickIndexList (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, bool topLevel=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</td>
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


<p>Definition at line <a href="#l02635">2635</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5cd9e00e6fd36cfbc6a66324910eb618">2635</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5cd9e00e6fd36cfbc6a66324910eb618">startQuickIndexList</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> topLevel=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2636</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2637</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DISABLE_INDEX))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2638</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2639</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (topLevel)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2640</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2641</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;div id=\"navrow1\" class=\"tabs\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2642</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2643</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2644</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2645</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;div id=\"navrow2\" class=\"tabs2\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2646</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2647</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;ul class=\"tablist\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2648</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2649</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2650</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2651</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;ul&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2652</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2653</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="#a6d45214fe7f759039bfd8cc7b37abbf5">renderQuickLinksAsTabs</a> and <a href="#acd16443590d430ed27faa06521ec03e4">renderQuickLinksAsTree</a>.
</div>
</div>

### startSectionContent() {#a34e1ea8704b315e66086811539bd1a5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void startSectionContent (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, int sectionCount)</td>
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


<p>Definition at line <a href="#l01949">1949</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a34e1ea8704b315e66086811539bd1a5f">1949</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a34e1ea8704b315e66086811539bd1a5f">startSectionContent</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> sectionCount)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1950</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1951</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//t &lt;&lt; "&lt;!-- startSectionContent --&gt;";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1952</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> dynamicSections = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(HTML_DYNAMIC_SECTIONS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1953</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (dynamicSections)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1954</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1955</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div id=\"dynsection-"</span><span class="doxyHighlight"> &lt;&lt; sectionCount &lt;&lt; </span><span class="doxyHighlightStringLiteral">"-content\" "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1956</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"class=\"dyncontent\" "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1957</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"style=\"display:none;\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1958</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1959</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1960</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1961</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"dyncontent\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1962</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1963</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/htmlgenerator/#add957a1f68cc9b99a4c57caa58b33a9b">HtmlGenerator::endCallGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a6e132b23d93e17c4e30b815977a5c865">HtmlGenerator::endClassDiagram</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a603fd2d86e322ea4018747febe523edf">HtmlGenerator::endDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a8bf91873a8da583cfbb47b15806c0ae4">HtmlGenerator::endDotGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aabf59d930dff9f6aa46e3e5674678a35">HtmlGenerator::endGroupCollaboration</a> and <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ac78029628ccb4f7aef7ca0c4cbce0ae3">HtmlGenerator::endInclDepGraph</a>.
</div>
</div>

### startSectionHeader() {#ac5f89137286ceb01d9c5a1a14a36d8e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void startSectionHeader (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath, int sectionCount)</td>
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


<p>Definition at line <a href="#l01902">1902</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac5f89137286ceb01d9c5a1a14a36d8e1">1902</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac5f89137286ceb01d9c5a1a14a36d8e1">startSectionHeader</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1903</span><span class="doxyLineContent"><span class="doxyHighlight">                               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;relPath,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> sectionCount)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1904</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1905</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//t &lt;&lt; "&lt;!-- startSectionHeader --&gt;";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1906</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> dynamicSections = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(HTML_DYNAMIC_SECTIONS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1907</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (dynamicSections)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1908</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1909</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div id=\"dynsection-"</span><span class="doxyHighlight"> &lt;&lt; sectionCount &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1910</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"onclick=\"return dynsection.toggleVisibility(this)\" "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1911</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"class=\"dynheader closed\" "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1912</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"style=\"cursor:pointer;\"&gt;"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1913</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"&lt;span class=\"dynarrow\"&gt;&lt;span class=\"arrowhead closed\"&gt;&lt;/span&gt;&lt;/span&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1914</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1915</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1916</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1917</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"dynheader\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1918</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1919</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a34d21b07f7218dcc1161ed797dc8a74a">HtmlGenerator::startCallGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a005f1a46f9808e8a719ba756407259ec">HtmlGenerator::startClassDiagram</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a41dc42e70634afb2a68fd1c45dd16f91">HtmlGenerator::startDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a4cacd7e83fff3a670a66073686c882a8">HtmlGenerator::startDotGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a6d892ee256e9a34db8cf761569bb2c9c">HtmlGenerator::startGroupCollaboration</a> and <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a20449975cf6595d7c2cb353f1c26534f">HtmlGenerator::startInclDepGraph</a>.
</div>
</div>

### startSectionSummary() {#a5de92e3118bc2a62d1f43598d1cb2028}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void startSectionSummary (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, int sectionCount)</td>
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


<p>Definition at line <a href="#l01927">1927</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5de92e3118bc2a62d1f43598d1cb2028">1927</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5de92e3118bc2a62d1f43598d1cb2028">startSectionSummary</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> sectionCount)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1928</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1929</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//t &lt;&lt; "&lt;!-- startSectionSummary --&gt;";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1930</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> dynamicSections = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(HTML_DYNAMIC_SECTIONS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1931</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (dynamicSections)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1932</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1933</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div id=\"dynsection-"</span><span class="doxyHighlight"> &lt;&lt; sectionCount &lt;&lt; </span><span class="doxyHighlightStringLiteral">"-summary\" "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1934</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"class=\"dynsummary\" "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1935</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"style=\"display:block;\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1936</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1937</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/htmlgenerator/#add957a1f68cc9b99a4c57caa58b33a9b">HtmlGenerator::endCallGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a6e132b23d93e17c4e30b815977a5c865">HtmlGenerator::endClassDiagram</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a603fd2d86e322ea4018747febe523edf">HtmlGenerator::endDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a8bf91873a8da583cfbb47b15806c0ae4">HtmlGenerator::endDotGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aabf59d930dff9f6aa46e3e5674678a35">HtmlGenerator::endGroupCollaboration</a> and <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ac78029628ccb4f7aef7ca0c4cbce0ae3">HtmlGenerator::endInclDepGraph</a>.
</div>
</div>

### substituteHtmlKeywords() {#ac61bfc9dccd1552c036f2a3aabcd6b2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString substituteHtmlKeywords (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; navPath=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</td>
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


<p>Definition at line <a href="#l00323">323</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac61bfc9dccd1552c036f2a3aabcd6b2c">323</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ac61bfc9dccd1552c036f2a3aabcd6b2c">substituteHtmlKeywords</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;relPath,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;navPath=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Build CSS/JavaScript tags depending on treeview, search engine settings</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> cssFile;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> generatedBy;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> treeViewCssJs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> searchCssJs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> searchBox;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> mathJaxJs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> extraCssText;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> projectName = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(PROJECT_NAME);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> treeView = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_TREEVIEW);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> searchEngine = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(SEARCHENGINE);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> serverBasedSearch = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(SERVER_BASED_SEARCH);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> mathJax = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(USE_MATHJAX);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> mathJaxFormat = <a href="/web-doxygen/docs/api/files/src/config-h/#a251399cde30dd4c356bbd5634c6eb472">Config_getEnumAsString</a>(MATHJAX_FORMAT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> disableIndex = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DISABLE_INDEX);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasProjectName = !projectName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasProjectNumber = !<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(PROJECT_NUMBER).isEmpty();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">347</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasProjectBrief = !<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(PROJECT_BRIEF).isEmpty();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasProjectLogo = !<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(PROJECT_LOGO).isEmpty();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasProjectIcon = !<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(PROJECT_ICON).isEmpty();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasFullSideBar = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(FULL_SIDEBAR) &amp;&amp; </span><span class="doxyHighlightComment">/*disableIndex &amp;&amp;*/</span><span class="doxyHighlight"> treeView;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">351</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasCopyClipboard = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(HTML_COPY_CLIPBOARD);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasCookie = treeView || searchEngine || <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(HTML_COLORSTYLE)==HTML_COLORSTYLE_t::TOGGLE;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> titleArea = (hasProjectName || hasProjectBrief || hasProjectLogo || (disableIndex &amp;&amp; searchEngine));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">355</span><span class="doxyLineContent"><span class="doxyHighlight">  cssFile = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_STYLESHEET);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">356</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cssFile.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">    cssFile = </span><span class="doxyHighlightStringLiteral">"doxygen.css"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">361</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!cssFile.<a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">startsWith</a>(</span><span class="doxyHighlightStringLiteral">"http:"</span><span class="doxyHighlight">) &amp;&amp; !cssFile.<a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">startsWith</a>(</span><span class="doxyHighlightStringLiteral">"https:"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> cssfi(cssFile.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cssfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">366</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">367</span><span class="doxyLineContent"><span class="doxyHighlight">        cssFile = cssfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">fileName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">        cssFile = </span><span class="doxyHighlightStringLiteral">"doxygen.css"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">  extraCssText = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> &amp;extraCssFile = <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>(HTML_EXTRA_STYLESHEET);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;fileName : extraCssFile)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!fileName.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> htmlStyleSheet = fileName.c_str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (htmlStyleSheet.<a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">startsWith</a>(</span><span class="doxyHighlightStringLiteral">"http:"</span><span class="doxyHighlight">) || htmlStyleSheet.<a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">startsWith</a>(</span><span class="doxyHighlightStringLiteral">"https:"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">        extraCssText += </span><span class="doxyHighlightStringLiteral">"&lt;link href=\""</span><span class="doxyHighlight">+htmlStyleSheet+</span><span class="doxyHighlightStringLiteral">"\" rel=\"stylesheet\" type=\"text/css\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fi(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">          extraCssText += </span><span class="doxyHighlightStringLiteral">"&lt;link href=\"$relpath^"</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(fileName.c_str())+</span><span class="doxyHighlightStringLiteral">"\" rel=\"stylesheet\" type=\"text/css\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(TIMESTAMP))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> TIMESTAMP_t::NO:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlight">      generatedBy = <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trGeneratedBy();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">402</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">      generatedBy = <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trGeneratedAt(</span><span class="doxyHighlightStringLiteral">"&lt;span class=\"timestamp\"&gt;&lt;/span&gt;"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">405</span><span class="doxyLineContent"><span class="doxyHighlight">                    <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>(<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(PROJECT_NAME)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">406</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">407</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">408</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (treeView)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">409</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span><span class="doxyLineContent"><span class="doxyHighlight">    treeViewCssJs = </span><span class="doxyHighlightStringLiteral">"&lt;link href=\"$relpath^navtree.css\" rel=\"stylesheet\" type=\"text/css\"/&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">411</span><span class="doxyLineContent"><span class="doxyHighlight">                    </span><span class="doxyHighlightStringLiteral">"&lt;script type=\"text/javascript\" src=\"$relpath^navtreedata.js\"&gt;&lt;/script&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">412</span><span class="doxyLineContent"><span class="doxyHighlight">                    </span><span class="doxyHighlightStringLiteral">"&lt;script type=\"text/javascript\" src=\"$relpath^navtree.js\"&gt;&lt;/script&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">413</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">414</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">415</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (searchEngine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">417</span><span class="doxyLineContent"><span class="doxyHighlight">    searchCssJs = </span><span class="doxyHighlightStringLiteral">"&lt;link href=\"$relpath^search/search.css\" rel=\"stylesheet\" type=\"text/css\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">418</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!serverBasedSearch)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">419</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span><span class="doxyLineContent"><span class="doxyHighlight">      searchCssJs += </span><span class="doxyHighlightStringLiteral">"&lt;script type=\"text/javascript\" src=\"$relpath^search/searchdata.js\"&gt;&lt;/script&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">421</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">422</span><span class="doxyLineContent"><span class="doxyHighlight">    searchCssJs += </span><span class="doxyHighlightStringLiteral">"&lt;script type=\"text/javascript\" src=\"$relpath^search/search.js\"&gt;&lt;/script&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">423</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">424</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!serverBasedSearch)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">425</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">426</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (disableIndex || !<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(HTML_DYNAMIC_MENUS) || <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(FULL_SIDEBAR))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">427</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">428</span><span class="doxyLineContent"><span class="doxyHighlight">        searchCssJs += </span><span class="doxyHighlightStringLiteral">"&lt;script type=\"text/javascript\"&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">429</span><span class="doxyLineContent"><span class="doxyHighlight">                                        </span><span class="doxyHighlightStringLiteral">"  $(function() { init_search(); });\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">430</span><span class="doxyLineContent"><span class="doxyHighlight">                                        </span><span class="doxyHighlightStringLiteral">"&lt;/script&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">431</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">432</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">433</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">434</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">435</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (disableIndex || !<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(HTML_DYNAMIC_MENUS))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span><span class="doxyLineContent"><span class="doxyHighlight">        searchCssJs += </span><span class="doxyHighlightStringLiteral">"&lt;script type=\"text/javascript\"&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span><span class="doxyLineContent"><span class="doxyHighlight">                                        </span><span class="doxyHighlightStringLiteral">"  $(function() {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">439</span><span class="doxyLineContent"><span class="doxyHighlight">                                        </span><span class="doxyHighlightStringLiteral">"    if ($('.searchresults').length &gt; 0) { searchBox.DOMSearchField().focus(); }\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">                                        </span><span class="doxyHighlightStringLiteral">"  });\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">441</span><span class="doxyLineContent"><span class="doxyHighlight">                                        </span><span class="doxyHighlightStringLiteral">"&lt;/script&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">442</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// OPENSEARCH_PROVIDER {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">      searchCssJs += </span><span class="doxyHighlightStringLiteral">"&lt;link rel=\"search\" href=\""</span><span class="doxyHighlight"> + relPath +</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">446</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightStringLiteral">"search_opensearch.php?v=opensearch.xml\" "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">447</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightStringLiteral">"type=\"application/opensearchdescription+xml\" title=\""</span><span class="doxyHighlight"> +</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span><span class="doxyLineContent"><span class="doxyHighlight">                     (hasProjectName ? projectName : <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"Doxygen"</span><span class="doxyHighlight">)) +</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightStringLiteral">"\"/&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// OPENSEARCH_PROVIDER }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">    searchBox = <a href="#aa474343ce62c6bd88db53d9924b223a0">getSearchBox</a>(serverBasedSearch, relPath, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mathJax)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">457</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> mathJaxVersion = <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(MATHJAX_VERSION);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> path = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(MATHJAX_RELPATH);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (path.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() || path.<a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">startsWith</a>(</span><span class="doxyHighlightStringLiteral">".."</span><span class="doxyHighlight">)) </span><span class="doxyHighlightComment">// relative path</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">      path.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(relPath);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (mathJaxVersion)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> MATHJAX_VERSION_t::MathJax_3:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">          mathJaxJs += </span><span class="doxyHighlightComment">// "&lt;script src=\"https://polyfill.io/v3/polyfill.min.js?features=es6\"&gt;&lt;/script&gt;\n" // needed for IE11 only, see #10354</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightStringLiteral">"&lt;script type=\"text/javascript\"&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightStringLiteral">"window.MathJax = {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightStringLiteral">"  options: {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightStringLiteral">"    ignoreHtmlClass: 'tex2jax_ignore',\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightStringLiteral">"    processHtmlClass: 'tex2jax_process'\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightStringLiteral">"  }"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> &amp;mathJaxExtensions = <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>(MATHJAX_EXTENSIONS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!mathJaxExtensions.empty() || !<a href="#abe3baaa3e5fc0455cd443d1722191cf5">g_latex_macro</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span><span class="doxyLineContent"><span class="doxyHighlight">         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">           mathJaxJs+= </span><span class="doxyHighlightStringLiteral">",\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">479</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!mathJaxExtensions.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span><span class="doxyLineContent"><span class="doxyHighlight">           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">             </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> first = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">             mathJaxJs+= </span><span class="doxyHighlightStringLiteral">"  loader: {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightStringLiteral">"    load: ["</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">             </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;s : mathJaxExtensions)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">             {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!first) mathJaxJs+= </span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">               mathJaxJs+= </span><span class="doxyHighlightStringLiteral">"'[tex]/"</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(s.c_str())+</span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">               first = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">             }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">             mathJaxJs+= </span><span class="doxyHighlightStringLiteral">"]\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightStringLiteral">"  },\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">           }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">           mathJaxJs+= </span><span class="doxyHighlightStringLiteral">"  tex: {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightStringLiteral">"    macros: {"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#abe3baaa3e5fc0455cd443d1722191cf5">g_latex_macro</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span><span class="doxyLineContent"><span class="doxyHighlight">             mathJaxJs += <a href="#abe3baaa3e5fc0455cd443d1722191cf5">g_latex_macro</a>+</span><span class="doxyHighlightStringLiteral">"    "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">           }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlight">           mathJaxJs+=</span><span class="doxyHighlightStringLiteral">"},\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightStringLiteral">"    packages: ['base','configmacros'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#abe3baaa3e5fc0455cd443d1722191cf5">g_latex_macro</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">             mathJaxJs+= </span><span class="doxyHighlightStringLiteral">",'newcommand'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">           }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;s : mathJaxExtensions)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">             mathJaxJs+= </span><span class="doxyHighlightStringLiteral">",'"</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(s.c_str())+</span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">           }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span><span class="doxyLineContent"><span class="doxyHighlight">           mathJaxJs += </span><span class="doxyHighlightStringLiteral">"]\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightStringLiteral">"  }\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlight">         }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">513</span><span class="doxyLineContent"><span class="doxyHighlight">         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">514</span><span class="doxyLineContent"><span class="doxyHighlight">           mathJaxJs += </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">515</span><span class="doxyLineContent"><span class="doxyHighlight">         }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">516</span><span class="doxyLineContent"><span class="doxyHighlight">         mathJaxJs += </span><span class="doxyHighlightStringLiteral">"};\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">517</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightComment">// MATHJAX_CODEFILE</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">518</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a4e0395c7f64c90455b817813fdaf3952">g_mathjax_code</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span><span class="doxyLineContent"><span class="doxyHighlight">         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span><span class="doxyLineContent"><span class="doxyHighlight">           mathJaxJs += <a href="#a4e0395c7f64c90455b817813fdaf3952">g_mathjax_code</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">521</span><span class="doxyLineContent"><span class="doxyHighlight">           mathJaxJs += </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">         }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">         mathJaxJs += </span><span class="doxyHighlightStringLiteral">"&lt;/script&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">         mathJaxJs += </span><span class="doxyHighlightStringLiteral">"&lt;script type=\"text/javascript\" id=\"MathJax-script\" async=\"async\" src=\""</span><span class="doxyHighlight"> +</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">525</span><span class="doxyLineContent"><span class="doxyHighlight">                      path + </span><span class="doxyHighlightStringLiteral">"es5/tex-"</span><span class="doxyHighlight"> + mathJaxFormat.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>() + </span><span class="doxyHighlightStringLiteral">".js\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">526</span><span class="doxyLineContent"><span class="doxyHighlight">         mathJaxJs+=</span><span class="doxyHighlightStringLiteral">"&lt;/script&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">527</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">528</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">529</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> MATHJAX_VERSION_t::MathJax_2:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">530</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">531</span><span class="doxyLineContent"><span class="doxyHighlight">          mathJaxJs = </span><span class="doxyHighlightStringLiteral">"&lt;script type=\"text/x-mathjax-config\"&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">532</span><span class="doxyLineContent"><span class="doxyHighlight">                      </span><span class="doxyHighlightStringLiteral">"MathJax.Hub.Config({\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">533</span><span class="doxyLineContent"><span class="doxyHighlight">                      </span><span class="doxyHighlightStringLiteral">"  extensions: [\"tex2jax.js\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">534</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> &amp;mathJaxExtensions = <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>(MATHJAX_EXTENSIONS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">535</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;s : mathJaxExtensions)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">536</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">537</span><span class="doxyLineContent"><span class="doxyHighlight">            mathJaxJs+= </span><span class="doxyHighlightStringLiteral">", \""</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(s.c_str())+</span><span class="doxyHighlightStringLiteral">".js\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">538</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">539</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mathJaxFormat.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">540</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">541</span><span class="doxyLineContent"><span class="doxyHighlight">            mathJaxFormat = </span><span class="doxyHighlightStringLiteral">"HTML-CSS"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">542</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">543</span><span class="doxyLineContent"><span class="doxyHighlight">          mathJaxJs += </span><span class="doxyHighlightStringLiteral">"],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">544</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightStringLiteral">"  jax: [\"input/TeX\",\"output/"</span><span class="doxyHighlight">+mathJaxFormat+</span><span class="doxyHighlightStringLiteral">"\"],\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">545</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#abe3baaa3e5fc0455cd443d1722191cf5">g_latex_macro</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">546</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">547</span><span class="doxyLineContent"><span class="doxyHighlight">            mathJaxJs += </span><span class="doxyHighlightStringLiteral">"   TeX: { Macros: {\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">548</span><span class="doxyLineContent"><span class="doxyHighlight">            mathJaxJs += <a href="#abe3baaa3e5fc0455cd443d1722191cf5">g_latex_macro</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">549</span><span class="doxyLineContent"><span class="doxyHighlight">            mathJaxJs += </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">550</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightStringLiteral">"  } }\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">551</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">552</span><span class="doxyLineContent"><span class="doxyHighlight">          mathJaxJs +=   </span><span class="doxyHighlightStringLiteral">"});\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">553</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a4e0395c7f64c90455b817813fdaf3952">g_mathjax_code</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">554</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">555</span><span class="doxyLineContent"><span class="doxyHighlight">            mathJaxJs += <a href="#a4e0395c7f64c90455b817813fdaf3952">g_mathjax_code</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">556</span><span class="doxyLineContent"><span class="doxyHighlight">            mathJaxJs += </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">557</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">558</span><span class="doxyLineContent"><span class="doxyHighlight">          mathJaxJs += </span><span class="doxyHighlightStringLiteral">"&lt;/script&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">559</span><span class="doxyLineContent"><span class="doxyHighlight">          mathJaxJs += </span><span class="doxyHighlightStringLiteral">"&lt;script type=\"text/javascript\" async=\"async\" src=\""</span><span class="doxyHighlight"> + path + </span><span class="doxyHighlightStringLiteral">"MathJax.js\"&gt;&lt;/script&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">560</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">561</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">563</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> darkModeJs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">566</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(HTML_COLORSTYLE)==HTML_COLORSTYLE_t::TOGGLE)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">567</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">568</span><span class="doxyLineContent"><span class="doxyHighlight">    darkModeJs=</span><span class="doxyHighlightStringLiteral">"&lt;script type=\"text/javascript\" src=\"$relpath^darkmode_toggle.js\"&gt;&lt;/script&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">569</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">570</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">571</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hasCookie) </span><span class="doxyHighlightComment">// extend the $treeview tag to avoid breaking old files used with HTML_HEADER</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">572</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">    treeViewCssJs+=</span><span class="doxyHighlightStringLiteral">"&lt;script type=\"text/javascript\" src=\"$relpath^cookie.js\"&gt;&lt;/script&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">575</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">576</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// first substitute generic keywords</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">577</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5c85e13964c82e9aa4cef183a767651e">substituteKeywords</a>(file,str,title,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">578</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>(<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(PROJECT_NAME)),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>(<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(PROJECT_NUMBER)),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>(<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(PROJECT_BRIEF)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// then do the HTML specific keywords</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">  result = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5c85e13964c82e9aa4cef183a767651e">substituteKeywords</a>(file,result,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">584</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// keyword           value getter</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">586</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"$navpath"</span><span class="doxyHighlight">,        [&amp;]() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> navPath;        } },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">587</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"$stylesheet"</span><span class="doxyHighlight">,     [&amp;]() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> cssFile;        } },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"$treeview"</span><span class="doxyHighlight">,       [&amp;]() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> treeViewCssJs;  } },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">589</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"$searchbox"</span><span class="doxyHighlight">,      [&amp;]() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> searchBox;      } },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">590</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"$search"</span><span class="doxyHighlight">,         [&amp;]() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> searchCssJs;    } },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">591</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"$mathjax"</span><span class="doxyHighlight">,        [&amp;]() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mathJaxJs;      } },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">592</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"$darkmode"</span><span class="doxyHighlight">,       [&amp;]() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> darkModeJs;     } },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">593</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"$generatedby"</span><span class="doxyHighlight">,    [&amp;]() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> generatedBy;    } },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"$extrastylesheet"</span><span class="doxyHighlight">,[&amp;]() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> extraCssText;   } },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"$relpath$"</span><span class="doxyHighlight">,       [&amp;]() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> relPath;        } } </span><span class="doxyHighlightComment">//&lt;-- obsolete: for backwards compatibility only</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">  });</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlight">  result = <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(result,</span><span class="doxyHighlightStringLiteral">"$relpath^"</span><span class="doxyHighlight">,relPath); </span><span class="doxyHighlightComment">//&lt;-- must be done after the previous substitutions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// remove conditional blocks</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">601</span><span class="doxyLineContent"><span class="doxyHighlight">  result = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a558bfa6d487cad0977c6d706cd638a6c">selectBlocks</a>(result,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">602</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">603</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// keyword,            is enabled</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">604</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"FULL_SIDEBAR"</span><span class="doxyHighlight">,      hasFullSideBar   },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"DISABLE_INDEX"</span><span class="doxyHighlight">,     disableIndex     },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"GENERATE_TREEVIEW"</span><span class="doxyHighlight">, treeView         },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"SEARCHENGINE"</span><span class="doxyHighlight">,      searchEngine     },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"TITLEAREA"</span><span class="doxyHighlight">,         titleArea        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"PROJECT_NAME"</span><span class="doxyHighlight">,      hasProjectName   },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"PROJECT_NUMBER"</span><span class="doxyHighlight">,    hasProjectNumber },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"PROJECT_BRIEF"</span><span class="doxyHighlight">,     hasProjectBrief  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"PROJECT_LOGO"</span><span class="doxyHighlight">,      hasProjectLogo   },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">613</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"PROJECT_ICON"</span><span class="doxyHighlight">,      hasProjectIcon   },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">614</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"COPY_CLIPBOARD"</span><span class="doxyHighlight">,    hasCopyClipboard },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">615</span><span class="doxyLineContent"><span class="doxyHighlight">  },<a href="#a789823b9d7598023371f64ac0da067da">htmlMarkerInfo</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">616</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">  result = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3f2329035cfde039380d267efff68c76">removeEmptyLines</a>(result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">618</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">619</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">620</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config&#95;getEnum</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a251399cde30dd4c356bbd5634c6eb472">Config&#95;getEnumAsString</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config&#95;getList</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">FileInfo::exists</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">FileInfo::fileName</a>, <a href="#abe3baaa3e5fc0455cd443d1722191cf5">g&#95;latex&#95;macro</a>, <a href="#a4e0395c7f64c90455b817813fdaf3952">g&#95;mathjax&#95;code</a>, <a href="#aa474343ce62c6bd88db53d9924b223a0">getSearchBox</a>, <a href="#a789823b9d7598023371f64ac0da067da">htmlMarkerInfo</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">QCString::prepend</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3f2329035cfde039380d267efff68c76">removeEmptyLines</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a558bfa6d487cad0977c6d706cd638a6c">selectBlocks</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">QCString::startsWith</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5c85e13964c82e9aa4cef183a767651e">substituteKeywords</a> and <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a0c4c6cd48e43f74bf258851f8b109faf">HtmlGenerator::init</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ab59c183ba1429ec58b88fd83ea686d6c">HtmlGenerator::startFile</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9588784ebebaad9cb24e153c07aeb662">HtmlGenerator::writeExternalSearchPage</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9b5d4e446eeaff119ace5a9e0407e984">HtmlGenerator::writePageFooter</a> and <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a1fd6971ba73b744d9ceb90478194d61d">HtmlGenerator::writeSearchPage</a>.
</div>
</div>

### writeClientSearchBox() {#ae5924fde57d9d6dd319193f24735d748}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeClientSearchBox (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath)</td>
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


<p>Definition at line <a href="#l00076">76</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae5924fde57d9d6dd319193f24735d748">76</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae5924fde57d9d6dd319193f24735d748">writeClientSearchBox</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;relPath)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;div id=\"MSearchBox\" class=\"MSearchBoxInactive\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;span class=\"left\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"          &lt;span id=\"MSearchSelect\" class=\"search-icon\" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"onmouseover=\"return searchBox.OnSearchSelectShow()\" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"onmouseout=\"return searchBox.OnSearchSelectHide()\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;span class=\"search-icon-dropdown\"&gt;&lt;/span&gt;&lt;/span&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"          &lt;input type=\"text\" id=\"MSearchField\" value=\"\" placeholder=\""</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">    &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trSearch() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" accesskey=\"S\"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"               onfocus=\"searchBox.OnSearchFieldFocus(true)\" \n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"               onblur=\"searchBox.OnSearchFieldFocus(false)\" \n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"               onkeyup=\"searchBox.OnSearchFieldChange(event)\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"          &lt;/span&gt;&lt;span class=\"right\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"            &lt;a id=\"MSearchClose\" href=\"javascript:searchBox.CloseResultsWindow()\"&gt;"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">    &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div id=\"MSearchCloseImg\" class=\"close-icon\"&gt;&lt;/div&gt;&lt;/a&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"          &lt;/span&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;/div&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>.

Referenced by <a href="#aa474343ce62c6bd88db53d9924b223a0">getSearchBox</a> and <a href="#a6d45214fe7f759039bfd8cc7b37abbf5">renderQuickLinksAsTabs</a>.
</div>
</div>

### writeDefaultQuickLinks() {#a891e19196667b0ff8421e74ccf682140}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDefaultQuickLinks (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09">HighlightedItem</a> hli, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath, bool extraTabs)</td>
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


<p>Definition at line <a href="#l02844">2844</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a891e19196667b0ff8421e74ccf682140">2844</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a891e19196667b0ff8421e74ccf682140">writeDefaultQuickLinks</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2845</span><span class="doxyLineContent"><span class="doxyHighlight">                                   <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09">HighlightedItem</a> hli,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2846</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2847</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;relPath,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2848</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> extraTabs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2849</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2850</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> serverBasedSearch = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(SERVER_BASED_SEARCH);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2851</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> searchEngine      = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(SEARCHENGINE);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2852</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> externalSearch    = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(EXTERNAL_SEARCH);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2853</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> generateTreeView  = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_TREEVIEW);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2854</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> fullSidebar       = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(FULL_SIDEBAR);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2855</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> disableIndex      = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DISABLE_INDEX);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2856</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> dynamicMenus      = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(HTML_DYNAMIC_MENUS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2857</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/layoutnaventry">LayoutNavEntry</a> *root = <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#a87bc2288833b8769bd03e47c58fbba6a">LayoutDocManager::instance</a>().<a href="/web-doxygen/docs/api/classes/layoutdocmanager/#ad70cfcbfc25b8f303a59cd8f76c61465">rootNavEntry</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2858</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/layoutnaventry/#aef36305dd829f7cde87ca203ae647c7c">LayoutNavEntry::Kind</a> kind = LayoutNavEntry::None;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2859</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/layoutnaventry/#aef36305dd829f7cde87ca203ae647c7c">LayoutNavEntry::Kind</a> altKind = LayoutNavEntry::None; </span><span class="doxyHighlightComment">// fall back for the old layout file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2860</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> highlightParent=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2861</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (hli) </span><span class="doxyHighlightComment">// map HLI enums to LayoutNavEntry::Kind enums</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2862</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2863</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09aa02c83a7dbd96295beaefb72c2bee2de">HighlightedItem::Main</a>:                kind = LayoutNavEntry::MainPage;         </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2864</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a34ac805c9077c5ca6ae3565dab6ce723">HighlightedItem::Topics</a>:              kind = LayoutNavEntry::Topics;           </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2865</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09abf17ac149e2e7a530c677e9bd51d3fd2">HighlightedItem::Modules</a>:             kind = LayoutNavEntry::ModuleList;       altKind = LayoutNavEntry::Modules;     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2866</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13d28e8dfc702e3456e0767dff9a128a">HighlightedItem::Namespaces</a>:          kind = LayoutNavEntry::NamespaceList;    altKind = LayoutNavEntry::Namespaces;  </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2867</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a57c86047fd5564e8ea7b49b28fd65467">HighlightedItem::ClassHierarchy</a>:      kind = LayoutNavEntry::ClassHierarchy;   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2868</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a347c6ace003d365adff6ce4a5ea13b70">HighlightedItem::InterfaceHierarchy</a>:  kind = LayoutNavEntry::InterfaceHierarchy;   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2869</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09af4665b1025ccaea95821504b54c901bf">HighlightedItem::ExceptionHierarchy</a>:  kind = LayoutNavEntry::ExceptionHierarchy;   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2870</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09ae9878b4854d29907146149f695cb1cfb">HighlightedItem::Classes</a>:             kind = LayoutNavEntry::ClassIndex;       altKind = LayoutNavEntry::Classes;     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2871</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a0460583622f03a52d7693094d6fa2452">HighlightedItem::Concepts</a>:            kind = LayoutNavEntry::Concepts;         </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2872</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a756640f0aea5f5bea1cbe250a9d08989">HighlightedItem::Interfaces</a>:          kind = LayoutNavEntry::InterfaceIndex;   altKind = LayoutNavEntry::Interfaces;  </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2873</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a6293f87533836e1d190c7b144ee25975">HighlightedItem::Structs</a>:             kind = LayoutNavEntry::StructIndex;      altKind = LayoutNavEntry::Structs;     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2874</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09ad5f1381c5f97f928df4ef8d18c2a27c0">HighlightedItem::Exceptions</a>:          kind = LayoutNavEntry::ExceptionIndex;   altKind = LayoutNavEntry::Exceptions;  </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2875</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09ac3f90a419afd0c4c5e251e63b4a56357">HighlightedItem::AnnotatedClasses</a>:    kind = LayoutNavEntry::ClassList;        altKind = LayoutNavEntry::Classes;     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2876</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a6e52afe5d17ed2f2733183f5a42b0f57">HighlightedItem::AnnotatedInterfaces</a>: kind = LayoutNavEntry::InterfaceList;    altKind = LayoutNavEntry::Interfaces;  </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2877</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09ad4e357557064c964348405dc73fa489f">HighlightedItem::AnnotatedStructs</a>:    kind = LayoutNavEntry::StructList;       altKind = LayoutNavEntry::Structs;     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2878</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a2436f49e8b543b883baae319ab4e679e">HighlightedItem::AnnotatedExceptions</a>: kind = LayoutNavEntry::ExceptionList;    altKind = LayoutNavEntry::Exceptions;  </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2879</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a91f3a2c0e4424c87689525da44c4db11">HighlightedItem::Files</a>:               kind = LayoutNavEntry::FileList;         altKind = LayoutNavEntry::Files;       </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2880</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09abb043aaaabc51d3ab55bcacbcf11fa89">HighlightedItem::NamespaceMembers</a>:    kind = LayoutNavEntry::NamespaceMembers; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2881</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a21825dbffa43bad89156c64150a4bfa2">HighlightedItem::ModuleMembers</a>:       kind = LayoutNavEntry::ModuleMembers;    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2882</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09ae93acb146e114b5dfa6ce2d12dcb96e4">HighlightedItem::Functions</a>:           kind = LayoutNavEntry::ClassMembers;     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2883</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09ad33fc227c2fbdf803a5361d6d78b283b">HighlightedItem::Globals</a>:             kind = LayoutNavEntry::FileGlobals;      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2884</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a453aceb005ceaf54a47da15fee8b2a26">HighlightedItem::Pages</a>:               kind = LayoutNavEntry::Pages;            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2885</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09aff7c0fcd6a31e735a61c001f75426961">HighlightedItem::Examples</a>:            kind = LayoutNavEntry::Examples;         </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2886</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a84ddb07d15cabbefecb37c79122a197c">HighlightedItem::UserGroup</a>:           kind = LayoutNavEntry::UserGroup;        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2887</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09aad17ed06f7834adea0cebf8169d05853">HighlightedItem::ClassVisible</a>:        kind = LayoutNavEntry::ClassList;        altKind = LayoutNavEntry::Classes;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2888</span><span class="doxyLineContent"><span class="doxyHighlight">                                               highlightParent = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2889</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a0bcd73e11bb97ce2940efaebb939cf3e">HighlightedItem::ConceptVisible</a>:      kind = LayoutNavEntry::Concepts;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2890</span><span class="doxyLineContent"><span class="doxyHighlight">                                               highlightParent = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2891</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09aff004b5a3bd2f825025e5ef709e9f34d">HighlightedItem::ModuleVisible</a>:       kind = LayoutNavEntry::ModuleList;       altKind = LayoutNavEntry::Modules;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2892</span><span class="doxyLineContent"><span class="doxyHighlight">                                               highlightParent = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2893</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a34020ed21dcc073f421adcfcb8a4fe5d">HighlightedItem::InterfaceVisible</a>:    kind = LayoutNavEntry::InterfaceList;    altKind = LayoutNavEntry::Interfaces;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2894</span><span class="doxyLineContent"><span class="doxyHighlight">                                               highlightParent = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2895</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a50530abc870ff730c8a9c47f24126f9e">HighlightedItem::StructVisible</a>:       kind = LayoutNavEntry::StructList;       altKind = LayoutNavEntry::Structs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2896</span><span class="doxyLineContent"><span class="doxyHighlight">                                               highlightParent = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2897</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09ae4273455caaf197af0020bad16f55d0f">HighlightedItem::ExceptionVisible</a>:    kind = LayoutNavEntry::ExceptionList;    altKind = LayoutNavEntry::Exceptions;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2898</span><span class="doxyLineContent"><span class="doxyHighlight">                                               highlightParent = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2899</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09ae968691c188c1723e9406a7ceef5016b">HighlightedItem::NamespaceVisible</a>:    kind = LayoutNavEntry::NamespaceList;    altKind = LayoutNavEntry::Namespaces;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2900</span><span class="doxyLineContent"><span class="doxyHighlight">                                               highlightParent = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2901</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a1b93adca69eb7333f1571253486c6bfd">HighlightedItem::FileVisible</a>:         kind = LayoutNavEntry::FileList;         altKind = LayoutNavEntry::Files;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2902</span><span class="doxyLineContent"><span class="doxyHighlight">                                               highlightParent = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2903</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a6adf97f83acf6453d4a6a4b1070f3754">HighlightedItem::None</a>:   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2904</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">HighlightedItem::Search</a>: </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2905</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2906</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2907</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!disableIndex &amp;&amp; dynamicMenus)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2908</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2909</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> searchPage;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2910</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (externalSearch)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2911</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2912</span><span class="doxyLineContent"><span class="doxyHighlight">      searchPage = </span><span class="doxyHighlightStringLiteral">"search"</span><span class="doxyHighlight"> + <a href="/web-doxygen/docs/api/classes/doxygen/#aa98afe79970170f82848bc45b0f076ec">Doxygen::htmlFileExtension</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2913</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2914</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2915</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2916</span><span class="doxyLineContent"><span class="doxyHighlight">      searchPage = </span><span class="doxyHighlightStringLiteral">"search.php"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2917</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2918</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;script type=\"text/javascript\" src=\""</span><span class="doxyHighlight"> &lt;&lt; relPath &lt;&lt; </span><span class="doxyHighlightStringLiteral">"menudata.js\"&gt;&lt;/script&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2919</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;script type=\"text/javascript\" src=\""</span><span class="doxyHighlight"> &lt;&lt; relPath &lt;&lt; </span><span class="doxyHighlightStringLiteral">"menu.js\"&gt;&lt;/script&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2920</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;script type=\"text/javascript\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2921</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"$(function() {\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2922</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  initMenu('"</span><span class="doxyHighlight"> &lt;&lt; relPath &lt;&lt; </span><span class="doxyHighlightStringLiteral">"',"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2923</span><span class="doxyLineContent"><span class="doxyHighlight">      &lt;&lt; (searchEngine &amp;&amp; !(generateTreeView &amp;&amp; fullSidebar)?</span><span class="doxyHighlightStringLiteral">"true"</span><span class="doxyHighlight">:</span><span class="doxyHighlightStringLiteral">"false"</span><span class="doxyHighlight">) &lt;&lt; </span><span class="doxyHighlightStringLiteral">","</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2924</span><span class="doxyLineContent"><span class="doxyHighlight">      &lt;&lt; (serverBasedSearch?</span><span class="doxyHighlightStringLiteral">"true"</span><span class="doxyHighlight">:</span><span class="doxyHighlightStringLiteral">"false"</span><span class="doxyHighlight">) &lt;&lt; </span><span class="doxyHighlightStringLiteral">",'"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2925</span><span class="doxyLineContent"><span class="doxyHighlight">      &lt;&lt; searchPage &lt;&lt; </span><span class="doxyHighlightStringLiteral">"','"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2926</span><span class="doxyLineContent"><span class="doxyHighlight">      &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trSearch() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"',"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2927</span><span class="doxyLineContent"><span class="doxyHighlight">      &lt;&lt; (generateTreeView?</span><span class="doxyHighlightStringLiteral">"true"</span><span class="doxyHighlight">:</span><span class="doxyHighlightStringLiteral">"false"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2928</span><span class="doxyLineContent"><span class="doxyHighlight">      &lt;&lt; </span><span class="doxyHighlightStringLiteral">");\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2929</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (searchEngine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2930</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2931</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!serverBasedSearch)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2932</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2933</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!disableIndex &amp;&amp; dynamicMenus &amp;&amp; !fullSidebar)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2934</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2935</span><span class="doxyLineContent"><span class="doxyHighlight">          t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  $(function() { init_search(); });\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2936</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2937</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2938</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2939</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2940</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  $(function() {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2941</span><span class="doxyLineContent"><span class="doxyHighlight">          &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    if ($('.searchresults').length &gt; 0) { searchBox.DOMSearchField().focus(); }\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2942</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  });\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2943</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2944</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2945</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"});\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2946</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/script&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2947</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div id=\"main-nav\"&gt;&lt;/div&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2948</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2949</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!disableIndex) </span><span class="doxyHighlightComment">// &amp;&amp; !Config_getBool(HTML_DYNAMIC_MENUS)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2950</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2951</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// find highlighted index item</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2952</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/layoutnaventry">LayoutNavEntry</a> *hlEntry = root-&gt;<a href="/web-doxygen/docs/api/structs/layoutnaventry/#ab983afb4157621ae3548364755a75002">find</a>(kind,kind==LayoutNavEntry::UserGroup ? file : <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2953</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!hlEntry &amp;&amp; altKind!=LayoutNavEntry::None) { hlEntry=root-&gt;<a href="/web-doxygen/docs/api/structs/layoutnaventry/#ab983afb4157621ae3548364755a75002">find</a>(altKind); kind=altKind; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2954</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!hlEntry) </span><span class="doxyHighlightComment">// highlighted item not found in the index! -&gt; just show the level 1 index...</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2955</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2956</span><span class="doxyLineContent"><span class="doxyHighlight">      highlightParent=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2957</span><span class="doxyLineContent"><span class="doxyHighlight">      hlEntry = root-&gt;<a href="/web-doxygen/docs/api/structs/layoutnaventry/#a2111e544a2355f2b2a6592819b21b232">children</a>().front().get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2958</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hlEntry==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2959</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2960</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// argl, empty index!</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2961</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2962</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2963</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (kind==LayoutNavEntry::UserGroup)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2964</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2965</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/structs/layoutnaventry">LayoutNavEntry</a> *e = hlEntry-&gt;<a href="/web-doxygen/docs/api/structs/layoutnaventry/#a2111e544a2355f2b2a6592819b21b232">children</a>().front().get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2966</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (e)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2967</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2968</span><span class="doxyLineContent"><span class="doxyHighlight">        hlEntry = e;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2969</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2970</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2971</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div id=\"main-nav\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2972</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6d45214fe7f759039bfd8cc7b37abbf5">renderQuickLinksAsTabs</a>(t,relPath,hlEntry,kind,highlightParent,hli==<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">HighlightedItem::Search</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2973</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!extraTabs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2974</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2975</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;&lt;!-- main-nav --&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2976</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2977</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2978</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!generateTreeView)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2979</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2980</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#acd16443590d430ed27faa06521ec03e4">renderQuickLinksAsTree</a>(t,relPath,root);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2981</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2982</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (generateTreeView &amp;&amp; !disableIndex &amp;&amp; fullSidebar &amp;&amp; !extraTabs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2983</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2984</span><span class="doxyLineContent"><span class="doxyHighlight">     t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div id=\"container\"&gt;&lt;div id=\"doc-content\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2985</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2986</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09ac3f90a419afd0c4c5e251e63b4a56357">AnnotatedClasses</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a2436f49e8b543b883baae319ab4e679e">AnnotatedExceptions</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a6e52afe5d17ed2f2733183f5a42b0f57">AnnotatedInterfaces</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09ad4e357557064c964348405dc73fa489f">AnnotatedStructs</a>, <a href="/web-doxygen/docs/api/structs/layoutnaventry/#a2111e544a2355f2b2a6592819b21b232">LayoutNavEntry::children</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09ae9878b4854d29907146149f695cb1cfb">Classes</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a57c86047fd5564e8ea7b49b28fd65467">ClassHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09aad17ed06f7834adea0cebf8169d05853">ClassVisible</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a0460583622f03a52d7693094d6fa2452">Concepts</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a0bcd73e11bb97ce2940efaebb939cf3e">ConceptVisible</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09aff7c0fcd6a31e735a61c001f75426961">Examples</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09af4665b1025ccaea95821504b54c901bf">ExceptionHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09ad5f1381c5f97f928df4ef8d18c2a27c0">Exceptions</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09ae4273455caaf197af0020bad16f55d0f">ExceptionVisible</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a91f3a2c0e4424c87689525da44c4db11">Files</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a1b93adca69eb7333f1571253486c6bfd">FileVisible</a>, <a href="/web-doxygen/docs/api/structs/layoutnaventry/#ab983afb4157621ae3548364755a75002">LayoutNavEntry::find</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09ae93acb146e114b5dfa6ce2d12dcb96e4">Functions</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09ad33fc227c2fbdf803a5361d6d78b283b">Globals</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#aa98afe79970170f82848bc45b0f076ec">Doxygen::htmlFileExtension</a>, <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#a87bc2288833b8769bd03e47c58fbba6a">LayoutDocManager::instance</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a347c6ace003d365adff6ce4a5ea13b70">InterfaceHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a756640f0aea5f5bea1cbe250a9d08989">Interfaces</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a34020ed21dcc073f421adcfcb8a4fe5d">InterfaceVisible</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09aa02c83a7dbd96295beaefb72c2bee2de">Main</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a21825dbffa43bad89156c64150a4bfa2">ModuleMembers</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09abf17ac149e2e7a530c677e9bd51d3fd2">Modules</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09aff004b5a3bd2f825025e5ef709e9f34d">ModuleVisible</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09abb043aaaabc51d3ab55bcacbcf11fa89">NamespaceMembers</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13d28e8dfc702e3456e0767dff9a128a">Namespaces</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09ae968691c188c1723e9406a7ceef5016b">NamespaceVisible</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a6adf97f83acf6453d4a6a4b1070f3754">None</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a453aceb005ceaf54a47da15fee8b2a26">Pages</a>, <a href="#a6d45214fe7f759039bfd8cc7b37abbf5">renderQuickLinksAsTabs</a>, <a href="#acd16443590d430ed27faa06521ec03e4">renderQuickLinksAsTree</a>, <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#ad70cfcbfc25b8f303a59cd8f76c61465">LayoutDocManager::rootNavEntry</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">Search</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a6293f87533836e1d190c7b144ee25975">Structs</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a50530abc870ff730c8a9c47f24126f9e">StructVisible</a>, <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a34ac805c9077c5ca6ae3565dab6ce723">Topics</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a84ddb07d15cabbefecb37c79122a197c">UserGroup</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9588784ebebaad9cb24e153c07aeb662">HtmlGenerator::writeExternalSearchPage</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a23778fa833bc3d55e61c2cb13d39c090">HtmlGenerator::writeQuickLinks</a> and <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a1fd6971ba73b744d9ceb90478194d61d">HtmlGenerator::writeSearchPage</a>.
</div>
</div>

### writeDefaultStyleSheet() {#ac7339dc7ff25bcb7a9fbea1d671a16da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDefaultStyleSheet (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
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


<p>Definition at line <a href="#l01337">1337</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac7339dc7ff25bcb7a9fbea1d671a16da">1337</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac7339dc7ff25bcb7a9fbea1d671a16da">writeDefaultStyleSheet</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1338</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1339</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"/* The standard CSS for doxygen "</span><span class="doxyHighlight"> &lt;&lt; getDoxygenVersion() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"*/\n\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1340</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(HTML_COLORSTYLE))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1341</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1342</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> HTML_COLORSTYLE_t::LIGHT:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1343</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> HTML_COLORSTYLE_t::DARK:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1344</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">/* variables will be resolved while writing to the CSS file */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1345</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1346</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> HTML_COLORSTYLE_t::AUTO_LIGHT:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1347</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> HTML_COLORSTYLE_t::TOGGLE:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1348</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"html {\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1349</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#af10f5e35396e550af824e3029bab8dd4">replaceColorMarkers</a>(<a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>().getAsString(</span><span class="doxyHighlightStringLiteral">"lightmode_settings.css"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1350</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1351</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1352</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> HTML_COLORSTYLE_t::AUTO_DARK:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1353</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"html {\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1354</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#af10f5e35396e550af824e3029bab8dd4">replaceColorMarkers</a>(<a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>().getAsString(</span><span class="doxyHighlightStringLiteral">"darkmode_settings.css"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1355</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1356</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1357</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1358</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(HTML_COLORSTYLE)==HTML_COLORSTYLE_t::AUTO_LIGHT)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1359</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1360</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"@media (prefers-color-scheme: dark) {\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1361</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  html:not(.dark-mode) {\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1362</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    color-scheme: dark;\n\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1363</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#af10f5e35396e550af824e3029bab8dd4">replaceColorMarkers</a>(<a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>().getAsString(</span><span class="doxyHighlightStringLiteral">"darkmode_settings.css"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1364</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1365</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1366</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(HTML_COLORSTYLE)==HTML_COLORSTYLE_t::AUTO_DARK)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1367</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1368</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"@media (prefers-color-scheme: light) {\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1369</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  html:not(.light-mode) {\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1370</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    color-scheme: light;\n\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1371</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#af10f5e35396e550af824e3029bab8dd4">replaceColorMarkers</a>(<a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>().getAsString(</span><span class="doxyHighlightStringLiteral">"lightmode_settings.css"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1372</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1373</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1374</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(HTML_COLORSTYLE)==HTML_COLORSTYLE_t::TOGGLE)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1375</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1376</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"html.dark-mode {\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1377</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#af10f5e35396e550af824e3029bab8dd4">replaceColorMarkers</a>(<a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>().getAsString(</span><span class="doxyHighlightStringLiteral">"darkmode_settings.css"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1378</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1379</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1380</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1381</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> cssStr = <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>().<a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">getAsString</a>(</span><span class="doxyHighlightStringLiteral">"doxygen.css"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1382</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasFullSidebar = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(FULL_SIDEBAR) &amp;&amp; <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_TREEVIEW);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1383</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hasFullSidebar)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1384</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1385</span><span class="doxyLineContent"><span class="doxyHighlight">    cssStr+=</span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1386</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightStringLiteral">"#titlearea {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1387</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightStringLiteral">"  border-bottom: none;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1388</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightStringLiteral">"  background-color: var(--nav-background-color);\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1389</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightStringLiteral">"  border-right: 1px solid var(--nav-border-color);\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1390</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1391</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1392</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; <a href="#a2f3978430bdfefcb92e25f2da8854f45">replaceVariables</a>(cssStr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1393</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1394</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> addTimestamp = <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(TIMESTAMP)!=TIMESTAMP_t::NO;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1395</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (addTimestamp)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1396</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1397</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> timeStampStr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1398</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(TIMESTAMP))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1399</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1400</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> TIMESTAMP_t::YES:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1401</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> TIMESTAMP_t::DATETIME:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1402</span><span class="doxyLineContent"><span class="doxyHighlight">        timeStampStr = <a href="/web-doxygen/docs/api/files/src/datetime-cpp/#a28a0c3252d0f0f28c0611cbc3268b003">dateToString</a>(<a href="/web-doxygen/docs/api/files/src/datetime-h/#a20573bf423b169aa9100035b297c28fea8cf10d2341ed01492506085688270c1e">DateTimeType::DateTime</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1403</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1404</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> TIMESTAMP_t::DATE:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1405</span><span class="doxyLineContent"><span class="doxyHighlight">        timeStampStr = <a href="/web-doxygen/docs/api/files/src/datetime-cpp/#a28a0c3252d0f0f28c0611cbc3268b003">dateToString</a>(<a href="/web-doxygen/docs/api/files/src/datetime-h/#a20573bf423b169aa9100035b297c28fea44749712dbec183e983dcd78a7736c41">DateTimeType::Date</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1406</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1407</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1408</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1409</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1410</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\nhtml {\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1411</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"--timestamp: '"</span><span class="doxyHighlight"> &lt;&lt; timeStampStr &lt;&lt; </span><span class="doxyHighlightStringLiteral">"'\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1412</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1413</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"span.timestamp { content: ' '; }\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1414</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"span.timestamp:before { content: var(--timestamp); }\n\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1415</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1416</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1417</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// For Webkit based the scrollbar styling cannot be overruled (bug in chromium?).</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1418</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// To allow the user to style the scrollbars differently we should only add it in case</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1419</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// the user did not specify any extra stylesheets.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1420</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> addScrollbarStyling = <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>(HTML_EXTRA_STYLESHEET).empty();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1421</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (addScrollbarStyling)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1422</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1423</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="#a2f3978430bdfefcb92e25f2da8854f45">replaceVariables</a>(<a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>().getAsString(</span><span class="doxyHighlightStringLiteral">"scrollbar.css"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1424</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1425</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1426</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config&#95;getEnum</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config&#95;getList</a>, <a href="/web-doxygen/docs/api/files/src/datetime-h/#a20573bf423b169aa9100035b297c28fea44749712dbec183e983dcd78a7736c41">Date</a>, <a href="/web-doxygen/docs/api/files/src/datetime-h/#a20573bf423b169aa9100035b297c28fea8cf10d2341ed01492506085688270c1e">DateTime</a>, <a href="/web-doxygen/docs/api/files/src/datetime-cpp/#a28a0c3252d0f0f28c0611cbc3268b003">dateToString</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">ResourceMgr::getAsString</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af10f5e35396e550af824e3029bab8dd4">replaceColorMarkers</a> and <a href="#a2f3978430bdfefcb92e25f2da8854f45">replaceVariables</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a86eb94b45459e81c896e184152dd7176">HtmlGenerator::writeStyleInfo</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ae8f3ee4ac698d6d86e7dcaeebfe04fc9">LatexGenerator::writeStyleInfo</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9e0dc4a7197da8f8aa16b96d1c958ab2">HtmlGenerator::writeStyleSheetFile</a> and <a href="/web-doxygen/docs/api/classes/latexgenerator/#a6f04b647eec1bdaa79f1c5f5a9dc85d8">LatexGenerator::writeStyleSheetFile</a>.
</div>
</div>

### writeServerSearchBox() {#a589d7504a995d3f00ae97b7684d588eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeServerSearchBox (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath, bool highlightSearch)</td>
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


<p>Definition at line <a href="#l00098">98</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a589d7504a995d3f00ae97b7684d588eb">98</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a589d7504a995d3f00ae97b7684d588eb">writeServerSearchBox</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;relPath,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> highlightSearch)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> externalSearch = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(EXTERNAL_SEARCH);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;div id=\"MSearchBox\" class=\"MSearchBoxInactive\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"          &lt;div class=\"left\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"            &lt;form id=\"FSearchBox\" action=\""</span><span class="doxyHighlight"> &lt;&lt; relPath;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (externalSearch)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"search"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/classes/doxygen/#aa98afe79970170f82848bc45b0f076ec">Doxygen::htmlFileExtension</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"search.php"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" method=\"get\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"              &lt;span id=\"MSearchSelectExt\" class=\"search-icon\"&gt;&lt;/span&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!highlightSearch || !<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(HTML_DYNAMIC_MENUS))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"              &lt;input type=\"text\" id=\"MSearchField\" name=\"query\" value=\"\" placeholder=\""</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">      &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trSearch() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" size=\"20\" accesskey=\"S\" \n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"                     onfocus=\"searchBox.OnSearchFieldFocus(true)\" \n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"                     onblur=\"searchBox.OnSearchFieldFocus(false)\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"            &lt;/form&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"          &lt;/div&gt;&lt;div class=\"right\"&gt;&lt;/div&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;/div&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#aa98afe79970170f82848bc45b0f076ec">Doxygen::htmlFileExtension</a> and <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>.

Referenced by <a href="#aa474343ce62c6bd88db53d9924b223a0">getSearchBox</a> and <a href="#a6d45214fe7f759039bfd8cc7b37abbf5">renderQuickLinksAsTabs</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### g&#95;darkMap {#ae0f7f0e27ca0e60d44a291398f2b0375}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringUnorderedMap g_darkMap</td>
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


<p>Definition at line <a href="#l00625">625</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae0f7f0e27ca0e60d44a291398f2b0375">625</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/containers-h/#ae9221c0a3b5a2b23e4d7d2cbb8e0d66e">StringUnorderedMap</a> <a href="#ae0f7f0e27ca0e60d44a291398f2b0375">g_darkMap</a>;</span></span></div>

</div>


Referenced by <a href="#ac082e13d5df852dc8a34fd6e84668dff">fillColorStyleMaps</a> and <a href="#a2f3978430bdfefcb92e25f2da8854f45">replaceVariables</a>.
</div>
</div>

### g&#95;footer {#a6ef18a9e8d540c96bde81562abb60e42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString g_footer</td>
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


<p>Definition at line <a href="#l00067">67</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6ef18a9e8d540c96bde81562abb60e42">67</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a6ef18a9e8d540c96bde81562abb60e42">g_footer</a>;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/latexgenerator/#a33cad27a2b5dce6e2762d5915e554118">LatexGenerator::endIndexSection</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a0c4c6cd48e43f74bf258851f8b109faf">HtmlGenerator::init</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#af9a70007c56adecf1af4b4c29591e423">LatexGenerator::init</a> and <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9b5d4e446eeaff119ace5a9e0407e984">HtmlGenerator::writePageFooter</a>.
</div>
</div>

### g&#95;footer&#95;file {#a932663422cdebc372564c94056bf0a7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString g_footer_file</td>
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


<p>Definition at line <a href="#l00066">66</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a932663422cdebc372564c94056bf0a7e">66</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a932663422cdebc372564c94056bf0a7e">g_footer_file</a>;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/latexgenerator/#a33cad27a2b5dce6e2762d5915e554118">LatexGenerator::endIndexSection</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a0c4c6cd48e43f74bf258851f8b109faf">HtmlGenerator::init</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#af9a70007c56adecf1af4b4c29591e423">LatexGenerator::init</a> and <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9b5d4e446eeaff119ace5a9e0407e984">HtmlGenerator::writePageFooter</a>.
</div>
</div>

### g&#95;header {#a3498eed8e2e90303039a4e2245c319d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString g_header</td>
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


<p>Definition at line <a href="#l00064">64</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3498eed8e2e90303039a4e2245c319d3">64</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a3498eed8e2e90303039a4e2245c319d3">g_header</a>;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a0c4c6cd48e43f74bf258851f8b109faf">HtmlGenerator::init</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#af9a70007c56adecf1af4b4c29591e423">LatexGenerator::init</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ab59c183ba1429ec58b88fd83ea686d6c">HtmlGenerator::startFile</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a0de19d805d84ae14aff81334a010c9a1">LatexGenerator::startIndexSection</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9588784ebebaad9cb24e153c07aeb662">HtmlGenerator::writeExternalSearchPage</a> and <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a1fd6971ba73b744d9ceb90478194d61d">HtmlGenerator::writeSearchPage</a>.
</div>
</div>

### g&#95;header&#95;file {#a357af50f3d94adbe34df93d23e5bdd44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString g_header_file</td>
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


<p>Definition at line <a href="#l00065">65</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a357af50f3d94adbe34df93d23e5bdd44">65</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a357af50f3d94adbe34df93d23e5bdd44">g_header_file</a>;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a0c4c6cd48e43f74bf258851f8b109faf">HtmlGenerator::init</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#af9a70007c56adecf1af4b4c29591e423">LatexGenerator::init</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ab59c183ba1429ec58b88fd83ea686d6c">HtmlGenerator::startFile</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a0de19d805d84ae14aff81334a010c9a1">LatexGenerator::startIndexSection</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9588784ebebaad9cb24e153c07aeb662">HtmlGenerator::writeExternalSearchPage</a> and <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a1fd6971ba73b744d9ceb90478194d61d">HtmlGenerator::writeSearchPage</a>.
</div>
</div>

### g&#95;indexLock {#ad2a13506b949e3ae461c03411a8ff36b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex g_indexLock</td>
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


<p>Definition at line <a href="#l01446">1446</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad2a13506b949e3ae461c03411a8ff36b">1446</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::mutex <a href="#ad2a13506b949e3ae461c03411a8ff36b">g_indexLock</a>;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ab59c183ba1429ec58b88fd83ea686d6c">HtmlGenerator::startFile</a>.
</div>
</div>

### g&#95;latex&#95;macro {#abe3baaa3e5fc0455cd443d1722191cf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString g_latex_macro</td>
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


<p>Definition at line <a href="#l00069">69</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abe3baaa3e5fc0455cd443d1722191cf5">69</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#abe3baaa3e5fc0455cd443d1722191cf5">g_latex_macro</a>;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a0c4c6cd48e43f74bf258851f8b109faf">HtmlGenerator::init</a> and <a href="#ac61bfc9dccd1552c036f2a3aabcd6b2c">substituteHtmlKeywords</a>.
</div>
</div>

### g&#95;lightMap {#ac52a9791b71e7f3ccfb32256329e3594}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringUnorderedMap g_lightMap</td>
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


<p>Definition at line <a href="#l00624">624</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac52a9791b71e7f3ccfb32256329e3594">624</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/containers-h/#ae9221c0a3b5a2b23e4d7d2cbb8e0d66e">StringUnorderedMap</a> <a href="#ac52a9791b71e7f3ccfb32256329e3594">g_lightMap</a>;</span></span></div>

</div>


Referenced by <a href="#ac082e13d5df852dc8a34fd6e84668dff">fillColorStyleMaps</a> and <a href="#a2f3978430bdfefcb92e25f2da8854f45">replaceVariables</a>.
</div>
</div>

### g&#95;mathjax&#95;code {#a4e0395c7f64c90455b817813fdaf3952}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString g_mathjax_code</td>
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


<p>Definition at line <a href="#l00068">68</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4e0395c7f64c90455b817813fdaf3952">68</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a4e0395c7f64c90455b817813fdaf3952">g_mathjax_code</a>;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a0c4c6cd48e43f74bf258851f8b109faf">HtmlGenerator::init</a> and <a href="#ac61bfc9dccd1552c036f2a3aabcd6b2c">substituteHtmlKeywords</a>.
</div>
</div>

### hex {#a1748a7403991604b7f600589b77f9937}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto hex ="0123456789ABCDEF"</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00070">70</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1748a7403991604b7f600589b77f9937">70</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">constexpr</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a1748a7403991604b7f600589b77f9937">hex</a>=</span><span class="doxyHighlightStringLiteral">"0123456789ABCDEF"</span><span class="doxyHighlight">;</span></span></div>

</div>

</div>
</div>

### htmlMarkerInfo {#a789823b9d7598023371f64ac0da067da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SelectionMarkerInfo htmlMarkerInfo = { '&lt;', "&lt;!--BEGIN ",10,"&lt;!--END ",8,"--&gt;",3 }</td>
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


<p>Definition at line <a href="#l00072">72</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a789823b9d7598023371f64ac0da067da">72</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/selectionmarkerinfo">SelectionMarkerInfo</a> <a href="#a789823b9d7598023371f64ac0da067da">htmlMarkerInfo</a> = { </span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"&lt;!--BEGIN "</span><span class="doxyHighlight">,10,</span><span class="doxyHighlightStringLiteral">"&lt;!--END "</span><span class="doxyHighlight">,8,</span><span class="doxyHighlightStringLiteral">"--&gt;"</span><span class="doxyHighlight">,3 };</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a0c4c6cd48e43f74bf258851f8b109faf">HtmlGenerator::init</a> and <a href="#ac61bfc9dccd1552c036f2a3aabcd6b2c">substituteHtmlKeywords</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DBG&#95;HTML {#a0f5cdb91a5e817f82987bef2e7f9fc45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DBG_HTML(x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00062">62</a> of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0f5cdb91a5e817f82987bef2e7f9fc45">62</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DBG_HTML(x)</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a5068d044d959a849cf7fd9743d07c012">HtmlGenerator::endIndent</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#adcdb6177d9281921c6d2aa6893b1b5c9">HtmlGenerator::endInlineMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aed5d2db9d4bdda1b0ae0c6824bfbe415">HtmlGenerator::endInlineMemberName</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a7de90155aebd5eacbbca903687f8e5f5">HtmlGenerator::endInlineMemberType</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aa11aa8c21a8b7eb4af49fc708e43e909">HtmlGenerator::endLabels</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a6ca9bf50e7dc80e39b2e9264b3c916ad">HtmlGenerator::endMemberDescription</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ae84d2a7b716a16fa142c0fdb0f8c338c">HtmlGenerator::endMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9300885ee109900582e9a2c8dc298c21">HtmlGenerator::endMemberDocList</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a7ad614730d5b184f8d98b4d3ca6e6dcd">HtmlGenerator::endMemberDocName</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ac007b8ceaed1b6260def8b681ec1e1da">HtmlGenerator::endMemberDocPrefixItem</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aedce042225aecc4a3d499d675251bd6b">HtmlGenerator::endMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a8d2b7702acdf9b41c6b78cee0177820b">HtmlGenerator::endMemberHeader</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a3839bea77bec5697144e8fc0d6ebea15">HtmlGenerator::endMemberList</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9261c777bbdaa1882cbd9186c6b08fb6">HtmlGenerator::endMemberSections</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ae0f7f3498ff3870052db84b11e20eec4">HtmlGenerator::endMemberSubtitle</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a0ad8dcc25a41bc905e649e12b0302a3d">HtmlGenerator::endParameterExtra</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a4a76953ad9eafdccdad1bc536fd9a097">HtmlGenerator::endParameterList</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a535f67c3665549f6f93202fd19ec46da">HtmlGenerator::endParameterName</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a3462109af2644ffeb87b40975d7fb7bd">HtmlGenerator::endParameterType</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a726c53bd6e118a6ab62e6022c7dd80e6">HtmlGenerator::exceptionEntry</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9c6116e3f64dcba6a1b4152afdf91fa1">HtmlGenerator::insertMemberAlign</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a848866b2ca1f5ded259c90a391a7abc4">HtmlGenerator::startIndent</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a719fede306ded713d46b9551eec66cf7">HtmlGenerator::startInlineMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a0d47d7645dc5b280ff77706469a7dd87">HtmlGenerator::startInlineMemberName</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a12aa643326c720f1a8f80610c1bc82fc">HtmlGenerator::startInlineMemberType</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a34bd3e5c72c259091f2546327ac84868">HtmlGenerator::startLabels</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a477b9bf180d9c7a57edcd11c408cdb5b">HtmlGenerator::startMemberDescription</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a3e27be79946300ecc5d82289192fb691">HtmlGenerator::startMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a53aef5bc2dc01700784de5269730cb46">HtmlGenerator::startMemberDocList</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a30b47346a71e1216fb4083c64675bf4e">HtmlGenerator::startMemberDocName</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ae2f67237c29b8499dae33d2462cef68a">HtmlGenerator::startMemberDocPrefixItem</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a7f5dae7d567cd940f9dab8408272e8cd">HtmlGenerator::startMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aea90b1337254e9c10ceaefcff8b9c825">HtmlGenerator::startMemberHeader</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a1ec800447787c1eada0c828c6d3bb374">HtmlGenerator::startMemberItem</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a5b26359bf24a0cac681e048110451dda">HtmlGenerator::startMemberList</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a90e8e67b9d4140660537473a3c98c3d4">HtmlGenerator::startMemberSections</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a287320869b27536a66d09bd7f545507a">HtmlGenerator::startMemberSubtitle</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ac8133798f73d8a88098f57559170a0f0">HtmlGenerator::startParameterExtra</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#af453192b313a5d9bcc31360b15c7feaa">HtmlGenerator::startParameterList</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a1cc2066cc3b3716a98dfb95d756fa838">HtmlGenerator::startParameterName</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a566f2060c7d674363ec9f009e47430ac">HtmlGenerator::startParameterType</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#af012e45f04c5da89f11d17770dad1b00">HtmlGenerator::writeInheritedSectionTitle</a> and <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a8ebfa2100dc76714c34b65372f8ce867">HtmlGenerator::writeLabel</a>.
</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
