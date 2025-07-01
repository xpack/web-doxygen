---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/docnodelist
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `DocNodeList` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct DocNodeList { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/docnode-h">src/docnode.h</a>&gt;
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/growvector">GrowVector&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
std::vector like container optimized for pushing elements to the back. <a href="/web-doxygen/docs/api/classes/growvector/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, class... Args&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a834769ebf2b990228c84981003d7659b">append</a> (Args &amp;&amp;... args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Append a new <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> to the list by constructing it with type T and parameters Args. <a href="#a834769ebf2b990228c84981003d7659b">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bb13c84c8ad84d77584f6a3ec24a2a9">move_append</a> (DocNodeList &amp;l)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
moves the element of list <em>l</em> at the end of this list. <a href="#a6bb13c84c8ad84d77584f6a3ec24a2a9">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae3a5d9b77d64e18e642163cceac5fa2e">get_last</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns a pointer to the last element in the list if that element exists and holds a T, otherwise nullptr is returned. <a href="#ae3a5d9b77d64e18e642163cceac5fa2e">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


Definition at line 118 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxySectionDef">

## Public Member Functions

### append() {#a834769ebf2b990228c84981003d7659b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class... Args&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocNodeList::append (Args &amp;&amp;... args)</td>
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

Append a new <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> to the list by constructing it with type T and parameters Args.

Definition at line 124 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a834769ebf2b990228c84981003d7659b">1399</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a834769ebf2b990228c84981003d7659b">DocNodeList::append</a>(Args&amp;&amp;... args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1400</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1401</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// add a DocNodeVariant to the list containing an node T as its active member.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1402</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/growvector/#a7a92b9894590a7470f2f9ebd2d7cda7b">emplace_back</a>(T(std::forward&lt;Args&gt;(args)...));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1403</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// store a pointer to the variant holding node T inside the node itself.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1404</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Since DocNodeList is a GrowVector this reference will remain valid even if new</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1405</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// elements are added (which would not be the case if a std::vector was used)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1406</span><span class="doxyLineContent"><span class="doxyHighlight">  std::get_if&lt;T&gt;(&amp;<a href="/web-doxygen/docs/api/classes/growvector/#a32ffacabb2c328729f4e6ead6d96a4ad">back</a>())-&gt;setThisVariant(&amp;<a href="/web-doxygen/docs/api/classes/growvector/#a32ffacabb2c328729f4e6ead6d96a4ad">back</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1407</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/growvector/#a32ffacabb2c328729f4e6ead6d96a4ad">GrowVector&lt; DocNodeVariant &gt;::back</a> and <a href="/web-doxygen/docs/api/classes/growvector/#a7a92b9894590a7470f2f9ebd2d7cda7b">GrowVector&lt; DocNodeVariant &gt;::emplace\_back</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docsimplesect/#ae538f74c2d44222c9a45ef304c89e041">DocSimpleSect::appendLinkWord</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a105e51dc946d1daa2914afd2bc3e72af">DocParser::defaultHandleToken</a>, <a href="/web-doxygen/docs/api/classes/docparser/#afa9541b35f25f2f63a6f5ff338967f22">DocParser::errorHandleDefaultToken</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a6a6c955c9001d67e4b722038bfc5f16b">DocParser::handleAHref</a>, <a href="/web-doxygen/docs/api/classes/docparser/#adf24a6cf025048b8a3235ca2c897dc06">DocParser::handleAnchor</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a10a22fde1124375bf9f58cbea8eadf84">DocPara::handleCite</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a22c8bd336d14e9baf38a3ffcec3d0476">DocPara::handleDoxyConfig</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a724e489c954b750341d697b29e98033f">DocPara::handleEmoji</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a2c5971c7bbbb5bd01e02ac7d93600281">DocPara::handleFile</a>, <a href="/web-doxygen/docs/api/classes/docpara/#aef70041ddeb0e5767c66089ba24f0afe">DocPara::handleHtmlEndTag</a>, <a href="/web-doxygen/docs/api/classes/docpara/#ac2433e9fbc80306d6ae28ff94a019068">DocPara::handleHtmlHeader</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a>, <a href="/web-doxygen/docs/api/classes/docparser/#aa923af2c2ca8d81fa9b65a6fa1e65a83">DocParser::handleImage</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ae3321ce556544cc7281b783f2b250be4">DocParser::handleImg</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1bb9289a32b8c06de83c728786bb0669">DocPara::handleInclude</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a7c235343a063e005bfee6c68b14a835e">DocPara::handleIncludeOperator</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a334b7286f0a4445d85743cce35a3c090">DocParser::handleInternalRef</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a0bff680b96bc9c76b2228affeaa90bbb">DocPara::handleLink</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a2b2971ad53e50d90ca4affca6a6e1d67">DocParser::handleLinkedWord</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a367fe5ccd7e0378c2e5c94df6e60dd0d">DocParser::handleParameterType</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a474887b8878a41eb2abf8ab378b6e847">DocPara::handleParamSection</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a94f06b2f61c71069d46589a7cd4f7b6b">DocParser::handlePendingStyleCommands</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a8541b3718d4e34888ecfcfc218f5c331">DocPara::handleRef</a>, <a href="/web-doxygen/docs/api/classes/docpara/#ad112877bd5902d918781a9f2d5e0f703">DocPara::handleShowDate</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a04534e1c41f2c421346fb9f313e2b737">DocPara::handleSimpleSection</a>, <a href="/web-doxygen/docs/api/classes/docpara/#af621e2f0d576fff189b3d94552edec15">DocPara::handleStartCode</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ab004ed65c6ab11f6ca2a4caee610bb49">DocParser::handleStyleEnter</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a92d044475f815e09877c88ce15399802">DocParser::handleStyleLeave</a>, <a href="/web-doxygen/docs/api/classes/docpara/#ab5639797f3123c08c83f16819f7a74d7">DocPara::handleVhdlFlow</a>, <a href="/web-doxygen/docs/api/classes/docpara/#ae14027652a29ff9eda818d4ba6098329">DocPara::handleXRefItem</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a6d276e7995db319294ea1fb2bc76459e">DocParser::internalValidatingParseDoc</a>, <a href="/web-doxygen/docs/api/classes/docautolist/#a8eef0f06619e7a80df0c5dd10e83cb2b">DocAutoList::parse</a>, <a href="/web-doxygen/docs/api/classes/docautolistitem/#a88f642289a7ff2d625c726cc4777b989">DocAutoListItem::parse</a>, <a href="/web-doxygen/docs/api/classes/dochref/#a2a9332a0da85f6e0596e3d46cea53fe5">DocHRef::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlblockquote/#aa64ab14e969b672324338c1be6b607e1">DocHtmlBlockQuote::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#af23dec8c6549a7a73bb69037f5324c70">DocHtmlCell::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldescdata/#ab176f44cd7bc955df0c352bd714e4e1c">DocHtmlDescData::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldesclist/#a74ff0b5b4a4173213a643d6897d7f9c2">DocHtmlDescList::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldesctitle/#a92b042aef732d7da8cc71182810e76c5">DocHtmlDescTitle::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldetails/#a12b425f8cc20de1ed4183ea8a9a454f8">DocHtmlDetails::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlheader/#a5f57a370972a9ce3f7aa769973c5d2e8">DocHtmlHeader::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#ab8fc1655d43a50f996a8878eb66e0dc7">DocHtmlList::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmllistitem/#a7c0ac2e655d8a3cf7deb76cdd23e95e5">DocHtmlListItem::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#afbeab8f03e2ef431c05b8d3bcb6291aa">DocHtmlRow::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmltable/#a6f4ae9d09701b93305b6e90260bc5662">DocHtmlTable::parse</a>, <a href="/web-doxygen/docs/api/classes/docinternal/#ad783a8507dd1e64ad38a889d9fa7a851">DocInternal::parse</a>, <a href="/web-doxygen/docs/api/classes/doclink/#aeb676914fb893fa31c99b39c1f7bb6d3">DocLink::parse</a>, <a href="/web-doxygen/docs/api/classes/docpara/#aafc94d2ed7856e4a11e404e2ee05fb40">DocPara::parse</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#ab528e49d6e133ca42c29bb46bdc3cbec">DocParamSect::parse</a>, <a href="/web-doxygen/docs/api/classes/docparblock/#aa0283029f3578c44cd54c93d648bd909">DocParBlock::parse</a>, <a href="/web-doxygen/docs/api/classes/docroot/#a860207dd6bee34648ddbfd55e3ddaff8">DocRoot::parse</a>, <a href="/web-doxygen/docs/api/classes/docsecreflist/#a9b279250711bb61d12bff4c34e70d2f3">DocSecRefList::parse</a>, <a href="/web-doxygen/docs/api/classes/docsection/#a9b6c66c2f51de17bc5748754090c1e41">DocSection::parse</a>, <a href="/web-doxygen/docs/api/classes/docsimplelist/#a915a61640051b31d2252ae075b9c220e">DocSimpleList::parse</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3e4b28664b6fe921f89c934f9d2f4ba0">DocSimpleSect::parse</a>, <a href="/web-doxygen/docs/api/classes/doctext/#aada5a740aa0832964895e683340b76a5">DocText::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#a48640c52ba4009264ee01b0761663756">DocHtmlCell::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#a53b4acdb633ea0dea82a74cafd533e31">DocHtmlList::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmllistitem/#ae1c82a584506da65bd320d481f774854">DocHtmlListItem::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#a10bb2141d4a0d7867a97d829794184e3">DocHtmlRow::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmltable/#a2a913b8204fc7637dea2f3783da7b1a2">DocHtmlTable::parseXml</a> and <a href="/web-doxygen/docs/api/classes/docsimplesect/#ae33bb7d70b15676b9244be8de396edc0">DocSimpleSect::parseXml</a>.
</div>
</div>

### get\_last() {#ae3a5d9b77d64e18e642163cceac5fa2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * DocNodeList::get_last ()</td>
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

Returns a pointer to the last element in the list if that element exists and holds a T, otherwise nullptr is returned.

Definition at line 134 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae3a5d9b77d64e18e642163cceac5fa2e">1410</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> T *<a href="#ae3a5d9b77d64e18e642163cceac5fa2e">DocNodeList::get_last</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1411</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1412</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::get_if&lt;T&gt;(&amp;<a href="/web-doxygen/docs/api/classes/growvector/#a32ffacabb2c328729f4e6ead6d96a4ad">back</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1413</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/growvector/#a32ffacabb2c328729f4e6ead6d96a4ad">GrowVector&lt; DocNodeVariant &gt;::back</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docsimplesect/#ae538f74c2d44222c9a45ef304c89e041">DocSimpleSect::appendLinkWord</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a6a6c955c9001d67e4b722038bfc5f16b">DocParser::handleAHref</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a2c5971c7bbbb5bd01e02ac7d93600281">DocPara::handleFile</a>, <a href="/web-doxygen/docs/api/classes/docpara/#ac2433e9fbc80306d6ae28ff94a019068">DocPara::handleHtmlHeader</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a>, <a href="/web-doxygen/docs/api/classes/docparser/#aa923af2c2ca8d81fa9b65a6fa1e65a83">DocParser::handleImage</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1bb9289a32b8c06de83c728786bb0669">DocPara::handleInclude</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a7c235343a063e005bfee6c68b14a835e">DocPara::handleIncludeOperator</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a334b7286f0a4445d85743cce35a3c090">DocParser::handleInternalRef</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a0bff680b96bc9c76b2228affeaa90bbb">DocPara::handleLink</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a474887b8878a41eb2abf8ab378b6e847">DocPara::handleParamSection</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a8541b3718d4e34888ecfcfc218f5c331">DocPara::handleRef</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a04534e1c41f2c421346fb9f313e2b737">DocPara::handleSimpleSection</a>, <a href="/web-doxygen/docs/api/classes/docpara/#ab5639797f3123c08c83f16819f7a74d7">DocPara::handleVhdlFlow</a>, <a href="/web-doxygen/docs/api/classes/docpara/#ae14027652a29ff9eda818d4ba6098329">DocPara::handleXRefItem</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a6d276e7995db319294ea1fb2bc76459e">DocParser::internalValidatingParseDoc</a>, <a href="/web-doxygen/docs/api/classes/docautolist/#a8eef0f06619e7a80df0c5dd10e83cb2b">DocAutoList::parse</a>, <a href="/web-doxygen/docs/api/classes/docautolistitem/#a88f642289a7ff2d625c726cc4777b989">DocAutoListItem::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlblockquote/#aa64ab14e969b672324338c1be6b607e1">DocHtmlBlockQuote::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#af23dec8c6549a7a73bb69037f5324c70">DocHtmlCell::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldescdata/#ab176f44cd7bc955df0c352bd714e4e1c">DocHtmlDescData::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldesclist/#a74ff0b5b4a4173213a643d6897d7f9c2">DocHtmlDescList::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldesctitle/#a92b042aef732d7da8cc71182810e76c5">DocHtmlDescTitle::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldetails/#a12b425f8cc20de1ed4183ea8a9a454f8">DocHtmlDetails::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#ab8fc1655d43a50f996a8878eb66e0dc7">DocHtmlList::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmllistitem/#a7c0ac2e655d8a3cf7deb76cdd23e95e5">DocHtmlListItem::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#afbeab8f03e2ef431c05b8d3bcb6291aa">DocHtmlRow::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmltable/#a6f4ae9d09701b93305b6e90260bc5662">DocHtmlTable::parse</a>, <a href="/web-doxygen/docs/api/classes/docinternal/#ad783a8507dd1e64ad38a889d9fa7a851">DocInternal::parse</a>, <a href="/web-doxygen/docs/api/classes/docpara/#aafc94d2ed7856e4a11e404e2ee05fb40">DocPara::parse</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#ab528e49d6e133ca42c29bb46bdc3cbec">DocParamSect::parse</a>, <a href="/web-doxygen/docs/api/classes/docparblock/#aa0283029f3578c44cd54c93d648bd909">DocParBlock::parse</a>, <a href="/web-doxygen/docs/api/classes/docroot/#a860207dd6bee34648ddbfd55e3ddaff8">DocRoot::parse</a>, <a href="/web-doxygen/docs/api/classes/docsecreflist/#a9b279250711bb61d12bff4c34e70d2f3">DocSecRefList::parse</a>, <a href="/web-doxygen/docs/api/classes/docsection/#a9b6c66c2f51de17bc5748754090c1e41">DocSection::parse</a>, <a href="/web-doxygen/docs/api/classes/docsimplelist/#a915a61640051b31d2252ae075b9c220e">DocSimpleList::parse</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3e4b28664b6fe921f89c934f9d2f4ba0">DocSimpleSect::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#a48640c52ba4009264ee01b0761663756">DocHtmlCell::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#a53b4acdb633ea0dea82a74cafd533e31">DocHtmlList::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmllistitem/#ae1c82a584506da65bd320d481f774854">DocHtmlListItem::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#a10bb2141d4a0d7867a97d829794184e3">DocHtmlRow::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmltable/#a2a913b8204fc7637dea2f3783da7b1a2">DocHtmlTable::parseXml</a> and <a href="/web-doxygen/docs/api/classes/docsimplesect/#ae33bb7d70b15676b9244be8de396edc0">DocSimpleSect::parseXml</a>.
</div>
</div>

### move\_append() {#a6bb13c84c8ad84d77584f6a3ec24a2a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocNodeList::move_append (<a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp; l)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

moves the element of list <em>l</em> at the end of this list.


List <em>l</em> will become empty.

Declaration at line 128 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line 816 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6bb13c84c8ad84d77584f6a3ec24a2a9">816</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6bb13c84c8ad84d77584f6a3ec24a2a9">DocNodeList::move_append</a>(<a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;elements)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">817</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">818</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;&amp;elem : elements)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">819</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">820</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/growvector/#a7a92b9894590a7470f2f9ebd2d7cda7b">emplace_back</a>(std::move(elem));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">821</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">822</span><span class="doxyLineContent"><span class="doxyHighlight">  elements.<a href="/web-doxygen/docs/api/classes/growvector/#a198715b8f95bc34cb020ae11170470f7">clear</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">823</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/growvector/#a198715b8f95bc34cb020ae11170470f7">GrowVector&lt; T &gt;::clear</a> and <a href="/web-doxygen/docs/api/classes/growvector/#a7a92b9894590a7470f2f9ebd2d7cda7b">GrowVector&lt; DocNodeVariant &gt;::emplace\_back</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a71dd66dcbef8ad6aa74feb1e87e2a06b">flattenParagraphs</a>.
</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
