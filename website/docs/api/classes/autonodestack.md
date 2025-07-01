---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/autonodestack
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `AutoNodeStack` Class Reference



## Declaration

<div class="doxyDeclaration">
class AutoNodeStack { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/docparser-p-h">src/docparser_p.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84baa3d44d0f437d4a80a0d3d6fc06df">AutoNodeStack</a> (DocParser *parser, DocNodeVariant *node)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a9a492c39c16b054ab81d12ea3e73ac">~AutoNodeStack</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36908098e146343a72a946a270f5980a">m_parser</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a452992566701eb2e0fcb67ca0e38e890">m_node</a></td>
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


Definition at line 147 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.

<div class="doxySectionDef">

## Public Constructors

### AutoNodeStack() {#a84baa3d44d0f437d4a80a0d3d6fc06df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AutoNodeStack::AutoNodeStack (<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> * parser, <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * node)</td>
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



Definition at line 150 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a84baa3d44d0f437d4a80a0d3d6fc06df">150</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a84baa3d44d0f437d4a80a0d3d6fc06df">AutoNodeStack</a>(<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> *parser,<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a>* node)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">      : <a href="#a36908098e146343a72a946a270f5980a">m_parser</a>(parser), <a href="#a452992566701eb2e0fcb67ca0e38e890">m_node</a>(node) { <a href="#a36908098e146343a72a946a270f5980a">m_parser</a>-&gt;context.nodeStack.push(node); }</span></span></div>

</div>


References <a href="#a452992566701eb2e0fcb67ca0e38e890">m\_node</a> and <a href="#a36908098e146343a72a946a270f5980a">m\_parser</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~AutoNodeStack() {#a7a9a492c39c16b054ab81d12ea3e73ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AutoNodeStack::~AutoNodeStack ()</td>
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



Definition at line 152 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7a9a492c39c16b054ab81d12ea3e73ac">152</a></span><span class="doxyLineContent"><span class="doxyHighlight">   <a href="#a7a9a492c39c16b054ab81d12ea3e73ac">~AutoNodeStack</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#if defined(NDEBUG)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">      (void)<a href="#a452992566701eb2e0fcb67ca0e38e890">m_node</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a36908098e146343a72a946a270f5980a">m_parser</a>-&gt;context.nodeStack.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a36908098e146343a72a946a270f5980a">m_parser</a>-&gt;context.nodeStack.pop(); </span><span class="doxyHighlightComment">// robust version that does not assert</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">      assert(<a href="#a36908098e146343a72a946a270f5980a">m_parser</a>-&gt;context.nodeStack.top()==<a href="#a452992566701eb2e0fcb67ca0e38e890">m_node</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a36908098e146343a72a946a270f5980a">m_parser</a>-&gt;context.nodeStack.pop(); </span><span class="doxyHighlightComment">// error checking version</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a452992566701eb2e0fcb67ca0e38e890">m\_node</a> and <a href="#a36908098e146343a72a946a270f5980a">m\_parser</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_node {#a452992566701eb2e0fcb67ca0e38e890}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DocNodeVariant* AutoNodeStack::m_node</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 169 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a452992566701eb2e0fcb67ca0e38e890">169</a></span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="#a452992566701eb2e0fcb67ca0e38e890">m_node</a>;</span></span></div>

</div>


Referenced by <a href="#a84baa3d44d0f437d4a80a0d3d6fc06df">AutoNodeStack</a> and <a href="#a7a9a492c39c16b054ab81d12ea3e73ac">\~AutoNodeStack</a>.
</div>
</div>

### m\_parser {#a36908098e146343a72a946a270f5980a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocParser* AutoNodeStack::m_parser</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 168 of file <a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a36908098e146343a72a946a270f5980a">168</a></span><span class="doxyLineContent"><span class="doxyHighlight">   <a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> *<a href="#a36908098e146343a72a946a270f5980a">m_parser</a>;</span></span></div>

</div>


Referenced by <a href="#a84baa3d44d0f437d4a80a0d3d6fc06df">AutoNodeStack</a> and <a href="#a7a9a492c39c16b054ab81d12ea3e73ac">\~AutoNodeStack</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/docparser-p-h">docparser_p.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
