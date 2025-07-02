---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/namespaces/mappers
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - namespace
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `Mappers` Namespace Reference

Namespace for the doxygen and HTML command mappers. <a href="#details">More...</a>

## Definition

<div class="doxyDefinition">
namespace Mappers { ... }
</div>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/mapper">Mapper</a>&lt; <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352">CommandType</a> &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca1c1147352a87e1d896e0c4cf70b8c9">cmdMapper</a> = &amp;<a href="/web-doxygen/docs/api/files/src/cmdmapper-cpp/#aa088b30c3ac7640e4c8cfb125e4bd6e6">g_cmdMapper</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/mapper">Mapper</a>&lt; <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273">HtmlTagType</a> &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8390ce8e78c02d974d515d560a551958">htmlTagMapper</a> = &amp;<a href="/web-doxygen/docs/api/files/src/cmdmapper-cpp/#ad0bcba33ac06a2623c8bdaca5b36a7b2">g_htmlTagMapper</a></td>
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

## Description {#details}

Namespace for the doxygen and HTML command mappers.

<div class="doxySectionDef">

## Variables

### cmdMapper {#aca1c1147352a87e1d896e0c4cf70b8c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Mapper&lt; CommandType &gt; * Mappers::cmdMapper = &amp;<a href="/web-doxygen/docs/api/files/src/cmdmapper-cpp/#aa088b30c3ac7640e4c8cfb125e4bd6e6">g_cmdMapper</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 250 of file <a href="/web-doxygen/docs/api/files/src/cmdmapper-cpp">cmdmapper.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aca1c1147352a87e1d896e0c4cf70b8c9">250</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/mapper">Mapper&lt;CommandType&gt;</a> *<a href="#aca1c1147352a87e1d896e0c4cf70b8c9">cmdMapper</a>     = &amp;<a href="/web-doxygen/docs/api/files/src/cmdmapper-cpp/#aa088b30c3ac7640e4c8cfb125e4bd6e6">g_cmdMapper</a>;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/docparser/#ae88d59b299df415c0c2028d863288599">DocParser::defaultHandleTitleAndSize</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a105e51dc946d1daa2914afd2bc3e72af">DocParser::defaultHandleToken</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/classes/dochtmldesctitle/#a92b042aef732d7da8cc71182810e76c5">DocHtmlDescTitle::parse</a>, <a href="/web-doxygen/docs/api/classes/docindexentry/#a788ff313987522a9be055abe2fdb1592">DocIndexEntry::parse</a>, <a href="/web-doxygen/docs/api/classes/doclink/#aeb676914fb893fa31c99b39c1f7bb6d3">DocLink::parse</a>, <a href="/web-doxygen/docs/api/classes/docpara/#aafc94d2ed7856e4a11e404e2ee05fb40">DocPara::parse</a>, <a href="/web-doxygen/docs/api/classes/docsecreflist/#a9b279250711bb61d12bff4c34e70d2f3">DocSecRefList::parse</a> and <a href="/web-doxygen/docs/api/classes/doctext/#aada5a740aa0832964895e683340b76a5">DocText::parse</a>.
</div>
</div>

### htmlTagMapper {#a8390ce8e78c02d974d515d560a551958}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Mapper&lt; HtmlTagType &gt; * Mappers::htmlTagMapper = &amp;<a href="/web-doxygen/docs/api/files/src/cmdmapper-cpp/#ad0bcba33ac06a2623c8bdaca5b36a7b2">g_htmlTagMapper</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 251 of file <a href="/web-doxygen/docs/api/files/src/cmdmapper-cpp">cmdmapper.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8390ce8e78c02d974d515d560a551958">251</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/mapper">Mapper&lt;HtmlTagType&gt;</a> *<a href="#a8390ce8e78c02d974d515d560a551958">htmlTagMapper</a> = &amp;<a href="/web-doxygen/docs/api/files/src/cmdmapper-cpp/#ad0bcba33ac06a2623c8bdaca5b36a7b2">g_htmlTagMapper</a>;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/docparser/#a105e51dc946d1daa2914afd2bc3e72af">DocParser::defaultHandleToken</a>, <a href="/web-doxygen/docs/api/classes/docpara/#aef70041ddeb0e5767c66089ba24f0afe">DocPara::handleHtmlEndTag</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a>, <a href="/web-doxygen/docs/api/classes/docparser/#abf46a000544ae1a4f45df6430cd3e6bf">DocParser::handleStyleArgument</a>, <a href="/web-doxygen/docs/api/classes/dochref/#a2a9332a0da85f6e0596e3d46cea53fe5">DocHRef::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcaption/#a4f952166357e3d6d33312208d4a768f3">DocHtmlCaption::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#af23dec8c6549a7a73bb69037f5324c70">DocHtmlCell::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldesclist/#a74ff0b5b4a4173213a643d6897d7f9c2">DocHtmlDescList::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldesctitle/#a92b042aef732d7da8cc71182810e76c5">DocHtmlDescTitle::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlheader/#a5f57a370972a9ce3f7aa769973c5d2e8">DocHtmlHeader::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#ab8fc1655d43a50f996a8878eb66e0dc7">DocHtmlList::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#afbeab8f03e2ef431c05b8d3bcb6291aa">DocHtmlRow::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlsummary/#a4768457c4357b86443890d950cb3e740">DocHtmlSummary::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmltable/#a6f4ae9d09701b93305b6e90260bc5662">DocHtmlTable::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#a48640c52ba4009264ee01b0761663756">DocHtmlCell::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#a53b4acdb633ea0dea82a74cafd533e31">DocHtmlList::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#a10bb2141d4a0d7867a97d829794184e3">DocHtmlRow::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmltable/#a2a913b8204fc7637dea2f3783da7b1a2">DocHtmlTable::parseXml</a> and <a href="/web-doxygen/docs/api/classes/docparamlist/#a79bb36905dd1401288d55e12ee52ce03">DocParamList::parseXml</a>.
</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/cmdmapper-cpp">cmdmapper.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
