---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/markdown-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `markdown.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;stdio.h&gt;
#include &lt;unordered_map&gt;
#include &lt;functional&gt;
#include &lt;atomic&gt;
#include &lt;array&gt;
#include &lt;string_view&gt;
#include "<a href="/web-doxygen/docs/api/files/src/markdown-h">markdown.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/commentscan-h">commentscan.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/entry-h">entry.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/portable-h">portable.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/fileinfo-h">fileinfo.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/trace-h">trace.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/anchor-h">anchor.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/stringutil-h">stringutil.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/tablecell">TableCell</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/markdown/private">Private</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/markdown/private/linkref">LinkRef</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/markdownoutlineparser/private">Private</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">ExplicitPageResult { <a href="#a32bd5ad1ca53505df49807d933ab3611">...</a> }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">Alignment { <a href="#acdfaca60ec19c0265bac2692d7982726">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc4de25503fad3bbfadba71ff6e7581a">isNewline</a> (std::string_view data)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d4cb7f7e85f41df2eab7827e3bec33e">escapeDoubleQuotes</a> (const QCString &amp;s)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ba50f3a46a2d635f06fbc600356ee4a">escapeSpecialChars</a> (const QCString &amp;s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#acdfaca60ec19c0265bac2692d7982726">Alignment</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53933ee56e6d62357cc60bde3156f544">markersToAlignment</a> (bool leftMarker, bool rightMarker)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>helper function to convert presence of left and/or right alignment markers to an alignment value <a href="#a53933ee56e6d62357cc60bde3156f544">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5f8f274225faad69b969f4828376f06">getFilteredImageAttributes</a> (std::string_view fmt, const QCString &amp;attrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parse the image attributes and return attributes for given format <a href="#ad5f8f274225faad69b969f4828376f06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32f3ae19472e55905bc21e27835568d5">isBlockQuote</a> (std::string_view data, size_t indent)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns true if this line starts a block quote <a href="#a32f3ae19472e55905bc21e27835568d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3712f14d18ec5d547f7c55413abdb9fb">isLinkRef</a> (std::string_view data, QCString &amp;refid, QCString &amp;link, QCString &amp;title)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns end of the link ref if this is indeed a link reference. <a href="#a3712f14d18ec5d547f7c55413abdb9fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1f1abe1811f3c45c5b4ee867c15989f">isHRuler</a> (std::string_view data)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b54fef3d70eef54bd49dda068709f43">isEmptyLine</a> (std::string_view data)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a515c2b44ec8500cdb661ff5ab86c60af">computeIndentExcludingListMarkers</a> (std::string_view data)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0a6b598945a869cd184d17fe1f16812">isListMarker</a> (std::string_view data)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4808ea595b45102dac19491e80d2ac9c">isEndOfList</a> (std::string_view data)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acea395582e617dd69781da74f320161e">isFencedCodeBlock</a> (std::string_view data, size_t refIndent, QCString &amp;lang, size_t &amp;start, size_t &amp;end, size_t &amp;offset)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76c8e357497a35b016ee0289e26ee0dd">isCodeBlock</a> (std::string_view data, size_t offset, size_t &amp;indent)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90640de61c785c42e3dc3787610b18eb">findTableColumns</a> (std::string_view data, size_t &amp;start, size_t &amp;end, size_t &amp;columns)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finds the location of the table's contains in the string <em>data</em>. <a href="#a90640de61c785c42e3dc3787610b18eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefadebc5df285d25ef8121a87639323e">isTableBlock</a> (std::string_view data)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns TRUE iff data points to the start of a table block. <a href="#aefadebc5df285d25ef8121a87639323e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a228aefe349d4d8c9272c606c9fbc8c81">hasLineBreak</a> (std::string_view data)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae22648d9504bbec4b64a0c33260fbe4f">skipOverFileAndLineCommands</a> (std::string_view data, size_t indent, size_t &amp;offset, std::string &amp;location)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a127b59cfb20342292c23547477181f9d">isOtherPage</a> (std::string_view data)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a32bd5ad1ca53505df49807d933ab3611">ExplicitPageResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ef42eb1068c60ccbe59ef0024ed1c90">isExplicitPage</a> (const QCString &amp;docs)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a158f67dd586087dac0e968ea384f09">markdownFileNameToId</a> (const QCString &amp;fileName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>processes string <em>s</em> and converts markdown into doxygen/html commands. <a href="#a0a158f67dd586087dac0e968ea384f09">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab90a38f35e109b0e55a693490232d93d">g_utf8_nbsp</a> = "\xc2\xa0"</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5411339961a1e433bf9b59570c97fa6a">g_doxy_nbsp</a> = "&amp;_doxy_nbsp;"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a918fa8a25e6bc30b364b55bc19a5dafd">codeBlockIndent</a> = 4</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static const std::unordered_map&lt; std::string, std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb9b9cc222a09dc4b31c86cf18cd68df">g_quotationHeaderMap</a> = ...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(...)&nbsp;&nbsp;&nbsp;(void)0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(...)&nbsp;&nbsp;&nbsp;(void)0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(...)&nbsp;&nbsp;&nbsp;(void)0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a243e6edb7617162067edc19f3f20bdb9">isIdChar</a>(c)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebe67bf622b3e6fa702be02ee5087910">extraChar</a>(c)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acda15964dfc7b413ab5abb3fca10a1ef">isOpenEmphChar</a>(c)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb2def26524ecd4c96d000b854dee831">ignoreCloseEmphChar</a>(c, cn)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8651540cb26651ce580fdc9504e7fdf2">isLiTag</a>(i)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a644d79c9440b660abd83934b8304b21b">OPC</a>(x)&nbsp;&nbsp;&nbsp;if (<a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>(data,#x " ") || <a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>(data,#x "\n")) return true</td>
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

## Enumerations

### Alignment {#acdfaca60ec19c0265bac2692d7982726}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum Alignment </td>
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
<td class="doxyEnumItemName">AlignNone<a id="acdfaca60ec19c0265bac2692d7982726a4258b9785acff3438d08d41ddb4439d9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AlignLeft<a id="acdfaca60ec19c0265bac2692d7982726a291bdf1a2284d5648efc75ee78fbeb4c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AlignCenter<a id="acdfaca60ec19c0265bac2692d7982726afed76d6718c0a44a25c5e19ae8fb51d1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AlignRight<a id="acdfaca60ec19c0265bac2692d7982726a4758d977046d9c084a0eaf7434fd29e1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 194 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acdfaca60ec19c0265bac2692d7982726afed76d6718c0a44a25c5e19ae8fb51d1">194</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">enum</span><span class="doxyHighlight"> <a href="#acdfaca60ec19c0265bac2692d7982726">Alignment</a> { <a href="#acdfaca60ec19c0265bac2692d7982726a4258b9785acff3438d08d41ddb4439d9">AlignNone</a>, <a href="#acdfaca60ec19c0265bac2692d7982726a291bdf1a2284d5648efc75ee78fbeb4c">AlignLeft</a>, <a href="#acdfaca60ec19c0265bac2692d7982726afed76d6718c0a44a25c5e19ae8fb51d1">AlignCenter</a>, <a href="#acdfaca60ec19c0265bac2692d7982726a4758d977046d9c084a0eaf7434fd29e1">AlignRight</a> };</span></span></div>

</div>

</div>
</div>

### ExplicitPageResult {#a32bd5ad1ca53505df49807d933ab3611}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class ExplicitPageResult </td>
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
<td class="doxyEnumItemName">explicitPage<a id="a32bd5ad1ca53505df49807d933ab3611ae2813323b951a15b22babe5224d9dabe"></a></td>
<td class="doxyEnumItemDescription">docs start with a page command</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">explicitMainPage<a id="a32bd5ad1ca53505df49807d933ab3611a7e256e56ac82ab7e84c0a827a6f87530"></a></td>
<td class="doxyEnumItemDescription">docs start with a mainpage command</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">explicitOtherPage<a id="a32bd5ad1ca53505df49807d933ab3611afac4940bb70ae7157485b0a935d65548"></a></td>
<td class="doxyEnumItemDescription">docs start with a dir / defgroup / addtogroup command</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">notExplicit<a id="a32bd5ad1ca53505df49807d933ab3611aed049ce087485c91fc2610599aebd142"></a></td>
<td class="doxyEnumItemDescription">docs doesn't start with either page or mainpage</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 66 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a32bd5ad1ca53505df49807d933ab3611ae2813323b951a15b22babe5224d9dabe">68</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a32bd5ad1ca53505df49807d933ab3611ae2813323b951a15b22babe5224d9dabe">explicitPage</a>,      </span><span class="doxyHighlightComment">/**&lt; docs start with a page command */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a32bd5ad1ca53505df49807d933ab3611a7e256e56ac82ab7e84c0a827a6f87530">69</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a32bd5ad1ca53505df49807d933ab3611a7e256e56ac82ab7e84c0a827a6f87530">explicitMainPage</a>,  </span><span class="doxyHighlightComment">/**&lt; docs start with a mainpage command */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a32bd5ad1ca53505df49807d933ab3611afac4940bb70ae7157485b0a935d65548">70</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a32bd5ad1ca53505df49807d933ab3611afac4940bb70ae7157485b0a935d65548">explicitOtherPage</a>, </span><span class="doxyHighlightComment">/**&lt; docs start with a dir / defgroup / addtogroup command */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a32bd5ad1ca53505df49807d933ab3611aed049ce087485c91fc2610599aebd142">71</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a32bd5ad1ca53505df49807d933ab3611aed049ce087485c91fc2610599aebd142">notExplicit</a>        </span><span class="doxyHighlightComment">/**&lt; docs doesn't start with either page or mainpage */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### computeIndentExcludingListMarkers() {#a515c2b44ec8500cdb661ff5ab86c60af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t computeIndentExcludingListMarkers (std::string_view data)</td>
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



<p>Definition at line 2113 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a515c2b44ec8500cdb661ff5ab86c60af">2113</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a515c2b44ec8500cdb661ff5ab86c60af">computeIndentExcludingListMarkers</a>(std::string_view data)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2114</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2115</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}'"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2116</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2117</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size=data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2118</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> indent=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2119</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isDigit=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2120</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isLi=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2121</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> listMarkerSkipped=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2122</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2123</span><span class="doxyLineContent"><span class="doxyHighlight">         (data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> ||                                    </span><span class="doxyHighlightComment">// space</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2124</span><span class="doxyLineContent"><span class="doxyHighlight">          (!listMarkerSkipped &amp;&amp;                             </span><span class="doxyHighlightComment">// first list marker</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2125</span><span class="doxyLineContent"><span class="doxyHighlight">           (data[i]==</span><span class="doxyHighlightCharLiteral">'+'</span><span class="doxyHighlight"> || data[i]==</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight"> || data[i]==</span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight"> ||  </span><span class="doxyHighlightComment">// unordered list char</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2126</span><span class="doxyLineContent"><span class="doxyHighlight">            (data[i]==</span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight"> &amp;&amp; i&gt;0 &amp;&amp; data[i-1]==</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">) ||       </span><span class="doxyHighlightComment">// -# item</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2127</span><span class="doxyLineContent"><span class="doxyHighlight">            (isDigit=(data[i]&gt;=</span><span class="doxyHighlightCharLiteral">'1'</span><span class="doxyHighlight"> &amp;&amp; data[i]&lt;=</span><span class="doxyHighlightCharLiteral">'9'</span><span class="doxyHighlight">)) ||      </span><span class="doxyHighlightComment">// ordered list marker?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2128</span><span class="doxyLineContent"><span class="doxyHighlight">            (isLi=(size&gt;=3 &amp;&amp; i+3&lt;size &amp;&amp; <a href="#a8651540cb26651ce580fdc9504e7fdf2">isLiTag</a>(i)))       </span><span class="doxyHighlightComment">// &lt;li&gt; tag</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2129</span><span class="doxyLineContent"><span class="doxyHighlight">           )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2130</span><span class="doxyLineContent"><span class="doxyHighlight">          )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2131</span><span class="doxyLineContent"><span class="doxyHighlight">         )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2132</span><span class="doxyLineContent"><span class="doxyHighlight">        )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2133</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2134</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isDigit) </span><span class="doxyHighlightComment">// skip over ordered list marker '10. '</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2135</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2136</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> j=i+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2137</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (j&lt;size &amp;&amp; ((data[j]&gt;=</span><span class="doxyHighlightCharLiteral">'0'</span><span class="doxyHighlight"> &amp;&amp; data[j]&lt;=</span><span class="doxyHighlightCharLiteral">'9'</span><span class="doxyHighlight">) || data[j]==</span><span class="doxyHighlightCharLiteral">'.'</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2138</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2139</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[j]==</span><span class="doxyHighlightCharLiteral">'.'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// should be end of the list marker</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2140</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2141</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (j+1&lt;size &amp;&amp; data[j+1]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// valid list marker</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2142</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2143</span><span class="doxyLineContent"><span class="doxyHighlight">            listMarkerSkipped=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2144</span><span class="doxyLineContent"><span class="doxyHighlight">            indent+=j+1-i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2145</span><span class="doxyLineContent"><span class="doxyHighlight">            i=j+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2146</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2147</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2148</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// not a list marker</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2149</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2150</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2151</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2152</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2153</span><span class="doxyLineContent"><span class="doxyHighlight">        j++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2154</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2155</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2156</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isLi)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2157</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2158</span><span class="doxyLineContent"><span class="doxyHighlight">      i+=3; </span><span class="doxyHighlightComment">// skip over &lt;li&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2159</span><span class="doxyLineContent"><span class="doxyHighlight">      indent+=3;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2160</span><span class="doxyLineContent"><span class="doxyHighlight">      listMarkerSkipped=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2161</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2162</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight"> &amp;&amp; size&gt;=2 &amp;&amp; i+2&lt;size &amp;&amp; data[i+1]==</span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight"> &amp;&amp; data[i+2]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2163</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightComment">// case "-# "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2164</span><span class="doxyLineContent"><span class="doxyHighlight">      listMarkerSkipped=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>; </span><span class="doxyHighlightComment">// only a single list marker is accepted</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2165</span><span class="doxyLineContent"><span class="doxyHighlight">      i++; </span><span class="doxyHighlightComment">// skip over #</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2166</span><span class="doxyLineContent"><span class="doxyHighlight">      indent++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2167</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2168</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]!=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> &amp;&amp; i+1&lt;size &amp;&amp; data[i+1]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2169</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightComment">// case "- " or "+ " or "* "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2170</span><span class="doxyLineContent"><span class="doxyHighlight">      listMarkerSkipped=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>; </span><span class="doxyHighlightComment">// only a single list marker is accepted</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2171</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2172</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]!=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> &amp;&amp; !listMarkerSkipped)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2173</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightComment">// end of indent</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2174</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2175</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2176</span><span class="doxyLineContent"><span class="doxyHighlight">    indent++,i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2177</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2178</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,indent);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2179</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> indent;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2180</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a8651540cb26651ce580fdc9504e7fdf2">isLiTag</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.</p>


<p>Referenced by <a href="#a76c8e357497a35b016ee0289e26ee0dd">isCodeBlock</a> and <a href="#ad0a6b598945a869cd184d17fe1f16812">isListMarker</a>.</p>

</div>
</div>

### escapeDoubleQuotes() {#a3d4cb7f7e85f41df2eab7827e3bec33e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString escapeDoubleQuotes (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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



<p>Definition at line 220 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3d4cb7f7e85f41df2eab7827e3bec33e">220</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a3d4cb7f7e85f41df2eab7827e3bec33e">escapeDoubleQuotes</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"s={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(s));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c=0, pc=</span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight"> &amp;&amp; pc!=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">) result+=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">    result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">    pc=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/markdown/private/#a1213861d8af699057686e457bce66509">Markdown::Private::writeMarkdownImage</a>.</p>

</div>
</div>

### escapeSpecialChars() {#a5ba50f3a46a2d635f06fbc600356ee4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString escapeSpecialChars (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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



<p>Definition at line 238 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5ba50f3a46a2d635f06fbc600356ee4a">238</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a5ba50f3a46a2d635f06fbc600356ee4a">escapeSpecialChars</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"s={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(s));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> insideQuote=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c=0, pc=</span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pc!=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">)  { insideQuote=!insideQuote; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">        result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// fall through</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!insideQuote)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">          result+=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">          result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((p[0]==</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight">) &amp;&amp; (p[1]==</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">            result+=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">            result+=</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">            p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">          result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!insideQuote) { result+=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">; } result+=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">:  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!insideQuote) { result+=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">; } result+=</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// commented out next line due to regression when using % to suppress a link</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//case '%':  if (!insideQuote) { result+='\\'; } result+='%'; break;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">:  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!insideQuote) { result+=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">; } result+=</span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'$'</span><span class="doxyHighlight">:  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!insideQuote) { result+=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">; } result+=</span><span class="doxyHighlightCharLiteral">'$'</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&amp;'</span><span class="doxyHighlight">:  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!insideQuote) { result+=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">; } result+=</span><span class="doxyHighlightCharLiteral">'&amp;'</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">        result+=c; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">    pc=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/markdown/private/#a42dc4e1d481af0574e750df55678d54d">Markdown::Private::processCodeSpan</a>.</p>

</div>
</div>

### findTableColumns() {#a90640de61c785c42e3dc3787610b18eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t findTableColumns (std::string_view data, size_t &amp; start, size_t &amp; end, size_t &amp; columns)</td>
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

<p>Finds the location of the table's contains in the string <em>data</em>.</p>


<p>Only one line will be inspected.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] data</td>
<td class="doxyParamItemDescription"><p>pointer to the string buffer.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] start</td>
<td class="doxyParamItemDescription"><p>offset of the first character of the table content</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] end</td>
<td class="doxyParamItemDescription"><p>offset of the last character of the table content</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] columns</td>
<td class="doxyParamItemDescription"><p>number of table columns found</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The offset until the next line in the buffer.</p></dd>
</dl>


<p>Definition at line 2398 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a90640de61c785c42e3dc3787610b18eb">2398</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a90640de61c785c42e3dc3787610b18eb">findTableColumns</a>(std::string_view data,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> &amp;start,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> &amp;<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> &amp;columns)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2399</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2400</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}'"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2401</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2402</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0,n=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2403</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// find start character of the table line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2404</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2405</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">'|'</span><span class="doxyHighlight"> &amp;&amp; data[i]!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) i++,n++; </span><span class="doxyHighlightComment">// leading | does not count</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2406</span><span class="doxyLineContent"><span class="doxyHighlight">  start = i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2407</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2408</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// find end character of the table line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2409</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> j = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2410</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; (j = <a href="#afc4de25503fad3bbfadba71ff6e7581a">isNewline</a>(data.substr(i)))==0) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2411</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/vhdlparser/parseexception-h/#a55b81f273444186ad83e1087f9a3706d">eol</a>=i+j;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2412</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2413</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (j&gt;0 &amp;&amp; i&gt;0) i--; </span><span class="doxyHighlightComment">// move i to point before newline</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2414</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&gt;0 &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) i--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2415</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&gt;0 &amp;&amp; data[i-1]!=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight"> &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">'|'</span><span class="doxyHighlight">) i--,n++; </span><span class="doxyHighlightComment">// trailing or escaped | does not count</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2416</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a> = i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2417</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2418</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// count columns between start and end</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2419</span><span class="doxyLineContent"><span class="doxyHighlight">  columns=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2420</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>&gt;start)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2421</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2422</span><span class="doxyLineContent"><span class="doxyHighlight">    i=start;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2423</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;=<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>) </span><span class="doxyHighlightComment">// look for more column markers</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2424</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2425</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'|'</span><span class="doxyHighlight"> &amp;&amp; (i==0 || data[i-1]!=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">)) columns++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2426</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (columns==1) columns++; </span><span class="doxyHighlightComment">// first | make a non-table into a two column table</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2427</span><span class="doxyLineContent"><span class="doxyHighlight">      i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2428</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2429</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2430</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (n==2 &amp;&amp; columns==0) </span><span class="doxyHighlightComment">// table row has | ... |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2431</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2432</span><span class="doxyLineContent"><span class="doxyHighlight">    columns++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2433</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2434</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"eol={} start={} end={} columns={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/vhdlparser/parseexception-h/#a55b81f273444186ad83e1087f9a3706d">eol</a>,start,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>,columns);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2435</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/vhdlparser/parseexception-h/#a55b81f273444186ad83e1087f9a3706d">eol</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2436</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="/web-doxygen/docs/api/files/vhdlparser/parseexception-h/#a55b81f273444186ad83e1087f9a3706d">eol</a>, <a href="#afc4de25503fad3bbfadba71ff6e7581a">isNewline</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.</p>


<p>Referenced by <a href="#aefadebc5df285d25ef8121a87639323e">isTableBlock</a> and <a href="/web-doxygen/docs/api/structs/markdown/private/#a21b82aade2e5a369ec438f0cd49f8107">Markdown::Private::writeTableBlock</a>.</p>

</div>
</div>

### getFilteredImageAttributes() {#ad5f8f274225faad69b969f4828376f06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString getFilteredImageAttributes (std::string_view fmt, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; attrs)</td>
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

<p>parse the image attributes and return attributes for given format</p>

<p>Definition at line 313 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad5f8f274225faad69b969f4828376f06">313</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ad5f8f274225faad69b969f4828376f06">getFilteredImageAttributes</a>(std::string_view <a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;attrs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"fmt={} attrs={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>,attrs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> attrList = <a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a>(attrs.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),</span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;attr_ : attrList)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> attr = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(attr_).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = attr.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&gt;0) </span><span class="doxyHighlightComment">// has format</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> format = attr.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(i).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (format == <a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>) </span><span class="doxyHighlightComment">// matching format</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,attr.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(i+1));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> attr.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(i+1); </span><span class="doxyHighlightComment">// keep part after :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// option that applies to all formats</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,attr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> attr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/markdown/private/#a1213861d8af699057686e457bce66509">Markdown::Private::writeMarkdownImage</a>.</p>

</div>
</div>

### hasLineBreak() {#a228aefe349d4d8c9272c606c9fbc8c81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasLineBreak (std::string_view data)</td>
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



<p>Definition at line 2679 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a228aefe349d4d8c9272c606c9fbc8c81">2679</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a228aefe349d4d8c9272c606c9fbc8c81">hasLineBreak</a>(std::string_view data)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2680</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2681</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}'"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2682</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2683</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> j=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2684</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// search for end of line and also check if it is not a completely blank</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2685</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;data.size() &amp;&amp; data[i]!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2686</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2687</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]!=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> &amp;&amp; data[i]!=</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">) j++; </span><span class="doxyHighlightComment">// some non whitespace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2688</span><span class="doxyLineContent"><span class="doxyHighlight">    i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2689</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2690</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&gt;=data.size()) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; } </span><span class="doxyHighlightComment">// empty line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2691</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;2)            { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; } </span><span class="doxyHighlightComment">// not long enough</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2692</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> res = (j&gt;0 &amp;&amp; data[i-1]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> &amp;&amp; data[i-2]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">); </span><span class="doxyHighlightComment">// non blank line with at two spaces at the end</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2693</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,res);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2694</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> res;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2695</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/markdown/private/#af7ceebe6b90c368816a6d9bd0ca501c0">Markdown::Private::writeOneLineHeaderOrRuler</a>.</p>

</div>
</div>

### isBlockQuote() {#a32f3ae19472e55905bc21e27835568d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isBlockQuote (std::string_view data, size_t indent)</td>
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

<p>returns true if this line starts a block quote</p>

<p>Definition at line 1842 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a32f3ae19472e55905bc21e27835568d5">1842</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a32f3ae19472e55905bc21e27835568d5">isBlockQuote</a>(std::string_view data,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> indent)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1843</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1844</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}' indent={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data),indent);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1845</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1846</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1847</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1848</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;indent+<a href="#a918fa8a25e6bc30b364b55bc19a5dafd">codeBlockIndent</a>) </span><span class="doxyHighlightComment">// could be a quotation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1849</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1850</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// count &gt;'s and skip spaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1851</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1852</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; (data[i]==</span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight"> || data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1853</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1854</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight">) level++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1855</span><span class="doxyLineContent"><span class="doxyHighlight">      i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1856</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1857</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// last characters should be a space or newline,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1858</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// so a line starting with &gt;= does not match, but only when level equals 1</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1859</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> res = (level&gt;0 &amp;&amp; i&lt;size &amp;&amp; ((data[i-1]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) || data[i]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)) || (level &gt; 1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1860</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,res);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1861</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> res;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1862</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1863</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// too much indentation -&gt; code block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1864</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1865</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result=false: too much indentation"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1866</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1867</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1868</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="#a918fa8a25e6bc30b364b55bc19a5dafd">codeBlockIndent</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/markdown/private/#a9792322da9173be90556ef009d37afa4">Markdown::Private::processQuotations</a>.</p>

</div>
</div>

### isCodeBlock() {#a76c8e357497a35b016ee0289e26ee0dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isCodeBlock (std::string_view data, size_t offset, size_t &amp; indent)</td>
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



<p>Definition at line 2305 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a76c8e357497a35b016ee0289e26ee0dd">2305</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a76c8e357497a35b016ee0289e26ee0dd">isCodeBlock</a>(std::string_view data, </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> offset,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> &amp;indent)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2306</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2307</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}' offset={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data),offset);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2308</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("&lt;isCodeBlock(offset=%d,size=%d,indent=%d)\n",offset,size,indent);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2309</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// determine the indent of this line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2310</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2311</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> indent0=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2312</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2313</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) indent0++,i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2314</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2315</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (indent0&lt;<a href="#a918fa8a25e6bc30b364b55bc19a5dafd">codeBlockIndent</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2316</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2317</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}: line is not indented enough {}&lt;4"</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,indent0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2318</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2319</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2320</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (indent0&gt;=size || data[indent0]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// empty line does not start a code block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2321</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2322</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}: only spaces at the end of a comment block"</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2323</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2324</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2325</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2326</span><span class="doxyLineContent"><span class="doxyHighlight">  i=offset;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2327</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> nl=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2328</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> nl_pos[3];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2329</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> offset_i = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(offset);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2330</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// search back 3 lines and remember the start of lines -1 and -2</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2331</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&gt;0 &amp;&amp; nl&lt;3) </span><span class="doxyHighlightComment">// i counts down from offset to 1</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2332</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2333</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> j = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(i)-offset_i-1; </span><span class="doxyHighlightComment">// j counts from -1 to -offset</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2334</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// since j can be negative we need to rewrap data in a std::string_view</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2335</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> nl_size = <a href="#afc4de25503fad3bbfadba71ff6e7581a">isNewline</a>(std::string_view(data.data()+j,data.size()-j));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2336</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nl_size&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2337</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2338</span><span class="doxyLineContent"><span class="doxyHighlight">      nl_pos[nl++]=j+</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(nl_size);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2339</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2340</span><span class="doxyLineContent"><span class="doxyHighlight">    i--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2341</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2342</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2343</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// if there are only 2 preceding lines, then line -2 starts at -offset</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2344</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i==0 &amp;&amp; nl==2) nl_pos[nl++]=-offset_i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2345</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2346</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nl==3) </span><span class="doxyHighlightComment">// we have at least 2 preceding lines</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2347</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2348</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("  positions: nl_pos=[%d,%d,%d] line[-2]='%s' line[-1]='%s'\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2349</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//    nl_pos[0],nl_pos[1],nl_pos[2],</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2350</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//    qPrint(QCString(data+nl_pos[1]).left(nl_pos[0]-nl_pos[1]-1)),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2351</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//    qPrint(QCString(data+nl_pos[2]).left(nl_pos[1]-nl_pos[2]-1)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2352</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2353</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// check that line -1 is empty</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2354</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// Note that the offset is negative so we need to rewrap the string view</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2355</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7b54fef3d70eef54bd49dda068709f43">isEmptyLine</a>(std::string_view(data.data()+nl_pos[1],nl_pos[0]-nl_pos[1]-1)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2356</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2357</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2358</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2359</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2360</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2361</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// determine the indent of line -2</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2362</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// Note that the offset is negative so we need to rewrap the string view</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2363</span><span class="doxyLineContent"><span class="doxyHighlight">    indent=std::max(indent,<a href="#a515c2b44ec8500cdb661ff5ab86c60af">computeIndentExcludingListMarkers</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2364</span><span class="doxyLineContent"><span class="doxyHighlight">          std::string_view(data.data()+nl_pos[2],nl_pos[1]-nl_pos[2])));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2365</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2366</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("&gt;isCodeBlock local_indent %d&gt;=%d+%d=%d\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2367</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//    indent0,indent,codeBlockIndent,indent0&gt;=indent+codeBlockIndent);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2368</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// if the difference is &gt;4 spaces -&gt; code block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2369</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> res = indent0&gt;=indent+<a href="#a918fa8a25e6bc30b364b55bc19a5dafd">codeBlockIndent</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2370</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}: code block if indent difference &gt;4 spaces"</span><span class="doxyHighlight">,res);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2371</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> res;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2372</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2373</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// not enough lines to determine the relative indent, use global indent</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2374</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2375</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// check that line -1 is empty</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2376</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// Note that the offset is negative so we need to rewrap the string view</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2377</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nl==1 &amp;&amp; !<a href="#a7b54fef3d70eef54bd49dda068709f43">isEmptyLine</a>(std::string_view(data.data()-offset,offset-1)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2378</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2379</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result=false"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2380</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2381</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2382</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("&gt;isCodeBlock global indent %d&gt;=%d+4=%d nl=%d\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2383</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//    indent0,indent,indent0&gt;=indent+4,nl);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2384</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> res = indent0&gt;=indent+<a href="#a918fa8a25e6bc30b364b55bc19a5dafd">codeBlockIndent</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2385</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}: code block if indent difference &gt;4 spaces"</span><span class="doxyHighlight">,res);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2386</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> res;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2387</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2388</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="#a918fa8a25e6bc30b364b55bc19a5dafd">codeBlockIndent</a>, <a href="#a515c2b44ec8500cdb661ff5ab86c60af">computeIndentExcludingListMarkers</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a7b54fef3d70eef54bd49dda068709f43">isEmptyLine</a>, <a href="#afc4de25503fad3bbfadba71ff6e7581a">isNewline</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/markdown/private/#a9835402c2d15b122de1c3ba4180ebd58">Markdown::Private::processBlocks</a>.</p>

</div>
</div>

### isEmptyLine() {#a7b54fef3d70eef54bd49dda068709f43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isEmptyLine (std::string_view data)</td>
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



<p>Definition at line 2091 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7b54fef3d70eef54bd49dda068709f43">2091</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a7b54fef3d70eef54bd49dda068709f43">isEmptyLine</a>(std::string_view data)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2092</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2093</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}'"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2094</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2095</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;data.size())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2096</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2097</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) { <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"true"</span><span class="doxyHighlight">);  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2098</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]!=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">)  { <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"false"</span><span class="doxyHighlight">); </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2099</span><span class="doxyLineContent"><span class="doxyHighlight">    i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2100</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2101</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"true"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2102</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2103</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.</p>


<p>Referenced by <a href="#a76c8e357497a35b016ee0289e26ee0dd">isCodeBlock</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9835402c2d15b122de1c3ba4180ebd58">Markdown::Private::processBlocks</a> and <a href="/web-doxygen/docs/api/structs/markdown/private/#a9792322da9173be90556ef009d37afa4">Markdown::Private::processQuotations</a>.</p>

</div>
</div>

### isEndOfList() {#a4808ea595b45102dac19491e80d2ac9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isEndOfList (std::string_view data)</td>
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



<p>Definition at line 2193 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4808ea595b45102dac19491e80d2ac9c">2193</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a4808ea595b45102dac19491e80d2ac9c">isEndOfList</a>(std::string_view data)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2194</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2195</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}'"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2196</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> dots=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2197</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2198</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// end of list marker is an otherwise empty line with a dot.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2199</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;data.size())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2200</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2201</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'.'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2202</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2203</span><span class="doxyLineContent"><span class="doxyHighlight">      dots++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2204</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2205</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2206</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2207</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2208</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2209</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]!=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> &amp;&amp; data[i]!=</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// bail out if the line is not empty</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2210</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2211</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result=false"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2212</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2213</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2214</span><span class="doxyLineContent"><span class="doxyHighlight">    i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2215</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2216</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,dots==1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2217</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> dots==1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2218</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/markdown/private/#a9835402c2d15b122de1c3ba4180ebd58">Markdown::Private::processBlocks</a> and <a href="/web-doxygen/docs/api/structs/markdown/private/#a9792322da9173be90556ef009d37afa4">Markdown::Private::processQuotations</a>.</p>

</div>
</div>

### isExplicitPage() {#a9ef42eb1068c60ccbe59ef0024ed1c90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExplicitPageResult isExplicitPage (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; docs)</td>
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



<p>Definition at line 3450 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9ef42eb1068c60ccbe59ef0024ed1c90">3450</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="#a32bd5ad1ca53505df49807d933ab3611">ExplicitPageResult</a> <a href="#a9ef42eb1068c60ccbe59ef0024ed1c90">isExplicitPage</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;docs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3451</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3452</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"docs={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(docs));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3453</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3454</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string_view data(docs.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3455</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3456</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!data.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3457</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3458</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; (data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || data[i]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3459</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3460</span><span class="doxyLineContent"><span class="doxyHighlight">      i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3461</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3462</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>(data.substr(i),</span><span class="doxyHighlightStringLiteral">"&lt;!--!"</span><span class="doxyHighlight">)) </span><span class="doxyHighlightComment">// skip over &lt;!--! marker</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3463</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3464</span><span class="doxyLineContent"><span class="doxyHighlight">      i+=5;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3465</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; (data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || data[i]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)) </span><span class="doxyHighlightComment">// skip over spaces after the &lt;!--! marker</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3466</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3467</span><span class="doxyLineContent"><span class="doxyHighlight">        i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3468</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3469</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3470</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i+1&lt;size &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3471</span><span class="doxyLineContent"><span class="doxyHighlight">        (data[i]==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight"> || data[i]==</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3472</span><span class="doxyLineContent"><span class="doxyHighlight">        (<a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>(data.substr(i+1),</span><span class="doxyHighlightStringLiteral">"page "</span><span class="doxyHighlight">) || <a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>(data.substr(i+1),</span><span class="doxyHighlightStringLiteral">"mainpage"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3473</span><span class="doxyLineContent"><span class="doxyHighlight">       )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3474</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3475</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>(data.substr(i+1),</span><span class="doxyHighlightStringLiteral">"page "</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3476</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3477</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result=ExplicitPageResult::explicitPage"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3478</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a32bd5ad1ca53505df49807d933ab3611ae2813323b951a15b22babe5224d9dabe">ExplicitPageResult::explicitPage</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3479</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3480</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3481</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3482</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result=ExplicitPageResult::explicitMainPage"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3483</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a32bd5ad1ca53505df49807d933ab3611a7e256e56ac82ab7e84c0a827a6f87530">ExplicitPageResult::explicitMainPage</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3484</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3485</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3486</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i+1&lt;size &amp;&amp; (data[i]==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight"> || data[i]==</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">) &amp;&amp; <a href="#a127b59cfb20342292c23547477181f9d">isOtherPage</a>(data.substr(i+1)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3487</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3488</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result=ExplicitPageResult::explicitOtherPage"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3489</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a32bd5ad1ca53505df49807d933ab3611afac4940bb70ae7157485b0a935d65548">ExplicitPageResult::explicitOtherPage</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3490</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3491</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3492</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result=ExplicitPageResult::notExplicit"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3493</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a32bd5ad1ca53505df49807d933ab3611aed049ce087485c91fc2610599aebd142">ExplicitPageResult::notExplicit</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3494</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="#a32bd5ad1ca53505df49807d933ab3611a7e256e56ac82ab7e84c0a827a6f87530">explicitMainPage</a>, <a href="#a32bd5ad1ca53505df49807d933ab3611afac4940bb70ae7157485b0a935d65548">explicitOtherPage</a>, <a href="#a32bd5ad1ca53505df49807d933ab3611ae2813323b951a15b22babe5224d9dabe">explicitPage</a>, <a href="#a127b59cfb20342292c23547477181f9d">isOtherPage</a>, <a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>, <a href="#a32bd5ad1ca53505df49807d933ab3611aed049ce087485c91fc2610599aebd142">notExplicit</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/markdownoutlineparser/#a0cb95204f0f91c085e6a9808efb2ebdc">MarkdownOutlineParser::parseInput</a>.</p>

</div>
</div>

### isFencedCodeBlock() {#acea395582e617dd69781da74f320161e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isFencedCodeBlock (std::string_view data, size_t refIndent, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; lang, size_t &amp; start, size_t &amp; end, size_t &amp; offset)</td>
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



<p>Definition at line 2220 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acea395582e617dd69781da74f320161e">2220</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#acea395582e617dd69781da74f320161e">isFencedCodeBlock</a>(std::string_view data,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> refIndent,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2221</span><span class="doxyLineContent"><span class="doxyHighlight">                             <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;lang,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> &amp;start,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> &amp;<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> &amp;offset)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2222</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2223</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}' refIndent={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data),refIndent);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2224</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> dot = </span><span class="doxyHighlightCharLiteral">'.'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2225</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> isAlphaChar  = [ ](</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> (c&gt;=</span><span class="doxyHighlightCharLiteral">'A'</span><span class="doxyHighlight"> &amp;&amp; c&lt;=</span><span class="doxyHighlightCharLiteral">'Z'</span><span class="doxyHighlight">) || (c&gt;=</span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight"> &amp;&amp; c&lt;=</span><span class="doxyHighlightCharLiteral">'z'</span><span class="doxyHighlight">); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2226</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> isAlphaNChar = [ ](</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> (c&gt;=</span><span class="doxyHighlightCharLiteral">'A'</span><span class="doxyHighlight"> &amp;&amp; c&lt;=</span><span class="doxyHighlightCharLiteral">'Z'</span><span class="doxyHighlight">) || (c&gt;=</span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight"> &amp;&amp; c&lt;=</span><span class="doxyHighlightCharLiteral">'z'</span><span class="doxyHighlight">) || (c&gt;=</span><span class="doxyHighlightCharLiteral">'0'</span><span class="doxyHighlight"> &amp;&amp; c&lt;=</span><span class="doxyHighlightCharLiteral">'9'</span><span class="doxyHighlight">) || (c==</span><span class="doxyHighlightCharLiteral">'+'</span><span class="doxyHighlight">); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2227</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> isLangChar   = [&amp;](</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> c==dot || isAlphaChar(c); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2228</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// rules: at least 3 ~~~, end of the block same amount of ~~~'s, otherwise</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2229</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// return FALSE</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2230</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2231</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> indent=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2232</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startTildes=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2233</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2234</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) indent++,i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2235</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (indent&gt;=refIndent+4)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2236</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2237</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result=false: content is part of code block indent={} refIndent={}"</span><span class="doxyHighlight">,indent,refIndent);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2238</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2239</span><span class="doxyLineContent"><span class="doxyHighlight">  } </span><span class="doxyHighlightComment">// part of code block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2240</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> tildaChar=</span><span class="doxyHighlightCharLiteral">'~'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2241</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">'`'</span><span class="doxyHighlight">) tildaChar=</span><span class="doxyHighlightCharLiteral">'`'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2242</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==tildaChar) startTildes++,i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2243</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (startTildes&lt;3)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2244</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2245</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result=false: no fence marker found #tildes={}"</span><span class="doxyHighlight">,startTildes);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2246</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2247</span><span class="doxyLineContent"><span class="doxyHighlight">  } </span><span class="doxyHighlightComment">// not enough tildes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2248</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// extract .py from ```{.py} ... ```</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2249</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2250</span><span class="doxyLineContent"><span class="doxyHighlight">    i++; </span><span class="doxyHighlightComment">// skip over {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2251</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i] == dot) i++; </span><span class="doxyHighlightComment">// skip over initial dot</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2252</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> startLang=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2253</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; (data[i]!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight"> &amp;&amp; data[i]!=</span><span class="doxyHighlightCharLiteral">'}'</span><span class="doxyHighlight">)) i++; </span><span class="doxyHighlightComment">// find matching }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2254</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">'}'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2255</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2256</span><span class="doxyLineContent"><span class="doxyHighlight">      lang = data.substr(startLang,i-startLang);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2257</span><span class="doxyLineContent"><span class="doxyHighlight">      i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2258</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2259</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// missing closing bracket, treat `{` as part of the content</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2260</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2261</span><span class="doxyLineContent"><span class="doxyHighlight">      i=startLang-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2262</span><span class="doxyLineContent"><span class="doxyHighlight">      lang=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2263</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2264</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2265</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; isLangChar(data[i])) </span><span class="doxyHighlightComment">/// extract python or .py from ```python...``` or ```.py...```</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2266</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2267</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i] == dot) i++; </span><span class="doxyHighlightComment">// skip over initial dot</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2268</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> startLang=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2269</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; isAlphaChar(data[i])) </span><span class="doxyHighlightComment">//check first character of language specifier</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2270</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2271</span><span class="doxyLineContent"><span class="doxyHighlight">      i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2272</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; isAlphaNChar(data[i])) i++; </span><span class="doxyHighlightComment">// find end of language specifier</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2273</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2274</span><span class="doxyLineContent"><span class="doxyHighlight">    lang = data.substr(startLang,i-startLang);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2275</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2276</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// no language specified</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2277</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2278</span><span class="doxyLineContent"><span class="doxyHighlight">    lang=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2279</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2280</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2281</span><span class="doxyLineContent"><span class="doxyHighlight">  start=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2282</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2283</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2284</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==tildaChar)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2285</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2286</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2287</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> endTildes=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2288</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==tildaChar) endTildes++,i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2289</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2290</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2291</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (endTildes==startTildes)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2292</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2293</span><span class="doxyLineContent"><span class="doxyHighlight">          offset=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2294</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result=true: found end marker at offset {} lang='{}'"</span><span class="doxyHighlight">,offset,lang);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2295</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2296</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2297</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2298</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2299</span><span class="doxyLineContent"><span class="doxyHighlight">    i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2300</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2301</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result=false: no end marker found lang={}'"</span><span class="doxyHighlight">,lang);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2302</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2303</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/markdown/private/#a9835402c2d15b122de1c3ba4180ebd58">Markdown::Private::processBlocks</a> and <a href="/web-doxygen/docs/api/structs/markdown/private/#a9792322da9173be90556ef009d37afa4">Markdown::Private::processQuotations</a>.</p>

</div>
</div>

### isHRuler() {#ad1f1abe1811f3c45c5b4ee867c15989f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isHRuler (std::string_view data)</td>
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



<p>Definition at line 1960 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad1f1abe1811f3c45c5b4ee867c15989f">1960</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ad1f1abe1811f3c45c5b4ee867c15989f">isHRuler</a>(std::string_view data)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1961</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1962</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}'"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1963</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1964</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1965</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (size&gt;0 &amp;&amp; data[size-1]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) size--; </span><span class="doxyHighlightComment">// ignore newline character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1966</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1967</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&gt;=size) { <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result=false: empty line"</span><span class="doxyHighlight">); </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">; } </span><span class="doxyHighlightComment">// empty line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1968</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c=data[i];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1969</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c!=</span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'_'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1970</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1971</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result=false: {} is not a hrule character"</span><span class="doxyHighlight">,c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1972</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// not a hrule character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1973</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1974</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> n=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1975</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1976</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1977</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1978</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1979</span><span class="doxyLineContent"><span class="doxyHighlight">      n++; </span><span class="doxyHighlightComment">// count rule character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1980</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1981</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]!=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1982</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1983</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result=false: line contains non hruler characters"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1984</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// line contains non hruler characters</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1985</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1986</span><span class="doxyLineContent"><span class="doxyHighlight">    i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1987</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1988</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,n&gt;=3);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1989</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> n&gt;=3; </span><span class="doxyHighlightComment">// at least 3 characters needed for a hruler</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1990</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/markdown/private/#a2a97ed987f163573d91e6a46363c99de">Markdown::Private::writeBlockQuote</a> and <a href="/web-doxygen/docs/api/structs/markdown/private/#af7ceebe6b90c368816a6d9bd0ca501c0">Markdown::Private::writeOneLineHeaderOrRuler</a>.</p>

</div>
</div>

### isLinkRef() {#a3712f14d18ec5d547f7c55413abdb9fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t isLinkRef (std::string_view data, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; refid, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; link, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title)</td>
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

<p>returns end of the link ref if this is indeed a link reference.</p>

<p>Definition at line 1871 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3712f14d18ec5d547f7c55413abdb9fb">1871</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a3712f14d18ec5d547f7c55413abdb9fb">isLinkRef</a>(std::string_view data, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;refid, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;link, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1872</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1873</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}'"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1874</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1875</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// format: start with [some text]:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1876</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1877</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1878</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&gt;=size || data[i]!=</span><span class="doxyHighlightCharLiteral">'['</span><span class="doxyHighlight">) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1879</span><span class="doxyLineContent"><span class="doxyHighlight">  i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1880</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> refIdStart=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1881</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight"> &amp;&amp; data[i]!=</span><span class="doxyHighlightCharLiteral">']'</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1882</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&gt;=size || data[i]!=</span><span class="doxyHighlightCharLiteral">']'</span><span class="doxyHighlight">) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1883</span><span class="doxyLineContent"><span class="doxyHighlight">  refid = data.substr(refIdStart,i-refIdStart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1884</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (refid.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1885</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"refid found {}"</span><span class="doxyHighlight">,refid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1886</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("  isLinkRef: found refid='%s'\n",qPrint(refid));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1887</span><span class="doxyLineContent"><span class="doxyHighlight">  i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1888</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&gt;=size || data[i]!=</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight">) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1889</span><span class="doxyLineContent"><span class="doxyHighlight">  i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1890</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1891</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// format: whitespace* \n? whitespace* (&lt;url&gt; | url)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1892</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1893</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1894</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1895</span><span class="doxyLineContent"><span class="doxyHighlight">    i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1896</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1897</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1898</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&gt;=size) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1899</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1900</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1901</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> linkStart=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1902</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]!=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> &amp;&amp; data[i]!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1903</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> linkEnd=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1904</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1905</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (linkStart==linkEnd) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; } </span><span class="doxyHighlightComment">// empty link</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1906</span><span class="doxyLineContent"><span class="doxyHighlight">  link = data.substr(linkStart,linkEnd-linkStart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1907</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"link found {}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(link));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1908</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (link==</span><span class="doxyHighlightStringLiteral">"@ref"</span><span class="doxyHighlight"> || link==</span><span class="doxyHighlightStringLiteral">"\\ref"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1909</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1910</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> argStart=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1911</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight"> &amp;&amp; data[i]!=</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1912</span><span class="doxyLineContent"><span class="doxyHighlight">    link+=data.substr(argStart,i-argStart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1913</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1914</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1915</span><span class="doxyLineContent"><span class="doxyHighlight">  title.<a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">clear</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1916</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1917</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// format: (whitespace* \n? whitespace* ( 'title' | "title" | (title) ))?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1918</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/vhdlparser/parseexception-h/#a55b81f273444186ad83e1087f9a3706d">eol</a>=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1919</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1920</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1921</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1922</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/vhdlparser/parseexception-h/#a55b81f273444186ad83e1087f9a3706d">eol</a>=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1923</span><span class="doxyLineContent"><span class="doxyHighlight">    i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1924</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1925</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1926</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&gt;=size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1927</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1928</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}: end of isLinkRef while looking for title"</span><span class="doxyHighlight">,i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1929</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> i; </span><span class="doxyHighlightComment">// end of buffer while looking for the optional title</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1930</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1931</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1932</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = data[i];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1933</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// optional title present?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1934</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1935</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("  start of title found! char='%c'\n",c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1936</span><span class="doxyLineContent"><span class="doxyHighlight">    i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1937</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">) c=</span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// replace c by end character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1938</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> titleStart=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1939</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// search for end of the line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1940</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1941</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/vhdlparser/parseexception-h/#a55b81f273444186ad83e1087f9a3706d">eol</a> = i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1942</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1943</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// search back to matching character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1944</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=i-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1945</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>&gt;titleStart &amp;&amp; data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>]!=c) <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1946</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>&gt;titleStart)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1947</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1948</span><span class="doxyLineContent"><span class="doxyHighlight">      title = data.substr(titleStart,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-titleStart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1949</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1950</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"title found {}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(title));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1951</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1952</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1953</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("end of isLinkRef: i=%d size=%d data[i]='%c' eol=%d\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1954</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//    i,size,data[i],eol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1955</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">      (i&gt;=size)       { <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,i);   </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> i; }    </span><span class="doxyHighlightComment">// end of buffer while ref id was found</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1956</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/vhdlparser/parseexception-h/#a55b81f273444186ad83e1087f9a3706d">eol</a>&gt;0)         { <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/vhdlparser/parseexception-h/#a55b81f273444186ad83e1087f9a3706d">eol</a>); </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/vhdlparser/parseexception-h/#a55b81f273444186ad83e1087f9a3706d">eol</a>; }  </span><span class="doxyHighlightComment">// end of line while ref id was found</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1957</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;                            </span><span class="doxyHighlightComment">// invalid link ref</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1958</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">QCString::clear</a>, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="/web-doxygen/docs/api/files/vhdlparser/parseexception-h/#a55b81f273444186ad83e1087f9a3706d">eol</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/markdown/private/#a9835402c2d15b122de1c3ba4180ebd58">Markdown::Private::processBlocks</a>.</p>

</div>
</div>

### isListMarker() {#ad0a6b598945a869cd184d17fe1f16812}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t isListMarker (std::string_view data)</td>
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



<p>Definition at line 2182 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad0a6b598945a869cd184d17fe1f16812">2182</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#ad0a6b598945a869cd184d17fe1f16812">isListMarker</a>(std::string_view data)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2183</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2184</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}'"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2185</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> normalIndent = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2186</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (normalIndent&lt;data.size() &amp;&amp; data[normalIndent]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) normalIndent++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2187</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> listIndent = <a href="#a515c2b44ec8500cdb661ff5ab86c60af">computeIndentExcludingListMarkers</a>(data);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2188</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> result = listIndent&gt;normalIndent ? listIndent : 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2189</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2190</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2191</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="#a515c2b44ec8500cdb661ff5ab86c60af">computeIndentExcludingListMarkers</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/markdown/private/#a9835402c2d15b122de1c3ba4180ebd58">Markdown::Private::processBlocks</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9792322da9173be90556ef009d37afa4">Markdown::Private::processQuotations</a> and <a href="/web-doxygen/docs/api/structs/markdown/private/#a2a97ed987f163573d91e6a46363c99de">Markdown::Private::writeBlockQuote</a>.</p>

</div>
</div>

### isNewline() {#afc4de25503fad3bbfadba71ff6e7581a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t isNewline (std::string_view data)</td>
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



<p>Definition at line 207 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afc4de25503fad3bbfadba71ff6e7581a">207</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#afc4de25503fad3bbfadba71ff6e7581a">isNewline</a>(std::string_view data)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// normal newline</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[0] == </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// artificial new line from ^^ in ALIASES</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>(data,</span><span class="doxyHighlightStringLiteral">"\\ilinebr"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> (data.size()&gt;8 &amp;&amp; data[8]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) ? 9 : 8; </span><span class="doxyHighlightComment">// also count space after \ilinebr if present</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/markdown/private/#aad2fb530e3d19a77de38a8c1b633b786">Markdown::Private::findEndOfLine</a>, <a href="#a90640de61c785c42e3dc3787610b18eb">findTableColumns</a> and <a href="#a76c8e357497a35b016ee0289e26ee0dd">isCodeBlock</a>.</p>

</div>
</div>

### isOtherPage() {#a127b59cfb20342292c23547477181f9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isOtherPage (std::string_view data)</td>
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



<p>Definition at line 3437 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a127b59cfb20342292c23547477181f9d">3437</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a127b59cfb20342292c23547477181f9d">isOtherPage</a>(std::string_view data)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3438</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3439</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define OPC(x) if (literal_at(data,#x " ") || literal_at(data,#x "\n")) return true</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3440</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a644d79c9440b660abd83934b8304b21b">OPC</a>(dir);      <a href="#a644d79c9440b660abd83934b8304b21b">OPC</a>(defgroup);  <a href="#a644d79c9440b660abd83934b8304b21b">OPC</a>(addtogroup); <a href="#a644d79c9440b660abd83934b8304b21b">OPC</a>(weakgroup); <a href="#a644d79c9440b660abd83934b8304b21b">OPC</a>(ingroup);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3441</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a644d79c9440b660abd83934b8304b21b">OPC</a>(fn);       <a href="#a644d79c9440b660abd83934b8304b21b">OPC</a>(property);  <a href="#a644d79c9440b660abd83934b8304b21b">OPC</a>(</span><span class="doxyHighlightKeyword">typedef</span><span class="doxyHighlight">);    <a href="#a644d79c9440b660abd83934b8304b21b">OPC</a>(var);       <a href="#a644d79c9440b660abd83934b8304b21b">OPC</a>(def);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3442</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a644d79c9440b660abd83934b8304b21b">OPC</a>(</span><span class="doxyHighlightKeyword">enum</span><span class="doxyHighlight">);     <a href="#a644d79c9440b660abd83934b8304b21b">OPC</a>(</span><span class="doxyHighlightKeyword">namespace</span><span class="doxyHighlight">); <a href="#a644d79c9440b660abd83934b8304b21b">OPC</a>(</span><span class="doxyHighlightKeyword">class</span><span class="doxyHighlight">);      <a href="#a644d79c9440b660abd83934b8304b21b">OPC</a>(</span><span class="doxyHighlightKeyword">concept</span><span class="doxyHighlight">);   <a href="#a644d79c9440b660abd83934b8304b21b">OPC</a>(module);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3443</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a644d79c9440b660abd83934b8304b21b">OPC</a>(protocol); <a href="#a644d79c9440b660abd83934b8304b21b">OPC</a>(category);  <a href="#a644d79c9440b660abd83934b8304b21b">OPC</a>(</span><span class="doxyHighlightKeyword">union</span><span class="doxyHighlight">);      <a href="#a644d79c9440b660abd83934b8304b21b">OPC</a>(</span><span class="doxyHighlightKeyword">struct</span><span class="doxyHighlight">);    <a href="#a644d79c9440b660abd83934b8304b21b">OPC</a>(interface);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3444</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a644d79c9440b660abd83934b8304b21b">OPC</a>(idlexcept);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3445</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#undef OPC</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3446</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3447</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3448</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a644d79c9440b660abd83934b8304b21b">OPC</a>.</p>


<p>Referenced by <a href="#a9ef42eb1068c60ccbe59ef0024ed1c90">isExplicitPage</a>.</p>

</div>
</div>

### isTableBlock() {#aefadebc5df285d25ef8121a87639323e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isTableBlock (std::string_view data)</td>
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

<p>Returns TRUE iff data points to the start of a table block.</p>

<p>Definition at line 2439 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aefadebc5df285d25ef8121a87639323e">2439</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aefadebc5df285d25ef8121a87639323e">isTableBlock</a>(std::string_view data)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2440</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2441</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}'"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2442</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> cc0=0, start=0, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2443</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2444</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// the first line should have at least two columns separated by '|'</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2445</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i = <a href="#a90640de61c785c42e3dc3787610b18eb">findTableColumns</a>(data,start,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>,cc0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2446</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&gt;=data.size() || cc0&lt;1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2447</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2448</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result=false: no |'s in the header"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2449</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2450</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2451</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2452</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> cc1 = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2453</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> ret = <a href="#a90640de61c785c42e3dc3787610b18eb">findTableColumns</a>(data.substr(i),start,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>,cc1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2454</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> j=i+start;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2455</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// separator line should consist of |, - and : and spaces only</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2456</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (j&lt;=<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>+i)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2457</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2458</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[j]!=</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight"> &amp;&amp; data[j]!=</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight"> &amp;&amp; data[j]!=</span><span class="doxyHighlightCharLiteral">'|'</span><span class="doxyHighlight"> &amp;&amp; data[j]!=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2459</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2460</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result=false: invalid character '{}'"</span><span class="doxyHighlight">,data[j]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2461</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>; </span><span class="doxyHighlightComment">// invalid characters in table separator</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2462</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2463</span><span class="doxyLineContent"><span class="doxyHighlight">    j++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2464</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2465</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cc1!=cc0) </span><span class="doxyHighlightComment">// number of columns should be same as previous line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2466</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2467</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result=false: different number of columns as previous line {}!={}"</span><span class="doxyHighlight">,cc1,cc0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2468</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2469</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2470</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2471</span><span class="doxyLineContent"><span class="doxyHighlight">  i+=ret; </span><span class="doxyHighlightComment">// goto next line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2472</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> cc2 = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2473</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a90640de61c785c42e3dc3787610b18eb">findTableColumns</a>(data.substr(i),start,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>,cc2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2474</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2475</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,cc1==cc2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2476</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> cc1==cc2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2477</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a90640de61c785c42e3dc3787610b18eb">findTableColumns</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/markdown/private/#a9835402c2d15b122de1c3ba4180ebd58">Markdown::Private::processBlocks</a>.</p>

</div>
</div>

### markdownFileNameToId() {#a0a158f67dd586087dac0e968ea384f09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString markdownFileNameToId (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>processes string <em>s</em> and converts markdown into doxygen/html commands.</p>

<p>Definition at line 3600 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0a158f67dd586087dac0e968ea384f09">3600</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="/web-doxygen/docs/api/files/src/markdown-h/#a0a158f67dd586087dac0e968ea384f09">markdownFileNameToId</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3601</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3602</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"fileName={}"</span><span class="doxyHighlight">,fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3603</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string absFileName = <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a>(fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()).<a href="/web-doxygen/docs/api/classes/fileinfo/#af69e3949475014dcdbd504d742bdf270">absFilePath</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3604</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseFn  = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8c90a81fbaf02ad9af7387f3ed1c20c1">stripFromPath</a>(absFileName.c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3605</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = baseFn.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightCharLiteral">'.'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3606</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i!=-1) baseFn = baseFn.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3607</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseName = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a588c599deed30414ade1ed583a11827d">escapeCharsInString</a>(baseFn,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3608</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("markdownFileNameToId(%s)=md_%s\n",qPrint(fileName),qPrint(baseName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3609</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> res = </span><span class="doxyHighlightStringLiteral">"md_"</span><span class="doxyHighlight">+baseName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3610</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,res);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3611</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> res;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3612</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/fileinfo/#af69e3949475014dcdbd504d742bdf270">FileInfo::absFilePath</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a588c599deed30414ade1ed583a11827d">escapeCharsInString</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8c90a81fbaf02ad9af7387f3ed1c20c1">stripFromPath</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docref/#acb234cd7235b7c61a4c6f9dfd0cd586b">DocRef::DocRef</a>, <a href="/web-doxygen/docs/api/classes/docsecrefitem/#a35c9d6d150e7faaa88ea9ddfbeadb777">DocSecRefItem::parse</a> and <a href="/web-doxygen/docs/api/classes/markdownoutlineparser/#a0cb95204f0f91c085e6a9808efb2ebdc">MarkdownOutlineParser::parseInput</a>.</p>

</div>
</div>

### markersToAlignment() {#a53933ee56e6d62357cc60bde3156f544}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Alignment markersToAlignment (bool leftMarker, bool rightMarker)</td>
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

<p>helper function to convert presence of left and/or right alignment markers to an alignment value</p>

<p>Definition at line 292 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a53933ee56e6d62357cc60bde3156f544">292</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="#acdfaca60ec19c0265bac2692d7982726">Alignment</a> <a href="#a53933ee56e6d62357cc60bde3156f544">markersToAlignment</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> leftMarker,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> rightMarker)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (leftMarker &amp;&amp; rightMarker)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acdfaca60ec19c0265bac2692d7982726afed76d6718c0a44a25c5e19ae8fb51d1">AlignCenter</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (leftMarker)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acdfaca60ec19c0265bac2692d7982726a291bdf1a2284d5648efc75ee78fbeb4c">AlignLeft</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rightMarker)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acdfaca60ec19c0265bac2692d7982726a4758d977046d9c084a0eaf7434fd29e1">AlignRight</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acdfaca60ec19c0265bac2692d7982726a4258b9785acff3438d08d41ddb4439d9">AlignNone</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#acdfaca60ec19c0265bac2692d7982726afed76d6718c0a44a25c5e19ae8fb51d1">AlignCenter</a>, <a href="#acdfaca60ec19c0265bac2692d7982726a291bdf1a2284d5648efc75ee78fbeb4c">AlignLeft</a>, <a href="#acdfaca60ec19c0265bac2692d7982726a4258b9785acff3438d08d41ddb4439d9">AlignNone</a> and <a href="#acdfaca60ec19c0265bac2692d7982726a4758d977046d9c084a0eaf7434fd29e1">AlignRight</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/markdown/private/#a21b82aade2e5a369ec438f0cd49f8107">Markdown::Private::writeTableBlock</a>.</p>

</div>
</div>

### skipOverFileAndLineCommands() {#ae22648d9504bbec4b64a0c33260fbe4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool skipOverFileAndLineCommands (std::string_view data, size_t indent, size_t &amp; offset, std::string &amp; location)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2876 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae22648d9504bbec4b64a0c33260fbe4f">2876</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae22648d9504bbec4b64a0c33260fbe4f">skipOverFileAndLineCommands</a>(std::string_view data,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> indent,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> &amp;offset,std::string &amp;location)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2877</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2878</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i = offset;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2879</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2880</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;data.size() &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2881</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>(data.substr(i),</span><span class="doxyHighlightStringLiteral">"\\ifile \""</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2882</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2883</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> locStart = i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2884</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&gt;offset) locStart--; </span><span class="doxyHighlightComment">// include the space before \ifile</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2885</span><span class="doxyLineContent"><span class="doxyHighlight">    i+=8;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2886</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> found=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2887</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i+9&lt;size &amp;&amp; data[i]!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2888</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2889</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>(data.substr(i),</span><span class="doxyHighlightStringLiteral">"\\ilinebr "</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2890</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2891</span><span class="doxyLineContent"><span class="doxyHighlight">        found=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2892</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2893</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2894</span><span class="doxyLineContent"><span class="doxyHighlight">      i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2895</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2896</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (found)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2897</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2898</span><span class="doxyLineContent"><span class="doxyHighlight">      i+=9;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2899</span><span class="doxyLineContent"><span class="doxyHighlight">      location=data.substr(locStart,i-locStart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2900</span><span class="doxyLineContent"><span class="doxyHighlight">      location+=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2901</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (indent&gt;0 &amp;&amp; i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) i++,indent--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2902</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2903</span><span class="doxyLineContent"><span class="doxyHighlight">      offset = i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2904</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2905</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2906</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2907</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2908</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/markdown/private/#a79fd3fae285ba1f1beeb84c8e858bf46">Markdown::Private::writeCodeBlock</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### codeBlockIndent {#a918fa8a25e6bc30b364b55bc19a5dafd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const size_t codeBlockIndent = 4</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a918fa8a25e6bc30b364b55bc19a5dafd">201</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a918fa8a25e6bc30b364b55bc19a5dafd">codeBlockIndent</a> = 4;</span></span></div>

</div>


<p>Referenced by <a href="#a32f3ae19472e55905bc21e27835568d5">isBlockQuote</a>, <a href="#a76c8e357497a35b016ee0289e26ee0dd">isCodeBlock</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9835402c2d15b122de1c3ba4180ebd58">Markdown::Private::processBlocks</a> and <a href="/web-doxygen/docs/api/structs/markdown/private/#a79fd3fae285ba1f1beeb84c8e858bf46">Markdown::Private::writeCodeBlock</a>.</p>

</div>
</div>

### g\_doxy\_nbsp {#a5411339961a1e433bf9b59570c97fa6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* g_doxy_nbsp = "&amp;_doxy_nbsp;"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5411339961a1e433bf9b59570c97fa6a">200</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a5411339961a1e433bf9b59570c97fa6a">g_doxy_nbsp</a> = </span><span class="doxyHighlightStringLiteral">"&amp;_doxy_nbsp;"</span><span class="doxyHighlight">;  </span><span class="doxyHighlightComment">// doxygen escape command for UTF-8 nbsp</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/markdown/private/#a681582d0e894782b9509baa541931151">Markdown::Private::addStrEscapeUtf8Nbsp</a> and <a href="/web-doxygen/docs/api/classes/markdown/#ad40652cc4db61282f2b0ef5202927d10">Markdown::process</a>.</p>

</div>
</div>

### g\_quotationHeaderMap {#acb9b9cc222a09dc4b31c86cf18cd68df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::unordered_map&lt;std::string,std::string&gt; g_quotationHeaderMap</td>
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
<div class="doxyVerbatim">= {
  { "[!note]",      "\\note"      },
  { "[!warning]",   "\\warning"   },
  { "[!tip]",       "\\remark"    },
  { "[!caution]",   "\\attention" },
  { "[!important]", "\\important" }
}
</div>
</dd>
</dl>

<p>Definition at line 2749 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acb9b9cc222a09dc4b31c86cf18cd68df">2749</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::unordered_map&lt;std::string,std::string&gt; <a href="#acb9b9cc222a09dc4b31c86cf18cd68df">g_quotationHeaderMap</a> = {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2750</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// GitHub style   Doxygen command</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2751</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"[!note]"</span><span class="doxyHighlight">,      </span><span class="doxyHighlightStringLiteral">"\\note"</span><span class="doxyHighlight">      },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2752</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"[!warning]"</span><span class="doxyHighlight">,   </span><span class="doxyHighlightStringLiteral">"\\warning"</span><span class="doxyHighlight">   },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2753</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"[!tip]"</span><span class="doxyHighlight">,       </span><span class="doxyHighlightStringLiteral">"\\remark"</span><span class="doxyHighlight">    },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2754</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"[!caution]"</span><span class="doxyHighlight">,   </span><span class="doxyHighlightStringLiteral">"\\attention"</span><span class="doxyHighlight"> },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2755</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"[!important]"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"\\important"</span><span class="doxyHighlight"> }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2756</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/markdown/private/#a2a97ed987f163573d91e6a46363c99de">Markdown::Private::writeBlockQuote</a>.</p>

</div>
</div>

### g\_utf8\_nbsp {#ab90a38f35e109b0e55a693490232d93d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* g_utf8_nbsp = "\xc2\xa0"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 199 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab90a38f35e109b0e55a693490232d93d">199</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#ab90a38f35e109b0e55a693490232d93d">g_utf8_nbsp</a> = </span><span class="doxyHighlightStringLiteral">"\xc2\xa0"</span><span class="doxyHighlight">;      </span><span class="doxyHighlightComment">// UTF-8 nbsp</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/markdown/private/#a681582d0e894782b9509baa541931151">Markdown::Private::addStrEscapeUtf8Nbsp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### AUTO\_TRACE {#a210042a14f3a393be09c743c219126ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define AUTO_TRACE(...)&nbsp;&nbsp;&nbsp;(void)0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a210042a14f3a393be09c743c219126ae">61</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define AUTO_TRACE(...)      (void)0</span></span></div>

</div>


<p>Referenced by <a href="#a3d4cb7f7e85f41df2eab7827e3bec33e">escapeDoubleQuotes</a>, <a href="#a5ba50f3a46a2d635f06fbc600356ee4a">escapeSpecialChars</a> and <a href="#ad5f8f274225faad69b969f4828376f06">getFilteredImageAttributes</a>.</p>

</div>
</div>

### AUTO\_TRACE\_ADD {#a05be586784f268b947ad777aa316c4e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define AUTO_TRACE_ADD(...)&nbsp;&nbsp;&nbsp;(void)0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a05be586784f268b947ad777aa316c4e6">62</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define AUTO_TRACE_ADD(...)  (void)0</span></span></div>

</div>

</div>
</div>

### AUTO\_TRACE\_EXIT {#a81912d2a3d12aab7a9e546e5299e2e09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define AUTO_TRACE_EXIT(...)&nbsp;&nbsp;&nbsp;(void)0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a81912d2a3d12aab7a9e546e5299e2e09">63</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define AUTO_TRACE_EXIT(...) (void)0</span></span></div>

</div>


<p>Referenced by <a href="#a3d4cb7f7e85f41df2eab7827e3bec33e">escapeDoubleQuotes</a>, <a href="#a5ba50f3a46a2d635f06fbc600356ee4a">escapeSpecialChars</a> and <a href="#ad5f8f274225faad69b969f4828376f06">getFilteredImageAttributes</a>.</p>

</div>
</div>

### extraChar {#aebe67bf622b3e6fa702be02ee5087910}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define extraChar(c)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  (c=='-' || c=='+' || c=='!' || \
   c=='?' || c=='$' || c=='@' || \
   c=='&amp;' || c=='*' || c=='_' || c=='%' || \
   c=='[' || c=='(' || c=='.' || \
   c=='&gt;' || c==':' || c==',' || \
   c==';' || c=='\'' || c=='"' || c=='`')
</div>
</dd>
</dl>

<p>Definition at line 84 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aebe67bf622b3e6fa702be02ee5087910">84</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define extraChar(c) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  (c=='-' || c=='+' || c=='!' || \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">   c=='?' || c=='$' || c=='@' || \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">   c=='&amp;' || c=='*' || c=='_' || c=='%' || \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">   c=='[' || c=='(' || c=='.' || \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">   c=='&gt;' || c==':' || c==',' || \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">   c==';' || c=='\'' || c=='"' || c=='`')</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/markdown/private/#a9ac768dc126226996971e96ef20923aa">Markdown::Private::processEmphasis</a>.</p>

</div>
</div>

### ignoreCloseEmphChar {#acb2def26524ecd4c96d000b854dee831}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ignoreCloseEmphChar(c, cn)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  (c=='('  || c=='{' || c=='[' || (c=='&lt;' &amp;&amp; cn!='/') || \
   c=='\\' || \
   c=='@')
</div>
</dd>
</dl>

<p>Definition at line 100 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acb2def26524ecd4c96d000b854dee831">100</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define ignoreCloseEmphChar(c,cn) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  (c=='('  || c=='{' || c=='[' || (c=='&lt;' &amp;&amp; cn!='/') || \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">   c=='\\' || \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">   c=='@')</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/markdown/private/#a5b661698b94e4b37748ee38025784690">Markdown::Private::findEmphasisChar</a>.</p>

</div>
</div>

### isIdChar {#a243e6edb7617162067edc19f3f20bdb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define isIdChar(c)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  ((c&gt;='a' &amp;&amp; c&lt;='z') || \
   (c&gt;='A' &amp;&amp; c&lt;='Z') || \
   (c&gt;='0' &amp;&amp; c&lt;='9') || \
   (static_cast&lt;unsigned char&gt;(c)&gt;=0x80))
</div>
</dd>
</dl>

<p>Definition at line 77 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a243e6edb7617162067edc19f3f20bdb9">77</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define isIdChar(c) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  ((c&gt;='a' &amp;&amp; c&lt;='z') || \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">   (c&gt;='A' &amp;&amp; c&lt;='Z') || \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">   (c&gt;='0' &amp;&amp; c&lt;='9') || \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">   (static_cast&lt;unsigned char&gt;(c)&gt;=0x80)) </span><span class="doxyHighlightComment">// unicode characters</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/markdown/private/#a5b661698b94e4b37748ee38025784690">Markdown::Private::findEmphasisChar</a>, <a href="/web-doxygen/docs/api/classes/reg/ex/private/#acb10ddb380fa79ce0a346360feffce11">reg::Ex::Private::matchAt</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a42dc4e1d481af0574e750df55678d54d">Markdown::Private::processCodeSpan</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9ac768dc126226996971e96ef20923aa">Markdown::Private::processEmphasis</a> and <a href="/web-doxygen/docs/api/structs/markdown/private/#aa4f4085dfd3e73ae354c7cfd6fa69faf">Markdown::Private::processHtmlTagWrite</a>.</p>

</div>
</div>

### isLiTag {#a8651540cb26651ce580fdc9504e7fdf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define isLiTag(i)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">   (data[(i)]=='&lt;' &amp;&amp; \
   (data[(i)+1]=='l' || data[(i)+1]=='L') &amp;&amp; \
   (data[(i)+2]=='i' || data[(i)+2]=='I') &amp;&amp; \
   (data[(i)+3]=='&gt;'))
</div>
</dd>
</dl>

<p>Definition at line 2105 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8651540cb26651ce580fdc9504e7fdf2">2105</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define isLiTag(i) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2106</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">   (data[(i)]=='&lt;' &amp;&amp; \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2107</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">   (data[(i)+1]=='l' || data[(i)+1]=='L') &amp;&amp; \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2108</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">   (data[(i)+2]=='i' || data[(i)+2]=='I') &amp;&amp; \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2109</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">   (data[(i)+3]=='&gt;'))</span></span></div>

</div>


<p>Referenced by <a href="#a515c2b44ec8500cdb661ff5ab86c60af">computeIndentExcludingListMarkers</a>.</p>

</div>
</div>

### isOpenEmphChar {#acda15964dfc7b413ab5abb3fca10a1ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define isOpenEmphChar(c)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  (c=='\n' || c==' ' || c=='\'' || c=='&lt;' || \
   c=='&gt;'  || c=='{' || c=='('  || c=='[' || \
   c==','  || c==':' || c==';')
</div>
</dd>
</dl>

<p>Definition at line 93 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acda15964dfc7b413ab5abb3fca10a1ef">93</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define isOpenEmphChar(c) \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  (c=='\n' || c==' ' || c=='\'' || c=='&lt;' || \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">   c=='&gt;'  || c=='{' || c=='('  || c=='[' || \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">   c==','  || c==':' || c==';')</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/markdown/private/#a9ac768dc126226996971e96ef20923aa">Markdown::Private::processEmphasis</a>.</p>

</div>
</div>

### OPC {#a644d79c9440b660abd83934b8304b21b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OPC(x)&nbsp;&nbsp;&nbsp;if (<a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>(data,#x " ") || <a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>(data,#x "\n")) return true</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3439 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<p>Referenced by <a href="#a127b59cfb20342292c23547477181f9d">isOtherPage</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
