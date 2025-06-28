---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/doctext
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `DocText` Class Reference

<p>Root node of a text fragment. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class DocText { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d642b7d96dbed8c87c04a93f2bab31c">DocText</a> (DocParser *parser)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aada5a740aa0832964895e683340b76a5">parse</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeed56e5d1701811126f1bd221412ef2">isEmpty</a> () const</td>
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

<p>Root node of a text fragment.</p>

<p>Definition at line 1303 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxySectionDef">

## Public Constructors

### DocText() {#a2d642b7d96dbed8c87c04a93f2bab31c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocText::DocText (<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> * parser)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l01306">1306</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2d642b7d96dbed8c87c04a93f2bab31c">1306</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a2d642b7d96dbed8c87c04a93f2bab31c">DocText</a>(<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>) : <a href="/web-doxygen/docs/api/classes/doccompoundnode/#ae01ca6994447efab51eb155728e4f3f6">DocCompoundNode</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,nullptr) {}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/doccompoundnode/#ae01ca6994447efab51eb155728e4f3f6">DocCompoundNode::DocCompoundNode</a> and <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isEmpty() {#adeed56e5d1701811126f1bd221412ef2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocText::isEmpty ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l01308">1308</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adeed56e5d1701811126f1bd221412ef2">1308</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#adeed56e5d1701811126f1bd221412ef2">isEmpty</a>()</span><span class="doxyHighlightKeyword"> const    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/classes/growvector/#a4e81684f665c9a1a38b5e16cfbe31d41">empty</a>(); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a> and <a href="/web-doxygen/docs/api/classes/growvector/#a4e81684f665c9a1a38b5e16cfbe31d41">GrowVector&lt; T &gt;::empty</a>.
</div>
</div>

### parse() {#aada5a740aa0832964895e683340b76a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocText::parse ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l01307">1307</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#l06125">6125</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aada5a740aa0832964895e683340b76a5">6125</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aada5a740aa0832964895e683340b76a5">DocText::parse</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6126</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6127</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6128</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> ns = <a href="/web-doxygen/docs/api/classes/autonodestack">AutoNodeStack</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6129</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#aace7e3d8edd67ef73441256379557aea">setStateText</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6130</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6131</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/token">Token</a> tok = <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#a286239d4401fbbfb8b183a7e9c521866">lex</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6132</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_NONE, TokenRetval::TK_EOF)) </span><span class="doxyHighlightComment">// get the next token</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6133</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6134</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(tok.<a href="/web-doxygen/docs/api/classes/token/#ab0587c46b8e1a8e18f8416b3aad58342">value</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6135</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6136</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> TokenRetval::TK_WORD:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6137</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docword">DocWord</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">token</a>-&gt;<a href="/web-doxygen/docs/api/structs/tokeninfo/#ad01df4cf228c63091fd14007b7331b8e">name</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6138</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6139</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> TokenRetval::TK_WHITESPACE:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6140</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docwhitespace">DocWhiteSpace</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">token</a>-&gt;<a href="/web-doxygen/docs/api/structs/tokeninfo/#a7dc1ad1cf0a4e237d7be47b02092d6eb">chars</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6141</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6142</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> TokenRetval::TK_SYMBOL:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6143</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6144</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7df">HtmlEntityMapper::SymType</a> s = <a href="/web-doxygen/docs/api/classes/docsymbol/#ad2d60acd5c92da5e2bc0dab925e5c2fa">DocSymbol::decodeSymbol</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6145</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s!=<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa4afd8f33f5ff42a444da284278109d9f">HtmlEntityMapper::Sym_Unknown</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6146</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6147</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6148</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6149</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6150</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6151</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.fileName,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span><span class="doxyHighlightStringLiteral">"Unsupported symbol '{}' found"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6152</span><span class="doxyLineContent"><span class="doxyHighlight">                <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6153</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6154</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6155</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6156</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> TokenRetval::TK_COMMAND_AT:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6157</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// fall through</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6158</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> TokenRetval::TK_COMMAND_BS:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6159</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/namespaces/mappers/#aca1c1147352a87e1d896e0c4cf70b8c9">Mappers::cmdMapper</a>-&gt;map(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;name))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6160</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6161</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352ab41541930cbc3eb72b54d4c6da3c0ae8">CommandType::CMD_BSLASH</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6162</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfaea255b976fa03c5130fa92fd22ec6e3b">HtmlEntityMapper::Sym_BSlash</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6163</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6164</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a231334a819076be4d21ffbf9eb3d5fac">CommandType::CMD_AT</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6165</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa7cc15e3151231a2120a68b108d2807a5">HtmlEntityMapper::Sym_At</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6166</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6167</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352aa76513f8aaef2b7d02c9993b3920fcec">CommandType::CMD_LESS</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6168</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa1a8b38abfbed7b9cb11b7228b43c4cd0">HtmlEntityMapper::Sym_Less</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6169</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6170</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a6454f09b46f73d0d141a041314c0b95c">CommandType::CMD_GREATER</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6171</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa735e88daf2b0be93495e85e89e06de44">HtmlEntityMapper::Sym_Greater</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6172</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6173</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a6f9f21c0cb1ce6e48a2aac0475e7065d">CommandType::CMD_AMP</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6174</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfae7bb3cd758b8df439d9bcbe7ac787f4d">HtmlEntityMapper::Sym_Amp</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6175</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6176</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a036b0b8401bf33b8e70ea757f86bead6">CommandType::CMD_DOLLAR</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6177</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa648856a842f6bdcd5b8486a79d306e0f">HtmlEntityMapper::Sym_Dollar</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6178</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6179</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a602d16174562d50f3cf2f8eda1c6ebb6">CommandType::CMD_HASH</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6180</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfaaafb21b517e5aea3ffe901907c8f3355">HtmlEntityMapper::Sym_Hash</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6181</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6182</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a82d29f1aaf679ee418491b7e4f5ea07d">CommandType::CMD_DCOLON</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6183</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa8efb751ac50c34d457c8fc827ef55eb9">HtmlEntityMapper::Sym_DoubleColon</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6184</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6185</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a71a82fcfdc616129c03fe458496b4906">CommandType::CMD_PERCENT</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6186</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa8da48ef159e7932e8ed84473fbb067a5">HtmlEntityMapper::Sym_Percent</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6187</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6188</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352ac8a3932bd8a0d7bc9ce2a5deb488aba0">CommandType::CMD_NDASH</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6189</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfaf8a3a429e59ffa27cad6c8ee0c528975">HtmlEntityMapper::Sym_Minus</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6190</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfaf8a3a429e59ffa27cad6c8ee0c528975">HtmlEntityMapper::Sym_Minus</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6191</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6192</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a8fcff20c756832f83f46d634de1bcb04">CommandType::CMD_MDASH</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6193</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfaf8a3a429e59ffa27cad6c8ee0c528975">HtmlEntityMapper::Sym_Minus</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6194</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfaf8a3a429e59ffa27cad6c8ee0c528975">HtmlEntityMapper::Sym_Minus</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6195</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfaf8a3a429e59ffa27cad6c8ee0c528975">HtmlEntityMapper::Sym_Minus</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6196</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6197</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352ab632762af37578d45ecfb0cdaa5ff232">CommandType::CMD_QUOTE</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6198</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfacc4e69acbf92aa382154f7e1451eeb10">HtmlEntityMapper::Sym_Quot</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6199</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6200</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a327f68a61235c8922c3b4228bc2420c9">CommandType::CMD_PUNT</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6201</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa175b5cee6a647c949fb0cf94074ff0d4">HtmlEntityMapper::Sym_Dot</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6202</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6203</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a46b91211a7a50b7d83c96ac514028f2a">CommandType::CMD_EXCLAMATION</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6204</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfac8eb924022c2cca673aa35e558bc27f4">HtmlEntityMapper::Sym_Exclam</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6205</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6206</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a9098d932d7292ccdcdbfc7fbfab6035e">CommandType::CMD_QUESTION</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6207</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfacb93f1ef109f35c95ef77aa399c99ec1">HtmlEntityMapper::Sym_Quest</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6208</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6209</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a798425a98992c1b0eaada7bd20e4bf57">CommandType::CMD_PLUS</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6210</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfae04596de435bc484c107b0133d881e42">HtmlEntityMapper::Sym_Plus</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6211</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6212</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352aedbb38e82179db12cec6adb259f83ee4">CommandType::CMD_MINUS</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6213</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfaf8a3a429e59ffa27cad6c8ee0c528975">HtmlEntityMapper::Sym_Minus</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6214</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6215</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a3a9c7d82f8086ab2b77df8add8d10f7e">CommandType::CMD_EQUAL</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6216</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfae41d37f6c5803503a6a12ab12885c6b8">HtmlEntityMapper::Sym_Equal</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6217</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6218</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6219</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.fileName,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span><span class="doxyHighlightStringLiteral">"Unexpected command '{}' found"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6220</span><span class="doxyLineContent"><span class="doxyHighlight">                           <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6221</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6222</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6223</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6224</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6225</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.fileName,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span><span class="doxyHighlightStringLiteral">"Unexpected token {}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6226</span><span class="doxyLineContent"><span class="doxyHighlight">            tok.<a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">to_string</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6227</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6228</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6229</span><span class="doxyLineContent"><span class="doxyHighlight">    tok = <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#a286239d4401fbbfb8b183a7e9c521866">lex</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6230</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6231</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6232</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#af097a0f67abbe29e09a9956e88eb7642">handleUnclosedStyleCommands</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6233</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">6234</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">DocNodeList::append</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO&#95;TRACE</a>, <a href="/web-doxygen/docs/api/structs/tokeninfo/#a7dc1ad1cf0a4e237d7be47b02092d6eb">TokenInfo::chars</a>, <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a6f9f21c0cb1ce6e48a2aac0475e7065d">CMD&#95;AMP</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a231334a819076be4d21ffbf9eb3d5fac">CMD&#95;AT</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352ab41541930cbc3eb72b54d4c6da3c0ae8">CMD&#95;BSLASH</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a82d29f1aaf679ee418491b7e4f5ea07d">CMD&#95;DCOLON</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a036b0b8401bf33b8e70ea757f86bead6">CMD&#95;DOLLAR</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a3a9c7d82f8086ab2b77df8add8d10f7e">CMD&#95;EQUAL</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a46b91211a7a50b7d83c96ac514028f2a">CMD&#95;EXCLAMATION</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a6454f09b46f73d0d141a041314c0b95c">CMD&#95;GREATER</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a602d16174562d50f3cf2f8eda1c6ebb6">CMD&#95;HASH</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352aa76513f8aaef2b7d02c9993b3920fcec">CMD&#95;LESS</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a8fcff20c756832f83f46d634de1bcb04">CMD&#95;MDASH</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352aedbb38e82179db12cec6adb259f83ee4">CMD&#95;MINUS</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352ac8a3932bd8a0d7bc9ce2a5deb488aba0">CMD&#95;NDASH</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a71a82fcfdc616129c03fe458496b4906">CMD&#95;PERCENT</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a798425a98992c1b0eaada7bd20e4bf57">CMD&#95;PLUS</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a327f68a61235c8922c3b4228bc2420c9">CMD&#95;PUNT</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a9098d932d7292ccdcdbfc7fbfab6035e">CMD&#95;QUESTION</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352ab632762af37578d45ecfb0cdaa5ff232">CMD&#95;QUOTE</a>, <a href="/web-doxygen/docs/api/namespaces/mappers/#aca1c1147352a87e1d896e0c4cf70b8c9">Mappers::cmdMapper</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">DocParser::context</a>, <a href="/web-doxygen/docs/api/classes/docsymbol/#ad2d60acd5c92da5e2bc0dab925e5c2fa">DocSymbol::decodeSymbol</a>, <a href="/web-doxygen/docs/api/classes/docparser/#af097a0f67abbe29e09a9956e88eb7642">DocParser::handleUnclosedStyleCommands</a>, <a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">Token::is&#95;any&#95;of</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#a286239d4401fbbfb8b183a7e9c521866">DocTokenizer::lex</a>, <a href="/web-doxygen/docs/api/structs/tokeninfo/#ad01df4cf228c63091fd14007b7331b8e">TokenInfo::name</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#aace7e3d8edd67ef73441256379557aea">DocTokenizer::setStateText</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfae7bb3cd758b8df439d9bcbe7ac787f4d">HtmlEntityMapper::Sym&#95;Amp</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa7cc15e3151231a2120a68b108d2807a5">HtmlEntityMapper::Sym&#95;At</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfaea255b976fa03c5130fa92fd22ec6e3b">HtmlEntityMapper::Sym&#95;BSlash</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa648856a842f6bdcd5b8486a79d306e0f">HtmlEntityMapper::Sym&#95;Dollar</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa175b5cee6a647c949fb0cf94074ff0d4">HtmlEntityMapper::Sym&#95;Dot</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa8efb751ac50c34d457c8fc827ef55eb9">HtmlEntityMapper::Sym&#95;DoubleColon</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfae41d37f6c5803503a6a12ab12885c6b8">HtmlEntityMapper::Sym&#95;Equal</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfac8eb924022c2cca673aa35e558bc27f4">HtmlEntityMapper::Sym&#95;Exclam</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa735e88daf2b0be93495e85e89e06de44">HtmlEntityMapper::Sym&#95;Greater</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfaaafb21b517e5aea3ffe901907c8f3355">HtmlEntityMapper::Sym&#95;Hash</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa1a8b38abfbed7b9cb11b7228b43c4cd0">HtmlEntityMapper::Sym&#95;Less</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfaf8a3a429e59ffa27cad6c8ee0c528975">HtmlEntityMapper::Sym&#95;Minus</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa8da48ef159e7932e8ed84473fbb067a5">HtmlEntityMapper::Sym&#95;Percent</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfae04596de435bc484c107b0133d881e42">HtmlEntityMapper::Sym&#95;Plus</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfacb93f1ef109f35c95ef77aa399c99ec1">HtmlEntityMapper::Sym&#95;Quest</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfacc4e69acbf92aa382154f7e1451eeb10">HtmlEntityMapper::Sym&#95;Quot</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa4afd8f33f5ff42a444da284278109d9f">HtmlEntityMapper::Sym&#95;Unknown</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">DocNode::thisVariant</a>, <a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">Token::to&#95;string</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">DocParserContext::token</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">DocParser::tokenizer</a>, <a href="/web-doxygen/docs/api/classes/token/#ab0587c46b8e1a8e18f8416b3aad58342">Token::value</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn&#95;doc&#95;error</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following files:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
