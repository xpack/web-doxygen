---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/docsimplelistitem
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `DocSimpleListItem` Class Reference

Node representing a simple list item. <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
class DocSimpleListItem { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6744173871fecc4fd16f6e0a320724d">DocSimpleListItem</a> (DocParser *parser, DocNodeVariant *parent)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/token">Token</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82b621ab52e4940d34704be3841cc36e">parse</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cf88bdd86a58c836a938a20e13cf5c8">paragraph</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ca7914afeaa134e6ed91a7291a895fb">m_paragraph</a></td>
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

Node representing a simple list item.

Definition at line 1152 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxySectionDef">

## Public Constructors

### DocSimpleListItem() {#af6744173871fecc4fd16f6e0a320724d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocSimpleListItem::DocSimpleListItem (<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> * parser, <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 1155 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line 2841 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af6744173871fecc4fd16f6e0a320724d">2841</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#af6744173871fecc4fd16f6e0a320724d">DocSimpleListItem::DocSimpleListItem</a>(<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2842</span><span class="doxyLineContent"><span class="doxyHighlight">      : <a href="/web-doxygen/docs/api/classes/docnode/#a12e0244788c1b56cb307517cb8d9d96f">DocNode</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2843</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2844</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/docnode/#a12e0244788c1b56cb307517cb8d9d96f">DocNode::DocNode</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a> and <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### paragraph() {#a5cf88bdd86a58c836a938a20e13cf5c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DocNodeVariant * DocSimpleListItem::paragraph ()</td>
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



Definition at line 1157 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5cf88bdd86a58c836a938a20e13cf5c8">1157</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="#a5cf88bdd86a58c836a938a20e13cf5c8">paragraph</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a5ca7914afeaa134e6ed91a7291a895fb">m_paragraph</a>.get(); }</span></span></div>

</div>


Reference <a href="#a5ca7914afeaa134e6ed91a7291a895fb">m\_paragraph</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a5d1246ae30e71d074a6fb40c745494cc">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a27c23c74dc6525645a9f0f4fad4705a0">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a09c4ad96f7c5f045fbd0547b623f27bf">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#aad902c41e3df81277b2bf6f1e95f466d">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#a531bed2a476f2aea9ebaf37810ad9d17">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#af3cf02029125082792d5718aba631a43">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#add264d5a56e09e76ec274af99af747d2">RTFDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a69fc08e18c0395ca5855cbb69d9cde19">XmlDocVisitor::operator()</a>.
</div>
</div>

### parse() {#a82b621ab52e4940d34704be3841cc36e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Token DocSimpleListItem::parse ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 1156 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line 2847 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a82b621ab52e4940d34704be3841cc36e">2847</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/token">Token</a> <a href="#a82b621ab52e4940d34704be3841cc36e">DocSimpleListItem::parse</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2848</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2849</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> ns = <a href="/web-doxygen/docs/api/classes/autonodestack">AutoNodeStack</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2850</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5ca7914afeaa134e6ed91a7291a895fb">m_paragraph</a> = <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa42674aaf44286a4dbbf89f4da21609a">createDocNode&lt;DocPara&gt;</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2851</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docpara">DocPara</a> *par = &amp;std::get&lt;DocPara&gt;(*<a href="#a5ca7914afeaa134e6ed91a7291a895fb">m_paragraph</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2852</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/token">Token</a> rv=par-&gt;<a href="/web-doxygen/docs/api/classes/docpara/#aafc94d2ed7856e4a11e404e2ee05fb40">parse</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2853</span><span class="doxyLineContent"><span class="doxyHighlight">  par-&gt;<a href="/web-doxygen/docs/api/classes/docpara/#a849868e81af1e2ae0da511fa3e5a91b8">markFirst</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2854</span><span class="doxyLineContent"><span class="doxyHighlight">  par-&gt;<a href="/web-doxygen/docs/api/classes/docpara/#a569bc5841973bac45491c977814f62e0">markLast</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2855</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> rv;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2856</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa42674aaf44286a4dbbf89f4da21609a">createDocNode</a>, <a href="#a5ca7914afeaa134e6ed91a7291a895fb">m\_paragraph</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a849868e81af1e2ae0da511fa3e5a91b8">DocPara::markFirst</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a569bc5841973bac45491c977814f62e0">DocPara::markLast</a>, <a href="/web-doxygen/docs/api/classes/docpara/#aafc94d2ed7856e4a11e404e2ee05fb40">DocPara::parse</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a> and <a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">DocNode::thisVariant</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_paragraph {#a5ca7914afeaa134e6ed91a7291a895fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DocNodeVariant&gt; DocSimpleListItem::m_paragraph</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 1160 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5ca7914afeaa134e6ed91a7291a895fb">1160</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;DocNodeVariant&gt; <a href="#a5ca7914afeaa134e6ed91a7291a895fb">m_paragraph</a>;</span></span></div>

</div>


Referenced by <a href="#a5cf88bdd86a58c836a938a20e13cf5c8">paragraph</a> and <a href="#a82b621ab52e4940d34704be3841cc36e">parse</a>.
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
