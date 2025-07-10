---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/docparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DocParser` Class Reference



## Declaration

<div class="doxyDeclaration">
class DocParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/docparser-p-h">src/docparser_p.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/idocparser">IDocParser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>opaque parser interface <a href="/web-doxygen/docs/api/classes/idocparser/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af278dab51b58124b32a625d709a29d97">pushContext</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa05ab8dc59dfa50633146bdba08db5f0">popContext</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3321ce556544cc7281b783f2b250be4">handleImg</a> (DocNodeVariant *parent, DocNodeList &amp;children, const HtmlAttribList &amp;tagHtmlAttribs)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d276e7995db319294ea1fb2bc76459e">internalValidatingParseDoc</a> (DocNodeVariant *parent, DocNodeList &amp;children, const QCString &amp;doc)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b7d1c2724099f28c4f3a4c56c52d912">processCopyDoc</a> (const char *data, size_t &amp;len)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d46e03d176edeb9ec7044f80ffe3a81">findAndCopyImage</a> (const QCString &amp;fileName, DocImage::Type type, bool doWarn=true)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad426893f12b2bc919bc61b3d95e8f471">checkArgumentName</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fce1509c4bb1494537fe53ea294fa8c">checkRetvalName</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ca6efdbb8e10b7908ad6906f26ff1bd">checkUnOrMultipleDocumentedParams</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa75d3dc0424c6b364222f7f357406e62">findDocsForMemberOrCompound</a> (const QCString &amp;commandName, QCString *pDoc, QCString *pBrief, const Definition **pDef)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a105e51dc946d1daa2914afd2bc3e72af">defaultHandleToken</a> (DocNodeVariant *parent, Token tok, DocNodeList &amp;children, bool handleWord=TRUE)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa9541b35f25f2f63a6f5ff338967f22">errorHandleDefaultToken</a> (DocNodeVariant *parent, Token tok, DocNodeList &amp;children, const QCString &amp;txt)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae88d59b299df415c0c2028d863288599">defaultHandleTitleAndSize</a> (const CommandType cmd, DocNodeVariant *parent, DocNodeList &amp;children, QCString &amp;width, QCString &amp;height)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf46a000544ae1a4f45df6430cd3e6bf">handleStyleArgument</a> (DocNodeVariant *parent, DocNodeList &amp;children, const QCString &amp;cmdName)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab004ed65c6ab11f6ca2a4caee610bb49">handleStyleEnter</a> (DocNodeVariant *parent, DocNodeList &amp;children, DocStyleChange::Style s, const QCString &amp;tagName, const HtmlAttribList *attribs)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92d044475f815e09877c88ce15399802">handleStyleLeave</a> (DocNodeVariant *parent, DocNodeList &amp;children, DocStyleChange::Style s, const QCString &amp;tagName)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94f06b2f61c71069d46589a7cd4f7b6b">handlePendingStyleCommands</a> (DocNodeVariant *parent, DocNodeList &amp;children)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cbce284509ccf3109aa71472842ce4e">handleInitialStyleCommands</a> (DocNodeVariant *parent, DocNodeList &amp;children)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a6c955c9001d67e4b722038bfc5f16b">handleAHref</a> (DocNodeVariant *parent, DocNodeList &amp;children, const HtmlAttribList &amp;tagHtmlAttribs)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af097a0f67abbe29e09a9956e88eb7642">handleUnclosedStyleCommands</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b2971ad53e50d90ca4affca6a6e1d67">handleLinkedWord</a> (DocNodeVariant *parent, DocNodeList &amp;children, bool ignoreAutoLinkFlag=FALSE)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a367fe5ccd7e0378c2e5c94df6e60dd0d">handleParameterType</a> (DocNodeVariant *parent, DocNodeList &amp;children, const QCString &amp;paramTypes)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a334b7286f0a4445d85743cce35a3c090">handleInternalRef</a> (DocNodeVariant *parent, DocNodeList &amp;children)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf24a6cf025048b8a3235ca2c897dc06">handleAnchor</a> (DocNodeVariant *parent, DocNodeList &amp;children)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8ac10aa71d5d6c021a6e2f08df318f8">handlePrefix</a> (DocNodeVariant *parent, DocNodeList &amp;children)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa923af2c2ca8d81fa9b65a6fa1e65a83">handleImage</a> (DocNodeVariant *parent, DocNodeList &amp;children)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5340de5ad1c86c5c2d03b02e721b51e0">readTextFileByName</a> (const QCString &amp;file, QCString &amp;text)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::stack&lt; <a href="/web-doxygen/docs/api/structs/docparsercontext">DocParserContext</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15a2a88e43e50fa4d28b5675c97ec137">contextStack</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/docparsercontext">DocParserContext</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6738a87a82c364cedd836a084394960">context</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/doctokenizer">DocTokenizer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a></td>
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


<p>Definition at line 98 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### checkArgumentName() {#ad426893f12b2bc919bc61b3d95e8f471}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocParser::checkArgumentName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Collects the parameters found with @param command in a list context.paramsFound. If the parameter is not an actual parameter of the current member context.memberDef, then a warning is raised (unless warnings are disabled altogether).</p>


<p>Declaration at line 108 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>, definition at line 208 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad426893f12b2bc919bc61b3d95e8f471">208</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad426893f12b2bc919bc61b3d95e8f471">DocParser::checkArgumentName</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!(<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(WARN_IF_DOC_ERROR) || <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(WARN_IF_INCOMPLETE_DOC))) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// not a member</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string name = <a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name.str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;al=<a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;isDocsForDefinition() ?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">                         <a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;argumentList() :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">                         <a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;declArgumentList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang      = <a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;getLanguage();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("isDocsForDefinition()=%d\n",context.memberDef-&gt;isDocsForDefinition());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (al.<a href="/web-doxygen/docs/api/classes/argumentlist/#aaa15ddcfdb06a535a3398f1dc73d336d">empty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// no argument list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> re(R</span><span class="doxyHighlightStringLiteral">"(\$?\w+\.*)");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">  <a href="/web-doxygen/docs/api/classes/reg/iterator">reg::Iterator</a> it(name,re);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">  <a href="/web-doxygen/docs/api/classes/reg/iterator">reg::Iterator</a> <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (; it!=<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a> ; ++it)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;match = *it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> aName=match.str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lang==SrcLangExt::Fortran) aName=aName.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("aName='%s'\n",qPrint(aName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> found=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;a : al)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> argName = <a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;isDefine() ? a.type : a.name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lang==SrcLangExt::Fortran) argName=argName.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">      argName=argName.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("argName='%s' aName=%s\n",qPrint(argName),qPrint(aName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (argName.<a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">endsWith</a>(</span><span class="doxyHighlightStringLiteral">"..."</span><span class="doxyHighlight">)) argName=argName.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(argName.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-3);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (aName==argName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad6738a87a82c364cedd836a084394960">context</a>.paramsFound.insert(aName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">        found=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!found)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("member type=%d\n",context.memberDef-&gt;memberType());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> scope=<a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;getScopeString();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!scope.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) scope+=</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> scope=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> inheritedFrom = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> docFile = <a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;docFile();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> docLine = <a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;docLine();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *inheritedMd = <a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;inheritsDocsFrom();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (inheritedMd) </span><span class="doxyHighlightComment">// documentation was inherited</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">        inheritedFrom.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">" inherited from member %s at line "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightStringLiteral">"%d in file %s"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(inheritedMd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>()),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">            inheritedMd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a26a4a6e3578aa6c81b2d6d77a1ce694f">docLine</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(inheritedMd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a00915f52f3b708bec07aab2b44f03d34">docFile</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">        docFile = <a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;getDefFileName();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">        docLine = <a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;getDefLine();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> alStr = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9d5c2a3aefbda0b0e684f768a380d2db">argListToString</a>(al);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(docFile,docLine,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"argument '{}' of command @param "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"is not found in the argument list of {}{}{}{}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">          aName, scope, <a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;name(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">          alStr, inheritedFrom);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9d5c2a3aefbda0b0e684f768a380d2db">argListToString</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="#ad6738a87a82c364cedd836a084394960">context</a>, <a href="/web-doxygen/docs/api/classes/definition/#a00915f52f3b708bec07aab2b44f03d34">Definition::docFile</a>, <a href="/web-doxygen/docs/api/classes/definition/#a26a4a6e3578aa6c81b2d6d77a1ce694f">Definition::docLine</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#aaa15ddcfdb06a535a3398f1dc73d336d">ArgumentList::empty</a>, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">QCString::endsWith</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">QCString::sprintf</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docparamlist/#a98345755b6311bcc4129bd7ee14759f1">DocParamList::parse</a> and <a href="/web-doxygen/docs/api/classes/docparamlist/#a79bb36905dd1401288d55e12ee52ce03">DocParamList::parseXml</a>.</p>

</div>
</div>

### checkRetvalName() {#a3fce1509c4bb1494537fe53ea294fa8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocParser::checkRetvalName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Collects the return values found with @retval command in a global list g_parserContext.retvalsFound.</p>


<p>Declaration at line 109 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>, definition at line 273 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3fce1509c4bb1494537fe53ea294fa8c">273</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3fce1509c4bb1494537fe53ea294fa8c">DocParser::checkRetvalName</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name = <a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(WARN_IF_DOC_ERROR)) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> || name.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// not a member or no valid name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ad6738a87a82c364cedd836a084394960">context</a>.retvalsFound.count(name.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>())==1) </span><span class="doxyHighlightComment">// only report the first double entry</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">     <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;getDefFileName(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">                    <a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;getDefLine(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">                    </span><span class="doxyHighlightStringLiteral">"return value '{}' of {} has multiple documentation sections"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">                    name, <a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;qualifiedName());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad6738a87a82c364cedd836a084394960">context</a>.retvalsFound.insert(name.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="#ad6738a87a82c364cedd836a084394960">context</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docparamlist/#a98345755b6311bcc4129bd7ee14759f1">DocParamList::parse</a> and <a href="/web-doxygen/docs/api/classes/docparamlist/#a79bb36905dd1401288d55e12ee52ce03">DocParamList::parseXml</a>.</p>

</div>
</div>

### checkUnOrMultipleDocumentedParams() {#a9ca6efdbb8e10b7908ad6906f26ff1bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocParser::checkUnOrMultipleDocumentedParams ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Checks if the parameters that have been specified using @param are indeed all parameters and that a parameter does not have multiple @param blocks. Must be called after <a href="#ad426893f12b2bc919bc61b3d95e8f471">checkArgumentName()</a> has been called for each argument.</p>


<p>Declaration at line 110 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>, definition at line 294 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9ca6efdbb8e10b7908ad6906f26ff1bd">294</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9ca6efdbb8e10b7908ad6906f26ff1bd">DocParser::checkUnOrMultipleDocumentedParams</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef &amp;&amp; <a href="#ad6738a87a82c364cedd836a084394960">context</a>.hasParamCommand)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;al=<a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;isDocsForDefinition() ?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;argumentList() :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;declArgumentList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang = <a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;getLanguage();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!al.<a href="/web-doxygen/docs/api/classes/argumentlist/#aaa15ddcfdb06a535a3398f1dc73d336d">empty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> undocParams;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;a: al)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> argName = <a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;isDefine() ? a.type : a.name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lang==SrcLangExt::Fortran) argName = argName.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">        argName=argName.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> aName = argName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (argName.<a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">endsWith</a>(</span><span class="doxyHighlightStringLiteral">"..."</span><span class="doxyHighlight">)) argName=argName.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(argName.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-3);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lang==SrcLangExt::Python &amp;&amp; (argName==</span><span class="doxyHighlightStringLiteral">"self"</span><span class="doxyHighlight"> || argName==</span><span class="doxyHighlightStringLiteral">"cls"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// allow undocumented self / cls parameter for Python</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lang==SrcLangExt::Cpp &amp;&amp; (a.type==</span><span class="doxyHighlightStringLiteral">"this"</span><span class="doxyHighlight"> || a.type.startsWith(</span><span class="doxyHighlightStringLiteral">"this "</span><span class="doxyHighlight">)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// allow undocumented this (for C++23 deducing this), see issue #11123</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!argName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> count = <a href="#ad6738a87a82c364cedd836a084394960">context</a>.paramsFound.count(argName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (count==0 &amp;&amp; a.docs.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">            undocParams.<a href="/web-doxygen/docs/api/classes/argumentlist/#aa80c14f74871d9274671a9e33ac3c870">push_back</a>(a);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (count&gt;1 &amp;&amp; <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(WARN_IF_DOC_ERROR))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;docFile(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">                           <a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;docLine(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">                           </span><span class="doxyHighlightStringLiteral">"argument {} from the argument list of {} has multiple @param documentation sections"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">                           aName, <a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;qualifiedName());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!undocParams.<a href="/web-doxygen/docs/api/classes/argumentlist/#aaa15ddcfdb06a535a3398f1dc73d336d">empty</a>() &amp;&amp; <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(WARN_IF_INCOMPLETE_DOC))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> first=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> errMsg = </span><span class="doxyHighlightStringLiteral">"The following parameter"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (undocParams.<a href="/web-doxygen/docs/api/classes/argumentlist/#a4d651caeb995400fad17d4ab4a020a3a">size</a>()&gt;1) errMsg+=</span><span class="doxyHighlightStringLiteral">"s"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">        errMsg+=</span><span class="doxyHighlightStringLiteral">" of "</span><span class="doxyHighlight">+</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;qualifiedName()) +</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(<a href="/web-doxygen/docs/api/files/src/util-cpp/#a9d5c2a3aefbda0b0e684f768a380d2db">argListToString</a>(al)) +</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">            (undocParams.<a href="/web-doxygen/docs/api/classes/argumentlist/#a4d651caeb995400fad17d4ab4a020a3a">size</a>()&gt;1 ? </span><span class="doxyHighlightStringLiteral">" are"</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">" is"</span><span class="doxyHighlight">) + </span><span class="doxyHighlightStringLiteral">" not documented:\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;a : undocParams)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">347</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> argName = <a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;isDefine() ? a.type : a.name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lang==SrcLangExt::Fortran) argName = argName.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlight">          argName=argName.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!first) errMsg+=</span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">351</span><span class="doxyLineContent"><span class="doxyHighlight">          first=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">          errMsg+=</span><span class="doxyHighlightStringLiteral">"  parameter '"</span><span class="doxyHighlight">+argName+</span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#a8020989d06b5ab1656c968885ae22486">warn_incomplete_doc</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;docFile(), <a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;docLine(), </span><span class="doxyHighlightStringLiteral">"{}"</span><span class="doxyHighlight">, errMsg);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">355</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">356</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ad6738a87a82c364cedd836a084394960">context</a>.paramsFound.empty() &amp;&amp; <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(WARN_IF_DOC_ERROR))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">361</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;docFile(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;docLine(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightStringLiteral">"{} has @param documentation sections but no arguments"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;qualifiedName());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">366</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">367</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9d5c2a3aefbda0b0e684f768a380d2db">argListToString</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="#ad6738a87a82c364cedd836a084394960">context</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#aaa15ddcfdb06a535a3398f1dc73d336d">ArgumentList::empty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">QCString::endsWith</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#aa80c14f74871d9274671a9e33ac3c870">ArgumentList::push_back</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#a4d651caeb995400fad17d4ab4a020a3a">ArgumentList::size</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a8020989d06b5ab1656c968885ae22486">warn_incomplete_doc</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>.</p>

</div>
</div>

### defaultHandleTitleAndSize() {#ae88d59b299df415c0c2028d863288599}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocParser::defaultHandleTitleAndSize (const <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352">CommandType</a> cmd, <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp; children, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; width, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; height)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 120 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>, definition at line 1006 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae88d59b299df415c0c2028d863288599">1006</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae88d59b299df415c0c2028d863288599">DocParser::defaultHandleTitleAndSize</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352">CommandType</a> cmd, <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>, <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;children, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;width,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;height)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1007</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1008</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1009</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> ns = <a href="/web-doxygen/docs/api/classes/autonodestack">AutoNodeStack</a>(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1010</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1011</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// parse title</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1012</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStateTitle();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1013</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/token">Token</a> tok = <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.lex();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1014</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_NONE,TokenRetval::TK_EOF))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1015</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1016</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_WORD) &amp;&amp; (<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name==</span><span class="doxyHighlightStringLiteral">"width="</span><span class="doxyHighlight"> || <a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name==</span><span class="doxyHighlightStringLiteral">"height="</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1017</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1018</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// special case: no title, but we do have a size indicator</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1019</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1020</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1021</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_HTMLTAG))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1022</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1023</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.unputString(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;text);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1024</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1025</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1026</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a105e51dc946d1daa2914afd2bc3e72af">defaultHandleToken</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,tok,children))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1027</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1028</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#afa9541b35f25f2f63a6f5ff338967f22">errorHandleDefaultToken</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,tok,children,<a href="/web-doxygen/docs/api/namespaces/mappers/#aca1c1147352a87e1d896e0c4cf70b8c9">Mappers::cmdMapper</a>-&gt;find(cmd));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1029</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1030</span><span class="doxyLineContent"><span class="doxyHighlight">    tok = <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.lex();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1031</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1032</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// parse size attributes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1033</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_NONE,TokenRetval::TK_EOF))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1034</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1035</span><span class="doxyLineContent"><span class="doxyHighlight">    tok=<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.lex();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1036</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1037</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_WHITESPACE,TokenRetval::TK_WORD,TokenRetval::TK_HTMLTAG)) </span><span class="doxyHighlightComment">// there are values following the title</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1038</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1039</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_WORD))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1040</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1041</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name==</span><span class="doxyHighlightStringLiteral">"width="</span><span class="doxyHighlight"> || <a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name==</span><span class="doxyHighlightStringLiteral">"height="</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1042</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1043</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStateTitleAttrValue();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1044</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name = <a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name.left(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name.length()-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1045</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1046</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1047</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name==</span><span class="doxyHighlightStringLiteral">"width"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1048</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1049</span><span class="doxyLineContent"><span class="doxyHighlight">        width = <a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;chars;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1050</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1051</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name==</span><span class="doxyHighlightStringLiteral">"height"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1052</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1053</span><span class="doxyLineContent"><span class="doxyHighlight">        height = <a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;chars;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1054</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1055</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// other text after the title -&gt; treat as normal text</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1056</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1057</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.unputString(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1058</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//warn_doc_error(context.fileName,tokenizer.getLineNr(),"Unknown option '{}' after \\{} command, expected 'width' or 'height'",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1059</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//               context.token-&gt;name, Mappers::cmdMapper-&gt;find(cmd));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1060</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1061</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1062</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1063</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1064</span><span class="doxyLineContent"><span class="doxyHighlight">    tok=<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.lex();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1065</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// if we found something we did not expect, push it back to the stream</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1066</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// so it can still be processed</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1067</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_COMMAND_AT,TokenRetval::TK_COMMAND_BS))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1068</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1069</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.unputString(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1070</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.unputString(tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_COMMAND_AT) ? </span><span class="doxyHighlightStringLiteral">"@"</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">"\\"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1071</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1072</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1073</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_SYMBOL))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1074</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1075</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.unputString(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1076</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1077</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1078</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_HTMLTAG))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1079</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1080</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.unputString(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;text);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1081</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1082</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1083</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1084</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStatePara();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1085</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1086</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a94f06b2f61c71069d46589a7cd4f7b6b">handlePendingStyleCommands</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,children);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1087</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"width={} height={}"</span><span class="doxyHighlight">,width,height);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1088</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/namespaces/mappers/#aca1c1147352a87e1d896e0c4cf70b8c9">Mappers::cmdMapper</a>, <a href="#ad6738a87a82c364cedd836a084394960">context</a>, <a href="#a105e51dc946d1daa2914afd2bc3e72af">defaultHandleToken</a>, <a href="#afa9541b35f25f2f63a6f5ff338967f22">errorHandleDefaultToken</a>, <a href="#a94f06b2f61c71069d46589a7cd4f7b6b">handlePendingStyleCommands</a>, <a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">Token::is</a>, <a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">Token::is_any_of</a>, <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a> and <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/classes/docdiafile/#a1396bc16741d66e4abf8a5293eda4632">DocDiaFile::parse</a>, <a href="/web-doxygen/docs/api/classes/docdotfile/#a2043f4bc708113c37611f56b991b6cb0">DocDotFile::parse</a>, <a href="/web-doxygen/docs/api/classes/docimage/#acbcccdba0822fb5c0776ca318cbfd631">DocImage::parse</a>, <a href="/web-doxygen/docs/api/classes/docmscfile/#ae8a3e4c248768b7438a264aaa5114813">DocMscFile::parse</a> and <a href="/web-doxygen/docs/api/classes/docplantumlfile/#aced065805a867717cc792ae759c96876">DocPlantUmlFile::parse</a>.</p>

</div>
</div>

### defaultHandleToken() {#a105e51dc946d1daa2914afd2bc3e72af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocParser::defaultHandleToken (<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, <a href="/web-doxygen/docs/api/classes/token">Token</a> tok, <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp; children, bool handleWord=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 115 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>, definition at line 1208 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a105e51dc946d1daa2914afd2bc3e72af">1208</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a105e51dc946d1daa2914afd2bc3e72af">DocParser::defaultHandleToken</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/classes/token">Token</a> tok, <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;children,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> handleWord)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1209</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1210</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"token={} handleWord={}"</span><span class="doxyHighlight">,tok.<a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">to_string</a>(),handleWord);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1211</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_WORD,TokenRetval::TK_LNKWORD,TokenRetval::TK_SYMBOL,TokenRetval::TK_URL,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1212</span><span class="doxyLineContent"><span class="doxyHighlight">                    TokenRetval::TK_COMMAND_AT,TokenRetval::TK_COMMAND_BS,TokenRetval::TK_HTMLTAG)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1213</span><span class="doxyLineContent"><span class="doxyHighlight">     )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1214</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1215</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1216</span><span class="doxyLineContent"><span class="doxyHighlight">reparsetoken:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1217</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tokenName = <a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1218</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"tokenName={}"</span><span class="doxyHighlight">,tokenName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1219</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#ab0587c46b8e1a8e18f8416b3aad58342">value</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1220</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1221</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> TokenRetval::TK_COMMAND_AT:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1222</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// fall through</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1223</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> TokenRetval::TK_COMMAND_BS:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1224</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/namespaces/mappers/#aca1c1147352a87e1d896e0c4cf70b8c9">Mappers::cmdMapper</a>-&gt;map(tokenName))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1225</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1226</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352ab41541930cbc3eb72b54d4c6da3c0ae8">CommandType::CMD_BSLASH</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1227</span><span class="doxyLineContent"><span class="doxyHighlight">          children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfaea255b976fa03c5130fa92fd22ec6e3b">HtmlEntityMapper::Sym_BSlash</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1228</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1229</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a231334a819076be4d21ffbf9eb3d5fac">CommandType::CMD_AT</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1230</span><span class="doxyLineContent"><span class="doxyHighlight">          children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa7cc15e3151231a2120a68b108d2807a5">HtmlEntityMapper::Sym_At</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1231</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1232</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352aa76513f8aaef2b7d02c9993b3920fcec">CommandType::CMD_LESS</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1233</span><span class="doxyLineContent"><span class="doxyHighlight">          children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa1a8b38abfbed7b9cb11b7228b43c4cd0">HtmlEntityMapper::Sym_Less</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1234</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1235</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a6454f09b46f73d0d141a041314c0b95c">CommandType::CMD_GREATER</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1236</span><span class="doxyLineContent"><span class="doxyHighlight">          children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa735e88daf2b0be93495e85e89e06de44">HtmlEntityMapper::Sym_Greater</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1237</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1238</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a6f9f21c0cb1ce6e48a2aac0475e7065d">CommandType::CMD_AMP</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1239</span><span class="doxyLineContent"><span class="doxyHighlight">          children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfae7bb3cd758b8df439d9bcbe7ac787f4d">HtmlEntityMapper::Sym_Amp</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1240</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1241</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a036b0b8401bf33b8e70ea757f86bead6">CommandType::CMD_DOLLAR</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1242</span><span class="doxyLineContent"><span class="doxyHighlight">          children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa648856a842f6bdcd5b8486a79d306e0f">HtmlEntityMapper::Sym_Dollar</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1243</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1244</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a602d16174562d50f3cf2f8eda1c6ebb6">CommandType::CMD_HASH</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1245</span><span class="doxyLineContent"><span class="doxyHighlight">          children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfaaafb21b517e5aea3ffe901907c8f3355">HtmlEntityMapper::Sym_Hash</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1246</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1247</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a82d29f1aaf679ee418491b7e4f5ea07d">CommandType::CMD_DCOLON</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1248</span><span class="doxyLineContent"><span class="doxyHighlight">          children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa8efb751ac50c34d457c8fc827ef55eb9">HtmlEntityMapper::Sym_DoubleColon</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1249</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1250</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a71a82fcfdc616129c03fe458496b4906">CommandType::CMD_PERCENT</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1251</span><span class="doxyLineContent"><span class="doxyHighlight">          children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa8da48ef159e7932e8ed84473fbb067a5">HtmlEntityMapper::Sym_Percent</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1252</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1253</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352ac8a3932bd8a0d7bc9ce2a5deb488aba0">CommandType::CMD_NDASH</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1254</span><span class="doxyLineContent"><span class="doxyHighlight">          children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfaf8a3a429e59ffa27cad6c8ee0c528975">HtmlEntityMapper::Sym_Minus</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1255</span><span class="doxyLineContent"><span class="doxyHighlight">          children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfaf8a3a429e59ffa27cad6c8ee0c528975">HtmlEntityMapper::Sym_Minus</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1256</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1257</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a8fcff20c756832f83f46d634de1bcb04">CommandType::CMD_MDASH</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1258</span><span class="doxyLineContent"><span class="doxyHighlight">          children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfaf8a3a429e59ffa27cad6c8ee0c528975">HtmlEntityMapper::Sym_Minus</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1259</span><span class="doxyLineContent"><span class="doxyHighlight">          children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfaf8a3a429e59ffa27cad6c8ee0c528975">HtmlEntityMapper::Sym_Minus</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1260</span><span class="doxyLineContent"><span class="doxyHighlight">          children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfaf8a3a429e59ffa27cad6c8ee0c528975">HtmlEntityMapper::Sym_Minus</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1261</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1262</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352ab632762af37578d45ecfb0cdaa5ff232">CommandType::CMD_QUOTE</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1263</span><span class="doxyLineContent"><span class="doxyHighlight">          children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfacc4e69acbf92aa382154f7e1451eeb10">HtmlEntityMapper::Sym_Quot</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1264</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1265</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a327f68a61235c8922c3b4228bc2420c9">CommandType::CMD_PUNT</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1266</span><span class="doxyLineContent"><span class="doxyHighlight">          children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa175b5cee6a647c949fb0cf94074ff0d4">HtmlEntityMapper::Sym_Dot</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1267</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1268</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a46b91211a7a50b7d83c96ac514028f2a">CommandType::CMD_EXCLAMATION</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1269</span><span class="doxyLineContent"><span class="doxyHighlight">          children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfac8eb924022c2cca673aa35e558bc27f4">HtmlEntityMapper::Sym_Exclam</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1270</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1271</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a9098d932d7292ccdcdbfc7fbfab6035e">CommandType::CMD_QUESTION</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1272</span><span class="doxyLineContent"><span class="doxyHighlight">          children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfacb93f1ef109f35c95ef77aa399c99ec1">HtmlEntityMapper::Sym_Quest</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1273</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1274</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a798425a98992c1b0eaada7bd20e4bf57">CommandType::CMD_PLUS</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1275</span><span class="doxyLineContent"><span class="doxyHighlight">          children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfae04596de435bc484c107b0133d881e42">HtmlEntityMapper::Sym_Plus</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1276</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1277</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352aedbb38e82179db12cec6adb259f83ee4">CommandType::CMD_MINUS</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1278</span><span class="doxyLineContent"><span class="doxyHighlight">          children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfaf8a3a429e59ffa27cad6c8ee0c528975">HtmlEntityMapper::Sym_Minus</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1279</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1280</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a3a9c7d82f8086ab2b77df8add8d10f7e">CommandType::CMD_EQUAL</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1281</span><span class="doxyLineContent"><span class="doxyHighlight">          children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfae41d37f6c5803503a6a12ab12885c6b8">HtmlEntityMapper::Sym_Equal</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1282</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1283</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a4ea7c7754bb98d8d463a08828e44811e">CommandType::CMD_EMPHASIS</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1284</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1285</span><span class="doxyLineContent"><span class="doxyHighlight">            children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.nodeStack.size(),<a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a8c32aed981a8fef9dab678551395440d">DocStyleChange::Italic</a>,tokenName,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1286</span><span class="doxyLineContent"><span class="doxyHighlight">            tok=<a href="#abf46a000544ae1a4f45df6430cd3e6bf">handleStyleArgument</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,children,tokenName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1287</span><span class="doxyLineContent"><span class="doxyHighlight">            children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.nodeStack.size(),<a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a8c32aed981a8fef9dab678551395440d">DocStyleChange::Italic</a>,tokenName,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1288</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_WORD)) children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docwhitespace">DocWhiteSpace</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1289</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_NEWPARA)) </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> handlepara;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1290</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_WORD,TokenRetval::TK_HTMLTAG))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1291</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1292</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"CommandType::CMD_EMPHASIS: reparsing"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1293</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> reparsetoken;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1294</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1295</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1296</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1297</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352aed8e4495d256975e34e0fcaee34ebe3b">CommandType::CMD_BOLD</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1298</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1299</span><span class="doxyLineContent"><span class="doxyHighlight">            children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.nodeStack.size(),<a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a807d9b8b8360cb61511e5ea56237c306">DocStyleChange::Bold</a>,tokenName,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1300</span><span class="doxyLineContent"><span class="doxyHighlight">            tok=<a href="#abf46a000544ae1a4f45df6430cd3e6bf">handleStyleArgument</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,children,tokenName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1301</span><span class="doxyLineContent"><span class="doxyHighlight">            children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.nodeStack.size(),<a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a807d9b8b8360cb61511e5ea56237c306">DocStyleChange::Bold</a>,tokenName,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1302</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_WORD)) children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docwhitespace">DocWhiteSpace</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1303</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_NEWPARA)) </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> handlepara;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1304</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_WORD,TokenRetval::TK_HTMLTAG))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1305</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1306</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"CommandType::CMD_BOLD: reparsing"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1307</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> reparsetoken;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1308</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1309</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1310</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1311</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a8de3af7ff872fa5ad8f22fc5eac6465b">CommandType::CMD_CODE</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1312</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1313</span><span class="doxyLineContent"><span class="doxyHighlight">            children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.nodeStack.size(),<a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad1c85e30cf1da2bdb0de2f1fe2690aa2">DocStyleChange::Code</a>,tokenName,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1314</span><span class="doxyLineContent"><span class="doxyHighlight">            tok=<a href="#abf46a000544ae1a4f45df6430cd3e6bf">handleStyleArgument</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,children,tokenName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1315</span><span class="doxyLineContent"><span class="doxyHighlight">            children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.nodeStack.size(),<a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad1c85e30cf1da2bdb0de2f1fe2690aa2">DocStyleChange::Code</a>,tokenName,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1316</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_WORD)) children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docwhitespace">DocWhiteSpace</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1317</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_NEWPARA)) </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> handlepara;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1318</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_WORD,TokenRetval::TK_HTMLTAG))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1319</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1320</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"CommandType::CMD_CODE: reparsing"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1321</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> reparsetoken;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1322</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1323</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1324</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1325</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a02ff5a94f1a879395b00661ec8185dfa">CommandType::CMD_HTMLONLY</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1326</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1327</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStateHtmlOnly();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1328</span><span class="doxyLineContent"><span class="doxyHighlight">            tok = <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.lex();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1329</span><span class="doxyLineContent"><span class="doxyHighlight">            children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.context,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;verb,<a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a8abc5ca69c3762e97cffaacc244457f1">DocVerbatim::HtmlOnly</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.isExample,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.exampleName,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name==</span><span class="doxyHighlightStringLiteral">"block"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1330</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_NONE,TokenRetval::TK_EOF))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1331</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1332</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"htmlonly section ended without end marker"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1333</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1334</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStatePara();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1335</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1336</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1337</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a6f7c17eb953b73f62e88291a95b8f8f1">CommandType::CMD_MANONLY</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1338</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1339</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStateManOnly();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1340</span><span class="doxyLineContent"><span class="doxyHighlight">            tok = <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.lex();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1341</span><span class="doxyLineContent"><span class="doxyHighlight">            children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.context,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;verb,<a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a578f19d38fb29903c3f55aea4f76bccb">DocVerbatim::ManOnly</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.isExample,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.exampleName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1342</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_NONE,TokenRetval::TK_EOF))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1343</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1344</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"manonly section ended without end marker"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1345</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1346</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStatePara();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1347</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1348</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1349</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352aeda637e085517ac5c985e4bbde534cbf">CommandType::CMD_RTFONLY</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1350</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1351</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStateRtfOnly();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1352</span><span class="doxyLineContent"><span class="doxyHighlight">            tok = <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.lex();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1353</span><span class="doxyLineContent"><span class="doxyHighlight">            children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.context,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;verb,<a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a53b96b0c5ba74d8884669c178eb88bf9">DocVerbatim::RtfOnly</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.isExample,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.exampleName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1354</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_NONE,TokenRetval::TK_EOF))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1355</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1356</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"rtfonly section ended without end marker"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1357</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1358</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStatePara();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1359</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1360</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1361</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a873d102356c495a37910b496c4ab1baa">CommandType::CMD_LATEXONLY</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1362</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1363</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStateLatexOnly();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1364</span><span class="doxyLineContent"><span class="doxyHighlight">            tok = <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.lex();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1365</span><span class="doxyLineContent"><span class="doxyHighlight">            children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.context,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;verb,<a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ac5a4818987c756de7d336c3d7ad04173">DocVerbatim::LatexOnly</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.isExample,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.exampleName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1366</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_NONE,TokenRetval::TK_EOF))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1367</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1368</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"latexonly section ended without end marker"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1369</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1370</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStatePara();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1371</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1372</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1373</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a57e61b352c9fdfb95920473a739e8c93">CommandType::CMD_XMLONLY</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1374</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1375</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStateXmlOnly();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1376</span><span class="doxyLineContent"><span class="doxyHighlight">            tok = <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.lex();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1377</span><span class="doxyLineContent"><span class="doxyHighlight">            children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.context,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;verb,<a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ad30f4dea69d46825ffdf21d1748e3715">DocVerbatim::XmlOnly</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.isExample,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.exampleName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1378</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_NONE,TokenRetval::TK_EOF))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1379</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1380</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"xmlonly section ended without end marker"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1381</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1382</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStatePara();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1383</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1384</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1385</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a13d8ae4592b82027eaed541ef9f0dbe9">CommandType::CMD_DBONLY</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1386</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1387</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStateDbOnly();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1388</span><span class="doxyLineContent"><span class="doxyHighlight">            tok = <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.lex();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1389</span><span class="doxyLineContent"><span class="doxyHighlight">            children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.context,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;verb,<a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a18bd2b8d2df70a8423919cf6dd4d33e1">DocVerbatim::DocbookOnly</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.isExample,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.exampleName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1390</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_NONE,TokenRetval::TK_EOF))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1391</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1392</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"docbookonly section ended without end marker"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1393</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1394</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStatePara();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1395</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1396</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1397</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352acc81c3d8371cc6a7b01e183a8c9fa04e">CommandType::CMD_FORMULA</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1398</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1399</span><span class="doxyLineContent"><span class="doxyHighlight">            children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docformula">DocFormula</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1400</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1401</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1402</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352aea2d6a1dd2fe7915d34d1932402a5389">CommandType::CMD_ANCHOR</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1403</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352adf944b4dade3ec860a15f1cf658f0545">CommandType::CMD_IANCHOR</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1404</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1405</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#adf24a6cf025048b8a3235ca2c897dc06">handleAnchor</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,children);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1406</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1407</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1408</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a735e652991dbdfb489d4c8265b3ff64e">CommandType::CMD_IPREFIX</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1409</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1410</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#ab8ac10aa71d5d6c021a6e2f08df318f8">handlePrefix</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,children);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1411</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1412</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1413</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a85bc5fc2f86ed5c6b7d7a1b753776372">CommandType::CMD_INTERNALREF</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1414</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1415</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a334b7286f0a4445d85743cce35a3c090">handleInternalRef</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,children);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1416</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStatePara();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1417</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1418</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1419</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a0c476e6469537815832cd5c98ef1204d">CommandType::CMD_SETSCOPE</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1420</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1421</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStateSetScope();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1422</span><span class="doxyLineContent"><span class="doxyHighlight">            (void)<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.lex();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1423</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#ad6738a87a82c364cedd836a084394960">context</a>.context = <a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1424</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">//printf("Found scope='%s'\n",qPrint(context.context));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1425</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStatePara();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1426</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1427</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1428</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a50ef1a2484f87e0e789063b64718f9c6">CommandType::CMD_IMAGE</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1429</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#aa923af2c2ca8d81fa9b65a6fa1e65a83">handleImage</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,children);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1430</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1431</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a3966b700ae5102ce64cb9b28b8001195">CommandType::CMD_ILINE</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1432</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.pushState();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1433</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStateILine();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1434</span><span class="doxyLineContent"><span class="doxyHighlight">          (void)<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.lex();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1435</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.popState();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1436</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1437</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a9ce6c869197029284ddc2d3ed0e7d966">CommandType::CMD_IFILE</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1438</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.pushState();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1439</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStateIFile();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1440</span><span class="doxyLineContent"><span class="doxyHighlight">          (void)<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.lex();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1441</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.popState();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1442</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1443</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1444</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1445</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1446</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1447</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> TokenRetval::TK_HTMLTAG:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1448</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1449</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> handleEnterLeaveStyle = [</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,&amp;<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,&amp;children,&amp;tokenName](<a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277">DocStyleChange::Style</a> style) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1450</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;endTag)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1451</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1452</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="#ab004ed65c6ab11f6ca2a4caee610bb49">handleStyleEnter</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,children,style,tokenName,&amp;<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;attribs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1453</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1454</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1455</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1456</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="#a92d044475f815e09877c88ce15399802">handleStyleLeave</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,children,style,tokenName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1457</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1458</span><span class="doxyLineContent"><span class="doxyHighlight">        };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1459</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/namespaces/mappers/#a8390ce8e78c02d974d515d560a551958">Mappers::htmlTagMapper</a>-&gt;map(tokenName))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1460</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1461</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273adf291d923a41e335a409b36d04b056c9">HtmlTagType::HTML_DIV</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1462</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"found &lt;div&gt; tag in heading"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1463</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1464</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273ad20ebedb0f176150f27c8cc20336d075">HtmlTagType::HTML_PRE</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1465</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"found &lt;pre&gt; tag in heading"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1466</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1467</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a21f6ee40064060cfd1b5dbf822ac48b5">HtmlTagType::HTML_SPAN</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1468</span><span class="doxyLineContent"><span class="doxyHighlight">            handleEnterLeaveStyle(<a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ab8e6f97aabed0d46a7cb62007fbb825f">DocStyleChange::Span</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1469</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1470</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273ab4a6927c07490c4883842f1b74c10706">HtmlTagType::HTML_BOLD</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1471</span><span class="doxyLineContent"><span class="doxyHighlight">            handleEnterLeaveStyle(<a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a807d9b8b8360cb61511e5ea56237c306">DocStyleChange::Bold</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1472</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1473</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a06c725d9e48f372affa01fdb8266c5f2">HtmlTagType::HTML_S</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1474</span><span class="doxyLineContent"><span class="doxyHighlight">            handleEnterLeaveStyle(<a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a55596f97583b8bab6927a66ea8f869d5">DocStyleChange::S</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1475</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1476</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a8a532f6aa0ff83feeb6611f7d1dd3b08">HtmlTagType::HTML_STRIKE</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1477</span><span class="doxyLineContent"><span class="doxyHighlight">            handleEnterLeaveStyle(<a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277afbc227d38530df65d31a768c8c68a54e">DocStyleChange::Strike</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1478</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1479</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a3fe7e05e1718e8e6ba5d244e6b4674db">HtmlTagType::HTML_DEL</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1480</span><span class="doxyLineContent"><span class="doxyHighlight">            handleEnterLeaveStyle(<a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a0417c5d59bbd1a5c8fb87853ae58dc63">DocStyleChange::Del</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1481</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1482</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273ab06a28f3b1cebabd6fae9d7323acac91">HtmlTagType::HTML_UNDERLINE</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1483</span><span class="doxyLineContent"><span class="doxyHighlight">            handleEnterLeaveStyle(<a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a75800ad1019038b22142b5a760df10a4">DocStyleChange::Underline</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1484</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1485</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a2dac325066ce35bf3c2b36a7e7b80cb9">HtmlTagType::HTML_INS</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1486</span><span class="doxyLineContent"><span class="doxyHighlight">            handleEnterLeaveStyle(<a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad4de98733a18ab2f074935240873fdae">DocStyleChange::Ins</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1487</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1488</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a625085c514754f3aff0a372e2d544862">HtmlTagType::HTML_CODE</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1489</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273af3ec0555269e1dbf8e1f318b7b889651">HtmlTagType::XML_C</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1490</span><span class="doxyLineContent"><span class="doxyHighlight">            handleEnterLeaveStyle(<a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad1c85e30cf1da2bdb0de2f1fe2690aa2">DocStyleChange::Code</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1491</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1492</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a5a3f7649abce807b951b5f54bc169cea">HtmlTagType::HTML_KBD</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1493</span><span class="doxyLineContent"><span class="doxyHighlight">            handleEnterLeaveStyle(<a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad048174170b3f3fc9aa377ef27324a97">DocStyleChange::Kbd</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1494</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1495</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273ae69b5e3f7ee92734b47a599b364cb885">HtmlTagType::HTML_TT</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1496</span><span class="doxyLineContent"><span class="doxyHighlight">            handleEnterLeaveStyle(<a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a6779a1e8815fc7b3a0a95e05166b5e85">DocStyleChange::Typewriter</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1497</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1498</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a980fa4689bd7bea32d8e46d8f07e84b0">HtmlTagType::HTML_EMPHASIS</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1499</span><span class="doxyLineContent"><span class="doxyHighlight">            handleEnterLeaveStyle(<a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a8c32aed981a8fef9dab678551395440d">DocStyleChange::Italic</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1500</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1501</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a43905d2b1313969ae2f210df9ef7c3bb">HtmlTagType::HTML_SUB</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1502</span><span class="doxyLineContent"><span class="doxyHighlight">            handleEnterLeaveStyle(<a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a5b36fd18bd9fcf1410577a6958997438">DocStyleChange::Subscript</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1503</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1504</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a7e216fed22259530ae959dd65ffdb7b9">HtmlTagType::HTML_SUP</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1505</span><span class="doxyLineContent"><span class="doxyHighlight">            handleEnterLeaveStyle(<a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a7883a437d4ca4973a9cb59231980004f">DocStyleChange::Superscript</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1506</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1507</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273aa98e78abc5a518292bf17a61e90af51e">HtmlTagType::HTML_CENTER</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1508</span><span class="doxyLineContent"><span class="doxyHighlight">            handleEnterLeaveStyle(<a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ae4330ac7dbaf5ee725a5813109f1854a">DocStyleChange::Center</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1509</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1510</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a9f1d616da06520eb5ed69e011e353e70">HtmlTagType::HTML_SMALL</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1511</span><span class="doxyLineContent"><span class="doxyHighlight">            handleEnterLeaveStyle(<a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a78ba2b4ff14390fbf298b4d232a469bc">DocStyleChange::Small</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1512</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1513</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273ac75d65616ed13b8354516ca1f4a3eabe">HtmlTagType::HTML_CITE</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1514</span><span class="doxyLineContent"><span class="doxyHighlight">            handleEnterLeaveStyle(<a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a4fd52aeff707aa62ec5f03f5cca312e6">DocStyleChange::Cite</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1515</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1516</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a03c65afaa75c587603bb62db4a3ab38a">HtmlTagType::HTML_IMG</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1517</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;endTag)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1518</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1519</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="#ae3321ce556544cc7281b783f2b250be4">handleImg</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,children,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;attribs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1520</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1521</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1522</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1523</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1524</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1525</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1526</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1527</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1528</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> TokenRetval::TK_SYMBOL:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1529</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1530</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7df">HtmlEntityMapper::SymType</a> s = <a href="/web-doxygen/docs/api/classes/docsymbol/#ad2d60acd5c92da5e2bc0dab925e5c2fa">DocSymbol::decodeSymbol</a>(tokenName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1531</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s!=<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa4afd8f33f5ff42a444da284278109d9f">HtmlEntityMapper::Sym_Unknown</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1532</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1533</span><span class="doxyLineContent"><span class="doxyHighlight">          children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1534</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1535</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1536</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1537</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1538</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1539</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1540</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1541</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> TokenRetval::TK_WHITESPACE:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1542</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> TokenRetval::TK_NEWPARA:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1543</span><span class="doxyLineContent"><span class="doxyHighlight">handlepara:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1544</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a66b237bbac35526d7fa7b944ca815088">insidePRE</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>) || !children.<a href="/web-doxygen/docs/api/classes/growvector/#a4e81684f665c9a1a38b5e16cfbe31d41">empty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1545</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1546</span><span class="doxyLineContent"><span class="doxyHighlight">        children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docwhitespace">DocWhiteSpace</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;chars);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1547</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1548</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1549</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> TokenRetval::TK_LNKWORD:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1550</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (handleWord)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1551</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1552</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a2b2971ad53e50d90ca4affca6a6e1d67">handleLinkedWord</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,children);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1553</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1554</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1555</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1556</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1557</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> TokenRetval::TK_WORD:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1558</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (handleWord)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1559</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1560</span><span class="doxyLineContent"><span class="doxyHighlight">        children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docword">DocWord</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1561</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1562</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1563</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1564</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1565</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> TokenRetval::TK_URL:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1566</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ad6738a87a82c364cedd836a084394960">context</a>.insideHtmlLink)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1567</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1568</span><span class="doxyLineContent"><span class="doxyHighlight">        children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docword">DocWord</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1569</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1570</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1571</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1572</span><span class="doxyLineContent"><span class="doxyHighlight">        children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docurl">DocURL</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;isEMailAddr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1573</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1574</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1575</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1576</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1577</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1578</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1579</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">DocNodeList::append</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a807d9b8b8360cb61511e5ea56237c306">DocStyleChange::Bold</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ae4330ac7dbaf5ee725a5813109f1854a">DocStyleChange::Center</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a4fd52aeff707aa62ec5f03f5cca312e6">DocStyleChange::Cite</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a6f9f21c0cb1ce6e48a2aac0475e7065d">CMD_AMP</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352aea2d6a1dd2fe7915d34d1932402a5389">CMD_ANCHOR</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a231334a819076be4d21ffbf9eb3d5fac">CMD_AT</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352aed8e4495d256975e34e0fcaee34ebe3b">CMD_BOLD</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352ab41541930cbc3eb72b54d4c6da3c0ae8">CMD_BSLASH</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a8de3af7ff872fa5ad8f22fc5eac6465b">CMD_CODE</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a13d8ae4592b82027eaed541ef9f0dbe9">CMD_DBONLY</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a82d29f1aaf679ee418491b7e4f5ea07d">CMD_DCOLON</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a036b0b8401bf33b8e70ea757f86bead6">CMD_DOLLAR</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a4ea7c7754bb98d8d463a08828e44811e">CMD_EMPHASIS</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a3a9c7d82f8086ab2b77df8add8d10f7e">CMD_EQUAL</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a46b91211a7a50b7d83c96ac514028f2a">CMD_EXCLAMATION</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352acc81c3d8371cc6a7b01e183a8c9fa04e">CMD_FORMULA</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a6454f09b46f73d0d141a041314c0b95c">CMD_GREATER</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a602d16174562d50f3cf2f8eda1c6ebb6">CMD_HASH</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a02ff5a94f1a879395b00661ec8185dfa">CMD_HTMLONLY</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352adf944b4dade3ec860a15f1cf658f0545">CMD_IANCHOR</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a9ce6c869197029284ddc2d3ed0e7d966">CMD_IFILE</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a3966b700ae5102ce64cb9b28b8001195">CMD_ILINE</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a50ef1a2484f87e0e789063b64718f9c6">CMD_IMAGE</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a85bc5fc2f86ed5c6b7d7a1b753776372">CMD_INTERNALREF</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a735e652991dbdfb489d4c8265b3ff64e">CMD_IPREFIX</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a873d102356c495a37910b496c4ab1baa">CMD_LATEXONLY</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352aa76513f8aaef2b7d02c9993b3920fcec">CMD_LESS</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a6f7c17eb953b73f62e88291a95b8f8f1">CMD_MANONLY</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a8fcff20c756832f83f46d634de1bcb04">CMD_MDASH</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352aedbb38e82179db12cec6adb259f83ee4">CMD_MINUS</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352ac8a3932bd8a0d7bc9ce2a5deb488aba0">CMD_NDASH</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a71a82fcfdc616129c03fe458496b4906">CMD_PERCENT</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a798425a98992c1b0eaada7bd20e4bf57">CMD_PLUS</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a327f68a61235c8922c3b4228bc2420c9">CMD_PUNT</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a9098d932d7292ccdcdbfc7fbfab6035e">CMD_QUESTION</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352ab632762af37578d45ecfb0cdaa5ff232">CMD_QUOTE</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352aeda637e085517ac5c985e4bbde534cbf">CMD_RTFONLY</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a0c476e6469537815832cd5c98ef1204d">CMD_SETSCOPE</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a57e61b352c9fdfb95920473a739e8c93">CMD_XMLONLY</a>, <a href="/web-doxygen/docs/api/namespaces/mappers/#aca1c1147352a87e1d896e0c4cf70b8c9">Mappers::cmdMapper</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad1c85e30cf1da2bdb0de2f1fe2690aa2">DocStyleChange::Code</a>, <a href="#ad6738a87a82c364cedd836a084394960">context</a>, <a href="/web-doxygen/docs/api/classes/docsymbol/#ad2d60acd5c92da5e2bc0dab925e5c2fa">DocSymbol::decodeSymbol</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a0417c5d59bbd1a5c8fb87853ae58dc63">DocStyleChange::Del</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a18bd2b8d2df70a8423919cf6dd4d33e1">DocVerbatim::DocbookOnly</a>, <a href="/web-doxygen/docs/api/classes/growvector/#a4e81684f665c9a1a38b5e16cfbe31d41">GrowVector&lt; T &gt;::empty</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#adf24a6cf025048b8a3235ca2c897dc06">handleAnchor</a>, <a href="#aa923af2c2ca8d81fa9b65a6fa1e65a83">handleImage</a>, <a href="#ae3321ce556544cc7281b783f2b250be4">handleImg</a>, <a href="#a334b7286f0a4445d85743cce35a3c090">handleInternalRef</a>, <a href="#a2b2971ad53e50d90ca4affca6a6e1d67">handleLinkedWord</a>, <a href="#ab8ac10aa71d5d6c021a6e2f08df318f8">handlePrefix</a>, <a href="#abf46a000544ae1a4f45df6430cd3e6bf">handleStyleArgument</a>, <a href="#ab004ed65c6ab11f6ca2a4caee610bb49">handleStyleEnter</a>, <a href="#a92d044475f815e09877c88ce15399802">handleStyleLeave</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273ab4a6927c07490c4883842f1b74c10706">HTML_BOLD</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273aa98e78abc5a518292bf17a61e90af51e">HTML_CENTER</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273ac75d65616ed13b8354516ca1f4a3eabe">HTML_CITE</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a625085c514754f3aff0a372e2d544862">HTML_CODE</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a3fe7e05e1718e8e6ba5d244e6b4674db">HTML_DEL</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273adf291d923a41e335a409b36d04b056c9">HTML_DIV</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a980fa4689bd7bea32d8e46d8f07e84b0">HTML_EMPHASIS</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a03c65afaa75c587603bb62db4a3ab38a">HTML_IMG</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a2dac325066ce35bf3c2b36a7e7b80cb9">HTML_INS</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a5a3f7649abce807b951b5f54bc169cea">HTML_KBD</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273ad20ebedb0f176150f27c8cc20336d075">HTML_PRE</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a06c725d9e48f372affa01fdb8266c5f2">HTML_S</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a9f1d616da06520eb5ed69e011e353e70">HTML_SMALL</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a21f6ee40064060cfd1b5dbf822ac48b5">HTML_SPAN</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a8a532f6aa0ff83feeb6611f7d1dd3b08">HTML_STRIKE</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a43905d2b1313969ae2f210df9ef7c3bb">HTML_SUB</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a7e216fed22259530ae959dd65ffdb7b9">HTML_SUP</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273ae69b5e3f7ee92734b47a599b364cb885">HTML_TT</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273ab06a28f3b1cebabd6fae9d7323acac91">HTML_UNDERLINE</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a8abc5ca69c3762e97cffaacc244457f1">DocVerbatim::HtmlOnly</a>, <a href="/web-doxygen/docs/api/namespaces/mappers/#a8390ce8e78c02d974d515d560a551958">Mappers::htmlTagMapper</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad4de98733a18ab2f074935240873fdae">DocStyleChange::Ins</a>, <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a66b237bbac35526d7fa7b944ca815088">insidePRE</a>, <a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">Token::is</a>, <a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">Token::is_any_of</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a8c32aed981a8fef9dab678551395440d">DocStyleChange::Italic</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad048174170b3f3fc9aa377ef27324a97">DocStyleChange::Kbd</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ac5a4818987c756de7d336c3d7ad04173">DocVerbatim::LatexOnly</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a578f19d38fb29903c3f55aea4f76bccb">DocVerbatim::ManOnly</a>, <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a53b96b0c5ba74d8884669c178eb88bf9">DocVerbatim::RtfOnly</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a55596f97583b8bab6927a66ea8f869d5">DocStyleChange::S</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a78ba2b4ff14390fbf298b4d232a469bc">DocStyleChange::Small</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ab8e6f97aabed0d46a7cb62007fbb825f">DocStyleChange::Span</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277afbc227d38530df65d31a768c8c68a54e">DocStyleChange::Strike</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a5b36fd18bd9fcf1410577a6958997438">DocStyleChange::Subscript</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a7883a437d4ca4973a9cb59231980004f">DocStyleChange::Superscript</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfae7bb3cd758b8df439d9bcbe7ac787f4d">HtmlEntityMapper::Sym_Amp</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa7cc15e3151231a2120a68b108d2807a5">HtmlEntityMapper::Sym_At</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfaea255b976fa03c5130fa92fd22ec6e3b">HtmlEntityMapper::Sym_BSlash</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa648856a842f6bdcd5b8486a79d306e0f">HtmlEntityMapper::Sym_Dollar</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa175b5cee6a647c949fb0cf94074ff0d4">HtmlEntityMapper::Sym_Dot</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa8efb751ac50c34d457c8fc827ef55eb9">HtmlEntityMapper::Sym_DoubleColon</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfae41d37f6c5803503a6a12ab12885c6b8">HtmlEntityMapper::Sym_Equal</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfac8eb924022c2cca673aa35e558bc27f4">HtmlEntityMapper::Sym_Exclam</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa735e88daf2b0be93495e85e89e06de44">HtmlEntityMapper::Sym_Greater</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfaaafb21b517e5aea3ffe901907c8f3355">HtmlEntityMapper::Sym_Hash</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa1a8b38abfbed7b9cb11b7228b43c4cd0">HtmlEntityMapper::Sym_Less</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfaf8a3a429e59ffa27cad6c8ee0c528975">HtmlEntityMapper::Sym_Minus</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa8da48ef159e7932e8ed84473fbb067a5">HtmlEntityMapper::Sym_Percent</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfae04596de435bc484c107b0133d881e42">HtmlEntityMapper::Sym_Plus</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfacb93f1ef109f35c95ef77aa399c99ec1">HtmlEntityMapper::Sym_Quest</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfacc4e69acbf92aa382154f7e1451eeb10">HtmlEntityMapper::Sym_Quot</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa4afd8f33f5ff42a444da284278109d9f">HtmlEntityMapper::Sym_Unknown</a>, <a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">Token::to_string</a>, <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a6779a1e8815fc7b3a0a95e05166b5e85">DocStyleChange::Typewriter</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a75800ad1019038b22142b5a760df10a4">DocStyleChange::Underline</a>, <a href="/web-doxygen/docs/api/classes/token/#ab0587c46b8e1a8e18f8416b3aad58342">Token::value</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273af3ec0555269e1dbf8e1f318b7b889651">XML_C</a> and <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ad30f4dea69d46825ffdf21d1748e3715">DocVerbatim::XmlOnly</a>.</p>


<p>Referenced by <a href="#ae88d59b299df415c0c2028d863288599">defaultHandleTitleAndSize</a>, <a href="#abf46a000544ae1a4f45df6430cd3e6bf">handleStyleArgument</a> and <a href="/web-doxygen/docs/api/classes/docpara/#af9a6952aca6a271fde9a883efd65cc58">DocPara::injectToken</a>.</p>

</div>
</div>

### errorHandleDefaultToken() {#afa9541b35f25f2f63a6f5ff338967f22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocParser::errorHandleDefaultToken (<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, <a href="/web-doxygen/docs/api/classes/token">Token</a> tok, <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp; children, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; txt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 118 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>, definition at line 536 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afa9541b35f25f2f63a6f5ff338967f22">536</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afa9541b35f25f2f63a6f5ff338967f22">DocParser::errorHandleDefaultToken</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/classes/token">Token</a> tok,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">537</span><span class="doxyLineContent"><span class="doxyHighlight">                                        <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;children,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;txt)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">538</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">539</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#ab0587c46b8e1a8e18f8416b3aad58342">value</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">540</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">541</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> TokenRetval::TK_COMMAND_AT:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">542</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// fall through</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">543</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> TokenRetval::TK_COMMAND_BS:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">544</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">545</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> cs[2] = { tok.<a href="/web-doxygen/docs/api/classes/token/#af1f1b6694606ac143d8e0f7d9c084114">command_to_char</a>(), 0 };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">546</span><span class="doxyLineContent"><span class="doxyHighlight">        children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docword">DocWord</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,cs + <a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">547</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"Illegal command '{:c}{}' found as part of a {}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">548</span><span class="doxyLineContent"><span class="doxyHighlight">         tok.<a href="/web-doxygen/docs/api/classes/token/#af1f1b6694606ac143d8e0f7d9c084114">command_to_char</a>(),<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name,txt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">549</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">550</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">551</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> TokenRetval::TK_SYMBOL:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">552</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"Unsupported symbol '{}' found as part of a {}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">553</span><span class="doxyLineContent"><span class="doxyHighlight">           <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name), <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(txt));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">554</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">555</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> TokenRetval::TK_HTMLTAG:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">556</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"Unsupported HTML tag &lt;{}{}&gt; found as part of a {}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">557</span><span class="doxyLineContent"><span class="doxyHighlight">           <a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;endTag ? </span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name, txt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">558</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">559</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">560</span><span class="doxyLineContent"><span class="doxyHighlight">      children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docword">DocWord</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">561</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"Unexpected token {} found as part of a {}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlight">        tok.<a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">to_string</a>(), txt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">563</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">DocNodeList::append</a>, <a href="/web-doxygen/docs/api/classes/token/#af1f1b6694606ac143d8e0f7d9c084114">Token::command_to_char</a>, <a href="#ad6738a87a82c364cedd836a084394960">context</a>, <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>, <a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">Token::to_string</a>, <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>, <a href="/web-doxygen/docs/api/classes/token/#ab0587c46b8e1a8e18f8416b3aad58342">Token::value</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>.</p>


<p>Referenced by <a href="#ae88d59b299df415c0c2028d863288599">defaultHandleTitleAndSize</a>, <a href="#abf46a000544ae1a4f45df6430cd3e6bf">handleStyleArgument</a>, <a href="/web-doxygen/docs/api/classes/dochref/#a2a9332a0da85f6e0596e3d46cea53fe5">DocHRef::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcaption/#a4f952166357e3d6d33312208d4a768f3">DocHtmlCaption::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlheader/#a5f57a370972a9ce3f7aa769973c5d2e8">DocHtmlHeader::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlsummary/#a4768457c4357b86443890d950cb3e740">DocHtmlSummary::parse</a>, <a href="/web-doxygen/docs/api/classes/docinternalref/#ab9cc38fde444889a618974f396bf36ed">DocInternalRef::parse</a>, <a href="/web-doxygen/docs/api/classes/docref/#a6004b78783411b8c5752371572afa3ef">DocRef::parse</a>, <a href="/web-doxygen/docs/api/classes/docsecrefitem/#a35c9d6d150e7faaa88ea9ddfbeadb777">DocSecRefItem::parse</a>, <a href="/web-doxygen/docs/api/classes/doctitle/#a12306a4f4de4310c8201fac9d29eb627">DocTitle::parse</a> and <a href="/web-doxygen/docs/api/classes/docvhdlflow/#afe55c9c5bf1a823e78d6aa3ea3f0777b">DocVhdlFlow::parse</a>.</p>

</div>
</div>

### findAndCopyImage() {#a3d46e03d176edeb9ec7044f80ffe3a81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocParser::findAndCopyImage (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93e">DocImage::Type</a> type, bool doWarn=true)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>search for an image in the imageNameDict and if found copies the image to the output directory (which depends on the <em>type</em> parameter).</p>


<p>Declaration at line 107 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>, definition at line 94 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3d46e03d176edeb9ec7044f80ffe3a81">94</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a3d46e03d176edeb9ec7044f80ffe3a81">DocParser::findAndCopyImage</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName, <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93e">DocImage::Type</a> type, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> doWarn)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ambig = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd = <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#a7062fae1e1507b5c093fe5b71a866371">Doxygen::imageNameLinkedMap</a>,fileName,ambig);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("Search for %s\n",fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ambig &amp; doWarn)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"image file name '{}' is ambiguous.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"Possible candidates:\n{}"</span><span class="doxyHighlight">, fileName,<a href="/web-doxygen/docs/api/files/src/util-cpp/#a70d0b468521b0304252fb659f3b15e24">showFileDefMatches</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#a7062fae1e1507b5c093fe5b71a866371">Doxygen::imageNameLinkedMap</a>,fileName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> inputFile = fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">absFilePath</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> infi(inputFile.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (infi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">      result = fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = result.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i!=-1 || (i=result.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">))!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">        result = result.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(result.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>())-i-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("fileName=%s result=%s\n",fileName,qPrint(result));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> outputDir;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(type)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ea11831c0ddc505e031751197b1bab0623">DocImage::Html</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_HTML)) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">          outputDir = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93eaa40720221c0f30f373e9b3a9ec9711e5">DocImage::Latex</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_LATEX)) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">          outputDir = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(LATEX_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ea725d162f5603b60f365bad17013c5d5a">DocImage::DocBook</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_DOCBOOK)) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">          outputDir = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(DOCBOOK_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93eaf742255bd9dc963b18e768c2b7fb7d70">DocImage::Rtf</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_RTF)) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">          outputDir = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(RTF_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ead2e9647950376dfa87071aa9913b703f">DocImage::Xml</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_XML)) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">          outputDir = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(XML_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> outputFile = outputDir+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> outfi(outputFile.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (outfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a1c0213518da428b8b85e7fb55927dccc">isSymLink</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/dir">Dir</a>().<a href="/web-doxygen/docs/api/classes/dir/#a5a64060f8e1731e8f00da7e8f7051e4b">remove</a>(outputFile.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightStringLiteral">"destination of image {} is a symlink, replacing with image"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">            outputFile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (outputFile!=inputFile) </span><span class="doxyHighlightComment">// prevent copying to ourself</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>(inputFile,outputFile) &amp;&amp; type==<a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ea11831c0ddc505e031751197b1bab0623">DocImage::Html</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/doxygen/#a91aa9805ef52783816d9da5e457b8cfb">Doxygen::indexList</a>-&gt;addImageFile(result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"could not open image {}"</span><span class="doxyHighlight">,fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (type==<a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93eaa40720221c0f30f373e9b3a9ec9711e5">DocImage::Latex</a> &amp;&amp; <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(USE_PDFLATEX) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">        fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">endsWith</a>(</span><span class="doxyHighlightStringLiteral">".eps"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">       )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightComment">// we have an .eps image in pdflatex mode =&gt; convert it to a pdf.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> outputDir = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(LATEX_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseName  = fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-4);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> epstopdfArgs(4096, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">      epstopdfArgs.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"\"%s/%s.eps\" --outfile=\"%s/%s.pdf\""</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">                           <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(outputDir), <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(baseName),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">                           <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(outputDir), <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(baseName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/namespaces/portable/#ab30a636186b72a67d57e9f7f1e917e99">Portable::system</a>(</span><span class="doxyHighlightStringLiteral">"epstopdf"</span><span class="doxyHighlight">,epstopdfArgs)!=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Problems running epstopdf. Check your TeX installation!\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/dir">Dir</a>().<a href="/web-doxygen/docs/api/classes/dir/#a5a64060f8e1731e8f00da7e8f7051e4b">remove</a>(outputDir.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+baseName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()+</span><span class="doxyHighlightStringLiteral">".eps"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> baseName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">    result=fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!result.<a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">startsWith</a>(</span><span class="doxyHighlightStringLiteral">"http:"</span><span class="doxyHighlight">) &amp;&amp; !result.<a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">startsWith</a>(</span><span class="doxyHighlightStringLiteral">"https:"</span><span class="doxyHighlight">) &amp;&amp; doWarn)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightStringLiteral">"image file {} is not found in IMAGE_PATH: "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightStringLiteral">"assuming external image."</span><span class="doxyHighlight">,fileName</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">          );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">FileDef::absFilePath</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="#ad6738a87a82c364cedd836a084394960">context</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>, <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ea725d162f5603b60f365bad17013c5d5a">DocImage::DocBook</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">QCString::endsWith</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">FileInfo::exists</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a>, <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ea11831c0ddc505e031751197b1bab0623">DocImage::Html</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a7062fae1e1507b5c093fe5b71a866371">Doxygen::imageNameLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a91aa9805ef52783816d9da5e457b8cfb">Doxygen::indexList</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a1c0213518da428b8b85e7fb55927dccc">FileInfo::isSymLink</a>, <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93eaa40720221c0f30f373e9b3a9ec9711e5">DocImage::Latex</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>, <a href="/web-doxygen/docs/api/classes/dir/#a5a64060f8e1731e8f00da7e8f7051e4b">Dir::remove</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">QCString::right</a>, <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93eaf742255bd9dc963b18e768c2b7fb7d70">DocImage::Rtf</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a70d0b468521b0304252fb659f3b15e24">showFileDefMatches</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">QCString::sprintf</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">QCString::startsWith</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#ab30a636186b72a67d57e9f7f1e917e99">Portable::system</a>, <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a> and <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ead2e9647950376dfa87071aa9913b703f">DocImage::Xml</a>.</p>


<p>Referenced by <a href="#aa923af2c2ca8d81fa9b65a6fa1e65a83">handleImage</a> and <a href="#ae3321ce556544cc7281b783f2b250be4">handleImg</a>.</p>

</div>
</div>

### findDocsForMemberOrCompound() {#aa75d3dc0424c6b364222f7f357406e62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocParser::findDocsForMemberOrCompound (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; commandName, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> * pDoc, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> * pBrief, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> ** pDef)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Looks for a documentation block with name commandName in the current context (g_parserContext.context). The resulting documentation string is put in pDoc, the definition in which the documentation was found is put in pDef.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Return Values</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">TRUE</td>
<td class="doxyParamItemDescription"><p>if name was found.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FALSE</td>
<td class="doxyParamItemDescription"><p>if name was not found.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 111 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>, definition at line 383 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa75d3dc0424c6b364222f7f357406e62">383</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aa75d3dc0424c6b364222f7f357406e62">DocParser::findDocsForMemberOrCompound</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;commandName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> *pDoc,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">                                            <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> *pBrief,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> **pDef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"commandName={}"</span><span class="doxyHighlight">,commandName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span><span class="doxyLineContent"><span class="doxyHighlight">  *pDoc=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span><span class="doxyLineContent"><span class="doxyHighlight">  *pBrief=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlight">  *pDef=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> cmdArg=commandName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cmdArg.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"empty"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a>      *fd=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a>     *gd=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/pagedef">PageDef</a>      *pd=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">402</span><span class="doxyLineContent"><span class="doxyHighlight">  gd = <a href="/web-doxygen/docs/api/classes/doxygen/#afd89d49084b42d085e9d40fc2636da9c">Doxygen::groupLinkedMap</a>-&gt;find(cmdArg);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (gd) </span><span class="doxyHighlightComment">// group</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">405</span><span class="doxyLineContent"><span class="doxyHighlight">    *pDoc=gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">406</span><span class="doxyLineContent"><span class="doxyHighlight">    *pBrief=gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">407</span><span class="doxyLineContent"><span class="doxyHighlight">    *pDef=gd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">408</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"group"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">409</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">411</span><span class="doxyLineContent"><span class="doxyHighlight">  pd = <a href="/web-doxygen/docs/api/classes/doxygen/#abd2756663a014ee48e1660d32a48cac5">Doxygen::pageLinkedMap</a>-&gt;find(cmdArg);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">412</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pd) </span><span class="doxyHighlightComment">// page</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">413</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">414</span><span class="doxyLineContent"><span class="doxyHighlight">    *pDoc=pd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">415</span><span class="doxyLineContent"><span class="doxyHighlight">    *pBrief=pd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlight">    *pDef=pd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">417</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"page"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">418</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">419</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ambig = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">421</span><span class="doxyLineContent"><span class="doxyHighlight">  fd = <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>,cmdArg,ambig);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">422</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fd &amp;&amp; !ambig) </span><span class="doxyHighlightComment">// file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">423</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">424</span><span class="doxyLineContent"><span class="doxyHighlight">    *pDoc=fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">425</span><span class="doxyLineContent"><span class="doxyHighlight">    *pBrief=fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">426</span><span class="doxyLineContent"><span class="doxyHighlight">    *pDef=fd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">427</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"file"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">428</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">429</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">430</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">431</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// for symbols we need to normalize the separator, so A#B, or A\B, or A.B becomes A::B</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">432</span><span class="doxyLineContent"><span class="doxyHighlight">  cmdArg = <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(cmdArg,</span><span class="doxyHighlightStringLiteral">"#"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">433</span><span class="doxyLineContent"><span class="doxyHighlight">  cmdArg = <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(cmdArg,</span><span class="doxyHighlightStringLiteral">"\\"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">434</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> extractAnonNs = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(EXTRACT_ANON_NSPACES);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">435</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (extractAnonNs &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">      cmdArg.<a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">startsWith</a>(</span><span class="doxyHighlightStringLiteral">"anonymous_namespace{"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span><span class="doxyLineContent"><span class="doxyHighlight">      )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">439</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> rightBracePos = cmdArg.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#abbf37d4aef6d2148223fb259a360a4dc">qstrlen</a>(</span><span class="doxyHighlightStringLiteral">"anonymous_namespace{"</span><span class="doxyHighlight">)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> leftPart = cmdArg.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(rightBracePos + 1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">441</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> rightPart = cmdArg.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(cmdArg.<a href="/web-doxygen/docs/api/classes/qcstring/#a957be37e3b98707fc7e8daeff18e391b">size</a>() - rightBracePos - 1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">442</span><span class="doxyLineContent"><span class="doxyHighlight">    rightPart = <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(rightPart, </span><span class="doxyHighlightStringLiteral">"."</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span><span class="doxyLineContent"><span class="doxyHighlight">    cmdArg = leftPart + rightPart;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">446</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">447</span><span class="doxyLineContent"><span class="doxyHighlight">    cmdArg = <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(cmdArg,</span><span class="doxyHighlightStringLiteral">"."</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> l=</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(cmdArg.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> funcStart=cmdArg.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (funcStart==-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">    funcStart=l;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">457</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// Check for the case of operator() and the like.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// beware of scenarios like operator()((foo)bar)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> secondParen = cmdArg.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">, funcStart+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> leftParen   = cmdArg.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">, funcStart+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (leftParen!=-1 &amp;&amp; secondParen!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (leftParen&lt;secondParen)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">        funcStart=secondParen;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name=<a href="/web-doxygen/docs/api/files/src/util-cpp/#a0940360aa6d41fd2496603fc565e3996">removeRedundantWhiteSpace</a>(cmdArg.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(funcStart));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> args=cmdArg.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(l-funcStart);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// try if the link is to a member</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/getdefinput">GetDefInput</a> input(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad6738a87a82c364cedd836a084394960">context</a>.context.find(</span><span class="doxyHighlightCharLiteral">'.'</span><span class="doxyHighlight">)==-1 ? <a href="#ad6738a87a82c364cedd836a084394960">context</a>.context : <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), </span><span class="doxyHighlightComment">// find('.') is a hack to detect files</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span><span class="doxyLineContent"><span class="doxyHighlight">      name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">      args);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">479</span><span class="doxyLineContent"><span class="doxyHighlight">  input.<a href="/web-doxygen/docs/api/structs/getdefinput/#a3e145754020e4907684f7363696d3634">checkCV</a>=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/getdefresult">GetDefResult</a> result = <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab5d70bf9e42fcc2766efb0655ff317e0">getDefs</a>(input);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("found=%d context=%s name=%s\n",result.found,qPrint(context.context),qPrint(name));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (result.<a href="/web-doxygen/docs/api/structs/getdefresult/#aefbd789f9b02619692da2d373bd6bd49">found</a> &amp;&amp; result.<a href="/web-doxygen/docs/api/structs/getdefresult/#a1b2b492b93267849df2dd80ced551622">md</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">    *pDoc=result.<a href="/web-doxygen/docs/api/structs/getdefresult/#a1b2b492b93267849df2dd80ced551622">md</a>-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">    *pBrief=result.<a href="/web-doxygen/docs/api/structs/getdefresult/#a1b2b492b93267849df2dd80ced551622">md</a>-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">    *pDef=result.<a href="/web-doxygen/docs/api/structs/getdefresult/#a1b2b492b93267849df2dd80ced551622">md</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"member"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> scopeOffset=</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.context.length());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">do</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// for each scope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fullName=cmdArg;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (scopeOffset&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span><span class="doxyLineContent"><span class="doxyHighlight">      fullName.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.context.left(scopeOffset)+</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("Trying fullName='%s'\n",qPrint(fullName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// try class, namespace, group, page, file reference</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd = <a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>-&gt;find(fullName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd) </span><span class="doxyHighlightComment">// class</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">      *pDoc=cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">      *pBrief=cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">      *pDef=cd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"class"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *nd = <a href="/web-doxygen/docs/api/classes/doxygen/#a033b4829afda05c5eef5cd54749b19bf">Doxygen::namespaceLinkedMap</a>-&gt;find(fullName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nd) </span><span class="doxyHighlightComment">// namespace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">513</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">514</span><span class="doxyLineContent"><span class="doxyHighlight">      *pDoc=nd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">515</span><span class="doxyLineContent"><span class="doxyHighlight">      *pBrief=nd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">516</span><span class="doxyLineContent"><span class="doxyHighlight">      *pDef=nd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">517</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"namespace"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">518</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (scopeOffset==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">521</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">      scopeOffset=-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">525</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">526</span><span class="doxyLineContent"><span class="doxyHighlight">      scopeOffset = <a href="#ad6738a87a82c364cedd836a084394960">context</a>.context.findRev(</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">,scopeOffset-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">527</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (scopeOffset==-1) scopeOffset=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">528</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">529</span><span class="doxyLineContent"><span class="doxyHighlight">  } </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (scopeOffset&gt;=0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">530</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">531</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"not found"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">532</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">533</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">Definition::briefDescription</a>, <a href="/web-doxygen/docs/api/structs/getdefinput/#a3e145754020e4907684f7363696d3634">GetDefInput::checkCV</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="#ad6738a87a82c364cedd836a084394960">context</a>, <a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">Definition::documentation</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>, <a href="/web-doxygen/docs/api/structs/getdefresult/#aefbd789f9b02619692da2d373bd6bd49">GetDefResult::found</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab5d70bf9e42fcc2766efb0655ff317e0">getDefs</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#afd89d49084b42d085e9d40fc2636da9c">Doxygen::groupLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/structs/getdefresult/#a1b2b492b93267849df2dd80ced551622">GetDefResult::md</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a033b4829afda05c5eef5cd54749b19bf">Doxygen::namespaceLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#abd2756663a014ee48e1660d32a48cac5">Doxygen::pageLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">QCString::prepend</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#abbf37d4aef6d2148223fb259a360a4dc">qstrlen</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a0940360aa6d41fd2496603fc565e3996">removeRedundantWhiteSpace</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">QCString::right</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a957be37e3b98707fc7e8daeff18e391b">QCString::size</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">QCString::startsWith</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>.</p>


<p>Referenced by <a href="#a4b7d1c2724099f28c4f3a4c56c52d912">processCopyDoc</a>.</p>

</div>
</div>

### handleAHref() {#a6a6c955c9001d67e4b722038bfc5f16b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Token DocParser::handleAHref (<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp; children, const <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> &amp; tagHtmlAttribs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 130 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>, definition at line 708 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6a6c955c9001d67e4b722038bfc5f16b">708</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/token">Token</a> <a href="#a6a6c955c9001d67e4b722038bfc5f16b">DocParser::handleAHref</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;children,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">709</span><span class="doxyLineContent"><span class="doxyHighlight">                           </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> &amp;tagHtmlAttribs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">710</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">711</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">712</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> index=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">713</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/token">Token</a> retval = Token::make_RetVal_OK();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">714</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;opt : tagHtmlAttribs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">715</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">716</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.name==</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight"> || opt.name==</span><span class="doxyHighlightStringLiteral">"id"</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// &lt;a name=label&gt; or &lt;a id=label&gt; tag</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">717</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">718</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!opt.value.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">719</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">720</span><span class="doxyLineContent"><span class="doxyHighlight">        children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docanchor">DocAnchor</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,opt.value,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">721</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// stop looking for other tag attribs</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">722</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">723</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">724</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">725</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"found &lt;a&gt; tag with name option but without value!"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">726</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">727</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">728</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.name==</span><span class="doxyHighlightStringLiteral">"href"</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// &lt;a href=url&gt;..&lt;/a&gt; tag</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">729</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">730</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// copy attributes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">731</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> attrList = tagHtmlAttribs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">732</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// and remove the href attribute</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">733</span><span class="doxyLineContent"><span class="doxyHighlight">      attrList.erase(attrList.begin()+index);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">734</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> relPath;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">735</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.value.at(0) != </span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">) relPath = <a href="#ad6738a87a82c364cedd836a084394960">context</a>.relPath;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">736</span><span class="doxyLineContent"><span class="doxyHighlight">      children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/dochref">DocHRef</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>, attrList,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">737</span><span class="doxyLineContent"><span class="doxyHighlight">                               opt.value, relPath,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">738</span><span class="doxyLineContent"><span class="doxyHighlight">                               <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8e04495ad97c6aab7960cc989e3f8c67">convertNameToFile</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">739</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad6738a87a82c364cedd836a084394960">context</a>.insideHtmlLink=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">740</span><span class="doxyLineContent"><span class="doxyHighlight">      retval = children.<a href="/web-doxygen/docs/api/structs/docnodelist/#ae3a5d9b77d64e18e642163cceac5fa2e">get_last</a>&lt;<a href="/web-doxygen/docs/api/classes/dochref">DocHRef</a>&gt;()-&gt;parse();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">741</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad6738a87a82c364cedd836a084394960">context</a>.insideHtmlLink=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">742</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStatePara();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">743</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">744</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">745</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// unsupported option for tag a</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">746</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">747</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">748</span><span class="doxyLineContent"><span class="doxyHighlight">    ++index;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">749</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">750</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> retval;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">751</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">DocNodeList::append</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="#ad6738a87a82c364cedd836a084394960">context</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8e04495ad97c6aab7960cc989e3f8c67">convertNameToFile</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/structs/docnodelist/#ae3a5d9b77d64e18e642163cceac5fa2e">DocNodeList::get_last</a>, <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>, <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a>, <a href="/web-doxygen/docs/api/classes/dochtmldesctitle/#a92b042aef732d7da8cc71182810e76c5">DocHtmlDescTitle::parse</a> and <a href="/web-doxygen/docs/api/classes/dochtmlheader/#a5f57a370972a9ce3f7aa769973c5d2e8">DocHtmlHeader::parse</a>.</p>

</div>
</div>

### handleAnchor() {#adf24a6cf025048b8a3235ca2c897dc06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocParser::handleAnchor (<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp; children)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 135 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>, definition at line 942 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adf24a6cf025048b8a3235ca2c897dc06">942</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#adf24a6cf025048b8a3235ca2c897dc06">DocParser::handleAnchor</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;children)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">943</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">944</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">945</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/token">Token</a> tok=<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.lex();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">946</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_WHITESPACE))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">947</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">948</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"expected whitespace after \\{} command"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">949</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">950</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">951</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">952</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStateAnchor();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">953</span><span class="doxyLineContent"><span class="doxyHighlight">  tok=<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.lex();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">954</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_NONE,TokenRetval::TK_EOF))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">955</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">956</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"unexpected end of comment block while parsing the "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">957</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightStringLiteral">"argument of command {}"</span><span class="doxyHighlight">,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">958</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">959</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">960</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_WORD,TokenRetval::TK_LNKWORD))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">961</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">962</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"unexpected token {} as the argument of {}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">963</span><span class="doxyLineContent"><span class="doxyHighlight">        tok.<a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">to_string</a>(),<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">964</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">965</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">966</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStatePara();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">967</span><span class="doxyLineContent"><span class="doxyHighlight">  children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docanchor">DocAnchor</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">968</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">DocNodeList::append</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="#ad6738a87a82c364cedd836a084394960">context</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">Token::is</a>, <a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">Token::is_any_of</a>, <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>, <a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">Token::to_string</a>, <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>.</p>


<p>Referenced by <a href="#a105e51dc946d1daa2914afd2bc3e72af">defaultHandleToken</a> and <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>.</p>

</div>
</div>

### handleImage() {#aa923af2c2ca8d81fa9b65a6fa1e65a83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocParser::handleImage (<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp; children)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 137 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>, definition at line 1090 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa923af2c2ca8d81fa9b65a6fa1e65a83">1090</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa923af2c2ca8d81fa9b65a6fa1e65a83">DocParser::handleImage</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>, <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;children)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1091</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1092</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1093</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inlineImage = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1094</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> anchorStr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1095</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1096</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/token">Token</a> tok=<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.lex();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1097</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_WHITESPACE))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1098</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1099</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_WORD))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1100</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1101</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name == </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1102</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1103</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStateOptions();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1104</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.lex();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1105</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStatePara();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1106</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> optList=<a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name.str(),</span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1107</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;opt : optList)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1108</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1109</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.empty()) </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1110</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> locOpt(opt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1111</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> locOptLow;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1112</span><span class="doxyLineContent"><span class="doxyHighlight">          locOpt = locOpt.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1113</span><span class="doxyLineContent"><span class="doxyHighlight">          locOptLow = locOpt.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1114</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (locOptLow == </span><span class="doxyHighlightStringLiteral">"inline"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1115</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1116</span><span class="doxyLineContent"><span class="doxyHighlight">            inlineImage = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1117</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1118</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (locOptLow.<a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">startsWith</a>(</span><span class="doxyHighlightStringLiteral">"anchor:"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1119</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1120</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!anchorStr.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1121</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1122</span><span class="doxyLineContent"><span class="doxyHighlight">               <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1123</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightStringLiteral">"multiple use of option 'anchor' for 'image' command, ignoring: '{}'"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1124</span><span class="doxyLineContent"><span class="doxyHighlight">                  locOpt.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(7));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1125</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1126</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1127</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1128</span><span class="doxyLineContent"><span class="doxyHighlight">               anchorStr = locOpt.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(7);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1129</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1130</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1131</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1132</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1133</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1134</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightStringLiteral">"unknown option '{}' for 'image' command specified"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1135</span><span class="doxyLineContent"><span class="doxyHighlight">                  locOpt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1136</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1137</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1138</span><span class="doxyLineContent"><span class="doxyHighlight">        tok=<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.lex();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1139</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_WHITESPACE))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1140</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1141</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"expected whitespace after \\image command"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1142</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1143</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1144</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1145</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1146</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1147</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1148</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"expected whitespace after \\image command"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1149</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1150</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1151</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1152</span><span class="doxyLineContent"><span class="doxyHighlight">  tok=<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.lex();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1153</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_WORD,TokenRetval::TK_LNKWORD))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1154</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1155</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"unexpected token {} as the argument of \\image"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1156</span><span class="doxyLineContent"><span class="doxyHighlight">        tok.<a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">to_string</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1157</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1158</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1159</span><span class="doxyLineContent"><span class="doxyHighlight">  tok=<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.lex();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1160</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_WHITESPACE))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1161</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1162</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"expected whitespace after \\image command"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1163</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1164</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1165</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93e">DocImage::Type</a> t = <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ea11831c0ddc505e031751197b1bab0623">DocImage::Html</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1166</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> imgType = <a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name.lower();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1167</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">      (imgType==</span><span class="doxyHighlightStringLiteral">"html"</span><span class="doxyHighlight">)    t=<a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ea11831c0ddc505e031751197b1bab0623">DocImage::Html</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1168</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (imgType==</span><span class="doxyHighlightStringLiteral">"latex"</span><span class="doxyHighlight">)   t=<a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93eaa40720221c0f30f373e9b3a9ec9711e5">DocImage::Latex</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1169</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (imgType==</span><span class="doxyHighlightStringLiteral">"docbook"</span><span class="doxyHighlight">) t=<a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ea725d162f5603b60f365bad17013c5d5a">DocImage::DocBook</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1170</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (imgType==</span><span class="doxyHighlightStringLiteral">"rtf"</span><span class="doxyHighlight">)     t=<a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93eaf742255bd9dc963b18e768c2b7fb7d70">DocImage::Rtf</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1171</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (imgType==</span><span class="doxyHighlightStringLiteral">"xml"</span><span class="doxyHighlight">)     t=<a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ead2e9647950376dfa87071aa9913b703f">DocImage::Xml</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1172</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1173</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1174</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"output format `{}` specified as the first argument of "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1175</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightStringLiteral">"\\image command is not valid"</span><span class="doxyHighlight">, imgType);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1176</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1177</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1178</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStateFile();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1179</span><span class="doxyLineContent"><span class="doxyHighlight">  tok=<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.lex();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1180</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStatePara();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1181</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_WORD))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1182</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1183</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"unexpected token {} as the argument of \\image"</span><span class="doxyHighlight">, tok.<a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">to_string</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1184</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1185</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1186</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!anchorStr.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1187</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1188</span><span class="doxyLineContent"><span class="doxyHighlight">    children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docanchor">DocAnchor</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,anchorStr,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1189</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1190</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> attrList;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1191</span><span class="doxyLineContent"><span class="doxyHighlight">  children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docimage">DocImage</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,attrList,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1192</span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a3d46e03d176edeb9ec7044f80ffe3a81">findAndCopyImage</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name,t),t,</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">,inlineImage);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1193</span><span class="doxyLineContent"><span class="doxyHighlight">  children.<a href="/web-doxygen/docs/api/structs/docnodelist/#ae3a5d9b77d64e18e642163cceac5fa2e">get_last</a>&lt;<a href="/web-doxygen/docs/api/classes/docimage">DocImage</a>&gt;()-&gt;parse();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1194</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">DocNodeList::append</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="#ad6738a87a82c364cedd836a084394960">context</a>, <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ea725d162f5603b60f365bad17013c5d5a">DocImage::DocBook</a>, <a href="#a3d46e03d176edeb9ec7044f80ffe3a81">findAndCopyImage</a>, <a href="/web-doxygen/docs/api/structs/docnodelist/#ae3a5d9b77d64e18e642163cceac5fa2e">DocNodeList::get_last</a>, <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ea11831c0ddc505e031751197b1bab0623">DocImage::Html</a>, <a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">Token::is</a>, <a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">Token::is_any_of</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93eaa40720221c0f30f373e9b3a9ec9711e5">DocImage::Latex</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>, <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93eaf742255bd9dc963b18e768c2b7fb7d70">DocImage::Rtf</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">QCString::startsWith</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>, <a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">Token::to_string</a>, <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a> and <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ead2e9647950376dfa87071aa9913b703f">DocImage::Xml</a>.</p>


<p>Referenced by <a href="#a105e51dc946d1daa2914afd2bc3e72af">defaultHandleToken</a> and <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>.</p>

</div>
</div>

### handleImg() {#ae3321ce556544cc7281b783f2b250be4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocParser::handleImg (<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp; children, const <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> &amp; tagHtmlAttribs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 103 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>, definition at line 1583 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae3321ce556544cc7281b783f2b250be4">1583</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae3321ce556544cc7281b783f2b250be4">DocParser::handleImg</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>, <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;children,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> &amp;tagHtmlAttribs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1584</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1585</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1586</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> found=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1587</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> index=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1588</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;opt : tagHtmlAttribs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1589</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1590</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"option name={} value='{}'"</span><span class="doxyHighlight">,opt.name,opt.value);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1591</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.name==</span><span class="doxyHighlightStringLiteral">"src"</span><span class="doxyHighlight"> &amp;&amp; !opt.value.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1592</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1593</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// copy attributes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1594</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> attrList = tagHtmlAttribs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1595</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// and remove the src attribute</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1596</span><span class="doxyLineContent"><span class="doxyHighlight">      attrList.erase(attrList.begin()+index);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1597</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93e">DocImage::Type</a> t = <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ea11831c0ddc505e031751197b1bab0623">DocImage::Html</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1598</span><span class="doxyLineContent"><span class="doxyHighlight">      children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docimage">DocImage</a>&gt;(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1599</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,attrList,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1600</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a3d46e03d176edeb9ec7044f80ffe3a81">findAndCopyImage</a>(opt.value,t,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1601</span><span class="doxyLineContent"><span class="doxyHighlight">            t,opt.value);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1602</span><span class="doxyLineContent"><span class="doxyHighlight">      found = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1603</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1604</span><span class="doxyLineContent"><span class="doxyHighlight">    ++index;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1605</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1606</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!found)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1607</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1608</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"IMG tag does not have a SRC attribute!"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1609</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1610</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">DocNodeList::append</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>, <a href="#ad6738a87a82c364cedd836a084394960">context</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a3d46e03d176edeb9ec7044f80ffe3a81">findAndCopyImage</a>, <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ea11831c0ddc505e031751197b1bab0623">DocImage::Html</a>, <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>, <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>.</p>


<p>Referenced by <a href="#a105e51dc946d1daa2914afd2bc3e72af">defaultHandleToken</a> and <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a>.</p>

</div>
</div>

### handleInitialStyleCommands() {#a7cbce284509ccf3109aa71472842ce4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocParser::handleInitialStyleCommands (<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp; children)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 129 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>, definition at line 697 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7cbce284509ccf3109aa71472842ce4e">697</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7cbce284509ccf3109aa71472842ce4e">DocParser::handleInitialStyleCommands</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;children)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">698</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">699</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">700</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!<a href="#ad6738a87a82c364cedd836a084394960">context</a>.initialStyleStack.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">701</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">702</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a> &amp;sc = std::get&lt;DocStyleChange&gt;(*<a href="#ad6738a87a82c364cedd836a084394960">context</a>.initialStyleStack.top());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">703</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ab004ed65c6ab11f6ca2a4caee610bb49">handleStyleEnter</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,children,sc.<a href="/web-doxygen/docs/api/classes/docstylechange/#a56d079390f264e34af453a015bd2e2c9">style</a>(),sc.<a href="/web-doxygen/docs/api/classes/docstylechange/#a44ca0ca006829c1ca5d0fb87cb699a84">tagName</a>(),&amp;sc.<a href="/web-doxygen/docs/api/classes/docstylechange/#a3c0ac63aee1132f4dbe442366444c99c">attribs</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">704</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad6738a87a82c364cedd836a084394960">context</a>.initialStyleStack.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">705</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">706</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docstylechange/#a3c0ac63aee1132f4dbe442366444c99c">DocStyleChange::attribs</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="#ad6738a87a82c364cedd836a084394960">context</a>, <a href="#ab004ed65c6ab11f6ca2a4caee610bb49">handleStyleEnter</a>, <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a56d079390f264e34af453a015bd2e2c9">DocStyleChange::style</a> and <a href="/web-doxygen/docs/api/classes/docstylechange/#a44ca0ca006829c1ca5d0fb87cb699a84">DocStyleChange::tagName</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#aafc94d2ed7856e4a11e404e2ee05fb40">DocPara::parse</a>.</p>

</div>
</div>

### handleInternalRef() {#a334b7286f0a4445d85743cce35a3c090}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocParser::handleInternalRef (<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp; children)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 134 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>, definition at line 920 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a334b7286f0a4445d85743cce35a3c090">920</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a334b7286f0a4445d85743cce35a3c090">DocParser::handleInternalRef</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;children)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">921</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">922</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/token">Token</a> tok=<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.lex();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">923</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tokenName = <a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">924</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"name={}"</span><span class="doxyHighlight">,tokenName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">925</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_WHITESPACE))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">926</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">927</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"expected whitespace after \\{} command"</span><span class="doxyHighlight">, tokenName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">928</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">929</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">930</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStateInternalRef();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">931</span><span class="doxyLineContent"><span class="doxyHighlight">  tok=<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.lex(); </span><span class="doxyHighlightComment">// get the reference id</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">932</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_WORD,TokenRetval::TK_LNKWORD))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">933</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">934</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"unexpected token {} as the argument of {}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">935</span><span class="doxyLineContent"><span class="doxyHighlight">        tok.<a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">to_string</a>(),tokenName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">936</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">937</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">938</span><span class="doxyLineContent"><span class="doxyHighlight">  children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docinternalref">DocInternalRef</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">939</span><span class="doxyLineContent"><span class="doxyHighlight">  children.<a href="/web-doxygen/docs/api/structs/docnodelist/#ae3a5d9b77d64e18e642163cceac5fa2e">get_last</a>&lt;<a href="/web-doxygen/docs/api/classes/docinternalref">DocInternalRef</a>&gt;()-&gt;parse();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">940</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">DocNodeList::append</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="#ad6738a87a82c364cedd836a084394960">context</a>, <a href="/web-doxygen/docs/api/structs/docnodelist/#ae3a5d9b77d64e18e642163cceac5fa2e">DocNodeList::get_last</a>, <a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">Token::is</a>, <a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">Token::is_any_of</a>, <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>, <a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">Token::to_string</a>, <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>.</p>


<p>Referenced by <a href="#a105e51dc946d1daa2914afd2bc3e72af">defaultHandleToken</a> and <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>.</p>

</div>
</div>

### handleLinkedWord() {#a2b2971ad53e50d90ca4affca6a6e1d67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocParser::handleLinkedWord (<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp; children, bool ignoreAutoLinkFlag=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 132 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>, definition at line 777 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2b2971ad53e50d90ca4affca6a6e1d67">777</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2b2971ad53e50d90ca4affca6a6e1d67">DocParser::handleLinkedWord</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;children,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ignoreAutoLinkFlag)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">778</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">779</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// helper to check if word w starts with any of the words in AUTOLINK_IGNORE_WORDS</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">780</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> ignoreWord = [](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;w) -&gt; </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">781</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;list = <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>(AUTOLINK_IGNORE_WORDS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">782</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::find_if(list.begin(), list.end(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">783</span><span class="doxyLineContent"><span class="doxyHighlight">                       [&amp;w](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ignore) { return w.startsWith(ignore); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">784</span><span class="doxyLineContent"><span class="doxyHighlight">                      )!=list.end();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">785</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">786</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1193619fc22f8093dc4096b092165b96">linkToText</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.lang,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">787</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"word={}"</span><span class="doxyHighlight">,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">788</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((!<a href="#ad6738a87a82c364cedd836a084394960">context</a>.autolinkSupport &amp;&amp; !ignoreAutoLinkFlag) || ignoreWord(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name)) </span><span class="doxyHighlightComment">// no autolinking -&gt; add as normal word</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">789</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">790</span><span class="doxyLineContent"><span class="doxyHighlight">    children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docword">DocWord</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">791</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">792</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">793</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">794</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// ------- try to turn the word 'name' into a link</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">795</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">796</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *compound=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">797</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>  *member=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">798</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len = <a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">799</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">800</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ambig = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">801</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd = <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,ambig);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">802</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> lang = <a href="#ad6738a87a82c364cedd836a084394960">context</a>.lang;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">803</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("handleLinkedWord(%s) context.context=%s\n",qPrint(context.token-&gt;name),qPrint(context.context));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">804</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ad6738a87a82c364cedd836a084394960">context</a>.insideHtmlLink &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">805</span><span class="doxyLineContent"><span class="doxyHighlight">      (<a href="/web-doxygen/docs/api/files/src/util-cpp/#a2bb57904806cf057f0d38374a63209ea">resolveRef</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.context,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.inSeeBlock,&amp;compound,&amp;member,lang,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,fd,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">806</span><span class="doxyLineContent"><span class="doxyHighlight">       || (!<a href="#ad6738a87a82c364cedd836a084394960">context</a>.context.isEmpty() &amp;&amp;  </span><span class="doxyHighlightComment">// also try with global scope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">807</span><span class="doxyLineContent"><span class="doxyHighlight">           <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2bb57904806cf057f0d38374a63209ea">resolveRef</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.inSeeBlock,&amp;compound,&amp;member,lang,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">808</span><span class="doxyLineContent"><span class="doxyHighlight">      )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">809</span><span class="doxyLineContent"><span class="doxyHighlight">     )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">810</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">811</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("ADD %s = %p (linkable?=%d)\n",qPrint(context.token-&gt;name),(void*)member,member ? member-&gt;isLinkable() : FALSE);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">812</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (member &amp;&amp; member-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">isLinkable</a>()) </span><span class="doxyHighlightComment">// member link</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">813</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">814</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"resolved reference as member link"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">815</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (member-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a146e2a27f8eee953b076a03e42ecf2b4">isObjCMethod</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">816</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">817</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> localLink = <a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef ? member-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a33ff70edee6691aacaeecf40a1146995">getClassDef</a>()==<a href="#ad6738a87a82c364cedd836a084394960">context</a>.memberDef-&gt;getClassDef() : <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">818</span><span class="doxyLineContent"><span class="doxyHighlight">        name = member-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#aa7228a0cbd28108dfab580c17d3f2751">objCMethodName</a>(localLink,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.inSeeBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">819</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">820</span><span class="doxyLineContent"><span class="doxyHighlight">      children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/doclinkedword">DocLinkedWord</a>&gt;(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">821</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">822</span><span class="doxyLineContent"><span class="doxyHighlight">            member-&gt;<a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">getReference</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">823</span><span class="doxyLineContent"><span class="doxyHighlight">            member-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">824</span><span class="doxyLineContent"><span class="doxyHighlight">            member-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">825</span><span class="doxyLineContent"><span class="doxyHighlight">            member-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a5915353219702c6ea73cc1476bda793a">briefDescriptionAsTooltip</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">826</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">827</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (compound-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">isLinkable</a>()) </span><span class="doxyHighlightComment">// compound link</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">828</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">829</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"resolved reference as compound link"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">830</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> anchor = compound-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">831</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (compound-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea203462c7d34ced15beac624562c2708e">Definition::TypeFile</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">832</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">833</span><span class="doxyLineContent"><span class="doxyHighlight">        name=<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">834</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">835</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (compound-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eade4f51e436ce466a886244c7a4c373eb">Definition::TypeGroup</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">836</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">837</span><span class="doxyLineContent"><span class="doxyHighlight">        name=<a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a81b6ac5e79beed572376b9aebfa96da5">toGroupDef</a>(compound)-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a2caedefd187d92eb8c4afe01d403456e">groupTitle</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">838</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">839</span><span class="doxyLineContent"><span class="doxyHighlight">      children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/doclinkedword">DocLinkedWord</a>&gt;(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">840</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">841</span><span class="doxyLineContent"><span class="doxyHighlight">            compound-&gt;<a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">getReference</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">842</span><span class="doxyLineContent"><span class="doxyHighlight">            compound-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">843</span><span class="doxyLineContent"><span class="doxyHighlight">            anchor,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">844</span><span class="doxyLineContent"><span class="doxyHighlight">            compound-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a5915353219702c6ea73cc1476bda793a">briefDescriptionAsTooltip</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">845</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">846</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (compound-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea203462c7d34ced15beac624562c2708e">Definition::TypeFile</a> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">847</span><span class="doxyLineContent"><span class="doxyHighlight">             (<a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a4114c484f3ccea1048608b9caa9f51de">toFileDef</a>(compound))-&gt;generateSourceFile()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">848</span><span class="doxyLineContent"><span class="doxyHighlight">            ) </span><span class="doxyHighlightComment">// undocumented file that has source code we can link to</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">849</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">850</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"resolved reference as source link"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">851</span><span class="doxyLineContent"><span class="doxyHighlight">      children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/doclinkedword">DocLinkedWord</a>&gt;(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">852</span><span class="doxyLineContent"><span class="doxyHighlight">             </span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">853</span><span class="doxyLineContent"><span class="doxyHighlight">             compound-&gt;<a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">getReference</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">854</span><span class="doxyLineContent"><span class="doxyHighlight">             compound-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ab7ecf3e26ca026ed20af225f332e5fe7">getSourceFileBase</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">855</span><span class="doxyLineContent"><span class="doxyHighlight">             </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">856</span><span class="doxyLineContent"><span class="doxyHighlight">             compound-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a5915353219702c6ea73cc1476bda793a">briefDescriptionAsTooltip</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">857</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">858</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// not linkable</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">859</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">860</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"resolved reference as unlinkable compound={} (linkable={}) member={} (linkable={})"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">861</span><span class="doxyLineContent"><span class="doxyHighlight">                     compound ? compound-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>() : </span><span class="doxyHighlightStringLiteral">"&lt;none&gt;"</span><span class="doxyHighlight">, compound ? (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)compound-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">isLinkable</a>() : -1,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">862</span><span class="doxyLineContent"><span class="doxyHighlight">                     member   ? member-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>()   : </span><span class="doxyHighlightStringLiteral">"&lt;none&gt;"</span><span class="doxyHighlight">, member   ? (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)member-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">isLinkable</a>()   : -1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">863</span><span class="doxyLineContent"><span class="doxyHighlight">      children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docword">DocWord</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">864</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">865</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">866</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ad6738a87a82c364cedd836a084394960">context</a>.insideHtmlLink &amp;&amp; len&gt;1 &amp;&amp; <a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name.at(len-1)==</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">867</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">868</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// special case, where matching Foo: fails to be an Obj-C reference,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">869</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// but Foo itself might be linkable.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">870</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name=<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name.left(len-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">871</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a2b2971ad53e50d90ca4affca6a6e1d67">handleLinkedWord</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,children,ignoreAutoLinkFlag);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">872</span><span class="doxyLineContent"><span class="doxyHighlight">    children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docword">DocWord</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,</span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">873</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">874</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ad6738a87a82c364cedd836a084394960">context</a>.insideHtmlLink &amp;&amp; (cd=<a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a9682735bd2cf0656eaa944f8b3e364a2">getClass</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name+</span><span class="doxyHighlightStringLiteral">"-p"</span><span class="doxyHighlight">)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">875</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">876</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// special case 2, where the token name is not a class, but could</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">877</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// be a Obj-C protocol</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">878</span><span class="doxyLineContent"><span class="doxyHighlight">    children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/doclinkedword">DocLinkedWord</a>&gt;(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">879</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">880</span><span class="doxyLineContent"><span class="doxyHighlight">          cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">getReference</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">881</span><span class="doxyLineContent"><span class="doxyHighlight">          cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">882</span><span class="doxyLineContent"><span class="doxyHighlight">          cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">883</span><span class="doxyLineContent"><span class="doxyHighlight">          cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a5915353219702c6ea73cc1476bda793a">briefDescriptionAsTooltip</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">884</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">885</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// normal non-linkable word</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">886</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">887</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"non-linkable"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">888</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name.startsWith(</span><span class="doxyHighlightStringLiteral">"#"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">889</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">890</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"explicit link request to '{}' could not be resolved"</span><span class="doxyHighlight">,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">891</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">892</span><span class="doxyLineContent"><span class="doxyHighlight">    children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docword">DocWord</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">893</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">894</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">Definition::anchor</a>, <a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">DocNodeList::append</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>, <a href="/web-doxygen/docs/api/classes/definition/#a5915353219702c6ea73cc1476bda793a">Definition::briefDescriptionAsTooltip</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>, <a href="#ad6738a87a82c364cedd836a084394960">context</a>, <a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">Definition::definitionType</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a9682735bd2cf0656eaa944f8b3e364a2">getClass</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a33ff70edee6691aacaeecf40a1146995">MemberDef::getClassDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">Definition::getReference</a>, <a href="/web-doxygen/docs/api/classes/definition/#ab7ecf3e26ca026ed20af225f332e5fe7">Definition::getSourceFileBase</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#a2caedefd187d92eb8c4afe01d403456e">GroupDef::groupTitle</a>, <a href="#a2b2971ad53e50d90ca4affca6a6e1d67">handleLinkedWord</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">Definition::isLinkable</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a146e2a27f8eee953b076a03e42ecf2b4">MemberDef::isObjCMethod</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1193619fc22f8093dc4096b092165b96">linkToText</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#aa7228a0cbd28108dfab580c17d3f2751">MemberDef::objCMethodName</a>, <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2bb57904806cf057f0d38374a63209ea">resolveRef</a>, <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a4114c484f3ccea1048608b9caa9f51de">toFileDef</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a81b6ac5e79beed572376b9aebfa96da5">toGroupDef</a>, <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea203462c7d34ced15beac624562c2708e">Definition::TypeFile</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eade4f51e436ce466a886244c7a4c373eb">Definition::TypeGroup</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>.</p>


<p>Referenced by <a href="#a105e51dc946d1daa2914afd2bc3e72af">defaultHandleToken</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a>, <a href="#a2b2971ad53e50d90ca4affca6a6e1d67">handleLinkedWord</a>, <a href="#a367fe5ccd7e0378c2e5c94df6e60dd0d">handleParameterType</a>, <a href="/web-doxygen/docs/api/classes/docpara/#aafc94d2ed7856e4a11e404e2ee05fb40">DocPara::parse</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a98345755b6311bcc4129bd7ee14759f1">DocParamList::parse</a> and <a href="/web-doxygen/docs/api/classes/docparamlist/#a79bb36905dd1401288d55e12ee52ce03">DocParamList::parseXml</a>.</p>

</div>
</div>

### handleParameterType() {#a367fe5ccd7e0378c2e5c94df6e60dd0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocParser::handleParameterType (<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp; children, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; paramTypes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 133 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>, definition at line 896 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a367fe5ccd7e0378c2e5c94df6e60dd0d">896</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a367fe5ccd7e0378c2e5c94df6e60dd0d">DocParser::handleParameterType</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;children,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;paramTypes)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">897</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">898</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name = <a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name; </span><span class="doxyHighlightComment">// save token name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">899</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"name={}"</span><span class="doxyHighlight">,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">900</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">901</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> p=0, i=0, ii=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">902</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((i=paramTypes.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'|'</span><span class="doxyHighlight">,p))!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">903</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">904</span><span class="doxyLineContent"><span class="doxyHighlight">    name1 = paramTypes.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(p,i-p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">905</span><span class="doxyLineContent"><span class="doxyHighlight">    ii=name1.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'['</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">906</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name=ii!=-1 ? name1.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(0,ii) : name1; </span><span class="doxyHighlightComment">// take part without []</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">907</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a2b2971ad53e50d90ca4affca6a6e1d67">handleLinkedWord</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,children);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">908</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ii!=-1) children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docword">DocWord</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,name1.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(ii)); </span><span class="doxyHighlightComment">// add [] part</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">909</span><span class="doxyLineContent"><span class="doxyHighlight">    p=i+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">910</span><span class="doxyLineContent"><span class="doxyHighlight">    children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docseparator">DocSeparator</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,</span><span class="doxyHighlightStringLiteral">"|"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">911</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">912</span><span class="doxyLineContent"><span class="doxyHighlight">  name1 = paramTypes.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">913</span><span class="doxyLineContent"><span class="doxyHighlight">  ii=name1.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'['</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">914</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name=ii!=-1 ? name1.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(0,ii) : name1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">915</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2b2971ad53e50d90ca4affca6a6e1d67">handleLinkedWord</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,children);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">916</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ii!=-1) children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docword">DocWord</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,name1.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(ii));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">917</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name = name; </span><span class="doxyHighlightComment">// restore original token name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">918</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">DocNodeList::append</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="#ad6738a87a82c364cedd836a084394960">context</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="#a2b2971ad53e50d90ca4affca6a6e1d67">handleLinkedWord</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a> and <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docparamlist/#a98345755b6311bcc4129bd7ee14759f1">DocParamList::parse</a>.</p>

</div>
</div>

### handlePendingStyleCommands() {#a94f06b2f61c71069d46589a7cd4f7b6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocParser::handlePendingStyleCommands (<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp; children)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Called at the end of a paragraph to close all open style changes (e.g. a <b> without a </b>). The closed styles are pushed onto a stack and entered again at the start of a new paragraph.</p>


<p>Declaration at line 128 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>, definition at line 680 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a94f06b2f61c71069d46589a7cd4f7b6b">680</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a94f06b2f61c71069d46589a7cd4f7b6b">DocParser::handlePendingStyleCommands</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;children)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">681</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">682</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">683</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ad6738a87a82c364cedd836a084394960">context</a>.styleStack.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">684</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">685</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a> *sc = &amp;std::get&lt;DocStyleChange&gt;(*<a href="#ad6738a87a82c364cedd836a084394960">context</a>.styleStack.top());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">686</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (sc &amp;&amp; sc-&gt;<a href="/web-doxygen/docs/api/classes/docstylechange/#a9cfdbb1f8ace3872966d8e6338cc9720">position</a>()&gt;=<a href="#ad6738a87a82c364cedd836a084394960">context</a>.nodeStack.size())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">687</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightComment">// there are unclosed style modifiers in the paragraph</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">688</span><span class="doxyLineContent"><span class="doxyHighlight">      children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.nodeStack.size(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">689</span><span class="doxyLineContent"><span class="doxyHighlight">                                           sc-&gt;<a href="/web-doxygen/docs/api/classes/docstylechange/#a56d079390f264e34af453a015bd2e2c9">style</a>(),sc-&gt;<a href="/web-doxygen/docs/api/classes/docstylechange/#a44ca0ca006829c1ca5d0fb87cb699a84">tagName</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">690</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad6738a87a82c364cedd836a084394960">context</a>.initialStyleStack.push(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.styleStack.top());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">691</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad6738a87a82c364cedd836a084394960">context</a>.styleStack.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">692</span><span class="doxyLineContent"><span class="doxyHighlight">      sc = !<a href="#ad6738a87a82c364cedd836a084394960">context</a>.styleStack.empty() ? &amp;std::get&lt;DocStyleChange&gt;(*<a href="#ad6738a87a82c364cedd836a084394960">context</a>.styleStack.top()) : </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">693</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">694</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">DocNodeList::append</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="#ad6738a87a82c364cedd836a084394960">context</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a9cfdbb1f8ace3872966d8e6338cc9720">DocStyleChange::position</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a56d079390f264e34af453a015bd2e2c9">DocStyleChange::style</a> and <a href="/web-doxygen/docs/api/classes/docstylechange/#a44ca0ca006829c1ca5d0fb87cb699a84">DocStyleChange::tagName</a>.</p>


<p>Referenced by <a href="#ae88d59b299df415c0c2028d863288599">defaultHandleTitleAndSize</a>, <a href="/web-doxygen/docs/api/classes/dochref/#a2a9332a0da85f6e0596e3d46cea53fe5">DocHRef::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcaption/#a4f952166357e3d6d33312208d4a768f3">DocHtmlCaption::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldesctitle/#a92b042aef732d7da8cc71182810e76c5">DocHtmlDescTitle::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlheader/#a5f57a370972a9ce3f7aa769973c5d2e8">DocHtmlHeader::parse</a>, <a href="/web-doxygen/docs/api/classes/docinternalref/#ab9cc38fde444889a618974f396bf36ed">DocInternalRef::parse</a>, <a href="/web-doxygen/docs/api/classes/doclink/#aeb676914fb893fa31c99b39c1f7bb6d3">DocLink::parse</a>, <a href="/web-doxygen/docs/api/classes/docpara/#aafc94d2ed7856e4a11e404e2ee05fb40">DocPara::parse</a>, <a href="/web-doxygen/docs/api/classes/docref/#a6004b78783411b8c5752371572afa3ef">DocRef::parse</a>, <a href="/web-doxygen/docs/api/classes/docsecrefitem/#a35c9d6d150e7faaa88ea9ddfbeadb777">DocSecRefItem::parse</a>, <a href="/web-doxygen/docs/api/classes/doctitle/#a12306a4f4de4310c8201fac9d29eb627">DocTitle::parse</a> and <a href="/web-doxygen/docs/api/classes/docvhdlflow/#afe55c9c5bf1a823e78d6aa3ea3f0777b">DocVhdlFlow::parse</a>.</p>

</div>
</div>

### handlePrefix() {#ab8ac10aa71d5d6c021a6e2f08df318f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocParser::handlePrefix (<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp; children)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 136 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>, definition at line 970 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab8ac10aa71d5d6c021a6e2f08df318f8">970</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab8ac10aa71d5d6c021a6e2f08df318f8">DocParser::handlePrefix</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;children)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">971</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">972</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">973</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/token">Token</a> tok=<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.lex();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">974</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_WHITESPACE))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">975</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">976</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"expected whitespace after \\{} command"</span><span class="doxyHighlight">, <a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">977</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">978</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">979</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStatePrefix();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">980</span><span class="doxyLineContent"><span class="doxyHighlight">  tok=<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.lex();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">981</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_NONE,TokenRetval::TK_EOF))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">982</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">983</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"unexpected end of comment block while parsing the "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">984</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightStringLiteral">"argument of command {}"</span><span class="doxyHighlight">,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">985</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">986</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">987</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_WORD))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">988</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">989</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"unexpected token {} as the argument of {}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">990</span><span class="doxyLineContent"><span class="doxyHighlight">        tok.<a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">to_string</a>(),<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">991</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">992</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">993</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad6738a87a82c364cedd836a084394960">context</a>.prefix = <a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">994</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setStatePara();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">995</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="#ad6738a87a82c364cedd836a084394960">context</a>, <a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">Token::is</a>, <a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">Token::is_any_of</a>, <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>, <a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">Token::to_string</a>, <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>.</p>


<p>Referenced by <a href="#a105e51dc946d1daa2914afd2bc3e72af">defaultHandleToken</a> and <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>.</p>

</div>
</div>

### handleStyleArgument() {#abf46a000544ae1a4f45df6430cd3e6bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Token DocParser::handleStyleArgument (<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp; children, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; cmdName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 122 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>, definition at line 569 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abf46a000544ae1a4f45df6430cd3e6bf">569</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/token">Token</a> <a href="#abf46a000544ae1a4f45df6430cd3e6bf">DocParser::handleStyleArgument</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;children,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;cmdName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">570</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">571</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"cmdName={}"</span><span class="doxyHighlight">,cmdName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">572</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> saveCmdName = cmdName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/token">Token</a> tok=<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.lex();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_WHITESPACE))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">575</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">576</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"expected whitespace after \\{} command"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">577</span><span class="doxyLineContent"><span class="doxyHighlight">        saveCmdName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">578</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> tok;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span><span class="doxyLineContent"><span class="doxyHighlight">  tok = <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.lex();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_NONE, TokenRetval::TK_EOF, TokenRetval::TK_WHITESPACE,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span><span class="doxyLineContent"><span class="doxyHighlight">                        TokenRetval::TK_NEWPARA, TokenRetval::TK_LISTITEM, TokenRetval::TK_ENDLIST)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">        )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">584</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> specialChar(R</span><span class="doxyHighlightStringLiteral">"([.,|()\[\]:;?])");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">586</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_WORD) &amp;&amp; <a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name.length()==1 &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">587</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/namespaces/reg/#abd83bf57cdc053d40135b7c8f211f2b9">reg::match</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name.str(),specialChar))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">589</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// special character that ends the markup command</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">590</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> tok;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">591</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">592</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a105e51dc946d1daa2914afd2bc3e72af">defaultHandleToken</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,tok,children))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">593</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#ab0587c46b8e1a8e18f8416b3aad58342">value</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> TokenRetval::TK_HTMLTAG:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a786afe8925235dea586eb23046acaf41">insideLI</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>) &amp;&amp; <a href="/web-doxygen/docs/api/namespaces/mappers/#a8390ce8e78c02d974d515d560a551958">Mappers::htmlTagMapper</a>-&gt;map(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;name)!=<a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a696b031073e74bf2cb98e5ef201d4aa3">HtmlTagType::UNKNOWN</a> &amp;&amp; <a href="#ad6738a87a82c364cedd836a084394960">context</a>.token-&gt;endTag)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// ignore &lt;/li&gt; as the end of a style command</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">601</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">602</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">603</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"end tok={}"</span><span class="doxyHighlight">,tok.<a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">to_string</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">604</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> tok;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#afa9541b35f25f2f63a6f5ff338967f22">errorHandleDefaultToken</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,tok,children,</span><span class="doxyHighlightStringLiteral">"\\"</span><span class="doxyHighlight"> + saveCmdName + </span><span class="doxyHighlightStringLiteral">" command"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">613</span><span class="doxyLineContent"><span class="doxyHighlight">    tok = <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.lex();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">614</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">615</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"end tok={}"</span><span class="doxyHighlight">,tok.<a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">to_string</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">616</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_NEWPARA,TokenRetval::TK_LISTITEM,TokenRetval::TK_ENDLIST)) ? tok : Token::make_RetVal_OK();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="#ad6738a87a82c364cedd836a084394960">context</a>, <a href="#a105e51dc946d1daa2914afd2bc3e72af">defaultHandleToken</a>, <a href="#afa9541b35f25f2f63a6f5ff338967f22">errorHandleDefaultToken</a>, <a href="/web-doxygen/docs/api/namespaces/mappers/#a8390ce8e78c02d974d515d560a551958">Mappers::htmlTagMapper</a>, <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a786afe8925235dea586eb23046acaf41">insideLI</a>, <a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">Token::is</a>, <a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">Token::is_any_of</a>, <a href="/web-doxygen/docs/api/namespaces/reg/#abd83bf57cdc053d40135b7c8f211f2b9">reg::match</a>, <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>, <a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">Token::to_string</a>, <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a696b031073e74bf2cb98e5ef201d4aa3">UNKNOWN</a>, <a href="/web-doxygen/docs/api/classes/token/#ab0587c46b8e1a8e18f8416b3aad58342">Token::value</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>.</p>


<p>Referenced by <a href="#a105e51dc946d1daa2914afd2bc3e72af">defaultHandleToken</a> and <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>.</p>

</div>
</div>

### handleStyleEnter() {#ab004ed65c6ab11f6ca2a4caee610bb49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocParser::handleStyleEnter (<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp; children, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277">DocStyleChange::Style</a> s, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; tagName, const <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> * attribs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Called when a style change starts. For instance a &lt;b&gt; command is encountered.</p>


<p>Declaration at line 124 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>, definition at line 622 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab004ed65c6ab11f6ca2a4caee610bb49">622</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab004ed65c6ab11f6ca2a4caee610bb49">DocParser::handleStyleEnter</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;children,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">623</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277">DocStyleChange::Style</a> s,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;tagName,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> *attribs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">624</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">625</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"tagName={}"</span><span class="doxyHighlight">,tagName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">626</span><span class="doxyLineContent"><span class="doxyHighlight">  children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.nodeStack.size(),s,tagName,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">627</span><span class="doxyLineContent"><span class="doxyHighlight">                                  <a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),attribs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">628</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad6738a87a82c364cedd836a084394960">context</a>.styleStack.push(&amp;children.<a href="/web-doxygen/docs/api/classes/growvector/#a32ffacabb2c328729f4e6ead6d96a4ad">back</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">629</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">DocNodeList::append</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/classes/growvector/#a32ffacabb2c328729f4e6ead6d96a4ad">GrowVector&lt; T &gt;::back</a>, <a href="#ad6738a87a82c364cedd836a084394960">context</a>, <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>, <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>


<p>Referenced by <a href="#a105e51dc946d1daa2914afd2bc3e72af">defaultHandleToken</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a> and <a href="#a7cbce284509ccf3109aa71472842ce4e">handleInitialStyleCommands</a>.</p>

</div>
</div>

### handleStyleLeave() {#a92d044475f815e09877c88ce15399802}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocParser::handleStyleLeave (<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp; children, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277">DocStyleChange::Style</a> s, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; tagName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Called when a style change ends. For instance a &lt;/b&gt; command is encountered.</p>


<p>Declaration at line 126 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>, definition at line 634 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a92d044475f815e09877c88ce15399802">634</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a92d044475f815e09877c88ce15399802">DocParser::handleStyleLeave</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;children,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">635</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277">DocStyleChange::Style</a> s,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;tagName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">636</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">637</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"tagName={}"</span><span class="doxyHighlight">,tagName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">638</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tagNameLower = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(tagName).<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">639</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">640</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> topStyleChange = [](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a5f6c903a8ded6b802b258c1a4eb466a6">DocStyleChangeStack</a> &amp;stack) -&gt; </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a> &amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">641</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">642</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::get&lt;DocStyleChange&gt;(*stack.top());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">643</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">644</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">645</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ad6738a87a82c364cedd836a084394960">context</a>.styleStack.empty() ||                            </span><span class="doxyHighlightComment">// no style change</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">646</span><span class="doxyLineContent"><span class="doxyHighlight">      topStyleChange(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.styleStack).style()!=s ||         </span><span class="doxyHighlightComment">// wrong style change</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">647</span><span class="doxyLineContent"><span class="doxyHighlight">      topStyleChange(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.styleStack).tagName()!=tagNameLower ||  </span><span class="doxyHighlightComment">// wrong style change</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">648</span><span class="doxyLineContent"><span class="doxyHighlight">      topStyleChange(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.styleStack).position()!=<a href="#ad6738a87a82c364cedd836a084394960">context</a>.nodeStack.size() </span><span class="doxyHighlightComment">// wrong position</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">649</span><span class="doxyLineContent"><span class="doxyHighlight">     )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">650</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">651</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ad6738a87a82c364cedd836a084394960">context</a>.styleStack.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">652</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">653</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"found &lt;/{0}&gt; tag without matching &lt;{0}&gt;"</span><span class="doxyHighlight">,tagName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">654</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">655</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (topStyleChange(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.styleStack).tagName()!=tagNameLower ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">656</span><span class="doxyLineContent"><span class="doxyHighlight">             topStyleChange(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.styleStack).style()!=s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">657</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">658</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"found &lt;/{}&gt; tag while expecting &lt;/{}&gt;"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">659</span><span class="doxyLineContent"><span class="doxyHighlight">          tagName,topStyleChange(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.styleStack).tagName());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">660</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">661</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">662</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">663</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"found &lt;/{}&gt; at different nesting level ({}) than expected ({})"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">664</span><span class="doxyLineContent"><span class="doxyHighlight">          tagName,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.nodeStack.size(),topStyleChange(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.styleStack).position());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">665</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">666</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// end the section</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">668</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">    children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a>&gt;(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">670</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.nodeStack.size(),s,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">671</span><span class="doxyLineContent"><span class="doxyHighlight">          topStyleChange(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.styleStack).tagName(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">672</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad6738a87a82c364cedd836a084394960">context</a>.styleStack.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">673</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">674</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">DocNodeList::append</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="#ad6738a87a82c364cedd836a084394960">context</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>, <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>, <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>.</p>


<p>Referenced by <a href="#a105e51dc946d1daa2914afd2bc3e72af">defaultHandleToken</a>, <a href="/web-doxygen/docs/api/classes/docpara/#aef70041ddeb0e5767c66089ba24f0afe">DocPara::handleHtmlEndTag</a> and <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a>.</p>

</div>
</div>

### handleUnclosedStyleCommands() {#af097a0f67abbe29e09a9956e88eb7642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocParser::handleUnclosedStyleCommands ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 131 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>, definition at line 753 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af097a0f67abbe29e09a9956e88eb7642">753</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af097a0f67abbe29e09a9956e88eb7642">DocParser::handleUnclosedStyleCommands</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">754</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">755</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">756</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ad6738a87a82c364cedd836a084394960">context</a>.initialStyleStack.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">757</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">758</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tagName = std::get&lt;DocStyleChange&gt;(*<a href="#ad6738a87a82c364cedd836a084394960">context</a>.initialStyleStack.top()).tagName();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">759</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fileName = std::get&lt;DocStyleChange&gt;(*<a href="#ad6738a87a82c364cedd836a084394960">context</a>.initialStyleStack.top()).fileName();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">760</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr = std::get&lt;DocStyleChange&gt;(*<a href="#ad6738a87a82c364cedd836a084394960">context</a>.initialStyleStack.top()).lineNr();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">761</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad6738a87a82c364cedd836a084394960">context</a>.initialStyleStack.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">762</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af097a0f67abbe29e09a9956e88eb7642">handleUnclosedStyleCommands</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">763</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lineNr != -1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">764</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">765</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">766</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightStringLiteral">"end of comment block while expecting "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">767</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightStringLiteral">"command &lt;/{}&gt; (Probable start '{}' at line {})"</span><span class="doxyHighlight">,tagName, fileName, lineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">768</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">769</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">770</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">771</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">772</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightStringLiteral">"end of comment block while expecting command &lt;/{}&gt;"</span><span class="doxyHighlight">,tagName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">773</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">774</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">775</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="#ad6738a87a82c364cedd836a084394960">context</a>, <a href="#af097a0f67abbe29e09a9956e88eb7642">handleUnclosedStyleCommands</a>, <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>.</p>


<p>Referenced by <a href="#af097a0f67abbe29e09a9956e88eb7642">handleUnclosedStyleCommands</a>, <a href="/web-doxygen/docs/api/classes/docroot/#a860207dd6bee34648ddbfd55e3ddaff8">DocRoot::parse</a> and <a href="/web-doxygen/docs/api/classes/doctext/#aada5a740aa0832964895e683340b76a5">DocText::parse</a>.</p>

</div>
</div>

### internalValidatingParseDoc() {#a6d276e7995db319294ea1fb2bc76459e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Token DocParser::internalValidatingParseDoc (<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp; children, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; doc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 104 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>, definition at line 1614 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6d276e7995db319294ea1fb2bc76459e">1614</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/token">Token</a> <a href="#a6d276e7995db319294ea1fb2bc76459e">DocParser::internalValidatingParseDoc</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,<a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;children,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1615</span><span class="doxyLineContent"><span class="doxyHighlight">                                    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;doc)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1616</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1617</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1618</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/token">Token</a> retval = Token::make_RetVal_OK();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1619</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1620</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> retval;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1621</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1622</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.init(doc.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.markdownSupport,<a href="#ad6738a87a82c364cedd836a084394960">context</a>.insideHtmlLink);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1623</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1624</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// first parse any number of paragraphs</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1625</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isFirst=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1626</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docpara">DocPara</a> *lastPar=!children.<a href="/web-doxygen/docs/api/classes/growvector/#a4e81684f665c9a1a38b5e16cfbe31d41">empty</a>() ? std::get_if&lt;DocPara&gt;(&amp;children.<a href="/web-doxygen/docs/api/classes/growvector/#a32ffacabb2c328729f4e6ead6d96a4ad">back</a>()): </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1627</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lastPar)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1628</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightComment">// last child item was a paragraph</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1629</span><span class="doxyLineContent"><span class="doxyHighlight">    isFirst=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1630</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1631</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">do</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1632</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1633</span><span class="doxyLineContent"><span class="doxyHighlight">    children.<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docpara">DocPara</a>&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1634</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/docpara">DocPara</a> *par  = children.<a href="/web-doxygen/docs/api/structs/docnodelist/#ae3a5d9b77d64e18e642163cceac5fa2e">get_last</a>&lt;<a href="/web-doxygen/docs/api/classes/docpara">DocPara</a>&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1635</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isFirst) { par-&gt;markFirst(); isFirst=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1636</span><span class="doxyLineContent"><span class="doxyHighlight">    retval=par-&gt;parse();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1637</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!par-&gt;isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1638</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1639</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lastPar) lastPar-&gt;<a href="/web-doxygen/docs/api/classes/docpara/#a569bc5841973bac45491c977814f62e0">markLast</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1640</span><span class="doxyLineContent"><span class="doxyHighlight">      lastPar=par;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1641</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1642</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1643</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1644</span><span class="doxyLineContent"><span class="doxyHighlight">      children.<a href="/web-doxygen/docs/api/classes/growvector/#a47b0fff0a3347fd5134ff7f121511d5f">pop_back</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1645</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1646</span><span class="doxyLineContent"><span class="doxyHighlight">  } </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (retval.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_NEWPARA));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1647</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lastPar) lastPar-&gt;<a href="/web-doxygen/docs/api/classes/docpara/#a569bc5841973bac45491c977814f62e0">markLast</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1648</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1649</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"isFirst={} isLast={}"</span><span class="doxyHighlight">,lastPar?lastPar-&gt;<a href="/web-doxygen/docs/api/classes/docpara/#a819aff0142426458d430f63e216bfb74">isFirst</a>():-1,lastPar?lastPar-&gt;<a href="/web-doxygen/docs/api/classes/docpara/#a32a474477c8d44117a82964eeac50e53">isLast</a>():-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1650</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> retval;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1651</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">DocNodeList::append</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/classes/growvector/#a32ffacabb2c328729f4e6ead6d96a4ad">GrowVector&lt; T &gt;::back</a>, <a href="#ad6738a87a82c364cedd836a084394960">context</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/growvector/#a4e81684f665c9a1a38b5e16cfbe31d41">GrowVector&lt; T &gt;::empty</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/structs/docnodelist/#ae3a5d9b77d64e18e642163cceac5fa2e">DocNodeList::get_last</a>, <a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">Token::is</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a819aff0142426458d430f63e216bfb74">DocPara::isFirst</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a32a474477c8d44117a82964eeac50e53">DocPara::isLast</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a569bc5841973bac45491c977814f62e0">DocPara::markLast</a>, <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>, <a href="/web-doxygen/docs/api/classes/growvector/#a47b0fff0a3347fd5134ff7f121511d5f">GrowVector&lt; T &gt;::pop_back</a>, <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a0eecb8116d4410392244f76fb8c209e6">DocPara::handleInheritDoc</a>, <a href="/web-doxygen/docs/api/classes/docref/#a6004b78783411b8c5752371572afa3ef">DocRef::parse</a>, <a href="/web-doxygen/docs/api/classes/docxrefitem/#acfb3aacf4b559a4b9fb4fb5b2dc960bc">DocXRefItem::parse</a>, <a href="/web-doxygen/docs/api/classes/doctitle/#a410946c3855fd51f18485d6e3dcce59b">DocTitle::parseFromString</a> and <a href="/web-doxygen/docs/api/classes/docsimplesect/#a7eb70bb58c30a5dab96c862583503b7e">DocSimpleSect::parseRcs</a>.</p>

</div>
</div>

### popContext() {#aa05ab8dc59dfa50633146bdba08db5f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocParser::popContext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 102 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>, definition at line 74 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa05ab8dc59dfa50633146bdba08db5f0">74</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa05ab8dc59dfa50633146bdba08db5f0">DocParser::popContext</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ctx = <a href="#a15a2a88e43e50fa4d28b5675c97ec137">contextStack</a>.top();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad6738a87a82c364cedd836a084394960">context</a> = ctx;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.setLineNr(ctx.lineNo);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a15a2a88e43e50fa4d28b5675c97ec137">contextStack</a>.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.popContext();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad6738a87a82c364cedd836a084394960">context</a>.token = <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.token();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//QCString indent;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//indent.fill(' ',contextStack.size()*2+2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("%sdocParserPopContext() count=%zu\n",qPrint(indent),context.nodeStack.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#ad6738a87a82c364cedd836a084394960">context</a>, <a href="#a15a2a88e43e50fa4d28b5675c97ec137">contextStack</a> and <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a0eecb8116d4410392244f76fb8c209e6">DocPara::handleInheritDoc</a>, <a href="/web-doxygen/docs/api/classes/docref/#a6004b78783411b8c5752371572afa3ef">DocRef::parse</a>, <a href="/web-doxygen/docs/api/classes/docxrefitem/#acfb3aacf4b559a4b9fb4fb5b2dc960bc">DocXRefItem::parse</a>, <a href="/web-doxygen/docs/api/classes/doctitle/#a410946c3855fd51f18485d6e3dcce59b">DocTitle::parseFromString</a> and <a href="/web-doxygen/docs/api/classes/docsimplesect/#a7eb70bb58c30a5dab96c862583503b7e">DocSimpleSect::parseRcs</a>.</p>

</div>
</div>

### processCopyDoc() {#a4b7d1c2724099f28c4f3a4c56c52d912}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocParser::processCopyDoc (const char * data, size_t &amp; len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 106 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>, definition at line 1809 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4b7d1c2724099f28c4f3a4c56c52d912">1809</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a4b7d1c2724099f28c4f3a4c56c52d912">DocParser::processCopyDoc</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *data,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> &amp;len)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1810</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1811</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"data={} len={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(data),len);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1812</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/growbuf">GrowBuf</a> buf;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1813</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1814</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr = <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1815</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;len)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1816</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1817</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = data[i];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1818</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// look for a command</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1819</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1820</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isBrief=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1821</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> j=<a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ae291c1cbee2c4f673156c84666e768f7">isCopyBriefOrDetailsCmd</a>(data,i,len,isBrief);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1822</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (j&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1823</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1824</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// skip whitespace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1825</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (j&lt;len &amp;&amp; (data[j]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || data[j]==</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">)) j++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1826</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// extract the argument</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1827</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> = <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a3e870f07917a178b708537e85177a6d0">extractCopyDocId</a>(data,j,len);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1828</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *def = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1829</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> doc,brief;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1830</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("resolving docs='%s'\n",qPrint(id));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1831</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> found = <a href="#aa75d3dc0424c6b364222f7f357406e62">findDocsForMemberOrCompound</a>(</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,&amp;doc,&amp;brief,&amp;def);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1832</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (found &amp;&amp; def-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1833</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1834</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1835</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightStringLiteral">"@copy{} or @copydoc target '{}' found but is from a tag file, skipped"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1836</span><span class="doxyLineContent"><span class="doxyHighlight">               isBrief?</span><span class="doxyHighlightStringLiteral">"brief"</span><span class="doxyHighlight">:</span><span class="doxyHighlightStringLiteral">"details"</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1837</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1838</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (found)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1839</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1840</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//printf("found it def=%p brief='%s' doc='%s' isBrief=%d\n",def,qPrint(brief),qPrint(doc),isBrief);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1841</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = std::find(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.copyStack.begin(),<a href="#ad6738a87a82c364cedd836a084394960">context</a>.copyStack.end(),def);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1842</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it==<a href="#ad6738a87a82c364cedd836a084394960">context</a>.copyStack.end()) </span><span class="doxyHighlightComment">// definition not parsed earlier</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1843</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1844</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> orgFileName = <a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1845</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#ad6738a87a82c364cedd836a084394960">context</a>.copyStack.push_back(def);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1846</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> addDocs = [&amp;](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file_,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> line_,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;doc_)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1847</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1848</span><span class="doxyLineContent"><span class="doxyHighlight">              buf.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(</span><span class="doxyHighlightStringLiteral">" \\ifile \""</span><span class="doxyHighlight">+file_+</span><span class="doxyHighlightStringLiteral">"\" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1849</span><span class="doxyLineContent"><span class="doxyHighlight">              buf.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(</span><span class="doxyHighlightStringLiteral">"\\iline "</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>().setNum(line_)+</span><span class="doxyHighlightStringLiteral">" \\ilinebr "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1850</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len_ = doc_.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1851</span><span class="doxyLineContent"><span class="doxyHighlight">              buf.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(<a href="#a4b7d1c2724099f28c4f3a4c56c52d912">processCopyDoc</a>(doc_.data(),len_));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1852</span><span class="doxyLineContent"><span class="doxyHighlight">            };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1853</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isBrief)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1854</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1855</span><span class="doxyLineContent"><span class="doxyHighlight">              addDocs(def-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac74d77550941a8f568ea56fecc30c873">briefFile</a>(),def-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8073d399d39c43e66a4b487b3e06ade1">briefLine</a>(),brief);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1856</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1857</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1858</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1859</span><span class="doxyLineContent"><span class="doxyHighlight">              addDocs(def-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a00915f52f3b708bec07aab2b44f03d34">docFile</a>(),def-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a26a4a6e3578aa6c81b2d6d77a1ce694f">docLine</a>(),doc);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1860</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (def-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea422b8b811bcf8869a67732f9829d005b">Definition::TypeMember</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1861</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1862</span><span class="doxyLineContent"><span class="doxyHighlight">                </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md = <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>(def);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1863</span><span class="doxyLineContent"><span class="doxyHighlight">                </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;docArgList = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#aaa1f125e42e876b4e552f71a4748b42f">templateMaster</a>() ?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1864</span><span class="doxyLineContent"><span class="doxyHighlight">                    md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#aaa1f125e42e876b4e552f71a4748b42f">templateMaster</a>()-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">argumentList</a>() :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1865</span><span class="doxyLineContent"><span class="doxyHighlight">                    md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">argumentList</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1866</span><span class="doxyLineContent"><span class="doxyHighlight">                buf.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(<a href="/web-doxygen/docs/api/files/src/util-cpp/#ae53504faf9e304d72ec1f2e38f3c9013">inlineArgListToDoc</a>(docArgList));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1867</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1868</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1869</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#ad6738a87a82c364cedd836a084394960">context</a>.copyStack.pop_back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1870</span><span class="doxyLineContent"><span class="doxyHighlight">            buf.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(</span><span class="doxyHighlightStringLiteral">" \\ilinebr \\ifile \""</span><span class="doxyHighlight">+<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName+</span><span class="doxyHighlightStringLiteral">"\" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1871</span><span class="doxyLineContent"><span class="doxyHighlight">            buf.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(</span><span class="doxyHighlightStringLiteral">"\\iline "</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>().setNum(lineNr)+</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1872</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1873</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1874</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1875</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1876</span><span class="doxyLineContent"><span class="doxyHighlight">                 </span><span class="doxyHighlightStringLiteral">"Found recursive @copy{} or @copydoc relation for argument '{}'."</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1877</span><span class="doxyLineContent"><span class="doxyHighlight">                 isBrief?</span><span class="doxyHighlightStringLiteral">"brief"</span><span class="doxyHighlight">:</span><span class="doxyHighlightStringLiteral">"details"</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1878</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1879</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1880</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1881</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1882</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1883</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightStringLiteral">"@copy{} or @copydoc target '{}' not found"</span><span class="doxyHighlight">, isBrief?</span><span class="doxyHighlightStringLiteral">"brief"</span><span class="doxyHighlight">:</span><span class="doxyHighlightStringLiteral">"details"</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1884</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1885</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// skip over command</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1886</span><span class="doxyLineContent"><span class="doxyHighlight">        i=j;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1887</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1888</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1889</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1890</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> endMarker;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1891</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> k = <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a8c308bc53d34b79a49d251a8b7cc2666">isVerbatimSection</a>(data,i,len,endMarker);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1892</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (k&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1893</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1894</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> orgPos = i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1895</span><span class="doxyLineContent"><span class="doxyHighlight">          i=<a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a45928a3aa04b29c259685a5d3f6cbf4d">skipToEndMarker</a>(data,k,len,endMarker);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1896</span><span class="doxyLineContent"><span class="doxyHighlight">          buf.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(data+orgPos,i-orgPos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1897</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// TODO: adjust lineNr</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1898</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1899</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1900</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1901</span><span class="doxyLineContent"><span class="doxyHighlight">          buf.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1902</span><span class="doxyLineContent"><span class="doxyHighlight">          i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1903</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1904</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1905</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1906</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// not a command, just copy</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1907</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1908</span><span class="doxyLineContent"><span class="doxyHighlight">      buf.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1909</span><span class="doxyLineContent"><span class="doxyHighlight">      i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1910</span><span class="doxyLineContent"><span class="doxyHighlight">      lineNr += (c==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) ? 1 : 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1911</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1912</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1913</span><span class="doxyLineContent"><span class="doxyHighlight">  len = buf.<a href="/web-doxygen/docs/api/classes/growbuf/#a1a0ecc7a79837ed02005befe12d49994">getPos</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1914</span><span class="doxyLineContent"><span class="doxyHighlight">  buf.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1915</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(buf.<a href="/web-doxygen/docs/api/classes/growbuf/#a88d6408723b8c1a58187f24da81dfd5e">get</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1916</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> buf.<a href="/web-doxygen/docs/api/classes/growbuf/#a88d6408723b8c1a58187f24da81dfd5e">get</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1917</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">GrowBuf::addChar</a>, <a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">GrowBuf::addStr</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">MemberDef::argumentList</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/classes/definition/#ac74d77550941a8f568ea56fecc30c873">Definition::briefFile</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8073d399d39c43e66a4b487b3e06ade1">Definition::briefLine</a>, <a href="#ad6738a87a82c364cedd836a084394960">context</a>, <a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">Definition::definitionType</a>, <a href="/web-doxygen/docs/api/classes/definition/#a00915f52f3b708bec07aab2b44f03d34">Definition::docFile</a>, <a href="/web-doxygen/docs/api/classes/definition/#a26a4a6e3578aa6c81b2d6d77a1ce694f">Definition::docLine</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a3e870f07917a178b708537e85177a6d0">extractCopyDocId</a>, <a href="#aa75d3dc0424c6b364222f7f357406e62">findDocsForMemberOrCompound</a>, <a href="/web-doxygen/docs/api/classes/growbuf/#a88d6408723b8c1a58187f24da81dfd5e">GrowBuf::get</a>, <a href="/web-doxygen/docs/api/classes/growbuf/#a1a0ecc7a79837ed02005befe12d49994">GrowBuf::getPos</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae53504faf9e304d72ec1f2e38f3c9013">inlineArgListToDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ae291c1cbee2c4f673156c84666e768f7">isCopyBriefOrDetailsCmd</a>, <a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">Definition::isReference</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a8c308bc53d34b79a49d251a8b7cc2666">isVerbatimSection</a>, <a href="#a4b7d1c2724099f28c4f3a4c56c52d912">processCopyDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a45928a3aa04b29c259685a5d3f6cbf4d">skipToEndMarker</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#aaa1f125e42e876b4e552f71a4748b42f">MemberDef::templateMaster</a>, <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea422b8b811bcf8869a67732f9829d005b">Definition::TypeMember</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>.</p>


<p>Referenced by <a href="#a4b7d1c2724099f28c4f3a4c56c52d912">processCopyDoc</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>.</p>

</div>
</div>

### pushContext() {#af278dab51b58124b32a625d709a29d97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocParser::pushContext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 101 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>, definition at line 60 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af278dab51b58124b32a625d709a29d97">60</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af278dab51b58124b32a625d709a29d97">DocParser::pushContext</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//QCString indent;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//indent.fill(' ',contextStack.size()*2+2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("%sdocParserPushContext() count=%zu\n",qPrint(indent),context.nodeStack.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.pushContext();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a15a2a88e43e50fa4d28b5675c97ec137">contextStack</a>.emplace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ctx = <a href="#a15a2a88e43e50fa4d28b5675c97ec137">contextStack</a>.top();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">  ctx = <a href="#ad6738a87a82c364cedd836a084394960">context</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">  ctx.lineNo = <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad6738a87a82c364cedd836a084394960">context</a>.token = <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.token();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#ad6738a87a82c364cedd836a084394960">context</a>, <a href="#a15a2a88e43e50fa4d28b5675c97ec137">contextStack</a> and <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a0eecb8116d4410392244f76fb8c209e6">DocPara::handleInheritDoc</a>, <a href="/web-doxygen/docs/api/classes/docref/#a6004b78783411b8c5752371572afa3ef">DocRef::parse</a>, <a href="/web-doxygen/docs/api/classes/docxrefitem/#acfb3aacf4b559a4b9fb4fb5b2dc960bc">DocXRefItem::parse</a>, <a href="/web-doxygen/docs/api/classes/doctitle/#a410946c3855fd51f18485d6e3dcce59b">DocTitle::parseFromString</a> and <a href="/web-doxygen/docs/api/classes/docsimplesect/#a7eb70bb58c30a5dab96c862583503b7e">DocSimpleSect::parseRcs</a>.</p>

</div>
</div>

### readTextFileByName() {#a5340de5ad1c86c5c2d03b02e721b51e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocParser::readTextFileByName (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 138 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>, definition at line 1655 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5340de5ad1c86c5c2d03b02e721b51e0">1655</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5340de5ad1c86c5c2d03b02e721b51e0">DocParser::readTextFileByName</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1656</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1657</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"file={} text={}"</span><span class="doxyHighlight">,file,text);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1658</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ambig = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1659</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> filePath = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a103513ad1b948e1fc70ba3a98c761e31">findFilePath</a>(file,ambig);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1660</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!filePath.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1661</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1662</span><span class="doxyLineContent"><span class="doxyHighlight">    text = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a71d0079fa5936a41b6ff2d1ca5eb5480">fileToString</a>(filePath,<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(FILTER_SOURCE_FILES));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1663</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ambig)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1664</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1665</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"included file name '{}' is ambiguous"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1666</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"Possible candidates:\n{}"</span><span class="doxyHighlight">,file, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a70d0b468521b0304252fb659f3b15e24">showFileDefMatches</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#ae1bf779155bea73ec696cba27e640e66">Doxygen::exampleNameLinkedMap</a>,file));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1667</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1668</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1669</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1670</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1671</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="#ad6738a87a82c364cedd836a084394960">context</a>.fileName,<a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.getLineNr(),</span><span class="doxyHighlightStringLiteral">"included file '{}' is not found. "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1672</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightStringLiteral">"Check your EXAMPLE_PATH"</span><span class="doxyHighlight">,file);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1673</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1674</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="#ad6738a87a82c364cedd836a084394960">context</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#ae1bf779155bea73ec696cba27e640e66">Doxygen::exampleNameLinkedMap</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a71d0079fa5936a41b6ff2d1ca5eb5480">fileToString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a103513ad1b948e1fc70ba3a98c761e31">findFilePath</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a70d0b468521b0304252fb659f3b15e24">showFileDefMatches</a>, <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docinclude/#a191446e0b57311d58cf1ef51a91417ee">DocInclude::parse</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### context {#ad6738a87a82c364cedd836a084394960}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocParserContext DocParser::context</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad6738a87a82c364cedd836a084394960">141</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/docparsercontext">DocParserContext</a>               <a href="#ad6738a87a82c364cedd836a084394960">context</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docsimplesect/#ae538f74c2d44222c9a45ef304c89e041">DocSimpleSect::appendLinkWord</a>, <a href="#ad426893f12b2bc919bc61b3d95e8f471">checkArgumentName</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#adbe932c521ee8cde5ccc5cdca438fa5f">checkIfHtmlEndTagEndsAutoList</a>, <a href="#a3fce1509c4bb1494537fe53ea294fa8c">checkRetvalName</a>, <a href="#a9ca6efdbb8e10b7908ad6906f26ff1bd">checkUnOrMultipleDocumentedParams</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a81d4810c1b7d0715b60aea2ac421bfd1">createRef</a>, <a href="#ae88d59b299df415c0c2028d863288599">defaultHandleTitleAndSize</a>, <a href="#a105e51dc946d1daa2914afd2bc3e72af">defaultHandleToken</a>, <a href="#afa9541b35f25f2f63a6f5ff338967f22">errorHandleDefaultToken</a>, <a href="#a3d46e03d176edeb9ec7044f80ffe3a81">findAndCopyImage</a>, <a href="#aa75d3dc0424c6b364222f7f357406e62">findDocsForMemberOrCompound</a>, <a href="#a6a6c955c9001d67e4b722038bfc5f16b">handleAHref</a>, <a href="#adf24a6cf025048b8a3235ca2c897dc06">handleAnchor</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a10a22fde1124375bf9f58cbea8eadf84">DocPara::handleCite</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a22c8bd336d14e9baf38a3ffcec3d0476">DocPara::handleDoxyConfig</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a724e489c954b750341d697b29e98033f">DocPara::handleEmoji</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a2c5971c7bbbb5bd01e02ac7d93600281">DocPara::handleFile</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a3a7bca787f76b9c7cd05429fe738e790">DocPara::handleIFile</a>, <a href="#aa923af2c2ca8d81fa9b65a6fa1e65a83">handleImage</a>, <a href="#ae3321ce556544cc7281b783f2b250be4">handleImg</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1bb9289a32b8c06de83c728786bb0669">DocPara::handleInclude</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a7c235343a063e005bfee6c68b14a835e">DocPara::handleIncludeOperator</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a0eecb8116d4410392244f76fb8c209e6">DocPara::handleInheritDoc</a>, <a href="#a7cbce284509ccf3109aa71472842ce4e">handleInitialStyleCommands</a>, <a href="#a334b7286f0a4445d85743cce35a3c090">handleInternalRef</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a0bff680b96bc9c76b2228affeaa90bbb">DocPara::handleLink</a>, <a href="#a2b2971ad53e50d90ca4affca6a6e1d67">handleLinkedWord</a>, <a href="#a367fe5ccd7e0378c2e5c94df6e60dd0d">handleParameterType</a>, <a href="#a94f06b2f61c71069d46589a7cd4f7b6b">handlePendingStyleCommands</a>, <a href="#ab8ac10aa71d5d6c021a6e2f08df318f8">handlePrefix</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a8541b3718d4e34888ecfcfc218f5c331">DocPara::handleRef</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a2bb5ccde078a4388fbd245dd98b466bf">DocPara::handleSection</a>, <a href="/web-doxygen/docs/api/classes/docpara/#ad112877bd5902d918781a9f2d5e0f703">DocPara::handleShowDate</a>, <a href="/web-doxygen/docs/api/classes/docpara/#af621e2f0d576fff189b3d94552edec15">DocPara::handleStartCode</a>, <a href="#abf46a000544ae1a4f45df6430cd3e6bf">handleStyleArgument</a>, <a href="#ab004ed65c6ab11f6ca2a4caee610bb49">handleStyleEnter</a>, <a href="#a92d044475f815e09877c88ce15399802">handleStyleLeave</a>, <a href="#af097a0f67abbe29e09a9956e88eb7642">handleUnclosedStyleCommands</a>, <a href="/web-doxygen/docs/api/classes/docpara/#ae14027652a29ff9eda818d4ba6098329">DocPara::handleXRefItem</a>, <a href="/web-doxygen/docs/api/classes/docpara/#af9a6952aca6a271fde9a883efd65cc58">DocPara::injectToken</a>, <a href="#a6d276e7995db319294ea1fb2bc76459e">internalValidatingParseDoc</a>, <a href="/web-doxygen/docs/api/classes/docautolist/#a8eef0f06619e7a80df0c5dd10e83cb2b">DocAutoList::parse</a>, <a href="/web-doxygen/docs/api/classes/dochref/#a2a9332a0da85f6e0596e3d46cea53fe5">DocHRef::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldescdata/#ab176f44cd7bc955df0c352bd714e4e1c">DocHtmlDescData::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldesclist/#a74ff0b5b4a4173213a643d6897d7f9c2">DocHtmlDescList::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldesctitle/#a92b042aef732d7da8cc71182810e76c5">DocHtmlDescTitle::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlheader/#a5f57a370972a9ce3f7aa769973c5d2e8">DocHtmlHeader::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#ab8fc1655d43a50f996a8878eb66e0dc7">DocHtmlList::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#afbeab8f03e2ef431c05b8d3bcb6291aa">DocHtmlRow::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmltable/#a6f4ae9d09701b93305b6e90260bc5662">DocHtmlTable::parse</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a191446e0b57311d58cf1ef51a91417ee">DocInclude::parse</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a468e20836d11e4cd9e62159e169acc68">DocIncOperator::parse</a>, <a href="/web-doxygen/docs/api/classes/docindexentry/#a788ff313987522a9be055abe2fdb1592">DocIndexEntry::parse</a>, <a href="/web-doxygen/docs/api/classes/docinternal/#ad783a8507dd1e64ad38a889d9fa7a851">DocInternal::parse</a>, <a href="/web-doxygen/docs/api/classes/doclink/#aeb676914fb893fa31c99b39c1f7bb6d3">DocLink::parse</a>, <a href="/web-doxygen/docs/api/classes/docpara/#aafc94d2ed7856e4a11e404e2ee05fb40">DocPara::parse</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a98345755b6311bcc4129bd7ee14759f1">DocParamList::parse</a>, <a href="/web-doxygen/docs/api/classes/docref/#a6004b78783411b8c5752371572afa3ef">DocRef::parse</a>, <a href="/web-doxygen/docs/api/classes/docroot/#a860207dd6bee34648ddbfd55e3ddaff8">DocRoot::parse</a>, <a href="/web-doxygen/docs/api/classes/docsecreflist/#a9b279250711bb61d12bff4c34e70d2f3">DocSecRefList::parse</a>, <a href="/web-doxygen/docs/api/classes/docsection/#a9b6c66c2f51de17bc5748754090c1e41">DocSection::parse</a>, <a href="/web-doxygen/docs/api/classes/doctext/#aada5a740aa0832964895e683340b76a5">DocText::parse</a>, <a href="/web-doxygen/docs/api/classes/doctitle/#a410946c3855fd51f18485d6e3dcce59b">DocTitle::parseFromString</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a7eb70bb58c30a5dab96c862583503b7e">DocSimpleSect::parseRcs</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#a53b4acdb633ea0dea82a74cafd533e31">DocHtmlList::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#a10bb2141d4a0d7867a97d829794184e3">DocHtmlRow::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmltable/#a2a913b8204fc7637dea2f3783da7b1a2">DocHtmlTable::parseXml</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a79bb36905dd1401288d55e12ee52ce03">DocParamList::parseXml</a>, <a href="#aa05ab8dc59dfa50633146bdba08db5f0">popContext</a>, <a href="#a4b7d1c2724099f28c4f3a4c56c52d912">processCopyDoc</a>, <a href="#af278dab51b58124b32a625d709a29d97">pushContext</a>, <a href="#a5340de5ad1c86c5c2d03b02e721b51e0">readTextFileByName</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>.</p>

</div>
</div>

### contextStack {#a15a2a88e43e50fa4d28b5675c97ec137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::stack&lt; DocParserContext &gt; DocParser::contextStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a15a2a88e43e50fa4d28b5675c97ec137">140</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::stack&lt; DocParserContext &gt; <a href="#a15a2a88e43e50fa4d28b5675c97ec137">contextStack</a>;</span></span></div>

</div>


<p>Referenced by <a href="#aa05ab8dc59dfa50633146bdba08db5f0">popContext</a> and <a href="#af278dab51b58124b32a625d709a29d97">pushContext</a>.</p>

</div>
</div>

### tokenizer {#a31ff77e4308ae2b7691a8381736201d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocTokenizer DocParser::tokenizer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a31ff77e4308ae2b7691a8381736201d1">142</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/doctokenizer">DocTokenizer</a>                   <a href="#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#adbe932c521ee8cde5ccc5cdca438fa5f">checkIfHtmlEndTagEndsAutoList</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a81d4810c1b7d0715b60aea2ac421bfd1">createRef</a>, <a href="#ae88d59b299df415c0c2028d863288599">defaultHandleTitleAndSize</a>, <a href="#a105e51dc946d1daa2914afd2bc3e72af">defaultHandleToken</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a0fc0d3e4ca95dd0dc254d0efb1fd045a">docFindSections</a>, <a href="#afa9541b35f25f2f63a6f5ff338967f22">errorHandleDefaultToken</a>, <a href="#a3d46e03d176edeb9ec7044f80ffe3a81">findAndCopyImage</a>, <a href="#a6a6c955c9001d67e4b722038bfc5f16b">handleAHref</a>, <a href="#adf24a6cf025048b8a3235ca2c897dc06">handleAnchor</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a10a22fde1124375bf9f58cbea8eadf84">DocPara::handleCite</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a22c8bd336d14e9baf38a3ffcec3d0476">DocPara::handleDoxyConfig</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a724e489c954b750341d697b29e98033f">DocPara::handleEmoji</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a2c5971c7bbbb5bd01e02ac7d93600281">DocPara::handleFile</a>, <a href="/web-doxygen/docs/api/classes/docpara/#aef70041ddeb0e5767c66089ba24f0afe">DocPara::handleHtmlEndTag</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a3a7bca787f76b9c7cd05429fe738e790">DocPara::handleIFile</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a8cdd911ef9ea557d2fd2a0f034efcaa4">DocPara::handleILine</a>, <a href="#aa923af2c2ca8d81fa9b65a6fa1e65a83">handleImage</a>, <a href="#ae3321ce556544cc7281b783f2b250be4">handleImg</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1bb9289a32b8c06de83c728786bb0669">DocPara::handleInclude</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a7c235343a063e005bfee6c68b14a835e">DocPara::handleIncludeOperator</a>, <a href="#a334b7286f0a4445d85743cce35a3c090">handleInternalRef</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a0bff680b96bc9c76b2228affeaa90bbb">DocPara::handleLink</a>, <a href="#a2b2971ad53e50d90ca4affca6a6e1d67">handleLinkedWord</a>, <a href="#ab8ac10aa71d5d6c021a6e2f08df318f8">handlePrefix</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a8541b3718d4e34888ecfcfc218f5c331">DocPara::handleRef</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a2bb5ccde078a4388fbd245dd98b466bf">DocPara::handleSection</a>, <a href="/web-doxygen/docs/api/classes/docpara/#ad112877bd5902d918781a9f2d5e0f703">DocPara::handleShowDate</a>, <a href="/web-doxygen/docs/api/classes/docpara/#af621e2f0d576fff189b3d94552edec15">DocPara::handleStartCode</a>, <a href="#abf46a000544ae1a4f45df6430cd3e6bf">handleStyleArgument</a>, <a href="#ab004ed65c6ab11f6ca2a4caee610bb49">handleStyleEnter</a>, <a href="#a92d044475f815e09877c88ce15399802">handleStyleLeave</a>, <a href="#af097a0f67abbe29e09a9956e88eb7642">handleUnclosedStyleCommands</a>, <a href="/web-doxygen/docs/api/classes/docpara/#ae14027652a29ff9eda818d4ba6098329">DocPara::handleXRefItem</a>, <a href="#a6d276e7995db319294ea1fb2bc76459e">internalValidatingParseDoc</a>, <a href="/web-doxygen/docs/api/classes/docautolist/#a8eef0f06619e7a80df0c5dd10e83cb2b">DocAutoList::parse</a>, <a href="/web-doxygen/docs/api/classes/dochref/#a2a9332a0da85f6e0596e3d46cea53fe5">DocHRef::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcaption/#a4f952166357e3d6d33312208d4a768f3">DocHtmlCaption::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldesclist/#a74ff0b5b4a4173213a643d6897d7f9c2">DocHtmlDescList::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldesctitle/#a92b042aef732d7da8cc71182810e76c5">DocHtmlDescTitle::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlheader/#a5f57a370972a9ce3f7aa769973c5d2e8">DocHtmlHeader::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#ab8fc1655d43a50f996a8878eb66e0dc7">DocHtmlList::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#afbeab8f03e2ef431c05b8d3bcb6291aa">DocHtmlRow::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlsummary/#a4768457c4357b86443890d950cb3e740">DocHtmlSummary::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmltable/#a6f4ae9d09701b93305b6e90260bc5662">DocHtmlTable::parse</a>, <a href="/web-doxygen/docs/api/classes/docindexentry/#a788ff313987522a9be055abe2fdb1592">DocIndexEntry::parse</a>, <a href="/web-doxygen/docs/api/classes/docinternalref/#ab9cc38fde444889a618974f396bf36ed">DocInternalRef::parse</a>, <a href="/web-doxygen/docs/api/classes/doclink/#aeb676914fb893fa31c99b39c1f7bb6d3">DocLink::parse</a>, <a href="/web-doxygen/docs/api/classes/docpara/#aafc94d2ed7856e4a11e404e2ee05fb40">DocPara::parse</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a98345755b6311bcc4129bd7ee14759f1">DocParamList::parse</a>, <a href="/web-doxygen/docs/api/classes/docref/#a6004b78783411b8c5752371572afa3ef">DocRef::parse</a>, <a href="/web-doxygen/docs/api/classes/docroot/#a860207dd6bee34648ddbfd55e3ddaff8">DocRoot::parse</a>, <a href="/web-doxygen/docs/api/classes/docsecrefitem/#a35c9d6d150e7faaa88ea9ddfbeadb777">DocSecRefItem::parse</a>, <a href="/web-doxygen/docs/api/classes/docsecreflist/#a9b279250711bb61d12bff4c34e70d2f3">DocSecRefList::parse</a>, <a href="/web-doxygen/docs/api/classes/doctext/#aada5a740aa0832964895e683340b76a5">DocText::parse</a>, <a href="/web-doxygen/docs/api/classes/doctitle/#a12306a4f4de4310c8201fac9d29eb627">DocTitle::parse</a>, <a href="/web-doxygen/docs/api/classes/docvhdlflow/#afe55c9c5bf1a823e78d6aa3ea3f0777b">DocVhdlFlow::parse</a>, <a href="/web-doxygen/docs/api/classes/doctitle/#a410946c3855fd51f18485d6e3dcce59b">DocTitle::parseFromString</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#a53b4acdb633ea0dea82a74cafd533e31">DocHtmlList::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#a10bb2141d4a0d7867a97d829794184e3">DocHtmlRow::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmltable/#a2a913b8204fc7637dea2f3783da7b1a2">DocHtmlTable::parseXml</a>, <a href="#aa05ab8dc59dfa50633146bdba08db5f0">popContext</a>, <a href="#a4b7d1c2724099f28c4f3a4c56c52d912">processCopyDoc</a>, <a href="#af278dab51b58124b32a625d709a29d97">pushContext</a>, <a href="#a5340de5ad1c86c5c2d03b02e721b51e0">readTextFileByName</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a></li>
<li><a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
