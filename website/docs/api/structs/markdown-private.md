---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/markdown/private
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `Private` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct Markdown::Private { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38ce2a429b8c4a268507157a45cac671">Action_t</a> = std::function&lt; int(std::string_view, size_t)&gt;</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8b74ada051582d23d31e3290ce5e917">Private</a> (const QCString &amp;fn, int line, int indent)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9792322da9173be90556ef009d37afa4">processQuotations</a> (std::string_view data, size_t refIndent)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9835402c2d15b122de1c3ba4180ebd58">processBlocks</a> (std::string_view data, size_t indent)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d7d4814ead5c919439c6b2d681e2ce7">isBlockCommand</a> (std::string_view data, size_t offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e37305849fa544aff8f399a6f41c7b1">isSpecialCommand</a> (std::string_view data, size_t offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad2fb530e3d19a77de38a8c1b633b786">findEndOfLine</a> (std::string_view data, size_t offset)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4f4085dfd3e73ae354c7cfd6fa69faf">processHtmlTagWrite</a> (std::string_view data, size_t offset, bool doWrite)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Process a HTML tag. <a href="#aa4f4085dfd3e73ae354c7cfd6fa69faf">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ef2d648f867a25fac44f095b89630c6">processHtmlTag</a> (std::string_view data, size_t offset)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ac768dc126226996971e96ef20923aa">processEmphasis</a> (std::string_view data, size_t offset)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bb20b07bce14eca215477b9ec05adbd">processEmphasis1</a> (std::string_view data, char c)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
process single emphasis <a href="#a0bb20b07bce14eca215477b9ec05adbd">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbb763f2449b932ef3468560e30a0478">processEmphasis2</a> (std::string_view data, char c)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
process double emphasis <a href="#abbb763f2449b932ef3468560e30a0478">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4041a1e946c4402894bfff49b611e63b">processEmphasis3</a> (std::string_view data, char c)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Parsing triple emphasis. <a href="#a4041a1e946c4402894bfff49b611e63b">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adafbef72995b1327272b82a2b2075480">processNmdash</a> (std::string_view data, size_t offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Process ndash and mdashes. <a href="#adafbef72995b1327272b82a2b2075480">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f211ac431de2f23ca4874c125ab1551">processQuoted</a> (std::string_view data, size_t offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Process quoted section "...", can contain one embedded newline. <a href="#a0f211ac431de2f23ca4874c125ab1551">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42dc4e1d481af0574e750df55678d54d">processCodeSpan</a> (std::string_view data, size_t offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<code> ` </code> parsing a code span (assuming codespan != 0) <a href="#a42dc4e1d481af0574e750df55678d54d">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43b1695a69a83037471e5445c7c940ce">processSpecialCommand</a> (std::string_view data, size_t offset)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b99b7f5084eb08d7ffe43f3fbe79d69">processLink</a> (std::string_view data, size_t offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b661698b94e4b37748ee38025784690">findEmphasisChar</a> (std::string_view, char c, size_t c_size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
looks for the next emph char, skipping other constructs, and stopping when either it is found, or we are at the end of a paragraph. <a href="#a5b661698b94e4b37748ee38025784690">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a681582d0e894782b9509baa541931151">addStrEscapeUtf8Nbsp</a> (std::string_view data)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0a9e3273eb76713a9e197d5be61e11a">processInline</a> (std::string_view data)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1213861d8af699057686e457bce66509">writeMarkdownImage</a> (std::string_view fmt, bool inline_img, bool explicitTitle, const QCString &amp;title, const QCString &amp;content, const QCString &amp;link, const QCString &amp;attributes, const FileDef *fd)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5628c6052a120856d53921f8746d0251">isHeaderline</a> (std::string_view data, bool allowAdjustLevel)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
returns whether the line is a setext-style hdr underline <a href="#a5628c6052a120856d53921f8746d0251">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8a42c32241bc89aa626ce55c23b7df5">isAtxHeader</a> (std::string_view data, QCString &amp;header, QCString &amp;id, bool allowAdjustLevel, bool *pIsIdGenerated=nullptr)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7ceebe6b90c368816a6d9bd0ca501c0">writeOneLineHeaderOrRuler</a> (std::string_view data)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a494fc3fc6c848a37caa06e5d85854ffe">writeFencedCodeBlock</a> (std::string_view data, std::string_view lang, size_t blockStart, size_t blockEnd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a97ed987f163573d91e6a46363c99de">writeBlockQuote</a> (std::string_view data)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79fd3fae285ba1f1beeb84c8e858bf46">writeCodeBlock</a> (std::string_view, size_t refIndent)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21b82aade2e5a369ec438f0cd49f8107">writeTableBlock</a> (std::string_view data)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46231fc8d72391f38170f184dd956ed1">extractTitleId</a> (QCString &amp;title, int level, bool *pIsIdGenerated=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; std::string, <a href="/web-doxygen/docs/api/structs/markdown/private/linkref">LinkRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dd95f5138a9eb830f708bf8f669e89b">linkRefs</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a778a4f710c8847455c0685dba1736c8b">fileName</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98d598fd49a59a5fd0b3eef5d2a35193">lineNr</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e73fa22df79d3f15db2f1824d64f08c">indentLevel</a> =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::array&lt; <a href="#a38ce2a429b8c4a268507157a45cac671">Action_t</a>, 256 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbee8604b9f0ac5704c3ee99a7f4c7b9">actions</a></td>
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


Definition at line 113 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxySectionDef">

## Public Member Typedefs

### Action\_t {#a38ce2a429b8c4a268507157a45cac671}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using Markdown::Private::Action_t =  std::function&lt;int(std::string_view,size_t)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 172 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a38ce2a429b8c4a268507157a45cac671">172</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a38ce2a429b8c4a268507157a45cac671">Action_t</a> = std::function&lt;int(std::string_view,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight">)&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Private() {#ac8b74ada051582d23d31e3290ce5e917}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Markdown::Private::Private (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fn, int line, int indent)</td>
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



Definition at line 115 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac8b74ada051582d23d31e3290ce5e917">115</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  Private(const QCString &amp;fn,int line,int indent)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    : fileName(fn), lineNr(line), indentLevel(indent)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    // setup callback table for special characters</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    actions[static_cast&lt;unsigned int&gt;('_')] = [this](std::string_view data,size_t offset) { return processEmphasis      (data,offset); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    actions[static_cast&lt;unsigned int&gt;('*')] = [this](std::string_view data,size_t offset) { return processEmphasis      (data,offset); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    actions[static_cast&lt;unsigned int&gt;('~')] = [this](std::string_view data,size_t offset) { return processEmphasis      (data,offset); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    actions[static_cast&lt;unsigned int&gt;('`')] = [this](std::string_view data,size_t offset) { return processCodeSpan      (data,offset); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    actions[static_cast&lt;unsigned int&gt;('\\')]= [this](std::string_view data,size_t offset) { return processSpecialCommand(data,offset); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    actions[static_cast&lt;unsigned int&gt;('@')] = [this](std::string_view data,size_t offset) { return processSpecialCommand(data,offset); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    actions[static_cast&lt;unsigned int&gt;('[')] = [this](std::string_view data,size_t offset) { return processLink          (data,offset); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    actions[static_cast&lt;unsigned int&gt;('!')] = [this](std::string_view data,size_t offset) { return processLink          (data,offset); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    actions[static_cast&lt;unsigned int&gt;('&lt;')] = [this](std::string_view data,size_t offset) { return processHtmlTag       (data,offset); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    actions[static_cast&lt;unsigned int&gt;('-')] = [this](std::string_view data,size_t offset) { return processNmdash        (data,offset); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    actions[static_cast&lt;unsigned int&gt;('"')] = [this](std::string_view data,size_t offset) { return processQuoted        (data,offset); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addStrEscapeUtf8Nbsp() {#a681582d0e894782b9509baa541931151}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Markdown::Private::addStrEscapeUtf8Nbsp (std::string_view data)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 149 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a681582d0e894782b9509baa541931151">1689</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a681582d0e894782b9509baa541931151">Markdown::Private::addStrEscapeUtf8Nbsp</a>(std::string_view data)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1690</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1691</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"{}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1692</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/namespaces/portable/#ada69eeb681c8f036f6a3327478acbd75">Portable::strnstr</a>(data.data(),<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a5411339961a1e433bf9b59570c97fa6a">g_doxy_nbsp</a>,data.size())==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// no escape needed -&gt; fast</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1693</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1694</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=data;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1695</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1696</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// escape needed -&gt; slow</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1697</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1698</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(data),<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a5411339961a1e433bf9b59570c97fa6a">g_doxy_nbsp</a>,<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ab90a38f35e109b0e55a693490232d93d">g_utf8_nbsp</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1699</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1700</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a5411339961a1e433bf9b59570c97fa6a">g\_doxy\_nbsp</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ab90a38f35e109b0e55a693490232d93d">g\_utf8\_nbsp</a>, <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#ada69eeb681c8f036f6a3327478acbd75">Portable::strnstr</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.

Referenced by <a href="#a43b1695a69a83037471e5445c7c940ce">processSpecialCommand</a> and <a href="#a494fc3fc6c848a37caa06e5d85854ffe">writeFencedCodeBlock</a>.
</div>
</div>

### extractTitleId() {#a46231fc8d72391f38170f184dd956ed1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString Markdown::Private::extractTitleId (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, int level, bool * pIsIdGenerated=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 164 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a46231fc8d72391f38170f184dd956ed1">1992</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a46231fc8d72391f38170f184dd956ed1">Markdown::Private::extractTitleId</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> *pIsIdGenerated)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1993</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1994</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"title={} level={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(title),level);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1995</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// match e.g. '{#id-b11} ' and capture 'id-b11'</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1996</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> r2(R</span><span class="doxyHighlightStringLiteral">"({#(\a[\w-]*)}\s*$)");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1997</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">  <a href="/web-doxygen/docs/api/classes/reg/match">reg::Match</a> match;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1998</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">  std::string ti = title.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1999</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>(ti,match,r2))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2000</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2001</span><span class="doxyLineContent"><span class="doxyHighlight">    std::string </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> = match[1].str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2002</span><span class="doxyLineContent"><span class="doxyHighlight">    title = title.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(match.position());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2003</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/anchorgenerator/#a282543ddcf48b1b7cf7d2921573d453d">AnchorGenerator::instance</a>().reserve(</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">)&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2004</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2005</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(<a href="#a778a4f710c8847455c0685dba1736c8b">fileName</a>, <a href="#a98d598fd49a59a5fd0b3eef5d2a35193">lineNr</a>, </span><span class="doxyHighlightStringLiteral">"An automatically generated id already has the name '{}'!"</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2006</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2007</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("found match id='%s' title=%s\n",id.c_str(),qPrint(title));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2008</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"id={}"</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2009</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> id;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2010</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2011</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (((level&gt;0) &amp;&amp; (level&lt;=<a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(TOC_INCLUDE_HEADINGS))) || (<a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(MARKDOWN_ID_STYLE)==MARKDOWN_ID_STYLE_t::GITHUB))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2012</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2013</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> = <a href="/web-doxygen/docs/api/classes/anchorgenerator/#a282543ddcf48b1b7cf7d2921573d453d">AnchorGenerator::instance</a>().<a href="/web-doxygen/docs/api/classes/anchorgenerator/#a557525dbf46d474a3baea1642fe756bd">generate</a>(ti);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2014</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pIsIdGenerated) *pIsIdGenerated=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2015</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("auto-generated id='%s' title='%s'\n",qPrint(id),qPrint(title));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2016</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"id={}"</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2017</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> id;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2018</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2019</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("no id found in title '%s'\n",qPrint(title));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2020</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2021</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO\_TRACE\_EXIT</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config\_getEnum</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config\_getInt</a>, <a href="#a778a4f710c8847455c0685dba1736c8b">fileName</a>, <a href="/web-doxygen/docs/api/classes/anchorgenerator/#a557525dbf46d474a3baea1642fe756bd">AnchorGenerator::generate</a>, <a href="/web-doxygen/docs/api/classes/anchorgenerator/#a282543ddcf48b1b7cf7d2921573d453d">AnchorGenerator::instance</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="#a98d598fd49a59a5fd0b3eef5d2a35193">lineNr</a>, <a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.

Referenced by <a href="#aa8a42c32241bc89aa626ce55c23b7df5">isAtxHeader</a> and <a href="#a9835402c2d15b122de1c3ba4180ebd58">processBlocks</a>.
</div>
</div>

### findEmphasisChar() {#a5b661698b94e4b37748ee38025784690}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t Markdown::Private::findEmphasisChar (std::string_view data, char c, size_t c_size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

looks for the next emph char, skipping other constructs, and stopping when either it is found, or we are at the end of a paragraph.

Definition at line 148 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5b661698b94e4b37748ee38025784690">702</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a5b661698b94e4b37748ee38025784690">Markdown::Private::findEmphasisChar</a>(std::string_view data, </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c, </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> c_size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">703</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">704</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}' c={} c_size={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data),c,c_size);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">705</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">706</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">707</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">708</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">709</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">710</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]!=c    &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">711</span><span class="doxyLineContent"><span class="doxyHighlight">                     data[i]!=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight"> &amp;&amp; data[i]!=</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight"> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">712</span><span class="doxyLineContent"><span class="doxyHighlight">                     !(data[i]==</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight"> &amp;&amp; data[i-1]==</span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">) &amp;&amp; </span><span class="doxyHighlightComment">// html end tag also ends emphasis</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">713</span><span class="doxyLineContent"><span class="doxyHighlight">                     data[i]!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">714</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// avoid overflow (unclosed emph token)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">715</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i==size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">716</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">717</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">718</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">719</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("findEmphasisChar: data=[%s] i=%d c=%c\n",data,i,data[i]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">720</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">721</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// not counting escaped chars or characters that are unlikely</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">722</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// to appear as the end of the emphasis char</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">723</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#acb2def26524ecd4c96d000b854dee831">ignoreCloseEmphChar</a>(data[i-1],data[i]))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">724</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">725</span><span class="doxyLineContent"><span class="doxyHighlight">      i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">726</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">727</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">728</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">729</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">730</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// get length of emphasis token</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">731</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">732</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i+len&lt;size &amp;&amp; data[i+len]==c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">733</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">734</span><span class="doxyLineContent"><span class="doxyHighlight">        len++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">735</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">736</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">737</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (len&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">738</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">739</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (len!=c_size || (i+len&lt;size &amp;&amp; <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a243e6edb7617162067edc19f3f20bdb9">isIdChar</a>(data[i+len]))) </span><span class="doxyHighlightComment">// to prevent touching some_underscore_identifier</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">740</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">741</span><span class="doxyLineContent"><span class="doxyHighlight">          i+=len;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">742</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">743</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">744</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">745</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(i); </span><span class="doxyHighlightComment">// found it</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">746</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">747</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">748</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">749</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// skipping a code span</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">750</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'`'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">751</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">752</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> snb=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">753</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">'`'</span><span class="doxyHighlight">) snb++,i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">754</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">755</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// find same pattern to end the span</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">756</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> enb=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">757</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; enb&lt;snb)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">758</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">759</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'`'</span><span class="doxyHighlight">) enb++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">760</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (snb==1 &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// ` ended by '</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">761</span><span class="doxyLineContent"><span class="doxyHighlight">        i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">762</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">763</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">764</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight"> || data[i]==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">765</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightComment">// skip over blocks that should not be processed</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">766</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> endBlockName = <a href="#a6d7d4814ead5c919439c6b2d681e2ce7">isBlockCommand</a>(data.substr(i),i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">767</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!endBlockName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">768</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">769</span><span class="doxyLineContent"><span class="doxyHighlight">        i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">770</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> l = endBlockName.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">771</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i+l&lt;size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">772</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">773</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((data[i]==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight"> || data[i]==</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">) &amp;&amp; </span><span class="doxyHighlightComment">// command</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">774</span><span class="doxyLineContent"><span class="doxyHighlight">              data[i-1]!=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight"> &amp;&amp; data[i-1]!=</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// not escaped</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">775</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">776</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a19faae287d13ccea75b1d5a0eb110d97">qstrncmp</a>(&amp;data[i+1],endBlockName.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),l)==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">777</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">778</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">779</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">780</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">781</span><span class="doxyLineContent"><span class="doxyHighlight">          i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">782</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">783</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">784</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i+1&lt;size &amp;&amp; <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a243e6edb7617162067edc19f3f20bdb9">isIdChar</a>(data[i+1])) </span><span class="doxyHighlightComment">// @cmd, stop processing, see bug 690385</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">785</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">786</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">787</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">788</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">789</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">790</span><span class="doxyLineContent"><span class="doxyHighlight">        i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">791</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">792</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">793</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i-1]==</span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight"> &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// html end tag invalidates emphasis</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">794</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">795</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">796</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">797</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// end * or _ at paragraph boundary</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">798</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">799</span><span class="doxyLineContent"><span class="doxyHighlight">      i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">800</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">801</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&gt;=size || data[i]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">802</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">803</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">804</span><span class="doxyLineContent"><span class="doxyHighlight">      } </span><span class="doxyHighlightComment">// empty line -&gt; paragraph</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">805</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">806</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// should not get here!</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">807</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">808</span><span class="doxyLineContent"><span class="doxyHighlight">      i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">809</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">810</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">811</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">812</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO\_TRACE\_EXIT</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#acb2def26524ecd4c96d000b854dee831">ignoreCloseEmphChar</a>, <a href="#a6d7d4814ead5c919439c6b2d681e2ce7">isBlockCommand</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a243e6edb7617162067edc19f3f20bdb9">isIdChar</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a19faae287d13ccea75b1d5a0eb110d97">qstrncmp</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.

Referenced by <a href="#a0bb20b07bce14eca215477b9ec05adbd">processEmphasis1</a>, <a href="#abbb763f2449b932ef3468560e30a0478">processEmphasis2</a> and <a href="#a4041a1e946c4402894bfff49b611e63b">processEmphasis3</a>.
</div>
</div>

### findEndOfLine() {#aad2fb530e3d19a77de38a8c1b633b786}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t Markdown::Private::findEndOfLine (std::string_view data, size_t offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 136 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aad2fb530e3d19a77de38a8c1b633b786">2978</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#aad2fb530e3d19a77de38a8c1b633b786">Markdown::Private::findEndOfLine</a>(std::string_view data,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> offset)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2979</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2980</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}'"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2981</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// find end of the line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2982</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2983</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> nb=0, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=offset+1, j=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2984</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>&lt;=size &amp;&amp; (j=<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#afc4de25503fad3bbfadba71ff6e7581a">isNewline</a>(data.substr(<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-1)))==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2985</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2986</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// while looking for the end of the line we might encounter a block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2987</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// that needs to be passed unprocessed.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2988</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-1]==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight"> || data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-1]==</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">) &amp;&amp;          </span><span class="doxyHighlightComment">// command</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2989</span><span class="doxyLineContent"><span class="doxyHighlight">        (<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>&lt;=1 || (data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-2]!=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight"> &amp;&amp; data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-2]!=</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">)) </span><span class="doxyHighlightComment">// not escaped</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2990</span><span class="doxyLineContent"><span class="doxyHighlight">       )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2991</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2992</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> endBlockName = <a href="#a6d7d4814ead5c919439c6b2d681e2ce7">isBlockCommand</a>(data.substr(<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-1),<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2993</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2994</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!endBlockName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2995</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2996</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> l = endBlockName.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2997</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (;<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>+l+1&lt;size;<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>++) </span><span class="doxyHighlightComment">// search for end of block marker</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2998</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2999</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>]==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight"> || data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>]==</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3000</span><span class="doxyLineContent"><span class="doxyHighlight">              data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-1]!=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight"> &amp;&amp; data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-1]!=</span><span class="doxyHighlightCharLiteral">'@'</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3001</span><span class="doxyLineContent"><span class="doxyHighlight">             )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3002</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3003</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a19faae287d13ccea75b1d5a0eb110d97">qstrncmp</a>(&amp;data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>+1],endBlockName.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),l)==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3004</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3005</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightComment">// found end marker, skip over this block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3006</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightComment">//printf("feol.block out={%s}\n",qPrint(QCString(data+i).left(end+l+1-i)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3007</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a> = <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a> + l + 2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3008</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3009</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3010</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3011</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3012</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3013</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3014</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nb==0 &amp;&amp; data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-1]==</span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight"> &amp;&amp; size&gt;=6 &amp;&amp; <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>+6&lt;size &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3015</span><span class="doxyLineContent"><span class="doxyHighlight">             (<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>&lt;=1 || (data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-2]!=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight"> &amp;&amp; data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-2]!=</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3016</span><span class="doxyLineContent"><span class="doxyHighlight">            )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3017</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3018</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tolower(data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>])==</span><span class="doxyHighlightCharLiteral">'p'</span><span class="doxyHighlight"> &amp;&amp; tolower(data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>+1])==</span><span class="doxyHighlightCharLiteral">'r'</span><span class="doxyHighlight"> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3019</span><span class="doxyLineContent"><span class="doxyHighlight">          tolower(data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>+2])==</span><span class="doxyHighlightCharLiteral">'e'</span><span class="doxyHighlight"> &amp;&amp; (data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>+3]==</span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight"> || data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>+3]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">)) </span><span class="doxyHighlightComment">// &lt;pre&gt; tag</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3020</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3021</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// skip part until including &lt;/pre&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3022</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>  = <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a> + <a href="#aa4f4085dfd3e73ae354c7cfd6fa69faf">processHtmlTagWrite</a>(data.substr(<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-1),<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-1,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3023</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3024</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3025</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3026</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3027</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3028</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3029</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3030</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nb==0 &amp;&amp; data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-1]==</span><span class="doxyHighlightCharLiteral">'`'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3031</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3032</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>&lt;=size &amp;&amp; data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-1]==</span><span class="doxyHighlightCharLiteral">'`'</span><span class="doxyHighlight">) <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>++,nb++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3033</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3034</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nb&gt;0 &amp;&amp; data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-1]==</span><span class="doxyHighlightCharLiteral">'`'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3035</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3036</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> enb=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3037</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>&lt;=size &amp;&amp; data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-1]==</span><span class="doxyHighlightCharLiteral">'`'</span><span class="doxyHighlight">) <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>++,enb++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3038</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (enb==nb) nb=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3039</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3040</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3041</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3042</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3043</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3044</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3045</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (j&gt;0) <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>+=j-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3046</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"offset={} end={}"</span><span class="doxyHighlight">,offset,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3047</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3048</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO\_TRACE\_EXIT</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="#a6d7d4814ead5c919439c6b2d681e2ce7">isBlockCommand</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#afc4de25503fad3bbfadba71ff6e7581a">isNewline</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#aa4f4085dfd3e73ae354c7cfd6fa69faf">processHtmlTagWrite</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a19faae287d13ccea75b1d5a0eb110d97">qstrncmp</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.

Referenced by <a href="#a9835402c2d15b122de1c3ba4180ebd58">processBlocks</a> and <a href="#a9792322da9173be90556ef009d37afa4">processQuotations</a>.
</div>
</div>

### isAtxHeader() {#aa8a42c32241bc89aa626ce55c23b7df5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int Markdown::Private::isAtxHeader (std::string_view data, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; header, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; id, bool allowAdjustLevel, bool * pIsIdGenerated=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 156 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa8a42c32241bc89aa626ce55c23b7df5">2024</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#aa8a42c32241bc89aa626ce55c23b7df5">Markdown::Private::isAtxHeader</a>(std::string_view data,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2025</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;header,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> allowAdjustLevel,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> *pIsIdGenerated)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2026</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2027</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}' header={} id={} allowAdjustLevel={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data),<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(header),</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,allowAdjustLevel);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2028</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2029</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level = 0, blanks=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2030</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2031</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2032</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// find start of header text and determine heading level</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2033</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2034</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&gt;=size || data[i]!=</span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2035</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2036</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2037</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2038</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">) i++,level++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2039</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (level&gt;<a href="/web-doxygen/docs/api/classes/sectiontype/#a2f832ab2bf817c8581feb03e123f09d5">SectionType::MaxLevel</a>) </span><span class="doxyHighlightComment">// too many #'s -&gt; no section</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2040</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2041</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2042</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2043</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) i++,blanks++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2044</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (level==1 &amp;&amp; blanks==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2045</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2046</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; </span><span class="doxyHighlightComment">// special case to prevent #someid seen as a header (see bug 671395)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2047</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2048</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2049</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// find end of header text</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2050</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2051</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>&lt;size &amp;&amp; data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>]!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2052</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>&gt;i &amp;&amp; (data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-1]==</span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight"> || data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-1]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">)) <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2053</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2054</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// store result</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2055</span><span class="doxyLineContent"><span class="doxyHighlight">  header = data.substr(i,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2056</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> = <a href="#a46231fc8d72391f38170f184dd956ed1">extractTitleId</a>(header, level, pIsIdGenerated);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2057</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">.isEmpty()) </span><span class="doxyHighlightComment">// strip #'s between title and id</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2058</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2059</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> idx=</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(header.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>())-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2060</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (idx&gt;=0 &amp;&amp; (header.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(idx)==</span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight"> || header.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(idx)==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">)) idx--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2061</span><span class="doxyLineContent"><span class="doxyHighlight">    header=header.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(idx+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2062</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2063</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2064</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (allowAdjustLevel &amp;&amp; level==1 &amp;&amp; <a href="#a5e73fa22df79d3f15db2f1824d64f08c">indentLevel</a>==-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2065</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2066</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// in case we find a `# Section` on a markdown page that started with the same level</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2067</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// header, we no longer need to artificially decrease the paragraph level.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2068</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// So both</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2069</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// -------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2070</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// # heading 1    &lt;-- here we set g_indentLevel to -1</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2071</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// # heading 2    &lt;-- here we set g_indentLevel back to 0 such that this will be a @section</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2072</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// -------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2073</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// and</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2074</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// -------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2075</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// # heading 1    &lt;-- here we set  g_indentLevel to -1</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2076</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// ## heading 2   &lt;-- here we keep g_indentLevel at -1 such that @subsection will be @section</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2077</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// -------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2078</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// will convert to</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2079</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// -------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2080</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// @page md_page Heading 1</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2081</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// @section autotoc_md1 Heading 2</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2082</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// -------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2083</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2084</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5e73fa22df79d3f15db2f1824d64f08c">indentLevel</a>=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2085</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2086</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> res = level+<a href="#a5e73fa22df79d3f15db2f1824d64f08c">indentLevel</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2087</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,res);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2088</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> res;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2089</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO\_TRACE\_EXIT</a>, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="#a46231fc8d72391f38170f184dd956ed1">extractTitleId</a>, <a href="#a5e73fa22df79d3f15db2f1824d64f08c">indentLevel</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/sectiontype/#a2f832ab2bf817c8581feb03e123f09d5">SectionType::MaxLevel</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.

Referenced by <a href="#af7ceebe6b90c368816a6d9bd0ca501c0">writeOneLineHeaderOrRuler</a>.
</div>
</div>

### isBlockCommand() {#a6d7d4814ead5c919439c6b2d681e2ce7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString Markdown::Private::isBlockCommand (std::string_view data, size_t offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 134 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6d7d4814ead5c919439c6b2d681e2ce7">360</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a6d7d4814ead5c919439c6b2d681e2ce7">Markdown::Private::isBlockCommand</a>(std::string_view data,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> offset)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">361</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}' offset={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data),offset);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight">EndBlockFunc = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> (*)(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;,bool,char);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">366</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> getEndBlock   = [](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;blockName,bool,char) -&gt; <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">367</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"end"</span><span class="doxyHighlight">+blockName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> getEndCode    = [](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;blockName,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> openBracket,char) -&gt; <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> openBracket ? <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">) : </span><span class="doxyHighlightStringLiteral">"end"</span><span class="doxyHighlight">+blockName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> getEndUml     = [](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;</span><span class="doxyHighlightComment">/* blockName */</span><span class="doxyHighlight">,bool,char) -&gt; <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"enduml"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> getEndFormula = [](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;</span><span class="doxyHighlightComment">/* blockName */</span><span class="doxyHighlight">,bool,</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> nextChar) -&gt; <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (nextChar)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'$'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"f$"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"f)"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'['</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"f]"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"f}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// table mapping a block start command to a function that can return the matching end block string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::unordered_map&lt;std::string,EndBlockFunc&gt; blockNames =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"dot"</span><span class="doxyHighlight">,         getEndBlock   },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"code"</span><span class="doxyHighlight">,        getEndCode    },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"icode"</span><span class="doxyHighlight">,       getEndBlock   },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"msc"</span><span class="doxyHighlight">,         getEndBlock   },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"verbatim"</span><span class="doxyHighlight">,    getEndBlock   },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"iverbatim"</span><span class="doxyHighlight">,   getEndBlock   },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"iliteral"</span><span class="doxyHighlight">,    getEndBlock   },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"latexonly"</span><span class="doxyHighlight">,   getEndBlock   },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"htmlonly"</span><span class="doxyHighlight">,    getEndBlock   },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">402</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"xmlonly"</span><span class="doxyHighlight">,     getEndBlock   },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"rtfonly"</span><span class="doxyHighlight">,     getEndBlock   },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"manonly"</span><span class="doxyHighlight">,     getEndBlock   },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">405</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"docbookonly"</span><span class="doxyHighlight">, getEndBlock   },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">406</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"startuml"</span><span class="doxyHighlight">,    getEndUml     },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">407</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"f"</span><span class="doxyHighlight">,           getEndFormula }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">408</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">409</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.<a href="/web-doxygen/docs/api/classes/qcstring/#a957be37e3b98707fc7e8daeff18e391b">size</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">411</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> openBracket = offset&gt;0 &amp;&amp; data.data()[-1]==</span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">412</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isEscaped = offset&gt;0 &amp;&amp; (data.data()[-1]==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight"> || data.data()[-1]==</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">413</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isEscaped) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">414</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">415</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>&lt;size &amp;&amp; (data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>]&gt;=</span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight"> &amp;&amp; data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>]&lt;=</span><span class="doxyHighlightCharLiteral">'z'</span><span class="doxyHighlight">)) <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">417</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>==1) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">418</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string blockName(data.substr(1,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-1));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">419</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = blockNames.find(blockName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">421</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=blockNames.end()) </span><span class="doxyHighlightComment">// there is a function assigned</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">422</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">423</span><span class="doxyLineContent"><span class="doxyHighlight">    result = it-&gt;second(blockName, openBracket, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>&lt;size ? data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>] : 0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">424</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">425</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">426</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">427</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO\_TRACE\_EXIT</a>, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a957be37e3b98707fc7e8daeff18e391b">QCString::size</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.

Referenced by <a href="#a5b661698b94e4b37748ee38025784690">findEmphasisChar</a>, <a href="#aad2fb530e3d19a77de38a8c1b633b786">findEndOfLine</a>, <a href="#a9835402c2d15b122de1c3ba4180ebd58">processBlocks</a> and <a href="#a43b1695a69a83037471e5445c7c940ce">processSpecialCommand</a>.
</div>
</div>

### isHeaderline() {#a5628c6052a120856d53921f8746d0251}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int Markdown::Private::isHeaderline (std::string_view data, bool allowAdjustLevel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

returns whether the line is a setext-style hdr underline

Definition at line 155 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5628c6052a120856d53921f8746d0251">1805</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a5628c6052a120856d53921f8746d0251">Markdown::Private::isHeaderline</a>(std::string_view data, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> allowAdjustLevel)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1806</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1807</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}' allowAdjustLevel"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data),allowAdjustLevel);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1808</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0, c=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1809</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1810</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1811</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i==size) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1812</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1813</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// test of level 1 header</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1814</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'='</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1815</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1816</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">'='</span><span class="doxyHighlight">) i++,c++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1817</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1818</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level = (c&gt;1 &amp;&amp; (i&gt;=size || data[i]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)) ? 1 : 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1819</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (allowAdjustLevel &amp;&amp; level==1 &amp;&amp; <a href="#a5e73fa22df79d3f15db2f1824d64f08c">indentLevel</a>==-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1820</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1821</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// In case a page starts with a header line we use it as title, promoting it to @page.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1822</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// We set g_indentLevel to -1 to promoting the other sections if they have a deeper</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1823</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// nesting level than the page header, i.e. @section..@subsection becomes @page..@section.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1824</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// In case a section at the same level is found (@section..@section) however we need</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1825</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// to undo this (and the result will be @page..@section).</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1826</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5e73fa22df79d3f15db2f1824d64f08c">indentLevel</a>=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1827</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1828</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,<a href="#a5e73fa22df79d3f15db2f1824d64f08c">indentLevel</a>+level);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1829</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a5e73fa22df79d3f15db2f1824d64f08c">indentLevel</a>+level;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1830</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1831</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// test of level 2 header</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1832</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1833</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1834</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">) i++,c++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1835</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1836</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> (c&gt;1 &amp;&amp; (i&gt;=size || data[i]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)) ? <a href="#a5e73fa22df79d3f15db2f1824d64f08c">indentLevel</a>2 : 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1837</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1838</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1839</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO\_TRACE\_EXIT</a>, <a href="#a5e73fa22df79d3f15db2f1824d64f08c">indentLevel</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.

Referenced by <a href="#a9835402c2d15b122de1c3ba4180ebd58">processBlocks</a>.
</div>
</div>

### isSpecialCommand() {#a2e37305849fa544aff8f399a6f41c7b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t Markdown::Private::isSpecialCommand (std::string_view data, size_t offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 135 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2e37305849fa544aff8f399a6f41c7b1">429</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a2e37305849fa544aff8f399a6f41c7b1">Markdown::Private::isSpecialCommand</a>(std::string_view data,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> offset)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">430</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">431</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}' offset={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data),offset);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">432</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">433</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight">EndCmdFunc = size_t (*)(std::string_view,size_t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">434</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">435</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> endOfLine = [](std::string_view data_,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> offset_) -&gt; </span><span class="doxyHighlightKeywordType">size_t</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// skip until the end of line (allowing line continuation characters)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> lc = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">439</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (offset_&lt;data_.size() &amp;&amp; ((c=data_[offset_])!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight"> || lc==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">441</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">442</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">)     lc=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// last character was a line continuation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c!=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) lc=0;    </span><span class="doxyHighlightComment">// rest line continuation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span><span class="doxyLineContent"><span class="doxyHighlight">      offset_++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">446</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> offset_;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">447</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> endOfLabels = [](std::string_view data_,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> offset_,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> multi_) -&gt; </span><span class="doxyHighlightKeywordType">size_t</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (offset_&lt;data_.size() &amp;&amp; data_[offset_]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// we expect a space before the label</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">      offset_++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> done=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!done)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">457</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// skip over spaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (offset_&lt;data_.size() &amp;&amp; data_[offset_]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">          offset_++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// skip over label</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (offset_&lt;data_.size() &amp;&amp; (c=data_[offset_])!=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">','</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">          offset_++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// optionally skip over a comma separated list of labels</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (multi_ &amp;&amp; offset_&lt;data_.size() &amp;&amp; (data_[offset_]==</span><span class="doxyHighlightCharLiteral">','</span><span class="doxyHighlight"> || data_[offset_]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> off = offset_;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (off&lt;data_.size() &amp;&amp; data_[off]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlight">            off++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (off&lt;data_.size() &amp;&amp; data_[off]==</span><span class="doxyHighlightCharLiteral">','</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">            offset_ = ++off;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">479</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// no next label found</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">            done=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">          done=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> offset_;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> endOfLabel = [](std::string_view data_,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> offset_) -&gt; </span><span class="doxyHighlightKeywordType">size_t</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> endOfLabels(data_,offset_,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> endOfLabelOpt = [](std::string_view data_,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> offset_) -&gt; </span><span class="doxyHighlightKeywordType">size_t</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> index=offset_;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index&lt;data_.size() &amp;&amp; data_[index]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// skip over optional spaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">      index++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (index&lt;data_.size() &amp;&amp; data_[index]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) index++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index&lt;data_.size() &amp;&amp; data_[index]==</span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// find matching '}'</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlight">      index++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (index&lt;data_.size() &amp;&amp; (c=data_[index])!=</span><span class="doxyHighlightCharLiteral">'}'</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) index++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">513</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index==data_.size() || data_[index]!=</span><span class="doxyHighlightCharLiteral">'}'</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; </span><span class="doxyHighlightComment">// invalid option</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">514</span><span class="doxyLineContent"><span class="doxyHighlight">      offset_=index+1; </span><span class="doxyHighlightComment">// part after {...} is the option</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">515</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">516</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> endOfLabel(data_,offset_);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">517</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">518</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> endOfParam = [](std::string_view data_,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> offset_) -&gt; </span><span class="doxyHighlightKeywordType">size_t</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">521</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> index=offset_;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index&lt;data_.size() &amp;&amp; data_[index]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// skip over optional spaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">      index++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">525</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (index&lt;data_.size() &amp;&amp; data_[index]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) index++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">526</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">527</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index&lt;data_.size() &amp;&amp; data_[index]==</span><span class="doxyHighlightCharLiteral">'['</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// find matching ']'</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">528</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">529</span><span class="doxyLineContent"><span class="doxyHighlight">      index++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">530</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">531</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (index&lt;data_.size() &amp;&amp; (c=data_[index])!=</span><span class="doxyHighlightCharLiteral">']'</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) index++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">532</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index==data_.size() || data_[index]!=</span><span class="doxyHighlightCharLiteral">']'</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; </span><span class="doxyHighlightComment">// invalid parameter</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">533</span><span class="doxyLineContent"><span class="doxyHighlight">      offset_=index+1; </span><span class="doxyHighlightComment">// part after [...] is the parameter name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">534</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">535</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> endOfLabels(data_,offset_,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">536</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">537</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">538</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> endOfRetVal = [](std::string_view data_,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> offset_) -&gt; </span><span class="doxyHighlightKeywordType">size_t</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">539</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">540</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> endOfLabels(data_,offset_,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">541</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">542</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">543</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> endOfFuncLike = [](std::string_view data_,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> offset_,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> allowSpaces) -&gt; </span><span class="doxyHighlightKeywordType">size_t</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">544</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">545</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (offset_&lt;data_.size() &amp;&amp; data_[offset_]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// we expect a space before the name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">546</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">547</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">548</span><span class="doxyLineContent"><span class="doxyHighlight">      offset_++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">549</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// skip over spaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">550</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (offset_&lt;data_.size() &amp;&amp; data_[offset_]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">551</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">552</span><span class="doxyLineContent"><span class="doxyHighlight">        offset_++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">553</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">554</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// skip over name (and optionally type)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">555</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (offset_&lt;data_.size() &amp;&amp; (c=data_[offset_])!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight"> &amp;&amp; (allowSpaces || c!=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">556</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">557</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>(data_.substr(offset_),</span><span class="doxyHighlightStringLiteral">"\\ilinebr "</span><span class="doxyHighlight">)) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">558</span><span class="doxyLineContent"><span class="doxyHighlight">        offset_++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">559</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">560</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// find the end of the function</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">561</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> count=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">563</span><span class="doxyLineContent"><span class="doxyHighlight">        offset_++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (offset_&lt;data_.size() &amp;&amp; (c=data_[offset_++]))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">566</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">      (c==</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">) count++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">567</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">) count--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">568</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (count==0) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> offset_;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">569</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">570</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">571</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> offset_;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">572</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">575</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">576</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> endOfFunc = [](std::string_view data_,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> offset_) -&gt; </span><span class="doxyHighlightKeywordType">size_t</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">577</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">578</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> endOfFuncLike(data_,offset_,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> endOfGuard = [](std::string_view data_,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> offset_) -&gt; </span><span class="doxyHighlightKeywordType">size_t</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> endOfFuncLike(data_,offset_,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">584</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">586</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::unordered_map&lt;std::string,EndCmdFunc&gt; cmdNames =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">587</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"a"</span><span class="doxyHighlight">,              endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">589</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"addindex"</span><span class="doxyHighlight">,       endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">590</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"addtogroup"</span><span class="doxyHighlight">,     endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">591</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"anchor"</span><span class="doxyHighlight">,         endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">592</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"b"</span><span class="doxyHighlight">,              endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">593</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"c"</span><span class="doxyHighlight">,              endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"category"</span><span class="doxyHighlight">,       endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"cite"</span><span class="doxyHighlight">,           endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"class"</span><span class="doxyHighlight">,          endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"concept"</span><span class="doxyHighlight">,        endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"copybrief"</span><span class="doxyHighlight">,      endOfFunc  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"copydetails"</span><span class="doxyHighlight">,    endOfFunc  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"copydoc"</span><span class="doxyHighlight">,        endOfFunc  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">601</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"def"</span><span class="doxyHighlight">,            endOfFunc  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">602</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"defgroup"</span><span class="doxyHighlight">,       endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">603</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"diafile"</span><span class="doxyHighlight">,        endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">604</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"dir"</span><span class="doxyHighlight">,            endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"dockbookinclude"</span><span class="doxyHighlight">,endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"dontinclude"</span><span class="doxyHighlight">,    endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"dotfile"</span><span class="doxyHighlight">,        endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"e"</span><span class="doxyHighlight">,              endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"elseif"</span><span class="doxyHighlight">,         endOfGuard },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"em"</span><span class="doxyHighlight">,             endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"emoji"</span><span class="doxyHighlight">,          endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"enum"</span><span class="doxyHighlight">,           endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">613</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"example"</span><span class="doxyHighlight">,        endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">614</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"exception"</span><span class="doxyHighlight">,      endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">615</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"extends"</span><span class="doxyHighlight">,        endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">616</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"file"</span><span class="doxyHighlight">,           endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"fn"</span><span class="doxyHighlight">,             endOfFunc  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">618</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"headerfile"</span><span class="doxyHighlight">,     endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">619</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"htmlinclude"</span><span class="doxyHighlight">,    endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">620</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"ianchor"</span><span class="doxyHighlight">,        endOfLabelOpt },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">621</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"idlexcept"</span><span class="doxyHighlight">,      endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">622</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"if"</span><span class="doxyHighlight">,             endOfGuard },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">623</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"ifnot"</span><span class="doxyHighlight">,          endOfGuard },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">624</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"image"</span><span class="doxyHighlight">,          endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">625</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"implements"</span><span class="doxyHighlight">,     endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">626</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"include"</span><span class="doxyHighlight">,        endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">627</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"includedoc"</span><span class="doxyHighlight">,     endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">628</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"includelineno"</span><span class="doxyHighlight">,  endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">629</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"ingroup"</span><span class="doxyHighlight">,        endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">630</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"interface"</span><span class="doxyHighlight">,      endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">631</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"latexinclude"</span><span class="doxyHighlight">,   endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">632</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"maninclude"</span><span class="doxyHighlight">,     endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">633</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"memberof"</span><span class="doxyHighlight">,       endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">634</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"mscfile"</span><span class="doxyHighlight">,        endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">635</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"namespace"</span><span class="doxyHighlight">,      endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">636</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"noop"</span><span class="doxyHighlight">,           endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">637</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"overload"</span><span class="doxyHighlight">,       endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">638</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"p"</span><span class="doxyHighlight">,              endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">639</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"package"</span><span class="doxyHighlight">,        endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">640</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"page"</span><span class="doxyHighlight">,           endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">641</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"paragraph"</span><span class="doxyHighlight">,      endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">642</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"param"</span><span class="doxyHighlight">,          endOfParam },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">643</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"property"</span><span class="doxyHighlight">,       endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">644</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"protocol"</span><span class="doxyHighlight">,       endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">645</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"qualifier"</span><span class="doxyHighlight">,      endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">646</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"ref"</span><span class="doxyHighlight">,            endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">647</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"refitem"</span><span class="doxyHighlight">,        endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">648</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"related"</span><span class="doxyHighlight">,        endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">649</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"relatedalso"</span><span class="doxyHighlight">,    endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">650</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"relates"</span><span class="doxyHighlight">,        endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">651</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"relatesalso"</span><span class="doxyHighlight">,    endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">652</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"retval"</span><span class="doxyHighlight">,         endOfRetVal},</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">653</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"rtfinclude"</span><span class="doxyHighlight">,     endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">654</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"section"</span><span class="doxyHighlight">,        endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">655</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"skip"</span><span class="doxyHighlight">,           endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">656</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"skipline"</span><span class="doxyHighlight">,       endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">657</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"snippet"</span><span class="doxyHighlight">,        endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">658</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"snippetdoc"</span><span class="doxyHighlight">,     endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">659</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"snippetlineno"</span><span class="doxyHighlight">,  endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">660</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"struct"</span><span class="doxyHighlight">,         endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">661</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"subpage"</span><span class="doxyHighlight">,        endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">662</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"subparagraph"</span><span class="doxyHighlight">,   endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">663</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"subsubparagraph"</span><span class="doxyHighlight">,endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">664</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"subsection"</span><span class="doxyHighlight">,     endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">665</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"subsubsection"</span><span class="doxyHighlight">,  endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">666</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"throw"</span><span class="doxyHighlight">,          endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"throws"</span><span class="doxyHighlight">,         endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">668</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"tparam"</span><span class="doxyHighlight">,         endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"typedef"</span><span class="doxyHighlight">,        endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">670</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"plantumlfile"</span><span class="doxyHighlight">,   endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">671</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"union"</span><span class="doxyHighlight">,          endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">672</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"until"</span><span class="doxyHighlight">,          endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">673</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"var"</span><span class="doxyHighlight">,            endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">674</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"verbinclude"</span><span class="doxyHighlight">,    endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">675</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"weakgroup"</span><span class="doxyHighlight">,      endOfLabel },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">676</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"xmlinclude"</span><span class="doxyHighlight">,     endOfLine  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">677</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightStringLiteral">"xrefitem"</span><span class="doxyHighlight">,       endOfLabel }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">678</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">679</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">680</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isEscaped = offset&gt;0 &amp;&amp; (data.data()[-1]==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight"> || data.data()[-1]==</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">681</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isEscaped) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">682</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">683</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">684</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">685</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>&lt;size &amp;&amp; (data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>]&gt;=</span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight"> &amp;&amp; data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>]&lt;=</span><span class="doxyHighlightCharLiteral">'z'</span><span class="doxyHighlight">)) <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">686</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>==1) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">687</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string cmdName(data.substr(1,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-1));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">688</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> result=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">689</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = cmdNames.find(cmdName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">690</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=cmdNames.end()) </span><span class="doxyHighlightComment">// command with parameters that should be ignored by markdown</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">691</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">692</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// find the end of the parameters</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">693</span><span class="doxyLineContent"><span class="doxyHighlight">    result = it-&gt;second(data,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">694</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">696</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">697</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO\_TRACE\_EXIT</a>, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal\_at</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.

Referenced by <a href="#a43b1695a69a83037471e5445c7c940ce">processSpecialCommand</a>.
</div>
</div>

### processBlocks() {#a9835402c2d15b122de1c3ba4180ebd58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString Markdown::Private::processBlocks (std::string_view data, size_t indent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 133 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9835402c2d15b122de1c3ba4180ebd58">3232</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a9835402c2d15b122de1c3ba4180ebd58">Markdown::Private::processBlocks</a>(std::string_view data,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> indent)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3233</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3234</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}' indent={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data),indent);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3235</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3236</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pi = std::string::npos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3237</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> id,link,title;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3238</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3239</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#if 0 </span><span class="doxyHighlightComment">// commented out, since starting with a comment block is probably a usage error</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3240</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// see also http://stackoverflow.com/q/20478611/784672</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3241</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3242</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// special case when the documentation starts with a code block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3243</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// since the first line is skipped when looking for a code block later on.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3244</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>&gt;<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a918fa8a25e6bc30b364b55bc19a5dafd">codeBlockIndent</a> &amp;&amp; <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a76c8e357497a35b016ee0289e26ee0dd">isCodeBlock</a>(data,0,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>,blockIndent))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3245</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3246</span><span class="doxyLineContent"><span class="doxyHighlight">    i=<a href="#a79fd3fae285ba1f1beeb84c8e858bf46">writeCodeBlock</a>(<a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>,data,size,blockIndent);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3247</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=i+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3248</span><span class="doxyLineContent"><span class="doxyHighlight">    pi=-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3249</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3250</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3251</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3252</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> currentIndent = indent;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3253</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> listIndent = indent;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3254</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> insideList = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3255</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> newBlock = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3256</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// process each line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3257</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3258</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;data.size())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3259</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3260</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a> = <a href="#aad2fb530e3d19a77de38a8c1b633b786">findEndOfLine</a>(data,i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3261</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// line is now found at [i..end)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3262</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3263</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> lineIndent=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3264</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3265</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (lineIndent&lt;<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a> &amp;&amp; data[i+lineIndent]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) lineIndent++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3266</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("** lineIndent=%d line=(%s)\n",lineIndent,qPrint(QCString(data+i).left(end-i)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3267</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3268</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (newBlock)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3269</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3270</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("** end of block\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3271</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (insideList &amp;&amp; lineIndent&lt;currentIndent) </span><span class="doxyHighlightComment">// end of list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3272</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3273</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("** end of list\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3274</span><span class="doxyLineContent"><span class="doxyHighlight">        currentIndent = indent;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3275</span><span class="doxyLineContent"><span class="doxyHighlight">        insideList = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3276</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3277</span><span class="doxyLineContent"><span class="doxyHighlight">      newBlock = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3278</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3279</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3280</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((listIndent=<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ad0a6b598945a869cd184d17fe1f16812">isListMarker</a>(data.substr(i,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-i)))) </span><span class="doxyHighlightComment">// see if we need to increase the indent level</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3281</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3282</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (listIndent&lt;currentIndent+4)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3283</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3284</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("** start of list\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3285</span><span class="doxyLineContent"><span class="doxyHighlight">        insideList = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3286</span><span class="doxyLineContent"><span class="doxyHighlight">        currentIndent = listIndent;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3287</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3288</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3289</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a4808ea595b45102dac19491e80d2ac9c">isEndOfList</a>(data.substr(i,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-i)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3290</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3291</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("** end of list\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3292</span><span class="doxyLineContent"><span class="doxyHighlight">      insideList = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3293</span><span class="doxyLineContent"><span class="doxyHighlight">      currentIndent = listIndent;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3294</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3295</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a7b54fef3d70eef54bd49dda068709f43">isEmptyLine</a>(data.substr(i,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-i)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3296</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3297</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("** new block\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3298</span><span class="doxyLineContent"><span class="doxyHighlight">      newBlock = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3299</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3300</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3301</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("indent=%d listIndent=%d blockIndent=%d\n",indent,listIndent,blockIndent);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3302</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3303</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("findEndOfLine: pi=%d i=%d end=%d\n",pi,i,end);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3304</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3305</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pi!=std::string::npos)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3306</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3307</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> blockStart=0, blockEnd=0, blockOffset=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3308</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> lang;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3309</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> blockIndent = currentIndent;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3310</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> ref = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3311</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("isHeaderLine(%s)=%d\n",QCString(data+i).left(size-i).data(),level);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3312</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> endBlockName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3313</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight"> || data[i]==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">) endBlockName = <a href="#a6d7d4814ead5c919439c6b2d681e2ce7">isBlockCommand</a>(data.substr(i),i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3314</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!endBlockName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3315</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3316</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// handle previous line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3317</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a3712f14d18ec5d547f7c55413abdb9fb">isLinkRef</a>(data.substr(pi,i-pi),</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,link,title))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3318</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3319</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a5dd95f5138a9eb830f708bf8f669e89b">linkRefs</a>.emplace(</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">.lower().str(),<a href="/web-doxygen/docs/api/structs/markdown/private/linkref">LinkRef</a>(link,title));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3320</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3321</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3322</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3323</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#af7ceebe6b90c368816a6d9bd0ca501c0">writeOneLineHeaderOrRuler</a>(data.substr(pi,i-pi));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3324</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3325</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=data[i];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3326</span><span class="doxyLineContent"><span class="doxyHighlight">        i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3327</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> l = endBlockName.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3328</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i+l&lt;data.size())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3329</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3330</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((data[i]==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight"> || data[i]==</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">) &amp;&amp; </span><span class="doxyHighlightComment">// command</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3331</span><span class="doxyLineContent"><span class="doxyHighlight">              data[i-1]!=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight"> &amp;&amp; data[i-1]!=</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// not escaped</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3332</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3333</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a19faae287d13ccea75b1d5a0eb110d97">qstrncmp</a>(&amp;data[i+1],endBlockName.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),l)==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3334</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3335</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=data[i];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3336</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=endBlockName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3337</span><span class="doxyLineContent"><span class="doxyHighlight">              i+=l+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3338</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3339</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3340</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3341</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=data[i];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3342</span><span class="doxyLineContent"><span class="doxyHighlight">          i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3343</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3344</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3345</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((level=<a href="#a5628c6052a120856d53921f8746d0251">isHeaderline</a>(data.substr(i),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>))&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3346</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3347</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("Found header at %d-%d\n",i,end);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3348</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (pi&lt;data.size() &amp;&amp; data[pi]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) pi++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3349</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> header = data.substr(pi,i-pi-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3350</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> = <a href="#a46231fc8d72391f38170f184dd956ed1">extractTitleId</a>(header, level);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3351</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("header='%s' is='%s'\n",qPrint(header),qPrint(id));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3352</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!header.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3353</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3354</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3355</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3356</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=level==1?</span><span class="doxyHighlightStringLiteral">"@section "</span><span class="doxyHighlight">:</span><span class="doxyHighlightStringLiteral">"@subsection "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3357</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=id;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3358</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3359</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=header;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3360</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"\n\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3361</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3362</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3363</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3364</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=level==1?</span><span class="doxyHighlightStringLiteral">"&lt;h1&gt;"</span><span class="doxyHighlight">:</span><span class="doxyHighlightStringLiteral">"&lt;h2&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3365</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=header;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3366</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=level==1?</span><span class="doxyHighlightStringLiteral">"\n&lt;/h1&gt;\n"</span><span class="doxyHighlight">:</span><span class="doxyHighlightStringLiteral">"\n&lt;/h2&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3367</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3368</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3369</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3370</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3371</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"\n&lt;hr&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3372</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3373</span><span class="doxyLineContent"><span class="doxyHighlight">        pi=std::string::npos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3374</span><span class="doxyLineContent"><span class="doxyHighlight">        i=<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3375</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=i+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3376</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3377</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3378</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((ref=<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a3712f14d18ec5d547f7c55413abdb9fb">isLinkRef</a>(data.substr(pi),</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,link,title)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3379</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3380</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("found link ref: id='%s' link='%s' title='%s'\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3381</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//       qPrint(id),qPrint(link),qPrint(title));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3382</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a5dd95f5138a9eb830f708bf8f669e89b">linkRefs</a>.emplace(</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">.lower().str(),<a href="/web-doxygen/docs/api/structs/markdown/private/linkref">LinkRef</a>(link,title));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3383</span><span class="doxyLineContent"><span class="doxyHighlight">        i=ref+pi;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3384</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=i+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3385</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3386</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#acea395582e617dd69781da74f320161e">isFencedCodeBlock</a>(data.substr(pi),currentIndent,lang,blockStart,blockEnd,blockOffset))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3387</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3388</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("Found FencedCodeBlock lang='%s' start=%d end=%d code={%s}\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3389</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//       qPrint(lang),blockStart,blockEnd,QCString(data+pi+blockStart).left(blockEnd-blockStart).data());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3390</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a494fc3fc6c848a37caa06e5d85854ffe">writeFencedCodeBlock</a>(data.substr(pi),lang.<a href="/web-doxygen/docs/api/classes/qcstring/#ac853c00269498870dfefa8185f2ee79a">view</a>(),blockStart,blockEnd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3391</span><span class="doxyLineContent"><span class="doxyHighlight">        i=pi+blockOffset;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3392</span><span class="doxyLineContent"><span class="doxyHighlight">        pi=std::string::npos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3393</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=i+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3394</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3395</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3396</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a76c8e357497a35b016ee0289e26ee0dd">isCodeBlock</a>(data.substr(i,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-i),i,blockIndent))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3397</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3398</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// skip previous line (it is empty anyway)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3399</span><span class="doxyLineContent"><span class="doxyHighlight">        i+=<a href="#a79fd3fae285ba1f1beeb84c8e858bf46">writeCodeBlock</a>(data.substr(i),blockIndent);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3400</span><span class="doxyLineContent"><span class="doxyHighlight">        pi=std::string::npos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3401</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=i+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3402</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3403</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3404</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#aefadebc5df285d25ef8121a87639323e">isTableBlock</a>(data.substr(pi)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3405</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3406</span><span class="doxyLineContent"><span class="doxyHighlight">        i=pi+<a href="#a21b82aade2e5a369ec438f0cd49f8107">writeTableBlock</a>(data.substr(pi));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3407</span><span class="doxyLineContent"><span class="doxyHighlight">        pi=std::string::npos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3408</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=i+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3409</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3410</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3411</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3412</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3413</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af7ceebe6b90c368816a6d9bd0ca501c0">writeOneLineHeaderOrRuler</a>(data.substr(pi,i-pi));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3414</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3415</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3416</span><span class="doxyLineContent"><span class="doxyHighlight">    pi=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3417</span><span class="doxyLineContent"><span class="doxyHighlight">    i=<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3418</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3419</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("last line %d size=%d\n",i,size);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3420</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pi!=std::string::npos &amp;&amp; pi&lt;data.size()) </span><span class="doxyHighlightComment">// deal with the last line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3421</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3422</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a3712f14d18ec5d547f7c55413abdb9fb">isLinkRef</a>(data.substr(pi),</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,link,title))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3423</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3424</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("found link ref: id='%s' link='%s' title='%s'\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3425</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//    qPrint(id),qPrint(link),qPrint(title));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3426</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5dd95f5138a9eb830f708bf8f669e89b">linkRefs</a>.emplace(</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">.lower().str(),<a href="/web-doxygen/docs/api/structs/markdown/private/linkref">LinkRef</a>(link,title));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3427</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3428</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3429</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3430</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af7ceebe6b90c368816a6d9bd0ca501c0">writeOneLineHeaderOrRuler</a>(data.substr(pi));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3431</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3432</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3433</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3434</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3435</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a918fa8a25e6bc30b364b55bc19a5dafd">codeBlockIndent</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="#a46231fc8d72391f38170f184dd956ed1">extractTitleId</a>, <a href="#aad2fb530e3d19a77de38a8c1b633b786">findEndOfLine</a>, <a href="#a6d7d4814ead5c919439c6b2d681e2ce7">isBlockCommand</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a76c8e357497a35b016ee0289e26ee0dd">isCodeBlock</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a7b54fef3d70eef54bd49dda068709f43">isEmptyLine</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a4808ea595b45102dac19491e80d2ac9c">isEndOfList</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#acea395582e617dd69781da74f320161e">isFencedCodeBlock</a>, <a href="#a5628c6052a120856d53921f8746d0251">isHeaderline</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a3712f14d18ec5d547f7c55413abdb9fb">isLinkRef</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ad0a6b598945a869cd184d17fe1f16812">isListMarker</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#aefadebc5df285d25ef8121a87639323e">isTableBlock</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#a5dd95f5138a9eb830f708bf8f669e89b">linkRefs</a>, <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a19faae287d13ccea75b1d5a0eb110d97">qstrncmp</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac853c00269498870dfefa8185f2ee79a">QCString::view</a>, <a href="#a79fd3fae285ba1f1beeb84c8e858bf46">writeCodeBlock</a>, <a href="#a494fc3fc6c848a37caa06e5d85854ffe">writeFencedCodeBlock</a>, <a href="#af7ceebe6b90c368816a6d9bd0ca501c0">writeOneLineHeaderOrRuler</a> and <a href="#a21b82aade2e5a369ec438f0cd49f8107">writeTableBlock</a>.
</div>
</div>

### processCodeSpan() {#a42dc4e1d481af0574e750df55678d54d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int Markdown::Private::processCodeSpan (std::string_view data, size_t offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<code> ` </code> parsing a code span (assuming codespan != 0)

Definition at line 145 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a42dc4e1d481af0574e750df55678d54d">1629</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a42dc4e1d481af0574e750df55678d54d">Markdown::Private::processCodeSpan</a>(std::string_view data,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1630</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1631</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}'"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1632</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1633</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1634</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/* counting the number of backticks in the delimiter */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1635</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> nb=0, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1636</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (nb&lt;size &amp;&amp; data[nb]==</span><span class="doxyHighlightCharLiteral">'`'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1637</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1638</span><span class="doxyLineContent"><span class="doxyHighlight">    nb++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1639</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1640</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1641</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/* finding the next delimiter */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1642</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1643</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> pc = </span><span class="doxyHighlightCharLiteral">'`'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1644</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=nb; <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>&lt;size &amp;&amp; i&lt;nb; <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1645</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1646</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>]==</span><span class="doxyHighlightCharLiteral">'`'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1647</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1648</span><span class="doxyLineContent"><span class="doxyHighlight">      i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1649</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1650</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1651</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1652</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// consecutive newlines</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1653</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pc == </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1654</span><span class="doxyLineContent"><span class="doxyHighlight">      pc = </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1655</span><span class="doxyLineContent"><span class="doxyHighlight">      i = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1656</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1657</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>]==</span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight"> &amp;&amp; nb==1 &amp;&amp; (<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>==size-1 || (<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>+1&lt;size &amp;&amp; !<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a243e6edb7617162067edc19f3f20bdb9">isIdChar</a>(data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>+1]))))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1658</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightComment">// look for quoted strings like 'some word', but skip strings like `it's cool`</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1659</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"&amp;lsquo;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1660</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=data.substr(nb,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-nb);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1661</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"&amp;rsquo;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1662</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1663</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1664</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1665</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1666</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>]!=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) pc = data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1667</span><span class="doxyLineContent"><span class="doxyHighlight">      i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1668</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1669</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1670</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i &lt; nb &amp;&amp; end &gt;= size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1671</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1672</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;  </span><span class="doxyHighlightComment">// no matching delimiter</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1673</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1674</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1675</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("found code span '%s'\n",qPrint(QCString(data+f_begin).left(f_end-f_begin)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1676</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1677</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/* real code span */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1678</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nb+nb &lt; <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1679</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1680</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> codeFragment = data.substr(nb, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-nb-nb);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1681</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"&lt;tt&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1682</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a5ba50f3a46a2d635f06fbc600356ee4a">escapeSpecialChars</a>(codeFragment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1683</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"&lt;/tt&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1684</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1685</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1686</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1687</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO\_TRACE\_EXIT</a>, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a5ba50f3a46a2d635f06fbc600356ee4a">escapeSpecialChars</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a243e6edb7617162067edc19f3f20bdb9">isIdChar</a>, <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.
</div>
</div>

### processEmphasis() {#a9ac768dc126226996971e96ef20923aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int Markdown::Private::processEmphasis (std::string_view data, size_t offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 139 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9ac768dc126226996971e96ef20923aa">1105</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a9ac768dc126226996971e96ef20923aa">Markdown::Private::processEmphasis</a>(std::string_view data,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> offset)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1106</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1107</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}' offset={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data),offset);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1108</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1109</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1110</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((offset&gt;0 &amp;&amp; !<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#acda15964dfc7b413ab5abb3fca10a1ef">isOpenEmphChar</a>(data.data()[-1])) || </span><span class="doxyHighlightComment">// invalid char before * or _</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1111</span><span class="doxyLineContent"><span class="doxyHighlight">      (size&gt;1 &amp;&amp; data[0]!=data[1] &amp;&amp; !(<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a243e6edb7617162067edc19f3f20bdb9">isIdChar</a>(data[1]) || <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#aebe67bf622b3e6fa702be02ee5087910">extraChar</a>(data[1]))) || </span><span class="doxyHighlightComment">// invalid char after * or _</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1112</span><span class="doxyLineContent"><span class="doxyHighlight">      (size&gt;2 &amp;&amp; data[0]==data[1] &amp;&amp; !(<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a243e6edb7617162067edc19f3f20bdb9">isIdChar</a>(data[2]) || <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#aebe67bf622b3e6fa702be02ee5087910">extraChar</a>(data[2]))))   </span><span class="doxyHighlightComment">// invalid char after ** or __</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1113</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1114</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"invalid surrounding characters"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1115</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1116</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1117</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1118</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = data[0];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1119</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> ret = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1120</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (size&gt;2 &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'~'</span><span class="doxyHighlight"> &amp;&amp; data[1]!=c) </span><span class="doxyHighlightComment">// _bla or *bla</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1121</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1122</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// whitespace cannot follow an opening emphasis</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1123</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[1]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || data[1]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight"> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1124</span><span class="doxyLineContent"><span class="doxyHighlight">        (ret = <a href="#a0bb20b07bce14eca215477b9ec05adbd">processEmphasis1</a>(data.substr(1), c)) == 0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1125</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1126</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1127</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1128</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,ret+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1129</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> ret+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1130</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1131</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (size&gt;3 &amp;&amp; data[1]==c &amp;&amp; data[2]!=c) </span><span class="doxyHighlightComment">// __bla or **bla</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1132</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1133</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[2]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || data[2]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight"> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1134</span><span class="doxyLineContent"><span class="doxyHighlight">        (ret = <a href="#abbb763f2449b932ef3468560e30a0478">processEmphasis2</a>(data.substr(2), c)) == 0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1135</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1136</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1137</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1138</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,ret+2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1139</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> ret+2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1140</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1141</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (size&gt;4 &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'~'</span><span class="doxyHighlight"> &amp;&amp; data[1]==c &amp;&amp; data[2]==c &amp;&amp; data[3]!=c) </span><span class="doxyHighlightComment">// ___bla or ***bla</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1142</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1143</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[3]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || data[3]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight"> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1144</span><span class="doxyLineContent"><span class="doxyHighlight">        (ret = <a href="#a4041a1e946c4402894bfff49b611e63b">processEmphasis3</a>(data.substr(3), c)) == 0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1145</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1146</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1147</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1148</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,ret+3);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1149</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> ret+3;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1150</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1151</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1152</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO\_TRACE\_EXIT</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#aebe67bf622b3e6fa702be02ee5087910">extraChar</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a243e6edb7617162067edc19f3f20bdb9">isIdChar</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#acda15964dfc7b413ab5abb3fca10a1ef">isOpenEmphChar</a>, <a href="#a0bb20b07bce14eca215477b9ec05adbd">processEmphasis1</a>, <a href="#abbb763f2449b932ef3468560e30a0478">processEmphasis2</a>, <a href="#a4041a1e946c4402894bfff49b611e63b">processEmphasis3</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.
</div>
</div>

### processEmphasis1() {#a0bb20b07bce14eca215477b9ec05adbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int Markdown::Private::processEmphasis1 (std::string_view data, char c)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

process single emphasis

Definition at line 140 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0bb20b07bce14eca215477b9ec05adbd">815</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a0bb20b07bce14eca215477b9ec05adbd">Markdown::Private::processEmphasis1</a>(std::string_view data, </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">816</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">817</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}' c={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data),c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">818</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">819</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">820</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">821</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/* skipping one symbol if coming from emph3 */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">822</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (size&gt;1 &amp;&amp; data[0]==c &amp;&amp; data[1]==c) { i=1; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">823</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">824</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">825</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">826</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len = <a href="#a5b661698b94e4b37748ee38025784690">findEmphasisChar</a>(data.substr(i), c, 1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">827</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (len==0) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">828</span><span class="doxyLineContent"><span class="doxyHighlight">    i+=len;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">829</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&gt;=size) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">830</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">831</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i+1&lt;size &amp;&amp; data[i+1]==c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">832</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">833</span><span class="doxyLineContent"><span class="doxyHighlight">      i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">834</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">835</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">836</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==c &amp;&amp; data[i-1]!=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> &amp;&amp; data[i-1]!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">837</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">838</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"&lt;em&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">839</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ac0a9e3273eb76713a9e197d5be61e11a">processInline</a>(data.substr(0,i));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">840</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"&lt;/em&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">841</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,i+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">842</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(i+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">843</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">844</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">845</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">846</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO\_TRACE\_EXIT</a>, <a href="#a5b661698b94e4b37748ee38025784690">findEmphasisChar</a>, <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>, <a href="#ac0a9e3273eb76713a9e197d5be61e11a">processInline</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.

Referenced by <a href="#a9ac768dc126226996971e96ef20923aa">processEmphasis</a> and <a href="#a4041a1e946c4402894bfff49b611e63b">processEmphasis3</a>.
</div>
</div>

### processEmphasis2() {#abbb763f2449b932ef3468560e30a0478}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int Markdown::Private::processEmphasis2 (std::string_view data, char c)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

process double emphasis

Definition at line 141 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abbb763f2449b932ef3468560e30a0478">849</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#abbb763f2449b932ef3468560e30a0478">Markdown::Private::processEmphasis2</a>(std::string_view data, </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">850</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">851</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}' c={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data),c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">852</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">853</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">854</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">855</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">856</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">857</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len = <a href="#a5b661698b94e4b37748ee38025784690">findEmphasisChar</a>(data.substr(i), c, 2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">858</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (len==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">859</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">860</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">861</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">862</span><span class="doxyLineContent"><span class="doxyHighlight">    i += len;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">863</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i+1&lt;size &amp;&amp; data[i]==c &amp;&amp; data[i+1]==c &amp;&amp; i &amp;&amp; data[i-1]!=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> &amp;&amp; data[i-1]!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">864</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">865</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c == </span><span class="doxyHighlightCharLiteral">'~'</span><span class="doxyHighlight">) <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"&lt;strike&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">866</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"&lt;strong&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">867</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ac0a9e3273eb76713a9e197d5be61e11a">processInline</a>(data.substr(0,i));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">868</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c == </span><span class="doxyHighlightCharLiteral">'~'</span><span class="doxyHighlight">) <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"&lt;/strike&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">869</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"&lt;/strong&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">870</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,i+2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">871</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(i+2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">872</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">873</span><span class="doxyLineContent"><span class="doxyHighlight">    i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">874</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">875</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">876</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO\_TRACE\_EXIT</a>, <a href="#a5b661698b94e4b37748ee38025784690">findEmphasisChar</a>, <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>, <a href="#ac0a9e3273eb76713a9e197d5be61e11a">processInline</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.

Referenced by <a href="#a9ac768dc126226996971e96ef20923aa">processEmphasis</a> and <a href="#a4041a1e946c4402894bfff49b611e63b">processEmphasis3</a>.
</div>
</div>

### processEmphasis3() {#a4041a1e946c4402894bfff49b611e63b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int Markdown::Private::processEmphasis3 (std::string_view data, char c)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Parsing triple emphasis.


Finds the first closing tag, and delegates to the other emph

Definition at line 142 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4041a1e946c4402894bfff49b611e63b">881</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a4041a1e946c4402894bfff49b611e63b">Markdown::Private::processEmphasis3</a>(std::string_view data,</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">882</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">883</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}' c={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data),c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">884</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">885</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">886</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">887</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">888</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">889</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len = <a href="#a5b661698b94e4b37748ee38025784690">findEmphasisChar</a>(data.substr(i), c, 3);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">890</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (len==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">891</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">892</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">893</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">894</span><span class="doxyLineContent"><span class="doxyHighlight">    i+=len;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">895</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">896</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">/* skip whitespace preceded symbols */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">897</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]!=c || data[i-1]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || data[i-1]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">898</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">899</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">900</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">901</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">902</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i+2&lt;size &amp;&amp; data[i+1]==c &amp;&amp; data[i+2]==c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">903</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">904</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"&lt;em&gt;&lt;strong&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">905</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ac0a9e3273eb76713a9e197d5be61e11a">processInline</a>(data.substr(0,i));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">906</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"&lt;/strong&gt;&lt;/em&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">907</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,i+3);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">908</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(i+3);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">909</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">910</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i+1&lt;size &amp;&amp; data[i+1]==c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">911</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">912</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// double symbol found, handing over to emph1</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">913</span><span class="doxyLineContent"><span class="doxyHighlight">      len = <a href="#a0bb20b07bce14eca215477b9ec05adbd">processEmphasis1</a>(std::string_view(data.data()-2, size+2), c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">914</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (len==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">915</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">916</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">917</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">918</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">919</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">920</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,len-2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">921</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(len - 2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">922</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">923</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">924</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">925</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">926</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// single symbol found, handing over to emph2</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">927</span><span class="doxyLineContent"><span class="doxyHighlight">      len = <a href="#abbb763f2449b932ef3468560e30a0478">processEmphasis2</a>(std::string_view(data.data()-1, size+1), c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">928</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (len==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">929</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">930</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">931</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">932</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">933</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">934</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,len-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">935</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(len - 1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">936</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">937</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">938</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">939</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">940</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO\_TRACE\_EXIT</a>, <a href="#a5b661698b94e4b37748ee38025784690">findEmphasisChar</a>, <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>, <a href="#a0bb20b07bce14eca215477b9ec05adbd">processEmphasis1</a>, <a href="#abbb763f2449b932ef3468560e30a0478">processEmphasis2</a>, <a href="#ac0a9e3273eb76713a9e197d5be61e11a">processInline</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.

Referenced by <a href="#a9ac768dc126226996971e96ef20923aa">processEmphasis</a>.
</div>
</div>

### processHtmlTag() {#a7ef2d648f867a25fac44f095b89630c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int Markdown::Private::processHtmlTag (std::string_view data, size_t offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 138 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7ef2d648f867a25fac44f095b89630c6">1099</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a7ef2d648f867a25fac44f095b89630c6">Markdown::Private::processHtmlTag</a>(std::string_view data,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> offset)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1100</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1101</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}' offset={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data),offset);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1102</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aa4f4085dfd3e73ae354c7cfd6fa69faf">processHtmlTagWrite</a>(data,offset,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1103</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="#aa4f4085dfd3e73ae354c7cfd6fa69faf">processHtmlTagWrite</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.
</div>
</div>

### processHtmlTagWrite() {#aa4f4085dfd3e73ae354c7cfd6fa69faf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int Markdown::Private::processHtmlTagWrite (std::string_view data, size_t offset, bool doWrite)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Process a HTML tag.


Note that


<pre><code>..
</code></pre>


are treated specially, in the sense that all code inside is written unprocessed

Definition at line 137 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa4f4085dfd3e73ae354c7cfd6fa69faf">1009</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#aa4f4085dfd3e73ae354c7cfd6fa69faf">Markdown::Private::processHtmlTagWrite</a>(std::string_view data,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> offset,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> doWrite)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1010</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1011</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}' offset={} doWrite={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data),offset,doWrite);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1012</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (offset&gt;0 &amp;&amp; data.data()[-1]==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; } </span><span class="doxyHighlightComment">// escaped &lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1013</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1014</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1015</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1016</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// find the end of the html tag</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1017</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1018</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> l=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1019</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// compute length of the tag name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1020</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a243e6edb7617162067edc19f3f20bdb9">isIdChar</a>(data[i])) i++,l++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1021</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tagName(data.substr(1,i-1));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1022</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tagName.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>()==</span><span class="doxyHighlightStringLiteral">"pre"</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// found &lt;pre&gt; tag</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1023</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1024</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> insideStr=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1025</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i+6&lt;size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1026</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1027</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c=data[i];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1028</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!insideStr &amp;&amp; c==</span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// potential start of html tag</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1029</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1030</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i+1]==</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight"> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1031</span><span class="doxyLineContent"><span class="doxyHighlight">            tolower(data[i+2])==</span><span class="doxyHighlightCharLiteral">'p'</span><span class="doxyHighlight"> &amp;&amp; tolower(data[i+3])==</span><span class="doxyHighlightCharLiteral">'r'</span><span class="doxyHighlight"> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1032</span><span class="doxyLineContent"><span class="doxyHighlight">            tolower(data[i+4])==</span><span class="doxyHighlightCharLiteral">'e'</span><span class="doxyHighlight"> &amp;&amp; tolower(data[i+5])==</span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1033</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightComment">// found &lt;/pre&gt; tag, copy from start to end of tag</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1034</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doWrite) <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=data.substr(0,i+6);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1035</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//printf("found &lt;pre&gt;..&lt;/pre&gt; [%d..%d]\n",0,i+6);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1036</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,i+6);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1037</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(i+6);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1038</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1039</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1040</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (insideStr &amp;&amp; c==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1041</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1042</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i-1]!=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">) insideStr=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1043</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1044</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1045</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1046</span><span class="doxyLineContent"><span class="doxyHighlight">        insideStr=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1047</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1048</span><span class="doxyLineContent"><span class="doxyHighlight">      i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1049</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1050</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1051</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// some other html tag</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1052</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1053</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (l&gt;0 &amp;&amp; i&lt;size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1054</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1055</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight"> &amp;&amp; i+1&lt;size &amp;&amp; data[i+1]==</span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// &lt;bla/&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1056</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1057</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("Found htmlTag={%s}\n",qPrint(QCString(data).left(i+2)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1058</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doWrite) <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=data.substr(0,i+2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1059</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,i+2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1060</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(i+2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1061</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1062</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// &lt;bla&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1063</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1064</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("Found htmlTag={%s}\n",qPrint(QCString(data).left(i+1)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1065</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doWrite) <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=data.substr(0,i+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1066</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,i+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1067</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(i+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1068</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1069</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// &lt;bla attr=...</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1070</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1071</span><span class="doxyLineContent"><span class="doxyHighlight">        i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1072</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> insideAttr=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1073</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1074</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1075</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!insideAttr &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1076</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1077</span><span class="doxyLineContent"><span class="doxyHighlight">            insideAttr=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1078</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1079</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight"> &amp;&amp; data[i-1]!=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1080</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1081</span><span class="doxyLineContent"><span class="doxyHighlight">            insideAttr=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1082</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1083</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!insideAttr &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// found end of tag</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1084</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1085</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">//printf("Found htmlTag={%s}\n",qPrint(QCString(data).left(i+1)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1086</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doWrite) <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=data.substr(0,i+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1087</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,i+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1088</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(i+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1089</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1090</span><span class="doxyLineContent"><span class="doxyHighlight">          i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1091</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1092</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1093</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1094</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1095</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"not a valid html tag"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1096</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1097</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO\_TRACE\_EXIT</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a243e6edb7617162067edc19f3f20bdb9">isIdChar</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>, <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.

Referenced by <a href="#aad2fb530e3d19a77de38a8c1b633b786">findEndOfLine</a> and <a href="#a7ef2d648f867a25fac44f095b89630c6">processHtmlTag</a>.
</div>
</div>

### processInline() {#ac0a9e3273eb76713a9e197d5be61e11a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Markdown::Private::processInline (std::string_view data)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 150 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac0a9e3273eb76713a9e197d5be61e11a">1775</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac0a9e3273eb76713a9e197d5be61e11a">Markdown::Private::processInline</a>(std::string_view data)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1776</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1777</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}'"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1778</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1779</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1780</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a38ce2a429b8c4a268507157a45cac671">Action_t</a> action;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1781</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1782</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1783</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1784</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// skip over characters that do not trigger a specific action</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1785</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>&lt;size &amp;&amp; ((action=<a href="#afbee8604b9f0ac5704c3ee99a7f4c7b9">actions</a>[</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight">uint8_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>])])==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)) <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1786</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// and add them to the output</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1787</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=data.substr(i,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1788</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>&gt;=size) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1789</span><span class="doxyLineContent"><span class="doxyHighlight">    i=<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1790</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// do the action matching a special character at i</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1791</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> iend = action(data.substr(i),i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1792</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (iend&lt;=0) </span><span class="doxyHighlightComment">// update end</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1793</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1794</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=i+1-iend;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1795</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1796</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// skip until end</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1797</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1798</span><span class="doxyLineContent"><span class="doxyHighlight">      i+=iend;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1799</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1800</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1801</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1802</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#afbee8604b9f0ac5704c3ee99a7f4c7b9">actions</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.

Referenced by <a href="#a0bb20b07bce14eca215477b9ec05adbd">processEmphasis1</a>, <a href="#abbb763f2449b932ef3468560e30a0478">processEmphasis2</a>, <a href="#a4041a1e946c4402894bfff49b611e63b">processEmphasis3</a> and <a href="#a9b99b7f5084eb08d7ffe43f3fbe79d69">processLink</a>.
</div>
</div>

### processLink() {#a9b99b7f5084eb08d7ffe43f3fbe79d69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int Markdown::Private::processLink (std::string_view data, size_t offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 147 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9b99b7f5084eb08d7ffe43f3fbe79d69">1197</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a9b99b7f5084eb08d7ffe43f3fbe79d69">Markdown::Private::processLink</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string_view data,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> offset)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1198</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1199</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}' offset={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data),offset);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1200</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1201</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> content;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1202</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> link;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1203</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> title;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1204</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isImageLink = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1205</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isImageInline = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1206</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isToc = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1207</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1208</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[0]==</span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1209</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1210</span><span class="doxyLineContent"><span class="doxyHighlight">    isImageLink = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1211</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (size&lt;2 || data[1]!=</span><span class="doxyHighlightCharLiteral">'['</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1212</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1213</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1214</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1215</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1216</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// if there is non-whitespace before the ![ within the scope of two new lines, the image</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1217</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// is considered inlined, i.e. the image is not preceded by an empty line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1218</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> numNLsNeeded=2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1219</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> pos = -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1220</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (pos&gt;=-</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(offset) &amp;&amp; numNLsNeeded&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1221</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1222</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data.data()[pos]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) numNLsNeeded--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1223</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data.data()[pos]!=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// found non-whitespace, stop searching</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1224</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1225</span><span class="doxyLineContent"><span class="doxyHighlight">        isImageInline=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1226</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1227</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1228</span><span class="doxyLineContent"><span class="doxyHighlight">      pos--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1229</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1230</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// skip '!['</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1231</span><span class="doxyLineContent"><span class="doxyHighlight">    i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1232</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1233</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> contentStart=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1234</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1235</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> nlTotal=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1236</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> nl=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1237</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// find the matching ]</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1238</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1239</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1240</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i-1]==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// skip escaped characters</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1241</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1242</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1243</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'['</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1244</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1245</span><span class="doxyLineContent"><span class="doxyHighlight">      level++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1246</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1247</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">']'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1248</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1249</span><span class="doxyLineContent"><span class="doxyHighlight">      level--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1250</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (level&lt;=0) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1251</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1252</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1253</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1254</span><span class="doxyLineContent"><span class="doxyHighlight">      nl++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1255</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nl&gt;1) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; } </span><span class="doxyHighlightComment">// only allow one newline in the content</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1256</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1257</span><span class="doxyLineContent"><span class="doxyHighlight">    i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1258</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1259</span><span class="doxyLineContent"><span class="doxyHighlight">  nlTotal += nl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1260</span><span class="doxyLineContent"><span class="doxyHighlight">  nl = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1261</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&gt;=size) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; </span><span class="doxyHighlightComment">// premature end of comment -&gt; no link</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1262</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> contentEnd=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1263</span><span class="doxyLineContent"><span class="doxyHighlight">  content = data.substr(contentStart,contentEnd-contentStart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1264</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("processLink: content={%s}\n",qPrint(content));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1265</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!isImageLink &amp;&amp; content.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; } </span><span class="doxyHighlightComment">// no link text</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1266</span><span class="doxyLineContent"><span class="doxyHighlight">  i++; </span><span class="doxyHighlightComment">// skip over ]</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1267</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1268</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> whiteSpace = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1269</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// skip whitespace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1270</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) { whiteSpace = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; i++; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1271</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// one newline allowed here</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1272</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1273</span><span class="doxyLineContent"><span class="doxyHighlight">    whiteSpace = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1274</span><span class="doxyLineContent"><span class="doxyHighlight">    i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1275</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// skip more whitespace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1276</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1277</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1278</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (whiteSpace &amp;&amp; i&lt;size &amp;&amp; (data[i]==</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight"> || data[i]==</span><span class="doxyHighlightCharLiteral">'['</span><span class="doxyHighlight">)) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1279</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1280</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> explicitTitle=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1281</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// inline link</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1282</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1283</span><span class="doxyLineContent"><span class="doxyHighlight">    i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1284</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1285</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> uriFormat=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1286</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">) { i++; uriFormat=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1287</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> linkStart=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1288</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> braceCount=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1289</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]!=</span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight"> &amp;&amp; data[i]!=</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight"> &amp;&amp; braceCount&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1290</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1291</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// unexpected EOL</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1292</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1293</span><span class="doxyLineContent"><span class="doxyHighlight">        nl++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1294</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nl&gt;1) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1295</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1296</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1297</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1298</span><span class="doxyLineContent"><span class="doxyHighlight">        braceCount++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1299</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1300</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1301</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1302</span><span class="doxyLineContent"><span class="doxyHighlight">        braceCount--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1303</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1304</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (braceCount&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1305</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1306</span><span class="doxyLineContent"><span class="doxyHighlight">        i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1307</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1308</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1309</span><span class="doxyLineContent"><span class="doxyHighlight">    nlTotal += nl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1310</span><span class="doxyLineContent"><span class="doxyHighlight">    nl = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1311</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&gt;=size || data[i]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1312</span><span class="doxyLineContent"><span class="doxyHighlight">    link = data.substr(linkStart,i-linkStart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1313</span><span class="doxyLineContent"><span class="doxyHighlight">    link = link.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1314</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("processLink: link={%s}\n",qPrint(link));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1315</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (link.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1316</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (uriFormat &amp;&amp; link.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(link.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-1)==</span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight">) link=link.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(link.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1317</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1318</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// optional title</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1319</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight"> || data[i]==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1320</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1321</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = data[i];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1322</span><span class="doxyLineContent"><span class="doxyHighlight">      i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1323</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> titleStart=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1324</span><span class="doxyLineContent"><span class="doxyHighlight">      nl=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1325</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1326</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1327</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1328</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1329</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nl&gt;1) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1330</span><span class="doxyLineContent"><span class="doxyHighlight">          nl++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1331</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1332</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// escaped char in string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1333</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1334</span><span class="doxyLineContent"><span class="doxyHighlight">          i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1335</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1336</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1337</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1338</span><span class="doxyLineContent"><span class="doxyHighlight">          i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1339</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1340</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1341</span><span class="doxyLineContent"><span class="doxyHighlight">        i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1342</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1343</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&gt;=size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1344</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1345</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1346</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1347</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> titleEnd = i-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1348</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// search back for closing marker</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1349</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (titleEnd&gt;titleStart &amp;&amp; data[titleEnd]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) titleEnd--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1350</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[titleEnd]==c) </span><span class="doxyHighlightComment">// found it</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1351</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1352</span><span class="doxyLineContent"><span class="doxyHighlight">        title = data.substr(titleStart,titleEnd-titleStart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1353</span><span class="doxyLineContent"><span class="doxyHighlight">        explicitTitle=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1354</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1355</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1356</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">)i++; </span><span class="doxyHighlightComment">// remove space after the closing quote and the closing bracket</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1357</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i] == </span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// the end bracket</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1358</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// illegal</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1359</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1360</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1361</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1362</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1363</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1364</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1365</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1366</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1367</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1368</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1369</span><span class="doxyLineContent"><span class="doxyHighlight">    i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1370</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1371</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">'['</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// reference link</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1372</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1373</span><span class="doxyLineContent"><span class="doxyHighlight">    i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1374</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> linkStart=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1375</span><span class="doxyLineContent"><span class="doxyHighlight">    nl=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1376</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// find matching ]</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1377</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]!=</span><span class="doxyHighlightCharLiteral">']'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1378</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1379</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1380</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1381</span><span class="doxyLineContent"><span class="doxyHighlight">        nl++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1382</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nl&gt;1) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1383</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1384</span><span class="doxyLineContent"><span class="doxyHighlight">      i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1385</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1386</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&gt;=size) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1387</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// extract link</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1388</span><span class="doxyLineContent"><span class="doxyHighlight">    link = data.substr(linkStart,i-linkStart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1389</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("processLink: link={%s}\n",qPrint(link));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1390</span><span class="doxyLineContent"><span class="doxyHighlight">    link = link.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1391</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (link.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightComment">// shortcut link</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1392</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1393</span><span class="doxyLineContent"><span class="doxyHighlight">      link=content;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1394</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1395</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// lookup reference</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1396</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> link_lower = link.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1397</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> lr_it=<a href="#a5dd95f5138a9eb830f708bf8f669e89b">linkRefs</a>.find(link_lower.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1398</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lr_it!=<a href="#a5dd95f5138a9eb830f708bf8f669e89b">linkRefs</a>.end()) </span><span class="doxyHighlightComment">// found it</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1399</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1400</span><span class="doxyLineContent"><span class="doxyHighlight">      link  = lr_it-&gt;second.link;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1401</span><span class="doxyLineContent"><span class="doxyHighlight">      title = lr_it-&gt;second.title;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1402</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("processLink: ref: link={%s} title={%s}\n",qPrint(link),qPrint(title));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1403</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1404</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// reference not found!</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1405</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1406</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("processLink: ref {%s} do not exist\n",link.qPrint(lower()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1407</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1408</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1409</span><span class="doxyLineContent"><span class="doxyHighlight">    i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1410</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1411</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]!=</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight"> &amp;&amp; !content.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightComment">// minimal link ref notation [some id]</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1412</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1413</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> content_lower = content.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1414</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> lr_it = <a href="#a5dd95f5138a9eb830f708bf8f669e89b">linkRefs</a>.find(content_lower.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1415</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("processLink: minimal link {%s} lr=%p",qPrint(content),lr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1416</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lr_it!=<a href="#a5dd95f5138a9eb830f708bf8f669e89b">linkRefs</a>.end()) </span><span class="doxyHighlightComment">// found it</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1417</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1418</span><span class="doxyLineContent"><span class="doxyHighlight">      link  = lr_it-&gt;second.link;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1419</span><span class="doxyLineContent"><span class="doxyHighlight">      title = lr_it-&gt;second.title;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1420</span><span class="doxyLineContent"><span class="doxyHighlight">      explicitTitle=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1421</span><span class="doxyLineContent"><span class="doxyHighlight">      i=contentEnd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1422</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1423</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (content==</span><span class="doxyHighlightStringLiteral">"TOC"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1424</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1425</span><span class="doxyLineContent"><span class="doxyHighlight">      isToc=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1426</span><span class="doxyLineContent"><span class="doxyHighlight">      i=contentEnd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1427</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1428</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1429</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1430</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1431</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1432</span><span class="doxyLineContent"><span class="doxyHighlight">    i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1433</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1434</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1435</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1436</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1437</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1438</span><span class="doxyLineContent"><span class="doxyHighlight">  nlTotal += nl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1439</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1440</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// search for optional image attributes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1441</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> attributes;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1442</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isImageLink)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1443</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1444</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> j = i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1445</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// skip over whitespace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1446</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (j&lt;size &amp;&amp; data[j]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) { j++; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1447</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (j&lt;size &amp;&amp; data[j]==</span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// we have attributes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1448</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1449</span><span class="doxyLineContent"><span class="doxyHighlight">      i = j;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1450</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// skip over '{'</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1451</span><span class="doxyLineContent"><span class="doxyHighlight">      i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1452</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> attributesStart=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1453</span><span class="doxyLineContent"><span class="doxyHighlight">      nl=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1454</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// find the matching '}'</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1455</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1456</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1457</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i-1]==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// skip escaped characters</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1458</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1459</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1460</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1461</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1462</span><span class="doxyLineContent"><span class="doxyHighlight">          level++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1463</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1464</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'}'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1465</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1466</span><span class="doxyLineContent"><span class="doxyHighlight">          level--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1467</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (level&lt;=0) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1468</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1469</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1470</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1471</span><span class="doxyLineContent"><span class="doxyHighlight">          nl++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1472</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nl&gt;1) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; } </span><span class="doxyHighlightComment">// only allow one newline in the content</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1473</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1474</span><span class="doxyLineContent"><span class="doxyHighlight">        i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1475</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1476</span><span class="doxyLineContent"><span class="doxyHighlight">      nlTotal += nl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1477</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&gt;=size) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; </span><span class="doxyHighlightComment">// premature end of comment -&gt; no attributes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1478</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> attributesEnd=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1479</span><span class="doxyLineContent"><span class="doxyHighlight">      attributes = data.substr(attributesStart,attributesEnd-attributesStart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1480</span><span class="doxyLineContent"><span class="doxyHighlight">      i++; </span><span class="doxyHighlightComment">// skip over '}'</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1481</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1482</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!isImageInline)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1483</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1484</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// if there is non-whitespace after the image within the scope of two new lines, the image</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1485</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// is considered inlined, i.e. the image is not followed by an empty line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1486</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> numNLsNeeded=2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1487</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pos = i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1488</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (pos&lt;size &amp;&amp; numNLsNeeded&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1489</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1490</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[pos]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) numNLsNeeded--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1491</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[pos]!=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// found non-whitespace, stop searching</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1492</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1493</span><span class="doxyLineContent"><span class="doxyHighlight">          isImageInline=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1494</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1495</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1496</span><span class="doxyLineContent"><span class="doxyHighlight">        pos++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1497</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1498</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1499</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1500</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1501</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isToc) </span><span class="doxyHighlightComment">// special case for [TOC]</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1502</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1503</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> toc_level = <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(TOC_INCLUDE_HEADINGS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1504</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (toc_level&gt;=<a href="/web-doxygen/docs/api/classes/sectiontype/#ab44dce28d2b68c6514acbe2415a8a4d7">SectionType::MinLevel</a> &amp;&amp; toc_level&lt;=<a href="/web-doxygen/docs/api/classes/sectiontype/#a2f832ab2bf817c8581feb03e123f09d5">SectionType::MaxLevel</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1505</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1506</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"@tableofcontents{html:"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1507</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">setNum</a>(toc_level);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1508</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1509</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1510</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1511</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isImageLink)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1512</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1513</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ambig = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1514</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1515</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (link.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"@ref "</span><span class="doxyHighlight">)!=-1 || link.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"\\ref "</span><span class="doxyHighlight">)!=-1 ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1516</span><span class="doxyLineContent"><span class="doxyHighlight">        (fd=<a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#a7062fae1e1507b5c093fe5b71a866371">Doxygen::imageNameLinkedMap</a>,link,ambig)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1517</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// assume doxygen symbol link or local image link</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1518</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1519</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// check if different handling is needed per format</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1520</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1213861d8af699057686e457bce66509">writeMarkdownImage</a>(</span><span class="doxyHighlightStringLiteral">"html"</span><span class="doxyHighlight">,    isImageInline, explicitTitle, title, content, link, attributes, fd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1521</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1213861d8af699057686e457bce66509">writeMarkdownImage</a>(</span><span class="doxyHighlightStringLiteral">"latex"</span><span class="doxyHighlight">,   isImageInline, explicitTitle, title, content, link, attributes, fd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1522</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1213861d8af699057686e457bce66509">writeMarkdownImage</a>(</span><span class="doxyHighlightStringLiteral">"rtf"</span><span class="doxyHighlight">,     isImageInline, explicitTitle, title, content, link, attributes, fd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1523</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1213861d8af699057686e457bce66509">writeMarkdownImage</a>(</span><span class="doxyHighlightStringLiteral">"docbook"</span><span class="doxyHighlight">, isImageInline, explicitTitle, title, content, link, attributes, fd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1524</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1213861d8af699057686e457bce66509">writeMarkdownImage</a>(</span><span class="doxyHighlightStringLiteral">"xml"</span><span class="doxyHighlight">,     isImageInline, explicitTitle, title, content, link, attributes, fd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1525</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1526</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1527</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1528</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"&lt;img src=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1529</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=link;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1530</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"\" alt=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1531</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=content;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1532</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1533</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!title.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1534</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1535</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">" title=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1536</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(title.<a href="/web-doxygen/docs/api/classes/qcstring/#a8d6ace0deb439b916b9f97f54a6c9cc2">simplifyWhiteSpace</a>(),</span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"&amp;quot;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1537</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1538</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1539</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"/&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1540</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1541</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1542</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1543</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1544</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>(link);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1545</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lp=-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1546</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((lp=link.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"@ref "</span><span class="doxyHighlight">))!=-1 || (lp=link.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"\\ref "</span><span class="doxyHighlight">))!=-1 || (lang==SrcLangExt::Markdown &amp;&amp; !<a href="/web-doxygen/docs/api/files/src/util-cpp/#a7bc01022af843db19fb19614d340ba66">isURL</a>(link)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1547</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// assume doxygen symbol link</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1548</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1549</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lp==-1) </span><span class="doxyHighlightComment">// link to markdown page</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1550</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1551</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"@ref \""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1552</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!(<a href="/web-doxygen/docs/api/namespaces/portable/#a08dc4d7f652408d7fc2eaba792796cb1">Portable::isAbsolutePath</a>(link) || <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7bc01022af843db19fb19614d340ba66">isURL</a>(link)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1553</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1554</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> forg(link.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1555</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (forg.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>() &amp;&amp; forg.<a href="/web-doxygen/docs/api/classes/fileinfo/#aa7bd4cf0e93293d4c3bf057b53f02063">isReadable</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1556</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1557</span><span class="doxyLineContent"><span class="doxyHighlight">            link = forg.<a href="/web-doxygen/docs/api/classes/fileinfo/#af69e3949475014dcdbd504d742bdf270">absFilePath</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1558</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1559</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!(forg.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>() &amp;&amp; forg.<a href="/web-doxygen/docs/api/classes/fileinfo/#aa7bd4cf0e93293d4c3bf057b53f02063">isReadable</a>()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1560</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1561</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fi(<a href="#a778a4f710c8847455c0685dba1736c8b">fileName</a>.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1562</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> mdFile = <a href="#a778a4f710c8847455c0685dba1736c8b">fileName</a>.left(<a href="#a778a4f710c8847455c0685dba1736c8b">fileName</a>.length()-fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">fileName</a>().length()) + link;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1563</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fmd(mdFile.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1564</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fmd.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>() &amp;&amp; fmd.<a href="/web-doxygen/docs/api/classes/fileinfo/#aa7bd4cf0e93293d4c3bf057b53f02063">isReadable</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1565</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1566</span><span class="doxyLineContent"><span class="doxyHighlight">              link = fmd.<a href="/web-doxygen/docs/api/classes/fileinfo/#af69e3949475014dcdbd504d742bdf270">absFilePath</a>().data();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1567</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1568</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1569</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1570</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=link;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1571</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1572</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1573</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1574</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1575</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=link;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1576</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1577</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">" \""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1578</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (explicitTitle &amp;&amp; !title.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1579</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1580</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(title,</span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"&amp;quot;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1581</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1582</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1583</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1584</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ac0a9e3273eb76713a9e197d5be61e11a">processInline</a>(std::string_view(<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(content,</span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"&amp;quot;"</span><span class="doxyHighlight">).str()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1585</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1586</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1587</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1588</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((lp=link.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">))!=-1 || link.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">)!=-1 || link.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'.'</span><span class="doxyHighlight">)!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1589</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightComment">// file/url link</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1590</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lp==0 || (lp&gt;0 &amp;&amp; !<a href="/web-doxygen/docs/api/files/src/util-cpp/#a7bc01022af843db19fb19614d340ba66">isURL</a>(link) &amp;&amp; <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(MARKDOWN_ID_STYLE)==MARKDOWN_ID_STYLE_t::GITHUB))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1591</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1592</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"@ref \""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1593</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=<a href="/web-doxygen/docs/api/classes/anchorgenerator/#a54e3a84d24e7a6e688ebd6b46a566544">AnchorGenerator::addPrefixIfNeeded</a>(link.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(lp+1).<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1594</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"\" \""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1595</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(content.<a href="/web-doxygen/docs/api/classes/qcstring/#a8d6ace0deb439b916b9f97f54a6c9cc2">simplifyWhiteSpace</a>(),</span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"&amp;quot;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1596</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1597</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1598</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1599</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1600</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"&lt;a href=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1601</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=link;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1602</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1603</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> ii = 0; ii &lt; nlTotal; ii++) <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1604</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!title.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1605</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1606</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">" title=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1607</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(title.<a href="/web-doxygen/docs/api/classes/qcstring/#a8d6ace0deb439b916b9f97f54a6c9cc2">simplifyWhiteSpace</a>(),</span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"&amp;quot;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1608</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1609</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1610</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1611</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=<a href="/web-doxygen/docs/api/files/src/util-cpp/#ad3f3c94bc6e432d34fa1a51db3b7d5e2">externalLinkTarget</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1612</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1613</span><span class="doxyLineContent"><span class="doxyHighlight">        content = content.<a href="/web-doxygen/docs/api/classes/qcstring/#a8d6ace0deb439b916b9f97f54a6c9cc2">simplifyWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1614</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ac0a9e3273eb76713a9e197d5be61e11a">processInline</a>(std::string_view(content.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1615</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"&lt;/a&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1616</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1617</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1618</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// avoid link to e.g. F[x](y)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1619</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1620</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("no link for '%s'\n",qPrint(link));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1621</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1622</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1623</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1624</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1625</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1626</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/fileinfo/#af69e3949475014dcdbd504d742bdf270">FileInfo::absFilePath</a>, <a href="/web-doxygen/docs/api/classes/anchorgenerator/#a54e3a84d24e7a6e688ebd6b46a566544">AnchorGenerator::addPrefixIfNeeded</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO\_TRACE\_EXIT</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config\_getEnum</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config\_getInt</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">FileInfo::exists</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad3f3c94bc6e432d34fa1a51db3b7d5e2">externalLinkTarget</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">FileInfo::fileName</a>, <a href="#a778a4f710c8847455c0685dba1736c8b">fileName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a7062fae1e1507b5c093fe5b71a866371">Doxygen::imageNameLinkedMap</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a08dc4d7f652408d7fc2eaba792796cb1">Portable::isAbsolutePath</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#aa7bd4cf0e93293d4c3bf057b53f02063">FileInfo::isReadable</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7bc01022af843db19fb19614d340ba66">isURL</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#a5dd95f5138a9eb830f708bf8f669e89b">linkRefs</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>, <a href="/web-doxygen/docs/api/classes/sectiontype/#a2f832ab2bf817c8581feb03e123f09d5">SectionType::MaxLevel</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/classes/sectiontype/#ab44dce28d2b68c6514acbe2415a8a4d7">SectionType::MinLevel</a>, <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>, <a href="#ac0a9e3273eb76713a9e197d5be61e11a">processInline</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">QCString::setNum</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a8d6ace0deb439b916b9f97f54a6c9cc2">QCString::simplifyWhiteSpace</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a> and <a href="#a1213861d8af699057686e457bce66509">writeMarkdownImage</a>.
</div>
</div>

### processNmdash() {#adafbef72995b1327272b82a2b2075480}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int Markdown::Private::processNmdash (std::string_view data, size_t offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Process ndash and mdashes.

Definition at line 143 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adafbef72995b1327272b82a2b2075480">943</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#adafbef72995b1327272b82a2b2075480">Markdown::Private::processNmdash</a>(std::string_view data,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> offset)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">944</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">945</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}' offset={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data),offset);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">946</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">947</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// precondition: data[0]=='-'</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">948</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">949</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> count=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">950</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// found --</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">951</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">952</span><span class="doxyLineContent"><span class="doxyHighlight">    count++,i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">953</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">954</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// found ---</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">955</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">956</span><span class="doxyLineContent"><span class="doxyHighlight">    count++,i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">957</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">958</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// found ----</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">959</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">960</span><span class="doxyLineContent"><span class="doxyHighlight">    count++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">961</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">962</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (count&gt;=2 &amp;&amp; offset&gt;=2 &amp;&amp; <a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>(data.data()-2,</span><span class="doxyHighlightStringLiteral">"&lt;!"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">963</span><span class="doxyLineContent"><span class="doxyHighlight">  { <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,1-count); </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 1-count; } </span><span class="doxyHighlightComment">// start HTML comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">964</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (count==2 &amp;&amp; size &gt; 2 &amp;&amp; data[2]==</span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">965</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; } </span><span class="doxyHighlightComment">// end HTML comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">966</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (count==3 &amp;&amp; size &gt; 3 &amp;&amp; data[3]==</span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">967</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; } </span><span class="doxyHighlightComment">// end HTML comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">968</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (count==2 &amp;&amp; (offset&lt;8 || !<a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>(data.data()-8,</span><span class="doxyHighlightStringLiteral">"operator"</span><span class="doxyHighlight">))) </span><span class="doxyHighlightComment">// -- =&gt; ndash</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">969</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">970</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"&amp;ndash;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">971</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result=2"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">972</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">973</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">974</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (count==3) </span><span class="doxyHighlightComment">// --- =&gt; ndash</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">975</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">976</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"&amp;mdash;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">977</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result=3"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">978</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 3;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">979</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">980</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// not an ndash or mdash</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">981</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">982</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO\_TRACE\_EXIT</a>, <a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal\_at</a>, <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.
</div>
</div>

### processQuotations() {#a9792322da9173be90556ef009d37afa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString Markdown::Private::processQuotations (std::string_view data, size_t refIndent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 132 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9792322da9173be90556ef009d37afa4">3073</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a9792322da9173be90556ef009d37afa4">Markdown::Private::processQuotations</a>(std::string_view data,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> refIndent)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3074</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3075</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}' refIndex='{}'"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data),refIndent);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3076</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3077</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3078</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pi=std::string::npos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3079</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> newBlock = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3080</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> insideList = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3081</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> currentIndent = refIndent;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3082</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> listIndent = refIndent;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3083</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3084</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> lang;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3085</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3086</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3087</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a> = <a href="#aad2fb530e3d19a77de38a8c1b633b786">findEndOfLine</a>(data,i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3088</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// line is now found at [i..end)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3089</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3090</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> lineIndent=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3091</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (lineIndent&lt;<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a> &amp;&amp; data[i+lineIndent]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) lineIndent++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3092</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("** lineIndent=%d line=(%s)\n",lineIndent,qPrint(QCString(data+i).left(end-i)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3093</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3094</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (newBlock)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3095</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3096</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("** end of block\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3097</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (insideList &amp;&amp; lineIndent&lt;currentIndent) </span><span class="doxyHighlightComment">// end of list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3098</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3099</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("** end of list\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3100</span><span class="doxyLineContent"><span class="doxyHighlight">        currentIndent = refIndent;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3101</span><span class="doxyLineContent"><span class="doxyHighlight">        insideList = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3102</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3103</span><span class="doxyLineContent"><span class="doxyHighlight">      newBlock = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3104</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3105</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3106</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((listIndent=<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ad0a6b598945a869cd184d17fe1f16812">isListMarker</a>(data.substr(i,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-i)))) </span><span class="doxyHighlightComment">// see if we need to increase the indent level</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3107</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3108</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (listIndent&lt;currentIndent+4)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3109</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3110</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("** start of list\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3111</span><span class="doxyLineContent"><span class="doxyHighlight">        insideList = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3112</span><span class="doxyLineContent"><span class="doxyHighlight">        currentIndent = listIndent;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3113</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3114</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3115</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a4808ea595b45102dac19491e80d2ac9c">isEndOfList</a>(data.substr(i,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-i)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3116</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3117</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("** end of list\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3118</span><span class="doxyLineContent"><span class="doxyHighlight">      insideList = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3119</span><span class="doxyLineContent"><span class="doxyHighlight">      currentIndent = listIndent;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3120</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3121</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a7b54fef3d70eef54bd49dda068709f43">isEmptyLine</a>(data.substr(i,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-i)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3122</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3123</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("** new block\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3124</span><span class="doxyLineContent"><span class="doxyHighlight">      newBlock = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3125</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3126</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("currentIndent=%d listIndent=%d refIndent=%d\n",currentIndent,listIndent,refIndent);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3127</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3128</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pi!=std::string::npos)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3129</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3130</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> blockStart=0, blockEnd=0, blockOffset=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3131</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#acea395582e617dd69781da74f320161e">isFencedCodeBlock</a>(data.substr(pi),currentIndent,lang,blockStart,blockEnd,blockOffset))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3132</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3133</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> addSpecialCommand = [&amp;](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;startCmd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;endCmd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3134</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3135</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> cmdPos  = pi+blockStart+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3136</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> pl = data.substr(cmdPos,blockEnd-blockStart-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3137</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> ii = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3138</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> nl = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3139</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// check for absence of start command, either @start&lt;cmd&gt;, or \\start&lt;cmd&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3140</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (ii&lt;pl.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() &amp;&amp; <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a>(pl[ii]))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3141</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3142</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pl[ii]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) nl++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3143</span><span class="doxyLineContent"><span class="doxyHighlight">            ii++; </span><span class="doxyHighlightComment">// skip leading whitespace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3144</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3145</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> addNewLines = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3146</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ii+startCmd.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()&gt;=pl.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() || </span><span class="doxyHighlightComment">// no room for start command</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3147</span><span class="doxyLineContent"><span class="doxyHighlight">              (pl[ii]!=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight"> &amp;&amp; pl[ii]!=</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">)     || </span><span class="doxyHighlightComment">// no @ or \ after whitespace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3148</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a19faae287d13ccea75b1d5a0eb110d97">qstrncmp</a>(pl.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()+ii+1,startCmd.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),startCmd.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>())!=0) </span><span class="doxyHighlightComment">// no start command</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3149</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3150</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// input:                            output:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3151</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// ----------------------------------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3152</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// ```{plantuml}            =&gt;       @startuml</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3153</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// A-&gt;B                              A-&gt;B</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3154</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// ```                               @enduml</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3155</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// ----------------------------------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3156</span><span class="doxyLineContent"><span class="doxyHighlight">            pl = </span><span class="doxyHighlightStringLiteral">"@"</span><span class="doxyHighlight">+startCmd+</span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight"> + pl + </span><span class="doxyHighlightStringLiteral">"@"</span><span class="doxyHighlight">+endCmd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3157</span><span class="doxyLineContent"><span class="doxyHighlight">            addNewLines = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3158</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3159</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// we have a @start... command inside the code block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3160</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3161</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// input:                            output:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3162</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// ----------------------------------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3163</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// ```{plantuml}                     \n</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3164</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">//                                   \n</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3165</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// @startuml                =&gt;       @startuml</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3166</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// A-&gt;B                              A-&gt;B</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3167</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// @enduml                           @enduml</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3168</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// ```                               \n</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3169</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// ----------------------------------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3170</span><span class="doxyLineContent"><span class="doxyHighlight">            addNewLines = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3171</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3172</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (addNewLines) </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> j=0;j&lt;nl;j++) <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3173</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a43b1695a69a83037471e5445c7c940ce">processSpecialCommand</a>(pl.<a href="/web-doxygen/docs/api/classes/qcstring/#ac853c00269498870dfefa8185f2ee79a">view</a>().substr(ii),ii);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3174</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (addNewLines) <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3175</span><span class="doxyLineContent"><span class="doxyHighlight">        };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3176</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3177</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(PLANTUML_JAR_PATH).isEmpty() &amp;&amp; lang==</span><span class="doxyHighlightStringLiteral">"plantuml"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3178</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3179</span><span class="doxyLineContent"><span class="doxyHighlight">          addSpecialCommand(</span><span class="doxyHighlightStringLiteral">"startuml"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"enduml"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3180</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3181</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(HAVE_DOT) &amp;&amp; lang==</span><span class="doxyHighlightStringLiteral">"dot"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3182</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3183</span><span class="doxyLineContent"><span class="doxyHighlight">          addSpecialCommand(</span><span class="doxyHighlightStringLiteral">"dot"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"enddot"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3184</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3185</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lang==</span><span class="doxyHighlightStringLiteral">"msc"</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// msc is built-in</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3186</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3187</span><span class="doxyLineContent"><span class="doxyHighlight">          addSpecialCommand(</span><span class="doxyHighlightStringLiteral">"msc"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"endmsc"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3188</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3189</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// normal code block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3190</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3191</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a494fc3fc6c848a37caa06e5d85854ffe">writeFencedCodeBlock</a>(data.substr(pi),lang.<a href="/web-doxygen/docs/api/classes/qcstring/#ac853c00269498870dfefa8185f2ee79a">view</a>(),blockStart,blockEnd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3192</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3193</span><span class="doxyLineContent"><span class="doxyHighlight">        i=pi+blockOffset;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3194</span><span class="doxyLineContent"><span class="doxyHighlight">        pi=std::string::npos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3195</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=i+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3196</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3197</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3198</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a32f3ae19472e55905bc21e27835568d5">isBlockQuote</a>(data.substr(pi,i-pi),currentIndent))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3199</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3200</span><span class="doxyLineContent"><span class="doxyHighlight">        i = pi+<a href="#a2a97ed987f163573d91e6a46363c99de">writeBlockQuote</a>(data.substr(pi));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3201</span><span class="doxyLineContent"><span class="doxyHighlight">        pi=std::string::npos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3202</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=i+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3203</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3204</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3205</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3206</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3207</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("quote out={%s}\n",QCString(data+pi).left(i-pi).data());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3208</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=data.substr(pi,i-pi);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3209</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3210</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3211</span><span class="doxyLineContent"><span class="doxyHighlight">    pi=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3212</span><span class="doxyLineContent"><span class="doxyHighlight">    i=<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3213</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3214</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pi!=std::string::npos &amp;&amp; pi&lt;size) </span><span class="doxyHighlightComment">// deal with the last line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3215</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3216</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a32f3ae19472e55905bc21e27835568d5">isBlockQuote</a>(data.substr(pi),currentIndent))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3217</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3218</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a2a97ed987f163573d91e6a46363c99de">writeBlockQuote</a>(data.substr(pi));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3219</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3220</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3221</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3222</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=data.substr(pi);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3223</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3224</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3225</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3226</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("Process quotations\n---- input ----\n%s\n---- output ----\n%s\n------------\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3227</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//    qPrint(s),prv-&gt;out.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3228</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3229</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3230</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config\_getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config\_getString</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="#aad2fb530e3d19a77de38a8c1b633b786">findEndOfLine</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a32f3ae19472e55905bc21e27835568d5">isBlockQuote</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a7b54fef3d70eef54bd49dda068709f43">isEmptyLine</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a4808ea595b45102dac19491e80d2ac9c">isEndOfList</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#acea395582e617dd69781da74f320161e">isFencedCodeBlock</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ad0a6b598945a869cd184d17fe1f16812">isListMarker</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>, <a href="#a43b1695a69a83037471e5445c7c940ce">processSpecialCommand</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a19faae287d13ccea75b1d5a0eb110d97">qstrncmp</a>, <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac853c00269498870dfefa8185f2ee79a">QCString::view</a>, <a href="#a2a97ed987f163573d91e6a46363c99de">writeBlockQuote</a> and <a href="#a494fc3fc6c848a37caa06e5d85854ffe">writeFencedCodeBlock</a>.
</div>
</div>

### processQuoted() {#a0f211ac431de2f23ca4874c125ab1551}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int Markdown::Private::processQuoted (std::string_view data, size_t offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Process quoted section "...", can contain one embedded newline.

Definition at line 144 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0f211ac431de2f23ca4874c125ab1551">985</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a0f211ac431de2f23ca4874c125ab1551">Markdown::Private::processQuoted</a>(std::string_view data,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">986</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">987</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}'"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">988</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">989</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">990</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> nl=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">991</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]!=</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight"> &amp;&amp; nl&lt;2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">992</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">993</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) nl++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">994</span><span class="doxyLineContent"><span class="doxyHighlight">    i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">995</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">996</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; data[i]==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight"> &amp;&amp; nl&lt;2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">997</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">998</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=data.substr(0,i+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">999</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,i+2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1000</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(i+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1001</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1002</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// not a quoted section</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1003</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1004</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO\_TRACE\_EXIT</a>, <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.
</div>
</div>

### processSpecialCommand() {#a43b1695a69a83037471e5445c7c940ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int Markdown::Private::processSpecialCommand (std::string_view data, size_t offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 146 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a43b1695a69a83037471e5445c7c940ce">1702</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a43b1695a69a83037471e5445c7c940ce">Markdown::Private::processSpecialCommand</a>(std::string_view data, </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> offset)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1703</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1704</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"{}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1705</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1706</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1707</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> endBlockName = <a href="#a6d7d4814ead5c919439c6b2d681e2ce7">isBlockCommand</a>(data,offset);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1708</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!endBlockName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1709</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1710</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"endBlockName={}"</span><span class="doxyHighlight">,endBlockName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1711</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> l = endBlockName.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1712</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i+l&lt;size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1713</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1714</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((data[i]==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight"> || data[i]==</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">) &amp;&amp; </span><span class="doxyHighlightComment">// command</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1715</span><span class="doxyLineContent"><span class="doxyHighlight">          data[i-1]!=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight"> &amp;&amp; data[i-1]!=</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// not escaped</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1716</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1717</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a19faae287d13ccea75b1d5a0eb110d97">qstrncmp</a>(&amp;data[i+1],endBlockName.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),l)==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1718</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1719</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//printf("found end at %d\n",i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1720</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a681582d0e894782b9509baa541931151">addStrEscapeUtf8Nbsp</a>(data.substr(0,i+1+l));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1721</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,i+1+l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1722</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(i+1+l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1723</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1724</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1725</span><span class="doxyLineContent"><span class="doxyHighlight">      i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1726</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1727</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1728</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> endPos = <a href="#a2e37305849fa544aff8f399a6f41c7b1">isSpecialCommand</a>(data,offset);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1729</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (endPos&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1730</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1731</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=data.substr(0,endPos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1732</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(endPos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1733</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1734</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (size&gt;1 &amp;&amp; data[0]==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// escaped characters</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1735</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1736</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c=data[1];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1737</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'['</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">']'</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'`'</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'_'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1738</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1739</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=data[1];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1740</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"2"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1741</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1742</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1743</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1744</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1745</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=data.substr(0,2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1746</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"2"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1747</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1748</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1749</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight"> &amp;&amp; size&gt;3 &amp;&amp; data[2]==</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight"> &amp;&amp; data[3]==</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// \---</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1750</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1751</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=data.substr(1,3);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1752</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"2"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1753</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 4;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1754</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1755</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight"> &amp;&amp; size&gt;2 &amp;&amp; data[2]==</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// \--</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1756</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1757</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=data.substr(1,2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1758</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"3"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1759</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 3;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1760</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1761</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1762</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (size&gt;1 &amp;&amp; data[0]==</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// escaped characters</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1763</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1764</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c=data[1];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1765</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1766</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1767</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=data.substr(0,2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1768</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"2"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1769</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1770</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1771</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1772</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1773</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a681582d0e894782b9509baa541931151">addStrEscapeUtf8Nbsp</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO\_TRACE\_ADD</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO\_TRACE\_EXIT</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="#a6d7d4814ead5c919439c6b2d681e2ce7">isBlockCommand</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a2e37305849fa544aff8f399a6f41c7b1">isSpecialCommand</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a19faae287d13ccea75b1d5a0eb110d97">qstrncmp</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.

Referenced by <a href="#a9792322da9173be90556ef009d37afa4">processQuotations</a>.
</div>
</div>

### writeBlockQuote() {#a2a97ed987f163573d91e6a46363c99de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t Markdown::Private::writeBlockQuote (std::string_view data)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 161 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2a97ed987f163573d91e6a46363c99de">2758</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a2a97ed987f163573d91e6a46363c99de">Markdown::Private::writeBlockQuote</a>(std::string_view data)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2759</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2760</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}'"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2761</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2762</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> curLevel=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2763</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2764</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2765</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string startCmd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2766</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> isGitHubAlert = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2767</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> isGitHubFirst = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2768</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2769</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2770</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// find end of this line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2771</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=i+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2772</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>&lt;=size &amp;&amp; data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-1]!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2773</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> j=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2774</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2775</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> indent=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2776</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// compute the quoting level</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2777</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (j&lt;<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a> &amp;&amp; (data[j]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || data[j]==</span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2778</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2779</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[j]==</span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight">) { level++; indent=j+1; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2780</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (j&gt;0 &amp;&amp; data[j-1]==</span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight">) indent=j+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2781</span><span class="doxyLineContent"><span class="doxyHighlight">      j++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2782</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2783</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (indent&gt;0 &amp;&amp; j&gt;0 &amp;&amp; data[j-1]==</span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight"> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2784</span><span class="doxyLineContent"><span class="doxyHighlight">        !(j==size || data[j]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)) </span><span class="doxyHighlightComment">// disqualify last &gt; if not followed by space</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2785</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2786</span><span class="doxyLineContent"><span class="doxyHighlight">      indent--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2787</span><span class="doxyLineContent"><span class="doxyHighlight">      level--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2788</span><span class="doxyLineContent"><span class="doxyHighlight">      j--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2789</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2790</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"indent={} i={} j={} end={} level={} line={}"</span><span class="doxyHighlight">,indent,i,j,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>,level,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(&amp;data[i]));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2791</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (level==0 &amp;&amp; j&lt;<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-1 &amp;&amp; !<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ad0a6b598945a869cd184d17fe1f16812">isListMarker</a>(data.substr(j)) &amp;&amp; !<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ad1f1abe1811f3c45c5b4ee867c15989f">isHRuler</a>(data.substr(j)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2792</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2793</span><span class="doxyLineContent"><span class="doxyHighlight">      level = curLevel; </span><span class="doxyHighlightComment">// lazy</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2794</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2795</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (level==1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2796</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2797</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> txt = <a href="/web-doxygen/docs/api/files/src/stringutil-h/#aef47e534975880014a6514745e885a99">stripWhiteSpace</a>(data.substr(indent,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-indent));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2798</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#acb9b9cc222a09dc4b31c86cf18cd68df">g_quotationHeaderMap</a>.find(txt.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()); </span><span class="doxyHighlightComment">// TODO: in C++20 the std::string can be dropped</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2799</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it != <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#acb9b9cc222a09dc4b31c86cf18cd68df">g_quotationHeaderMap</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2800</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2801</span><span class="doxyLineContent"><span class="doxyHighlight">        isGitHubAlert = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2802</span><span class="doxyLineContent"><span class="doxyHighlight">        isGitHubFirst = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2803</span><span class="doxyLineContent"><span class="doxyHighlight">        startCmd = it-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2804</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2805</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2806</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (level&gt;curLevel) </span><span class="doxyHighlightComment">// quote level increased =&gt; add start markers</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2807</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2808</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (level!=1 || !isGitHubAlert) </span><span class="doxyHighlightComment">// normal block quote</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2809</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2810</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> l=curLevel;l&lt;level-1;l++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2811</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2812</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"&lt;blockquote&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2813</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2814</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a> += </span><span class="doxyHighlightStringLiteral">"&lt;blockquote&gt;&amp;zwj;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// empty blockquotes are also shown</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2815</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2816</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!startCmd.empty()) </span><span class="doxyHighlightComment">// GitHub style alert</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2817</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2818</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a> += startCmd + </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2819</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2820</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2821</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (level&lt;curLevel) </span><span class="doxyHighlightComment">// quote level decreased =&gt; add end markers</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2822</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2823</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/pre-l/#a1917523a9eee16ade8021a9135d5e1da">decrLevel</a> = curLevel;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2824</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (level==0 &amp;&amp; isGitHubAlert)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2825</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2826</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/pre-l/#a1917523a9eee16ade8021a9135d5e1da">decrLevel</a>--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2827</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2828</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> l=level;l&lt;<a href="/web-doxygen/docs/api/files/src/pre-l/#a1917523a9eee16ade8021a9135d5e1da">decrLevel</a>;l++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2829</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2830</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a> += </span><span class="doxyHighlightStringLiteral">"&lt;/blockquote&gt;\\ilinebr "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2831</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2832</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2833</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (level==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2834</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2835</span><span class="doxyLineContent"><span class="doxyHighlight">      curLevel=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2836</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// end of quote block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2837</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2838</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// copy line without quotation marks</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2839</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (curLevel!=0 || !isGitHubAlert)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2840</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2841</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string_view txt = data.substr(indent,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-indent);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2842</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/stringutil-h/#aef47e534975880014a6514745e885a99">stripWhiteSpace</a>(txt).empty() &amp;&amp; !startCmd.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2843</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2844</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!isGitHubFirst) <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a> += </span><span class="doxyHighlightStringLiteral">"&lt;br&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2845</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a> += </span><span class="doxyHighlightStringLiteral">"&lt;br&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2846</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2847</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2848</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2849</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a> += txt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2850</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2851</span><span class="doxyLineContent"><span class="doxyHighlight">      isGitHubFirst = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2852</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2853</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// GitHub alert section</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2854</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2855</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+= </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2856</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2857</span><span class="doxyLineContent"><span class="doxyHighlight">    curLevel=level;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2858</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// proceed with next line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2859</span><span class="doxyLineContent"><span class="doxyHighlight">    i=<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2860</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2861</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// end of comment within blockquote =&gt; add end markers</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2862</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isGitHubAlert) </span><span class="doxyHighlightComment">// GitHub alert doesn't have a blockquote</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2863</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2864</span><span class="doxyLineContent"><span class="doxyHighlight">    curLevel--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2865</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2866</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> l=0;l&lt;curLevel;l++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2867</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2868</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"&lt;/blockquote&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2869</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2870</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"i={}"</span><span class="doxyHighlight">,i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2871</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2872</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO\_TRACE\_ADD</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO\_TRACE\_EXIT</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a1917523a9eee16ade8021a9135d5e1da">decrLevel</a>, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#acb9b9cc222a09dc4b31c86cf18cd68df">g\_quotationHeaderMap</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ad1f1abe1811f3c45c5b4ee867c15989f">isHRuler</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ad0a6b598945a869cd184d17fe1f16812">isListMarker</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>, <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/files/src/stringutil-h/#aef47e534975880014a6514745e885a99">stripWhiteSpace</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.

Referenced by <a href="#a9792322da9173be90556ef009d37afa4">processQuotations</a>.
</div>
</div>

### writeCodeBlock() {#a79fd3fae285ba1f1beeb84c8e858bf46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t Markdown::Private::writeCodeBlock (std::string_view data, size_t refIndent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 162 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a79fd3fae285ba1f1beeb84c8e858bf46">2910</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a79fd3fae285ba1f1beeb84c8e858bf46">Markdown::Private::writeCodeBlock</a>(std::string_view data,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> refIndent)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2911</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2912</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}' refIndent={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data),refIndent);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2913</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2914</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2915</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// no need for \ilinebr here as the previous line was empty and was skipped</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2916</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"@iverbatim\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2917</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> emptyLines=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2918</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string location;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2919</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2920</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2921</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// find end of this line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2922</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=i+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2923</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>&lt;=size &amp;&amp; data[<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-1]!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2924</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> j=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2925</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> indent=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2926</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (j&lt;<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a> &amp;&amp; data[j]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) j++,indent++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2927</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("j=%d end=%d indent=%d refIndent=%d tabSize=%d data={%s}\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2928</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//    j,end,indent,refIndent,Config_getInt(TAB_SIZE),qPrint(QCString(data+i).left(end-i-1)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2929</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (j==<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-1) </span><span class="doxyHighlightComment">// empty line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2930</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2931</span><span class="doxyLineContent"><span class="doxyHighlight">      emptyLines++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2932</span><span class="doxyLineContent"><span class="doxyHighlight">      i=<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2933</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2934</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (indent&gt;=refIndent+<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a918fa8a25e6bc30b364b55bc19a5dafd">codeBlockIndent</a>) </span><span class="doxyHighlightComment">// enough indent to continue the code block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2935</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2936</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (emptyLines&gt;0) </span><span class="doxyHighlightComment">// write skipped empty lines</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2937</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2938</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// add empty line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2939</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2940</span><span class="doxyLineContent"><span class="doxyHighlight">        emptyLines--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2941</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2942</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// add code line minus the indent</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2943</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> offset = i+refIndent+<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a918fa8a25e6bc30b364b55bc19a5dafd">codeBlockIndent</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2944</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string lineLoc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2945</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ae22648d9504bbec4b64a0c33260fbe4f">skipOverFileAndLineCommands</a>(data,<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a918fa8a25e6bc30b364b55bc19a5dafd">codeBlockIndent</a>,offset,lineLoc))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2946</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2947</span><span class="doxyLineContent"><span class="doxyHighlight">        location = lineLoc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2948</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2949</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=data.substr(offset,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-offset);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2950</span><span class="doxyLineContent"><span class="doxyHighlight">      i=<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2951</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2952</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// end of code block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2953</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2954</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2955</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2956</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2957</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"@endiverbatim"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2958</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!location.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2959</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2960</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=location;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2961</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2962</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2963</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2964</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"\\ilinebr "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2965</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2966</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (emptyLines&gt;0) </span><span class="doxyHighlightComment">// write skipped empty lines</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2967</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2968</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// add empty line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2969</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2970</span><span class="doxyLineContent"><span class="doxyHighlight">    emptyLines--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2971</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2972</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"i={}"</span><span class="doxyHighlight">,i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2973</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2974</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO\_TRACE\_EXIT</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a918fa8a25e6bc30b364b55bc19a5dafd">codeBlockIndent</a>, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ae22648d9504bbec4b64a0c33260fbe4f">skipOverFileAndLineCommands</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.

Referenced by <a href="#a9835402c2d15b122de1c3ba4180ebd58">processBlocks</a>.
</div>
</div>

### writeFencedCodeBlock() {#a494fc3fc6c848a37caa06e5d85854ffe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Markdown::Private::writeFencedCodeBlock (std::string_view data, std::string_view lang, size_t blockStart, size_t blockEnd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 159 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a494fc3fc6c848a37caa06e5d85854ffe">3050</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a494fc3fc6c848a37caa06e5d85854ffe">Markdown::Private::writeFencedCodeBlock</a>(std::string_view data,std::string_view lang,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3051</span><span class="doxyLineContent"><span class="doxyHighlight">                </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> blockStart,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> blockEnd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3052</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3053</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}' lang={} blockStart={} blockEnd={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data),lang,blockStart,blockEnd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3054</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!lang.empty() &amp;&amp; lang[0]==</span><span class="doxyHighlightCharLiteral">'.'</span><span class="doxyHighlight">) lang=lang.substr(1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3055</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size=data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3056</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3057</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; (data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || data[i]==</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3058</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3059</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=data[i++];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3060</span><span class="doxyLineContent"><span class="doxyHighlight">    blockStart--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3061</span><span class="doxyLineContent"><span class="doxyHighlight">    blockEnd--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3062</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3063</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"@icode"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3064</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!lang.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3065</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3066</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight">+lang+</span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3067</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3068</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3069</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a681582d0e894782b9509baa541931151">addStrEscapeUtf8Nbsp</a>(data.substr(blockStart+i,blockEnd-blockStart));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3070</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"@endicode "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3071</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a681582d0e894782b9509baa541931151">addStrEscapeUtf8Nbsp</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.

Referenced by <a href="#a9835402c2d15b122de1c3ba4180ebd58">processBlocks</a> and <a href="#a9792322da9173be90556ef009d37afa4">processQuotations</a>.
</div>
</div>

### writeMarkdownImage() {#a1213861d8af699057686e457bce66509}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Markdown::Private::writeMarkdownImage (std::string_view fmt, bool inline_img, bool explicitTitle, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; content, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; link, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; attributes, const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 151 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1213861d8af699057686e457bce66509">1154</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1213861d8af699057686e457bce66509">Markdown::Private::writeMarkdownImage</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1155</span><span class="doxyLineContent"><span class="doxyHighlight">                                  std::string_view <a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inline_img, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> explicitTitle,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1156</span><span class="doxyLineContent"><span class="doxyHighlight">                                  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;content,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1157</span><span class="doxyLineContent"><span class="doxyHighlight">                                  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;link, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;attrs,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1158</span><span class="doxyLineContent"><span class="doxyHighlight">                                  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1159</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1160</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"fmt={} inline_img={} explicitTitle={} title={} content={} link={} attrs={}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1161</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>,inline_img,explicitTitle,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(title),<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(content),link,attrs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1162</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> attributes = <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ad5f8f274225faad69b969f4828376f06">getFilteredImageAttributes</a>(<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>, attrs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1163</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"@image"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1164</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (inline_img)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1165</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1166</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"{inline}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1167</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1168</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1169</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1170</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1171</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=link.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(fd ? 0 : 5);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1172</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!explicitTitle &amp;&amp; !content.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1173</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1174</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">" \""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1175</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a3d4cb7f7e85f41df2eab7827e3bec33e">escapeDoubleQuotes</a>(content);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1176</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1177</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1178</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((content.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() || explicitTitle) &amp;&amp; !title.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1179</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1180</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">" \""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1181</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a3d4cb7f7e85f41df2eab7827e3bec33e">escapeDoubleQuotes</a>(title);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1182</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1183</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1184</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1185</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1186</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span><span class="doxyHighlightComment">// so the line break will not be part of the image name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1187</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1188</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!attributes.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1189</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1190</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1191</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=attributes;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1192</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1193</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1194</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"\\ilinebr "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1195</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a3d4cb7f7e85f41df2eab7827e3bec33e">escapeDoubleQuotes</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ad5f8f274225faad69b969f4828376f06">getFilteredImageAttributes</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.

Referenced by <a href="#a9b99b7f5084eb08d7ffe43f3fbe79d69">processLink</a>.
</div>
</div>

### writeOneLineHeaderOrRuler() {#af7ceebe6b90c368816a6d9bd0ca501c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Markdown::Private::writeOneLineHeaderOrRuler (std::string_view data)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 158 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af7ceebe6b90c368816a6d9bd0ca501c0">2698</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af7ceebe6b90c368816a6d9bd0ca501c0">Markdown::Private::writeOneLineHeaderOrRuler</a>(std::string_view data)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2699</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2700</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}'"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2701</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2702</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> header;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2703</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> id;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2704</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ad1f1abe1811f3c45c5b4ee867c15989f">isHRuler</a>(data))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2705</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2706</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"&lt;hr&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2707</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2708</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((level=<a href="#aa8a42c32241bc89aa626ce55c23b7df5">isAtxHeader</a>(data,header,</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2709</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2710</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> hTag;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2711</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2712</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2713</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (level)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2714</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2715</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectiontype/#a16a0139dc8140f1c1626f46db559dac6">SectionType::Section</a>:         <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"@section "</span><span class="doxyHighlight">;         </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2716</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectiontype/#a53adf06c99d78c4fcf4a8e4a1366c401">SectionType::Subsection</a>:      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"@subsection "</span><span class="doxyHighlight">;      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2717</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectiontype/#a5f6dc2a0df2c922d077db4211dcec9d1">SectionType::Subsubsection</a>:   <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"@subsubsection "</span><span class="doxyHighlight">;   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2718</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectiontype/#ae77523c9ecd298b11cdcdc8fae693a33">SectionType::Paragraph</a>:       <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"@paragraph "</span><span class="doxyHighlight">;       </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2719</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectiontype/#afe5ca7520c54e7d647adb55a910b53cd">SectionType::Subparagraph</a>:    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"@subparagraph "</span><span class="doxyHighlight">;    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2720</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectiontype/#afc5a4c3df18d1ff4855525a78069b63b">SectionType::Subsubparagraph</a>: <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"@subsubparagraph "</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2721</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2722</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=id;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2723</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2724</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=header;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2725</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2726</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2727</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2728</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2729</span><span class="doxyLineContent"><span class="doxyHighlight">      hTag.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"h%d"</span><span class="doxyHighlight">,level);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2730</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"&lt;"</span><span class="doxyHighlight">+hTag+</span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2731</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=header;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2732</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"&lt;/"</span><span class="doxyHighlight">+hTag+</span><span class="doxyHighlightStringLiteral">"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2733</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2734</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2735</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data.size()&gt;0) </span><span class="doxyHighlightComment">// nothing interesting -&gt; just output the line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2736</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2737</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> tmpSize = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2738</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[data.size()-1] == </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) tmpSize--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2739</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=data.substr(0,tmpSize);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2740</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2741</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a228aefe349d4d8c9272c606c9fbc8c81">hasLineBreak</a>(data))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2742</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2743</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"\\ilinebr&lt;br&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2744</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2745</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tmpSize != data.size()) <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2746</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2747</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a228aefe349d4d8c9272c606c9fbc8c81">hasLineBreak</a>, <a href="#aa8a42c32241bc89aa626ce55c23b7df5">isAtxHeader</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ad1f1abe1811f3c45c5b4ee867c15989f">isHRuler</a>, <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>, <a href="/web-doxygen/docs/api/classes/sectiontype/#ae77523c9ecd298b11cdcdc8fae693a33">SectionType::Paragraph</a>, <a href="/web-doxygen/docs/api/classes/sectiontype/#a16a0139dc8140f1c1626f46db559dac6">SectionType::Section</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">QCString::sprintf</a>, <a href="/web-doxygen/docs/api/classes/sectiontype/#afe5ca7520c54e7d647adb55a910b53cd">SectionType::Subparagraph</a>, <a href="/web-doxygen/docs/api/classes/sectiontype/#a53adf06c99d78c4fcf4a8e4a1366c401">SectionType::Subsection</a>, <a href="/web-doxygen/docs/api/classes/sectiontype/#afc5a4c3df18d1ff4855525a78069b63b">SectionType::Subsubparagraph</a>, <a href="/web-doxygen/docs/api/classes/sectiontype/#a5f6dc2a0df2c922d077db4211dcec9d1">SectionType::Subsubsection</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.

Referenced by <a href="#a9835402c2d15b122de1c3ba4180ebd58">processBlocks</a>.
</div>
</div>

### writeTableBlock() {#a21b82aade2e5a369ec438f0cd49f8107}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t Markdown::Private::writeTableBlock (std::string_view data)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 163 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21b82aade2e5a369ec438f0cd49f8107">2479</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a21b82aade2e5a369ec438f0cd49f8107">Markdown::Private::writeTableBlock</a>(std::string_view data)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2480</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2481</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data='{}'"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2482</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2483</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2484</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> columns=0, start=0, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2485</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i = <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a90640de61c785c42e3dc3787610b18eb">findTableColumns</a>(data,start,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>,columns);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2486</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> headerStart = start;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2487</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> headerEnd   = <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2488</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2489</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// read cell alignments</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2490</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> cc = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2491</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> ret = <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a90640de61c785c42e3dc3787610b18eb">findTableColumns</a>(data.substr(i),start,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>,cc);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2492</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> k=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2493</span><span class="doxyLineContent"><span class="doxyHighlight">  std::vector&lt;int&gt; columnAlignment(columns);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2494</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2495</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> leftMarker=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">, rightMarker=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">, startFound=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2496</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> j=start+i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2497</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (j&lt;=<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>+i)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2498</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2499</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!startFound)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2500</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2501</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[j]==</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight">) { leftMarker=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>; startFound=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2502</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[j]==</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">) startFound=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2503</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("  data[%d]=%c startFound=%d\n",j,data[j],startFound);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2504</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2505</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">      (data[j]==</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">) rightMarker=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2506</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[j]==</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight">) rightMarker=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2507</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (j&lt;=<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>+i &amp;&amp; (data[j]==</span><span class="doxyHighlightCharLiteral">'|'</span><span class="doxyHighlight"> &amp;&amp; (j==0 || data[j-1]!=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2508</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2509</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (k&lt;columns)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2510</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2511</span><span class="doxyLineContent"><span class="doxyHighlight">        columnAlignment[k] = <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a53933ee56e6d62357cc60bde3156f544">markersToAlignment</a>(leftMarker,rightMarker);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2512</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("column[%d] alignment=%d\n",k,columnAlignment[k]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2513</span><span class="doxyLineContent"><span class="doxyHighlight">        leftMarker=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2514</span><span class="doxyLineContent"><span class="doxyHighlight">        rightMarker=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2515</span><span class="doxyLineContent"><span class="doxyHighlight">        startFound=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2516</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2517</span><span class="doxyLineContent"><span class="doxyHighlight">      k++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2518</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2519</span><span class="doxyLineContent"><span class="doxyHighlight">    j++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2520</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2521</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (k&lt;columns)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2522</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2523</span><span class="doxyLineContent"><span class="doxyHighlight">    columnAlignment[k] = <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a53933ee56e6d62357cc60bde3156f544">markersToAlignment</a>(leftMarker,rightMarker);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2524</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("column[%d] alignment=%d\n",k,columnAlignment[k]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2525</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2526</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// proceed to next line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2527</span><span class="doxyLineContent"><span class="doxyHighlight">  i+=ret;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2528</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2529</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Store the table cell information by row then column.  This</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2530</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// allows us to handle row spanning.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2531</span><span class="doxyLineContent"><span class="doxyHighlight">  std::vector&lt;std::vector&lt;TableCell&gt; &gt; tableContents;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2532</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2533</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> m = headerStart;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2534</span><span class="doxyLineContent"><span class="doxyHighlight">  std::vector&lt;TableCell&gt; headerContents(columns);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2535</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (k=0;k&lt;columns;k++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2536</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2537</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (m&lt;=headerEnd &amp;&amp; (data[m]!=</span><span class="doxyHighlightCharLiteral">'|'</span><span class="doxyHighlight"> || (m&gt;0 &amp;&amp; data[m-1]==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2538</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2539</span><span class="doxyLineContent"><span class="doxyHighlight">      headerContents[k].cellText += data[m++];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2540</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2541</span><span class="doxyLineContent"><span class="doxyHighlight">    m++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2542</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// do the column span test before stripping white space</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2543</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// || is spanning columns, | | is not</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2544</span><span class="doxyLineContent"><span class="doxyHighlight">    headerContents[k].colSpan = headerContents[k].cellText.isEmpty();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2545</span><span class="doxyLineContent"><span class="doxyHighlight">    headerContents[k].cellText = headerContents[k].cellText.stripWhiteSpace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2546</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2547</span><span class="doxyLineContent"><span class="doxyHighlight">  tableContents.push_back(headerContents);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2548</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2549</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// write table cells</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2550</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2551</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2552</span><span class="doxyLineContent"><span class="doxyHighlight">    ret = <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a90640de61c785c42e3dc3787610b18eb">findTableColumns</a>(data.substr(i),start,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>,cc);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2553</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cc!=columns) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// end of table</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2554</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2555</span><span class="doxyLineContent"><span class="doxyHighlight">    j=start+i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2556</span><span class="doxyLineContent"><span class="doxyHighlight">    k=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2557</span><span class="doxyLineContent"><span class="doxyHighlight">    std::vector&lt;TableCell&gt; rowContents(columns);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2558</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (j&lt;=<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>+i)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2559</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2560</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (j&lt;=<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>+i &amp;&amp; (data[j]==</span><span class="doxyHighlightCharLiteral">'|'</span><span class="doxyHighlight"> &amp;&amp; (j==0 || data[j-1]!=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2561</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2562</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// do the column span test before stripping white space</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2563</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// || is spanning columns, | | is not</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2564</span><span class="doxyLineContent"><span class="doxyHighlight">        rowContents[k].colSpan = rowContents[k].cellText.isEmpty();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2565</span><span class="doxyLineContent"><span class="doxyHighlight">        rowContents[k].cellText = rowContents[k].cellText.stripWhiteSpace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2566</span><span class="doxyLineContent"><span class="doxyHighlight">        k++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2567</span><span class="doxyLineContent"><span class="doxyHighlight">      } </span><span class="doxyHighlightComment">// if (j&lt;=end+i &amp;&amp; (data[j]=='|' &amp;&amp; (j==0 || data[j-1]!='\\')))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2568</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2569</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2570</span><span class="doxyLineContent"><span class="doxyHighlight">        rowContents[k].cellText += data[j];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2571</span><span class="doxyLineContent"><span class="doxyHighlight">      } </span><span class="doxyHighlightComment">// else { if (j&lt;=end+i &amp;&amp; (data[j]=='|' &amp;&amp; (j==0 || data[j-1]!='\\'))) }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2572</span><span class="doxyLineContent"><span class="doxyHighlight">      j++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2573</span><span class="doxyLineContent"><span class="doxyHighlight">    } </span><span class="doxyHighlightComment">// while (j&lt;=end+i)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2574</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// do the column span test before stripping white space</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2575</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// || is spanning columns, | | is not</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2576</span><span class="doxyLineContent"><span class="doxyHighlight">    rowContents[k].colSpan  = rowContents[k].cellText.isEmpty();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2577</span><span class="doxyLineContent"><span class="doxyHighlight">    rowContents[k].cellText = rowContents[k].cellText.stripWhiteSpace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2578</span><span class="doxyLineContent"><span class="doxyHighlight">    tableContents.push_back(rowContents);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2579</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2580</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// proceed to next line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2581</span><span class="doxyLineContent"><span class="doxyHighlight">    i+=ret;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2582</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2583</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2584</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"&lt;table class=\"markdownTable\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2585</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> cellTag(</span><span class="doxyHighlightStringLiteral">"th"</span><span class="doxyHighlight">), cellClass(</span><span class="doxyHighlightStringLiteral">"class=\"markdownTableHead"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2586</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> row = 0; row &lt; tableContents.size(); row++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2587</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2588</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (row)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2589</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2590</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (row % 2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2591</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2592</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"\n&lt;tr class=\"markdownTableRowOdd\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2593</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2594</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2595</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2596</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"\n&lt;tr class=\"markdownTableRowEven\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2597</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2598</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2599</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2600</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2601</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"\n  &lt;tr class=\"markdownTableHead\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2602</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2603</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> c = 0; c &lt; columns; c++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2604</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2605</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// save the cell text for use after column span computation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2606</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> cellText(tableContents[row][c].cellText);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2607</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2608</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// Row span handling.  Spanning rows will contain a caret ('^').</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2609</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// If the current cell contains just a caret, this is part of an</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2610</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// earlier row's span and the cell should not be added to the</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2611</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// output.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2612</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tableContents[row][c].cellText == </span><span class="doxyHighlightStringLiteral">"^"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2613</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2614</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2615</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2616</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tableContents[row][c].colSpan)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2617</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2618</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> cr = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2619</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ( cr &gt;= 0 &amp;&amp; tableContents[row][cr].colSpan)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2620</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2621</span><span class="doxyLineContent"><span class="doxyHighlight">          cr--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2622</span><span class="doxyLineContent"><span class="doxyHighlight">        };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2623</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cr &gt;= 0 &amp;&amp; tableContents[row][cr].cellText == </span><span class="doxyHighlightStringLiteral">"^"</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2624</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2625</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> rowSpan = 1, spanRow = row+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2626</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((spanRow &lt; tableContents.size()) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2627</span><span class="doxyLineContent"><span class="doxyHighlight">             (tableContents[spanRow][c].cellText == </span><span class="doxyHighlightStringLiteral">"^"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2628</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2629</span><span class="doxyLineContent"><span class="doxyHighlight">        spanRow++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2630</span><span class="doxyLineContent"><span class="doxyHighlight">        rowSpan++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2631</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2632</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2633</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"    &lt;"</span><span class="doxyHighlight"> + cellTag + </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> + cellClass;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2634</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// use appropriate alignment style</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2635</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (columnAlignment[c])</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2636</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2637</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#acdfaca60ec19c0265bac2692d7982726a291bdf1a2284d5648efc75ee78fbeb4c">AlignLeft</a>:   <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"Left\""</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2638</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#acdfaca60ec19c0265bac2692d7982726a4758d977046d9c084a0eaf7434fd29e1">AlignRight</a>:  <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"Right\""</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2639</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#acdfaca60ec19c0265bac2692d7982726afed76d6718c0a44a25c5e19ae8fb51d1">AlignCenter</a>: <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"Center\""</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2640</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#acdfaca60ec19c0265bac2692d7982726a4258b9785acff3438d08d41ddb4439d9">AlignNone</a>:   <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"None\""</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2641</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2642</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2643</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rowSpan &gt; 1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2644</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2645</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> spanStr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2646</span><span class="doxyLineContent"><span class="doxyHighlight">        spanStr.<a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">setNum</a>(rowSpan);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2647</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">" rowspan=\""</span><span class="doxyHighlight"> + spanStr + </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2648</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2649</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// Column span handling, assumes that column spans will have</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2650</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// empty strings, which would indicate the sequence "||", used</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2651</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// to signify spanning columns.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2652</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> colSpan = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2653</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c+1 &lt; columns) &amp;&amp; tableContents[row][c+1].colSpan)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2654</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2655</span><span class="doxyLineContent"><span class="doxyHighlight">        c++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2656</span><span class="doxyLineContent"><span class="doxyHighlight">        colSpan++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2657</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2658</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (colSpan &gt; 1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2659</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2660</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> spanStr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2661</span><span class="doxyLineContent"><span class="doxyHighlight">        spanStr.<a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">setNum</a>(colSpan);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2662</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">" colspan=\""</span><span class="doxyHighlight"> + spanStr + </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2663</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2664</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// need at least one space on either side of the cell text in</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2665</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// order for doxygen to do other formatting</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2666</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"&gt; "</span><span class="doxyHighlight"> + cellText + </span><span class="doxyHighlightStringLiteral">" \\ilinebr &lt;/"</span><span class="doxyHighlight"> + cellTag + </span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2667</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2668</span><span class="doxyLineContent"><span class="doxyHighlight">    cellTag = </span><span class="doxyHighlightStringLiteral">"td"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2669</span><span class="doxyLineContent"><span class="doxyHighlight">    cellClass = </span><span class="doxyHighlightStringLiteral">"class=\"markdownTableBody"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2670</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"  &lt;/tr&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2671</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2672</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>+=</span><span class="doxyHighlightStringLiteral">"&lt;/table&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2673</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2674</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"i={}"</span><span class="doxyHighlight">,i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2675</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2676</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#acdfaca60ec19c0265bac2692d7982726afed76d6718c0a44a25c5e19ae8fb51d1">AlignCenter</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#acdfaca60ec19c0265bac2692d7982726a291bdf1a2284d5648efc75ee78fbeb4c">AlignLeft</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#acdfaca60ec19c0265bac2692d7982726a4258b9785acff3438d08d41ddb4439d9">AlignNone</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#acdfaca60ec19c0265bac2692d7982726a4758d977046d9c084a0eaf7434fd29e1">AlignRight</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO\_TRACE\_EXIT</a>, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a90640de61c785c42e3dc3787610b18eb">findTableColumns</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a53933ee56e6d62357cc60bde3156f544">markersToAlignment</a>, <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">QCString::setNum</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.

Referenced by <a href="#a9835402c2d15b122de1c3ba4180ebd58">processBlocks</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### actions {#afbee8604b9f0ac5704c3ee99a7f4c7b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt;Action_t,256&gt; Markdown::Private::actions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 179 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afbee8604b9f0ac5704c3ee99a7f4c7b9">179</a></span><span class="doxyLineContent"><span class="doxyHighlight">  std::array&lt;Action_t,256&gt; <a href="#afbee8604b9f0ac5704c3ee99a7f4c7b9">actions</a>;</span></span></div>

</div>


Referenced by <a href="#ac0a9e3273eb76713a9e197d5be61e11a">processInline</a>.
</div>
</div>

### fileName {#a778a4f710c8847455c0685dba1736c8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString Markdown::Private::fileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 175 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a778a4f710c8847455c0685dba1736c8b">175</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>       <a href="#a778a4f710c8847455c0685dba1736c8b">fileName</a>;</span></span></div>

</div>


Referenced by <a href="#a46231fc8d72391f38170f184dd956ed1">extractTitleId</a> and <a href="#a9b99b7f5084eb08d7ffe43f3fbe79d69">processLink</a>.
</div>
</div>

### indentLevel {#a5e73fa22df79d3f15db2f1824d64f08c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int Markdown::Private::indentLevel =0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 177 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5e73fa22df79d3f15db2f1824d64f08c">177</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">            <a href="#a5e73fa22df79d3f15db2f1824d64f08c">indentLevel</a>=0;  </span><span class="doxyHighlightComment">// 0 is outside markdown, -1=page level</span></span></div>

</div>


Referenced by <a href="#aa8a42c32241bc89aa626ce55c23b7df5">isAtxHeader</a> and <a href="#a5628c6052a120856d53921f8746d0251">isHeaderline</a>.
</div>
</div>

### lineNr {#a98d598fd49a59a5fd0b3eef5d2a35193}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int Markdown::Private::lineNr = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 176 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a98d598fd49a59a5fd0b3eef5d2a35193">176</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">            <a href="#a98d598fd49a59a5fd0b3eef5d2a35193">lineNr</a> = 0;</span></span></div>

</div>


Referenced by <a href="#a46231fc8d72391f38170f184dd956ed1">extractTitleId</a>.
</div>
</div>

### linkRefs {#a5dd95f5138a9eb830f708bf8f669e89b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;std::string,LinkRef&gt; Markdown::Private::linkRefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 174 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5dd95f5138a9eb830f708bf8f669e89b">174</a></span><span class="doxyLineContent"><span class="doxyHighlight">  std::unordered_map&lt;std::string,LinkRef&gt; <a href="#a5dd95f5138a9eb830f708bf8f669e89b">linkRefs</a>;</span></span></div>

</div>


Referenced by <a href="#a9835402c2d15b122de1c3ba4180ebd58">processBlocks</a> and <a href="#a9b99b7f5084eb08d7ffe43f3fbe79d69">processLink</a>.
</div>
</div>

### out {#a13ea88c6a2b91303ba3be08d61bd17df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString Markdown::Private::out</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 178 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a13ea88c6a2b91303ba3be08d61bd17df">178</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>       <a href="#a13ea88c6a2b91303ba3be08d61bd17df">out</a>;</span></span></div>

</div>


Referenced by <a href="#a681582d0e894782b9509baa541931151">addStrEscapeUtf8Nbsp</a>, <a href="#a9835402c2d15b122de1c3ba4180ebd58">processBlocks</a>, <a href="#a42dc4e1d481af0574e750df55678d54d">processCodeSpan</a>, <a href="#a0bb20b07bce14eca215477b9ec05adbd">processEmphasis1</a>, <a href="#abbb763f2449b932ef3468560e30a0478">processEmphasis2</a>, <a href="#a4041a1e946c4402894bfff49b611e63b">processEmphasis3</a>, <a href="#aa4f4085dfd3e73ae354c7cfd6fa69faf">processHtmlTagWrite</a>, <a href="#ac0a9e3273eb76713a9e197d5be61e11a">processInline</a>, <a href="#a9b99b7f5084eb08d7ffe43f3fbe79d69">processLink</a>, <a href="#adafbef72995b1327272b82a2b2075480">processNmdash</a>, <a href="#a9792322da9173be90556ef009d37afa4">processQuotations</a>, <a href="#a0f211ac431de2f23ca4874c125ab1551">processQuoted</a>, <a href="#a43b1695a69a83037471e5445c7c940ce">processSpecialCommand</a>, <a href="#a2a97ed987f163573d91e6a46363c99de">writeBlockQuote</a>, <a href="#a79fd3fae285ba1f1beeb84c8e858bf46">writeCodeBlock</a>, <a href="#a494fc3fc6c848a37caa06e5d85854ffe">writeFencedCodeBlock</a>, <a href="#a1213861d8af699057686e457bce66509">writeMarkdownImage</a>, <a href="#af7ceebe6b90c368816a6d9bd0ca501c0">writeOneLineHeaderOrRuler</a> and <a href="#a21b82aade2e5a369ec438f0cd49f8107">writeTableBlock</a>.
</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
