---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/docemoji
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DocEmoji` Class Reference

<p>Node representing an emoji. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class DocEmoji { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/docnode-h">src/docnode.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docnode">DocNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract node interface with type information. <a href="/web-doxygen/docs/api/classes/docnode/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f8d09770b5024c02b1777e2b8801962">DocEmoji</a> (DocParser *parser, DocNodeVariant *parent, const QCString &amp;symName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c754f3d5f362c43008fe6bf6d11147a">name</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07de0cec2007bc102188a656a354b8b9">index</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada1a7ba04c15d5ea9692c9f033047e48">m_symName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a311b8fcf87a4864e6ef29609f8bcc649">m_index</a> = 0</td>
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

<p>Node representing an emoji.</p>

<p>Definition at line 340 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DocEmoji() {#a0f8d09770b5024c02b1777e2b8801962}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocEmoji::DocEmoji (<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> * parser, <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; symName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 343 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line 160 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0f8d09770b5024c02b1777e2b8801962">160</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a0f8d09770b5024c02b1777e2b8801962">DocEmoji::DocEmoji</a>(<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;symName) :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docnode/#a12e0244788c1b56cb307517cb8d9d96f">DocNode</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>), <a href="#ada1a7ba04c15d5ea9692c9f033047e48">m_symName</a>(symName), <a href="#a311b8fcf87a4864e6ef29609f8bcc649">m_index</a>(-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> locSymName = symName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len=locSymName.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (len&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (locSymName.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(len-1)!=</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight">) locSymName.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">append</a>(</span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (locSymName.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(0)!=</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight">)     locSymName.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(</span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ada1a7ba04c15d5ea9692c9f033047e48">m_symName</a> = locSymName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a311b8fcf87a4864e6ef29609f8bcc649">m_index</a> = <a href="/web-doxygen/docs/api/classes/emojientitymapper/#a6b4ebc91738fb8f8af7459346a86f49b">EmojiEntityMapper::instance</a>().<a href="/web-doxygen/docs/api/classes/emojientitymapper/#a8f20a25544d61a753eaf73d2618c9c88">symbol2index</a>(<a href="#ada1a7ba04c15d5ea9692c9f033047e48">m_symName</a>.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a311b8fcf87a4864e6ef29609f8bcc649">m_index</a>==-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>-&gt;context.fileName,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>-&gt;tokenizer.getLineNr(),</span><span class="doxyHighlightStringLiteral">"Found unsupported emoji symbol '{}'"</span><span class="doxyHighlight">,<a href="#ada1a7ba04c15d5ea9692c9f033047e48">m_symName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">QCString::append</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a12e0244788c1b56cb307517cb8d9d96f">DocNode::DocNode</a>, <a href="/web-doxygen/docs/api/classes/emojientitymapper/#a6b4ebc91738fb8f8af7459346a86f49b">EmojiEntityMapper::instance</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#a311b8fcf87a4864e6ef29609f8bcc649">m_index</a>, <a href="#ada1a7ba04c15d5ea9692c9f033047e48">m_symName</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">QCString::prepend</a>, <a href="/web-doxygen/docs/api/classes/emojientitymapper/#a8f20a25544d61a753eaf73d2618c9c88">EmojiEntityMapper::symbol2index</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### index() {#a07de0cec2007bc102188a656a354b8b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DocEmoji::index ()</td>
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



<p>Definition at line 345 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a07de0cec2007bc102188a656a354b8b9">345</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a07de0cec2007bc102188a656a354b8b9">index</a>()</span><span class="doxyHighlightKeyword"> const          </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a311b8fcf87a4864e6ef29609f8bcc649">m_index</a>; }</span></span></div>

</div>


<p>Reference <a href="#a311b8fcf87a4864e6ef29609f8bcc649">m_index</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a0eca51c43b643d592b22070d062a3b77">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#aa066a9ae73449ff8017a1e94565fae2e">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a60686dad3b83395d42770683c5e1e6a9">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#ae151cc7686cf768f2e7e91002bac8dcc">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#a69768613d52a739ff1824beee29e9c52">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a8b0c3df81502ad08c0887a26b78061c2">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#adc374c79a2895d83e349ffc76358209e">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/textdocvisitor/#a23c1a244d091ae31fcd8ff2d66747054">TextDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#ac090b55ba575d25794fb3cdce0e02967">XmlDocVisitor::operator()</a>.</p>

</div>
</div>

### name() {#a5c754f3d5f362c43008fe6bf6d11147a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocEmoji::name ()</td>
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



<p>Definition at line 344 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5c754f3d5f362c43008fe6bf6d11147a">344</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a5c754f3d5f362c43008fe6bf6d11147a">name</a>()</span><span class="doxyHighlightKeyword"> const      </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ada1a7ba04c15d5ea9692c9f033047e48">m_symName</a>; }</span></span></div>

</div>


<p>Reference <a href="#ada1a7ba04c15d5ea9692c9f033047e48">m_symName</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a0eca51c43b643d592b22070d062a3b77">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#aa066a9ae73449ff8017a1e94565fae2e">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a60686dad3b83395d42770683c5e1e6a9">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#ae151cc7686cf768f2e7e91002bac8dcc">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#a69768613d52a739ff1824beee29e9c52">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a8b0c3df81502ad08c0887a26b78061c2">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#adc374c79a2895d83e349ffc76358209e">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/textdocvisitor/#a23c1a244d091ae31fcd8ff2d66747054">TextDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#ac090b55ba575d25794fb3cdce0e02967">XmlDocVisitor::operator()</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_index {#a311b8fcf87a4864e6ef29609f8bcc649}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DocEmoji::m_index = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 349 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a311b8fcf87a4864e6ef29609f8bcc649">349</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a311b8fcf87a4864e6ef29609f8bcc649">m_index</a> = 0;</span></span></div>

</div>


<p>Referenced by <a href="#a0f8d09770b5024c02b1777e2b8801962">DocEmoji</a> and <a href="#a07de0cec2007bc102188a656a354b8b9">index</a>.</p>

</div>
</div>

### m\_symName {#ada1a7ba04c15d5ea9692c9f033047e48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocEmoji::m_symName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 348 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ada1a7ba04c15d5ea9692c9f033047e48">348</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ada1a7ba04c15d5ea9692c9f033047e48">m_symName</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a0f8d09770b5024c02b1777e2b8801962">DocEmoji</a> and <a href="#a5c754f3d5f362c43008fe6bf6d11147a">name</a>.</p>

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
