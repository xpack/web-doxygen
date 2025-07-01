---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/docword
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `DocWord` Class Reference

Node representing a word. <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
class DocWord { ... }
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
Abstract node interface with type information. <a href="/web-doxygen/docs/api/classes/docnode/#details">More...</a>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a265a3d55d519502ceb631433816b7d95">DocWord</a> (DocParser *parser, DocNodeVariant *parent, const QCString &amp;word)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9ecbc2daa4fb051a07c510ab0a7d461">word</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e5d0e1117e15c98fb841341a7d4309f">m_word</a></td>
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

Node representing a word.

Definition at line 152 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxySectionDef">

## Public Constructors

### DocWord() {#a265a3d55d519502ceb631433816b7d95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocWord::DocWord (<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> * parser, <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; word)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 155 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line 180 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a265a3d55d519502ceb631433816b7d95">180</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a265a3d55d519502ceb631433816b7d95">DocWord::DocWord</a>(<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#af9ecbc2daa4fb051a07c510ab0a7d461">word</a>) :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docnode/#a12e0244788c1b56cb307517cb8d9d96f">DocNode</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>), <a href="#a7e5d0e1117e15c98fb841341a7d4309f">m_word</a>(<a href="#af9ecbc2daa4fb051a07c510ab0a7d461">word</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("new word %s url=%s\n",qPrint(word),qPrint(parser-&gt;context.searchUrl));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/doxygen/#ae3d8cc749e66634e3902def93f814d07">Doxygen::searchIndex</a>.enabled() &amp;&amp; !<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>-&gt;context.searchUrl.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">    Doxygen::searchIndex.addWord(word,false);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/docnode/#a12e0244788c1b56cb307517cb8d9d96f">DocNode::DocNode</a>, <a href="#a7e5d0e1117e15c98fb841341a7d4309f">m\_word</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#ae3d8cc749e66634e3902def93f814d07">Doxygen::searchIndex</a> and <a href="#af9ecbc2daa4fb051a07c510ab0a7d461">word</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### word() {#af9ecbc2daa4fb051a07c510ab0a7d461}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocWord::word ()</td>
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



Definition at line 156 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af9ecbc2daa4fb051a07c510ab0a7d461">156</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#af9ecbc2daa4fb051a07c510ab0a7d461">word</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a7e5d0e1117e15c98fb841341a7d4309f">m_word</a>; }</span></span></div>

</div>


Reference <a href="#a7e5d0e1117e15c98fb841341a7d4309f">m\_word</a>.

Referenced by <a href="#a265a3d55d519502ceb631433816b7d95">DocWord</a>, <a href="/web-doxygen/docs/api/files/src/docnode-h/#ae06df9ac205468d82301870dbe23905c">dumpDocNodeList</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a58ea0b2d5d886e6c4347d450032c4481">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#adf7a140e70ce68021f8b0acf881e96af">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#ad03a5e89722d1ae6d7372e3db2027b13">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a1189a4bc09f26b09b5809fb5382b0a0c">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/textdocvisitor/#ad932c305668398f6c0b4aace1f3f8483">TextDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_word {#a7e5d0e1117e15c98fb841341a7d4309f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocWord::m_word</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 159 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7e5d0e1117e15c98fb841341a7d4309f">159</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>  <a href="#a7e5d0e1117e15c98fb841341a7d4309f">m_word</a>;</span></span></div>

</div>


Referenced by <a href="#a265a3d55d519502ceb631433816b7d95">DocWord</a> and <a href="#af9ecbc2daa4fb051a07c510ab0a7d461">word</a>.
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
