---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/doctitle
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DocTitle` Class Reference

<p>Node representing a simple section title. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class DocTitle { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5aaaddf559a8eba47e0e39b3225ff36">DocTitle</a> (DocParser *parser, DocNodeVariant *parent)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12306a4f4de4310c8201fac9d29eb627">parse</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a410946c3855fd51f18485d6e3dcce59b">parseFromString</a> (DocNodeVariant *, const QCString &amp;title)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae27763e0e3579fbd9d2d67e7fbebda47">hasTitle</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12f16328e5894a517eb3eca100ffeedd">isEmpty</a> () const</td>
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

<p>Node representing a simple section title.</p>

<p>Definition at line 607 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DocTitle() {#ab5aaaddf559a8eba47e0e39b3225ff36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocTitle::DocTitle (<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> * parser, <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent)</td>
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



<p>Definition at line 610 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab5aaaddf559a8eba47e0e39b3225ff36">610</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ab5aaaddf559a8eba47e0e39b3225ff36">DocTitle</a>(<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>) : <a href="/web-doxygen/docs/api/classes/doccompoundnode/#ae01ca6994447efab51eb155728e4f3f6">DocCompoundNode</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>) {}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doccompoundnode/#ae01ca6994447efab51eb155728e4f3f6">DocCompoundNode::DocCompoundNode</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a> and <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### hasTitle() {#ae27763e0e3579fbd9d2d67e7fbebda47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocTitle::hasTitle ()</td>
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



<p>Definition at line 613 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae27763e0e3579fbd9d2d67e7fbebda47">613</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae27763e0e3579fbd9d2d67e7fbebda47">hasTitle</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> !<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/classes/growvector/#a4e81684f665c9a1a38b5e16cfbe31d41">empty</a>(); }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a> and <a href="/web-doxygen/docs/api/classes/growvector/#a4e81684f665c9a1a38b5e16cfbe31d41">GrowVector&lt; T &gt;::empty</a>.</p>


<p>Referenced by <a href="#a12f16328e5894a517eb3eca100ffeedd">isEmpty</a> and <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#ad654cd7e66da83fdf2ff02f9bdcf34fd">DocbookDocVisitor::operator()</a>.</p>

</div>
</div>

### isEmpty() {#a12f16328e5894a517eb3eca100ffeedd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocTitle::isEmpty ()</td>
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



<p>Definition at line 614 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a12f16328e5894a517eb3eca100ffeedd">614</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a12f16328e5894a517eb3eca100ffeedd">isEmpty</a>()</span><span class="doxyHighlightKeyword"> const  </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> !<a href="#ae27763e0e3579fbd9d2d67e7fbebda47">hasTitle</a>(); }</span></span></div>

</div>


<p>Reference <a href="#ae27763e0e3579fbd9d2d67e7fbebda47">hasTitle</a>.</p>

</div>
</div>

### parse() {#a12306a4f4de4310c8201fac9d29eb627}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTitle::parse ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 611 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line 2968 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a12306a4f4de4310c8201fac9d29eb627">2968</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a12306a4f4de4310c8201fac9d29eb627">DocTitle::parse</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2969</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2970</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2971</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> ns = <a href="/web-doxygen/docs/api/classes/autonodestack">AutoNodeStack</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2972</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#a7b9c9df4ada21e5fb5c5a7d5eac0fbd2">setStateTitle</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2973</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/token">Token</a> tok = <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#a286239d4401fbbfb8b183a7e9c521866">lex</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2974</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_NONE, TokenRetval::TK_EOF))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2975</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2976</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;defaultHandleToken(<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),tok,<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2977</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2978</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#afa9541b35f25f2f63a6f5ff338967f22">errorHandleDefaultToken</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),tok,<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>(),</span><span class="doxyHighlightStringLiteral">"title section"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2979</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2980</span><span class="doxyLineContent"><span class="doxyHighlight">    tok = <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#a286239d4401fbbfb8b183a7e9c521866">lex</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2981</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2982</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#ae3c97a1c50f2345ed8a821b064752e4c">setStatePara</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2983</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a94f06b2f61c71069d46589a7cd4f7b6b">handlePendingStyleCommands</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2984</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a>, <a href="/web-doxygen/docs/api/classes/docparser/#afa9541b35f25f2f63a6f5ff338967f22">DocParser::errorHandleDefaultToken</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a94f06b2f61c71069d46589a7cd4f7b6b">DocParser::handlePendingStyleCommands</a>, <a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">Token::is_any_of</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#a286239d4401fbbfb8b183a7e9c521866">DocTokenizer::lex</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#ae3c97a1c50f2345ed8a821b064752e4c">DocTokenizer::setStatePara</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#a7b9c9df4ada21e5fb5c5a7d5eac0fbd2">DocTokenizer::setStateTitle</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">DocNode::thisVariant</a> and <a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">DocParser::tokenizer</a>.</p>

</div>
</div>

### parseFromString() {#a410946c3855fd51f18485d6e3dcce59b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTitle::parseFromString (<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 612 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line 2986 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a410946c3855fd51f18485d6e3dcce59b">2986</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a410946c3855fd51f18485d6e3dcce59b">DocTitle::parseFromString</a>(<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2987</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2988</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a88cb2bde6d7f9ded45c9d33f33b65bb3">insideHtmlLink</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2989</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#af278dab51b58124b32a625d709a29d97">pushContext</a>(); </span><span class="doxyHighlightComment">// this will create a new parser-&gt;context.token</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2990</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a6d276e7995db319294ea1fb2bc76459e">internalValidatingParseDoc</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>(),text);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2991</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#aa05ab8dc59dfa50633146bdba08db5f0">popContext</a>(); </span><span class="doxyHighlightComment">// this will restore the old parser-&gt;context.token</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2992</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a88cb2bde6d7f9ded45c9d33f33b65bb3">insideHtmlLink</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2993</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#ae3c97a1c50f2345ed8a821b064752e4c">setStatePara</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2994</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a71dd66dcbef8ad6aa74feb1e87e2a06b">flattenParagraphs</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2995</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">DocParser::context</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a71dd66dcbef8ad6aa74feb1e87e2a06b">flattenParagraphs</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a88cb2bde6d7f9ded45c9d33f33b65bb3">DocParserContext::insideHtmlLink</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a6d276e7995db319294ea1fb2bc76459e">DocParser::internalValidatingParseDoc</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>, <a href="/web-doxygen/docs/api/classes/docparser/#aa05ab8dc59dfa50633146bdba08db5f0">DocParser::popContext</a>, <a href="/web-doxygen/docs/api/classes/docparser/#af278dab51b58124b32a625d709a29d97">DocParser::pushContext</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#ae3c97a1c50f2345ed8a821b064752e4c">DocTokenizer::setStatePara</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">DocNode::thisVariant</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">DocParser::tokenizer</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

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
