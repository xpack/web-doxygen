---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/dochtmlheader
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `DocHtmlHeader` Class Reference

Node Html heading. <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
class DocHtmlHeader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/docnode-h">src/docnode.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

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

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1a8b505940894456be60c6f666e4d38">DocHtmlHeader</a> (DocParser *parser, DocNodeVariant *parent, const HtmlAttribList &amp;attribs, int level)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8e82a4c504c1d6acd6838fa21404263">level</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76ed1632faa88a97329d28933b0b1e14">attribs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/token">Token</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f57a370972a9ce3f7aa769973c5d2e8">parse</a> ()</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a958ebf1eb7cb3246217520578494ba96">m_level</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6de0b9ce1b4f6e0ba6648f5ef5d8af90">m_attribs</a></td>
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

Node Html heading.

Definition at line 872 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxySectionDef">

## Public Constructors

### DocHtmlHeader() {#ac1a8b505940894456be60c6f666e4d38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocHtmlHeader::DocHtmlHeader (<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> * parser, <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, const <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> &amp; attribs, int level)</td>
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



Definition at line 875 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac1a8b505940894456be60c6f666e4d38">875</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ac1a8b505940894456be60c6f666e4d38">DocHtmlHeader</a>(<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> &amp;<a href="#a76ed1632faa88a97329d28933b0b1e14">attribs</a>,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#af8e82a4c504c1d6acd6838fa21404263">level</a>) :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">876</span><span class="doxyLineContent"><span class="doxyHighlight">       <a href="/web-doxygen/docs/api/classes/doccompoundnode/#ae01ca6994447efab51eb155728e4f3f6">DocCompoundNode</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>), <a href="#a958ebf1eb7cb3246217520578494ba96">m_level</a>(<a href="#af8e82a4c504c1d6acd6838fa21404263">level</a>), <a href="#a6de0b9ce1b4f6e0ba6648f5ef5d8af90">m_attribs</a>(<a href="#a76ed1632faa88a97329d28933b0b1e14">attribs</a>) {}</span></span></div>

</div>


References <a href="#a76ed1632faa88a97329d28933b0b1e14">attribs</a>, <a href="/web-doxygen/docs/api/classes/doccompoundnode/#ae01ca6994447efab51eb155728e4f3f6">DocCompoundNode::DocCompoundNode</a>, <a href="#af8e82a4c504c1d6acd6838fa21404263">level</a>, <a href="#a6de0b9ce1b4f6e0ba6648f5ef5d8af90">m\_attribs</a>, <a href="#a958ebf1eb7cb3246217520578494ba96">m\_level</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a> and <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### attribs() {#a76ed1632faa88a97329d28933b0b1e14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const HtmlAttribList &amp; DocHtmlHeader::attribs ()</td>
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



Definition at line 878 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a76ed1632faa88a97329d28933b0b1e14">878</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> &amp;<a href="#a76ed1632faa88a97329d28933b0b1e14">attribs</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a6de0b9ce1b4f6e0ba6648f5ef5d8af90">m_attribs</a>; }</span></span></div>

</div>


Reference <a href="#a6de0b9ce1b4f6e0ba6648f5ef5d8af90">m\_attribs</a>.

Referenced by <a href="#ac1a8b505940894456be60c6f666e4d38">DocHtmlHeader</a> and <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a4f71b7f0fd9236e38d92839fe07e9cb9">HtmlDocVisitor::operator()</a>.
</div>
</div>

### level() {#af8e82a4c504c1d6acd6838fa21404263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DocHtmlHeader::level ()</td>
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



Definition at line 877 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af8e82a4c504c1d6acd6838fa21404263">877</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#af8e82a4c504c1d6acd6838fa21404263">level</a>()</span><span class="doxyHighlightKeyword"> const                     </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a958ebf1eb7cb3246217520578494ba96">m_level</a>; }</span></span></div>

</div>


Reference <a href="#a958ebf1eb7cb3246217520578494ba96">m\_level</a>.

Referenced by <a href="#ac1a8b505940894456be60c6f666e4d38">DocHtmlHeader</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a4f71b7f0fd9236e38d92839fe07e9cb9">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a2f950e3e8499edfa159d43d35ebda0b0">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#aa515f7b48fa75a22c9e1173511e8cb88">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#afecf296ad3e703456c558f8ea957844d">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a699f603f3208cebae8295fe330963979">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#adae81723bf98cc11856ec916852cf089">RTFDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a73746a7f0fbddc7813a141f7700a72e5">XmlDocVisitor::operator()</a>.
</div>
</div>

### parse() {#a5f57a370972a9ce3f7aa769973c5d2e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Token DocHtmlHeader::parse ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 879 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line 1304 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5f57a370972a9ce3f7aa769973c5d2e8">1304</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/token">Token</a> <a href="#a5f57a370972a9ce3f7aa769973c5d2e8">DocHtmlHeader::parse</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1305</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1306</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1307</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/token">Token</a> retval(TokenRetval::RetVal_OK);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1308</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> ns = <a href="/web-doxygen/docs/api/classes/autonodestack">AutoNodeStack</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1309</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1310</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/token">Token</a> tok = <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#a286239d4401fbbfb8b183a7e9c521866">lex</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1311</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_NONE, TokenRetval::TK_EOF))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1312</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1313</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;defaultHandleToken(<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),tok,<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1314</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1315</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#ab0587c46b8e1a8e18f8416b3aad58342">value</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1316</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1317</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> TokenRetval::TK_HTMLTAG:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1318</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1319</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273">HtmlTagType</a> tagId=<a href="/web-doxygen/docs/api/namespaces/mappers/#a8390ce8e78c02d974d515d560a551958">Mappers::htmlTagMapper</a>-&gt;map(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1320</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tagId==<a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a479296801803f02038ab03da7c2ad166">HtmlTagType::HTML_H1</a> &amp;&amp; <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;endTag) </span><span class="doxyHighlightComment">// found &lt;/h1&gt; tag</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1321</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1322</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a958ebf1eb7cb3246217520578494ba96">m_level</a>!=1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1323</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1324</span><span class="doxyLineContent"><span class="doxyHighlight">                <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.fileName,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span><span class="doxyHighlightStringLiteral">"&lt;h{:d}&gt; ended with &lt;/h1&gt;"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1325</span><span class="doxyLineContent"><span class="doxyHighlight">                    <a href="#a958ebf1eb7cb3246217520578494ba96">m_level</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1326</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1327</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> endheader;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1328</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1329</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tagId==<a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a5d5d3cb1354c3eb5e716123d381e1cb6">HtmlTagType::HTML_H2</a> &amp;&amp; <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;endTag) </span><span class="doxyHighlightComment">// found &lt;/h2&gt; tag</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1330</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1331</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a958ebf1eb7cb3246217520578494ba96">m_level</a>!=2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1332</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1333</span><span class="doxyLineContent"><span class="doxyHighlight">                <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.fileName,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span><span class="doxyHighlightStringLiteral">"&lt;h{:d}&gt; ended with &lt;/h2&gt;"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1334</span><span class="doxyLineContent"><span class="doxyHighlight">                    <a href="#a958ebf1eb7cb3246217520578494ba96">m_level</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1335</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1336</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> endheader;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1337</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1338</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tagId==<a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273afc62db7b668b12b358f7a07fd1281b81">HtmlTagType::HTML_H3</a> &amp;&amp; <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;endTag) </span><span class="doxyHighlightComment">// found &lt;/h3&gt; tag</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1339</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1340</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a958ebf1eb7cb3246217520578494ba96">m_level</a>!=3)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1341</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1342</span><span class="doxyLineContent"><span class="doxyHighlight">                <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.fileName,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span><span class="doxyHighlightStringLiteral">"&lt;h{:d}&gt; ended with &lt;/h3&gt;"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1343</span><span class="doxyLineContent"><span class="doxyHighlight">                    <a href="#a958ebf1eb7cb3246217520578494ba96">m_level</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1344</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1345</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> endheader;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1346</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1347</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tagId==<a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a3a83d8472eedade5c9285898725b2ae4">HtmlTagType::HTML_H4</a> &amp;&amp; <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;endTag) </span><span class="doxyHighlightComment">// found &lt;/h4&gt; tag</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1348</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1349</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a958ebf1eb7cb3246217520578494ba96">m_level</a>!=4)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1350</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1351</span><span class="doxyLineContent"><span class="doxyHighlight">                <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.fileName,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span><span class="doxyHighlightStringLiteral">"&lt;h{:d}&gt; ended with &lt;/h4&gt;"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1352</span><span class="doxyLineContent"><span class="doxyHighlight">                    <a href="#a958ebf1eb7cb3246217520578494ba96">m_level</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1353</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1354</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> endheader;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1355</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1356</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tagId==<a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a9ccc9adc294e5d51752440d870151645">HtmlTagType::HTML_H5</a> &amp;&amp; <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;endTag) </span><span class="doxyHighlightComment">// found &lt;/h5&gt; tag</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1357</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1358</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a958ebf1eb7cb3246217520578494ba96">m_level</a>!=5)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1359</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1360</span><span class="doxyLineContent"><span class="doxyHighlight">                <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.fileName,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span><span class="doxyHighlightStringLiteral">"&lt;h{:d}&gt; ended with &lt;/h5&gt;"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1361</span><span class="doxyLineContent"><span class="doxyHighlight">                    <a href="#a958ebf1eb7cb3246217520578494ba96">m_level</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1362</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1363</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> endheader;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1364</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1365</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tagId==<a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a73dec4eca50d315e033ed391ed9f68c4">HtmlTagType::HTML_H6</a> &amp;&amp; <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;endTag) </span><span class="doxyHighlightComment">// found &lt;/h6&gt; tag</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1366</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1367</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a958ebf1eb7cb3246217520578494ba96">m_level</a>!=6)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1368</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1369</span><span class="doxyLineContent"><span class="doxyHighlight">                <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.fileName,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span><span class="doxyHighlightStringLiteral">"&lt;h{:d}&gt; ended with &lt;/h6&gt;"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1370</span><span class="doxyLineContent"><span class="doxyHighlight">                    <a href="#a958ebf1eb7cb3246217520578494ba96">m_level</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1371</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1372</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> endheader;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1373</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1374</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tagId==<a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273ad7f6725429a6b56d148761e9cb4e910a">HtmlTagType::HTML_A</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1375</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1376</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;endTag)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1377</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1378</span><span class="doxyLineContent"><span class="doxyHighlight">                <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a6a6c955c9001d67e4b722038bfc5f16b">handleAHref</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;attribs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1379</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1380</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1381</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tagId==<a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a4f8fb36a7660142ed004cb82a93438d8">HtmlTagType::HTML_BR</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1382</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1383</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/doclinebreak">DocLineBreak</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">token</a>-&gt;<a href="/web-doxygen/docs/api/structs/tokeninfo/#a811b08400dcdf6aa65b3fd3149b890c9">attribs</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1384</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1385</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1386</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1387</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.fileName,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span><span class="doxyHighlightStringLiteral">"Unexpected html tag &lt;{}{}&gt; found within &lt;h{:d}&gt; context"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1388</span><span class="doxyLineContent"><span class="doxyHighlight">                  <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;endTag?</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">:</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;name,<a href="#a958ebf1eb7cb3246217520578494ba96">m_level</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1389</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1390</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1391</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1392</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1393</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> tmp[20];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1394</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a307ffe8cbc4a4aa695900441d1df49f3">qsnprintf</a>(tmp,20,</span><span class="doxyHighlightStringLiteral">"&lt;h%d&gt; tag"</span><span class="doxyHighlight">,<a href="#a958ebf1eb7cb3246217520578494ba96">m_level</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1395</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#afa9541b35f25f2f63a6f5ff338967f22">errorHandleDefaultToken</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),tok,<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>(),tmp);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1396</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1397</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1398</span><span class="doxyLineContent"><span class="doxyHighlight">    tok = <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#a286239d4401fbbfb8b183a7e9c521866">lex</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1399</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1400</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_NONE,TokenRetval::TK_EOF))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1401</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1402</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.fileName,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span><span class="doxyHighlightStringLiteral">"Unexpected end of comment while inside"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1403</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightStringLiteral">" &lt;h{:d}&gt; tag"</span><span class="doxyHighlight">,<a href="#a958ebf1eb7cb3246217520578494ba96">m_level</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1404</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1405</span><span class="doxyLineContent"><span class="doxyHighlight">endheader:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1406</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a94f06b2f61c71069d46589a7cd4f7b6b">handlePendingStyleCommands</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1407</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> retval;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1408</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">DocNodeList::append</a>, <a href="/web-doxygen/docs/api/structs/tokeninfo/#a811b08400dcdf6aa65b3fd3149b890c9">TokenInfo::attribs</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">DocParser::context</a>, <a href="/web-doxygen/docs/api/classes/docparser/#afa9541b35f25f2f63a6f5ff338967f22">DocParser::errorHandleDefaultToken</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a6a6c955c9001d67e4b722038bfc5f16b">DocParser::handleAHref</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a94f06b2f61c71069d46589a7cd4f7b6b">DocParser::handlePendingStyleCommands</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273ad7f6725429a6b56d148761e9cb4e910a">HTML\_A</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a4f8fb36a7660142ed004cb82a93438d8">HTML\_BR</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a479296801803f02038ab03da7c2ad166">HTML\_H1</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a5d5d3cb1354c3eb5e716123d381e1cb6">HTML\_H2</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273afc62db7b668b12b358f7a07fd1281b81">HTML\_H3</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a3a83d8472eedade5c9285898725b2ae4">HTML\_H4</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a9ccc9adc294e5d51752440d870151645">HTML\_H5</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a73dec4eca50d315e033ed391ed9f68c4">HTML\_H6</a>, <a href="/web-doxygen/docs/api/namespaces/mappers/#a8390ce8e78c02d974d515d560a551958">Mappers::htmlTagMapper</a>, <a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">Token::is\_any\_of</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#a286239d4401fbbfb8b183a7e9c521866">DocTokenizer::lex</a>, <a href="#a958ebf1eb7cb3246217520578494ba96">m\_level</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a307ffe8cbc4a4aa695900441d1df49f3">qsnprintf</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">DocNode::thisVariant</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">DocParserContext::token</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">DocParser::tokenizer</a>, <a href="/web-doxygen/docs/api/classes/token/#ab0587c46b8e1a8e18f8416b3aad58342">Token::value</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn\_doc\_error</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_attribs {#a6de0b9ce1b4f6e0ba6648f5ef5d8af90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HtmlAttribList DocHtmlHeader::m_attribs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 883 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6de0b9ce1b4f6e0ba6648f5ef5d8af90">883</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> <a href="#a6de0b9ce1b4f6e0ba6648f5ef5d8af90">m_attribs</a>;</span></span></div>

</div>


Referenced by <a href="#a76ed1632faa88a97329d28933b0b1e14">attribs</a> and <a href="#ac1a8b505940894456be60c6f666e4d38">DocHtmlHeader</a>.
</div>
</div>

### m\_level {#a958ebf1eb7cb3246217520578494ba96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DocHtmlHeader::m_level = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 882 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a958ebf1eb7cb3246217520578494ba96">882</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">           <a href="#a958ebf1eb7cb3246217520578494ba96">m_level</a> = 0;</span></span></div>

</div>


Referenced by <a href="#ac1a8b505940894456be60c6f666e4d38">DocHtmlHeader</a>, <a href="#af8e82a4c504c1d6acd6838fa21404263">level</a> and <a href="#a5f57a370972a9ce3f7aa769973c5d2e8">parse</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
