---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/docroot
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DocRoot` Class Reference

<p>Root node of documentation tree. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class DocRoot { ... }
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
<p>Base class for nodes with children. <a href="/web-doxygen/docs/api/classes/doccompoundnode/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a895591f00a7f0c35ddc283bee7e395f8">DocRoot</a> (DocParser *parser, bool indent, bool sl)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a860207dd6bee34648ddbfd55e3ddaff8">parse</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65e7fbdda6784c769c6333adc1fe629c">indent</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32e7c733315cae51633409dfaaf6020f">singleLine</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade1a2bc91120fb42b66313298b37199d">isEmpty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbf9ad3d0105c6d110954381037a4100">m_indent</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67e39cfe41312efdf577e2f65d6b5d38">m_singleLine</a> = false</td>
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

<p>Root node of documentation tree.</p>

<p>Definition at line 1312 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DocRoot() {#a895591f00a7f0c35ddc283bee7e395f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocRoot::DocRoot (<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> * parser, bool indent, bool sl)</td>
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



<p>Definition at line 1315 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a895591f00a7f0c35ddc283bee7e395f8">1315</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a895591f00a7f0c35ddc283bee7e395f8">DocRoot</a>(<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a65e7fbdda6784c769c6333adc1fe629c">indent</a>,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> sl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1316</span><span class="doxyLineContent"><span class="doxyHighlight">      : <a href="/web-doxygen/docs/api/classes/doccompoundnode/#ae01ca6994447efab51eb155728e4f3f6">DocCompoundNode</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,nullptr), <a href="#adbf9ad3d0105c6d110954381037a4100">m_indent</a>(<a href="#a65e7fbdda6784c769c6333adc1fe629c">indent</a>), <a href="#a67e39cfe41312efdf577e2f65d6b5d38">m_singleLine</a>(sl) {}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doccompoundnode/#ae01ca6994447efab51eb155728e4f3f6">DocCompoundNode::DocCompoundNode</a>, <a href="#a65e7fbdda6784c769c6333adc1fe629c">indent</a>, <a href="#adbf9ad3d0105c6d110954381037a4100">m_indent</a>, <a href="#a67e39cfe41312efdf577e2f65d6b5d38">m_singleLine</a> and <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### indent() {#a65e7fbdda6784c769c6333adc1fe629c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocRoot::indent ()</td>
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



<p>Definition at line 1318 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a65e7fbdda6784c769c6333adc1fe629c">1318</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a65e7fbdda6784c769c6333adc1fe629c">indent</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#adbf9ad3d0105c6d110954381037a4100">m_indent</a>; }</span></span></div>

</div>


<p>Reference <a href="#adbf9ad3d0105c6d110954381037a4100">m_indent</a>.</p>


<p>Referenced by <a href="#a895591f00a7f0c35ddc283bee7e395f8">DocRoot</a> and <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a07acb7803948c3811f88d4efa00587a4">RTFDocVisitor::operator()</a>.</p>

</div>
</div>

### isEmpty() {#ade1a2bc91120fb42b66313298b37199d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocRoot::isEmpty ()</td>
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



<p>Definition at line 1320 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ade1a2bc91120fb42b66313298b37199d">1320</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ade1a2bc91120fb42b66313298b37199d">isEmpty</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/classes/growvector/#a4e81684f665c9a1a38b5e16cfbe31d41">empty</a>(); }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a> and <a href="/web-doxygen/docs/api/classes/growvector/#a4e81684f665c9a1a38b5e16cfbe31d41">GrowVector&lt; T &gt;::empty</a>.</p>

</div>
</div>

### parse() {#a860207dd6bee34648ddbfd55e3ddaff8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocRoot::parse ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1317 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line 6239 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a860207dd6bee34648ddbfd55e3ddaff8">6239</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a860207dd6bee34648ddbfd55e3ddaff8">DocRoot::parse</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6240</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6241</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6242</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> ns = <a href="/web-doxygen/docs/api/classes/autonodestack">AutoNodeStack</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6243</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#ae3c97a1c50f2345ed8a821b064752e4c">setStatePara</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6244</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/token">Token</a> retval = Token::make_TK_NONE();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6245</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6246</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// first parse any number of paragraphs</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6247</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isFirst=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6248</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docpara">DocPara</a> *lastPar = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6249</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">do</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6250</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6251</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6252</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docpara">DocPara</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6253</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docpara">DocPara</a> *par  = <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#ae3a5d9b77d64e18e642163cceac5fa2e">get_last</a>&lt;<a href="/web-doxygen/docs/api/classes/docpara">DocPara</a>&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6254</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isFirst) { par-&gt;markFirst(); isFirst=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6255</span><span class="doxyLineContent"><span class="doxyHighlight">      retval=par-&gt;parse();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6256</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (par-&gt;isEmpty() &amp;&amp; par-&gt;attribs().empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6257</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6258</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/classes/growvector/#a47b0fff0a3347fd5134ff7f121511d5f">pop_back</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6259</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6260</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6261</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6262</span><span class="doxyLineContent"><span class="doxyHighlight">        lastPar = par;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6263</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6264</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6265</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> checkParagraph = [</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,&amp;retval](<a href="/web-doxygen/docs/api/classes/token">Token</a> t,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *sectionType,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *parentSectionType) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6266</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (retval == t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6267</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6268</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/classes/anchorgenerator/#a282543ddcf48b1b7cf7d2921573d453d">AnchorGenerator::instance</a>().isGenerated(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;sectionId.str()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6269</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6270</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.fileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6271</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6272</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightStringLiteral">"found {} command (id: '{}') outside of {} context!"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6273</span><span class="doxyLineContent"><span class="doxyHighlight">              sectionType,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;sectionId,parentSectionType);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6274</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6275</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (retval==t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6276</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6277</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;sectionId.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6278</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6279</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> *sec=<a href="/web-doxygen/docs/api/classes/sectionmanager/#afcf31c2b2bad467541c924342b08773d">SectionManager::instance</a>().<a href="/web-doxygen/docs/api/classes/linkedmap/#ad7659775b7de962b4fe0921456baf4f4">find</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;sectionId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6280</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sec)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6281</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6282</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsection">DocSection</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6283</span><span class="doxyLineContent"><span class="doxyHighlight">                  level,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6284</span><span class="doxyLineContent"><span class="doxyHighlight">                  <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">token</a>-&gt;<a href="/web-doxygen/docs/api/structs/tokeninfo/#a60510e59ef059f69c4c3c44547cdf68d">sectionId</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6285</span><span class="doxyLineContent"><span class="doxyHighlight">              retval = <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#ae3a5d9b77d64e18e642163cceac5fa2e">get_last</a>&lt;<a href="/web-doxygen/docs/api/classes/docsection">DocSection</a>&gt;()-&gt;<a href="#a860207dd6bee34648ddbfd55e3ddaff8">parse</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6286</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6287</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6288</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6289</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.fileName,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span><span class="doxyHighlightStringLiteral">"Invalid {} id '{}'; ignoring {}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6290</span><span class="doxyLineContent"><span class="doxyHighlight">                  sectionType,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;sectionId,sectionType);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6291</span><span class="doxyLineContent"><span class="doxyHighlight">              retval = Token::make_TK_NONE();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6292</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6293</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6294</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6295</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6296</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.fileName,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span><span class="doxyHighlightStringLiteral">"Missing id for {}; ignoring {}"</span><span class="doxyHighlight">,sectionType,sectionType);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6297</span><span class="doxyLineContent"><span class="doxyHighlight">            retval = Token::make_TK_NONE();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6298</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6299</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6300</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6301</span><span class="doxyLineContent"><span class="doxyHighlight">    };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6302</span><span class="doxyLineContent"><span class="doxyHighlight">    checkParagraph(Token::make_RetVal_SubSubParagraph(), 6, </span><span class="doxyHighlightStringLiteral">"subsubparagraph"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"subparagraph"</span><span class="doxyHighlight">  );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6303</span><span class="doxyLineContent"><span class="doxyHighlight">    checkParagraph(Token::make_RetVal_SubParagraph(),    5, </span><span class="doxyHighlightStringLiteral">"subparagraph"</span><span class="doxyHighlight">,    </span><span class="doxyHighlightStringLiteral">"paragraph"</span><span class="doxyHighlight">     );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6304</span><span class="doxyLineContent"><span class="doxyHighlight">    checkParagraph(Token::make_RetVal_Paragraph(),       4, </span><span class="doxyHighlightStringLiteral">"paragraph"</span><span class="doxyHighlight">,       </span><span class="doxyHighlightStringLiteral">"subsubsection"</span><span class="doxyHighlight"> );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6305</span><span class="doxyLineContent"><span class="doxyHighlight">    checkParagraph(Token::make_RetVal_Subsubsection(),   3, </span><span class="doxyHighlightStringLiteral">"subsubsection"</span><span class="doxyHighlight">,   </span><span class="doxyHighlightStringLiteral">"subsection"</span><span class="doxyHighlight">    );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6306</span><span class="doxyLineContent"><span class="doxyHighlight">    checkParagraph(Token::make_RetVal_Subsection(),      2, </span><span class="doxyHighlightStringLiteral">"subsection"</span><span class="doxyHighlight">,      </span><span class="doxyHighlightStringLiteral">"section"</span><span class="doxyHighlight">       );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6307</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6308</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (retval.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_LISTITEM))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6309</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6310</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.fileName,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span><span class="doxyHighlightStringLiteral">"Invalid list item found"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6311</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6312</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (retval.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::RetVal_Internal))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6313</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6314</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docinternal">DocInternal</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6315</span><span class="doxyLineContent"><span class="doxyHighlight">      retval = <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#ae3a5d9b77d64e18e642163cceac5fa2e">get_last</a>&lt;<a href="/web-doxygen/docs/api/classes/docinternal">DocInternal</a>&gt;()-&gt;<a href="#a860207dd6bee34648ddbfd55e3ddaff8">parse</a>(1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6316</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6317</span><span class="doxyLineContent"><span class="doxyHighlight">  } </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!retval.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_NONE,TokenRetval::TK_EOF,TokenRetval::RetVal_Section));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6318</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lastPar) lastPar-&gt;<a href="/web-doxygen/docs/api/classes/docpara/#a569bc5841973bac45491c977814f62e0">markLast</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6319</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6320</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("DocRoot::parse() retval=%d %d\n",retval,TokenRetval::RetVal_Section);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6321</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// then parse any number of level1 sections</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6322</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (retval.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::RetVal_Section))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6323</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6324</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;sectionId.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6325</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6326</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> *sec=<a href="/web-doxygen/docs/api/classes/sectionmanager/#afcf31c2b2bad467541c924342b08773d">SectionManager::instance</a>().<a href="/web-doxygen/docs/api/classes/linkedmap/#ad7659775b7de962b4fe0921456baf4f4">find</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;sectionId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6327</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sec)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6328</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6329</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsection">DocSection</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6330</span><span class="doxyLineContent"><span class="doxyHighlight">                                1,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6331</span><span class="doxyLineContent"><span class="doxyHighlight">                                <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">token</a>-&gt;<a href="/web-doxygen/docs/api/structs/tokeninfo/#a60510e59ef059f69c4c3c44547cdf68d">sectionId</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6332</span><span class="doxyLineContent"><span class="doxyHighlight">        retval = <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#ae3a5d9b77d64e18e642163cceac5fa2e">get_last</a>&lt;<a href="/web-doxygen/docs/api/classes/docsection">DocSection</a>&gt;()-&gt;<a href="#a860207dd6bee34648ddbfd55e3ddaff8">parse</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6333</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6334</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6335</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6336</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.fileName,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span><span class="doxyHighlightStringLiteral">"Invalid section id '{}'; ignoring section"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;sectionId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6337</span><span class="doxyLineContent"><span class="doxyHighlight">        retval = Token::make_TK_NONE();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6338</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6339</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6340</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6341</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6342</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.fileName,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span><span class="doxyHighlightStringLiteral">"Missing id for section; ignoring section"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6343</span><span class="doxyLineContent"><span class="doxyHighlight">      retval = Token::make_TK_NONE();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6344</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6345</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6346</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6347</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#af097a0f67abbe29e09a9956e88eb7642">handleUnclosedStyleCommands</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6348</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">DocNodeList::append</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">DocParser::context</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/linkedmap/#ad7659775b7de962b4fe0921456baf4f4">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>, <a href="/web-doxygen/docs/api/structs/docnodelist/#ae3a5d9b77d64e18e642163cceac5fa2e">DocNodeList::get_last</a>, <a href="/web-doxygen/docs/api/classes/docparser/#af097a0f67abbe29e09a9956e88eb7642">DocParser::handleUnclosedStyleCommands</a>, <a href="/web-doxygen/docs/api/classes/anchorgenerator/#a282543ddcf48b1b7cf7d2921573d453d">AnchorGenerator::instance</a>, <a href="/web-doxygen/docs/api/classes/sectionmanager/#afcf31c2b2bad467541c924342b08773d">SectionManager::instance</a>, <a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">Token::is</a>, <a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">Token::is_any_of</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a569bc5841973bac45491c977814f62e0">DocPara::markLast</a>, <a href="#a860207dd6bee34648ddbfd55e3ddaff8">parse</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>, <a href="/web-doxygen/docs/api/classes/growvector/#a47b0fff0a3347fd5134ff7f121511d5f">GrowVector&lt; T &gt;::pop_back</a>, <a href="/web-doxygen/docs/api/structs/tokeninfo/#a60510e59ef059f69c4c3c44547cdf68d">TokenInfo::sectionId</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#ae3c97a1c50f2345ed8a821b064752e4c">DocTokenizer::setStatePara</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">DocNode::thisVariant</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">DocParserContext::token</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">DocParser::tokenizer</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>.</p>


<p>Referenced by <a href="#a860207dd6bee34648ddbfd55e3ddaff8">parse</a>.</p>

</div>
</div>

### singleLine() {#a32e7c733315cae51633409dfaaf6020f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocRoot::singleLine ()</td>
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



<p>Definition at line 1319 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a32e7c733315cae51633409dfaaf6020f">1319</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a32e7c733315cae51633409dfaaf6020f">singleLine</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a67e39cfe41312efdf577e2f65d6b5d38">m_singleLine</a>; }</span></span></div>

</div>


<p>Reference <a href="#a67e39cfe41312efdf577e2f65d6b5d38">m_singleLine</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a07acb7803948c3811f88d4efa00587a4">RTFDocVisitor::operator()</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_indent {#adbf9ad3d0105c6d110954381037a4100}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocRoot::m_indent = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1323 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adbf9ad3d0105c6d110954381037a4100">1323</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#adbf9ad3d0105c6d110954381037a4100">m_indent</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a895591f00a7f0c35ddc283bee7e395f8">DocRoot</a> and <a href="#a65e7fbdda6784c769c6333adc1fe629c">indent</a>.</p>

</div>
</div>

### m\_singleLine {#a67e39cfe41312efdf577e2f65d6b5d38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocRoot::m_singleLine = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1324 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a67e39cfe41312efdf577e2f65d6b5d38">1324</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a67e39cfe41312efdf577e2f65d6b5d38">m_singleLine</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a895591f00a7f0c35ddc283bee7e395f8">DocRoot</a> and <a href="#a32e7c733315cae51633409dfaaf6020f">singleLine</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
