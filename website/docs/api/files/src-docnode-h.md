---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/docnode-h
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `docnode.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;cstdio&gt;
#include &lt;cstdint&gt;
#include &lt;vector&gt;
#include &lt;memory&gt;
#include &lt;variant&gt;
#include &lt;type_traits&gt;
#include "<a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/docvisitor-h">docvisitor.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/docparser-h">docparser.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/htmlattrib-h">htmlattrib.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/htmlentity-h">htmlentity.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/section-h">section.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/construct-h">construct.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/cite-h">cite.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/namespaces/details">details</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docnode">DocNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Abstract node interface with type information. <a href="/web-doxygen/docs/api/classes/docnode/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/doccompoundnode">DocCompoundNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Base class for nodes with children. <a href="/web-doxygen/docs/api/classes/doccompoundnode/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docword">DocWord</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a word. <a href="/web-doxygen/docs/api/classes/docword/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/doclinkedword">DocLinkedWord</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a word that can be linked to something. <a href="/web-doxygen/docs/api/classes/doclinkedword/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docurl">DocURL</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a URL (or email address) <a href="/web-doxygen/docs/api/classes/docurl/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/doclinebreak">DocLineBreak</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a line break. <a href="/web-doxygen/docs/api/classes/doclinebreak/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/dochorruler">DocHorRuler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a horizontal ruler. <a href="/web-doxygen/docs/api/classes/dochorruler/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docanchor">DocAnchor</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing an anchor. <a href="/web-doxygen/docs/api/classes/docanchor/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/doccite">DocCite</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a citation of some bibliographic reference. <a href="/web-doxygen/docs/api/classes/doccite/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a style change. <a href="/web-doxygen/docs/api/classes/docstylechange/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a special symbol. <a href="/web-doxygen/docs/api/classes/docsymbol/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docemoji">DocEmoji</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing an emoji. <a href="/web-doxygen/docs/api/classes/docemoji/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docwhitespace">DocWhiteSpace</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing some amount of white space. <a href="/web-doxygen/docs/api/classes/docwhitespace/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docseparator">DocSeparator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a separator. <a href="/web-doxygen/docs/api/classes/docseparator/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a verbatim, unparsed text fragment. <a href="/web-doxygen/docs/api/classes/docverbatim/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/docverbatim/private">Private</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docinclude">DocInclude</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing an included text block from file. <a href="/web-doxygen/docs/api/classes/docinclude/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docincoperator">DocIncOperator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a include/dontinclude operator block. <a href="/web-doxygen/docs/api/classes/docincoperator/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docformula">DocFormula</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing an item of a cross-referenced list. <a href="/web-doxygen/docs/api/classes/docformula/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docindexentry">DocIndexEntry</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing an entry in the index. <a href="/web-doxygen/docs/api/classes/docindexentry/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docautolist">DocAutoList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing an auto List. <a href="/web-doxygen/docs/api/classes/docautolist/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docautolistitem">DocAutoListItem</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing an item of a auto list. <a href="/web-doxygen/docs/api/classes/docautolistitem/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/doctitle">DocTitle</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a simple section title. <a href="/web-doxygen/docs/api/classes/doctitle/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docxrefitem">DocXRefItem</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing an item of a cross-referenced list. <a href="/web-doxygen/docs/api/classes/docxrefitem/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docimage">DocImage</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing an image. <a href="/web-doxygen/docs/api/classes/docimage/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/docimage/private">Private</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docdiagramfilebase">DocDiagramFileBase</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/docdiagramfilebase/private">Private</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docdotfile">DocDotFile</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a dot file. <a href="/web-doxygen/docs/api/classes/docdotfile/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docmscfile">DocMscFile</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a msc file. <a href="/web-doxygen/docs/api/classes/docmscfile/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docdiafile">DocDiaFile</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a dia file. <a href="/web-doxygen/docs/api/classes/docdiafile/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docplantumlfile">DocPlantUmlFile</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a uml file. <a href="/web-doxygen/docs/api/classes/docplantumlfile/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docvhdlflow">DocVhdlFlow</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a VHDL flow chart. <a href="/web-doxygen/docs/api/classes/docvhdlflow/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/doclink">DocLink</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a link to some item. <a href="/web-doxygen/docs/api/classes/doclink/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docref">DocRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a reference to some item. <a href="/web-doxygen/docs/api/classes/docref/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docinternalref">DocInternalRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing an internal reference to some item. <a href="/web-doxygen/docs/api/classes/docinternalref/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/dochref">DocHRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a Hypertext reference. <a href="/web-doxygen/docs/api/classes/dochref/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/dochtmlsummary">DocHtmlSummary</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node Html summary. <a href="/web-doxygen/docs/api/classes/dochtmlsummary/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/dochtmldetails">DocHtmlDetails</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node Html details. <a href="/web-doxygen/docs/api/classes/dochtmldetails/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/dochtmlheader">DocHtmlHeader</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node Html heading. <a href="/web-doxygen/docs/api/classes/dochtmlheader/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/dochtmldesctitle">DocHtmlDescTitle</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a Html description item. <a href="/web-doxygen/docs/api/classes/dochtmldesctitle/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/dochtmldesclist">DocHtmlDescList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a Html description list. <a href="/web-doxygen/docs/api/classes/dochtmldesclist/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docsection">DocSection</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a normal section. <a href="/web-doxygen/docs/api/classes/docsection/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docsecrefitem">DocSecRefItem</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a reference to a section. <a href="/web-doxygen/docs/api/classes/docsecrefitem/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docsecreflist">DocSecRefList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a list of section references. <a href="/web-doxygen/docs/api/classes/docsecreflist/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docinternal">DocInternal</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing an internal section of documentation. <a href="/web-doxygen/docs/api/classes/docinternal/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docparblock">DocParBlock</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing an block of paragraphs. <a href="/web-doxygen/docs/api/classes/docparblock/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docsimplelist">DocSimpleList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a simple list. <a href="/web-doxygen/docs/api/classes/docsimplelist/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/dochtmllist">DocHtmlList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a Html list. <a href="/web-doxygen/docs/api/classes/dochtmllist/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docsimplesect">DocSimpleSect</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a simple section. <a href="/web-doxygen/docs/api/classes/docsimplesect/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docsimplesectsep">DocSimpleSectSep</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a separator between two simple sections of the same type. <a href="/web-doxygen/docs/api/classes/docsimplesectsep/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docparamsect">DocParamSect</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a parameter section. <a href="/web-doxygen/docs/api/classes/docparamsect/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docpara">DocPara</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a paragraph in the documentation tree. <a href="/web-doxygen/docs/api/classes/docpara/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docparamlist">DocParamList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a parameter list. <a href="/web-doxygen/docs/api/classes/docparamlist/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docsimplelistitem">DocSimpleListItem</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a simple list item. <a href="/web-doxygen/docs/api/classes/docsimplelistitem/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/dochtmllistitem">DocHtmlListItem</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a HTML list item. <a href="/web-doxygen/docs/api/classes/dochtmllistitem/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/dochtmldescdata">DocHtmlDescData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a HTML description data. <a href="/web-doxygen/docs/api/classes/dochtmldescdata/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/dochtmlcell">DocHtmlCell</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a HTML table cell. <a href="/web-doxygen/docs/api/classes/dochtmlcell/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/dochtmlcaption">DocHtmlCaption</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a HTML table caption. <a href="/web-doxygen/docs/api/classes/dochtmlcaption/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/dochtmlrow">DocHtmlRow</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a HTML table row. <a href="/web-doxygen/docs/api/classes/dochtmlrow/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/dochtmltable">DocHtmlTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing a HTML table. <a href="/web-doxygen/docs/api/classes/dochtmltable/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/dochtmlblockquote">DocHtmlBlockQuote</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Node representing an HTML blockquote. <a href="/web-doxygen/docs/api/classes/dochtmlblockquote/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/doctext">DocText</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Root node of a text fragment. <a href="/web-doxygen/docs/api/classes/doctext/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docroot">DocRoot</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Root node of documentation tree. <a href="/web-doxygen/docs/api/classes/docroot/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/details/impl">Impl&lt;T, Ts&gt;</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/details/impl-f7399366cd6336ecbea702c3289d9432">Impl&lt;T&gt;</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/details/has-method-children">has_method_children&lt;T, typename&gt;</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/details/has-method-children-172d1b5c44de4c71f21bb0fc526052e1">has_method_children&lt;T, std::void_t&lt; decltype(std::declval&lt; T &gt;().children())&gt;&gt;</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docnodeast">DocNodeAST</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Class representing the abstract syntax tree of a documentation block. <a href="/web-doxygen/docs/api/classes/docnodeast/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> = std::variant&lt; <a href="/web-doxygen/docs/api/classes/docword">DocWord</a>, <a href="/web-doxygen/docs/api/classes/doclinkedword">DocLinkedWord</a>, <a href="/web-doxygen/docs/api/classes/docurl">DocURL</a>, <a href="/web-doxygen/docs/api/classes/doclinebreak">DocLineBreak</a>, <a href="/web-doxygen/docs/api/classes/dochorruler">DocHorRuler</a>, <a href="/web-doxygen/docs/api/classes/docanchor">DocAnchor</a>, <a href="/web-doxygen/docs/api/classes/doccite">DocCite</a>, <a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a>, <a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>, <a href="/web-doxygen/docs/api/classes/docemoji">DocEmoji</a>, <a href="/web-doxygen/docs/api/classes/docwhitespace">DocWhiteSpace</a>, <a href="/web-doxygen/docs/api/classes/docseparator">DocSeparator</a>, <a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a>, <a href="/web-doxygen/docs/api/classes/docinclude">DocInclude</a>, <a href="/web-doxygen/docs/api/classes/docincoperator">DocIncOperator</a>, <a href="/web-doxygen/docs/api/classes/docformula">DocFormula</a>, <a href="/web-doxygen/docs/api/classes/docindexentry">DocIndexEntry</a>, <a href="/web-doxygen/docs/api/classes/docautolist">DocAutoList</a>, <a href="/web-doxygen/docs/api/classes/docautolistitem">DocAutoListItem</a>, <a href="/web-doxygen/docs/api/classes/doctitle">DocTitle</a>, <a href="/web-doxygen/docs/api/classes/docxrefitem">DocXRefItem</a>, <a href="/web-doxygen/docs/api/classes/docimage">DocImage</a>, <a href="/web-doxygen/docs/api/classes/docdotfile">DocDotFile</a>, <a href="/web-doxygen/docs/api/classes/docmscfile">DocMscFile</a>, <a href="/web-doxygen/docs/api/classes/docdiafile">DocDiaFile</a>, <a href="/web-doxygen/docs/api/classes/docvhdlflow">DocVhdlFlow</a>, <a href="/web-doxygen/docs/api/classes/doclink">DocLink</a>, <a href="/web-doxygen/docs/api/classes/docref">DocRef</a>, <a href="/web-doxygen/docs/api/classes/docinternalref">DocInternalRef</a>, <a href="/web-doxygen/docs/api/classes/dochref">DocHRef</a>, <a href="/web-doxygen/docs/api/classes/dochtmlheader">DocHtmlHeader</a>, <a href="/web-doxygen/docs/api/classes/dochtmldesctitle">DocHtmlDescTitle</a>, <a href="/web-doxygen/docs/api/classes/dochtmldesclist">DocHtmlDescList</a>, <a href="/web-doxygen/docs/api/classes/docsection">DocSection</a>, <a href="/web-doxygen/docs/api/classes/docsecrefitem">DocSecRefItem</a>, <a href="/web-doxygen/docs/api/classes/docsecreflist">DocSecRefList</a>, <a href="/web-doxygen/docs/api/classes/docinternal">DocInternal</a>, <a href="/web-doxygen/docs/api/classes/docparblock">DocParBlock</a>, <a href="/web-doxygen/docs/api/classes/docsimplelist">DocSimpleList</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist">DocHtmlList</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect">DocSimpleSect</a>, <a href="/web-doxygen/docs/api/classes/docsimplesectsep">DocSimpleSectSep</a>, <a href="/web-doxygen/docs/api/classes/docparamsect">DocParamSect</a>, <a href="/web-doxygen/docs/api/classes/docpara">DocPara</a>, <a href="/web-doxygen/docs/api/classes/docparamlist">DocParamList</a>, <a href="/web-doxygen/docs/api/classes/docsimplelistitem">DocSimpleListItem</a>, <a href="/web-doxygen/docs/api/classes/dochtmllistitem">DocHtmlListItem</a>, <a href="/web-doxygen/docs/api/classes/dochtmldescdata">DocHtmlDescData</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell">DocHtmlCell</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcaption">DocHtmlCaption</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow">DocHtmlRow</a>, <a href="/web-doxygen/docs/api/classes/dochtmltable">DocHtmlTable</a>, <a href="/web-doxygen/docs/api/classes/dochtmlblockquote">DocHtmlBlockQuote</a>, <a href="/web-doxygen/docs/api/classes/doctext">DocText</a>, <a href="/web-doxygen/docs/api/classes/docroot">DocRoot</a>, <a href="/web-doxygen/docs/api/classes/dochtmldetails">DocHtmlDetails</a>, <a href="/web-doxygen/docs/api/classes/dochtmlsummary">DocHtmlSummary</a>, <a href="/web-doxygen/docs/api/classes/docplantumlfile">DocPlantUmlFile</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6d1fdb00451a93f990d0f6206157910">docNodeName</a> (const DocWord &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a4e9203a51278e3621896a36b1e0b32">docNodeName</a> (const DocLinkedWord &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8d37bbcaf17e92662b72b7f36324f64">docNodeName</a> (const DocURL &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee98e18d7997e805cb6c8bfa956209c9">docNodeName</a> (const DocLineBreak &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b3bd1babd5d330a232ae37e900f2218">docNodeName</a> (const DocHorRuler &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af27355d33faf413068bf3674df0126db">docNodeName</a> (const DocAnchor &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25bf981b4791e57f2119ad94d0f2bbf0">docNodeName</a> (const DocCite &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af387a885d3aa8da332a8af63afa4c833">docNodeName</a> (const DocStyleChange &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a427af078c464b8b0f486d2110ba5429f">docNodeName</a> (const DocSymbol &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf3a2068f98e15602e95e59b84799bac">docNodeName</a> (const DocEmoji &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcaca917d445e5bfa04bd9020f24e599">docNodeName</a> (const DocWhiteSpace &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad47705bac950b04139abff1a4d68233f">docNodeName</a> (const DocSeparator &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88d11625902fd3b7c28c24ec71f3983a">docNodeName</a> (const DocVerbatim &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71075bd9e3f3d2a72e8f3076668dbaa8">docNodeName</a> (const DocInclude &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75afda583e4bbc008bbc46b7bb80e0af">docNodeName</a> (const DocIncOperator &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82c31a69ce614bcf74ca55afb6d6a8c0">docNodeName</a> (const DocFormula &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dc79fee9524bbb27295812018b6620f">docNodeName</a> (const DocIndexEntry &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cc678f63d6ba116f503efe8d453107d">docNodeName</a> (const DocAutoList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc2a5b1ad9142a12d64fee4dcc586db5">docNodeName</a> (const DocAutoListItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09151e13b101aa07f9c073327f6db122">docNodeName</a> (const DocTitle &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca98d14378df2e86596505211a6f546b">docNodeName</a> (const DocXRefItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f959d81b4e60f01de1c537c16f61123">docNodeName</a> (const DocImage &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b07a6fada0036ce08402d3efdc1c036">docNodeName</a> (const DocDotFile &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09e185e46c7099f19f7f7e3f77ca89af">docNodeName</a> (const DocMscFile &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c41781c8655bb4ce801873b7dec32cf">docNodeName</a> (const DocDiaFile &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ee7052d381ee681051ec738c6fce411">docNodeName</a> (const DocVhdlFlow &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a779962b3aab813cef2c355940b054089">docNodeName</a> (const DocLink &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6648e535ff455bb7ce00f4184d94eb2">docNodeName</a> (const DocRef &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a563e6c63cd16b4d08805f1a10ebffd9a">docNodeName</a> (const DocInternalRef &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd8fabda622e59449cebdb72b389a925">docNodeName</a> (const DocHRef &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99c070811d0b461d9dfd9731777160a5">docNodeName</a> (const DocHtmlHeader &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5ba80d2b9d952d83532cbcba11e394e">docNodeName</a> (const DocHtmlDescTitle &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4858deb2895bfd3fed4256e7cdfb5498">docNodeName</a> (const DocHtmlDescList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fd07227bf5111ea5b4f9531dfb7fd32">docNodeName</a> (const DocSection &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f9ea7dd2b3bed3276b9322697c97116">docNodeName</a> (const DocSecRefItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af188b41ffe248dcb4bc5baf6640b5f4c">docNodeName</a> (const DocSecRefList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f176168cc5aced62e686b2f0db37e91">docNodeName</a> (const DocInternal &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a079c5210810b81f7148c0e61d1d180d6">docNodeName</a> (const DocParBlock &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5780017a98d463ff70ce1e76d882a688">docNodeName</a> (const DocSimpleList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bdcaefdf91b840f83261a9b37c462d0">docNodeName</a> (const DocHtmlList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae27ec5e952ca6128d692e37420977317">docNodeName</a> (const DocSimpleSect &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a1ce3813313037a38127afba1ea4c14">docNodeName</a> (const DocSimpleSectSep &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7548b0f7993bc2e6884cc649aef916aa">docNodeName</a> (const DocParamSect &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab21890529522fb9f5c8e4d38e5e12a38">docNodeName</a> (const DocPara &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb2cfae00037287ead56242ba925bc9e">docNodeName</a> (const DocParamList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab264be716147f46b6efe94ee708b6a5c">docNodeName</a> (const DocSimpleListItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ac362ec5f753a1bf585464632737a18">docNodeName</a> (const DocHtmlListItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05e42dbbeebd0072039270cc1c5dd2e3">docNodeName</a> (const DocHtmlDescData &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9f1beb16da5569fbad494b933314ebf">docNodeName</a> (const DocHtmlCell &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa30436cc01e54e6696fcea15319966d7">docNodeName</a> (const DocHtmlCaption &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64dbc24be458ea8c117c9d47eb8b8c4b">docNodeName</a> (const DocHtmlRow &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd3c1d75162ac744f586a16198910c07">docNodeName</a> (const DocHtmlTable &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab16aa23128c07de6c1209bd6177f79b0">docNodeName</a> (const DocHtmlBlockQuote &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dd1ebffb590724e4767959c4aacfcbe">docNodeName</a> (const DocText &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6550f443efcd3532c300cf2fe1145ef">docNodeName</a> (const DocRoot &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac6228581134621302d6978215b0b540">docNodeName</a> (const DocHtmlDetails &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18ad2b25da3577042c0632f33a0be7d8">docNodeName</a> (const DocHtmlSummary &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63f7ebb62a8039c0b9bb2918263b5555">docNodeName</a> (const DocPlantUmlFile &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa08872da61afee56859056e5a0612633">parent</a> (DocNodeVariant *n)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
returns the parent node of a given node <em>n</em> or nullptr if the node has no parent. <a href="#aa08872da61afee56859056e5a0612633">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr const <a href="#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4feec38265e781de0502142e696763a">parent</a> (const DocNodeVariant *n)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
returns the parent node of a given node <em>n</em> or nullptr if the node has no parent. <a href="#ab4feec38265e781de0502142e696763a">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class... Ts&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1c1632e37b281677f09baa3acce082cf">holds_one_of_alternatives</a> (const DocNodeVariant &amp;v)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
returns true iff <em>v</em> holds one of types passed as template parameters <a href="#a1c1632e37b281677f09baa3acce082cf">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a757dcb2ad9a839e761e6808f8cb51a04">call_method_children</a> (DocNodeVariant *v)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6c2b2b9786502bb407f7858cc1deef7">docNodeName</a> (const DocNodeVariant &amp;v)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cee4ebd85699ca3a3e70eb19dc5a199">dumpDocNodeSizes</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae06df9ac205468d82301870dbe23905c">dumpDocNodeList</a> (const DocNodeList &amp;children)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, class... Args&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa42674aaf44286a4dbbf89f4da21609a">createDocNode</a> (Args &amp;&amp;...args) -&gt; std::unique_ptr&lt; <a href="#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a>&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(x)&nbsp;&nbsp;&nbsp;class x;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(x)&nbsp;&nbsp;&nbsp;x</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a>&nbsp;&nbsp;&nbsp;,</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(x)&nbsp;&nbsp;&nbsp;constexpr const char *<a href="#ae6d1fdb00451a93f990d0f6206157910">docNodeName</a>(const x &amp;/* n */) { return #x; }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(x)&nbsp;&nbsp;&nbsp;#x</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a>&nbsp;&nbsp;&nbsp;,</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(x)&nbsp;&nbsp;&nbsp;#x</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a>&nbsp;&nbsp;&nbsp;,</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(x)&nbsp;&nbsp;&nbsp;sizeof(x)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a>&nbsp;&nbsp;&nbsp;,</td>
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

### DocNodeVariant {#a15a8494c4d80bb52db036d2fb5e9e9f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using DocNodeVariant =  std::variant&lt;
  DocWord , DocLinkedWord , DocURL , DocLineBreak , DocHorRuler ,  DocAnchor , DocCite , DocStyleChange , DocSymbol , DocEmoji ,  DocWhiteSpace , DocSeparator , DocVerbatim , DocInclude , DocIncOperator ,  DocFormula , DocIndexEntry , DocAutoList , DocAutoListItem , DocTitle ,  DocXRefItem , DocImage , DocDotFile , DocMscFile , DocDiaFile ,  DocVhdlFlow , DocLink , DocRef , DocInternalRef , DocHRef ,  DocHtmlHeader , DocHtmlDescTitle , DocHtmlDescList , DocSection , DocSecRefItem ,  DocSecRefList , DocInternal , DocParBlock , DocSimpleList , DocHtmlList ,  DocSimpleSect , DocSimpleSectSep , DocParamSect , DocPara , DocParamList ,  DocSimpleListItem , DocHtmlListItem , DocHtmlDescData , DocHtmlCell , DocHtmlCaption ,  DocHtmlRow , DocHtmlTable , DocHtmlBlockQuote , DocText , DocRoot ,  DocHtmlDetails , DocHtmlSummary , DocPlantUmlFile 
&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 67 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a15a8494c4d80bb52db036d2fb5e9e9f8">67</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> = std::variant&lt;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### call\_method\_children() {#a757dcb2ad9a839e761e6808f8cb51a04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNodeList * call_method_children (<a href="#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * v)</td>
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



Definition at line 1385 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a757dcb2ad9a839e761e6808f8cb51a04">1385</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a>* <a href="#a757dcb2ad9a839e761e6808f8cb51a04">call_method_children</a>(<a href="#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *v)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1386</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1387</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::visit([](</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight">&amp;&amp; value) -&gt; <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a>* {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1388</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">constexpr</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/structs/details/has-method-children">details::has_method_children</a>&lt;</span><span class="doxyHighlightKeyword">decltype</span><span class="doxyHighlight">(value)&gt;::value) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1389</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> &amp;value.children();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1390</span><span class="doxyLineContent"><span class="doxyHighlight">    } </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1391</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1392</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1393</span><span class="doxyLineContent"><span class="doxyHighlight">  }, *v);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1394</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a71dd66dcbef8ad6aa74feb1e87e2a06b">flattenParagraphs</a>.
</div>
</div>

### createDocNode() {#aa42674aaf44286a4dbbf89f4da21609a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class... Args&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; DocNodeVariant &gt; createDocNode (Args &amp;&amp;... args)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 1495 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa42674aaf44286a4dbbf89f4da21609a">1495</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::unique_ptr&lt;DocNodeVariant&gt; <a href="#aa42674aaf44286a4dbbf89f4da21609a">createDocNode</a>(Args&amp;&amp;...args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1496</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1497</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> node = std::make_unique&lt;DocNodeVariant&gt;(T(std::forward&lt;Args&gt;(args)...));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1498</span><span class="doxyLineContent"><span class="doxyHighlight">  std::get_if&lt;T&gt;(node.get())-&gt;setThisVariant(node.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1499</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> node;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1500</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/dochtmldetails/#a12b425f8cc20de1ed4183ea8a9a454f8">DocHtmlDetails::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmltable/#a6f4ae9d09701b93305b6e90260bc5662">DocHtmlTable::parse</a>, <a href="/web-doxygen/docs/api/classes/docsection/#a9b6c66c2f51de17bc5748754090c1e41">DocSection::parse</a>, <a href="/web-doxygen/docs/api/classes/docsimplelistitem/#a82b621ab52e4940d34704be3841cc36e">DocSimpleListItem::parse</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3e4b28664b6fe921f89c934f9d2f4ba0">DocSimpleSect::parse</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a7eb70bb58c30a5dab96c862583503b7e">DocSimpleSect::parseRcs</a> and <a href="/web-doxygen/docs/api/classes/dochtmldetails/#a7f705aecadc99bf342402a00f7c7fc38">DocHtmlDetails::parseSummary</a>.
</div>
</div>

### docNodeName() {#ae6d1fdb00451a93f990d0f6206157910}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docword">DocWord</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>


Reference <a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC\_NODES</a>.

Referenced by <a href="#ae06df9ac205468d82301870dbe23905c">dumpDocNodeList</a>.
</div>
</div>

### docNodeName() {#a9a4e9203a51278e3621896a36b1e0b32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/doclinkedword">DocLinkedWord</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#ab8d37bbcaf17e92662b72b7f36324f64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docurl">DocURL</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#aee98e18d7997e805cb6c8bfa956209c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/doclinebreak">DocLineBreak</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a8b3bd1babd5d330a232ae37e900f2218}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/dochorruler">DocHorRuler</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#af27355d33faf413068bf3674df0126db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docanchor">DocAnchor</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a25bf981b4791e57f2119ad94d0f2bbf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/doccite">DocCite</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#af387a885d3aa8da332a8af63afa4c833}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a427af078c464b8b0f486d2110ba5429f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#abf3a2068f98e15602e95e59b84799bac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docemoji">DocEmoji</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#adcaca917d445e5bfa04bd9020f24e599}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docwhitespace">DocWhiteSpace</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#ad47705bac950b04139abff1a4d68233f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docseparator">DocSeparator</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a88d11625902fd3b7c28c24ec71f3983a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a71075bd9e3f3d2a72e8f3076668dbaa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docinclude">DocInclude</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a75afda583e4bbc008bbc46b7bb80e0af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docincoperator">DocIncOperator</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a82c31a69ce614bcf74ca55afb6d6a8c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docformula">DocFormula</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a5dc79fee9524bbb27295812018b6620f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docindexentry">DocIndexEntry</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a6cc678f63d6ba116f503efe8d453107d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docautolist">DocAutoList</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#acc2a5b1ad9142a12d64fee4dcc586db5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docautolistitem">DocAutoListItem</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a09151e13b101aa07f9c073327f6db122}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/doctitle">DocTitle</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#aca98d14378df2e86596505211a6f546b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docxrefitem">DocXRefItem</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a8f959d81b4e60f01de1c537c16f61123}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docimage">DocImage</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a8b07a6fada0036ce08402d3efdc1c036}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docdotfile">DocDotFile</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a09e185e46c7099f19f7f7e3f77ca89af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docmscfile">DocMscFile</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a2c41781c8655bb4ce801873b7dec32cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docdiafile">DocDiaFile</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a1ee7052d381ee681051ec738c6fce411}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docvhdlflow">DocVhdlFlow</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a779962b3aab813cef2c355940b054089}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/doclink">DocLink</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#ad6648e535ff455bb7ce00f4184d94eb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docref">DocRef</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a563e6c63cd16b4d08805f1a10ebffd9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docinternalref">DocInternalRef</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#afd8fabda622e59449cebdb72b389a925}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/dochref">DocHRef</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a99c070811d0b461d9dfd9731777160a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/dochtmlheader">DocHtmlHeader</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#af5ba80d2b9d952d83532cbcba11e394e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/dochtmldesctitle">DocHtmlDescTitle</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a4858deb2895bfd3fed4256e7cdfb5498}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/dochtmldesclist">DocHtmlDescList</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a7fd07227bf5111ea5b4f9531dfb7fd32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docsection">DocSection</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a2f9ea7dd2b3bed3276b9322697c97116}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docsecrefitem">DocSecRefItem</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#af188b41ffe248dcb4bc5baf6640b5f4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docsecreflist">DocSecRefList</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a4f176168cc5aced62e686b2f0db37e91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docinternal">DocInternal</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a079c5210810b81f7148c0e61d1d180d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docparblock">DocParBlock</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a5780017a98d463ff70ce1e76d882a688}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docsimplelist">DocSimpleList</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a6bdcaefdf91b840f83261a9b37c462d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/dochtmllist">DocHtmlList</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#ae27ec5e952ca6128d692e37420977317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docsimplesect">DocSimpleSect</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a9a1ce3813313037a38127afba1ea4c14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docsimplesectsep">DocSimpleSectSep</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a7548b0f7993bc2e6884cc649aef916aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docparamsect">DocParamSect</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#ab21890529522fb9f5c8e4d38e5e12a38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docpara">DocPara</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#abb2cfae00037287ead56242ba925bc9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docparamlist">DocParamList</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#ab264be716147f46b6efe94ee708b6a5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docsimplelistitem">DocSimpleListItem</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a4ac362ec5f753a1bf585464632737a18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/dochtmllistitem">DocHtmlListItem</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a05e42dbbeebd0072039270cc1c5dd2e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/dochtmldescdata">DocHtmlDescData</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#ad9f1beb16da5569fbad494b933314ebf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/dochtmlcell">DocHtmlCell</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#aa30436cc01e54e6696fcea15319966d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/dochtmlcaption">DocHtmlCaption</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a64dbc24be458ea8c117c9d47eb8b8c4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/dochtmlrow">DocHtmlRow</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#acd3c1d75162ac744f586a16198910c07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/dochtmltable">DocHtmlTable</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#ab16aa23128c07de6c1209bd6177f79b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/dochtmlblockquote">DocHtmlBlockQuote</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a7dd1ebffb590724e4767959c4aacfcbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/doctext">DocText</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#ab6550f443efcd3532c300cf2fe1145ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docroot">DocRoot</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#aac6228581134621302d6978215b0b540}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/dochtmldetails">DocHtmlDetails</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a18ad2b25da3577042c0632f33a0be7d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/dochtmlsummary">DocHtmlSummary</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#a63f7ebb62a8039c0b9bb2918263b5555}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="/web-doxygen/docs/api/classes/docplantumlfile">DocPlantUmlFile</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6d1fdb00451a93f990d0f6206157910">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a></span></span></div>

</div>

</div>
</div>

### docNodeName() {#ad6c2b2b9786502bb407f7858cc1deef7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * docNodeName (const <a href="#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> &amp; v)</td>
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



Definition at line 1419 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad6c2b2b9786502bb407f7858cc1deef7">1419</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#ae6d1fdb00451a93f990d0f6206157910">docNodeName</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> &amp;v)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1420</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1421</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *table[] = { <a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a> };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1422</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> table[v.index()];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1423</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC\_NODES</a>.
</div>
</div>

### dumpDocNodeList() {#ae06df9ac205468d82301870dbe23905c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void dumpDocNodeList (const <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp; children)</td>
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



Definition at line 1451 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae06df9ac205468d82301870dbe23905c">1451</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae06df9ac205468d82301870dbe23905c">dumpDocNodeList</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;children)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1452</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1453</span><span class="doxyLineContent"><span class="doxyHighlight">  printf(</span><span class="doxyHighlightStringLiteral">"children=[\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1454</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;child : children)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1455</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1456</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docword">DocWord</a> *w = std::get_if&lt;DocWord&gt;(&amp;child);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1457</span><span class="doxyLineContent"><span class="doxyHighlight">    printf(</span><span class="doxyHighlightStringLiteral">"  %s (%p) %s\n"</span><span class="doxyHighlight">,<a href="#ae6d1fdb00451a93f990d0f6206157910">docNodeName</a>(child),(</span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight">*)&amp;child,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(w?w-&gt;<a href="/web-doxygen/docs/api/classes/docword/#af9ecbc2daa4fb051a07c510ab0a7d461">word</a>():</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1458</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1459</span><span class="doxyLineContent"><span class="doxyHighlight">  printf(</span><span class="doxyHighlightStringLiteral">"]\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1460</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ae6d1fdb00451a93f990d0f6206157910">docNodeName</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a> and <a href="/web-doxygen/docs/api/classes/docword/#af9ecbc2daa4fb051a07c510ab0a7d461">DocWord::word</a>.
</div>
</div>

### dumpDocNodeSizes() {#a0cee4ebd85699ca3a3e70eb19dc5a199}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void dumpDocNodeSizes ()</td>
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



Definition at line 1427 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0cee4ebd85699ca3a3e70eb19dc5a199">1427</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0cee4ebd85699ca3a3e70eb19dc5a199">dumpDocNodeSizes</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1428</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1429</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DN(x)  #x</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1430</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DN_SEP ,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1431</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *tableWithNames[] = { <a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a> };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1432</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#undef DN</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1433</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#undef DN_SEP</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1434</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1435</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DN(x)  sizeof(x)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1436</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DN_SEP ,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1437</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> tableWithSizes[] = { <a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC_NODES</a> };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1438</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#undef DN</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1439</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#undef DN_SEP</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1440</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1441</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> maxSize=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1442</span><span class="doxyLineContent"><span class="doxyHighlight">  printf(</span><span class="doxyHighlightStringLiteral">"DocNodeVariant(\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1443</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;i&lt;</span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(tableWithNames)/</span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(tableWithNames[0]);i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1444</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1445</span><span class="doxyLineContent"><span class="doxyHighlight">    printf(</span><span class="doxyHighlightStringLiteral">"  /* %2zu */ sizeof(%s)=%zu\n"</span><span class="doxyHighlight">,i,tableWithNames[i],tableWithSizes[i]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1446</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tableWithSizes[i]&gt;maxSize) maxSize = tableWithSizes[i];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1447</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1448</span><span class="doxyLineContent"><span class="doxyHighlight">  printf(</span><span class="doxyHighlightStringLiteral">")=%zu\n"</span><span class="doxyHighlight">,maxSize);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1449</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a9a1f232ee7a2138f67140f80ce7c6628">DOC\_NODES</a>.
</div>
</div>

### holds\_one\_of\_alternatives() {#a1c1632e37b281677f09baa3acce082cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class... Ts&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool holds_one_of_alternatives (const <a href="#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> &amp; v)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

returns true iff <em>v</em> holds one of types passed as template parameters

Definition at line 1366 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c1632e37b281677f09baa3acce082cf">1366</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">constexpr</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a1c1632e37b281677f09baa3acce082cf">holds_one_of_alternatives</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> &amp;v)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1367</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1368</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/details/impl/#a0fd4278ad6e530e3ed836849026072b6">details::Impl&lt;Ts...&gt;::holds_one_of_alternatives</a>(v);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1369</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/structs/details/impl/#a0fd4278ad6e530e3ed836849026072b6">details::Impl&lt; T, Ts &gt;::holds\_one\_of\_alternatives</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#a0f227199a40c25549528bd2f6a721483">determineIfNeedsTag</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#a64abc1e2247e925f2abbdd81045b8e08">getParagraphContext</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#aa2c5d961b9ad326122481acacc033172">LatexDocVisitor::isTableNested</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#a86acf8b4839daaae86b0a90ca98767b8">mustBeOutsideParagraph</a> and <a href="/web-doxygen/docs/api/classes/docpara/#aafc94d2ed7856e4a11e404e2ee05fb40">DocPara::parse</a>.
</div>
</div>

### parent() {#aa08872da61afee56859056e5a0612633}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNodeVariant * parent (<a href="#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * n)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

returns the parent node of a given node <em>n</em> or nullptr if the node has no parent.

Definition at line 1330 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa08872da61afee56859056e5a0612633">1330</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">constexpr</span><span class="doxyHighlight"> <a href="#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="#aa08872da61afee56859056e5a0612633">parent</a>(<a href="#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *n)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1331</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1332</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> n ? std::visit([](</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;&amp;x)-&gt;</span><span class="doxyHighlightKeyword">decltype</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight">) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> x.parent(); }, *n) : </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1333</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#a9d5caa3df18ab19e549d3b603a716780">buildDirectories</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#adbe932c521ee8cde5ccc5cdca438fa5f">checkIfHtmlEndTagEndsAutoList</a>, <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#a597bb9c69db0e2c07006194a6cb87b27">LayoutDocManager::createChildNavEntry</a>, <a href="/web-doxygen/docs/api/classes/ftvhelp/#a5949816300bc9d6a104dfd8305aa4e6f">FTVHelp::decContentsDepth</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ae88d59b299df415c0c2028d863288599">DocParser::defaultHandleTitleAndSize</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a105e51dc946d1daa2914afd2bc3e72af">DocParser::defaultHandleToken</a>, <a href="/web-doxygen/docs/api/classes/definemanager/definesperfile/#a28f786619e5a63c13d9f0d6233914675">DefineManager::DefinesPerFile::DefinesPerFile</a>, <a href="/web-doxygen/docs/api/classes/docdiafile/#a301dcfb948eec530d3d3dbf2745b4070">DocDiaFile::DocDiaFile</a>, <a href="/web-doxygen/docs/api/classes/docdotfile/#af70a6dd9deae4692c3a35ffa97a3b425">DocDotFile::DocDotFile</a>, <a href="/web-doxygen/docs/api/classes/docmscfile/#a6f948f54558a1198ae557ca57a3360a7">DocMscFile::DocMscFile</a>, <a href="/web-doxygen/docs/api/classes/docplantumlfile/#a31c47df6bcc6c6ce636b6a6898e27bd3">DocPlantUmlFile::DocPlantUmlFile</a>, <a href="/web-doxygen/docs/api/classes/treediagram/#a0993890eece743a86f2d874f288b6f7d">TreeDiagram::drawConnectors</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#a24d81fe9c93c2e315bd713aed99379c4">dupOfParent</a>, <a href="/web-doxygen/docs/api/classes/docparser/#afa9541b35f25f2f63a6f5ff338967f22">DocParser::errorHandleDefaultToken</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad3f3c94bc6e432d34fa1a51db3b7d5e2">externalLinkTarget</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a3345ad9e2ab3a9d1b524391ae5f6c545">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#aa1a81456e5d00c9e3c4ff4d9f3e3c123">generateIndent</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#af9cb5d8af596e5b9eb054f0b3a5c7e67">generateIndentLabel</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#a64abc1e2247e925f2abbdd81045b8e08">getParagraphContext</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a6a6c955c9001d67e4b722038bfc5f16b">DocParser::handleAHref</a>, <a href="/web-doxygen/docs/api/classes/docparser/#adf24a6cf025048b8a3235ca2c897dc06">DocParser::handleAnchor</a>, <a href="/web-doxygen/docs/api/classes/docparser/#aa923af2c2ca8d81fa9b65a6fa1e65a83">DocParser::handleImage</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ae3321ce556544cc7281b783f2b250be4">DocParser::handleImg</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a7cbce284509ccf3109aa71472842ce4e">DocParser::handleInitialStyleCommands</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a334b7286f0a4445d85743cce35a3c090">DocParser::handleInternalRef</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a2b2971ad53e50d90ca4affca6a6e1d67">DocParser::handleLinkedWord</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a367fe5ccd7e0378c2e5c94df6e60dd0d">DocParser::handleParameterType</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a94f06b2f61c71069d46589a7cd4f7b6b">DocParser::handlePendingStyleCommands</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ab8ac10aa71d5d6c021a6e2f08df318f8">DocParser::handlePrefix</a>, <a href="/web-doxygen/docs/api/classes/docparser/#abf46a000544ae1a4f45df6430cd3e6bf">DocParser::handleStyleArgument</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ab004ed65c6ab11f6ca2a4caee610bb49">DocParser::handleStyleEnter</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a92d044475f815e09877c88ce15399802">DocParser::handleStyleLeave</a>, <a href="/web-doxygen/docs/api/classes/diagramrow/#a8c301e781bb14b1a23c00974d2050496">DiagramRow::insertClass</a>, <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#ab5e581e18e98e7d8c3394a28791d7680">insideBlockQuote</a>, <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#af5482286b814ee04eea804a9a3261cf4">insideDetails</a>, <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a8ab563dcf6c027ecdc4b8df7c79cd166">insideDL</a>, <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a786afe8925235dea586eb23046acaf41">insideLI</a>, <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#af8c289300738a7353cb8e47d343e7998">insideOL</a>, <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a66b237bbac35526d7fa7b944ca815088">insidePRE</a>, <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a2515a32b6dfcda676ef65dd34fad5abf">insideTable</a>, <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a1f32f1e06f22781ceb8f7295ea6fca01">insideUL</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a6d276e7995db319294ea1fb2bc76459e">DocParser::internalValidatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#a520aa4c3a57667d69b67c176e4828d14">isFirstChildNode</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#abe2e2b94699822e58607ee92aa93cfc1">isLastChildNode</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#ab6b89b7570220507ecccee5aa2872f30">isSeparatedParagraph</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab022f0e28018d318dad5e23a75a40f02">isSymbolHidden</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#aa2c5d961b9ad326122481acacc033172">LatexDocVisitor::isTableNested</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#aa069e7d7edbf62f915d7635c7ab5f66e">listIsNested</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#add62a038409ef396c163d584412289cc">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a434a1f775b7fe0a37ad69ba2499cfdfb">parseMain</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#a8e90c9de4676d5baf1fb570c0c0c0495">pathToNode</a>, <a href="/web-doxygen/docs/api/files/src/util-h/#a11f1e398e07986ff1b2977f361e9eea0">recodeString</a> and <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp/#ac4e7090b3ce2c42151afd6b83298096f">writeDotDirDepGraph</a>.
</div>
</div>

### parent() {#ab4feec38265e781de0502142e696763a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DocNodeVariant * parent (const <a href="#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * n)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

returns the parent node of a given node <em>n</em> or nullptr if the node has no parent.

Definition at line 1336 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab4feec38265e781de0502142e696763a">1336</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">constexpr</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="#aa08872da61afee56859056e5a0612633">parent</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *n)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1337</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1338</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> n ? std::visit([](</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;&amp;x)-&gt;</span><span class="doxyHighlightKeyword">decltype</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight">) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> x.parent(); }, *n) : </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1339</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DN {#a6de37e0933d92bb91fcdc1b70ef32e2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DN(x)&nbsp;&nbsp;&nbsp;class x;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 58 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">58</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DN(x) class x;</span></span></div>

</div>

</div>
</div>

### DN {#a6de37e0933d92bb91fcdc1b70ef32e2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DN(x)&nbsp;&nbsp;&nbsp;x</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 65 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">58</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DN(x) class x;</span></span></div>

</div>

</div>
</div>

### DN {#a6de37e0933d92bb91fcdc1b70ef32e2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DN(x)&nbsp;&nbsp;&nbsp;constexpr const char *<a href="#ae6d1fdb00451a93f990d0f6206157910">docNodeName</a>(const x &amp;/* n */) { return #x; }</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 74 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">58</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DN(x) class x;</span></span></div>

</div>

</div>
</div>

### DN {#a6de37e0933d92bb91fcdc1b70ef32e2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DN(x)&nbsp;&nbsp;&nbsp;#x</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 1417 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">58</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DN(x) class x;</span></span></div>

</div>

</div>
</div>

### DN {#a6de37e0933d92bb91fcdc1b70ef32e2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DN(x)&nbsp;&nbsp;&nbsp;#x</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 1429 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">58</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DN(x) class x;</span></span></div>

</div>

</div>
</div>

### DN {#a6de37e0933d92bb91fcdc1b70ef32e2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DN(x)&nbsp;&nbsp;&nbsp;sizeof(x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 1435 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">58</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DN(x) class x;</span></span></div>

</div>

</div>
</div>

### DN\_SEP {#aac3b8854dead0ba7c6a9e83d49b7d945}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DN_SEP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 59 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aac3b8854dead0ba7c6a9e83d49b7d945">59</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DN_SEP</span></span></div>

</div>

</div>
</div>

### DN\_SEP {#aac3b8854dead0ba7c6a9e83d49b7d945}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DN_SEP&nbsp;&nbsp;&nbsp;,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 66 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aac3b8854dead0ba7c6a9e83d49b7d945">59</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DN_SEP</span></span></div>

</div>

</div>
</div>

### DN\_SEP {#aac3b8854dead0ba7c6a9e83d49b7d945}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DN_SEP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 75 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aac3b8854dead0ba7c6a9e83d49b7d945">59</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DN_SEP</span></span></div>

</div>

</div>
</div>

### DN\_SEP {#aac3b8854dead0ba7c6a9e83d49b7d945}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DN_SEP&nbsp;&nbsp;&nbsp;,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 1418 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aac3b8854dead0ba7c6a9e83d49b7d945">59</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DN_SEP</span></span></div>

</div>

</div>
</div>

### DN\_SEP {#aac3b8854dead0ba7c6a9e83d49b7d945}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DN_SEP&nbsp;&nbsp;&nbsp;,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 1430 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aac3b8854dead0ba7c6a9e83d49b7d945">59</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DN_SEP</span></span></div>

</div>

</div>
</div>

### DN\_SEP {#aac3b8854dead0ba7c6a9e83d49b7d945}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DN_SEP&nbsp;&nbsp;&nbsp;,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 1436 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aac3b8854dead0ba7c6a9e83d49b7d945">59</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DN_SEP</span></span></div>

</div>

</div>
</div>

### DOC\_NODES {#a9a1f232ee7a2138f67140f80ce7c6628}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DOC_NODES&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">/*  0 */  <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docword">DocWord</a>)           <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/doclinkedword">DocLinkedWord</a>)    <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docurl">DocURL</a>)            <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/doclinebreak">DocLineBreak</a>)    <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/dochorruler">DocHorRuler</a>)    <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a>   \
/*  5 */  <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docanchor">DocAnchor</a>)         <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/doccite">DocCite</a>)          <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a>)    <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>)       <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docemoji">DocEmoji</a>)       <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a>   \
/* 10 */  <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docwhitespace">DocWhiteSpace</a>)     <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docseparator">DocSeparator</a>)     <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a>)       <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docinclude">DocInclude</a>)      <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docincoperator">DocIncOperator</a>) <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a>   \
/* 15 */  <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docformula">DocFormula</a>)        <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docindexentry">DocIndexEntry</a>)    <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docautolist">DocAutoList</a>)       <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docautolistitem">DocAutoListItem</a>) <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/doctitle">DocTitle</a>)       <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a>   \
/* 20 */  <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docxrefitem">DocXRefItem</a>)       <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docimage">DocImage</a>)         <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docdotfile">DocDotFile</a>)        <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docmscfile">DocMscFile</a>)      <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docdiafile">DocDiaFile</a>)     <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a>   \
/* 25 */  <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docvhdlflow">DocVhdlFlow</a>)       <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/doclink">DocLink</a>)          <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docref">DocRef</a>)            <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docinternalref">DocInternalRef</a>)  <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/dochref">DocHRef</a>)        <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a>   \
/* 30 */  <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/dochtmlheader">DocHtmlHeader</a>)     <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/dochtmldesctitle">DocHtmlDescTitle</a>) <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/dochtmldesclist">DocHtmlDescList</a>)   <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docsection">DocSection</a>)      <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docsecrefitem">DocSecRefItem</a>)  <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a>   \
/* 35 */  <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docsecreflist">DocSecRefList</a>)     <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docinternal">DocInternal</a>)      <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docparblock">DocParBlock</a>)       <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docsimplelist">DocSimpleList</a>)   <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/dochtmllist">DocHtmlList</a>)    <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a>   \
/* 40 */  <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docsimplesect">DocSimpleSect</a>)     <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docsimplesectsep">DocSimpleSectSep</a>) <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docparamsect">DocParamSect</a>)      <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docpara">DocPara</a>)         <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docparamlist">DocParamList</a>)   <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a>   \
/* 45 */  <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docsimplelistitem">DocSimpleListItem</a>) <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/dochtmllistitem">DocHtmlListItem</a>)  <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/dochtmldescdata">DocHtmlDescData</a>)   <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/dochtmlcell">DocHtmlCell</a>)     <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/dochtmlcaption">DocHtmlCaption</a>) <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a>   \
/* 50 */  <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/dochtmlrow">DocHtmlRow</a>)        <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/dochtmltable">DocHtmlTable</a>)     <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/dochtmlblockquote">DocHtmlBlockQuote</a>) <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/doctext">DocText</a>)         <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docroot">DocRoot</a>)        <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a>   \
/* 55 */  <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/dochtmldetails">DocHtmlDetails</a>)    <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/dochtmlsummary">DocHtmlSummary</a>)   <a href="#aac3b8854dead0ba7c6a9e83d49b7d945">DN_SEP</a> <a href="#a6de37e0933d92bb91fcdc1b70ef32e2b">DN</a>(<a href="/web-doxygen/docs/api/classes/docplantumlfile">DocPlantUmlFile</a>)                                                                      \
</div>
</dd>
</dl>

Definition at line 43 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9a1f232ee7a2138f67140f80ce7c6628">43</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DOC_NODES                                                                                                                                      \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*  0 */</span><span class="doxyHighlightPreprocessor">  DN(DocWord)           DN_SEP DN(DocLinkedWord)    DN_SEP DN(DocURL)            DN_SEP DN(DocLineBreak)    DN_SEP DN(DocHorRuler)    DN_SEP   \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*  5 */</span><span class="doxyHighlightPreprocessor">  DN(DocAnchor)         DN_SEP DN(DocCite)          DN_SEP DN(DocStyleChange)    DN_SEP DN(DocSymbol)       DN_SEP DN(DocEmoji)       DN_SEP   \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlightComment">/* 10 */</span><span class="doxyHighlightPreprocessor">  DN(DocWhiteSpace)     DN_SEP DN(DocSeparator)     DN_SEP DN(DocVerbatim)       DN_SEP DN(DocInclude)      DN_SEP DN(DocIncOperator) DN_SEP   \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlightComment">/* 15 */</span><span class="doxyHighlightPreprocessor">  DN(DocFormula)        DN_SEP DN(DocIndexEntry)    DN_SEP DN(DocAutoList)       DN_SEP DN(DocAutoListItem) DN_SEP DN(DocTitle)       DN_SEP   \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlightComment">/* 20 */</span><span class="doxyHighlightPreprocessor">  DN(DocXRefItem)       DN_SEP DN(DocImage)         DN_SEP DN(DocDotFile)        DN_SEP DN(DocMscFile)      DN_SEP DN(DocDiaFile)     DN_SEP   \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlightComment">/* 25 */</span><span class="doxyHighlightPreprocessor">  DN(DocVhdlFlow)       DN_SEP DN(DocLink)          DN_SEP DN(DocRef)            DN_SEP DN(DocInternalRef)  DN_SEP DN(DocHRef)        DN_SEP   \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlightComment">/* 30 */</span><span class="doxyHighlightPreprocessor">  DN(DocHtmlHeader)     DN_SEP DN(DocHtmlDescTitle) DN_SEP DN(DocHtmlDescList)   DN_SEP DN(DocSection)      DN_SEP DN(DocSecRefItem)  DN_SEP   \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlightComment">/* 35 */</span><span class="doxyHighlightPreprocessor">  DN(DocSecRefList)     DN_SEP DN(DocInternal)      DN_SEP DN(DocParBlock)       DN_SEP DN(DocSimpleList)   DN_SEP DN(DocHtmlList)    DN_SEP   \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlightComment">/* 40 */</span><span class="doxyHighlightPreprocessor">  DN(DocSimpleSect)     DN_SEP DN(DocSimpleSectSep) DN_SEP DN(DocParamSect)      DN_SEP DN(DocPara)         DN_SEP DN(DocParamList)   DN_SEP   \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlightComment">/* 45 */</span><span class="doxyHighlightPreprocessor">  DN(DocSimpleListItem) DN_SEP DN(DocHtmlListItem)  DN_SEP DN(DocHtmlDescData)   DN_SEP DN(DocHtmlCell)     DN_SEP DN(DocHtmlCaption) DN_SEP   \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlightComment">/* 50 */</span><span class="doxyHighlightPreprocessor">  DN(DocHtmlRow)        DN_SEP DN(DocHtmlTable)     DN_SEP DN(DocHtmlBlockQuote) DN_SEP DN(DocText)         DN_SEP DN(DocRoot)        DN_SEP   \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlightComment">/* 55 */</span><span class="doxyHighlightPreprocessor">  DN(DocHtmlDetails)    DN_SEP DN(DocHtmlSummary)   DN_SEP DN(DocPlantUmlFile)                                                                      \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span></div>

</div>


Referenced by <a href="#ad6c2b2b9786502bb407f7858cc1deef7">docNodeName</a>, <a href="#ae6d1fdb00451a93f990d0f6206157910">docNodeName</a> and <a href="#a0cee4ebd85699ca3a3e70eb19dc5a199">dumpDocNodeSizes</a>.
</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
